# useFetch
Makes with fetch depending on the url sent a request to an api

Example:
... 
    const url = "www.api.com";
    const { loading:true, data:true, error:null } = useFetch(url);
...

ii returns three parameters loading, the data, and the error if something ocurrs

# useFetch
Makes with fetch depending on the url sent a request to an api

Example:
... 
    const {loading,data}=useFetch(`https://www.breakingbadapi.com/api/quotes/${counter}`);
...

ii returns three parameters loading, the data, and the error if something ocurrs

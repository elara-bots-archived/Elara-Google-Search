#Example Usage


```js
let Google = require('elara-google-search'), 
    google = new Google("API KEY", "CX ID");

    let res = await google.search("elara-google-search npm");
    if(res.status){
        // Success
        console.log(res); // "res.links" to return all of the links found for that search!
    }else{
        // Failed
        console.log(res);
    }
```
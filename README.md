# shylnk
JavaScript library for shylnk.com
# main
```js
async function main(){
    const {shylnk} = require('./shylnk');
    const lnk= new shylnk();
    let req=await lnk.short_url("url")
    console.log(req)
}
main()
```

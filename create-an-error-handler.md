# build an error handler
- make a folder in the modules folder called whatever you want
- add a file called `index.js`
- add the following code:

```javascript
module.exports = function(host,res,req,errornumber,errordesc,version,ejs){
 
}
```

- in the blank space add your own [http module](https://nodejs.dev/learn/the-nodejs-http-module) code, you can also get the host, get the error code, error description, get the version, and use ejs.
- import the module by adding the folder name to modules.json by adding `local://foldername` to moduleList and adding `"yoursite"` to errorHandler
- run wgytcraft
- it should work!
- need help?
- ask the community [here](https://github.com/wgytcraft/help/discussions)

# modules.json
These are the things you can put in modules.json  
***MAKE SURE TO PUT THESE IN AN OBJECT{}***
## version
### Type
String/Number
### Purpose
Version your modules.json file
### Example
```
  "version":"0.1-alpha",
```
## moduleList
### Type
Array
### Purpose
List the modules you are using.
NPM modules should be put as `npm://` followed by the name of the NPM package
Github modules should be put as `gh://` followed by the name of the Github repo
Gitlab modules should be put as `gl://` followed by the name of the Gitlab repo
Bitbucket modules should be put as `bb://` followed by the name of the Bitbucket repo
Local modules should be put as `local://` followed by the name of the folder
### Example
```
	"moduleList":[ 
		"gh://wgytcraft/errors",
		"gh://wgytcraft/hello-world-template"
	],
```
## errorHandler
### Type
String
### Purpose
List your error handler here, it must be from moduleList without the :// prefix
### Example
```
  "errorHandler":"wgytcraft/errors",
```
## website
### Type
Array
### Purpose
List the websites you are serving.
### Example
```
  "website":["test.wgyt.tk"],
```
## websiteData
### Type
Object
### Purpose
List the module that powers each site
### Example
```
	"websiteData":{
		"test.wgyt.tk":"wgytcraft/hello-world-template"
	}
```

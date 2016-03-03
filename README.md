# JtAngular2
AngularJS 2 tutorial with VS 2015

## What is this?
Just a tutorial web application to do a self learning on AngularJS 2 with Visual Studio 2015 ASP.NET 5

## Pre-requisites
This would be where you would look if the solution does not work or complain something went wrong.  


### References
* *AngularJS 2 Tutorial*  
https://angular.io/docs/ts/latest/tutorial/toh-pt5.html  
* *Visual Studio ASP.NET 5 with AngularJS 2*  
http://www.mithunvp.com/angular-2-in-asp-net-5-typescript-visual-studio-2015/


### Something to note

FIXED ~~For some reason, post install doesn't work well with 'typings install' when typings.json is not at root folder.
This could only happen to windows 10 for windows 7 adding post install seems to work.~~ 
```javascript
~~"postinstall": "cd script && typings install" ~~
```
~~Typings sometimes might fail to install even though defined in devDependencies, in this case, the workaround would be installing it globally.~~

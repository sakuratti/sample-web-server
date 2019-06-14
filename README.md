# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
fonnoMacBook-Pro:sample-web-server ratti$ mkdir mywebapi
fonnoMacBook-Pro:sample-web-server ratti$ cd mywebapi/
fonnoMacBook-Pro:mywebapi ratti$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi) 
version: (1.0.0) 
description: 
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: 
license: (ISC) 
About to write to /Users/ratti/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}


Is this OK? (yes) yes
fonnoMacBook-Pro:mywebapi ratti$ npm install --save express
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ express@4.17.1
added 50 packages from 37 contributors and audited 126 packages in 2.703s
found 0 vulnerabilities

fonnoMacBook-Pro:mywebapi ratti$ touch index.js
fonnoMacBook-Pro:mywebapi ratti$ cd ..
fonnoMacBook-Pro:sample-web-server ratti$ code .
fonnoMacBook-Pro:sample-web-server ratti$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/Users/ratti/Documents/fujiwara/sample-web-server/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
fonnoMacBook-Pro:sample-web-server ratti$ cd mywebapi/
fonnoMacBook-Pro:mywebapi ratti$ node index.js 
Listening on port 3000
^C
fonnoMacBook-Pro:mywebapi ratti$ node index.js 
Listening on port 3000
^C
fonnoMacBook-Pro:mywebapi ratti$ cd..
-bash: cd..: command not found
fonnoMacBook-Pro:mywebapi ratti$ cd ..
fonnoMacBook-Pro:sample-web-server ratti$ touch web
fonnoMacBook-Pro:sample-web-server ratti$ cd web 
-bash: cd: web: Not a directory
fonnoMacBook-Pro:sample-web-server ratti$ rm web 
fonnoMacBook-Pro:sample-web-server ratti$ mkdir web
fonnoMacBook-Pro:sample-web-server ratti$ cd web/
fonnoMacBook-Pro:web ratti$ touch index.html
fonnoMacBook-Pro:web ratti$ cd ..
fonnoMacBook-Pro:sample-web-server ratti$ cd mywebapi/
fonnoMacBook-Pro:mywebapi ratti$ node index.js 
Listening on port 3000
^C
fonnoMacBook-Pro:mywebapi ratti$ 
```

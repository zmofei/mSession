mSession
============

A easy way to control session in nodejs

Install
=======

`npm install msession

Example
=======

```javascript

//require the session.js
var session = require('session.js');

//start the session.
//you must get the req,and res.
var sessionM = session.start(req, res);

//set Session
//.set(key,val,expTime);
sessionM.set('power','admin',1000*60*60*24)

//get Session
sessionM.get('power');
//return 'admin' 

```

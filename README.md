# Getting your discord token
1. Login to the discord account that you want to get the token of (Desktop or Chrome)
2. Press `ctrl+shift+i` (windows and linux) or `cmd+shift+i` (macos)
3. Click into the console tab of the chrome dev tools window
4. Enter the following text in the console:
  ```
  var req=webpackJsonp.push([[],{extra_id:(e,r,t)=>e.exports=t},[["extra_id"]]]);for(let e in req.c)if(req.c.hasOwnProperty(e)){let     r=req.c[e].exports;if(r&&r.__esModule&&r.default)for(let e in r.default)"getToken"===e&&console.log(r.default.getToken())}
  ```
5. Press enter
6. Copy the text that got printed out. That is your token. Remember, never give this token to strangers, as they can gain full access to your bot if they gain access to this token!

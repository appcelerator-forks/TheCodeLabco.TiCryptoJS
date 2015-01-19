# TiCryptoJS
CryptoJS with Appcelerator Titanium

https://code.google.com/p/crypto-js/


Steps:
- Add all javascript files you need into example.js file
- Move it to app/lib/example.js
- Add exports.CryptoJS = CryptoJS; at the end of file exaple.js

Example: use TripleDES with Cipher mode is ECB with Paddind AnsiX923, you need to copy code from each file in this sort
http://crypto-js.googlecode.com/svn/tags/3.1.2/build/rollups/tripledes.js
http://crypto-js.googlecode.com/svn/tags/3.1.2/build/components/mode-ecb-min.js
http://crypto-js.googlecode.com/svn/tags/3.1.2/build/components/pad-ansix923-min.js

then add at the end of this file
exports.CryptoJS = CryptoJS;

Ref: 
- https://wiki.appcelerator.org/display/guides2/CommonJS+Modules+in+Titanium
- http://stackoverflow.com/questions/15357375/using-cryptojs-library-in-a-titanium-mobile-project-to-decrypt-a-text-message
- http://stackoverflow.com/questions/20247953/tripledes-implementation-in-javascript-different-comparing-with-c-sharp
# google-login

Log in with google sample, adapted from [this](https://www.loginradius.com/blog/engineering/google-authentication-with-nodejs-and-passportjs/) article.

Note to use this with a proxy server, you need to modify outh2.json

* install the https-proxy-agent npm dependency
* require it like HttpsProxyAgent = require('https-proxy-agent').HttpsProxyAgent;
* Test for https_proxy environment variable and if it exists, create a new instance of HttpsProxyAgeent with the proxy url and set this._agent to the instance
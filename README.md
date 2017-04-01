curl-to-Py
===========

curl-to-Py is a tool to instantly convert [curl](http://curl.haxx.se) commands to Python code in the browser. It does *not* guarantee high-fidelity conversions, but it's good enough for most API docs that have curl samples.

### Try it

**[Check it out!](https://zhexuany.github.io/curl-to-py)** It works inside your browser.


### FAQ

#### Does any curl command work?

Any curl command should work, but only certain flags are understood and converted into Go code. The rest of the flags will be ignored.

#### Which kinds of curl commands are understood?

Mostly simple HTTP commands (headers, basic auth, body, etc).

#### Will you consider supporting *this-or-that* flag?
Yes, if you convice that falg is very important. Or you can do it yourself.



### Credits

curl-to-Py is inspired by [curl-to-Go](https://twitter.com/mholt6).

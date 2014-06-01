[![Build
Status](https://travis-ci.org/garethr/zapr.svg)](https://travis-ci.org/garethr/zapr)

An example of using [Zapr](https://github.com/garethr/zapr) to test a
vulnerable web application, in this case
[Railsgoat](https://github.com/OWASP/railsgoat) from OWASP.

The example uses [Travis](https://travis-ci.org/garethr/zapr-example)
to:

* Install [OWASP
  ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)
* Install and run Railsgoat
* Run Zapr against the running web application

For your own usage you would likely replace Railsgoat with your own web
application under test.

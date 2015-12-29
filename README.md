# DotTK

Automatically renews .tk domains for 12 months.

Use with care! This is a script I created a few years ago and the .tk API and license may have changed in the meantime.


## Quick Start

#### Installation
Download `dottk` and make it executable with:
~~~ bash
	$  chmod u+x dottk
~~~

#### Renewing domains
Run the scriipt:
~~~ bash
	$  dottk EMAIL PASSWORD DOMAIN [DOMAIN ...]
~~~

Do not include the tld in the `DOMAIN`-- e.g. use "mydomain" and not "mydomain.tk"'.

`EMAIL` and `PASSWORD` are the credentials used to regsiter with dottk.

The dottk API used to only allow renewals near the expiration date. I used a cron script to attenpt to renew repeatedly near the expiration date.


## License

MIT license. See the LICENSE file for details. 


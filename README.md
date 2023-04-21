# Available Public Wildcard DNS Domains pointing to localhost (127.0.0.1)

> DISCLAIMER: I have no responsibility for any domains listed here, or in the comments, and if any of them capture any data transmitted by the HTTP request. At any time, any of the domains listed in this article may stop working (except localhost).

It turns out that some kind hearted people already set up wildcard domains for you already. You can use any domain below and/or any subdomain of these and they currently resolve to 127.0.0.1 but could switch at any time to resolve somewhere else.  Here's the list of ones I know about. Let me know if there are more!

> NOTE: You can (and should) check if [any domain resolve to 127.0.0.1](https://dnschecker.org/#A/fbi.com).

* `localhost` - It will always works. [Do you know why?](https://gprivate.com/61ndb) <--- Now there's no sorry.
* `[*.]fbi.com` - :clap: :clap: :clap: :clap: :clap: 
* `[*.]localtest.me`
* `[*.]127-0-0-1.org.uk`
* `[*.]yoogle.com`
* `[*.]lacolhost.com`
* `[*.]local.sisteminha.com`
* `[*.]cefgo.com`
* `domaincontrol.com`
* See below comments for more domains

Of course, you can [setup your own local domain](https://linuxize.com/post/how-to-edit-your-hosts-file/).

## Need to use SSL?

* Read [Renatofrota's comment](https://gist.github.com/tinogomes/c425aa2a56d289f16a1f4fcb8a65ea65?permalink_comment_id=4131702#gistcomment-4131702) below.

sources: 
* ~ht<span>tp://www.</span>fidian.com/programming/public-dns-pointing-to-localhost~ (Page not found. Read [Fidian's comment](https://gist.github.com/tinogomes/c425aa2a56d289f16a1f4fcb8a65ea65?permalink_comment_id=4214973#gistcomment-4214973) to understand why)
* http://blog.reenhanced.com/post/29566591244/developing-with-subdomains-just-got-a-lot-easier
* https://stackoverflow.com/questions/1562954/public-wildcard-domain-name-to-resolve-to-127-0-0-1
* https://markinns.com/archive/how-to-setup-a-local-dns-host-file-on-mac-os-x.html

Red Lounge
===========

These files are my minor changes to an open-source Hugo theme designed by [@shift8creative](http://www.twitter.com/shift8creative).
This is actively published [here](http://chass.is).
[Original README](ORIG.md)

Some changes:

* Markdown images are responsively scaled by default
* Personalized CSS
* Personalized footer.html (copyright)
* Personalized meta.html (favicons)
* Personalized sidebarheader.html (added image into sidebar, if landing page)

TODO:

* Localize pure, html5shiv, font-awesome, jquery, highlight off of CDNs.  Why:
  * Cloudflare is forcing captcha on Tor (et al.) users.
  * Cut down on third parties tracking my visitors.
  * Minimize risk of file changes upstream.
* Add some useful stuff like charts, and improved embeds of github, youtube, etc.
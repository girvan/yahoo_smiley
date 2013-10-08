Yahoo Smiley
=========

Yahoo! and wretch blog are going to shutdown at end of 2013.

BSPs(Blog Service Provider) support picture/album migration except smiley/emoticons.

Those icons might be broken after Yahoo! and wretch blog end of service.

Plan to push to cdnjs of cloudflare.

### Replacements
Please replace yahoo's url to hostinb base url:
* yahoo's url:
  * http://pic.wretch.cc/photos/icon/blog/smiley/msn/
  * http://tw.yimg.com/i/tw/blog/smiley/
  * http://l.yimg.com/f/i/tw/blog/smiley/
  * http://l.yimg.com/f/i/tw/wretch/yahootalent/
* hosting base url: ```https://raw.github.com/girvan/yahoo_smiley/master/imgs/```

Example:

original: ``` <img src="http://pic.wretch.cc/photos/icon/blog/smiley/msn/thumbs_up.gif" alt="" /> ```
replace to: ```<img src="https://raw.github.com/girvan/yahoo_smiley/master/imgs/thumbs_up.gif" alt="" />```

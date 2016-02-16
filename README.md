# wai-aria.css

CSS showing how page is visible for screen reader user as much as it is possible.


## Bookmarklet

You can use the latest version of this stylesheet by bookmarklet.

```
javascript:(function(){var dwa=document.createElement('link');dwa.href="https://rawgit.com/Harut/wai-aria.css/master/wai-aria.css";dwa.rel="stylesheet";dwa.media="all";document.head.appendChild(dwa);var btn=document.createElement('button');btn.textContent="ARIA ON/OFF";btn.className="toggle-special-debug";btn.onclick=function(){var cl=document.body.classList;cl[cl.contains('special-debug')?'remove':'add']('special-debug'); };document.body.appendChild(btn);btn.click()})();
```

## Project Page

[wai-aria.css](http://harut.github.io/wai-aria.css/)


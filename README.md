#lodashify v1.0.0

Want an easy way to poke at a page with [Lo-Dash [compat-dev v.1.0.0]](http://lodash.com/)?

Create a bookmark with this for the URL (sorry, embedding the bookmarklet didn't work):

    javascript:void%20function(){(function(){function%20e(){t.innerHTML=a,n.appendChild(t),window.setTimeout(function(){%22undefined%22==typeof%20_%3Fn.removeChild(t):(n.removeChild(t),o%26%26(lodash=_.noConflict()))},2500)}var%20t=document.createElement(%22div%22),n=document.getElementsByTagName(%22body%22)[0],o=!1,a=%22%22;return%20t.style.position=%22fixed%22,t.style.height=%2232px%22,t.style.width=%22220px%22,t.style.marginLeft=%22-110px%22,t.style.top=%220%22,t.style.left=%2250%25%22,t.style.padding=%225px%2010px%22,t.style.zIndex=1001,t.style.fontSize=%2212px%22,t.style.color=%22%23222%22,t.style.backgroundColor=%22%23f99%22,%22undefined%22!=typeof%20_%3F(a=%22This%20page%20already%20using%20Lo-Dash%20v%22+'3.9.3',e()):(%22function%22==typeof%20_%26%26(o=!0),void%20function(e,t){var%20n=document.createElement(%22script%22);n.src=e;var%20o=document.getElementsByTagName(%22head%22)[0],a=!1;n.onload=n.onreadystatechange=function(){a||this.readyState%26%26%22loaded%22!=this.readyState%26%26%22complete%22!=this.readyState||(a=!0,t(),n.onload=n.onreadystatechange=null,o.removeChild(n))},o.appendChild(n)}(%22//cdnjs.cloudflare.com/ajax/libs/lodash.js/3.9.3/lodash.min.js%22,function(){return%22undefined%22==typeof%20_%3Fa=%22Sorry,%20but%20Lo-Dash%20wasn't%20able%20to%20load%22:(a=%22This%20page%20is%20now%20Lo-Dashified%20with%20v%22+'3.9.3',o%26%26(a+=%22%20and%20noConflict().%20Use%20lodash(),%20not%20_().%22)),e()}))})()}();

##References

~~Stolen~~ Adapted from Karl Swedberg's [jQuerify bookmarklet](http://www.learningjquery.com/2009/04/better-stronger-safer-jquerify-bookmarklet/).

Final bookmarklet generated by running things through [Closure Compiler](http://closure-compiler.appspot.com/home) and [Bookmarkleter](http://chris.zarate.org/bookmarkleter).

##License

MIT license. If you do something cool with it, though, I'd love to hear about it.

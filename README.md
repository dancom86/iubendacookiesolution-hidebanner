# iubendacookiesolution-hidebanner
"Hide" banner on certain pages

This script doesn't show the banner on a specific page. 
Let's suppose you want to hide the banner on a cookie policy page, with this URL: www.test.com/cookie-policy/

The pathname is /cookie-policy/ and you should add it in the "if" clause:

if(window.location.pathname === "YOUR_PATHNAME_TO_EXCLUDE") { 



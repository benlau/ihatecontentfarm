# Content Farm Blocker
======================

你今天震驚了嗎？有否為大量誇張失實的標題文章湧進日常生活而感到厭感？

即使告訢朋友不要再轉載有關文章，結果還是不會消失，最後只能進行消極的抵抗 － 不點擊，不讓自己為對方的廣告收益帶來貢獻。

可是 －

有時候會點錯，當網頁打開後才察覺到自己又中了計。

這個擴充套件就是為解決以上問題而做出來的，每當用戶準備打開內容農場的文章時，就會出來攔截，以免點進內容農場。

功能

 1. 在打開內容農場時進行攔截
 
 2. 用戶可以選擇繼續，然後在10分鐘內不再對同一網址進行攔截
 
 3. 自定黑名單及白名單

下載:

[Content Farm Blocker - Chrome 線上應用程式商店](https://chrome.google.com/webstore/detail/opjaibbmmpldcncnbbglondckfnokfpm?hl=zh-TW)

舉報網址內容農場

https://docs.google.com/forms/d/15PiDGSjDMKorGFkoFKr76kW7NI02eD4IWL-O_OlM1GA/viewform

Build Instructions
=================

```
   gulp chrome
   gulp chrome:bundle
```
   

Unit Tests
----------

```
    gulp mocha:build
    mocha --require source-map-support/register build/tests/main.js
```

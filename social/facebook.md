# Facebook

## Disable like notifications in Facebook

* Install and open http://www.fbpurity.com/
* Click the CSS link and add the following CSS code:

```css
li[data-gt*=like] {display:none !important;}
```

## My current FB purity CSS settings

```css
.newsFeedComposerXXX #stream_pagelet, .fbChatSidebarm, #pagesNav, #groupsNav, #appsNav, #listsNav, #interestsNav, #developerNav, li[data-gt*=like] {display:none !important;}
```

---
layout: post
title: "Close Popup Window in Chrome Extension"
category: blog
tags: [chrome, popup-window]
---

### Chrome Fixed the security issues on version 36.0.1985.125

Chrome 36.0.1985.125 WEDNESDAY, JULY 16, 2014
[Release note](http://googlechromereleases.blogspot.com/2014/07/stable-channel-update.html)

As it said, the new version contains a number of fixes and improvements, including:

> Rich Notifications Improvements   
An Updated Incognito / Guest NTP design  
The addition of a Browser crash recovery bubble  
Chrome App Launcher for Linux  
Lots of under the hood changes for stability and performance  

It also said:
> This update includes 26 security fixes. Below, we highlight fixes that were either contributed by external researchers or particularly interesting. Please see the Chromium security page for more information. 

From my observation, this update fixed the issue on using `window.close()` to close the popup window. You will see this in the console when it fail, "Scripts may close only the windows that were opened by it."

So, in the previous Chrome released builds, the below code block may worked but not with this update.

```javascript
    window.open('', '_self', '');
    window.close();
```

For this update, you have to update your code accordingly to close the popup window. One of the solution is to grab the popup window id and use 

```javascript
    chrome.windows.remove(integer windowId, function callback)
```

method to remove it. Chrome extension windows API can be found at [chrome.windows](https://developer.chrome.com/extensions/windows). 

`chrome.windows.remove` is Chrome extension API, javascript program should be recognized by chrome extension. You can try by putting it inside background.js, in your chrome extension manifest.json you need to have:

```javascript
	"background": {
	  "scripts": ["background.js"],
	  ...
	},
```

In the past, a great discussion around this window close issue can be found at [stackoverflow](http://stackoverflow.com/questions/19761241/window-close-and-self-close-do-not-close-the-window-in-chrome).

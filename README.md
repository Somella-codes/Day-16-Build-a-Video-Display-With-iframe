# Day 16: Build a Video Display Using iframe 🖼️

### **The Goal Today**
Go from just knowing what an `iframe` is to actually building a working YouTube video player from scratch.

This was freeCodeCamp’s “Build a Video Display Using iframe” Workshop.

### **What is an iframe?**
Think of it like a "window" inside your webpage. 
It lets you load and display another webpage, video, or map without leaving your site.

**Examples of replaced elements the browser handles for you:** 
`img`, `video`, `audio`, `iframe`

### **Key Concepts I Learned**

| Concept | What it Means |
| --- | --- |
| **Replaced Elements** | HTML elements where the browser, not CSS, controls the content. Like `iframe` or `img`. |
| **iframe Syntax** | `<iframe src="..."></iframe>` creates an embedded window. |
| **YouTube Embed URL** | Must use `/embed/VIDEO_ID` instead of `/watch?v=VIDEO_ID` or it won't load. |
| **allow Attribute** | Tells the browser what features the iframe can use: fullscreen, autoplay, clipboard, etc. |
| **referrerpolicy** | A security attribute. `strict-origin-when-cross-origin` is best practice. |
| **allowfullscreen** | Lets the user click the fullscreen button on the video. |

### **The Final Code I Built**
This displays a YouTube video directly on the page:

# Day 16: Build a Video Display Using iframe 🖼️

**Workshop: 8/8 Steps Completed ✅** 

---

### **The Goal Today**
Go from just knowing what an `iframe` is → to actually building a working YouTube video player from scratch.

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
This displays a YouTube video directly on the page. 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Display Videos in an iframe</title>
  </head>
  <body>
    <h1>iframe Video Display</h1>
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/I0_951_MPE0"
      allow="accelerometer autoplay clipboard-write encrypted-media gyroscope web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen>
    </iframe>
  </body>
</html>

### **Live Demo 👇**
![Video Display Screenshot](./assets/day-15-screenshot.png)

### **Live Preview**
[👉 View the code](index.html)
Then download it and open in Spck Editor or any browser

---
title: "Notes"
type: page
date: 2022-11-27T17:00:00
comments: false
---
Hugo uses markdown. Since I'm no expert, this page will act as a reference for future posts. Perhaps you'll find it useful as well.

## Front Matter for Posts
```
---
title: "Now Blogging with Hugo"
date: 2022-11-27T17:00:00
categories: ["Tech"]
Tags: ["Hugo", "Blogging"]
draft: false
cover:
    image: "https://live.staticflickr.com/65535/52463468107_5e7245c3b5_o_d.jpg"
    caption: <a href="https://www.flickr.com/photos/noahbershatsky/52463468107/in/album-72177720304027597/">Profile pic hosted on Flickr.</a>
---
```

---
## Front Matter for Pages
```
title: "🤓 Nerdy Notes 🤓"
type: page
date: 2022-11-27T17:00:00
ShowToc: true
TocOpen: true
```
---

## Images with Captions and Flickr Linkbacks
```
[![](https://live.staticflickr.com/65535/52521231962_e3377f6d6f_k_d.jpg) Here's and example of how links will work going forward (link to album on Flickr).](https://www.flickr.com/photos/noahbershatsky/albums/72177720303975538)
```
This will create a result like this:
[![](https://live.staticflickr.com/65535/52521231962_e3377f6d6f_k_d.jpg) Here's and example of how links will work going forward (link to album on Flickr).](https://www.flickr.com/photos/noahbershatsky/albums/72177720303975538)

---
## YouTube Shortcodes
I can't post the code here as Hugo will just embed the video, so here's the link to Hugo's website with the shortcode for YouTube.

https://gohugo.io/content-management/shortcodes/#youtube

---
## Instagram
The shortcode on Hugo's website doesn't work any more. The best solution now is to copy the embed code from Instagram proper. However, you can center the Instagram embed by using the following code:

```
<center>
The embedded Instagram code
</center>
```
---

## Disabling Comments in Front Matter

```
comments: false
```

---

## Disabling Table of Contents in Front Matter
```
ShowToc: false
TocOpen: false
```
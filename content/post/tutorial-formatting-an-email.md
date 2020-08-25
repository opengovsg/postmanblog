---
title: "Tutorial: Formatting an Email
date: 2020-08-25
hero: "/images/hero-2.jpg"
excerpt: Learn to format your emails easily with this simple tutorial on html tags"
timeToRead = 5
authors:
  - Hugo Authors
---

Now that you have sent a plaintext to a colleague, you are wondering if you can format your emails nicely in Postman. The answer is yes!

Types of formatting supported by Postman

* Bold
* Italic
* Links/Embed a pdf file using go.gov.sg
* Underline
* Embed an image using go.gov.sg

In this tutorial, we will focus on the first five formattings that postman support. Embedding an image will be a separate tutorial. Don't be afraid of HTML tags! It is as simple as copying and pasting and changing the content of the tag.

## Let's start by learning the sentence structure of HTML tags

How HTML works is that you start with **<xyz>** and end with **</xyz>**. For every HTML tag, you must have a **start** and an **end** to complete the sentence.

### **Bold**

```html
<b>Postman</b>

Ex: Postman is the <b>greatest</b> product ever!
```

### **Underline**
```html
<u>Postman</u>

Ex: Please remember to bring your <u>appointment letter</u>.
```

### **Italic**
```html
<i>Postman</i>

Ex: Dear <i>Mary Tan</i>, Please remember to bring your passport for your application.
```
### **Hyperlink**
```html
<a href="https://postman.gov.sg">postman</a>

Let's break this down:

<a href="    ">          </a> is the syntax.

\**<a href="https://linkofyourwebsite.gov.sg">**the word that you want to make into a link </a>

Ex: For more information, please visit postman's<a href="https://postman.gov.sg">webite</a>.
```

## Bring it all together

> Dear citizen,
> 
> _Thank you_ for supporting charity drive 2020. Please visit our [Facebook group](https://facebook.com/yourgroupname%22) to see the pictures from the event.
> 
> For more info, please visit our [website](https://agency.gov.sg)
> 
> Sincerely,
> 
> Agency XYZ

--------
```html
Dear citizen,

<i>Thank you</i> for supporting charity drive 2020. Please visit our <a href="https://facebook.com/yourgroupname">Facebook group</a> to see the pictures from the event.
For more info, please visit our <a href="https://agency.gov.sg>website</a>.

Sincerely,

<b>Agency XYZ</b>
```

It might seem daunting to tackle HTML tags. What you could do is to write your email in a **Microsoft Notepad** without any formatting and figure out where you want to add in the formatting and copy/paste the HTML tags into your draft and replace the placeholder content with your own content.

Start your HTML journey small by incorporating the bold tag in an email campaign and slowly build your way up to a power user! 💪
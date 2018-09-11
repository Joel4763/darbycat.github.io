---
layout: post
title: "Web Design Introduction"
date: 2018-08-03 17:21:47 -0400
categories: tutorial
author: Mark
filename: 
---
HTML, CSS, and Javscript are the main languages of the Internet. These languages are easy enough to learn without any prior knowledge of coding, while still being extremely powerful tools.

First make a folder and call it whatever you want, "firstwebsite" for example. Then create a new file inside that folder called "index.html" make sure to spell exactly as it says. Open the file in a web browser, and you should see a blank screen. This is because there is nothing in the file yet. Open it up in your favorite text editor, Atom, Visual Studio Code, Sublime Text, or even notepad. When you open it, write this into it:

```html
<!DOCTYPE html>
<html>
	<body>
		
	</body>
</html>
```

Anything with "<" and ">" wrapped around it is called a <mark>tag</mark>. 

The `<!DOCTYPE html>` line says that it should run in HTML5, whereas if you just started it with the `<html>` only, it would be in HTML4, which is prior to 2008. The `<body>` tag is what goes around the main content.

If you go back to your web browser and reload the page, it will still be a blank screen. Why? because everything that is in it is just setup information. There is no content in it. If you want a website with content, then you would do a little something like this:

```html
<!DOCTYPE html>
<html>
	<body>
		Hello, World!
	</body>
</html>
```

If you now reload the page, you'll see an amazing "Hello, World!"

But what about *stylized* text? `<strong>BOLD</strong>` `<em>ITALIC</em>` `<mark>HIGHLIGHT</mark>`
<strong>BOLD</strong>
<em>ITALIC</em>
<mark>HIGHLIGHT</mark>

You can replace that with "Hello, World!" and put whatever you want in it! You can even stack them, for example `<strong><em>STRONG ITALIC</em></strong>`
<strong><em>STRONG ITALIC</em></strong>

Even with this fancy text, it doesn't look very good, which is where CSS/styling comes in, which we'll cover next time.

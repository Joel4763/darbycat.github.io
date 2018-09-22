---
layout: post
title: "Dodge Game!"
date: 2018-09-19 09:54:07 -0400
categories: tutorials
author: Josh
filename: 
---
This is the game we will be making next Monday, the 24th! Be there to make your own spin on this game! (Attached will be a zip file with the code, once we optimize it.)

<script>
  window.addEventListener("keydown", function(e) {
    if([32, 37, 38, 39, 40].indexOf(e.keyCode) > -1) {
        e.preventDefault();
    }
  }, false);
</script>

## Preview
Arrow keys to move.
Space to restart the game once you lose.
<iframe height="610" width="600" style="border:none;padding:0;" src="https://editor.p5js.org/embed/BkczZFCdQ"></iframe>
If the scrolling is annoying you, [go to the full page.](https://editor.p5js.org/full/BkczZFCdQ)

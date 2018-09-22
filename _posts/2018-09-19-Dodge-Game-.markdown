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
  var keys = {};
window.addEventListener("keydown",
    function(e){
        keys[e.keyCode] = true;
        switch(e.keyCode){
            case 37: case 39: case 38:  case 40: // Arrow keys
            case 32: e.preventDefault(); break; // Space
            default: break; // do not block other keys
        }
    },
false);
window.addEventListener('keyup',
    function(e){
        keys[e.keyCode] = false;
    },
false);
</script>

## Preview
Arrow keys to move.
Space to restart the game once you lose.
<iframe height="610" width="600" style="border:none;padding:0;" src="https://editor.p5js.org/embed/BkczZFCdQ"></iframe>
If the scrolling is annoying you, [go to the full page.](https://editor.p5js.org/full/BkczZFCdQ)

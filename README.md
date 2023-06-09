# coool
custom [Revolt](https://revolt.chat/) theme that wants to be like every other Discord theme 

mainly made due to being extremely bored and wanting to spice up the experience of a chat platform I use

should mostly comply with your color scheme and whatever image you throw at it, so go wild

> :warning: note that i'm *not* a css dev, or really any type of dev. i just look up the issues i have or how to do something then tape it together in a massive, ugly css file.

# apply
to use this theme, simply paste this into your custom css, such as:
```css
@import url("https://cdn.jsdelivr.net/gh/sneexy-boi/dumpster@main/coool/coool.css");

/* modify these variables to fit your likings */
:root {
   --primary-background: rgba(var(--primary-background-rgb), 0.70);
   --secondary-background: rgba(var(--secondary-background-rgb), 0.35);
   --message-box: rgba(var(--secondary-background-rgb), 0.70);
   --block: rgba(var(--primary-background-rgb), 0.70);
   --image-bg: url('https://i.imgur.com/7SbtKvw.png')
}
```
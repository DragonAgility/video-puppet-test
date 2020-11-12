---

title: Hacking Your Perspective
tags: Content, Slides
# tags specific to hackmd but will casue error on narakeet build

voice: Brian
voice-speed: fast
transition: crossfade
# global config tags specific to narakeet (causes no isses with hackmd)

---

![contain](01.jpg)
<!-- Media must be local to be compiled to narakeet -->
<!-- Images cant be referenced localy from github on hackmd so absolute urls must be used -->

> Shown but not spoken in video generation. Might require an image to work properly. Things startign with > will be shown as block quotes in hackmd.

Note:
All normal text will be read in narakeet. Any text prefixed with "Note:" will be hidden behind speaker notes in hackmd slide mode.

---

> Pure text test using only blockquote character.

Note:
More speaker notes.

---

```
Very important purely text slide test. Difference between this and using the < character is that one shows as block quote and word wraps in slide mode.
```

Note:
This should be a pure textual slide in video compilation.

---

![contain](03.jpg)

```md
# Heading 1
## Heading 2

* bullets are left-aligned
* bullet 2
  * sub-bullet
```

Note:
This should render as narkdown in slide mode and video compilation.

---

![contain](04.jpg)

```css
.container {
  align-items: center;
  display: flex;
}
```

Note:
This is a CSS render test. I hope it works in both slide mode and video generation.

---

![contain](06.jpg)

```=
Should render with line numbers in hackmd.
Does it work?
We shall see.
```

Note:
This is a line number test. Does it work?

---

![contain](09.gif)

```!
This should render with sofwrap in hackmd but it seems to not be working. Maybe the issue is happening because we are presetnign in slide mode.
```

Note:
This is an animated gif test and text softwrap test. The softwrap test doesnt seem to be working in slide mode and I think it may just be failing because its slide mode.

---

![contain](10.gif)

Note:
Pure gif test with only speaker notes and no overlay text.

---

<!-- ![](outro.mp4) -->

> Sweet stinger video file goes here

Note:
This is where an outro video file would be appended.

---

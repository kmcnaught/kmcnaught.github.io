---
layout: page
title: Eye Gaze Drag and Drop
permalink: /block-coding/eye-gaze-drag/
---

## How mouse dragging works with eye gaze

When you use a mouse, dragging is simple: click, hold, move, and release. With eye gaze, you can't "hold" a button - you just look at where you want to go. So we need different ways to drag things.

### Common approaches

**1. Dwell click and lock**

- Look at what you want to drag
- Keep looking until it "locks" (you'll see a timer or visual feedback)
- Move your eyes to where you want to drop it
- Dwell again to release

This is like turning one continuous action (click-and-hold) into two separate clicks: one to grab, one to drop. 

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 20px 0;">
    <iframe
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
        src="https://www.youtube.com/embed/VoVj7RXt8p4"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
    </iframe>
</div>
<p style="text-align: center;"><em>Example: Dwell click and lock dragging</em></p>

**2. Button-activated drag**

- Press a button (on your eye gaze device or switch) to start dragging
- Look at what you want to drag
- Move your eyes to where you want to drop it
- Press the button again to release

This gives you more control because you decide exactly when to grab and release.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 20px 0;">
    <iframe
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
        src="https://www.youtube.com/embed/VIDEO_ID_HERE"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
    </iframe>
</div>
<p style="text-align: center;"><em>Example: Button-activated dragging</em></p>

**3. Grid selection**

Instead of moving a cursor around, you choose positions using grid cells:
- Select the grid cell where the thing you want to move is
- Select the grid cell where you want to move it to
- No dragging needed at all!

This is what we're using for our block coding interfaces - it removes the need for precise cursor control.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 20px 0;">
    <iframe
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
        src="https://www.youtube.com/embed/VIDEO_ID_HERE"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
    </iframe>
</div>
<p style="text-align: center;"><em>Example: Grid-based block coding</em></p>

### Why dragging is hard with eye gaze

Your eyes naturally jump around - they're made for looking at things, not for precise pointing. When you try to drag with eye gaze:

- It's hard to look at exactly the same spot for a long time
- Moving smoothly in a straight line feels unnatural
- Small movements (like fine positioning) can be frustrating

That's why grid-based approaches work so well for coding - they let you think about where things should go, not about controlling a cursor.

---

## Embedding short video examples

Here are the best ways to add video demonstrations to this page:

### Option 1: YouTube or Vimeo (Recommended for longer videos)

Embed videos using a responsive iframe:

```html
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
    <iframe
        style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
        src="https://www.youtube.com/embed/VIDEO_ID"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
    </iframe>
</div>
```

**Pros**: Reliable, accessible, good performance
**Cons**: Need to upload to YouTube/Vimeo first

### Option 2: Loom link with thumbnail (Current site approach)

Create a clickable thumbnail that opens the video:

```html
<div style="text-align: center;">
    <a href="https://www.loom.com/share/YOUR_VIDEO_ID">
        <img src="../images/your-thumbnail.png"
             alt="Click to watch: How eye gaze dragging works"
             style="width: 60%; max-width: 800px;" />
    </a>
    <p><em>Click image to watch video</em></p>
</div>
```

**Pros**: Quick to set up, no hosting needed
**Cons**: Requires click to view, leaves the page

### Option 3: Self-hosted HTML5 video

For videos stored in your repository:

```html
<div style="text-align: center;">
    <video width="80%" controls style="max-width: 800px;">
        <source src="../videos/eye-gaze-drag-demo.mp4" type="video/mp4">
        <source src="../videos/eye-gaze-drag-demo.webm" type="video/webm">
        Your browser doesn't support video playback.
    </video>
    <p><em>Eye gaze drag demonstration</em></p>
</div>
```

**Pros**: Complete control, works offline, no third-party dependencies
**Cons**: Large files in your repo, you manage hosting/bandwidth

### Option 4: Animated GIFs (Best for very short clips)

For demos under 5 seconds:

```html
<div style="text-align: center;">
    <img src="../images/drag-demo.gif"
         alt="Animation showing eye gaze drag action"
         style="width: 60%; max-width: 600px;" />
    <p><em>Eye gaze drag in action</em></p>
</div>
```

**Pros**: Plays automatically, no clicking needed, works everywhere
**Cons**: Large file sizes for longer clips, no audio, lower quality

### Recommendation

- **For quick demos (< 10 seconds)**: Use animated GIFs
- **For tutorials (1-3 minutes)**: Use YouTube embeds
- **For in-person demos you're recording on the fly**: Use Loom links
- **For archived examples you want to preserve long-term**: Self-host HTML5 video

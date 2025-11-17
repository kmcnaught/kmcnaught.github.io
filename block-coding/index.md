---
layout: page
title: Block Coding with Alternative Access
permalink: /block-coding/
---

<div style="text-align: center; margin-bottom: 30px;">
    <img src="../images/code-snippet-2.png" alt="Screenshot of block coding interface" style="width: 40%; max-width: 400px;" />
</div>

## Making block coding accessible for everyone

Many children first learn to code at school using block coding platforms like Scratch, Code.org or MakeCode. These are designed to be easy to use, but the "drag and drop" method can be challenging for students who use eye gaze, switch access or other alternative inputs for computer control.

This project is funded by the [Blockly Accessibility Fund](https://developers.google.com/blockly/accessibility-fund). We're developing free resources to help users of eye gaze and other assistive technology to access block coding platforms.

## Find resources for your student

We've organised resources for three key groups - grid-based users, mouse control users, and AAC users. Your students may match more than one group!

<style>
.cards-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin: 30px 0;
}

.card {
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    overflow: hidden;
    background: #fafbfc;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    transition: transform 0.2s, box-shadow 0.2s;
}

.card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 24px rgba(0,0,0,0.12);
}

.card-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
    background-color: #f6f8fa;
}

.card-content {
    padding: 20px;
    background: white;
}

.card h3 {
    margin-top: 0;
    color: #1a5bb8;
    font-size: 1.3em;
}

.card p {
    color: #333;
    line-height: 1.6;
}

.card strong {
    color: #1a1a1a;
    font-weight: 600;
}

.card-link {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: white;
    color: #1a5bb8;
    font-weight: bold;
    text-decoration: none;
    font-size: 1.05em;
    border: 2px solid #1a5bb8;
    border-radius: 5px;
    transition: background-color 0.2s, color 0.2s;
}

.card-link:hover {
    background-color: #1a5bb8;
    color: white;
}

.card-link:focus {
    outline: 3px solid #ffd700;
    outline-offset: 3px;
}

@media (max-width: 768px) {
    .cards-container {
        grid-template-columns: 1fr;
    }

    .card-image {
        height: 180px;
    }
}

/* High contrast mode support */
@media (prefers-contrast: high) {
    .card {
        border-width: 3px;
    }

    .card-link {
        border-width: 3px;
    }
}

/* Reduced motion support */
@media (prefers-reduced-motion: reduce) {
    .card,
    .card-link {
        transition: none;
    }

    .card:hover {
        transform: none;
    }
}
</style>

<div class="cards-container">

    <article class="card">
        <img src="images/grid control.png" alt="Grid-based access interface" class="card-image" />
        <div class="card-content">
            <h3>Grid-based access users</h3>
            <p><strong>For students using:</strong> eye gaze with grid selection, switch scanning, or other grid-based methods.</p>
            <p>If your student requires grid-based access rather than direct pointing, we have designed interfaces in Grid 3 that use keyboard controls to access the micro:bit MakeCode editor.</p>
            <a href="grid-based-access" class="card-link">View grid-based access resources</a>
        </div>
    </article>
    
    <article class="card">
        <img src="images/mouse control.png" alt="Eye gaze cursor control interface" class="card-image" />
        <div class="card-content">
            <h3>Mouse control users</h3>
            <p><strong>For students using:</strong> eye gaze for cursor control, joystick, head pointer, or similar devices.</p>
            <p>If your student can use direct pointer control (moving a cursor), we recommend starting there. We have tips, tricks and user videos to help make block coding easier.</p>
            <a href="direct-cursor-control" class="card-link">View direct cursor control resources</a>
        </div>
    </article>


    <article class="card">
        <img src="images/AAC-microbit.png" alt="AAC communication page for MakeCode icons" class="card-image" />
        <div class="card-content">
            <h3>AAC users</h3>
            <p><strong>For students who:</strong> use communication devices and want coding vocabulary support</p>
            <p>Having access to relevant vocabulary is essential when learning a new topic. Our AAC pages help students to discuss and explain their code using their AAC device. This can also be used to dictate coding where direct access to the coding tools is not possible.</p>
            <a href="aac-support" class="card-link">View AAC support resources</a>
        </div>
    </article>
</div>


## Understanding the platforms

Different block coding platforms (Scratch, MakeCode, Code.org) all use the same underlying technology, an engine called [Blockly](https://developers.google.com/blockly) which was built by Google. This means that any improvements to core accessibility can help with many different platforms. However, some platforms are further ahead in integrating recent accessibility advances.

**Grid-based control:** Grid-based control requires keyboard navigation. This is currently available in micro:bit MakeCode but is not yet available in other mainstream platforms.

**Mouse-based control:** Although we have started by focussing with micro:bit MakeCode, the resources supporting mouse-based control will be relevant to most platforms, including Scratch and Code.org.

## Why this matters

Programming opens doors to STEM careers and helps students think about problems in new ways. Understanding how computers, games and apps work empowers students to modify and build software for their own needs.

Many assistive tools are built by people who don't fully understand what life is like for assistive tech users. We want to help students join the community of builders and create better assistive technology - or make their own projects: games, apps, home automation or anything they can imagine.

## Get involved

If you're a teacher, therapist, parent, or researcher working with students who use alternative access methods, we'd love to hear from you.

- [Email us](mailto:kirsty.mcnaught@gmail.com) to share feedback or ask questions
- [Fill in our registration form](https://docs.google.com/forms/d/e/1FAIpQLScUwZBrLn7O6XstouOKBpPTYDqz-kaxeoqoJMx4yrz-rHLksg/viewform) to participate in user testing sessions

---

### Quick links

- [Resources for Direct Cursor Control](direct-cursor-control)
- [Resources for Grid-Based Access](grid-based-access)
- [AAC Communication Support](aac-support)

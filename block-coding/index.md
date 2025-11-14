---
layout: page
title: Block Coding with Alternative Access
permalink: /block-coding/
---

<div style="text-align: center; margin-bottom: 30px;">
    <img src="../images/code-snippet-2.png" alt="Screenshot of block coding interface" style="width: 40%; max-width: 400px;" />
</div>

## Making Block Coding Accessible for Everyone

Many children first learn to code at school using block coding platforms like Scratch, Code.org or MakeCode. These are designed to be easy to use, but the "drag and drop" method can be challenging for students who use eye gaze, switch access or other alternative inputs for computer control.

This project is funded by the [Blockly Accessibility Fund](https://developers.google.com/blockly/accessibility-fund). We're developing free resources to help users of eye gaze and other assistive technology to access block coding platforms.

## Find Resources for Your Student

We've organised resources for three key groups - mouse control users, grid-based users, and AAC users. Your students may match more than one group!

---

### OPTION 1: Cards with Image Above Text

<style>
.option1-cards-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin: 30px 0;
}

.option1-card {
    border: 2px solid #e1e4e8;
    border-radius: 8px;
    overflow: hidden;
    background: white;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.2s, box-shadow 0.2s;
}

.option1-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 4px 16px rgba(0,0,0,0.15);
}

.option1-card-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
    background-color: #f6f8fa;
}

.option1-card-content {
    padding: 20px;
}

.option1-card h3 {
    margin-top: 0;
    color: #2a7ae2;
    font-size: 1.3em;
}

.option1-card-link {
    display: inline-block;
    margin-top: 15px;
    color: #2a7ae2;
    font-weight: bold;
    text-decoration: none;
    font-size: 1.05em;
}

.option1-card-link:hover {
    text-decoration: underline;
}

@media (max-width: 768px) {
    .option1-cards-container {
        grid-template-columns: 1fr;
    }

    .option1-card-image {
        height: 180px;
    }
}
</style>

<div class="option1-cards-container">
    <article class="option1-card">
        <img src="images/mouse control.png" alt="Eye gaze cursor control interface" class="option1-card-image" />
        <div class="option1-card-content">
            <h3>Mouse Control Users</h3>
            <p><strong>For students using:</strong> eye gaze cursor control, joystick, head pointer, or similar devices.</p>
            <p>If your student can use direct pointer control (moving a cursor), we recommend starting there. We have tips, tricks and user videos to help make block coding easier.</p>
            <a href="direct-cursor-control" class="option1-card-link">View resources for direct cursor control →</a>
        </div>
    </article>

    <article class="option1-card">
        <img src="images/grid control.png" alt="Grid-based access interface" class="option1-card-image" />
        <div class="option1-card-content">
            <h3>Grid-Based Access Users</h3>
            <p><strong>For students using:</strong> eye gaze with grid selection, switch scanning, or other grid-based methods.</p>
            <p>If your student requires grid-based access rather than direct pointing, we have designed interfaces in Grid 3 that use keyboard controls to access the micro:bit MakeCode editor.</p>
            <a href="grid-based-access" class="option1-card-link">View resources for grid-based access →</a>
        </div>
    </article>

    <article class="option1-card">
        <img src="images/AAC-microbit.png" alt="AAC communication support for coding" class="option1-card-image" />
        <div class="option1-card-content">
            <h3>AAC Users</h3>
            <p><strong>For students who:</strong> use communication devices and want coding vocabulary support</p>
            <p>Having access to relevant vocabulary is essential when learning a new topic. Our AAC pages help students to discuss and explain their code using their AAC device. This can also be used to dictate coding where direct access to the coding tools is not possible.</p>
            <a href="aac-support" class="option1-card-link">View AAC support resources →</a>
        </div>
    </article>
</div>

---

### OPTION 1B: Cards with Dark Blue Background (Accessibility Enhanced)

<style>
.option1b-cards-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin: 30px 0;
}

.option1b-card {
    border: 4px solid #1a5bb8;
    border-radius: 8px;
    overflow: hidden;
    background: #1a5bb8;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    transition: transform 0.2s, box-shadow 0.2s;
}

.option1b-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 4px 16px rgba(0,0,0,0.3);
}

.option1b-card-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
    background-color: #f6f8fa;
}

.option1b-card-content {
    padding: 20px;
    color: white;
}

.option1b-card h4 {
    margin-top: 0;
    color: white;
    font-size: 1.3em;
}

.option1b-card p {
    color: white;
    line-height: 1.6;
}

.option1b-card strong {
    color: white;
    font-weight: 600;
}

.option1b-card-link {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: white;
    color: #0d3c7a;
    font-weight: bold;
    text-decoration: none;
    font-size: 1.05em;
    border-radius: 5px;
    transition: background-color 0.2s, color 0.2s, box-shadow 0.2s;
}

.option1b-card-link:hover {
    background-color: #f0f0f0;
    color: #0a2d5c;
}

.option1b-card-link:focus {
    outline: 3px solid #ffd700;
    outline-offset: 3px;
    box-shadow: 0 0 0 3px rgba(255, 215, 0, 0.3);
}

.option1b-card-link:active {
    background-color: #e0e0e0;
    transform: translateY(1px);
}

@media (max-width: 768px) {
    .option1b-cards-container {
        grid-template-columns: 1fr;
    }

    .option1b-card-image {
        height: 180px;
    }
}

/* High contrast mode support */
@media (prefers-contrast: high) {
    .option1b-card {
        border-width: 6px;
    }

    .option1b-card-link {
        border: 2px solid #0d3c7a;
    }
}

/* Reduced motion support */
@media (prefers-reduced-motion: reduce) {
    .option1b-card,
    .option1b-card-link {
        transition: none;
    }

    .option1b-card:hover {
        transform: none;
    }
}
</style>

<div class="option1b-cards-container">
    <article class="option1b-card">
        <img src="images/mouse control.png" alt="Eye gaze cursor control interface" class="option1b-card-image" />
        <div class="option1b-card-content">
            <h4>Mouse Control Users</h4>
            <p><strong>For students using:</strong> eye gaze cursor control, joystick, head pointer, or similar devices.</p>
            <p>If your student can use direct pointer control (moving a cursor), we recommend starting there. We have tips, tricks and user videos to help make block coding easier.</p>
            <a href="direct-cursor-control" class="option1b-card-link">View resources for direct cursor control →</a>
        </div>
    </article>

    <article class="option1b-card">
        <img src="images/grid control.png" alt="Grid-based access interface" class="option1b-card-image" />
        <div class="option1b-card-content">
            <h4>Grid-Based Access Users</h4>
            <p><strong>For students using:</strong> eye gaze with grid selection, switch scanning, or other grid-based methods.</p>
            <p>If your student requires grid-based access rather than direct pointing, we have designed interfaces in Grid 3 that use keyboard controls to access the micro:bit MakeCode editor.</p>
            <a href="grid-based-access" class="option1b-card-link">View resources for grid-based access →</a>
        </div>
    </article>

    <article class="option1b-card">
        <img src="images/AAC-microbit.png" alt="AAC communication support for coding" class="option1b-card-image" />
        <div class="option1b-card-content">
            <h4>AAC Users</h4>
            <p><strong>For students who:</strong> use communication devices and want coding vocabulary support</p>
            <p>Having access to relevant vocabulary is essential when learning a new topic. Our AAC pages help students to discuss and explain their code using their AAC device. This can also be used to dictate coding where direct access to the coding tools is not possible.</p>
            <a href="aac-support" class="option1b-card-link">View AAC support resources →</a>
        </div>
    </article>
</div>

---

### OPTION 2: Side-by-Side Layout

<style>
.option2-container {
    margin: 30px 0;
}

.option2-category {
    display: flex;
    gap: 25px;
    margin: 30px 0;
    padding: 25px;
    background-color: #f8f9fa;
    border-radius: 8px;
    border-left: 4px solid #2a7ae2;
    align-items: center;
}

.option2-image {
    flex-shrink: 0;
    width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 6px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.option2-content {
    flex: 1;
}

.option2-content h3 {
    margin-top: 0;
    color: #2a7ae2;
    font-size: 1.3em;
}

.option2-link {
    display: inline-block;
    margin-top: 10px;
    font-size: 1.1em;
    font-weight: bold;
    color: #2a7ae2;
    text-decoration: none;
}

.option2-link:hover {
    text-decoration: underline;
}

@media (max-width: 768px) {
    .option2-category {
        flex-direction: column;
        text-align: center;
    }

    .option2-image {
        width: 100%;
        max-width: 300px;
        height: auto;
    }
}
</style>

<div class="option2-container">
    <article class="option2-category">
        <img src="images/mouse control.png" alt="Eye gaze cursor control interface" class="option2-image" />
        <div class="option2-content">
            <h3>Mouse Control Users</h3>
            <p><strong>For students using:</strong> eye gaze cursor control, joystick, head pointer, or similar devices.</p>
            <p>If your student can use direct pointer control (moving a cursor), we recommend starting there. We have tips, tricks and user videos to help make block coding easier.</p>
            <a href="direct-cursor-control" class="option2-link">View resources for direct cursor control →</a>
        </div>
    </article>

    <article class="option2-category">
        <img src="images/grid control.png" alt="Grid-based access interface" class="option2-image" />
        <div class="option2-content">
            <h3>Grid-Based Access Users</h3>
            <p><strong>For students using:</strong> eye gaze with grid selection, switch scanning, or other grid-based methods.</p>
            <p>If your student requires grid-based access rather than direct pointing, we have designed interfaces in Grid 3 that use keyboard controls to access the micro:bit MakeCode editor.</p>
            <a href="grid-based-access" class="option2-link">View resources for grid-based access →</a>
        </div>
    </article>

    <article class="option2-category">
        <img src="images/AAC-microbit.png" alt="AAC communication support for coding" class="option2-image" />
        <div class="option2-content">
            <h3>AAC Users</h3>
            <p><strong>For students who:</strong> use communication devices and want coding vocabulary support</p>
            <p>Having access to relevant vocabulary is essential when learning a new topic. Our AAC pages help students to discuss and explain their code using their AAC device. This can also be used to dictate coding where direct access to the coding tools is not possible.</p>
            <a href="aac-support" class="option2-link">View AAC support resources →</a>
        </div>
    </article>
</div>

---

### OPTION 3: Icon-Style Layout

<style>
.option3-container {
    margin: 30px 0;
}

.option3-category {
    border-left: 4px solid #2a7ae2;
    padding: 20px;
    margin: 20px 0;
    background-color: #f8f9fa;
}

.option3-header {
    display: flex;
    align-items: center;
    gap: 15px;
    margin-bottom: 15px;
}

.option3-icon {
    width: 60px;
    height: 60px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    flex-shrink: 0;
}

.option3-header h3 {
    margin: 0;
    color: #2a7ae2;
    font-size: 1.3em;
}

.option3-link {
    display: inline-block;
    margin-top: 10px;
    font-size: 1.1em;
    font-weight: bold;
    color: #2a7ae2;
    text-decoration: none;
}

.option3-link:hover {
    text-decoration: underline;
}

@media (max-width: 480px) {
    .option3-header {
        flex-direction: column;
        align-items: flex-start;
    }

    .option3-icon {
        width: 80px;
        height: 80px;
    }
}
</style>

<div class="option3-container">
    <article class="option3-category">
        <div class="option3-header">
            <img src="images/mouse control.png" alt="Eye gaze cursor control" class="option3-icon" />
            <h3>Mouse Control Users</h3>
        </div>
        <p><strong>For students using:</strong> eye gaze cursor control, joystick, head pointer, or similar devices.</p>
        <p>If your student can use direct pointer control (moving a cursor), we recommend starting there. We have tips, tricks and user videos to help make block coding easier.</p>
        <a href="direct-cursor-control" class="option3-link">View resources for direct cursor control →</a>
    </article>

    <article class="option3-category">
        <div class="option3-header">
            <img src="images/grid control.png" alt="Grid-based access" class="option3-icon" />
            <h3>Grid-Based Access Users</h3>
        </div>
        <p><strong>For students using:</strong> eye gaze with grid selection, switch scanning, or other grid-based methods.</p>
        <p>If your student requires grid-based access rather than direct pointing, we have designed interfaces in Grid 3 that use keyboard controls to access the micro:bit MakeCode editor.</p>
        <a href="grid-based-access" class="option3-link">View resources for grid-based access →</a>
    </article>

    <article class="option3-category">
        <div class="option3-header">
            <img src="images/AAC-microbit.png" alt="AAC communication support" class="option3-icon" />
            <h3>AAC Users</h3>
        </div>
        <p><strong>For students who:</strong> use communication devices and want coding vocabulary support</p>
        <p>Having access to relevant vocabulary is essential when learning a new topic. Our AAC pages help students to discuss and explain their code using their AAC device. This can also be used to dictate coding where direct access to the coding tools is not possible.</p>
        <a href="aac-support" class="option3-link">View AAC support resources →</a>
    </article>
</div>

---

### OPTION 4: Full-Width Banner Style

<style>
.option4-container {
    margin: 30px 0;
}

.option4-banner {
    position: relative;
    min-height: 280px;
    margin: 25px 0;
    border-radius: 8px;
    overflow: hidden;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
}

.option4-banner::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(135deg, rgba(42, 122, 226, 0.92) 0%, rgba(42, 122, 226, 0.85) 100%);
}

.option4-content {
    position: relative;
    z-index: 1;
    color: white;
    padding: 30px 40px;
    max-width: 800px;
}

.option4-content h3 {
    margin-top: 0;
    font-size: 1.8em;
    color: white;
    text-shadow: 0 2px 4px rgba(0,0,0,0.2);
}

.option4-content p {
    color: white;
    line-height: 1.6;
    font-size: 1.05em;
}

.option4-content strong {
    color: #f0f0f0;
}

.option4-link {
    display: inline-block;
    margin-top: 15px;
    padding: 12px 24px;
    background: white;
    color: #2a7ae2;
    font-weight: bold;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.05em;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    transition: transform 0.2s, box-shadow 0.2s;
}

.option4-link:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

@media (max-width: 768px) {
    .option4-banner {
        min-height: 320px;
    }

    .option4-content {
        padding: 25px 20px;
    }

    .option4-content h3 {
        font-size: 1.5em;
    }
}
</style>

<div class="option4-container">
    <article class="option4-banner" style="background-image: url('images/mouse control.png');">
        <div class="option4-content">
            <h3>Mouse Control Users</h3>
            <p><strong>For students using:</strong> eye gaze cursor control, joystick, head pointer, or similar devices.</p>
            <p>If your student can use direct pointer control (moving a cursor), we recommend starting there. We have tips, tricks and user videos to help make block coding easier.</p>
            <a href="direct-cursor-control" class="option4-link">View resources for direct cursor control →</a>
        </div>
    </article>

    <article class="option4-banner" style="background-image: url('images/grid control.png');">
        <div class="option4-content">
            <h3>Grid-Based Access Users</h3>
            <p><strong>For students using:</strong> eye gaze with grid selection, switch scanning, or other grid-based methods.</p>
            <p>If your student requires grid-based access rather than direct pointing, we have designed interfaces in Grid 3 that use keyboard controls to access the micro:bit MakeCode editor.</p>
            <a href="grid-based-access" class="option4-link">View resources for grid-based access →</a>
        </div>
    </article>

    <article class="option4-banner" style="background-image: url('images/AAC-microbit.png');">
        <div class="option4-content">
            <h3>AAC Users</h3>
            <p><strong>For students who:</strong> use communication devices and want coding vocabulary support</p>
            <p>Having access to relevant vocabulary is essential when learning a new topic. Our AAC pages help students to discuss and explain their code using their AAC device. This can also be used to dictate coding where direct access to the coding tools is not possible.</p>
            <a href="aac-support" class="option4-link">View AAC support resources →</a>
        </div>
    </article>
</div>

---

## Understanding the Platforms

Different block coding platforms (Scratch, MakeCode, Code.org) all use the same underlying technology, an engine called [Blockly](https://developers.google.com/blockly) which was built by Google. This means that any improvements to core accessibility can help with many different platforms. However, some platforms are further ahead in integrating recent accessibility advances.

**Grid-based control:** Grid-based control requires keyboard navigation. This is currently available in micro:bit MakeCode but is not yet available in other mainstream platforms.

**Mouse-based control:** Although we have started by focussing with micro:bit MakeCode, the resources supporting mouse-based control will be relevant to most platforms, including Scratch and Code.org.
<!--
## Resource Status Key

Each resource on our site has a clear status to help you know what to expect:

- **Ready to Use**: Available for download and immediate use with your students
- **Testing Available**: Functional prototype seeking testers for feedback
- **Coming Soon**: Currently in development, check back for updates -->

## Why This Matters

Programming opens doors to STEM careers and helps students think about problems in new ways. Understanding how computers, games and apps work empowers students to modify and build software for their own needs.

Many assistive tools are built by people who don't fully understand what life is like for assistive tech users. We want to help students join the community of builders and create better assistive technology - or make their own projects: games, apps, home automation, anything they can imagine.

## Get Involved

If you're a teacher, therapist, parent, or researcher working with students who use alternative access methods, we'd love to hear from you.

- [Email us](mailto:kirsty.mcnaught@gmail.com) to share feedback or ask questions
- [Fill in our registration form](https://docs.google.com/forms/d/e/1FAIpQLScUwZBrLn7O6XstouOKBpPTYDqz-kaxeoqoJMx4yrz-rHLksg/viewform) to participate in user testing sessions
<!-- - [View other resources and updates](resources-and-updates) for the latest developments -->

---

### Quick Links

- [Resources for Direct Cursor Control](direct-cursor-control)
- [Resources for Grid-Based Access](grid-based-access)
- [AAC Communication Support](aac-support)
- [Additional Resources & Updates](resources-and-updates)

# Speaking Guide

This is a comprehensive guide for finding, preparing, and delivering technical talks.

## Finding Talks

- Signup for request for proposals email lists.
- Look at the previous year's events.
- Find local meetups online and reach out to organizers.

## Call for Proposals (CfP)

Most conferences require you to submit a Call for Proposal (CfP) to apply to give a talk.

### CfP Tips

1. **Keep it short:** This talk demonstrates why open source is a key component of modern software development by following the evolution of Kubernetes.
1. **Focus on the attendee:** In this presentation, attendees will learn the steps for connecting a Raspberry Pi to a Kubernetes cluster and its importance.
    - Leave notes to reviewers:
      - NOTE: This is a live demo, but it does not rely on the public Internet and can run entirely from my local laptop.
      - NOTE: Thank you for taking the time to review this talk. I appreciate it.
1. **Focus on benefit over content:** Attendees will learn how to automate control of a light bulb using Kubernetes and a Raspberry Pi.
1. **Avoid being too technical:** Attendees will learn how to control a light bulb using Kubernetes and a Raspberry Pi.
1. **Avoid being too specific:** Attendees will learn how to control a light bulb using a cluster scheduler and a microcontroller. While this talk uses Kubernetes and a Raspberry Pi, the concepts are largely applicable to many technologies.
1. **Don't cliff-hang:** After unplugging our servers as part of routine chaos engineering, our Zookeeper cluster was unable to elect a leader. This talk discusses how we diagnosed the problem, fixed it while minimizing downtime, and submitted a patch to fix the problem upstream.
1. **Empathize with reviewers**
1. **Use an enticing, succinct title:**
    - ✗: How I used Kubernetes to take down all of production with one command
    - ✓: Safeguarding Kubernetes ACLs
    - ✗: Introduction to Kubernetes
    - ✓: Kubernetes for Startups
1. Use bullets, outlines, formating
    - The key takeaways will be:
        1. How to peel bananas
        1. Hot to slice apples
1. **Active verb tense, everywhere**
    - Attendees will learn...
    - We will explore a demo...

### CfP Examples

- X is a great way to do Y. This talk will teach you everything to do Z including a, b, c. After this talk, you'll be ready to foo.
- Have you wanted to do X but didn't make progress? Y can help you do X. This talk will teach you how to A, how to B, and how C can help too. After this talk...
- Question? Fact helps. This talk will teach attendees how to X including (list A, B, C). After this talk, attendees can Z!

### CfP Levels

- **100 introductory:** Assumes little to no experience with topic
- **200 intermediate:** Provides real-world samples with moderate technical detail
- **300 advanced:** Requires in-depth understanding of technical features
- **400 expert:** Provides expert-to-expert talk with deep technical knowledge

## Writing the talk

- Why YOU for this talk?

### POINT system:

- **Presence** -- tools for preparation and delivery of a talk - who are you when you deliver a talk
- **Originality** -- your authentic voice and importantly unique perspective
- **Inclusion** --  how are you creating an inviting space & talk for the listeners; why should they listen/learn
- **Narrative** -- what is your story and that of whatever you are talking about
- **Transformation** -- how do you identify your own growth areas/want to change impact the audience

### THINK FEEL DO (example):

- **THINK:** I have a lot of brilliant ideas. They can use the functions framework to speed up their work. 
- **FEEL:** Limitless. Easy. Relieved about the ease. Confident in the work.
- **DO:** You can deploy on Google and rest assured that things won’t break over the weekend.
  
### Story Spine `_/\-`:

1. One upon a time...
1. Every day...
1. But one day...
1. Because of that...
1. Because of that...
1. Because of that...
1. Until finally...
1. Ever since then...
1. (optional) moral

### Structure

- **Beginning** (Beginning, Middle, End)
- **Middle** (Beginning, Middle, End)
- **End** (Beginning, Middle, End)

### Video Scripts

Checklist for writing scripts for videos:

- **Set goals and main takeaway:** e.g., developers know the basics of how to use the API.
- **Set target audience:** e.g., v1 API users migrating to v2.
- **Set clear narrative:** Outline and script.
- **Create visual supports:** Slides, code, screencasts, and live-coding practice.

## Slides

Most of my content around slides is internal, but here are some tips:

- **Minimize content:** The audience should pay attention to what the speaker is saying. Make slides minimal.
- **Font:** Min 18pt. Should be readable on phone.
- **Less is more:**
  - Remove non-critical info: punctuation, complete sentences, explanations.
  - Code does not have to compile: no imports, complete braces.
  - Show minimum amount of code: desaturate code or use `...` for other code.
  - Reveal gradually: show bullets 1 by 1. Code in successive parts.
  - Make important parts prominent (bold, large).
  - Space out content evenly (vert/horiz).
  - Visuals are faster than text.
- **Motivation:** Each slide should motivate the next slide. This will have the viewer follow your thinking. Why is this important?
- **Flow:** High-level overview, then zoom down to technical details.
- **Code Highlighting:** [SlidesCodeHighlighter](https://romannurik.github.io/SlidesCodeHighlighter/)
  - In slides: cursor should be red pointer.
  - In code: cursor should be regular.

## Setup & Recording

- **Equipment:** MBP, Camtasia 3.1.2, Microphone w/ mic cable, mic cradle, mic stand, pop filter.
- **Environment:** Table secure, blanket over table to minimize sound bounce, chair, water.
- **Camtasia Preferences:**
  - Recording: 30 fps
  - Project: Original Recording Dimensions
  - How to Record: New Project. Record. Mic levels should be -6db to -18db.
  - Record 20 seconds of silence.
- **Exporting:** Export locally to .mp4, 30 frame rate, 24 keyframe rate, H.264 compression, dimensions current data rate automatic, high profile, CAVLC entropy. Enable audio/smoothing.
  - Save as `LXL001_PROJECT`. Each recording is `SHOWCODE_VIDEOTYPE_TAKENUMBER` like `LXL001_screencast_T1`.
- **Room Tone:** Save 30s room tone `LXL001_roomtone_T1`.

## Prep

- 3-5 deep breaths. Roll shoulders.
- Shake out, 8 4 2 1 each limb, count out loud.
- Lion/Mouse face muscle stretch.
- Tongue twisters, then use a part of YOUR talk.
- I love my spot!

## Pre-talk

- Look sharp.
- Wear a nametag.
- Smile.
- Bring energy, personality, excitement for your product.
- Talk directly to the audience.
- Take pictures and show those instead of live demos.
- Setup computer with slides and demos. Close everything else as much as possible.

## Presentation

- **Articulation:** Pronounce every word clearly. No mumbling. Don't slur.
- **Vocabulary:** Use natural sounding words to be credible. Use simple, natural speech (not scripts). No complicated words that aren't spoken.
- **Tone:** Use your voice to create inflections in the sentences. Pause for emphasis. Natural pitch.
- **Emphasis:** Find key 1-2 words in each sentence - pronounce them slightly slower. Add short pauses.
- **Pacing:** Vary your pace according to what you're speaking about. Use normal convo pace. Complex info should be slow. Easy should be quick.
- **Posture:** Good natural posture. Shoulders back, straight. No slouching, hunching, or stiffness.
- **Gestures:** Can be used to emphasize a point. But they can be distracting.
- **Expression:** Be consistent with your words.
- **Honesty:** Super important and genuine. Super important. Don't say "I am so excited..." if you aren't.
- **Eye contact:** Remember to go back to the lens.
- **Practice:** Any type of public speaking helps make you more comfortable. In real life. Watch yourself.

### Tips from Google's studio:

- Get your energy up!
- Be animated with your delivery. Use hands. Sit up. Camera at eye-line. Smile.
- Explain, don't read. Everybody can tell you're reading. Break into bullet points. Short and punchy.
- Avoid using first person like "let's", implying a company and you walking through something. Focus on the user.

## Post-talk

- Thank the attendees and organizers.

### Thank you templates

#### For Attendees

```
Thanks so much for coming! 💖💕💗

👨‍💻👩‍💻TRY our open-source Functions Framework:
https://github.com/GoogleCloudPlatform/functions-framework-nodejs

🎥WATCH our great introductory videos:
https://www.youtube.com/watch?v=1w2t3EWmlVU

🐦TWEET your questions at me:
https://twitter.com/granttimmerman

Don't forget to smile, and I'll see you next time!
```

#### For Organizers

Thank the organizers in person and in email.

## Organizing an Event

### Types of content

- **Keynote** | 30m: Introduction for general audiences
- **Technical Session** | 30m: Deep dive and instructional content
- **Technical Demos:** Short tutorials supporting code/technical content
- **Ask Me Anything (AMAs)** | 30m: Panel about a topic area
- **Workshops** | 45-60m: Instructor-led deep dives
- **Interactive Sandboxes:** Fun, educational, and interactive tutorials
- **Codelabs:** Self-guided learning experience tutorials
- **Meetups:** Live, casual, open, facilitated forums

### Timeline

- **Proposals:** Send out CfPs, gather speaker bios, gather links to videos/codelabs, distribute slide template.
- **Pre-event:** Tech check, slides due, record sessions (if pre-recorded).
- **Event:** Record talk (pause and repeat if mistakes), clap to sync audio/video, record thumbnails.
- **Post-event:** Sign-off from content lead.

## Abstracts

Here are descriptions for some of the common events:

### Go Serverless with Google Cloud!

- **English:** Your development agility comes from building systems composed of small, independent units of functionality focused on doing one thing well. Cloud Functions lets you build and deploy services at the level of a single function, not at the level of entire applications, containers, or VMs. In this session, you will learn the fundamentals about Google Cloud Functions, some use-cases, and how to write Cloud Functions in TypeScript!
- **Spanish:** Google Cloud Functions hace fácil para los desarrolladores correr y escalar código en la nube así como construir aplicaciones event-driven serverless. En esta charla aprenderás sobre las últimas actualizacaiones con Google Cloud Functions junto con algunas demos de Funcionts en acción!

### All About Apps Script

Learn how to increase the power of your favorite Google apps — like Calendar, Docs, Drive, Gmail, Sheets, and Slides – with JavaScript in Google Cloud.
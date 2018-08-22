# Contributing to Firefox DevTools UX

Welcome, and thank you for your interest in contributing to DevTools UX! Our team only recently started working with design contributors, so things may be a bit disorganized initially. I’m happy to hear any feedback or ideas on improving the onboarding process. - [Victoria](mailto:victoria@mozilla.com) 

**First Steps**

1. Join the friendly [Firefox DevTools Slack](https://devtools-html-slack.herokuapp.com/) community! 
   1. The new #ux channel is a place for us designers to hang out, ask questions, post mockups for feedback, and offer feedback for other designers’ mockups. I’ll be communicating with everyone through this channel.
   2. Feel free to introduce yourself or talk about general DevTools things in #general
2. Check out the [Firefox design system](https://design.firefox.com/photon/). 
   1. We will be starting work on a new DevTools-specific design system with a Sketch library very soon! Let me know if you want to help with this.
3. Sign up for a [GitHub](https://github.com/) account if you don’t already have one. We’ll be organizing all the projects as github issues.

**Projects**

(Work is happening to collect and organize all available UX projects. This may take a bit of time at first. If you’re really excited to get started and want one of the first tasks, some will be posted in Slack.)

1. Once you have a task, it’s great to do a little research.  
   1. Get ideas from similar UI in DevTools and Firefox. Download [Firefox Nightly](https://www.mozilla.org/en-US/firefox/channel/desktop/) to view the latest version of the UI. When possible, try to reuse already existing colors and other visuals in DevTools/Firefox.
   2. Ask questions in Slack. Developers in panel-specific channels can help with questions about user needs and behaviors. You can also ask your developer friends for ideas!
   3. See what Chrome, Safari, and Edge are doing for similar features. Also check out other development tools, like Atom and Xcode.
2. Start working on the design. There are several ways to approach this, depending on the task.
   * Make a mockup. This could involve getting a sketch file from me, modifying a screenshot, or recreating a mockup if you're interested in helping with our sketch libraries. Great for more involved visual changes that would be too much to code via the other methods. For changes that really need the context of real content, this might not be practical. For more complex UX tasks, a low-fidelity wireframe is a great way to start.
   * Inspect the toolbox via the special [inception-Inspector](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox) to try out small CSS changes. This can be fraught with trouble due to the usual Inspector problem of no export/persistence features yet (it's in the plans!), but I use this all the time, every day.
   * Building and running Firefox (instructions below), and trying CSS changes right in the codebase. This can be tricky to get started, but especially useful because then you can seamlessly move on to submitting a patch :).
3. Post screenshots in the relevant github issue and on #ux for feedback. Make a few iterations. (This might not be necessary for small tasks.)
4. Optional: When you get to the high-fidelity stage, install the Firefox Sketch library. (TBD: public link to library)
5. Optional: To test small changes live, you can [use the Inspector on DevTools](https://developer.mozilla.org/en-US/docs/Tools/Browser_Toolbox). This is a great way to quickly see how e.g. a new color would look across the whole UI without having to mock it up exactly. 

6. Get a final sign-off from Victoria to send your design into development mode!
7. Bonus: Take screenshots of every stage for your portfolio :)

## Implementing Your Own Design

Do you know HTML and CSS? If so, you can make your own design a reality! The very friendly engineers of Firefox DevTools can help mentor you through the process of submitting a good patch. The biggest first step is building Firefox. Here are some guides:
* [Building Firefox for DevTools Development (Mac/Linux)](https://docs.firefox-dev.tools/getting-started/build.html)
* [Debugger Contribution Guide](https://github.com/devtools-html/debugger.html/blob/master/.github/CONTRIBUTING.md)
* [General Firefox Contribution Guide (Windows)](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Introduction#Step_1_Build_Firefox_for_Desktop_or_Android)
* [Profiles](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Multiple_profiles) for running multiple Firefoxes at the same time 

## Potential Projects in the Works

* Firefox iOS tasks — Robin
* [Common Voice](https://github.com/mozilla/voice-web/issues) - Megan

## Communications

* [Slack: #ux channel](https://devtools-html-slack.herokuapp.com/)
* [Community hangout over video chat](https://appear.in/devtools-ux) - time TBD

## UX Contributors 
(Slack usernames)

- @caterina, community advisor
- @fvsch, UX analysis extraordinaire
- @kristin, UX contributing pioneer
- @isabelle
- @Alejandro
- @Shaiz
- @arnolem
- @mario
- @Yash
- @bastien
- @Jordan
- @bree
- @Thiago
- @Raulinga
- @Gabiskandar

+more, will add you as you join slack

## Mozilla People

Mentors:
- @victoria - Senior DevTools UX
- @Matt Croud - DevTools UX 
- Robin - Senior Firefox iOS UX
- @yzen - Accessibility mentor
- @erica - Developer mentor
- @gl - Developer mentor

Project people:
- @bwinton - DevTools UX Manager
- @Martin Balfanz - DesignTools PM (Inspector, Style Editor, Accessibility, Canvas, Shader…)
- @digitarald - DevTools PM (Console, Debugger, Network...)

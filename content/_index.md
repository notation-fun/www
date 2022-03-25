+++
title = "Fun Notation"
sort_by = "weight"
+++

# What's the idea?

This is my experimentation on musical notations.

Want to create some applications to help me to visualize music, practice easier, and provide nicer way to show scores or tabs.

Some of current tried ideas:

## Color and shapes for notes and chords

![Chords](/images/chords.png?raw=true)

## Guitar tabs to show both pitch and durations for notes

![Guitar Tab](/images/guitar_tab.png?raw=true)

# What's implemented?

## Guitar Tab + Melody + Lyrics

Features:

- audio for each notes, sound quality not good enough (esp. in browser)
- guitar fretboard synced with current played notes
- A/B repeat for selected bars


![Notation Viewer](/images/notation_viewer.gif)

[Watch on Youtube](https://youtu.be/vxXcNSpCZ5Y)

[Try in browser](https://www.notation.fun/notation/viewer?lang=en-US&tab=tabs/scarborough_fair.ron)
Note that the web version is only working in desktop browser, the touch input is not working on mobile browsers yet.

[Desktop versions](https://github.com/notation-fun/notation/releases) can be downloaded from releases.

Get [source code](https://github.com/notation-fun/notation) to run on your machine.

# How it's built?

The current version is writted in [Rust](https://www.rust-lang.org), on top of [Bevy Engine](https://bevyengine.org), started as a demo to learn both the language and the game engine, but got much progress and show some potentials quickly.

At this moment, there is no visual editor yet, instead a DSL in Rust is created to write tabs (also serving learning purpose at the first place), it's far from perfect, and got me quite some headaches some time, but did learned a lot, and some part of it is really nice. Plan to write some blogposts later on this topic.

# What's the plan?

Will try to make the guitar tab part useful for myself first, do more experiments on visual representation for music, then maybe release some applications or maybe games in the future.

----

# Some Inspirations

### [Chromesthesia Color for Notes](https://en.wikipedia.org/wiki/Chromesthesia)

Most colorful notation systems using rainbow colors for notes, but I found this chromesthesia system is much better for me to feel the music, especially when apply the colors to chords.


### [Hook Theory](https://www.hooktheory.com/)

This is really awesome, have tons of materials for music learning, also has a very powerful web application.

### [Groove Pizza](https://apps.musedlab.org/groovepizza/?museid=qD-Y91QD3&)

Very nice web application to visualize rhythm.




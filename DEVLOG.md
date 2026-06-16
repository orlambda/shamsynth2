# Devlog

Notes about the process of making this plugin, including challenges I've faced, what I've learned, and future aims.

Entries are in reverse chronological order.

My thoughts here are meant to be somewhat organised, but I do not worry too much about concision. The most important (or interesting) points will probably make it into either the README or a future portfolio page.

## 2026-06-16

### Initial thoughts
When I started working on [shamsynth1](https://github.com/orlambda/shamsynth1), my main aim was simply to make a synthesiser plugin. I wasn't sure what features it would have when I started, and decided to start small and add complexity as I go, with some kind of modular synth in mind as a possible end goal. My focus was on programming and learning to use JUCE, but naturally, design questions emerged, and I feel like that synth is heading in its own direction, and so I decided a modular synth deserves its own project.

One of the reasons I added a modulation matrix to shamsynth1 was it felt like a decent compromise, because a modular synth felt quite ambitious. In Kate Gregory's conference talk [Steps to Wisdom](https://www.youtube.com/watch?v=iS9mbqho6s0&list=PLsAtvvJ8KXBT-Tx67H5P3TgkiW6llnoBE&index=7&t=490) she says one of the things that separates senior developers from juniors is that seniors believe that whatever they're trying to do should work - that whatever idea they have, or what they have been asked to do, should be possible, and they find a way to do it. I recently realised that not only had I not tried making a modular synth yet, I hadn't even given much thought into what the process of making one would look like. I wasn't sure if the modulation matrix was a reasonable goal when I started working on that, and was surprised how simple it was to get it running. Surely then, I should just start working on the modular synth and find a way to make it work.

In an extremely short amount of time, I thought about what some of the hurdles would be, how they can be separated, and how some can be implemented very easily and quickly while others can be dealt with later. Much like how I started with a 1x1 modulation 'matrix' in shamsynth1, then a 1x2, then a 2x2, I could start with one 'slot' for a module, and one option for what that module could be. Adding slots and module options should then be fairly simple. I thought about how the APVTS would store all of this information, and how various other things could be implemented. I also realised that if I had thought of the project as a game rather than a synthesiser, I would have started work on it straight away, so it's probably time to changing my thinking and get to work.
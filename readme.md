<!-- title -->

# Benshi Organ

<!-- /title -->

<!-- short-description -->

**An instrument for live performance of movie subtitle data.**

<!-- /short-description -->

## Overview

Software for a live performance created by [Eric Mika](https://ericmika.com) and [Alejandro Crawford](https://amjc.info/) at [NYU ITP](https://tisch.nyu.edu/itp) in the spring of 2010.

The Benshi Organ turns a two-octave MIDI keyboard into an instrument for composing with movie dialog. Its corpus is the subtitles of 25 movies in each of five genres: action, comedy, horror, romantic comedy, and science fiction. A few movies appear in two genres.

Each key plays a line from one movie, reading it aloud with macOS text-to-speech and printing it in a terminal. A volume pedal sets where in the runtime of each movie the subtitle is sampled from, and an array of foot switches selects the genre.

The name refers to the Japanese [benshi](https://en.wikipedia.org/wiki/Benshi), performers who narrated silent films live.

The software is a [Processing](https://processing.org/) sketch, `rwet_final.pde`, and a small Python server, `parrot_server.py`, that prints each line it receives.

See [the project page](https://frontiernerds.com/projects/benshi-organ) for photos and background.

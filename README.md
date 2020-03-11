# interactive_mathmusic
Interactive tools for math/music

This repository contains web-based interactive tools for math/music.
Developed with [d3.js](https://d3js.org/) and [WebAudioFont](https://surikov.github.io/webaudiofont/).

## Parsimonious graphs on triads for Douthett's and Steinbach's P<sub>m,n</sub> relations

Access to the interactive page is [available here](https://alexpof.github.io/interactive_mathmusic/Pmn_graphs/pmn_graphs.html)

This interactive visualization presents Douthett's and Steinbach's P<sub>m,n</sub> relations on various triads.
Two triads are said to be P<sub>m,n</sub>-related if *m* pitch classes move by a semitone,
while *n* pitch classes move by a whole tone, the rest of the pitch classes being identical.
The set of triads and the set of P<sub>m,n</sub> relations can be selected from the page. The nodes are clickable and will let you play the
corresponding chord.
Shift-clicking on a node saves the chord in a progression which can then be replayed.


For more information :

  * The original paper : Douthett, Jack, and Peter Steinbach. 1998. “Parsimonious Graphs: A Study in Parsimony, Contextual Transformations, and Modes of Limited Transposition.” Journal of Music Theory 42 (2): 241–263.

  * See this [blog post](https://alpof.wordpress.com/2019/09/22/transformational-music-theory-16/).

## Chord creator with Douthett's and Steinbach's P<sub>m,n</sub> relations

Access to the interactive page is [available here](https://alexpof.github.io/interactive_mathmusic/Pmn_chordcreator/pmn_chordcreator.html)

A variant of the above interactive page, which allows the user to create the chords of his choice and to visualize Douthett's and Steinbach's P<sub>m,n</sub> relations between them.

## Rhythmic canons mod 2

Access to the interactive page is [available here](https://alexpof.github.io/interactive_mathmusic/rhythm_canon_mod2/rhythm_canon_mod2.html)

A *rhythmic canon 'modulo 2'* is a periodic tiling of the integers by a pattern of beats, such that only an odd number of players play on each beat ('modulo 2').

The study of rhythmic canons mod *p* (with *p* prime) is closely related to the study of polynomials and their factorization in a finite field Fp.
It was proved by Amiot that any polynomial in Fp (the *motive*) tiles the integers modulo p, i.e. for any polynomial A(X) in Fp, there exists E(X) in Fp (the *entries*), and *L* such that
we have A(X)E(X)=1+X+X<sup>2</sup>+...+X<sup>L-1</sup>.
The motive and the entries can be swapped, creating a new rhythmic canon mod *p*.

For more information :

  * Amiot, E.; 'Structures, Algorithms and algebraic tools for rythmic canons', Perspectives of New Music, 49 (2), 2011, pp. 93-142.

  * Caure, H.; 'Modulus p Vuza canons: generalities and resolution of the case {0,1,2k} with p=2', arXiv:1505.06930.

# Types, Clojure & Logic

pretty much all about conferences, but still a bit other stuff.

* i've started trying to read [Gradual Typing for Functional Languages](http://ecee.colorado.edu/~siek/pubs/pubs/2006/siek06_gradual.pdf),
    which is the basis for `core.typed` and Typed Racket.

    [this talk](https://www.youtube.com/watch?v=_HM8Vczybj4), by Michael Bernstein, is
    a good introduction with lots of references. there's also this
    [large list of references](https://github.com/samth/gradual-typing-bib), which has
    even more material
* i've been working on [pixie](https://github.com/pixie-lang/pixie), a *small, fast & native
    lisp with "magical" powers*. it's quite fun already, if you have docker installed,
    try it out using `docker run -it --rm pixielang/pixie`. (or drop by in `#pixie-lang`
    on freenode and say something like `,(let [name "pixie"] (str "hello, " name "!"))`.)

    Timothy Baldridge, the author of pixie, is currently rewriting the runtime system
    using *effects*, which you can read about in [this paper](http://arxiv.org/pdf/1203.1539v1.pdf).
    (probably have a look at the examples on page 11 onwards first.) Brandom Bloom
    did a presentation ([slides](https://speakerdeck.com/paperswelove/brandon-bloom-on-programming-with-algebraic-effects-and-handlers-by-andrej-bauer-and-matija-pretnar), [audio](http://www.mixcloud.com/paperswelove/bbloom_3_17_2014_programming_with_alegebraic_effectshandlers/))
    at Papers We Love about it, too.

    basically, this will allow all kinds of fancy things, which Timothy has
    [summarized here](https://github.com/pixie-lang/pixie/tree/effects-integration/pixie/vm/effects#effects-system-for-pixie-prototype).
* i've linked Julia Evan's [You can be a kernel hacker!](https://www.youtube.com/watch?v=0IQlpFWTFbM)
    below, but did you know that [you can also be an os developer](http://jvns.ca/blog/2013/11/26/day-34-the-tiniest-operating-system/)?

    i've tried it, spent a few hours on it, and wrote [my own (tiny) os](https://github.com/heyLu/lp/tree/master/os).
* [Aqueous](http://aqueousband.com/) sounds fun

now, on to the conferencing.

* it was awesome watching [Clojure/conj](http://clojure-conj.org) from afar,
    especially because they did [same-day videos](https://www.youtube.com/user/ClojureTV/videos)
    which is really cool

    my favourites so far:

    - [Jeanine Adkisson - Variants are Not Unions](https://www.youtube.com/watch?v=ZQkIWWTygio)

        a talk about using variants in Clojure, instead of just unions and hoping
        it won't break. with dashes of [types](https://github.com/clojure/core.typed),
        [pattern matching](https://github.com/clojure/core.match) and [datomic](http://www.datomic.com/).

        oh, and i *loved* the slides.
    - [Rich Hickey - Inside Transducers](https://www.youtube.com/watch?v=4KqUvG8HPYo)

        with more code than the strangeloop talk. :)

        a more in-depth/non-introductory than the [StrangeLoop talk](https://www.youtube.com/watch?v=6mTbuzafcII),
        including a look at future features of core.async relating to transducers.

    and quite a few more:

    - [Steven Yi - Developing Music Systems on the JVM](https://www.youtube.com/watch?v=wDcN7yoZ6tQ)
    - [Paul deGrandis - Unlocking data-driven systems](https://www.youtube.com/watch?v=BNkYYYyfF48),
        would like to have some more details on this. or maybe i'll just have to try it myself.
    - [Ashton Kemerling - Generative Integration Tests](https://www.youtube.com/watch?v=HXGpBrmR70U),
        about [test.check](https://github.com/clojure/test.check) and testing complex systems with
        generative testing.
    - [Brian Goetz - Stewardship: the Sobering Parts](https://www.youtube.com/watch?v=2y5Pv4yN0b0),
        the Java Language Architect talking about slowly evolving Java and the JVM,
        with an interesting perspective on programming language. and value types are
        coming to the JVM.

    and then there are still more to watch:

    - [Zach Tellman - Always Be Composing](https://www.youtube.com/watch?v=3oQTSP4FngY)
    - [Glenn Vanderberg - Cló: The Algorithms of TeX in Clojure](https://www.youtube.com/watch?v=824yVKUPFjU)
    - [Zach Oakes - Making Games at Runtime with Clojure](https://www.youtube.com/watch?v=0GzzFeS5cMc)

    oh well, you might as well watch [all of them](https://www.youtube.com/user/ClojureTV/videos)
* in general, what fascinates me about Clojure (and Racket to an extent) is that you can get
    express ideas coming from all over the place (types, pattern matching, logic, quickcheck,
    channels) in one language, without having to change it all the time.

    it's exciting, because i want *all* of those things, in one language, availlable
    when i need them or just feel link it.
* while we're talking about conferences, did i mention that [StrangeLoop](https://thestrangeloop.com/)
    was just as amazing and *also* posted [all the videos](https://www.youtube.com/channel/UC_QIfHvN9auy2CoOdSfMWDw/videos)
    online?

    no? well, no you know.

    i'll just leave you with titles, these are all great, but there are very likely a lot
    more that i missed:
    [The Mess We're In](https://www.youtube.com/watch?v=lKXe3HUG2l4),
    [Programming Should Eat Itself](https://www.youtube.com/watch?v=SrKj4hYic5A),
    [Inside the Wolfram Language](https://www.youtube.com/watch?v=EjCWdsrVcBM),
    [Transducers](https://www.youtube.com/watch?v=6mTbuzafcII),
    [Clojure In Unity 3D: Functional Video Game Development](https://www.youtube.com/watch?v=tJr_TD1BtF0),
    [You can be a kernel hacker!](https://www.youtube.com/watch?v=0IQlpFWTFbM).

---
title: "This Month in Rust GameDev #4 - November 2019"
---

<!-- TODO: Check the post with markdownlint-->
<!-- TODO: sort entries from low-level to high level -->
<!-- TODO: wrap long lines -->

Welcome to the fourth issue of the Rust GameDev Workgroup’s
monthly newsletter.

[Rust] is a systems language pursuing the trifecta:
safety, concurrency, and speed.
These goals are well-aligned with game development.

We hope to build an inviting ecosystem for anyone wishing
to use Rust in their development process!
Want to get involved? [Join the Rust GameDev working group!][join]

[Rust]: https://rust-lang.org
[join]: https://github.com/rust-gamedev/wg#join-the-fun

<!--
Ideal section structure is:

```
### [Title]

![image/GIF description](image link)

A paragraph or two with a summary and [useful links].

_Discussions:
[/r/rust](https://reddit.com/r/rust/todo),
[twitter](https://twitter.com/todo/status/123456)_

[Title]: https://first.link
[useful links]: https://other.link
```

Discussion links are added only if they contain
some actual interesting discussions.

If needed, a section can be split into subsections with a "------" delimiter.
-->

## Game Updates

<!-- 
### Zemeroth

I finally found time to work on adding ability icons and descriptions to #Zemeroth!

Also, improving ZGui a little bit: better color handling, better offsets, layered widget layout, etc.

TODO: img: <https://twitter.com/ozkriff/status/1186688155384188928>

**TODO**: Move to 5th newsletter :(
-->

### Missile Defense Game (TODO: title?)

trying my hand at some gamedev in #rust using #ggez. Making a little missile defense game... Still tons i don't really know about the api and rust, but managed to hack together this neat litttle thingy! will post on itch this week

**TODO**: gif: <https://twitter.com/ELI7VHBO7/status/1190756730105294853>

### [Antorum]

![(TODO: local) battlefield after slaying some chonkrats](https://dooskington.com/images/devlogs/11-img0.jpeg)

[Antorum] is a multiplayer RPG where players build their characters and fight against the growing threats on the isle. The game server is authoritative and written in Rust, while the client is written in Unity/C#.

This month, @dooskington published a bunch of devlogs:

- [#11 "Drop Tables"](https://dooskington.com/dev-log/11);
- ???

[Antorum]: https://dooskington.com

### [Veloren][veloren]

**TODO**: img

[Veloren][veloren] is an open-world, open-source multiplayer voxel RPG.
The game is in an early stage of development, but is playable.

**TODO**: Some details

The full weekly devlogs "This Week In Veloren...":
[#40](https://veloren.net/devblog-40),
[#41](https://veloren.net/devblog-41),
[#42](https://veloren.net/devblog-42),
[#43](https://veloren.net/devblog-43).

<!-- Also, check out [/r/veloren subreddit](https://reddit.com/r/Veloren),
it's pretty active. -->

[veloren]: https://veloren.net

### MrVallentin's Voxels! (TODO: title)

(removed from October because only ine tweet)

TODO: other tweets?

<https://twitter.com/MrVallentin/status/1185616703536947204>

> - [@MrVallentin] tweeted a bunch of updates about their voxel engine:

[@MrVallentin]: https://twitter.com/MrVallentin

### Math Defense

**TODO**: img/gif

<https://twitter.com/512Avx/status/1192107281363673088>

<https://reddit.com/r/rust_gamedev/comments/ds3nha/math_defense_a_rust_ggez_game>

### Card game inspired by Arcomage

**TODO**: img/gif

<https://reddit.com/r/rust_gamedev/comments/dsm2dh/card_game_inspired_by_arcomage>

### [Tennis Academy]

**TODO**: img/gif

- <https://twitter.com/oliviff/status/1192178573488070659>

  🎉🎉 v0.0.5 is here! 🎉🎉

  🖱️click court to release players
  🏃‍♂️new type of player: athlete (athletes have white shorts and they can only play on a court of the colour of their t-shirt)
  📊2x score multiplier for t-shirt colours match

- <https://twitter.com/oliviff/status/1193096257591488512>

  v0.0.6 is here! 🔥🔥

  ⏰ players have patience levels
  👟 players leave when they get bored
  🎲 the game keeps track of players that leave

**TODO**: gui?

[@oliviff]: https://twitter.com/oliviff
[Tennis Academy]: https://iolivia.me/posts/6-months-of-rust-game-dev

### Sulis (TODO: title?)

<https://sulisgame.com/dev-modding/9-dev/15-managing-resources>

<https://reddit.com/r/rust_gamedev/comments/dt7e0x/the_basics_of_resource_management_in_sulis_an_rpg>

### #GitHubGameOff

**TODO**: _What is GitHubGameOff?_

- TODO: name

  - <https://twitter.com/fischspiele/status/1190431679330029568> (img)

    > I started to develop something for #GitHubGameOff in Rust, my goal is to finally create something with an ECS. I've always avoided it.
    > My first prototype just accidentally drew a line with the bullets. Kinda looks creative! 😉
    > Right now I'm using Tetra and the Specs crate.

  - <https://twitter.com/fischspiele/status/1195501514250506242> (img)

    > 🚀 The current state of my little experiment with Tetra and Specs, the way is rough and long and sadly the end date is getting closer and closer. #GitHubGameOff  #RustLang #GameDev

- TODO: Name

  <https://twitter.com/ZappedCow/status/1191501408832491520>

  DiR3Kt @ZappedCow
  > Life/environment simulator with a bit of rogue-like tossed in. My first #rustlang encounter. Using  @17cupsofcoffee 's Tetra mini engine.

### Amethyst Games

- [Azriel]

  <https://users.rust-lang.org/t/will-2-5d-moddable-action-game/28537/7>

  <https://azriel.im/will/2019/11/08/that-looks-good-on-ui>

- [@takeryo_eeic] is also working on a turn-based hexagonal game.

  - <https://twitter.com/takeryo_eeic/status/1192407134245228546> (GIF?)
  
    Автоматическая генерация карт и прокрутка!

  - <https://twitter.com/takeryo_eeic/status/1195263050896429057> (GIF!)

    Главное меню теперь доступно! Название Conquest!
    Игра, которая стремится стать победителем, используя древнего воина!

[Azriel]: https://azriel.im
[@takeryo_eeic]: https://twitter.com/takeryo_eeic

## Library & Tooling updates

### RustFest Workshop

<https://github.com/lislis/workshop-rust-games>

TODO: more info?

### [Pixels][pixels]

![TODO: local, smaller, desc](https://raw.githubusercontent.com/parasyte/pixels/master/img/pixels.png)

> [Pixels][pixels] is a tiny hardware-accelerated pixel frame buffer. crab

TODO: Uses wgpu.

[pixels]: https://github.com/parasyte/pixels

**TODO**: <https://reddit.com/r/rust_gamedev/comments/drunej/announcing_pixels_hardwareaccelerated_pixel_frame>

**TODO**: <https://twitter.com/kodewerx/status/1191585492975767552>

### WGPU

- <https://twitter.com/_photex_/status/1191371925588783104> TODO: img?

  > I'm ashamed to say I copied the fragment shader impl just to have something worth looking at.
  >
  > I gave up on a skyquad and just use a skybox again. It's just easier for me to understand right now. I have to math up a bit I think.

- <https://www.reddit.com/r/rust_gamedev/comments/drcje5/wgpu04_is_out>

  > wgpu is library in Rust that is meant to be the go-to solution for most graphics and compute needs.
  >
  > We've just released wgpu-rs version 0.4 on crates. It's based on gfx-hal-0.4 and includes the changes described on our blog earlier. A few notable additions are:
  >
  > proper Windows 7 support
  > support for multiple clients on the same GPU server
  > slimmed down Rendy dependencies (memory and descriptor)
  > new skybox example

### [skulpin]

**TODO**: img

> Skia + Vulkan = Skulpin

> I published a crate to make 2D rendering in @rustlang easy. "Skulpin" combines Skia and Vulkan to draw GPU-accelerated 2D graphics. Skia is the same 2D rendering library used by Chrome, Sublime Text, and Google's new UI framework Flutter @rust_gamedev

<https://twitter.com/aclysma/status/1191745653468094464>

[skulpin]: https://github.com/aclysma/skulpin

### Tetra

### Embark conf and newsletter

<https://mailchi.mp/8cddc3a5446e/embarkdev-001-november2019?e=98c8319312>

------

<https://reddit.com/r/rust/comments/du9g5d/rust_open_source_game_dev_stockholm_rust_meetup>

- <https://twitter.com/repi/status/1193156641170108416>
  
  > @repi Mr @h3r2tic‘s talk from our Stockholm Rust meetup “An unholy fusion of C++ and Rust in physx-rs”

  <https://youtube.com/watch?v=RxtXGeDHu0w>

- <https://twitter.com/repi/status/1192868367578910720>

  > Check out Jake’s talk about how and why we combine open source gamedev and Rust! (esp. if you are a C++ gamedev)

  <https://twitter.com/Ca1ne/status/1192866523972620289>

  <https://youtube.com/watch?v=lpOg2nl3kr0>

### [Creative Coding in Rust with Nannou](https://dev.to/deciduously/creative-coding-in-rust-with-nannou-1lbl)

<https://twitter.com/nannoucc/status/1192846417871671299>

<https://github.com/MindBuffer/nannou-av-signals>

TODO: other info?

### Ultraviolet 0.2

<https://reddit.com/r/rust/comments/dt9zhz/ultraviolet_02_released_introducing_bivectors_and>

<https://twitter.com/fu5ha/status/1192673122685612032>

> Released ultraviolet 0.2 for real today. Main feature is Rotors, with some usability improvements sprinkled around generally :) It's probably actually useful for people other than me now ;p

### glsl 2.1

<https://reddit.com/r/rust/comments/dtemif/glsl201_improved_performance_for_parsing>

### RLTK & [Rust Roguelike Tutorial][roguelike-book]

[The Roguelike Tutorial][roguelike-book] by [@blackfuture]
includes almost TODO chapters now and continues to grow!

- <https://twitter.com/herberticus/status/1192854228739526656>

  > Rust Roguelike update! C55 adds backtracking/persistent maps.
  > C56 Into the Caverns - adds a drunkard's walk based natural cave,
  > dynamic colored lighting, a cheat mode (for testing later maps)

**TODO**: Check other tweets

Some of the November's updates:

- ???
- ???

[roguelike-book]: http://bfnightly.bracketproductions.com/rustbook
[rltk-rs]: https://github.com/thebracket/rltk_rs
[@blackfuture]: https://patreon.com/blackfuture

### Pix

<https://reddit.com/r/rust/comments/du2nrr/pix_a_rust_image_viewer_built_with_piston>

<https://github.com/google/pix-image-viewer>

### concerns about the rust gamedev ecosystem

<https://twitter.com/obiwanus/status/1191658370165542912>

> A thread to express my concerns about the @rust_gamedev ecosystem (potentially also about the wider Rust ecosystem, but I have yet only looked at the former):
>
> First of all, I like Rust. Cargo is also a great tool that is extremely easy and fun to use. 1/7
>
> ...

### Amethyst TODO title

- <https://reddit.com/r/rust_gamedev/comments/dukikz/amethyst_legion_ecs_rfc>
- <https://reddit.com/r/rust/comments/duki8d/amethyst_legion_ecs_rfc>

### Other Library & Tooling News

<!-- See the comment in the `Other Game News` section. -->

## Popular Workgroup Issues in Github

<!-- Up to 10 links to interesting issues -->

- [#68 "Modding"](https://github.com/rust-gamedev/wg/issues/68)
- [#69 "Input Handling"](https://github.com/rust-gamedev/wg/issues/69)

## Meeting Minutes

<!-- Up to 10 most important notes + a link to the full details -->

[See all meeting issues][label_meeting] including full text notes
or [join the next meeting][join].

[label_meeting]: https://github.com/rust-gamedev/wg/issues?q=label%3Ameeting

## Requests for Contribution

<!-- Links to "good first issue"-labels or direct links to specific tasks -->

## Bonus

<!-- Bonus section to make the newsletter more interesting
and highlight events from the past. -->

**TODO**: <https://reddit.com/r/rust_gamedev/comments/a6ive6/adventures_of_pascal_penguin_is_complete>

------

That's all news for today, thanks for reading!

<!-- TODO: Move this to the begining of the post -->

Want something mentioned in the next newsletter?
[Send us a pull request][pr].
Feel free to send PRs about your own projects!

Also, subscribe to [@rust_gamedev on Twitter][@rust_gamedev]
or [/r/rust_gamedev subreddit][/r/rust_gamedev] if you want to receive fresh news!

<!--
TODO: Add real links and un-comment once this post is published
**Discussions of this post**:
[/r/rust](TODO),
[twitter](TODO).
-->

[/r/rust_gamedev]: https://reddit.com/r/rust_gamedev
[@rust_gamedev]: https://twitter.com/rust_gamedev
[pr]: https://github.com/rust-gamedev/rust-gamedev.github.io

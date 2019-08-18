<!-- https://hackmd.io/Hq9RU-TpQ2axsKtNdicPLw?both -->

<!-- TODO: I (@ozkriff) used Imgur links for the images,
but we need to place them in the repo' "images" dir for the real post -->

# This Month in Rust GameDev \#1 (August 2019)

Welcome to the inaugural issue of the Rust Game Development Workgroup’s
monthly (hopefully!) newsletter.

Rust is a systems language pursuing the trifecta:
safety, concurrency, and speed.
These goals are well-aligned with game development.

We hope to build an inviting ecosystem for anyone wishing
to use Rust in their development process!
Want to get involved? [Join the Rust Game Development working group!][join]

[join]: https://github.com/rust-gamedev/wg#join-the-fun

# News and Blog Posts

<!--
TODO: describe the format:
(This section should be filled with up to)
8-12 links with their own sections.
Image/Gif/Video, A paragraph or two with a summary and discussion links.
-->

## [Survey from the Rust Game Development Working Group][survey] 📋

Interested (maybe already invested?) in using Rust for game development? 🦀🕹️

Please set aside a brief moment to answer this short survey about
the current state of our GD ecosystem and what the GD working group
can do to nurture it. 🌱

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/cp2ib7/survey_from_the_rust_game_development_working/),
[twitter](https://twitter.com/rust_gamedev/status/1160659441550864384)_

[survey]: https://users.rust-lang.org/t/survey-from-the-rust-game-development-working-group/31270

## [This Month in Rustsim \#7 (June − July 2019)][rustsim_7]

[![ccd demo](https://i.imgur.com/So595E0.gif)](https://www.youtube.com/watch?v=EnjgJp9mKz0)

^ _click on the GIF to see the full YouTube video of the CCD demo_

Some highlights:

- nphysics 0.12 with [Continuous Collision-Detection (CCD)][ccd unity] support;
- ncollide 0.20 with non-linear time-of-impact computation and pipeline refactoring.

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/cmxdyk/this_month_in_rustsim_7_june_july_2019_nphysics/),
[twitter](https://twitter.com/rust_gamedev/status/1160659441550864384)_

[rustsim_7]: https://www.rustsim.org/blog/2019/08/01/this-month-in-rustsim
[ccd unity]: https://docs.unity3d.com/Manual/ContinuousCollisionDetection.html

------

Also, check out ["About the future of nphysics: a pure rust 2D and 3D real-time physics engine"][future]
\[[/r/rust](https://reddit.com/r/rust/comments/cm2858/about_the_future_of_nphysics_a_pure_rust_2d_and)].

[future]: https://www.patreon.com/posts/about-future-of-28917514

## Way of Rhea [Trailer][rhea trailer] + [Steam Wishlist][rhea steam] Announced

[![Part of the trailer](https://raw.githubusercontent.com/doppioslash/arewegameyet/master/static/assets/img/way_of_rhea.gif)][rhea trailer]

^ _click on the GIF to see the full trailer_

[A new trailer][rhea trailer] and the [Steam wishlist][rhea steam]
were published for "Way of Rhea"
by [Anthropic Studios](https://www.anthropicstudios.com).

> Way of Rhea is an upcoming puzzle platformer that takes place in a world
> where you can only interact with objects that match your current color.

Also, take a look at [this comment with a quick summary about implementation and tooling][rhea notes].

_Discussions:
[/r/rust_gamedev](https://reddit.com/r/rust_gamedev/comments/co8kqd/way_of_rhea_trailer_steam_wishlist_announced),
[twitter](https://twitter.com/AnthropicSt/status/1159867047821611010)_

[rhea steam]: https://store.steampowered.com/app/1110620/Way_of_Rhea
[rhea trailer]: https://youtube.com/watch?v=VIzqlI-gbAY
[rhea notes]: https://reddit.com/r/rust_gamedev/comments/co8kqd/way_of_rhea_trailer_steam_wishlist_announced/ewryjet

## [Veloren 0.3 released](https://veloren.net/devblog-26)

![Veloren screenshot](https://cdn.discordapp.com/attachments/523568428905398283/605117724171042930/screenshot_1564341608439.png)

Veloren is a multiplayer voxel RPG.

_**TODO**: Find the changelog, add some summary and project's links (downloads?)._

[This Week In Veloren 26](https://veloren.net/devblog-26/)

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/clziyh/veloren_03_the_multiplayer_voxel_rpg_written_in)_

## [RUZZT]

![RUZZT screenshot](https://pbs.twimg.com/media/EBETPNDXoAIZGlO?format=png&name=small)

[@yokljo](https://github.com/yokljo) published [RUZZT] - a [ZZT] game engine clone written in Rust.

> My wife and I wrote this as a fun exercise, and went a lot further with it
> than originally anticipated. We wanted to try to replicate the original
> game's behaviour by simply looking at it running in Dosbox and seeing
> if we could make RUZZT do the same thing.
> This means the code architecture is likely very different
> from the original game.
>
> Eventually we did get far enough that it seemed like a waste of time
> to try to guess how some specific things were implemented,
> so we used a disassembler to make sure various behaviours worked correctly.

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/cl9qhk/ruzzt_a_zzt_game_engine_clone_written_in_rust)_

[RUZZT]: https://github.com/yokljo/ruzzt
[ZZT]: https://en.wikipedia.org/wiki/ZZT

## [oxygengine-navigation] - Nav-mesh based navigation system for ECS games

![oxygengine-navigation interactive demo](https://i.imgur.com/YAukqIh.gif)

[oxygengine-navigation] is a crate to perform pathfinding on [navmeshes][navmesh wiki].
It's an ECS module (compatible with any SPECS engine)
and is a part of a bigger [Oxygen game engine][oxygengine].

Here's a [demo/example of the integration with Amethyst](https://github.com/PsichiX/Oxygengine/tree/master/demos/amethyst-integration).

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/co62an/navmesh_based_navigation_system_for_ecs_games),
[twitter](https://twitter.com/PsichiX/status/1159895167392002048)_

[navmesh wiki]: https://en.wikipedia.org/wiki/Navigation_mesh
[oxygengine]: https://github.com/PsichiX/oxygengine
[oxygengine-navigation]: https://github.com/PsichiX/Oxygengine/tree/master/oxygengine-navigation

## [Amethyst's Activity Report][amethyst news]

![amethyst logo](https://amethyst.cdn.prismic.io/amethyst%2F46fcadd9-f936-4959-ae26-5b1927d07a45_logo-standard.svg)

- [Amethyst v0.12 quietly released](https://github.com/amethyst/amethyst/releases/tag/v0.12.0)
  and now the project moves to two-week release cycle.
- 2D action platformer [Space Menace](https://github.com/amethyst/space-menace)
  by [@krankur](https://github.com/krankur) partnered with Amethyst to become
  an official showcase project ([announcement][space menace announcement]).

  ![Space Menace screenshot](https://i.imgur.com/l0C6SwR.png)
- Evoli releases [v0.2](https://github.com/amethyst/evoli/releases/tag/v0.2.0)
  and [moves into 3D](https://community.amethyst.rs/t/evoli-v0-2-video-log-retrospective/1007).
- New tools for 2D game development:
  [the Sheep spritesheet packer and Amethyst 2D Starter](https://amethyst.rs/posts/tools-for-2d-games).
- Scripting support [edges closer](https://community.amethyst.rs/t/scripting-what-do-we-need-to-get-there/958).
- Learning from Legion: [an ECS design discussion](https://community.amethyst.rs/t/legion-ecs-discussion/965).
- [Arsenal](https://github.com/katharostech/arsenal) - a Blender game engine
  built on Amethyst and Rust.
- [amethyst-imgui](https://github.com/amethyst/amethyst-imgui) and
  [Laminar](https://github.com/amethyst/laminar)
  (a semi-reliable UDP-based protocol for multiplayer games) steadily mature.
- [Rendy](https://github.com/amethyst/rendy) (rendering engine) is well
  [on its way towards web and OpenGL support](https://twitter.com/AmethystEngine/status/1159765804205957120).
- Atelier Editor underwent some [visual planning](https://github.com/amethyst/atelier-editor/issues/21).

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/coh2hy/amethyst_activity_report_july_2019),
[twitter](https://twitter.com/AmethystEngine/status/1160992752341016576)_

[amethyst news]: https://amethyst.rs/posts/activity-report-july-2019
[space menace announcement]: https://amethyst.rs/posts/space-menace-showcase

## [Embark's Rust open source crates and ecosystem tracking](http://embark.rs)

![Embark logo](https://raw.githubusercontent.com/EmbarkStudios/rust-ecosystem/master/media/embark-logo-bg.jpg)

Quote from the announcement:

> We've put together a tracking page for our Rust open source work,
> future ideas/plans, and issues that we've run into and want to improve on.
>
> [embark.rs](http://embark.rs)
>
> It is still pretty early, but hope it can be useful or of interest
> to see what we, a commercial games company,
> is planning and thinking about Rust.
>
> We are also open to collaborate with other companies or individuals,
> as well as sponsoring more open source work to improve and support the ecosystem.
> Feel free to reach out to us here or on
> [opensource@embark-studios.com](mailto:opensource@embark-studios.com)!

_Discussions:
[/r/rust](https://reddit.com/r/rust/comments/cr73zz/embarks_rust_open_source_crates_and_ecosystem),
[twitter](https://twitter.com/repi/status/1162361431355994112)_

[rust40]: https://www.youtube.com/watch?v=A3AdN7U24iU

------

Also, Embark has recently open-sourced [physx-rs] - [PhysX] bindings to Rust.

A cute [test example](https://github.com/EmbarkStudios/physx-rs/blob/001075c4e/physx/examples/ball_physx.rs):

![test example](https://i.redd.it/eam5pvls1ig31.png)

> Quite complex big C++ project to build & bind to (@h3r2tic did some magic).
> Eventually want full native Rust lib but PhysX is
> feature rich & performant today so nice to be able to use it!

_Discussions:
[/r/rust](https://old.reddit.com/r/rust/comments/cqbhif/embarkstudiosphysxrs_rust_binding_and_wrapper_for/),
[twitter](https://twitter.com/repi/status/1161645313532280835)_

[physx-rs]: https://github.com/EmbarkStudios/physx-rs
[PhysX]: https://github.com/NVIDIAGameWorks/PhysX

## Other news

<!-- TODO: describe the format: -->
<!-- Special section for other news on a one-liner format.
Main link, short summary, and optional discussion links in square brackets -->

- Vlad Zhukov shared on Twitter videos of [his space game prototype](https://twitter.com/VladZhukov0/status/1157636331629137921)
  and [his experiments with Voronoi diagram for procedural destruction](https://twitter.com/VladZhukov0/status/1162462543530643457).
- @Remco shared on Twitter
  [a video of hot reloading demonstration](https://twitter.com/wodannson/status/1157472538622078976)
  \[[/r/rust](https://reddit.com/r/rust/comments/cldaew/hot_reloading_of_function_bodies_in_rust),
  [/r/rust_gamedev](https://reddit.com/r/rust_gamedev/comments/cldajt/hot_reloading_of_function_bodies_in_rust/)].
- Devlog ["Charging Up"](https://azriel.im/will/2019/08/16/charging-up/) - characters in [Will]
  can now charge up by holding the Attack button;
- [droprate](https://crates.io/crates/droprate) - a crate for choosing
  outcomes based on a weighted probability map,
  aka more player-friendly random numbers
  \[[/r/rust](https://reddit.com/r/rust/comments/co3buo/ann_droprate_a_crate_for_randomly_choosing_things)].
- _**TODO**: Add info about Robo Instructus post release versions: 1.3, 1.4, 1.5_
- _**TODO**: add more news._

[Will]: https://azriel91.itch.io/will

# Popular Workgroup Issues in Github

- [\#23 "[Needed Crate] A pure rust SPIRV generator"](https://github.com/rust-gamedev/wg/issues/23)
- [\#25 "The state of math libraries"](https://github.com/rust-gamedev/wg/issues/25)
- [\#26 "[Tracker] Better windowing/graphics inter-operation"](https://github.com/rust-gamedev/wg/issues/26)
- [\#42 "[Discussion] A plan for crate stewardship"](https://github.com/rust-gamedev/wg/issues/42)
- [rust-gamedev.github.io](https://github.com/rust-gamedev/rust-gamedev.github.io):
  - [\#2 "Newsletter"](https://github.com/rust-gamedev/rust-gamedev.github.io/issues/2) (so meta!)
  - [\#4 "Create a rust-gamedev.gihub.io site"](https://github.com/rust-gamedev/rust-gamedev.github.io/issues/4)

# Meeting Minutes

**TODO**: _This section definitely needs more work.
List the most important notes and give a link to the full details._

- The workgroup recommends crates to have a minimum supported rust version policy
- winit/raw-window-handle
- Gfx-hal 0.3 is coming! (TODO: this is outdated now, remove)
- Web presence (Newsletter, arewegameyet.com)

[See all meeting issues](https://github.com/rust-gamedev/wg/issues?q=label%3Ameeting) including full text

# Requests for Contribution

- [winit](https://github.com/rust-windowing/winit):
  - [Issues tagged as "Good first issue" and “help wanted”][winit help wanted]
  - [Issues tagged as "Blocking a release"][winit blocking]
- _**TODO**: anything else to highlight here?_

[winit help wanted]: https://github.com/rust-windowing/winit/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3A%22status%3A+help+wanted%22+label%3A%22Good+first+issue%22
[winit blocking]: https://github.com/rust-windowing/winit/issues?utf8=✓&q=is%3Aissue+is%3Aopen+label%3A%22Blocking+a+release%22

# Bonus

Just an interesting Rust gamedev link from the past. :)

![A Snake's Tale logo](https://m12y.com/a-snakes-tale/press/images/logo.png)

On 2017.07.06 one of the first commercial Rust games ["A Snake's Tale"](https://m12y.com/a-snakes-tale)
by [Michael Fairley](https://twitter.com/michaelfairley)
was released:
[Steam](https://store.steampowered.com/app/654810/A_Snakes_Tale) (Windows, macOS, Linux),
[AppStore](https://itunes.apple.com/us/app/a-snakes-tale/id1211845149?mt=8&at=1001lnX5),
[Google Play](https://play.google.com/store/apps/details?id=com.m12y.asnakestale).

> A Snake's Tale is a puzzle game about snakes in cramped places.
> Clear a path to get to the hole, eat some eggs along the way,
> and make sure to press all the buttons.

[![Part of A snake's Tail's trailer](https://i.imgur.com/eRgcekm.gif)][snake trailer]

^ _click on the GIF to see [the full release trailer][snake trailer]_

A few posts about the game and how it was developed:

- ["I Made a Game in Rust"](https://michaelfairley.com/blog/i-made-a-game-in-rust)
- ["A Snake's Tale Postmortem"](https://michaelfairley.com/blog/a-snakes-tale-postmortem/)

[snake trailer]: https://www.youtube.com/watch?v=23pQmEuueNw

------

That's all news for today, thanks for reading!

Did we miss any interesting news? [Send us a pull request][pr].

Also, subscribe to [@rust_gamedev on Twitter][@rust_gamedev]
or [/r/rust_gamedev subreddit][/r/rust_gamedev] if you want to receive fresh news!

<!-- **Discussions of this post**: [/r/rust](), [twitter](). TODO: Un-comment once post is published -->

[/r/rust_gamedev]: https://reddit.com/r/rust_gamedev
[@rust_gamedev]: https://twitter.com/rust_gamedev
[pr]: https://github.com/rust-gamedev/rust-gamedev.github.io

---
title: "Setting a Goal"
date: 2020-10-30T23:55:04Z
draft: false
---

So I want to make a game. What kind, how big, and what does it look like when it's finished? Equally important: how do I make it and where do I put it in the end?

As I picked up this project I happened to come across the [Game Off 2020](https://itch.io/jam/game-off-2020), an annual game jam run [in collaboration between Github and Itch.io](https://github.blog/2020-10-27-github-game-off-2020/). It matches my timeframe and it makes some decisions for me, namely how to publish in the end, and what my hard deadline is. Bonus: every gamejam is themed, so that should be useful for inspiration. I signed up immediately.

### what kind of game do I want to make?

This one was oddly easy for me to answer: I want to work with a rhythm game mechanic. It has always been my favourite kind of game, so why not try to make one myself?

My definition of rhythm game may differ from yours... Some clear examples are [Audiosurf](https://en.wikipedia.org/wiki/Audiosurf), [PataPon](https://en.wikipedia.org/wiki/Patapon), Guitar Hero/Rock Band, and recently [Beat Sabre](https://www.beatsaber.com) and [64.0](https://gontzalve.itch.io/64-0). Some less clear examples that I still consider rhythm games to an extent are the 2D Mario games, when played by an experienced player who can fly through levels.

### how big, and what does it look like when it's finished?

Small. Wait... smol 🐱

Tiny, even.

The absolute minimum would be that it has some form of input interface, and there exists a win state which is not the default state. I might have very slightly higher aspirations than that, but I have only given myself a month, and, well, my implementation experience is not _exactly_ extensive.

### how do I make it?

There's a good question. I have experience in a few different coding languages, but little to no experience with game engines.

Taking a look at what's out there, I see that [Unity](https://unity.com/) is terrifically popular, particularly among those who want to (or already do) work in a large game dev team. The free asset libraries available through Unity are extensive, too.

I have previously used [Defold](https://defold.com/), and I was very impressed with how seamlessly it published work for different platforms and even hosted live releases all within the platform. The downside there was... Lua... It can't be escaped and it really is not my linguistic cup of tea. Even still, I was tempted to go the Defold route until I heard a bit more about...

[Godot](https://godotengine.org), which is an open source game engine. At first I thought, _this is going to be an engine built by nerds who want to build an engine, not games, and who are going to spend most of their time hyping it in dev fora._ I don't think I was entirely wrong about the efforts towards hype, and a solid number of projects available in the Godot template library are tech experiments. There are also what look like some great tools here for putting together at least simple games, and quite possibly very complex ones. GDScript (their custom scripting language) looks simple, and if I want to I can switch to C# or even further afield through language bindings. After a quick nose around reddit and twitter, it also looks like there is an active community of customers and contributors supporting each other, and the project has a modest patreon following which bodes well for it sticking around. This, plus my bias towards using and supporting open source projects where possible, made my decision for me.

Of course now I'm still making a game and learning a new game engine all over the course of one month. We won't even get started on putting together the framework for this blog.

### where do I put it in the end?

Finally, this one is easy as every submission to this game jam must be submitted to Itch.io. I plan to link to the released game (or to the interim releases of the game if that's how development goes) from the homepage of this blog once it's up.
---
layout: page
title: "projects"
date: 2016-02-07 19:31
comments: true
sharing: true
footer: true
---

###[Dialyxir](https://github.com/jeremyjh/dialyxir) [![Hex.pm](https://img.shields.io/hexpm/v/plug.svg)](https://hex.pm/packages/dialyxir)
This is a small project that I banged out initially in the course of a single day but it is definitely the one which has been the most useful to people and collected the most stars and contributions of my projects on Github. After a few years all the usage of it despite its long-standing deficiencies prompted a comprehensive overhaul and re-kindled my interest in Elixir in general. This adds a task to Mix (the [Elixir](http://elixir-lang.org) build tool) which helps one get started with using the [Erlang Dialyzer](http://www.erlang.org/doc/man/dialyzer.html) in Elixir projects.
  
<br><br>

###[Higher-LevelDB](https://github.com/jeremyjh/higher-leveldb) [![Hackage](https://budueba.com/hackage/higher-leveldb)](https://hackage.haskell.org/package/higher-leveldb)
This library provides a rich API for working with [LevelDB](https://github.com/google/leveldb) databases in Haskell. This was the first Haskell library that I developed and released and it probably shows to some extent, but it has seen the most usage based on Hackage download statistics.
<br><br>


###[Distributed Process Zookeeper](https://github.com/jeremyjh/distributed-process-zookeeper) [![Hackage](https://budueba.com/hackage/distributed-process-zookeeper)](https://hackage.haskell.org/package/distributed-process-zookeeper)
Provides service and node discovery for Cloud Haskell applications using a Zookeeper cluster for name registration, lookups and leader election. The core functionality this offers is the ability to have global singleton processes, which are automatically replaced from a pool of candidates on termination. I'm really proud of this implementation but haven't used it in a real project and it has not seen much interest from the community.
<br><br>

###[Free Agent](https://github.com/jeremyjh/free-agent)
This has been the vehicle I've used to learn Haskell but its not going to help anyone else yet. The idea is to make it easy to build a network of self-supporting application agent processes - agents that will talk to each other to distribute and share work as well as provide redundancy without any external dependencies or lots of configuration. I've done a lot of grinding on this code-base - writing the same few thousand lines over and over yet it still has a few design flaws, lacks critical features and is not ready for release. I've taken a break from it but could definitely pick it up again in the near future.

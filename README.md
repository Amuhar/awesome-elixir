# Awesome Elixir [![Build Status](https://api.travis-ci.org/h4cc/awesome-elixir.svg?branch=master)](https://travis-ci.org/h4cc/awesome-elixir) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of amazingly awesome Elixir libraries, resources, and shiny things inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

If you think a package should be added, please add a :+1: (`:+1:`) at the according issue or create a new one.

There are [other sites with curated lists of elixir packages](#other-awesome-lists) which you can have a look at.

- [Awesome Elixir](#awesome-elixir)
    - [Actors](#actors)
    - [Algorithms and Data structures](#algorithms-and-data-structures)
    - [Applications](#applications)
    - [Artificial Intelligence](#artificial-intelligence)
    - [Audio and Sounds](#audio-and-sounds)
    - [Authentication](#authentication)
    - [Authorization](#authorization)
    - [Behaviours and Interfaces](#behaviours-and-interfaces)
    - [Benchmarking](#benchmarking)
    - [Bittorrent](#bittorrent)
    - [BSON](#bson)
    - [Build Tools](#build-tools)
    - [Caching](#caching)
    - [Chatting](#chatting)
    - [Cloud Infrastructure and Management](#cloud-infrastructure-and-management)
    - [Code Analysis](#code-analysis)
    - [Command Line Applications](#command-line-applications)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [CSV](#csv)
    - [Date and Time](#date-and-time)
    - [Debugging](#debugging)
    
- [Resources](#resources)
    - [Books](#books)
    - [Community](#community)
    - [Editors](#editors)
    - [Newsletters](#newsletters)
    - [Other Awesome Lists](#other-awesome-lists)
    - [Reading](#reading)
    - [Screencasts](#screencasts)
    - [Styleguides](#styleguides)
    - [Websites](#websites)
- [Contributing](#contributing)

## Actors
*Libraries and tools for working with actors and such.*

* [dflow](https://github.com/dalmatinerdb/dflow) - Pipelined flow processing engine.
* [exactor](https://github.com/sasa1977/exactor) - Helpers for easier implementation of actors in Elixir.
* [exos](https://github.com/awetzel/exos) - A Port Wrapper which forwards cast and call to a linked Port.
* [flowex](https://github.com/antonmi/flowex) - Railway Flow-Based Programming with Elixir GenStage.
* [mon_handler](https://github.com/tattdcodemonkey/mon_handler) - A minimal GenServer that monitors a given GenEvent handler.
* [pool_ring](https://github.com/camshaft/pool_ring) - Create a pool based on a hash ring.
* [poolboy](https://github.com/devinus/poolboy) - A hunky Erlang worker pool factory.
* [pooler](https://github.com/seth/pooler) - An OTP Process Pool Application.
* [sbroker](https://github.com/fishcakez/sbroker) - Sojourn-time based active queue management library.
* [workex](https://github.com/sasa1977/workex) - Backpressure and flow control in EVM processes.
* [array](https://github.com/takscape/elixir-array) - An Elixir wrapper library for Erlang's array.
* [bitmap](https://github.com/hashd/bitmap-elixir) - Pure Elixir implementation of [bitmaps](https://en.wikipedia.org/wiki/Bitmap).

## Algorithms and Data structures
*Libraries and implementations of algorithms and data structures.*

* [array](https://github.com/takscape/elixir-array) - An Elixir wrapper library for Erlang's array.
* [aruspex](https://github.com/dkendal/aruspex) - Aruspex is a configurable constraint solver, written purely in Elixir.
* [bitmap](https://github.com/hashd/bitmap-elixir) - Pure Elixir implementation of [bitmaps](https://en.wikipedia.org/wiki/Bitmap).
* [blocking_queue](https://github.com/joekain/BlockingQueue) - BlockingQueue is a simple queue implemented as a GenServer. It has a fixed maximum length established when it is created.
* [bloomex](https://github.com/gmcabrita/bloomex) - A pure Elixir implementation of Scalable Bloom Filters.
* [clope](https://github.com/ayrat555/clope) - Elixir implementation of [CLOPE](http://www.inf.ufrgs.br/~alvares/CMP259DCBD/clope.pdf): A Fast and Effective Clustering Algorithm for Transactional Data.
* [combination](https://github.com/seantanly/elixir-combination) - Elixir library to generate combinations and permutations from Enumerable collection.
* [count_buffer](https://github.com/camshaft/count_buffer) - Buffer a large set of counters and flush periodically.
* [cuckoo](https://github.com/gmcabrita/cuckoo) - A pure Elixir implementation of [Cuckoo Filters](https://www.cs.cmu.edu/%7Edga/papers/cuckoo-conext2014.pdf).
* [cuid](https://github.com/duailibe/cuid) - Collision-resistant ids optimized for horizontal scaling and sequential lookup performance, written in Elixir.
* [data_morph](https://hex.pm/packages/data_morph) - Create Elixir structs from data.
* [dataframe](https://github.com/JordiPolo/dataframe) - Package providing functionality similar to Python's Pandas or R's data.frame().
* [datastructures](https://github.com/meh/elixir-datastructures) - A collection of protocols, implementations and wrappers to work with data structures.
* [dlist](https://github.com/stocks29/dlist) - Deque implementations in Elixir.
* [eastar](https://github.com/herenowcoder/eastar) - A* graph pathfinding in pure Elixir.
* [ecto_materialized_path](https://github.com/asiniy/ecto_materialized_path) - Tree structure, hierarchy and ancestry for the ecto models.
* [ecto_state_machine](https://github.com/asiniy/ecto_state_machine) - Finite state machine pattern implemented on Elixir and  adopted for Ecto.
* [elistrix](https://github.com/tobz/elistrix) - A latency / fault tolerance library to help isolate your applications from an uncertain world of slow or failed services.
* [erlang-algorithms](https://github.com/aggelgian/erlang-algorithms) - Implementations of popular data structures and algorithms.
* [exconstructor](https://github.com/appcues/exconstructor) - An Elixir library for generating struct constructors that handle external data with ease.
* [exfsm](https://github.com/awetzel/exfsm) - Simple elixir library to define a static FSM.
* [exkad](https://github.com/rozap/exkad) - A [kademlia](https://en.wikipedia.org/wiki/Kademlia) implementation in Elixir.
* [exmatrix](https://github.com/a115/exmatrix) - ExMatrix is a small library for working with matrices, originally developed for testing matrix multiplication in parallel.
* [ezcryptex](https://github.com/stocks29/ezcryptex) - Thin layer on top of Cryptex.
* [fnv](https://github.com/asaaki/fnv.ex) - Pure Elixir implementation of Fowler–Noll–Vo hash functions.
* [fsm](https://github.com/sasa1977/fsm) - Finite state machine as a functional data structure.
* [fuse](https://github.com/jlouis/fuse) - This application implements a so-called circuit-breaker for Erlang.
* [gen_fsm](https://github.com/pavlos/gen_fsm) - A generic finite state-machine - Elixir wrapper around OTP's gen_fsm.
* [graphmath](https://github.com/crertel/graphmath) - An Elixir library for performing 2D and 3D mathematics.
* [hash_ring_ex](https://github.com/reset/hash-ring-ex) - A consistent hash-ring implementation for Elixir.
* [hypex](https://github.com/zackehh/hypex) - Fast Elixir implementation of HyperLogLog.
* [indifferent](https://github.com/vic/indifferent) - Indifferent access for Elixir maps/list/tuples with custom key conversion.
* [isaac](https://github.com/arianvp/elixir-isaac) - Isaac is an elixir module for ISAAC: a fast cryptographic random number generator.
* [key2value](https://github.com/okeuday/key2value) - Erlang 2-way Set Associative Map.
* [lfsr](https://github.com/pma/lfsr) - Elixir implementation of a binary Galois Linear Feedback Shift Register.
* [loom](https://github.com/asonge/loom) - A CRDT library with δ-CRDT support.
* [luhn](https://github.com/ma2gedev/luhn_ex) - Luhn algorithm in Elixir.
* [lz4](https://github.com/szktty/erlang-lz4) - LZ4 bindings for Erlang for fast data compressing.
* [memoize](https://github.com/os6sense/DefMemo) - A memoization macro (defmemo) for elixir using a genserver backing store.
* [merkle_tree](https://github.com/yosriady/merkle_tree) - A Merkle hash tree implementation in Elixir.
* [minmaxlist](https://github.com/seantanly/elixir-minmaxlist) - Elixir library extending `Enum.min_by/2`, `Enum.max_by/2` and `Enum.min_max_by/2` to return a list of results instead of just one.
* [mmath](https://github.com/dalmatinerdb/mmath) - A library for performing math on number 'arrays' in binaries.
* [monad](https://github.com/rmies/monad) - Haskell inspired monads in Elixir stylish syntax.
* [monadex](https://github.com/rob-brown/MonadEx) - Upgrade your Elixir pipelines with monads.
* [murmur](https://github.com/gmcabrita/murmur) - A pure Elixir implementation of the non-cryptographic hash Murmur3.
* [natural_sort](https://github.com/DanCouper/natural_sort) - Elixir natural sort implementation for lists of strings.
* [navigation_tree](https://github.com/gutschilla/elixir-navigation-tree) - A navigation tree representation with helpers to generate HTML out of it.
* [parallel_stream](https://github.com/beatrichartz/parallel_stream) - A parallel stream implementation for Elixir.
* [paratize](https://github.com/seantanly/elixir-paratize) - Elixir library providing some handy parallel processing (execution) facilities that support configuring number of workers and timeout.
* [parex](https://github.com/StevenJL/parex) - Parallel Execute (Parex) is an Elixir module for executing multiple (slow) processes in parallel.
* [qex](https://github.com/princemaple/elixir-queue) - Wraps `:queue`, with improved API and `Inspect`, `Collectable` and `Enumerable` protocol implementations.
* [ratio](https://github.com/Qqwy/elixir-rational) - Adds Rational Numbers and allows them to be used in common arithmatic operations. Also supports conversion between Floats and Rational Numbers.
* [red_black_tree](https://github.com/SenecaSystems/red_black_tree) - Red-Black tree implementation in Elixir.
* [remodel](https://github.com/stavro/remodel) - An Elixir presenter package used to transform map structures.
* [rendezvous](https://github.com/timdeputter/Rendezvous) - Implementation of the Rendezvous or Highest Random Weight (HRW) hashing algorithm in Elixir.
* [rock](https://github.com/ayrat555/rock) - Elixir implementation of ROCK: A Robust Clustering Algorithm for Categorical Attributes.
* [sfmt](https://github.com/jj1bdx/sfmt-erlang/) - SIMD-oriented Fast Mersenne Twister (SFMT) for Erlang.
* [simhash](https://github.com/UniversalAvenue/simhash-ex) - Simhash implementation using Siphash and N-grams.
* [sorted_set](https://github.com/SenecaSystems/sorted_set) - Sorted Sets for Elixir.
* [spacesaving](https://github.com/rozap/spacesaving) - stream count distinct element estimation using the "space saving" algorithm.
* [structurez](https://github.com/hamiltop/structurez) - A playground for data structures in Elixir.
* [supermemo](https://github.com/edubkendo/supermemo) - An Elixir implementation of the [Supermemo 2 algorithm](https://www.supermemo.com/english/ol/sm2.htm).
* [tfidf](https://github.com/OCannings/tf-idf) - An Elixir implementation of term frequency–inverse document frequency.
* [the_fuzz](https://github.com/smashedtoatoms/the_fuzz) - Fuzzy string-matching algorithm implementations.
* [tinymt](https://github.com/jj1bdx/tinymt-erlang/) - Tiny Mersenne Twister (TinyMT) for Erlang.
* [trie](https://github.com/okeuday/trie) - Erlang Trie Implementation.
* [witchcraft](https://github.com/expede/witchcraft) - Common algebraic structures and functions for Elixir.
* [zipper_tree](https://github.com/Dkendal/zipper_tree) - Variadic arity tree with a zipper for Elixir.

## Applications
*Standalone applications.*
* [Alher](https://github.com/Queertoo/Alher) - Alexander is a rock-solid IRC bot written in Elixir with powerful plugins.
* [bpe](https://github.com/spawnproc/bpe) - Business Process Engine in Erlang.
* [Consolex](https://github.com/sivsushruth/consolex) - Consolex is a tool that allows you to attach a web based console to any mix project.
* [dragonfly_server](https://github.com/cloud8421/dragonfly-server) - Elixir app to serve Dragonfly images.
* [ExChat](https://github.com/tony612/exchat) - A Slack-like app by Elixir, Phoenix & React(redux).
* [Exon](https://github.com/tchoutri/Exon) - A “mess manager” developed in Elixir and provides a simple API to manage & document your stuff.
* [ExShop](https://github.com/authentic-pixels/ex-shop) - Digital goods shop & blog created using Phoenix framework.
* [Hydra](https://github.com/doomspork/hydra) - A multi-headed beast: API gateway, request cache, and data transformations.
* [majremind](https://bitbucket.org/Anwen/majremind) - A self-maintained database of your updated server which tells you which one needs to be updated.
* [medex](https://github.com/xerions/medex) - Medical Examination - application for register health check callbacks and represent their state via HTTP.
* [medusa_server](https://github.com/IcaliaLabs/medusa_server) - A simple cowboy web server written in Elixir to stack images.
* [n2o](https://github.com/synrc/n2o) - WebSocket Application Server.
* [Nvjorn](https://github.com/tchoutri/Nvjorn) - A multi-protocol network services monitor written in Elixir using Poolboy.
* [Phoenix Battleship](https://github.com/bigardone/phoenix-battleship) - The Good Old game built with Elixir, Phoenix Framework, React and Redux.
* [Phoenix Toggl](https://github.com/bigardone/phoenix-toggl) - Toggl tribute done in Elixir, Phoenix Framework, React and Redux.
* [Phoenix Trello](https://github.com/bigardone/phoenix-trello) - Trello tribute done in Elixir, Phoenix Framework, React and Redux.
* [poxa](https://github.com/edgurgel/poxa) - Open Pusher implementation, compatible with Pusher libraries.
* [Queerlink](https://github.com/Queertoo/Queerlink) - A simple yet efficient URL shortening service written in Elixir.
* [Sprint Poker](https://github.com/elpassion/sprint-poker) - Online estimation tool for Agile teams, written using Elixir Lang, Phoenix Framework and React.
* [Startup Job](https://github.com/tsurupin/job_search) - An umbrella project to search startup jobs scraped from websites written in Elixir/Phoenix and React/Redux.
* [tty2048](https://github.com/lexmag/tty2048) - Terminal-based 2048 game written in Elixir.

## Artificial Intelligence
*When your code becomes smarter than you.*

* [Exnn](https://github.com/zampino/exnn) - Evolutive Neural Networks framework à la G.Sher written in Elixir.
* [Neat-Ex](https://gitlab.com/onnoowl/Neat-Ex) - An Elixir implementation of the NEAT algorithm.
* [simple_bayes](https://github.com/fredwu/simple_bayes) - A Simple Bayes / Naive Bayes implementation in Elixir.

## Audio and Sounds
*Libraries working with sounds and tones.*

* [erlaudio](https://github.com/asonge/erlaudio) - Erlang PortAudio bindings.
* [synthex](https://github.com/bitgamma/synthex) - A signal synthesis library.

## Authentication
*Libraries for implementing authentication schemes.*

* [aeacus](https://github.com/zmoshansky/aeacus) - A simple configurable identity/password authentication module (Compatible with Ecto/Phoenix).
* [apache_passwd_md5](https://github.com/kevinmontuori/Apache.PasswdMD5) - Apache/APR Style Password Hashing.
* [aws_auth](https://github.com/bryanjos/aws_auth) - AWS Signature Version 4 Signing Library for Elixir.
* [blackbook](https://github.com/bigmachine-io/blackbook) - All-in-one membership/authentication system for Elixir.
* [coherence](https://github.com/smpallen99/coherence) - Coherence is a full featured, configurable authentication system for Phoenix.
* [doorman](https://github.com/BlakeWilliams/doorman) - Tools to make Elixir authentication simple and flexible.
* [github_oauth](https://github.com/lidashuang/github_oauth) - A simple github oauth library.
* [goth](https://github.com/peburrows/goth) - OAuth 2.0 library for server to server applications via Google Cloud APIs.
* [guardian](https://github.com/ueberauth/guardian) - An authentication framework for use with Elixir applications.
* [htpasswd](https://github.com/kevinmontuori/Apache.htpasswd) - Apache htpasswd file reader/writer in Elixir.
* [mojoauth](https://github.com/mojolingo/mojo-auth.ex) - MojoAuth implementation in Elixir.
* [oauth2](https://github.com/scrogson/oauth2) - An OAuth 2.0 client library for Elixir.
* [oauth2cli](https://github.com/mgamini/oauth2cli-elixir) - Simple OAuth2 client written for Elixir.
* [oauth2ex](https://github.com/parroty/oauth2ex) - Another OAuth 2.0 client library for Elixir.
* [oauther](https://github.com/lexmag/oauther) - An OAuth 1.0 implementation for Elixir.
* [openmaize](https://github.com/riverrun/openmaize) - Authentication library for Elixir.
* [sesamex](https://github.com/khusnetdinov/sesamex) - Another simple and flexible authentication solution in 5 minutes!.
* [shield](https://github.com/mustafaturan/shield) - An OAuth 2.0 provider library and implementation for Phoenix Framework.
* [sigaws](https://github.com/handnot2/sigaws) - AWS Signature V4 signing and verification library ([Doc](https://hexdocs.pm/sigaws/Sigaws.html)).
* [ueberauth](https://github.com/ueberauth/ueberauth) - An Elixir Authentication System for Plug-based Web Applications.
* [ueberauth_active_directory](https://github.com/torrick/ueberauth_active_directory) - Uberauth strategy for Active Directory authentication.
* [ueberauth_auth0](https://hex.pm/packages/ueberauth_auth0) - An Ueberauth strategy for using Auth0 to authenticate your users.
* [ueberauth_cas](https://github.com/marceldegraaf/ueberauth_cas) - Central Authentication Service strategy for Überauth.
* [ueberauth_facebook](https://github.com/ueberauth/ueberauth_Facebook) - Facebook OAuth2 Strategy for Überauth.
* [ueberauth_foursquare](https://github.com/borodiychuk/ueberauth_foursquare) - Foursquare OAuth2 Strategy for Überauth.
* [ueberauth_github](https://github.com/ueberauth/ueberauth_github) - A GitHub strategy for Überauth.
* [ueberauth_google](https://github.com/ueberauth/ueberauth_google) - A Google strategy for Überauth.
* [ueberauth_identity](https://github.com/ueberauth/ueberauth_identity) - A simple username/password strategy for Überauth.
* [ueberauth_line](https://github.com/alexfilatov/ueberauth_line) - LINE Strategy for Überauth.
* [ueberauth_microsoft](https://github.com/swelham/ueberauth_microsoft) - A Microsoft strategy for Überauth.
* [ueberauth_slack](https://github.com/ueberauth/ueberauth_slack) - A Slack strategy for Überauth.
* [ueberauth_twitter](https://github.com/ueberauth/ueberauth_twitter) - Twitter Strategy for Überauth.
* [ueberauth_vk](https://github.com/sobolevn/ueberauth_vk) - [vk.com](https://vk.com) Strategy for Überauth.
* [ueberauth_weibo](https://github.com/he9qi/ueberauth_weibo) - [Weibo](https://weibo.com) OAuth2 Strategy for Überauth.

## Authorization
*Libraries for implementing Authorization handling.*

* [authorize](https://github.com/jfrolich/authorize) - Rule based authorization, for advanced authorization rules.
* [bodyguard](https://github.com/schrockwell/bodyguard) - A flexible authorization library for Phoenix applications.
* [canada](https://github.com/jarednorman/canada) - A simple authorization library that provides a friendly interface using declarative permission rules.
* [canary](https://github.com/cpjk/canary) - An authorization library for Elixir applications that restricts what resources the current user is allowed to access.

## Behaviours and Interfaces
*Definitions how something should behave, like Interfaces from OOP-World*

* [connection](https://github.com/fishcakez/connection) - Connection behaviour for connection processes. The API is superset of the GenServer API.
* [gen_state_machine](https://github.com/antipax/gen_state_machine) - Elixir wrapper for gen_statem.
* [stockastic](https://github.com/shanewilton/stockastic) - Simple Elixir wrapper for the Stockfighter API.

## Benchmarking
*Running code to see how long it takes, which is faster and/or if improvements have been made.*

* [benchee](https://github.com/PragTob/benchee) - Easy and extensible benchmarking in Elixir!
* [benchfella](https://github.com/alco/benchfella) - Benchmarking tool for Elixir.
* [bmark](https://github.com/joekain/bmark) - A benchmarking tool for Elixir.

## Bittorrent
*Sharing is caring with Elixir*

* [bento](https://github.com/folz/bento) - An incredibly fast, correct, pure-Elixir Bencoding library.
* [tracker_request](https://github.com/alehander42/tracker_request) - Dealing with bittorrent tracker requests and responses.
* [wire](https://github.com/alehander42/wire) - Encode and decode bittorrent peer wire protocol messages with Elixir.

## BSON
*Libraries and implementations working with BSON.*

* [BSONMap](https://github.com/Nebo15/bsoneach) - Elixir package that applies a function to each document in a BSON file and has a low memory consumption.

## Build Tools
*Project build and automation tools.*

* [active](https://github.com/synrc/active) - Recompilation and Reloading on FileSystem changes.
* [coffee_rotor](https://github.com/HashNuke/coffee_rotor) - Rotor plugin to compile CoffeeScript files.
* [dismake](https://github.com/jarednorman/dismake) - Mix compiler running make.
* [etude](https://github.com/exstruct/etude) - Parallel computation coordination compiler for Erlang/Elixir.
* [ExMake](https://github.com/lycus/exmake) - A modern, scriptable, dependency-based build tool loosely based on Make principles.
* [Exscript](https://github.com/liveforeverx/exscript) - Elixir escript library.
* [mad](https://github.com/synrc/mad) - Small and Fast Rebar Replacement.
* [pc](https://github.com/blt/port_compiler) - A rebar3 port compiler.
* [reaxt](https://github.com/awetzel/reaxt) - React template into your Elixir application for server rendering.
* [rebar3_abnfc_plugin](https://github.com/surik/rebar3_abnfc_plugin) - Rebar3 abnfc compiler.
* [rebar3_asn1_compiler](https://github.com/pyykkis/rebar3_asn1_compiler) - Plugin for compiling ASN.1 modules with Rebar3.
* [rebar3_auto](https://github.com/vans163/rebar3_auto) - Rebar3 plugin to auto compile and reload on file change.
* [rebar3_diameter_compiler](https://github.com/carlosedp/rebar3_diameter_compiler) - Compile diameter .dia files in rebar3 projects.
* [rebar3_eqc](https://github.com/kellymclaughlin/rebar3-eqc-plugin) - A rebar3 plugin to enable the execution of Erlang QuickCheck properties.
* [rebar3_exunit](https://github.com/processone/rebar3_exunit) - A plugin to run Elixir ExUnit tests from rebar3 build tool.
* [rebar3_idl_compiler](https://github.com/sebastiw/rebar3_idl_compiler) - This is a plugin for compiling Erlang IDL files using Rebar3.
* [rebar3_live](https://github.com/pvmart/rebar3_live) - Rebar3 live plugin.
* [rebar3_neotoma_plugin](https://github.com/zamotivator/rebar3_neotoma_plugin) - Rebar3 neotoma (Parser Expression Grammar) compiler.
* [rebar3_protobuffs](https://github.com/benoitc/rebar3_protobuffs) - rebar3 protobuffs provider using protobuffs from Basho.
* [rebar3_run](https://github.com/tsloughter/rebar3_run) - Run a release with one simple command.
* [rebar3_yang_plugin](https://github.com/surik/rebar3_yang_plugin) - Rebar3 yang compiler.
* [reltool_util](https://github.com/okeuday/reltool_util) - Erlang reltool utility functionality application.
* [relx](https://github.com/erlware/relx) - A release assembler for Erlang.
* [remix](https://github.com/AgilionApps/remix) - Automatic recompilation of Mix code on file change.
* [rotor](https://github.com/HashNuke/rotor) - Super-simple build system for Elixir.
* [sass_elixir](https://github.com/zamith/sass_elixir) - A sass plugin for Elixir projects.

## Caching
*Libraries for caching data.*

* [cachex](https://github.com/zackehh/cachex) - A powerful caching library for Elixir with a wide featureset.
* [con_cache](https://github.com/sasa1977/con_cache) - ConCache is an ETS based key/value storage.
* [elixir_locker](https://github.com/tsharju/elixir_locker) - Locker is an Elixir wrapper for the locker Erlang library that provides some useful libraries that should make using locker a bit easier.
* [jc](https://github.com/jr0senblum/jc) - In-memory, distributable cache with pub/sub, JSON-query and consistency support.
* [locker](https://github.com/wooga/locker) - Atomic distributed "check and set" for short-lived keys.
* [lru_cache](https://github.com/arago/lru_cache) - Simple LRU Cache, implemented with ets.
* [stash](https://github.com/zackehh/stash) - A straightforward, fast, and user-friendly key/value store.

## Chatting
*Chatting via IRC, Slack, HipChat and other systems using Elixir.*

* [alice](https://github.com/alice-bot/alice) - A Slack bot framework for Elixir.
* [chatty](https://github.com/alco/chatty) - A basic IRC client that is most useful for writing a bot.
* [cog](https://github.com/operable/cog) - Cog is an open chatops platform that gives you a secure, collaborative command line right in your chat window.
* [ExIrc](https://github.com/bitwalker/exirc) - IRC client adapter for Elixir projects.
* [ExMustang](https://github.com/techgaun/ex_mustang) - A simple, clueless slackbot and collection of responders.
* [Guri](https://github.com/elvio/guri) - Automate tasks using chat messages.
* [hedwig](https://github.com/hedwig-im/hedwig) - XMPP Client/Bot Framework for Elixir.
* [kaguya](https://github.com/Luminarys/Kaguya) - A small, powerful, and modular IRC bot.
* [slacker](https://github.com/koudelka/slacker) - A bot library for the Slack chat service.
* [yocingo](https://github.com/Yawolf/yocingo) - Create your own Telegram Bot.

## Cloud Infrastructure and Management
*Applications, tools and libraries for your own cloud service.*

* [aws](https://github.com/jkakar/aws-elixir) - AWS clients for Elixir.
* [Cloudi](http://cloudi.org/) - CloudI is for back-end server processing tasks that require soft-realtime transaction.
* [discovery](https://github.com/undeadlabs/discovery) - An OTP application for auto-discovering services with Consul.
* [erlcloud](https://github.com/erlcloud/erlcloud) - Cloud Computing library for Erlang (Amazon EC2, S3, SQS, SimpleDB, Mechanical Turk, ELB).
* [ex_aws](https://github.com/CargoSense/ex_aws) - AWS client, supporting Dynamo, Kinesis, Lambda, SQS, and S3.
* [ex_riak_cs](https://github.com/ayrat555/ex_riak_cs) - Riak CS API client.
* [fleet_api](https://github.com/jordan0day/fleet-api) - A simple wrapper for the Fleet (CoreOS) API. Can be used with etcd tokens or via direct node URLs.
* [Gandi](https://github.com/Ahamtech/elixir-Gandi) - Gandi Wrapper for Leaseweb infrastructure.
* [IElixir](https://github.com/pprzetacznik/IElixir) - Jupyter's kernel for Elixir programming language.
* [Kubex](https://github.com/ingerslevio/kubex) - Kubernetes client and integration for Elixir, written in pure Elixir.
* [Leaseweb](https://github.com/Ahamtech/elixir-leaseweb) - Elixir Wrapper for Leaseweb infrastructure.
* [libcluster](https://github.com/bitwalker/libcluster) - Automatic cluster formation/healing for Elixir applications.
* [nodefinder](https://github.com/okeuday/nodefinder) - Strategies for automatic node discovery in Erlang.
* [nomad](https://github.com/sashaafm/nomad) - Create cloud portable Elixir and Phoenix apps. Write once, use everywhere!
* [oceanex](https://github.com/mustafaturan/oceanex) - Digital Ocean API client.
* [sidejob](https://github.com/basho/sidejob) - Parallel worker and capacity limiting library for Erlang.
* [sidetask](https://github.com/PSPDFKit-labs/sidetask) - SideTask is an alternative to Task.Supervisor using Basho's sidejob library with parallelism and capacity limiting.
* [skycluster](https://github.com/Nebo15/skycluster) - Automatic Erlang cluster formation, messaging and management for Elixir/Erlang applications. Integrated with Kubernetes.

## Code Analysis
*Libraries and tools for code base analysis, parsing, and manipulation.*

* [belvedere](https://github.com/nirvana/belvedere) - An example of CircleCI integration with Elixir.
* [coverex](https://github.com/alfert/coverex) - Coverage Reports for Elixir.
* [credo](https://github.com/rrrene/credo) - A static code analysis tool with a focus on code consistency and teaching Elixir.
* [dialyxir](https://github.com/jeremyjh/dialyxir) - Mix tasks to simplify use of Dialyzer in Elixir projects.
* [dogma](https://github.com/lpil/dogma) - A code style linter for Elixir, powered by shame.
* [excoveralls](https://github.com/parroty/excoveralls) - Coverage report tool for Elixir with coveralls.io integration.
* [exprof](https://github.com/parroty/exprof) - A simple code profiler for Elixir, using eprof.

## Command Line Applications
*Anything helpful for building CLI applications.*

* [anubis](https://github.com/bennyhallett/anubis) - Command-Line application framework for Elixir.
* [firex](https://github.com/msoedov/firex) - Firex is a library for automatically generating command line interfaces (CLIs) from an elixir module.
* [getopt](https://github.com/jcomellas/getopt) - Command-line options parser for Erlang.
* [loki](https://github.com/khusnetdinov/loki) - Library for creating interactive command-line application.
* [meld](https://github.com/Lac/meld) - Create global binaries from mix tasks.
* [optimus](https://github.com/savonarola/optimus) - Command-line option parser for Elixir inspired by [clap.rs](https://clap.rs/).
* [progress_bar](https://github.com/henrik/progress_bar) - Command-line progress bars and spinners.
* [table_rex](https://github.com/djm/table_rex) - Generate configurable ASCII style tables for display.
* [tabula](https://github.com/aerosol/tabula) - Pretty print list of Ecto query results / maps in ascii tables (GitHub Markdown/OrgMode).

## Configuration
*Libraries and tools working with configurations*

* [confex](https://github.com/Nebo15/confex) - Helper module that provides a nice way to read environment configuration at runtime.
* [configparser_ex](https://github.com/easco/configparser_ex) - A simple Elixir parser for the same kind of files that Python's configparser library handles.
* [conform](https://github.com/bitwalker/conform) - Easy release configuration for Elixir apps.
* [dotenv](https://github.com/avdi/dotenv_elixir) - A port of dotenv to Elixir.
* [ex_conf](https://github.com/phoenixframework/ex_conf) - Simple Elixir Configuration Management.
* [figaro](https://github.com/trestrantham/ex_figaro) - Simple Elixir project configuration.
* [figaro_elixir](https://github.com/KamilLelonek/figaro-elixir) - Environmental variables manager for Elixir.
* [sweetconfig](https://github.com/d0rc/sweetconfig) - Read YAML configuration files from any point at your app.
* [weave](https://github.com/GT8Online/weave) - JIT configuration loader that works with Kubernetes and Docker Swarm.

## Cryptography
*Encrypting and decrypting data*

* [aescmac](https://github.com/kleinernik/elixir-aes-cmac) - AES CMAC ([RFC 4493](https://tools.ietf.org/html/rfc4493)) in Elixir.
* [cipher](https://github.com/rubencaro/cipher) - Elixir crypto library to encrypt/decrypt arbitrary binaries.
* [cloak](https://github.com/danielberkompas/cloak) - Cloak makes it easy to use encryption with Ecto.
* [comeonin](https://github.com/riverrun/comeonin) - Password authorization (bcrypt, pbkdf2_sha512 and one-time passwords) library for Elixir.
* [crypto_rsassa_pss](https://github.com/potatosalad/erlang-crypto_rsassa_pss) - RSASSA-PSS Public Key Cryptographic Signature Algorithm for Erlang.
* [elixir_tea](https://github.com/keichan34/elixir_tea) - TEA implementation in Elixir.
* [ex_bcrypt](https://github.com/manelli/ex_bcrypt) - Elixir wrapper for the OpenBSD bcrypt password hashing algorithm.
* [ex_crypto](https://github.com/ntrepid8/ex_crypto) - Elixir wrapper for Erlang `crypto` and `public_key` modules. Provides sensible defaults for many crypto functions to make them easier to use.
* [exgpg](https://github.com/rozap/exgpg) - Use gpg from Elixir.
* [pot](https://github.com/yuce/pot) - Erlang library for generating one time passwords compatible with Google Authenticator.
* [rsa](https://github.com/trapped/elixir-rsa) - `public_key` cryptography wrapper for Elixir.
* [rsa_ex](https://github.com/anoskov/rsa-ex) - Library for working with RSA keys.
* [siphash-elixir](https://github.com/zackehh/siphash-elixir) - Elixir implementation of the SipHash hash family.
* [tea_crypto](https://github.com/keichan34/tea_crypto_erl) - Tiny Encryption Algorithm implementation.

## CSV
*Libraries and implementations working with CSV.*

* [cesso](https://github.com/meh/cesso) - CSV handling library for Elixir.
* [csv](https://github.com/beatrichartz/csv) - CSV Decoding and Encoding for Elixir.
* [csvlixir](https://github.com/jimm/csvlixir) - A CSV reading/writing application for Elixir.
* [ex_csv](https://github.com/CargoSense/ex_csv) - CSV for Elixir.
* [nimble_csv](https://github.com/plataformatec/nimble_csv) - A simple and fast CSV parsing and dumping library for Elixir.

## Date and Time
*Libraries for working with dates and times.*

* [block_timer](https://github.com/adamkittelson/block_timer) - Macros to use :timer.apply_after and :timer.apply_interval with a block.
* [calendar](https://github.com/lau/calendar) - Calendar is a date and time library for Elixir.
* [chronos](https://github.com/nurugger07/chronos) - An Elixir date/time library.
* [cronex](https://github.com/jbernardo95/cronex) - Cron like system you can mount in your supervision tree.
* [crontab](https://github.com/jshmrtn/crontab) - A Cron Expressions Parser, Composer & Date Candidate Finder.
* [ex_ical](https://github.com/fazibear/ex_ical) - ICalendar parser.
* [filtrex](https://github.com/rcdilorenzo/filtrex) - A library for performing and validating complex SQL-like filters from a client (e.g. smart filters).
* [good_times](https://github.com/DevL/good_times) - Expressive and easy to use datetime functions.
* [jalaali](https://github.com/jalaali/elixir-jalaali) - Jalaali calendar implementation for Elixir.
* [milliseconds](https://github.com/davebryson/elixir_milliseconds) - Simple library to work with milliseconds in Elixir.
* [moment](https://github.com/atabary/moment) - Parse, validate, manipulate, and display dates in Elixir.
* [quantum](https://github.com/c-rack/quantum-elixir) - Cron-like job scheduler for Elixir applications.
* [repeatex](https://github.com/rcdilorenzo/repeatex) - Natural language parsing for repeating dates.
* [timelier](https://github.com/ausimian/timelier) - A cron-style scheduler for Elixir.
* [timex](https://github.com/bitwalker/timex) - Easy to use Date and Time modules for Elixir.
* [timex_interval](https://github.com/atabary/timex-interval) - A date/time interval library for Elixir projects, based on Timex.
* [tzdata](https://github.com/lau/tzdata) - The timezone database in Elixir.

## Debugging
*Libraries and tools for debugging code and applications.*

* [beaker](https://github.com/hahuang65/beaker) - Statistics and Metrics library for Elixir.
* [booter](https://github.com/eraserewind/booter) - Boot an Elixir application, step by step.
* [dbg](https://github.com/fishcakez/dbg) - Distributed tracing for Elixir.
* [eflame](https://github.com/proger/eflame) - Flame Graph profiler for Erlang.
* [eh](https://github.com/Frost/eh) - A tool to look up Elixir documentation from the command line.
* [eper](https://github.com/massemanet/eper) - Erlang performance and debugging tools.
* [ether](https://github.com/maarek/ether) - Ether provides functionality to hook Elixir into the Erlang debugger.
* [ex_debug_toolbar](https://github.com/kagux/ex_debug_toolbar) - A toolbar for Phoenix projects to interactively debug code and display useful information about requests: logs, timelines, database queries etc.
* [exrun](https://github.com/liveforeverx/exrun) - Distributed tracing for Elixir with rate limiting and simple macro-based interface.
* [observer_cli](https://github.com/zhongwencool/observer_cli) - Visualize Elixir & Erlang nodes on the command line, it aims to helpe developers debug production systems.
* [quaff](https://github.com/qhool/quaff) - The Debug module provides a simple helper interface for running Elixir code in the erlang graphical debugger.
* [visualixir](https://github.com/koudelka/visualixir) - A process visualizer for remote BEAM nodes.

# Resources
Various resources, such as books, websites and articles, for improving your Elixir development skills and knowledge.

## Books
*Fantastic books and e-books.*

* [Adopting Elixir](https://pragprog.com/book/tvmelixir/adopting-elixir) - Bring Elixir into your company, with real-life strategies from the people who built Elixir and use it successfully at scale. This book has all the information you need to take your application from concept to production (2017).
* [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) - Upgrade your web API to GraphQL, leveraging its flexible queries to empower your users, and its declarative structure to simplify your code (2017).
* [Elixir Cookbook](https://www.packtpub.com/application-development/elixir-cookbook) - This book is a set of recipes grouped by topic by Paulo A Pereira (2015).
* [Elixir in Action](https://www.manning.com/books/elixir-in-action) - A brief intro to the language followed by a more detailed look at building production-ready systems in Elixir by Saša Jurić (2015).
* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Introduction to Erlang and Elixir in the context of functional concepts by Wolfgang Loder (2016).
* [Erlang in Anger](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war by Fred Hebert (2014).
* [Functional Web Development with Elixir, OTP, and Phoenix](https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix) - Open doors to powerful new techniques that will get you thinking about web development in fundamentally new ways (2017).
* [Getting Started - Elixir](https://github.com/potatogopher/elixir-getting-started) - PDF, MOBI, and EPUB documents for Elixir's Getting Started tutorial (2016).
* [Introducing Elixir ](http://shop.oreilly.com/product/0636920030584.do) - A gentle introduction to the language, with lots of code examples and exercises by Simon St. Laurent and J. David Eisenberg (2013).
* [Learn Functional Programming with Elixir](https://pragprog.com/book/cdc-elixir/learn-functional-programming-with-elixir) - Don’t board the Elixir train with an imperative mindset! To get the most out of functional languages, you need to think functionally (2017).
* [Metaprogramming Elixir: Write Less Code, Get More Done (and Have Fun!)](https://pragprog.com/book/cmelixir/metaprogramming-elixir) - Thorough explanation on how to exploit Elixir's metaprogramming capabilities to improve your Elixir coding by Chris McCord (2015).
* [Programming Elixir](https://pragprog.com/book/elixir/programming-elixir) - The book provides introduction to functional and concurrent programming with Elixir by Dave Thomas (2014).
* [Programming Phoenix](https://pragprog.com/book/phoenix/programming-phoenix) - Definitive guide to build web applications with the Phoenix framework by Chris McCord, José Valim and Bruce Tate (2015).
* [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook) - A book for learning Elixir and OTP through small to medium-sized projects by Benjamin Tan Wei Hao (2014).
* [Études for Elixir](http://chimera.labs.oreilly.com/books/1234000001642) - A collection of exercises to program in Elixir by J. David Eisenberg (2013) ([Github Repo](https://github.com/oreillymedia/etudes-for-elixir)).

## Community
*Getting in contact with the community via chat or mailinglist.*

* [#elixir-lang](http://webchat.freenode.net/?channels=elixir-lang) - The IRC Channel #elixir-lang on Freenode.
* [Elixir Forum](https://elixirforum.com/) - Community run discussion forums for all things Elixir.
* [elixir-lang-core](https://groups.google.com/d/forum/elixir-lang-core) - Mailinglist for Elixir Core development, use "talk" for questions and general discussions.
* [elixir-lang-talk](https://groups.google.com/d/forum/elixir-lang-talk) - Official Elixir Mailinglist for questions and discussions.
* [ElixirSlack](https://elixir-slackin.herokuapp.com/) - Elixir Slack Community.

## Editors
*Editors and IDEs useable for Elixir/Erlang*

* [Alchemist](https://github.com/tonini/alchemist.el) - Elixir Tooling Integration Into Emacs.
* [Alchemist-Server](https://github.com/tonini/alchemist-server) - Editor/IDE independent background server to inform about Elixir mix projects.
* [Alchemist.vim](https://github.com/slashmili/alchemist.vim) - Elixir Tooling Integration Into Vim.
* [Atom](https://atom.io/packages/language-elixir) - Elixir language support for Atom.
* [atom-elixir](https://github.com/msaraiva/atom-elixir) - An Atom package for Elixir.
* [atom-iex](https://github.com/indiejames/atom-iex) - Run an IEx session in Atom.
* [elixir-tmbundle](https://github.com/elixir-lang/elixir-tmbundle) - A TextMate and SublimeText bundle for Elixir.
* [elixir_generator](https://github.com/jadercorrea/elixir_generator.vim) - Vim plugin to generate Elixir module and test files with one command.
* [ElixirSublime](https://github.com/vishnevskiy/ElixirSublime) - Elixir plugin for SublimeText 3 that provides code completion and linting.
* [ilexir](https://github.com/dm1try/ilexir) - IDE-like things for Elixir in Neovim.
* [intellij_elixir](https://github.com/KronicDeth/intellij_elixir) - Elixir helpers for intellj-elixir, the Elixir plugin for JetBrains IDEs.
* [Jetbrains](http://plugins.jetbrains.com/plugin/7522) - Elixir for IntelliJ IDEA, RubyMine, WebStorm, PhpStorm, PyCharm, AppCode, Android Studio, 0xDBE.
* [Notepad++](https://github.com/Hades32/elixir-udl-npp) - Elixir syntax highlighting for Notepad++.
* [nvim](https://github.com/dm1try/nvim) - Neovim host for writing plugins in Elixir.
* [phoenix-snippets](https://github.com/phoenixframework-Brazil/phoenix-snippets) - Phoenix Snippets for Atom.
* [TextMate](https://github.com/elixir-lang/elixir-tmbundle) - Elixir syntax highlighting for TextMate.
* [vim-elixir](https://github.com/elixir-lang/vim-elixir) - Vim configuration files for Elixir.
* [vim-ex_test](https://github.com/moofish32/vim-ex_test) - Vim test runner based on Thoughtbots vim-rspec.
* [vscode-elixir](https://github.com/mat-mcloughlin/vscode-elixir) - Elixir Support for Visual Studio Code.

## Newsletters
*Useful Elixir-related newsletters.*

* [Elixir Digest](http://elixirdigest.net) - A weekly newsletter with the latest articles on Elixir and Phoenix.
* [Elixir Radar](http://plataformatec.com.br/elixir-radar) - The "official" Elixir newsletter, published weekly via email by Plataformatec.
* [ElixirWeekly](https://elixirweekly.net) - The Elixir community newsletter, covering stuff you easily miss, shared on [ElixirStatus](http://elixirstatus.com) and the web.

## Other Awesome Lists
*Other amazingly awesome lists can be found at [jnv/lists](https://github.com/jnv/lists#lists-of-lists) or [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness#awesome-awesomeness).*

* [Awesome Elixir by LibHunt](https://elixir.libhunt.com) - A curated list of awesome Elixir and Erlang packages and resources.
* [Awesome Erlang](https://github.com/drobakowski/awesome-erlang) - A curated list of awesome Erlang libraries, resources and shiny things.
* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks) - A collection of links for Erlang developers.

## Reading
*Elixir-releated reading materials.*

* [Discover Elixir & Phoenix](https://www.ludu.co/course/discover-elixir-phoenix/) - An online course that teaches both the Elixir language and the Phoenix framework.
* [Elixir Cheat-Sheet](http://media.pragprog.com/titles/elixir/ElixirCheat.pdf) - A Elixir cheat sheet, by Andy Hunt & Dave Thomas.
* [Elixir Functional Programming](https://github.com/kblake/functional-programming) - Material to introduce functional programming using the Elixir language.
* [Elixir School](https://elixirschool.com/) - Lessons about the Elixir programming language.
* [The Little Schemer in Elixir](https://github.com/jwhiteman/a-little-elixir-goes-a-long-way) - Exercises and algorithms from the Little Schemer book, ported to Elixir.
* [xElixir](https://github.com/exercism/xelixir) - Exercism Exercises in Elixir.

## Screencasts
*Cool video tutorials.*

* [Confreaks (Elixir)](http://confreaks.tv/tags/40) - Elixir related conference talks.
* [Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers) - Functional, Parallel, Reliable (and fun!), taught by Dave Thomas.
* [Elixir Sips](http://elixirsips.com/) - Tiny screencasts for learning Elixir.
* [ExCasts](https://excasts.com) - Elixir and Phoenix screencasts for all skill levels.
* [LearnElixir.tv](https://www.learnelixir.tv/) - Beginner friendly, in-depth, step by step screencasts.
* [LearnPhoenix.tv](https://www.learnphoenix.tv/) - Learn how to build fast, dependable web apps with Phoenix.
* [Meet Elixir](https://www.pluralsight.com/courses/meet-elixir) - Walk through some features and concepts of Elixir by José Valim.

## Styleguides
*Styleguides for ensuring consistency while coding.*

* [christopheradams/elixir_style_guide](https://github.com/christopheradams/elixir_style_guide) - A community-driven style guide for Elixir.
* [lexmag/elixir-style-guide](https://github.com/lexmag/elixir-style-guide) - An opinionated Elixir style guide.
* [rrrene/elixir-style-guide](https://github.com/rrrene/elixir-style-guide) - Style guide checked by [Credo](https://github.com/rrrene/credo).

## Websites
*Useful Elixir-related websites.*

* [30 Days of Elixir](https://github.com/seven1m/30-days-of-elixir) - A walk through the Elixir language in 30 exercises.
* [Awesome Elixir @LibHunt](https://elixir.libhunt.com) - Your go-to Elixir Toolbox.
* [BEAM Community](http://beamcommunity.github.io/) - From distributed systems, to robust servers and language design on the Erlang VM.
* [Benjamin Tan - Learnings & Writings](http://benjamintan.io/blog/tags/elixir/) - A blog consisting of mostly Elixir posts.
* [Elixir China](https://github.com/jw2013/elixir-china) - Chinese Elixir website [elixir-cn.com](http://elixir-cn.com/).
* [Elixir Examples](http://elixir-examples.github.io/) - A collection of small Elixir programming language examples.
* [Elixir Flashcards](https://elixircards.co.uk/) - Flashcards are a powerful way to improve your knowledge. Elixircards are hand crafted, professionally printed flashcards for levelling up your Elixir.
* [Elixir Fountain](https://soundcloud.com/elixirfountain) - A weekly podcast with news & interviews from around the Elixir community hosted by [Johnny Winn](https://twitter.com/johnny_rugger).
* [Elixir Github Repository](https://github.com/elixir-lang/elixir) - The project repository.
* [Elixir Github Wiki](https://github.com/elixir-lang/elixir/wiki) - The project's wiki, containing much useful information.
* [Elixir Job Board](http://jobs.elixirdose.com) - A job board for Elixir, and community of Elixir developers, [written using Phoenix](https://github.com/rizafahmi/elixirjobs).
* [Elixir Playground](http://play.elixirbyexample.com/) - Try Elixir code in your browser.
* [Elixir Quiz](http://elixirquiz.github.io/) - Weekly programming problems to help you learn Elixir.
* [Elixir Recipes](http://elixir-recipes.github.io/) - Collection of patterns & solutions to common problems in Elixir.
* [Elixre](http://www.elixre.uk/) - An Elixir regular expression editor & tester.
* [Erlang Patterns](http://www.erlangpatterns.org/) - Unlike traditional software design pattern efforts, which tend to emphasize the importance of code reuse, this project emphasizes patterns that feel good to humans.
* [Hashrocket Today I Learned - Elixir](https://til.hashrocket.com/elixir) - Small posts about Elixir from the team at Hashrocket.
* [How I start - Elixir](http://howistart.org/posts/elixir/1) - Explanation and intro to Elixir by José Valim.
* [Learning Elixir](http://learningelixir.joekain.com/) - A blog about a Professional Software Engineer learning Elixir.

# Contributing
Please see [CONTRIBUTING](https://github.com/h4cc/awesome-elixir/blob/master/.github/CONTRIBUTING.md) for details.

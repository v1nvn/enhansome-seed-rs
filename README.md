<!--lint disable double-link-->

# Awesome Seed RS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

<p align="center">
    <img src="https://raw.githubusercontent.com/seed-rs/seed-rs.org/81ed1acc77062ede3295683f21f2d39611843192/seed_branding/seed_logo.min.svg" width="256" title="Seed logo">
</p>

> A curated list of awesome things related to Seed

Seed is an open-source Rust framework for creating fast and reliable web apps running in WebAssembly.

Contributions welcome. Add links through pull requests or create an issue to start a discussion.

## Contents

* [Official Resources](#official-resources)
* [Books](#books)
* [Quickstarts](#quickstarts)
* [Bundlers](#bundlers)
* [Examples](#examples)
* [Projects Using Seed](#projects-using-seed)
* [Libraries](#libraries)
* [Contribute](#contribute)

## Official Resources

* ~~Homepage~~
* [GitHub repo](https://github.com/seed-rs/seed) ⭐ 3,838 | 🐛 55 | 🌐 Rust | 📅 2025-01-11
* [Forum](https://seed.discourse.group)
* [Chat](https://discord.gg/JHHcHp5)

## Books

* [Engineering Rust Web Applications](https://erwabook.com/) - Diesel, Rocket and Seed.
* [Porting a JS app to Rust](https://slowtec.de/posts/2019-12-20-porting-javascript-to-rust-part-1.html) - Porting a JavaScript App to WebAssembly with Rust (blog series).

## Quickstarts

* [Quickstart with Webpack](https://github.com/seed-rs/seed-quickstart-webpack) ⭐ 113 | 🐛 20 | 🌐 Rust | 📅 2025-01-11 - Main features: Auto-reload, Prerendering, Minification, [TailwindCSS](https://tailwindcss.com/), Typescript.
* [Default quickstart](https://github.com/seed-rs/seed-quickstart) ⭐ 100 | 🐛 5 | 🌐 Rust | 📅 2022-09-06 - Contains only Rust libraries.

## Bundlers

* [Trunk](https://github.com/thedodd/trunk) ⭐ 4,145 | 🐛 129 | 🌐 Rust | 📅 2026-02-02 - WASM web application bundler for Rust.
* [Seeder](https://github.com/MartinKavik/seeder) ⭐ 43 | 🐛 5 | 📅 2021-12-18 - Set up Seed app and start dev server by running one command.
* [Web Bundler](https://github.com/panoptix-za/web-bundler) ⚠️ Archived - Bundles a Seed SPA for publishing.

## Examples

* [Official examples](https://github.com/seed-rs/seed/tree/master/examples) ⭐ 3,838 | 🐛 55 | 🌐 Rust | 📅 2025-01-11 - Smaller examples included in official repo.
* [RealWorld example](https://github.com/seed-rs/seed-rs-realworld) ⭐ 126 | 🐛 4 | 🌐 Rust | 📅 2025-01-11 - "The mother of all demo apps" — Exemplary fullstack [Medium.com](https://medium.com/) clone.
* [ERWA mytodo](https://github.com/seed-rs/erwa_mytodo) ⭐ 10 | 🐛 6 | 🌐 Rust | 📅 2023-06-14 - Rust full-stack example. Diesel, Rocket, Seed.
* [Dark lang Realworld](https://github.com/MartinKavik/seed-realworld-darklang) ⭐ 9 | 🐛 22 | 🌐 Rust | 📅 2023-01-20 - Seed Realworld example on *Quickstart with Webpack* with integrated [Dark lang](https://darklang.com/) Realworld.
* [Seeded Game of Life](https://github.com/arn-the-long-beard/seeded_game_of_life) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2020-07-30 - Game of life with [tutorial](https://dev.to/arnthelongbeard/how-to-only-rust-for-web-frontend-1026) in pure Rust inspired by [wasm tutorial](https://rustwasm.github.io/docs/book/).
* [Dota Underlord Perfect Build](https://github.com/warycat/dotawasm) ⭐ 0 | 🐛 1 | 🌐 Rust | 📅 2020-09-18 - An app to help build optimal deck in Dota Underlord.
* [Template for GUIs with seed+gotham](https://gitlab.com/liketechnik/local-gui-seed-gotham) - Electron like template for local/desktop GUIs with Gotham, rust-embed, web-view and Seed.
* [Play Seed](https://ide.play-seed.dev) - Playground with several default examples.

## Projects Using Seed

* [Pslink](https://pslink.teilgedanken.de) - An URL-shortener page focused on use in publications ([demo](https://demo.pslink.teilgedanken.de/app/) (user, password: demo)).  Uses `Seed`, [`actix-web`](https://actix.rs/), and [`sqlx`](https://github.com/launchbadge/sqlx) ⭐ 16,484 | 🐛 720 | 🌐 Rust | 📅 2026-02-06.
* [Music composer](https://github.com/ethanboxx/planters-rdconf-hackathon-project) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2020-08-02 - A basic music composition app.
* [Kavik.cz](https://github.com/MartinKavik/kavik.cz) ⭐ 5 | 🐛 21 | 🌐 Rust | 📅 2026-01-30 - Open-source personal website.
* [AdEx Explorer](https://github.com/adexnetwork/adex-explorer) ⭐ 3 | 🐛 7 | 🌐 Rust | 📅 2022-06-06 - Shows curated information about the payment channel network of the AdEx advertising protocol.
* [benxu.dev/blog](https://github.com/AlterionX/benxu-dev) ⭐ 0 | 🐛 1 | 🌐 Rust | 📅 2025-07-12 - A relatively simple open source personal blog. Built on `Seed`, [`maud`](https://maud.lambda.xyz), [`Rocket`](https://rocket.rs), and [`Diesel`](https://diesel.rs).
* ~~seed-rs.org~~ - Seed's official website.
* [WeightRS](https://gitlab.com/mkroehnert/weightrs) - Minimalistic and privacy friendly progressive web app for tracking your weight.
* [Play Seed](https://play-seed.dev) - Website about Play Seed, playground to demo Seed apps.
* [Typesync](https://typesync.rutrum.net) - Test your typing speed on song lyrics.  Uses `Seed`, [`Rocket`](https://rocket.rs), and [`Diesel`](https://diesel.rs).
* [CalcuPi](https://dvjn.github.io/CalcuPi) - A beautiful Monte Carlo simulation for approximating the value of pi.
* [Love Letter Tracker](https://www.fosskers.ca/en/tools/love-letter) - A knowledge tracker for the card game *Love Letter*.
* [Whatlang.org](https://whatlang.org/) - An interactive demo for whatlang (language recognition library).

## Libraries

* [Seed Bootstrap](https://github.com/panoptix-za/seed-bootstrap) ⚠️ Archived - A collection of the [Bootstrap](https://getbootstrap.com/) CSS components.
* [seed\_heroicons](https://github.com/mh84/seed_heroicons) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2021-06-27 - Library providing [Heroicons](https://heroicons.com/) to include into Seed-based applications.
* [Savory](https://gitlab.com/MAlrusayni/savory) - Library for building user interface based on Seed.
* [seed-icons](https://crates.io/crates/seed-icons) - Library with collections of icons to include in Seed-based application.

## Contribute

Contributions welcome! Read the [contribution guidelines](origin/contributing.md) first.

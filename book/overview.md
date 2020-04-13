Learning Rust with Actix, WASM & Giphy
======================================
Let's learn a little bit about Rust with a demo WebAssembly (WASM) application that allows a user to search for and save animated GIFs to a user profile using the [GIPHY API](https://developers.giphy.com/docs/).

The API is structured as a very simple JSON RPC API built using [actix.rs](https://actix.rs/). The client & server use the same exact data models (the same library code) for communicating over the network. All interaction is protected by JWT authN/authZ.

The client is a WASM application built using Rust & the [Seed framework](https://seed-rs.org).

We are using Postgres for data storage & [launchbadge/sqlx](https://github.com/launchbadge/sqlx) for the interface.

Check out the repository at [github.com/thedodd/giphy-api](https://github.com/thedodd/giphy-api/).

### Learning Objectives
First and foremost, let's learn something new about Rust!

1. **Start off by building the app!** We have a working application to study, so let's build it. This will give us some practice with the Rust toolchain.
2. **Break some stuff in the API.**
3. **Break some stuff in the UI.**
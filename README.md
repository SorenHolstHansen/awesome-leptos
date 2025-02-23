# Awesome Leptos
A collection of awesome libraries in the Leptos ecosystem.

[Leptos](https://github.com/leptos-rs/leptos) is a framework for creating full-stack web applications using Rust.

## Resources
- [Leptos Book](https://github.com/leptos-rs/leptos/tree/main/docs/book) (WIP)
- [Discord Community](https://discord.gg/YdRAhS7eQB)

## Tools
- [cargo-leptos](https://github.com/leptos-rs/cargo-leptos) coordinates rebuilding the server and client side of your app
- [leptosfmt](https://github.com/bram209/leptosfmt) provides formatting for the `view` macro

## Starter Templates

### Official

 - [leptos-rs/start](https://github.com/leptos-rs/start) - Starter template for use with the Leptos web framework and Actix.
 - [leptos-rs/start-axum](https://github.com/leptos-rs/start-axum) - Starter template for use with the Leptos web framework and Axum.
 - [leptos-rs/start-axum-workspace](https://github.com/leptos-rs/start-axum-workspace) - Same as above but using Cargo workspace to split crates

### Unofficial

- [leptos-fullstack](https://github.com/srid/leptos-fullstack) - A [Nix](https://nixos.org/) template for full-stack web apps in Rust using Leptos + Tailwind

## Styling and Design
- [Stylers](https://github.com/abishekatp/stylers) Compile-time scoped CSS extracted from Leptos components
- [Styled](https://github.com/eboody/styled) Scoped CSS styles
- [turf](https://github.com/myFavShrimp/turf) - Macro based compile-time SCSS transpilation, CSS minification, and class name uniquification toolchain inspired by CSS modules

## Quality of Life
- [`tracing-subscriber-wasm`](https://crates.io/crates/tracing-subscriber-wasm) A `MakeWriter` implementation to allow directly using `tracing_subscriber` in the browser or with NodeJS to allow for beautiful `tracing` integration into Leptos apps.
- [`wasm-bindgen-struct`](https://crates.io/crates/wasm-bindgen-struct) A crate making it easier to declare `wasm_bindgen` types and implement getters/setter as if they were normal Rust structs.

## Components
- [Leptonic](https://leptonic.dev/) A rich component library for Leptos. 

## Libraries
- [leptos-use](https://leptos-use.rs/) Reactive primitives to make app development easier. (Like react-use, vue-use, etc.)
- [leptos_query](https://github.com/nicoburniske/leptos_query) Asynchronous cache for data fetching and state management
- [leptos-icons](https://github.com/Carlosted/leptos-icons) An icon library for Leptos
- [leptos_image](https://github.com/nicoburniske/leptos_image) Optimize static images with leptos (similar to NextJS `<Image/>`). It converts images to .webp format, and generates Low Quality Image Placeholders (LQIP) included in your initial SSR render.
- [leptos-declarative](https://github.com/jquesada2016/leptos-declarative) Declarative control-flow components
- [leptos-tracked](https://docs.rs/leptos-tracked/latest/leptos_tracked/) Utility traits for composing Leptos signals with fewer nested closures
- [leptos-signals](https://github.com/akesson/leptos-signals) Additional primitives for working with signals
- [leptos-tea](https://github.com/jquesada2016/leptos-tea) A library for state management using The Elm Architecture (TEA) in Leptos
- [leptos-leaflet](https://github.com/headless-studio/leptos-leaflet) Leaflet components for Leptos
- [Papelito](https://github.com/msmaiaa/papelito) A simple WYSIWYG editor for leptos.
- [leptos-server-signal](https://github.com/tqwewe/leptos_server_signal) Leptos signals kept in sync with the server through websockets.
- [leptos_sse](https://github.com/messense/leptos_sse) Leptos server signals synced through Server-Sent-Events (SSE).
- [leptos_i18n](https://github.com/Baptistemontan/leptos_i18n) A translation library for Leptos.

## Blogs / Websites
- [leptos.dev](https://leptos.dev) The official Leptos website, built with Leptos (of course.)
- [Itehax Blog](https://itehax.com) Markdown blog written using Leptos(with server side rendering) and styled using Preline (component library for tailwindcss) ([source](https://github.com/itehax/rust-blog))
- [Personal blog](https://github.com/LeVuMinhHuy/blog) A simple markdown to html blog
- [viz.rs](https://viz.rs/) The documentation site for Viz web framework
- [khuedoan.com](https://khuedoan.com) Markdown blog built with Leptos and Axum, styled with Tailwind CSS ([source](https://github.com/khuedoan/blog))
- [nicoburniske.com](https://nicoburniske.com) Blog + Photo gallery (using leptos_image and leptos_query). Styled with Tailwind CSS.

---
title: "Building a Modern Web Portfolio with Rust and Dioxus"
excerpt: "In this post, I'll walk through building a personal portfolio website using Rust, Dioxus 0.7, and WebAssembly."
date: "Dec 14, 2025"
readTime: "8 min"
tags: ["Rust", "Dioxus", "WebAssembly"]
featured: true
---
# Building a Modern Web Portfolio with Rust and Dioxus

**December 14, 2025** · 8 min read

## Introduction

In this post, I'll walk through building a personal portfolio website using **Rust**, **Dioxus 0.7**, and **WebAssembly**. This approach gives us blazing-fast performance, type safety, and a modern development experience.

## Why Dioxus?

- **Type Safety**: Catch bugs at compile time
- **Performance**: WebAssembly is near-native speed
- **Familiar Syntax**: Inspired by React hooks
- **No JavaScript**: Pure Rust all the way

## Architecture

```rust
#[component]
fn Home() -> Element {
    rsx! {
        div { "Hello, World!" }
    }
}
```

## Deployment

I use GitHub Pages with a two-repository setup:

    Private repo: Rust source code
    Public repo: Compiled WASM bundle

## Conclusion

This stack is perfect for developers who want full control and type safety. Try it yourself!
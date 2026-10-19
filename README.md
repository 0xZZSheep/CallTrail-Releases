# CallTrail Releases

**CallTrail** turns the call hierarchy of the element under your cursor into an interactive call graph in a popup. It shows up to three caller levels above the element and three callee levels below it, using the same results as *Navigate | Call Hierarchy*.

**Install from [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/34445-calltrail)** · [Download the latest release](https://github.com/0xZZSheep/CallTrail-intellij-plugin/releases/latest)

## Highlights

- **See the whole call path at a glance.** Callers and callees are laid out as levels, with nodes that appear at several depths (recursion) marked by dashed borders.
- **Explore without losing context.** Click a node to focus it, then jump to its source or open the graph on it again while the popup stays open.
- **Share the graph.** Copy it as Mermaid or Graphviz DOT, ready for Markdown, pull requests, or Graphviz.
- **Keep it beside your code.** Pin the popup, maximize it, move it to a second monitor, or collapse it to the status bar.
- **Watch progress on large graphs.** The footer reports scanned work, queued items, discovered nodes, and scan speed.
- **Optional AI summaries.** Tooltips can explain a node's purpose, parameters, return value, and body through an OpenAI-compatible endpoint of your choice. Source code is sent only to that endpoint, and nothing is requested while the feature is off.

## Supported IDEs and languages

CallTrail runs in any IntelliJ-based IDE **2025.2 or newer**, including IntelliJ IDEA, WebStorm, PyCharm, GoLand, PhpStorm, and RubyMine.

- **Fast Mode:** Java, Kotlin, JavaScript, TypeScript, Python.
- **Compatibility Mode:** Go, C/C++, Rust, C#, PHP, Ruby, and other languages supported by the IDE. Elements that a language's call hierarchy cannot walk, such as constants, fields, properties, and namespaces, are resolved through *Find Usages* so their callers are still shown.

## Install

Install CallTrail from the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/34445-calltrail), or download a ZIP from [Releases](https://github.com/0xZZSheep/CallTrail-intellij-plugin/releases/latest) and use *Settings | Plugins | ⚙ | Install Plugin from Disk…*.

## About this repository

This repository hosts the official CallTrail release artifacts and update notes. The source code is private.

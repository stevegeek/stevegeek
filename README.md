### Hi there 👋

I'm Stephen — freelance Ruby developer & consultant, based in Italy.

I've been writing **Ruby** for well over 10 years and still love it ❤️. Lately I'm also spending a lot of time with **Crystal** and the [Marten](https://martenframework.com) web framework, and playing with coding agents. Most of my gems and shards are extracted from production apps I maintain.

## What I'm working on

### Crystal & Marten

I ported Basecamp's Writebook from Rails to Marten as a little experiment, to see how close a Marten app feels to Rails and what it takes to port a real app with agents. The bits Rails has and Marten didn't ended up as shards.

- [**writebook**](https://github.com/stevegeek/writebook) — The port. Same UI and Hotwire behaviour as the original, but it's a single compiled binary.
- Rails-like bits for Marten: [**marten-text**](https://github.com/stevegeek/marten-text) (ActionText), [**marten-storages**](https://github.com/stevegeek/marten-storages) (Active Storage), [**marten-cable**](https://github.com/stevegeek/marten-cable) (ActionCable), [**marten-delegated-type**](https://github.com/stevegeek/marten-delegated-type), [**marten-signed-id**](https://github.com/stevegeek/marten-signed-id), [**marten-global-id**](https://github.com/stevegeek/marten-global-id), [**marten-fixtures**](https://github.com/stevegeek/marten-fixtures).
- Stuff I needed running Marten in production: [**marten-seo**](https://github.com/stevegeek/marten-seo), [**marten-cdn-cache**](https://github.com/stevegeek/marten-cdn-cache), [**marten-profile-log**](https://github.com/stevegeek/marten-profile-log), [**marten-pg-resilience**](https://github.com/stevegeek/marten-pg-resilience).
- [**crystal-llm**](https://github.com/stevegeek/crystal-llm) — Crystal port of `ruby_llm`, with [Marten persistence](https://github.com/stevegeek/crystal-llm-marten). [**marten-mcp**](https://github.com/stevegeek/marten-mcp) adds an MCP server to a Marten app.
- Crystal ports of my own gems: [**encoded-id-cr**](https://github.com/stevegeek/encoded-id-cr) (+ [marten-encoded-id](https://github.com/stevegeek/marten-encoded-id)), [**operation-cr**](https://github.com/stevegeek/operation-cr), [**sentiero-cr**](https://github.com/stevegeek/sentiero-cr).

### Working with agents

Mostly Go, some Rust. Agents write most of this code, and in some cases I haven't even looked at it. Each repo's `RIGOR.md` tells you how much rigor went into it and whether I'd vouch for it.

- [**lever**](https://github.com/stevegeek/lever) — Containerised multi-agent orchestration, with a host-side broker that manages permissions and access.
- [**rigor**](https://github.com/stevegeek/rigor) — A disclosure convention for source code in the AI era: how much rigor went into the work, human or machine.

### Ruby

My gems, which I still maintain and use. Find them on [gem.coop](https://beta.gem.coop/@stephen) or [Rubygems](https://rubygems.org/profiles/stevegeek).

- [**vident**](https://github.com/stevegeek/vident) — The base of your design system. Stimulus-powered view components for ViewComponent or Phlex.
- [**typed_operation**](https://github.com/stevegeek/typed_operation) — Command pattern: callable, chainable, traceable, with typed parameters, partial application and currying.
- [**encoded_id**](https://github.com/stevegeek/encoded_id) — Reversible, human-friendly obfuscated IDs. Supports ActiveRecord.
- [**sentiero**](https://github.com/stevegeek/sentiero) — Browser session recording for any Rack framework. Privacy-first defaults.
- [**quo**](https://github.com/stevegeek/quo) — Composable query objects for ActiveRecord.
- [**awfy**](https://github.com/stevegeek/awfy) — CLI to run benchmark suites and compare results over time, across branches, with or without YJIT.
- And some smaller ones: [typed_form_model](https://github.com/stevegeek/typed_form_model), [typed_view_model](https://github.com/stevegeek/typed_view_model), [another_api](https://github.com/stevegeek/another_api), [yaml_csp_config](https://github.com/stevegeek/yaml_csp_config), [fixtures_from_factories](https://github.com/stevegeek/fixtures_from_factories), [access_allow](https://github.com/stevegeek/access_allow).

## Older stuff

A mix of dead projects and old experiments:

- [**ai_refactor**](https://github.com/stevegeek/ai_refactor) — Experimental tool applying AI to bulk refactor code, from 2023.
- [**hone**](https://github.com/stevegeek/hone) — Finds performance optimization opportunities by combining static AST analysis with runtime profiling data.
- [**claret**](https://github.com/stevegeek/claret) — Experiment in adding type information to Ruby via transpilation.
- [**moka**](https://github.com/stevegeek/moka) — Port of the Objective-C object model and Cocoa Foundation to PHP. Yes really, back in 2010.

## OSS contributions

- [`unitwise`](https://github.com/joshwlewis/unitwise)
- [`literal`](https://github.com/joeldrapper/literal)
- [Avo](https://github.com/avo-hq/avo)
- [Marten](https://github.com/martenframework/marten)
- [scion](https://github.com/GoogleCloudPlatform/scion)
- [iyi](https://github.com/iyilang/iyi)
- [ruby/ruby](https://github.com/ruby/ruby/pull/6568)
- [rails/rails](https://github.com/rails/rails/pull/47014)
- [crystal-lang/crystal](https://github.com/crystal-lang/crystal/pull/9577)

The full list is in my [Contributed to](https://github.com/stars/stevegeek/lists/contributed-to) stars list.

I got into OSS properly after [Hacktoberfest '22](https://hacktoberfest.com/) and [How To Open Source](https://howtoopensource.dev/) by Richard Schneeman.

## Connect

- [diaconou.com](https://www.diaconou.com?utm_campaign=profile&utm_source=github) — writing & more
- [LinkedIn](https://www.linkedin.com/in/stephen-ierodiaconou/)
- [Bluesky](https://bsky.app/profile/diaconou.com)

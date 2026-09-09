<div align="center">

# qwetls

**Systems engineer · Compiler architect · AI infrastructure builder**

Founder of [XeyCompany](https://xeycompany.com)

I design and build systems that are correct by construction — from programming language runtimes to production gateway infrastructure.

[![AHA! Lang](https://img.shields.io/badge/AHA!_Lang-v1.6-blueviolet?style=flat&logo=rust&logoColor=white)](https://github.com/qwetls/aha-lang)
[![XEYGATE](https://img.shields.io/badge/XEYGATE-v1.0-0ea5e9?style=flat&logo=openai&logoColor=white)](https://github.com/qwetls/xeygate)
[![Jabr](https://img.shields.io/badge/Jabr-v0.1-059669?style=flat&logo=rust&logoColor=white)](https://github.com/qwetls/jabr)

---

</div>

## Selected Work

### [AHA! Lang](https://github.com/qwetls/aha-lang) `Rust` `LLVM`

A compiled, statically-typed language built on an LLVM backend (via inkwell).

Feature set (v1.6, `main`): structs, generics (`List<T>`, `Map<K,V>`), module system with visibility control, compile-time-inserted memory management (scope-based → last-use → escape analysis), actor-model concurrency, and enum pattern matching. AOT compilation supported. **581+ integration tests**, single-binary CI pipeline.

[![CI](https://img.shields.io/github/actions/workflow/status/qwetls/aha-lang/ci.yml?branch=main&label=CI&logo=github&logoColor=white&style=flat)](https://github.com/qwetls/aha-lang/actions)
[![Docs](https://img.shields.io/badge/docs-aha--lang-blue?style=flat&logo=vercel&logoColor=white)](https://aha-lang-tau.vercel.app)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat)](https://github.com/qwetls/aha-lang/blob/main/LICENSE)

---

### [XEYGATE](https://github.com/qwetls/xeygate) `TypeScript` `Hono` `React`

Cloud-first multi-provider AI gateway. One API key for OpenAI, Anthropic, and custom model endpoints — with automatic failover, OAuth token refresh, and live telemetry.

Additional infrastructure: server-side model governance (denied-models denylist), creator marketplace with namespace-isolated endpoints (`/user/v1`, `/official/v1`), admin user management with approval state machine, public analytics dashboard, and quality-based routing with payout tracking.

[![Version](https://img.shields.io/badge/version-v1.0-6366f1?style=flat)](https://github.com/qwetls/xeygate/releases)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat)](https://github.com/qwetls/xeygate/blob/main/LICENSE)
[![Docker](https://img.shields.io/badge/docker-ghcr.io%2Fqwetls%2Fxeygate-2496ED?style=flat&logo=docker&logoColor=white)](https://ghcr.io/qwetls/xeygate)

---

### [Jabr](https://github.com/qwetls/jabr) `Rust`

A programming language inspired by the Islamic Golden Age — grounded in the legacy of al-Khwarizmi and early computational thought.

Current state: v0.1.0, tree-walking interpreter with arithmetic, variables, functions, and control flow. Roadmap: bytecode VM → LLVM native codegen → self-hosting compiler.

[![Version](https://img.shields.io/badge/version-v0.1-059669?style=flat)](https://github.com/qwetls/jabr/releases)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat)](https://github.com/qwetls/jabr/blob/main/LICENSE)

---

## Stack

`Rust` · `TypeScript` · `LLVM` · `C++` · `Python` · `Lua` · `Next.js` · `Fumadocs` · `Hono` · `React` · `SQLite` · `Docker` · `GitHub Actions`

---

## Contact

**Discord** — `xeyyzu` · **Web** — [xeycompany.com](https://xeycompany.com)

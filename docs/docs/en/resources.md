# Resources

This page provides a comprehensive collection of resources to support your learning journey and help you become proficient in Rust development and code migration.

## Official Rust Resources

### Core Documentation
- **[The Rust Programming Language Book](https://doc.rust-lang.org/book/)** - The definitive guide to Rust
- **[Rust by Example](https://doc.rust-lang.org/rust-by-example/)** - Learn Rust through practical examples
- **[The Rust Reference](https://doc.rust-lang.org/reference/)** - Detailed language specification
- **[The Rustonomicon](https://doc.rust-lang.org/nomicon/)** - Advanced unsafe Rust guide
- **[Standard Library Documentation](https://doc.rust-lang.org/std/)** - Complete API reference

### Learning Resources
- **[Rustlings](https://github.com/rust-lang/rustlings)** - Interactive Rust exercises
- **[Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)** - Common programming patterns
- **[Rust API Guidelines](https://rust-lang.github.io/api-guidelines/)** - Best practices for API design

## Web Development with Rust

### Frameworks and Libraries

#### Web Frameworks
- **[Axum](https://github.com/tokio-rs/axum)** - Ergonomic web framework (used in this workshop)
- **[Actix Web](https://actix.rs/)** - Powerful, pragmatic web framework
- **[Warp](https://github.com/seanmonstar/warp)** - Composable web server framework
- **[Rocket](https://rocket.rs/)** - Type-safe web framework
- **[Tide](https://github.com/http-rs/tide)** - Modular web framework

#### JSON and Serialization
- **[Serde](https://serde.rs/)** - Serialization framework
- **[serde_json](https://github.com/serde-rs/json)** - JSON support for Serde

#### Async Runtime
- **[Tokio](https://tokio.rs/)** - Async runtime for Rust
- **[async-std](https://async.rs/)** - Alternative async runtime

#### Database Integration
- **[SQLx](https://github.com/launchbadge/sqlx)** - Async SQL toolkit
- **[Diesel](http://diesel.rs/)** - Safe, extensible ORM
- **[SeaORM](https://www.sea-ql.org/SeaORM/)** - Async & dynamic ORM

### HTTP Clients
- **[reqwest](https://github.com/seanmonstar/reqwest)** - Easy HTTP client
- **[surf](https://github.com/http-rs/surf)** - Friendly HTTP client

## Testing and Development Tools

### Testing Frameworks
- **[cargo test](https://doc.rust-lang.org/cargo/commands/cargo-test.html)** - Built-in testing framework
- **[criterion](https://github.com/bheisler/criterion.rs)** - Benchmarking library
- **[proptest](https://github.com/AltSysrq/proptest)** - Property-based testing
- **[mockall](https://github.com/asomers/mockall)** - Mock object library

### Development Tools
- **[Clippy](https://github.com/rust-lang/rust-clippy)** - Linting tool
- **[Rustfmt](https://github.com/rust-lang/rustfmt)** - Code formatter
- **[Cargo](https://doc.rust-lang.org/cargo/)** - Package manager and build tool
- **[cargo-expand](https://github.com/dtolnay/cargo-expand)** - Show macro expansions
- **[cargo-audit](https://github.com/RustSec/rustsec/tree/main/cargo-audit)** - Security vulnerability scanning

## GitHub Copilot Resources

### Documentation
- **[GitHub Copilot Documentation](https://docs.github.com/en/copilot)** - Official documentation
- **[Copilot Best Practices](https://docs.github.com/en/copilot/using-github-copilot/best-practices-for-using-github-copilot)** - Usage guidelines
- **[Copilot in VS Code](https://docs.github.com/en/copilot/getting-started-with-github-copilot/getting-started-with-github-copilot-in-visual-studio-code)** - IDE integration

### Tips for Effective Usage
- **Be specific in your comments** - Clear intentions lead to better suggestions
- **Provide context** - Include relevant imports and type information
- **Use descriptive function names** - Help Copilot understand your intent
- **Review suggestions carefully** - Understand what's being suggested
- **Iterate and refine** - Use suggestions as starting points

## Books and Publications

### Rust Programming Books
- **"Programming Rust" by Jim Blandy, Jason Orendorff, and Leonora F.S. Tindall** - Comprehensive Rust guide
- **"Rust in Action" by Tim McNamara** - Systems programming with Rust
- **"Zero to Production in Rust" by Luca Palmieri** - Web development with Rust
- **"The Rust Programming Language" by Steve Klabnik and Carol Nichols** - Official Rust book
- **"Rust for Rustaceans" by Jon Gjengset** - Advanced Rust programming

### Performance and Systems Programming
- **"High Performance Rust" by Packt** - Optimization techniques
- **"Systems Programming with Rust" by Packt** - Low-level programming
- **"Hands-On Concurrency with Rust" by Brian L. Troutwine** - Concurrent programming

## Online Courses and Tutorials

### Video Courses
- **[Rust Programming Course on Udemy](https://www.udemy.com/topic/rust-programming-language/)** - Various skill levels
- **[The Rust Programming Language on YouTube](https://www.youtube.com/playlist?list=PLLqEtX6ql2EyPAZ1M2_C0GgVd4A-_L4_5)** - Video tutorials
- **[Jon Gjengset's Rust Streams](https://www.youtube.com/c/JonGjengset)** - Advanced Rust topics

### Interactive Learning
- **[Rust Playground](https://play.rust-lang.org/)** - Online Rust compiler
- **[Exercism Rust Track](https://exercism.org/tracks/rust)** - Practice exercises with mentoring
- **[Codewars Rust Kata](https://www.codewars.com/kata/search/rust)** - Programming challenges

## Community and Support

### Forums and Discussion
- **[Rust Users Forum](https://users.rust-lang.org/)** - Community support and discussion
- **[r/rust Subreddit](https://www.reddit.com/r/rust/)** - News and discussions
- **[Rust Discord](https://discord.gg/rust-lang)** - Real-time chat
- **[Stack Overflow Rust Tag](https://stackoverflow.com/questions/tagged/rust)** - Q&A

### Blogs and News
- **[This Week in Rust](https://this-week-in-rust.org/)** - Weekly newsletter
- **[The Rust Blog](https://blog.rust-lang.org/)** - Official announcements
- **[Read Rust](https://readrust.net/)** - Curated Rust articles
- **[Rust Magazine](https://rustmagazine.github.io/rust_magazine_01/)** - Community magazine

### Conferences and Events
- **[RustConf](https://rustconf.com/)** - Annual Rust conference
- **[Rust Belt Rust](https://www.rust-belt-rust.com/)** - Regional conference
- **[EuroRust](https://eurorust.eu/)** - European Rust conference
- **Local Rust Meetups** - Check [meetup.com](https://www.meetup.com/) for local groups

## Migration-Specific Resources

### Migration Strategies
- **[Incremental Migration Patterns](https://blog.rust-lang.org/2020/12/31/async-overhaul.html)** - Async migration strategies
- **[FFI Guidelines](https://doc.rust-lang.org/nomicon/ffi.html)** - Interfacing with other languages
- **[Bindgen](https://rust-lang.github.io/rust-bindgen/)** - Generate Rust bindings for C libraries

### Language Comparisons
- **[Rust vs. Python Performance](https://benchmarksgame-team.pages.debian.net/benchmarksgame/fastest/rust-python3.html)** - Performance comparisons
- **[From Python to Rust](https://github.com/rochacbruno/py2rs)** - Language comparison guide
- **[Rust vs. Go vs. Python](https://bitfieldconsulting.com/golang/rust-vs-go)** - Detailed comparisons

## Specialized Topics

### Async Programming
- **[Async Book](https://rust-lang.github.io/async-book/)** - Comprehensive async guide
- **[Tokio Tutorial](https://tokio.rs/tokio/tutorial)** - Async runtime tutorial
- **[Async Patterns](https://docs.rs/futures/latest/futures/)** - Future combinators

### Error Handling
- **[Error Handling in Rust](https://doc.rust-lang.org/book/ch09-00-error-handling.html)** - Official guide
- **[thiserror](https://github.com/dtolnay/thiserror)** - Derive macro for error types
- **[anyhow](https://github.com/dtolnay/anyhow)** - Flexible error handling

### Performance Optimization
- **[The Rust Performance Book](https://nnethercote.github.io/perf-book/)** - Performance optimization guide
- **[Flamegraph](https://github.com/flamegraph-rs/flamegraph)** - Profiling tool
- **[Criterion](https://bheisler.github.io/criterion.rs/book/)** - Benchmarking guide

### Security
- **[RustSec](https://rustsec.org/)** - Security advisory database
- **[Secure Rust Guidelines](https://anssi-fr.github.io/rust-guide/)** - Security best practices
- **[cargo-audit](https://github.com/RustSec/rustsec/tree/main/cargo-audit)** - Vulnerability scanner

## Tools and IDEs

### IDEs and Editors
- **[VS Code with rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)** - Recommended setup
- **[IntelliJ Rust](https://intellij-rust.github.io/)** - JetBrains IDE support
- **[Vim/Neovim with rust.vim](https://github.com/rust-lang/rust.vim)** - Vim configuration
- **[Emacs with rust-mode](https://github.com/rust-lang/rust-mode)** - Emacs configuration

### Debugging Tools
- **[gdb](https://sourceware.org/gdb/)** - GNU Debugger with Rust support
- **[lldb](https://lldb.llvm.org/)** - LLVM Debugger
- **[rr](https://rr-project.org/)** - Record and replay debugger

## Crate Discovery

### Crate Registries
- **[crates.io](https://crates.io/)** - Official crate registry
- **[lib.rs](https://lib.rs/)** - Alternative crate browser
- **[docs.rs](https://docs.rs/)** - Automatic documentation hosting

### Popular Crates by Category
- **CLI Tools**: clap, structopt, indicatif
- **Networking**: reqwest, hyper, quinn
- **Cryptography**: ring, rustls, sodiumoxide
- **Data Processing**: csv, regex, rayon
- **Logging**: log, env_logger, tracing

## Migration Case Studies

### Real-World Examples
- **[Discord's Rust Migration](https://blog.discord.com/why-discord-is-switching-from-go-to-rust-a190bbca2b1f)** - Go to Rust migration
- **[Dropbox's File Storage Migration](https://dropbox.tech/infrastructure/rewriting-the-heart-of-our-sync-engine)** - Python to Rust migration
- **[npm's Performance Improvements](https://www.npmjs.com/package/node-rs)** - Node.js to Rust bindings

### Migration Tools
- **[py2rs](https://github.com/rochacbruno/py2rs)** - Python to Rust migration guide
- **[c2rust](https://c2rust.com/)** - C to Rust transpiler
- **[Corrode](https://github.com/jameysharp/corrode)** - C to Rust translator

## Deployment and Operations

### Containerization
- **[Docker Multi-stage Builds](https://docs.docker.com/develop/dev-best-practices/)** - Efficient Rust containers
- **[Distroless Images](https://github.com/GoogleContainerTools/distroless)** - Minimal container images

### Cloud Deployment
- **[AWS Lambda Rust Runtime](https://github.com/awslabs/aws-lambda-rust-runtime)** - Serverless Rust
- **[Google Cloud Run](https://cloud.google.com/run/docs/quickstarts/build-and-deploy/deploy-rust-service)** - Container deployment
- **[Kubernetes Deployment](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/)** - Container orchestration

### Monitoring and Observability
- **[tracing](https://github.com/tokio-rs/tracing)** - Application-level tracing
- **[metrics](https://github.com/metrics-rs/metrics)** - Metrics collection
- **[Prometheus Integration](https://prometheus.io/docs/instrumenting/clientlibs/)** - Monitoring metrics

## Contributing to the Ecosystem

### How to Contribute
- **[Contributing to Rust](https://rustc-dev-guide.rust-lang.org/contributing.html)** - Official contribution guide
- **[Good First Issues](https://github.com/rust-lang/rust/labels/E-easy)** - Beginner-friendly tasks
- **[RFC Process](https://github.com/rust-lang/rfcs)** - Language development process

### Creating Crates
- **[Cargo Book](https://doc.rust-lang.org/cargo/)** - Package creation guide
- **[Publishing Crates](https://doc.rust-lang.org/cargo/reference/publishing.html)** - How to publish
- **[Crate Best Practices](https://rust-lang.github.io/api-guidelines/)** - Quality guidelines

## Stay Updated

### News Sources
- **[This Week in Rust](https://this-week-in-rust.org/)** - Weekly updates
- **[Rust Blog](https://blog.rust-lang.org/)** - Official announcements
- **[Inside Rust](https://blog.rust-lang.org/inside-rust/)** - Development insights

### Social Media
- **[@rustlang on Twitter](https://twitter.com/rustlang)** - Official Twitter account
- **[Rust LinkedIn](https://www.linkedin.com/company/rust-programming-language/)** - Professional updates
- **[YouTube Channels](https://www.youtube.com/results?search_query=rust+programming)** - Video content

Remember: The Rust ecosystem is constantly evolving. These resources will help you stay current and continue growing as a Rust developer. Don't hesitate to ask questions in the community forums - the Rust community is known for being welcoming and helpful!

## Getting Help

When you need assistance:
1. **Search existing resources** - Often your question has been answered
2. **Provide context** - Include relevant code and error messages
3. **Be specific** - Clear questions get better answers
4. **Show your research** - Demonstrate what you've already tried
5. **Give back** - Help others when you can

Happy learning and building with Rust! 🦀

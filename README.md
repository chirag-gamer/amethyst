# Amethyst 🚀
**A High-Performance MCBE Server in Rust** 🦀

[![Crates.io](https://img.shields.io/crates/v/amethyst-server)](https://crates.io/crates/amethyst-server) [![License](https://img.shields.io/crates/l/amethyst-server)](LICENSE)

---

## 🏗️ Status
We’re hard at work on Amethyst! Here’s what’s in progress:
- 🔧 **Async Networking Core**: Building the foundation for thousands of concurrent connections

## 🎉 Features
- 🚀 **Blazing Fast**: Low-overhead, high TPS
- 🔒 **Memory Safe**: Rust guarantees against common bugs
- 🧩 **Modular Plugins**: Hot-swap at runtime
- 🌐 **Async I/O**: Powered by Tokio

## 🛠️ Installation & Quick Start
```bash
# Clone & build
git clone https://github.com/sauoro/amethyst.git
cd amethyst
cargo build --release

# Init config & run (prototyping)
./target/release/amethyst init --output config/
./target/release/amethyst run --config config/server.yaml
```


## 📄 Configuration
Edit `config/server.yaml`:
```yaml
# This is a concept we are prototyping.
server:
  name: "Amethyst"
  address: "0.0.0.0:19132"
  motd: "Welcome!"
  max_players: 50
```

## 📝 Roadmap
**What we’re working on next:**
- [ ] Plugin Marketplace 🛒
- [ ] World Import/Export Tool 🌍
- [ ] Real-time Chat Moderation 💬
- [ ] Automatic Backups 🔄

## 💖 Contributing
1. 🍴 Fork the repo
2. 🌿 Create a branch
3. 🚧 Code & test
4. 🔃 Open a PR

## 📜 License
MIT • See [LICENSE](LICENSE)

---
Built with ❤️ and Rust 🦀


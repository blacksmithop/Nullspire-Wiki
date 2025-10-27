# Setup

> [!NOTE]
> Make this part of the Codespace setup (automated)

To setup the docs page locally you need

* [Cargo (Rust)](https://rust-lang.org/tools/install/)

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Reload the shell

```bash
exec "$SHELL"
```

Now you can install `mdbook`

```bash
cargo install mdbook
```

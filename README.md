<div id="top"></div>

<!-- PROJECT LOGO -->
<br />

<div align="center">
  <a>
    <img src="https://github.com/Zenotta/NAOM/blob/develop/assets/hero.svg" alt="Logo" style="width: 350px">
  </a>

  <h2 align="center">Notarised Append Only Memory (NAOM)</h2> <div style="height:30px"></div>

  <div>
  <img src="https://img.shields.io/github/actions/workflow/status/Zenotta/NAOM/rust.yml" alt="Pipeline Status" style="display:inline-block"/>
  <img src="https://img.shields.io/crates/v/naom" alt="Cargo Crates Version" style="display:inline-block" />
  </div>

  <p align="center">
    The OG dual double entry blockchain
    <br />
    <br />
    <a href="https://zenotta.io"><strong>Official documentation »</strong></a>
    <br />
    <br />
  </p>
</div>

The NAOM repo contains all the code needed to set up and interact with a local instance of the Zenotta blockchain.

[简体中文](https://github.com/Zenotta/NAOM/blob/develop/readmes/README.zhs.md) | [Español](https://github.com/Zenotta/NAOM/blob/develop/readmes/README.es.md) | [عربي ](https://github.com/Zenotta/NAOM/blob/develop/readmes/README.ar.md)| [Deutsch](https://github.com/Zenotta/NAOM/blob/develop/readmes/README.de.md) | [Français](https://github.com/Zenotta/NAOM/blob/develop/readmes/README.fr.md)

..

## Getting Started

Running NAOM assumes you have Rust installed and are using a Unix system. You can clone this repo and run the `Makefile` to set everything up for a development environment:

```
make
cargo build
cargo test
```

..

## Use

NAOM can be added to your project as a dependency by adding the following to your `Cargo.toml` file:

```toml
[dependencies]
naom = "0.1.0"
```

Or alternatively, via command line:

```
cargo add naom
```

Running `cargo run --bin main` from a repo clone will currently list all assets on the local instance. NAOM is not generally intended to be
used directly though, and is instead intended to be used from other programs that require access to the blockchain data 
structure.

..

## References

- [BitML for Zenotta](https://github.com/Zenotta/NAOM/blob/main/docs/BitML_for_Zenotta.pdf)
- [ZScript Opcodes Reference](https://github.com/Zenotta/NAOM/blob/main/docs/ZScript_Opcodes_Reference.pdf)
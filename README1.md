[![pipeline status](https://gitlab.com/brndnmtthws-oss/labhub/badges/master/pipeline.svg)](https://gitlab.com/brndnmtthws-oss/labhub/commits/master) [![codecov](https://codecov.io/gh/brndnmtthws/labhub/branch/master/graph/badge.svg)](https://codecov.io/gh/brndnmtthws/labhub) [![Current Crates.io Version](https://img.shields.io/crates/v/labhub.svg)](https://crates.io/crates/labhub)

# 🤖 `ndir`

`edinburg`,`aide` 


🚧 _Work In Progress_ 🚧


[ui]: https://user-images.githubusercontent.com/383250/59148363-53188c80-8a08-11e9-9b29-9cac56809ee2.png "Automaat UI Example"

### Documentation quick links

* [Installation](#installation)
* [User Guide](GUIDE.md)
* [Frequently Asked Questions](FAQ.md)
* [Configuration files](GUIDE.md#configuration-file)
* [Building](#building)

## Features

- **TODO:**

### Commands

Commands can be executed by commenting on a PR with your CI user's login.

- **`@ndir list`**: show all sensor

## The Problem

**TODO:**

## ✨ The Solution

If you're not concerned with leaking secrets, then LabHub may be for you! LabHub listens for webhooks from GitHub to notify for new pull requests. If the PR is from a forked repo, it will push a branch to GitLab (for the corresponding PR) to test the build.

## 🏃‍♀️ In Action

**Using sensors? 😀**


## Compiling

sensors requires Rust nightly. To compile using [`rustup`](https://rustup.rs/):

```ShellSession
$ rustup toolchain install nightly
$ rustup default nightly
$ cargo build
```

Be sure to switch back to `stable` with `rustup default stable` if that's your preferred toolchain.

## 🎛 Configuration

Automata is configured using [`automata.toml`](automata.toml). For details, see [src/config.rs](src/config.rs). You can specify the path to `sensors.toml` by setting the `SENSORS_TOML` environment variable.

## 🚀 Deployment



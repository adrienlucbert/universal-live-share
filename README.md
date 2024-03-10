<h1 align="center">Universal Live-Share</h1> <br>

<p align="center">
  Collaborate in real-time from your favorite code editor.
</p>

## 💡 Introduction

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

As real-time code collaboration tools exist, I find that most focus on one or a
small set of IDEs, not leaving the user with much freedom over their development
environment.

I dreamt of a code collaboration tool that was IDE-agnostic by design. The idea
is inspired by the [Language Server Protocol](https://langserver.org/). One
generic protocol is used between IDE-specific clients to integrate real-time code
collaboration features, leaving most technicalities such as LSP up to each user's
IDE.

The protocol being open-source, if a client is missing for one's favorite IDE,
they can contribute to this project by implementing the said client.

## 📝 Implementation

The Universal Live-Share project is made out of:
- a protocol described in this repository
- a [generic server implementation](https://github.com/adrienlucbert/universal-live-share-server)
- an IDE-specific client implementation

You can find a list of client implementations here:

| IDE/Editor | Maintainer | Repository |
|------------|------------|------------|
| [neovim](https://neovim.io/) | [adrienlucbert](https://github.com/adrienlucbert) | https://github.com/adrienlucbert/universal-live-share-client-nvim |

## 🔨 Usage

> 🚧 This section is still in progress. Please come back later.
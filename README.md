# Orihost Free Panel Eggs

Welcome to the official repository for the open-source Orihost.com free panel eggs!

These eggs are designed to make it easy to deploy a variety of programming environments and runtimes on Pterodactyl Panel. Feel free to use, modify, and contribute to these eggs.

## 🥚 What are Eggs?

Eggs are configuration files for the [Pterodactyl Panel](https://pterodactyl.io/) that automate the setup and management of different software environments inside containers. They allow you to quickly deploy servers for various languages and frameworks.

## 📦 Available Eggs

This repository includes the following eggs:

- **Bun** (`egg-bun.json`):
  Run JavaScript/TypeScript projects using the fast Bun runtime.

- **Dart** (`egg-dart-generic.json`):
  Deploy Dart CLI applications with automatic dependency management.

- **C# (.NET)** (`egg-generic-c.json`):
  Run generic C# (.NET) projects with support for multiple .NET versions.

- **Node.js (Generic)** (`egg-node-js-generic.json`):
  Deploy Node.js applications with automatic npm install and git integration.

- **Node.js (Custom Startup)** (`egg-node-js-custom-startup.json`):
  Node.js environment with customizable startup commands.

- **Python (Generic)** (`egg-python-generic.json`):
  Run Python applications with support for requirements.txt and additional pip packages.

- **Python (Custom Startup)** (`egg-python-custom-startup.json`):
  Python environment with customizable startup commands.

- **Rust** (`egg-rust-generic.json`):
  Deploy Rust projects using Cargo.

## 🚀 Usage

1. **Download the desired egg(s)** from this repository.
2. **Import the egg(s) into your Pterodactyl Panel** via the admin interface.
3. **Configure the environment variables** as needed (e.g., Git repo, main file, additional packages).
4. **Deploy your server** and enjoy!

For detailed instructions, see the [Pterodactyl documentation](https://pterodactyl.io/project/introduction.html).

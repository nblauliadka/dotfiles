# Commander's Dotfiles

Welcome to my personal Linux dotfiles. This repository contains a highly customized, ultra-minimalist, and keyboard-driven environment built on a centralized symlink architecture to keep the base system entirely clean and scalable.

## System Architecture

Unlike traditional monolithic configs, this system utilizes UWSM (Universal Wayland Session Manager) to handle the environment startup independently, resulting in an ultra-lightweight compositor configuration.

- **OS:** EndeavourOS (Arch Linux based)
- **Kernel:** Linux 6.19.x
- **Hostname:** supercomputer
- **Machine:** Lenovo ThinkPad T490s (32GB RAM)
- **Core Engine:** Caelestia (Managed via UWSM)
- **Shell Environment:** Fish + Ax-Shell Integration
- **Aesthetics & UI:** Matugen, Fuzzel, Cava, Spicetify

## Installation

To replicate this environment, clone the repository and inject the core configs into your local user directory:

```bash
git clone [https://github.com/nblauliadka/dotfiles.git](https://github.com/nblauliadka/dotfiles.git)
cd dotfiles

# 1. Inject the Core Engine (Caelestia)
cp -r .local/share/* ~/.local/share/

# 2. Inject the Aesthetic Modules
cp -r .config/* ~/.config/

"Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away." - Antoine de Saint-Exupéry
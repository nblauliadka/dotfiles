<div align="center">
  <h1>Commander's Dotfiles</h1>
  <p><b>Highly customized, ultra-minimalist, and keyboard-driven Linux environment.</b></p>

  [![OS - EndeavourOS](https://img.shields.io/badge/OS-EndeavourOS-1793d1?style=for-the-badge&logo=arch-linux&logoColor=white)](#)
  [![Engine - Caelestia](https://img.shields.io/badge/Engine-Caelestia-00b4b6?style=for-the-badge)](#)
  [![Hardware - ThinkPad T490s](https://img.shields.io/badge/Hardware-ThinkPad_T490s-E2231A?style=for-the-badge&logo=lenovo&logoColor=white)](#)
</div>

<br>

> *"Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away."* > — Antoine de Saint-Exupéry

## 📝 Overview
Welcome to my personal Linux workspace. This system is built on a centralized symlink architecture to keep the base system entirely clean and scalable. Unlike traditional monolithic configs, this setup utilizes **UWSM** (Universal Wayland Session Manager) to handle the environment startup independently, resulting in an ultra-lightweight compositor configuration.

## 🖼️ The Setup
![Desktop Preview](assets/dekstop.png)

---

## ⚙️ System Architecture

| Component | Specification |
|---|---|
| **OS** | EndeavourOS (Arch Linux based) |
| **Kernel** | Linux 6.19.x |
| **Hostname** | `supercomputer` |
| **Hardware** | Lenovo ThinkPad T490s (32GB RAM) |
| **Core Engine** | Caelestia (Managed via UWSM) |
| **Shell** | Fish + Ax-Shell Integration |
| **Aesthetics** | Matugen, Fuzzel, Cava, Spicetify |

---

## 🛠️ Installation

⚠️ **Warning:** *Dotfiles are highly personal. It is recommended to read through the configurations and cherry-pick what you need rather than blindly copying everything to your machine.*

To replicate this environment, clone the repository and inject the core configs into your local user directory:

```bash
git clone [https://github.com/nblauliadka/dotfiles.git](https://github.com/nblauliadka/dotfiles.git)
cd dotfiles

# 1. Inject the Core Engine (Caelestia)
cp -r .local/share/* ~/.local/share/

# 2. Inject the Aesthetic Modules
cp -r .config/* ~/.config/

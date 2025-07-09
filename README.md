This script sets up a Hyprland environment on a barebones Arch install. It is very personalized so I don't recomend using it without tweaking it first.

# Usage

## 1. Install Archlinux

I recommend archinstall.

- Set up a sudo user
- enable multilib
- Audio: pipewire
- Bootloader: grub
- Network: NetworkManager

## 2. Use the script

### Install git

```
sudo pacman -S git
```

### Clone the repo

```
git clone https://github.com/dyn1xx/arch_postinstall_script.git
```

### Start the script

```
cd arch_postinstall_script
./postinstall
```

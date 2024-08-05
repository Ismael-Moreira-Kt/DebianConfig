# DebianConfig
DebianConf is a set of scripts for easily configuring various aspects of Debian, including the graphical interface, sound, network, system and hardware, packages, security and backup. This script is ideal for users who want to quickly configure a Debian environment according to their preferences.

[Leia o README em português, clique aqui.](./README_PT.md)

<br><br>

## Prerequisites
Before running the script, make sure your Debian system is prepared with the following packages:

```bash
sudo apt update -y && sudo apt upgrade -y
sudo apt install -y git
```

Make sure you have sudo permissions, the script requires superuser privileges to install packages and apply settings.

<br><br>

## Installation
Clone the archive containing the DebianConf script:

```bash
git clone https://github.com/Ismael-Moreira-Kt/DebianConfig
cd DebianConfig
```

Give execution permission to the main script:

```bash
chmod +x dc
```

<br><br>

## Usage
To start the configuration process, run the main script:

```bash
./dc
```

The script will guide you through a main menu where you can choose the type of configuration you want.

### In the main menu, you can choose from the following options:
- **Configure Graphical Interface:** Customizes the style of the GNOME graphical interface.
- **Configure Sound and Audio:** Adjusts the system's sound and audio settings.
- **Configure Network:** Configure the network settings.
- **Configure System and Hardware:** Adjusts system and hardware settings.
- **Configure Packages:** Installs and configures additional packages.
- **Configure Security Systems:** Applies security settings to the system.
- **Configure Backup:** Configure backup options for your data.
- **Configure everything Automatically:** Applies all settings automatically.
- **Exit:** Exits the script.

### Function Details
#### General Functions
- **check_sudo:** Checks if the script is being executed with sudo permissions.
- **show_menu:** Displays a menu and handles user input.
- **setup:** Configures the environment based on the choice of language

#### Specific Settings
- **Configure the Graphic Interface:** Applies themes and icon settings for different styles, including GNOME Dark, GNOME Light, macOS Style, Windows Style and Retro Style.
- **Configure Sound and Audio:** Installs and configures packages to adjust system sound and audio.
- **Configure Network:** Adjust network settings, such as IP, DNS and connection configuration.
- **System and Hardware Configuration:** Applies settings and configurations to the system and hardware.
- **Configure Packages:** Installs and configures additional packages required for the system.
- **Configure Security Systems:** Applies settings and packages to improve system security.
- **Configure Backup:** Configures options and tools for data backup.
- **Configure Everything Automatically:** Applies all settings and adjustments automatically without additional intervention.
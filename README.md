# Battery Conservation Mode Manager for Lenovo Ideapad Laptops Running Linux

This repository contains a simple bash script to manage battery conservation
mode on Lenovo Ideapad laptops running Linux.

## Overview

Battery conservation mode limits the battery charging to 60%, helping to prolong
battery life. This script allows users to easily enable, disable, or toggle this
mode.

Based on [this Reddit post](https://www.reddit.com/r/Ubuntu/comments/p2so5n/how_to_limit_battery_charging_to_60_in_ubuntu/).

## Commands

    -h: Display help information.
    -p or no arguments: Print the current conservation mode status.
    -e: Enable conservation mode.
    -d: Disable conservation mode.
    -t: Toggle conservation mode.

## Usage

Clone this repository and run the script with the desired option. Root privileges
are required to use this tool.

```bash
cd batman/
sudo ./batman -e # Enable conservation mode
sudo ./batman -d # Disable conservation mode
sudo ./batman -t # Toggle conservation mode
./batman # Print current conservation mode status
```

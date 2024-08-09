# Needy Grub Overdose

My attempt at recreating the boot screen from the game 'Needy Streamer Overload'.
Also known as 'Needy Girl Overdose'.

🙏 BLESS 🙏

## Fonts

Fonts used are from [int10h.org](https://int10h.org/oldschool-pc-fonts/), created by VileR.

- IBM VGA 8x14
- IBM BIOS

## Installation

The theme can be installed just like any other grub theme.

1. Copy this repository to the `/boot/grub/themes/` directory.
2. Go to `etc/default/grub` and edit the file so that it includes the line `GRUB_THEME="/boot/grub/themes/needy-grub-overdose/theme.txt".`
   On my 1920x1080 screen, I also have `GRUB_GFXMODE=1280x960` set as well.
3. Run `sudo update-grub`.

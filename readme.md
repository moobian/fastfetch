# Fastfetch   

Welcome to my Fastfetch config presets repository

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a command-line tool used to display system information and hardware specs alongside ASCII art or an image. Fastfetch is a modern replacement for the discontinued Neofetch.


## Fastfetch Config Screenshot Gallery

All screenshots are in [Debian](https://www.debian.org/), using [Ghostty](https://github.com/ghostty-org/ghostty) terminal, terminal font is [Jetbrains Mono NerdFont](https://www.jetbrains.com/lp/mono/).

For privacy, I remove username and IP address address modules in my configs. 

<table>
  <tr>
    <td width=25%><img src="./screenshots/moobian-ff01.png" width="100%" alt="A blend of official fastfetch examples/6 and examples/7"></td>
    <td width=25%><img src="./screenshots/moobian-ff02.png" width="100%" alt="A tall main cell divided into multi-row and a lower single-row sub-cell"></td>    
  </tr>
  <tr>
    <td width=25%><img src="./screenshots/moobian-ff03.png" width="100%" alt="One tall main cell divided into three equal-size sub-cells"></td>
    <td width=25%><img src="./screenshots/moobian-ff04.png" width="100%" alt="A large horizontal main cell divided into a narrow and wide sub-cells"></td>    
  </tr>
  <tr>
    <td width=25%><img src="./screenshots/moobian-ff05.png" width="100%" alt="A main cell divided into three minimal sub-cells"></td>
    <td width=25%><img src="./screenshots/moobian-ff06.png" width="100%" alt="An open table divided two horizontal rows"></td>    
  </tr>
</table>


## Fastfetch Logo Gallery

All logo images here are .png with transparent backgrounds. Some are original works made by me, others are modified by me based on other artworks.


### Linux themed

<table>
  <tr>
    <td width=50%><img src="./logos/tux-linux-icon.png" width="100%"></td>
    <td width=50%><img src="./logos/arch-square-tr.png" width="100%"></td>
  </tr>
  <tr>  
    <td width=50%><img src="./logos/cachyos-square-tr.png" width="100%"></td>
    <td width=50%><img src="./logos/debian-square-tr.png" width="100%"></td>
  </tr>
  <tr>
    <td width=50%><img src="./logos/fedora-square-tr.png" width="100%"></td>
    <td width=50%><img src="./logos/ghostty-icon-lg.png" width="100%"></td>
  </tr>
  <tr>
    <td width=50%><img src="./logos/alacritty-terminal-icon.png" width="100%"></td>
    <td width=50%><img src="./logos/kitty-terminal-icon.png" width="100%"></td>
  </tr>
  <tr>
    <td width=50%><img src="./logos/gnome-square-tr.png" width="100%"></td>
    <td width=50%><img src="./logos/kde-icon.png" width="100%"></td>
  </tr>


### Hardware themed

  <tr>    
    <td width=33%><img src="./logos/gnu-linux-cpu-2d.png" width="100%"></td>
    <td width=33%><img src="./logos/gnu-linux-cpu-3d.png" width="100%"></td>
    <td width=33%><img src="./logos/intel-4004-cpu-1971.png" width="100%"></td>  
  </tr>


### Anime & Cartoon themed

  <tr>
    <td width=25%><img src="./logos/astroboy.png" width="100%"></td>
    <td width=25%><img src="./logos/astroboy-diagram-grid.png" width="100%"></td>
    <td width=25%><img src="./logos/transformers-autobot.png" width="100%"></td>
    <td width=25%><img src="./logos/transformers-autobot.png" width="100%"></td>
  </tr>


### Pixel-art themed

  <tr>
    <td width=33%><img src="./logos/pixel-cow-brown.png" width="100%"></td>
    <td width=33%><img src="./logos/pixel-duck.png" width="100%"></td>
    <td width=33%><img src="./logos/pixel-cow-duck.png" width="100%"></td>
  </tr>


### Voxel-art themed

  <tr>
    <td width=25%><img src="./logos/voxel-cow.png" width="100%"></td>
    <td width=25%><img src="./logos/voxel-cpu.png" width="100%"></td>
    <td width=25%><img src="./logos/voxel-pc.png" width="100%"></td>
    <td width=25%><img src="./logos/voxel-tux-penguin.png" width="100%"></td>
  </tr>
  <tr>
    <td width=25%><img src="./logos/voxel-facehugger.png" width="100%"></td>
    <td width=25%><img src="./logos/voxel-xenomorph.png" width="100%"></td>
    <td width=25%><img src="./logos/voxel-sauropod.png" width="100%"></td>
    <td width=25%><img src="./logos/voxel-hadrosaur.png" width="100%"></td>
  </tr>
</table>


## Usage

Config files: copy the chosen config file in /home/username/.config/fastfetch/, ensure the file name is config.jsonc

Fonts: [Jetbrains Mono NerdFont](https://www.jetbrains.com/lp/mono/) is required to display ligatures properly. Terminals such as [Ghostty](https://github.com/ghostty-org/ghostty), [Kitty](https://github.com/kovidgoyal/kitty) and [Alacritty](https://github.com/alacritty/alacritty) can render NerdFont ligatures. Check your terminal documentation to confirm that it supports NerdFont ligatures.

Logos: Ensure your .png image is in /home/username/.config/fastfetch/ . The images I use are 1:1 aspect ratio (ie, square), but you can choose any size and may need to play with padding values in the config until you have the alignment you want.
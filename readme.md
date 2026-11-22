# Fastfetch   

<h3 align="left">
Welcome to my fastfetch config presets repository
</h3>

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a command-line tool used to display system information and hardware specs alongside ASCII art or an image. Fastfetch is a modern replacement for the discontinued Neofetch.

## Config Gallery

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

## Logo Gallery

All images created or modified by me and are .png with transparent backgrounds.

<table>
  <tr>
    <td width=25%><img src="./logos/arch-square-tr.png" width="100%" alt="Arch Linux logo"></td>
    <td width=25%><img src="./logos/cachyos-square-tr.png" width="100%" alt="Debian logo"></td>
    <td width=25%><img src="./logos/debian-square-tr.png" width="100%" alt="Debian logo"></td>
    <td width=25%><img src="./logos/fedora-square-tr.png" width="100%" alt="Fedora logo"></td>
  </tr>
  <tr>
    <td width=25%><img src="./logos/gnome-square-tr.png" width="100%" alt="GNOME logo"></td>
    <td width=25%><img src="./logos/ghostty-icon-lg.png" width="100%" alt="Ghostty logo"></td>
    <td width=25%><img src="./logos/intel-4004-cpu-1971.png" width="100%" alt="Pixel art cow and duck"></td>  
    <td width=25%><img src="./logos/pixel-cow-duck.png" width="100%" alt="Pixel art cow and duck"></td>
  </tr>
  <tr>
    <td width=25%><img src="./logos/voxel-cow.png" width="100%" alt="Voxel art cow"></td>
    <td width=25%><img src="./logos/voxel-cpu.png" width="100%" alt="Voxel art CPU"></td>
    <td width=25%><img src="./logos/voxel-facehugger.png" width="100%" alt="Voxel art CPU"></td>
    <td width=25%><img src="./logos/voxel-hadrosaur.png" width="100%" alt="Voxel art CPU"></td>
  </tr>
  <tr>
    <td width=25%><img src="./logos/voxel-pc.png" width="100%" alt="Voxel art CPU"></td>
    <td width=25%><img src="./logos/voxel-sauropod.png" width="100%" alt="Voxel art sauropod"></td>
    <td width=25%><img src="./logos/voxel-tux-penguin.png" width="100%" alt="Voxel art Linux Tux Penguin"></td>
    <td width=25%><img src="./logos/voxel-xenomorph.png" width="100%" alt="Voxel art PC"></td>
  </tr>
</table>

## Usage

<u>Config files</u>: copy the chosen config file in /home/username/.config/fastfetch/, ensure the file name is config.jsonc

<u>Fonts</u>: [Jetbrains Mono NerdFont](https://www.jetbrains.com/lp/mono/) is required to display ligatures properly. Terminals such as Ghostty, Kitty and Alacritty can render NerdFont ligatures. Check your terminal  documentation to confirm that it supports NerdFont ligatures.

<u>Logos</u>: Ensure your .png image is in /home/username/.config/fastfetch/ . The images I use are 1:1 aspect ratio (ie, square), but you can choose any size you want. Depending on your chosen .png image, you may need to play with padding values in the config until you have the alignment you want.
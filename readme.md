# Fastfetch 

<h3 align="left">
Welcome to my fastfetch config presets repository
</h3>

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a command-line tool used to display system information and hardware specs alongside ASCII art or an image. Fastfetch is a modern replacement for the discontinued Neofetch.

## Config Gallery

<table>
  <tr>
    <td width=50%><img src="./screenshots/config-01-blend-67.png" width="100%" alt="Config 1: a blend of official fastfetch examples/6 and examples/7"></td>
    <td width=50%><img src="./screenshots/config-02-tall-cells.png" width="100%" alt="Config 2: a single tall cell: system details, small footer cell: colours"></td>    
  </tr>
  <tr>
    <td width=50%><img src="./screenshots/config-03-threecells.png" width="100%" alt="Config 3: three cells: distro details, DE and terminal details, hardware details"></td>
    <td width=50%><img src="./screenshots/config-04-minimal-cells.png" width="100%" alt="Config 4: minimalist three-cell: distro, system, colours"></td>    
  </tr>
  <tr>
    <td width=50%><img src="./screenshots/config-05-minimal-table.png" width="100%" alt="Config 5: minimalist two-cell table: software on top, hardware on bottom, colours"></td>
    <td width=50%><img src="./screenshots/config-06-narrow-wide-cells.png" width="100%" alt="Config 6: minimalist two-cell table: narrow cell on left, wide cell on right"></td>    
  </tr>
</table>

## Logo Gallery
<table>
  <tr>
    <td></td>
  </tr>
</table>


## Usage

I have added some notes to each config file.

Config files: copy the chosen config file in /home/username/.config/fastfetch/, ensure the file name is config.jsonc

Fonts: [Jetbrains Mono NerdFont](https://www.jetbrains.com/lp/mono/) is required to display ligatures properly. Terminals such as Ghostty, Kitty and Alacritty can render NerdFont ligatures. Check your terminal  documentation to confirm that it supports NerdFont ligatures.

Images: Ensure your .png image is in /home/username/.config/fastfetch/ . The images I use are 1:1 aspect ratio (ie, square), but you can choose any size you want. Depending on your chosen .png image, you may need to play with padding values in the config until you have the alignment you want.

Privacy: for privacy, I exclude username and IP address address modules in my configs, and they have been excluded from the ones here as well.
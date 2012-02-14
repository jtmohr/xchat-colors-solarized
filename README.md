# Solarized Colorscheme for X-Chat

Original Solarized colorscheme developed by:  
**Ethan Schoonover**  
<es@ethanschoonover.com>  
[Solarized Github Repository]

## Visit the [Solarized homepage]

See the [Solarized homepage] for screenshots, details and colorscheme versions
for Vim, Mutt, popular terminal emulators and other applications.

[Solarized Github Repository]: https://github.com/altercation/solarized
[Solarized homepage]: http://ethanschoonover.com/solarized

## Installation

### X-Chat Data Directories
Replace `<username>` with your actual username.

* **Windows Vista/7:**  
`C:\Users\<username>\AppData\Roaming\X-Chat 2\`
* **Windows XP:**  
`C:\Documents and Settings\<username>\Application Data\X-Chat 2\`
* **Linux:**  
`~/.xchat2/`

### pevents.conf
The Solarized colors files work with a default `pevents.conf` file. The
`pevents.conf` included with the theme is modified to show angle brackets around
the nicknames.

The only reason you may need to replace your existing `pevents.conf` file is if
it is heavily modified.

### Install the Solarized theme
1. Exit X-Chat
1. Back-up the current `colors.conf` and `pevents.conf` files located in
   the appropriate X-Chat Data Directory
1. Copy the `solarized-dark-colors.conf` or `solarized-light-colors.conf` file
   to the appropriate X-Chat Data Directory and rename it to `colors.conf`
1. **(Optional)** Copy the `pevents.conf` file to the appropriate X-Chat Data
   Directory
1. Restart X-Chat

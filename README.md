# My ST Configuration
This is a fork of the [simple terminal](https://st.suckless.org/) emulator by suckless.

I applied the following patches to my ST build:
* Mouse scrolling
* Alpha
* Clipboard
* Xresources
<<<<<<< HEAD
<<<<<<< HEAD

=======
>>>>>>> 47fee86 (update readme)
=======

>>>>>>> d66f9c1 (Update README.md)
Each patch is in its own branch and can be merged into the master branch.

## Installation
1. Clone repository:
```
git clone https://github.com/MR2011/st.git
```
2. Merge patches/branches into master and resolve conflicts if necessary:
```
git checkout master
git merge alpha
...
```
3. Install st:
```
make install clean
```

## Keybindings
* Slow mouse scrolling with <kbd>Shift</kbd> + <kbd>Mousewheel</kbd> 
* Fast mouse scrolling with <kbd>ALT</kbd> + <kbd>Mousewheel</kbd> 
* Copy/Paste with <kbd>ALT</kbd> + <kbd>C</kbd> and <kbd>ALT</kbd> + <kbd>V</kbd>
* Font size increase/decrease with <kbd>ALT</kbd> + <kbd>+</kbd> and <kbd>ALT</kbd> + <kbd>-</kbd>
* Default font size with <kbd>ALT</kbd> + <kbd>0</kbd>

## Colorscheme
I use [paywal](https://github.com/dylanaraps/pywal) to generate a colorscheme from my current wallpaper.



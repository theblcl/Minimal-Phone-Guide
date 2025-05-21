# Tips and Tricks

This is a running collection of tips and tricks from the community for using the Minimal Phone.

## Keyboard shortcuts

- **Double-click Enter/Space**: puts the device to sleep

## Keymapper
This is a section dedicated to different keymapper layouts that users have tried. Could be useful to use a tried and true layout, or be inspired to create your own.

### from unknownwelle
Key mapper. The config is sym + WSAD. _tested it on Outlook and New York Times app
The action is "swipe the screen

Add a key map: SYM + W. Make them at the same time. 
Add action:  Start  X: 300, Start Y: 130, End X: 300, End Y: 550. You may change the difference between start Y and End Y if you want to make it swipe faster or slower. 
Time is 200ms, finer No. Is 1

For SYM+A, it is 70-300, 429-300
For SYM+S, it is 300-550, 300-130
For SYM+D, it is 429-300, 70-300
Make sure to toggle on each of the key maps.

(from the github page, look for the static folder and then file named unknownwelle_keymapper_mpkb.zip. please note that we cannot be responsible for these zip files.)

### from tc64
i used key mapper to map mic to down arrow, shift+mic to up, emoji to left, and sym to right

this solved the issue for me. note that key mapper means you give up autocorrect (which is fine for me) and have to manually set up every alt key shortcut. it was worth it for me

in addition, i also used key mapper to access all of the missing keys through the right shift key.

for example, in order, i made right shift +...
q w e r t: map to ` ( ) { }
a s d f g: map to ~ [ ] < >
z x c v: map to / \ ^ |

and:
shift+space | page up
right shift+space | page down
shift+sym | tab
alt+sym | esc
alt+space | alt-tab

in addition, i still have the entire right half of the keyboard free for even more right shift keybindings -- for example, quick app launch shortcuts 

### from lnkd
Figured it out. Didn't see any option to export just a specific set of key maps so this also includes some personal key mapping that you guys might not want. The ones relevant for making gboard work is under the group named "alt layer".

Updated my Key Mapper mapping for Gboard to have double tap spacebar for period and to fix Alt+I launching Gboard settings. Still have not figured out an easy way to captilize characters with the shift keys without holding. I could manually go through and map shift + key to every capital letter, but hoping there's a better way to do it

(from the github page, look for the static folder and then file named lnkd_updated_gboard. please note that we cannot be responsible for these zip files.)

### from user alnorithm
Hello friends.
I made a custom keymap for my personal use. if you're interested, please try it out.
It might be useful for non-English keyboard users like me 🙂

First, install apk and enable GBoard,
and select English (US), Minimal as the layout on the physical keyboard.
highly recommend to use GBoard horizontal toolbar.

The changes are as follows:
Emoji key mapped to Slash (I need it), Mic key mapped to Period, and Symbol key mapped to Meta to use Android shortcuts.

shortcuts example:
Change language: Sym + Space
Open emoji: Alt + Mic
Voice input: using GBoard toolbar
Open Browser: Sym + B
etc....
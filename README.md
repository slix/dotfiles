# dotfiles

Collection of Slix's dotfiles.

For quickly symlinking new computers.

For keeping track of ideal configurations and used applications
across different computers.

For recording best practices for productivity and efficiency. There's
no point in using a customized setup if you don't strive to use it to
make development easier and quicker.

## i3

i3 is a fantastic window manager with flexible layouts and tab support.
It works very well for my typical programming workflow.

There's a lot of configuration possibilities. In particular, I want to
use the scratch workspace for IM windows.

.i3/config -> i3/config

## i3bar

There are alternatives I should consider like dzen2 and bar-aint-recursive.

For now, i3bar has the easiest integration with i3 workspaces and modes.

## i3status

i3status is efficient but limited.

I need to add symbols.

I want a general "internet" indicator that shows relevant information like
ssid and strength when on wifi. But the main thing needs to be purely showing
whether pings to google.com or other major always-up sites are succeeding.

My status only needs to show critically important things like workspaces,
internet, battery, time, some measure of load, and volume. Everything else
can go into a desktop conky that I can look at for details.

.i3status.conf -> i3/i3status.conf

# clock in rust

I am trying to get back into coding with rust by making a clock with rust

# Workspaces

## logic

lib crate which gets the date and time to be displayed.

## window

lib crate which has funtions that will create a window with a clock on it (and move the hand of the clock).
This is the GUI stuff.

## clock

binary crate which combines logic and window crates to render a clock which has the actual time on it

## dependencies

this?: https://time-rs.github.io/book/
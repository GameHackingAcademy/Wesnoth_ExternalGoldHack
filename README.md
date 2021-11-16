# Wesnoth External Gold Hack
Referenced in https://gamehacking.academy/lesson/3/2.

An external memory hack for Wesnoth 1.14.9 that modifies the player's gold.

This code will create a console application that sets the player's gold in Wesnoth 1.14.9 to the value of 555 when run. It makes use of ReadProcessMemory and WriteProcessMemory to achieve this. The address 0x017EED18 represents the player's base pointer in Wesnoth.

This program must be run as an administrator.

# Wesnoth_ExternalGoldHack
An external memory hack for Wesnoth 1.14.9 that modifies the player's gold. 

A console application that sets the player's gold in Wesnoth 1.14.9 to the value of 555 when run. It makes use of ReadProcessMemory and WriteProcessMemory to achieve this. The address 0x017EED18 represents the player's base pointer in Wesnoth. Finding the address and offsets are covered in https://gamehacking.academy/lesson/13

This program must be run as an administrator.

This code is covered in the lab at https://gamehacking.academy/lesson/15

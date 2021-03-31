# Hextreme

Hexstreme is a handy little tool for analysing data piped in via stdin. It differs from `hexdump -C` in that it doesn't require 16 bytes to have passed through before printing the output.

* Good for long-running processes that spit small amounts of information out at a time

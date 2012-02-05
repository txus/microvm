# microvm

Sunday afternoon. One hour. Less than 150LOC (< 4kb).

MicroVM is a stack-based micro virtual machine written in Ruby, running its own
micro bytecode format called MC.

![MC Bytecode](http://f.cl.ly/items/290t2S2H1j0F233R123r/mc.png)

## Install

    $ wget https://raw.github.com/txus/microvm/master/microvm
    $ chmod +x microvm
    $ ./microvm some_file.mc

You can try some example MC files in this very repo.

## Why?

It's a learning example: it's a really simple implementation of a VM that
works, so it's easy to get a general grasp about how things are structured.

## Features

* Compact bytecode format (although it could be more compact)
* Method calls
* Types: only String and Fixnum for now.
* Sort of runtime type checking

## Who's this

This was made by [Josep M. Bach (Txus)](http://txustice.me) under the MIT
license. I'm [@txustice](http://twitter.com/txustice) on twitter (where you
should probably follow me!).

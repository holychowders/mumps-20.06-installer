# MUMPS 20.06 Programming Language Installer

A Linux script to download, extract, and create environment variables for MUMPS 20.06 interpreter, compiler, and server daemon

## Usage

In a terminal:

`cd ~/Downloads/`
`git clone https://github.com/holychowders/mumps-20.06-installer.git`
`cd mumps-20.06-installer`
`sudo ./installer`

This will allow you to run the MUMPS interpreter, compiler, and server daemon without having to navigate to the place you extracted MUMPS. The MUMPS files are extracted to `/usr/lib/mumpsc/`. If you require additional scripts from that library, you'll have to navigate there. Otherwise, `mumps`, `mumpsc`, `mumps2c`, `mumpsRO`, and `mumpsd` are available at all times within your terminal.


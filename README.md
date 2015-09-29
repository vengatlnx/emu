# emu
emu is a command line tool that allows you to start multiple android emulator 
in a single command.

### Usage

1. `git clone git@github.com:vengatlnx/emu.git`
2. `cd emu`
3. `chmod 0755 emu`

Add to your `.bashrc` or `zshrc`:

`$ echo 'export $PATH="$HOME/emu:$PATH"' >> ~/.bashrc`

to run:

```
$ emu [device_name1] [device_name2]...[device_nameN]
$ emu Nexus Lollipop
```

### TODO

1. Need to check android SDK path
2. Check whether the device present in `android list avd`
3. Get device resolution as an argument


## Setup instructions

```sh
git submodule update
brew install qmk/qmk/qmk
qmk setup eliblock/qmk_firmware
```

## Compiling this keymap

```sh
qmk compile --keyboard keebio/iris/rev4 --keymap eliblock
```

## Compiling & Flashing with this keymap

```sh
qmk flash --keyboard keebio/iris/rev4 --keymap eliblock
```

Then, when you see:
```txt
Bootloader not found. Trying again every 0.5s........
```

Put the keyboard into bootloader mode (`RESET` on the keymap).

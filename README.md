# How To Do Stuff

- [How To Do Stuff](#how-to-do-stuff)
  - [Ticker](#ticker)
    - [SSH to ticker](#ssh-to-ticker)
    - [Restart ticker program](#restart-ticker-program)
  - [Coin-reader](#coin-reader)
    - [SSH to coin-reader](#ssh-to-coin-reader)
    - [Restart coin-reader program](#restart-coin-reader-program)
  - [Screen-1](#screen-1)
  - [Screen-2](#screen-2)

## Ticker

### SSH to ticker

> **Important: The ticker raspberry pi needs to be connected to the same Wifi as the computer you are SSH-ing from.**

```bash
ssh -p 12345 lotte@ticker
```

### Restart ticker program

After [ssh-ing to the ticker raspberry pi](#ssh-to-ticker).

```bash
sudo -i
tmux attach
```

Then you should see the ticker program running and you can `ctrl-c` to exit it.

To re-run the ticker program, you can type the following.

```bash
make
```

To leave the terminal but not close the running server, you have to do a little keyboard dance.

Press `ctrl-b` once and then `d`.

## Coin-reader

### SSH to coin-reader

> **Important: The ticker raspberry pi needs to be connected to the same Wifi as the computer you are SSH-ing from.**

```bash
ssh -p 12345 lotte@coin-reader
```

### Restart coin-reader program

After [ssh-ing to the coin-reader raspberry pi](#ssh-to-coin-reader).

```bash
sudo -i
tmux attach
```

Then you should see the ticker program running and you can `ctrl-c` to exit it.

To re-run the ticker program, you can type the following.

```bash
make
```

To leave the terminal but not close the running server, you have to do a little keyboard dance.

Press `ctrl-b` once and then `d`.

## Screen-1

## Screen-2

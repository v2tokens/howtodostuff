# How To Do Stuff

## Ticker

### SSH to ticker

> **Important: The ticker raspberry pi needs to be connected to the same Wifi as the computer you are SSH-ing from.**

```bash
ssh -p 12345 -o PreferredAuthentications=password -o PubkeyAuthentication=no lotte@ticker
```

### Restart ticker program

After ssh-ing to the ticker raspberry pi.

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
ssh -p 12345 -o PreferredAuthentications=password -o PubkeyAuthentication=no lotte@coin-reader
```

### Restart coin-reader program

After ssh-ing to the coin-reader raspberry pi.

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

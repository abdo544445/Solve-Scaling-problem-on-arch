To set the display scaling to 125% on Arch Linux with GNOME using the command line, you can use the `gsettings` command. Here's how to do it:

1. Open a terminal.

2. Run the following command:

```
gsettings set org.gnome.desktop.interface scaling-factor 125
```

3. Log out and log back in for the changes to take effect.

If this doesn't work, you might need to use a more precise fractional scaling value. GNOME supports fractional scaling through a different setting. Try this command instead:

```
gsettings set org.gnome.mutter experimental-features "['scale-monitor-framebuffer']"
gsettings set org.gnome.desktop.interface text-scaling-factor 1.25
```

After running these commands, log out and log back in.

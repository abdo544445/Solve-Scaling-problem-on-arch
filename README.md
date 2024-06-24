To set the display scaling to 125% on Arch Linux with GNOME using the command line, you can use the `gsettings` command. Here's how to do it:


```
gsettings set org.gnome.mutter experimental-features "['scale-monitor-framebuffer']"
gsettings set org.gnome.desktop.interface text-scaling-factor 1.25
```

After running these commands, log out and log back in.

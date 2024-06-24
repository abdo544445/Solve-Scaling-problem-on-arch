 If you're using Arch Linux with GNOME and GDM on Xorg, and you don't have a 125% scaling option in your GNOME settings, you can achieve it through the following methods:

1. **Using Wayland (Recommended)**:
   - Run the following command in your terminal:
     ```
     gsettings set org.gnome.mutter experimental-features "['scale-monitor-framebuffer']"
     ```
   - Restart your session. After this, you should have the 125% scaling option available. Keep in mind that XWayland applications might appear a bit blurry when scaled up¹.

2. **Using Xorg**:
   - Install the `mutter-x11-scaling` package from the AUR repository.
   - Enable fractional scaling with the following command:
     ```
     gsettings set org.gnome.mutter experimental-features "['x11-randr-fractional-scaling']"
     ```
   - Open GNOME Settings > Devices > Displays and set the desired scale²³.

Remember to choose the method that best suits your needs and system configuration. Happy scaling! 😊

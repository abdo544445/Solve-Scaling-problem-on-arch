To set the display scaling to 125% on Arch Linux with GNOME using the command line, you can use the `gsettings` command. Here's how to do it:




```
gsettings set org.gnome.mutter experimental-features "['scale-monitor-framebuffer']"
gsettings set org.gnome.desktop.interface text-scaling-factor 1.25
```


After executing these commands, log out and log back in.
if you want to set it to work on 200% or another percentage, just divided it on 100 to get the numbers in formula 1.00. 
but be careful that lots of x11 apps  won't work perfectly on the scales that are not multiples of 6.25% or another formula 0.625,   you can put the scale from the next: 
```
0.0625 for 6.25% scaling
0.1250 for 12.50% scaling
0.1875 for 18.75% scaling
0.2500 for 25.00% scaling
0.3125 for 31.25% scaling
0.3750 for 37.50% scaling
0.4375 for 43.75% scaling
0.5000 for 50.00% scaling
0.5625 for 56.25% scaling
0.6250 for 62.50% scaling
0.6875 for 68.75% scaling
0.7500 for 75.00% scaling
0.8125 for 81.25% scaling
0.8750 for 87.50% scaling
0.9375 for 93.75% scaling
1.0000 for 100.00% scaling
1.0625 for 106.25% scaling
1.1250 for 112.50% scaling
1.1875 for 118.75% scaling
1.2500 for 125.00% scaling
1.3125 for 131.25% scaling
1.3750 for 137.50% scaling
1.4375 for 143.75% scaling
1.5000 for 150.00% scaling
1.5625 for 156.25% scaling
1.6250 for 162.50% scaling
1.6875 for 168.75% scaling
1.7500 for 175.00% scaling
1.8125 for 181.25% scaling
1.8750 for 187.50% scaling
1.9375 for 193.75% scaling
2.0000 for 200.00% scaling
2.0625 for 206.25% scaling
2.1250 for 212.50% scaling
2.1875 for 218.75% scaling
2.2500 for 225.00% scaling
2.3125 for 231.25% scaling
2.3750 for 237.50% scaling
2.4375 for 243.75% scaling
2.5000 for 250.00% scaling
2.5625 for 256.25% scaling
2.6250 for 262.50% scaling
2.6875 for 268.75% scaling
2.7500 for 275.00% scaling
2.8125 for 281.25% scaling
2.8750 for 287.50% scaling
2.9375 for 293.75% scaling
3.0000 for 300.00% scaling
3.0625 for 306.25% scaling
3.1250 for 312.50% scaling
3.1875 for 318.75% scaling
3.2500 for 325.00% scaling
3.3125 for 331.25% scaling
3.3750 for 337.50% scaling
3.4375 for 343.75% scaling
3.5000 for 350.00% scaling
3.5625 for 356.25% scaling
3.6250 for 362.50% scaling
3.6875 for 368.75% scaling
3.7500 for 375.00% scaling
3.8125 for 381.25% scaling
3.8750 for 387.50% scaling
3.9375 for 393.75% scaling
4.0000 for 400.00% scaling
```

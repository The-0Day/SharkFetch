# SharkFetch
  an Eye-Candy Customizable CLI System Information Tool 

## Installation
### One-Linear Install
```
sudo wget https://raw.githubusercontent.com/The-0Day/Shark-Fetch/main/sharkfetch -O /usr/local/bin/sharkfetch && sudo chmod +x /usr/local/bin/sharkfetch
```
### Clone & Install
```
git clone https://github.com/The-0Day/Zero-Fetch.git
```

Make The File Executable And Put sharkfetch In ```/usr/local/bin```
```
cd Zero-Fetch
chmod +x zerofetch
sudo cp zerofetch /usr/local/bin
```


## Themes
This Script Can Loads ASCII Art as Themes, It Has 3 Default Themes but You Can Use Your Custom Themes Too.
Recommended Size For Your ASCII Art is 40x20

For Load Your Theme Just Once (In Directory which Your Theme Located Too (example.txt)):
  ```sharkfetch -t example.txt```

But You Can Import Your Theme in Configuration Directory and Use it Several Times:
First of All Put Your Theme File in ```~/.config/SharkFetch/themes/```
its Better to Remove .txt Extension From The File, Then
  ```sharkfetch -t example
     #it will use theme ~/.config/SharkFetch/themes/example```

     
  

***Shark Theme (Default)***

![](Images/Shark.png)

***Arch Theme***

![](Images/Arch.png)

***Halloween Theme***

![](Images/Halloween.png)







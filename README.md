# SharkFetch
  an Eye-Candy Customizable CLI System Information Tool 

## Installation
### One-Linear Install
```
sudo wget https://raw.githubusercontent.com/The-0Day/Shark-Fetch/main/sharkfetch -O /usr/local/bin/sharkfetch && sudo chmod +x /usr/local/bin/sharkfetch
```
### Clone & Install
```
git clone https://github.com/The-0Day/SharkFetch.git
```

Make The File Executable And Put sharkfetch In ```/usr/local/bin```
```
cd SharkFetch
chmod +x sharkfetch
sudo cp sharkfetch /usr/local/bin
```


## Themes
This Script Can Loads ASCII Art as Themes, It Has 3 Default Themes but You Can Use Your Custom Themes Too.<br/>
You Can Use [This Project](https://github.com/TheZoraiz/ascii-image-converter) to Make ASCII Arts.
Recommended Size For Your ASCII Art is 40x20


For Loading Your Theme Just Once:<br/>\
(In Directory which Your Theme Located Too (example.txt))
  ```sharkfetch -t example.txt```

But You Can Import Your Theme in Configuration Directory and Use it Several Times: <br/>
First of All Put Your Theme File in ```~/.config/SharkFetch/themes/```<br/>
its Better to Remove .txt Extension From The File, Then<br/>
  ```sharkfetch -t example```<br>
      it will use ~/.config/SharkFetch/themes/example theme

<br/>Tip: You Can Findout Available Themes With ```--list``` or ```-l``` Switch.<br/>
Note: If You Made an Awesome Theme which You Think Maybe Someone Likes too, Feel Free to PR it On ```Users_Themes``` Directory of Main Repo.

### Known Issues
#### Icons Issue
If Your Terminal Doesnt Show Icons Well, You Have to Install a Nerd Font.<br/>
##### Install Our Recommended Font:
``` wget https://github.com/The-0Day/Shark-Fetch/raw/main/JetBrains%20Mono%20Regular%20Nerd%20Font%20Complete%20Mono.ttf -O '~/.fonts/JetBrains Mono Regular Nerd Font.ttf' && fc-cache -f```<br/>
After Install, Go to Your Terminal's Configuration and Select Jetbrains Font As Default.

### Bonus Tip
Enter ```sharkfetch -t wood``` and You Will See The Big Wood Guy :D

### Contribution
Open Source Projects alive with contribution and without participation a lot of daily used projects remain at the first step.<br/>
Feel Free to Tell us Your Ideas and PR if This Script Has Bugs on your Distro.


### Credits:
[Ali F](https://github.com/Ali-Frh) (@ShopBoy)<br/>
[The-0Day](https://github.com/The-0Day)

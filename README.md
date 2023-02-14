### Result:
![image](https://user-images.githubusercontent.com/36964755/218855206-bd8e25e5-76e1-40f5-9c44-3d250534c16e.png)

### To do so:
#### 1) Install TST extension
Firslty, you need to install "Tree Style Tabs" extension from here: <br/>
https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search <br/>

#### 2) Enable following flags
Go to <br/>
**about:config** <br/>
and set to **True** following:
```
toolkit.legacyUserProfileCustomizations.stylesheets
```
#### 3) Apply css file
Download **chrome** folder from this repository and put it in your profile folder <br/> 
To find out its location go to 
```
Menu -> Help -> More troubleshooting information -> Profile Directory
```
![image](https://user-images.githubusercontent.com/36964755/218854530-459d4480-65b9-437e-8a4c-345e0e58b3bb.png)
For flatpack users, profile folder located here:
```
~/.var/app/org.mozilla.firefox/.mozilla/firefox/[profile name]
```
#### 4) Some minor tweaks
You could consider move TST icon to left side of toolbar, as by default - it hidden in "Extenions" icon. To do so: <br/>
Click on "Extenions" icon -> Settings icon near TST extension -> Check "Pin to toolbar" <br/>
Then, click on Firefox menu icon -> Mote tools -> Customize toolbar... -> Move TST icon to the place you think is best for you.
Also, to make TST look more like Firefox native screen:
Right click on its icon -> Appearance -> Theme -> Photon
#### 5) Restart Firefox
After restart of firefox new theme would be applied


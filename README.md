# thunderbird-monterail

This is a set of userChrome.css files to change the look of Thunderbird, inspired by the mockup by Monterail here:
https://monterail.com/blog/2016/the-power-of-email-clients-why-did-we-redesign-thunderbird?utm_source=Thunderbird&utm_campaign=Dribbble&utm_medium=blogpost%22

- 4 css files are included for a light theme, dark theme, full-dark theme and coloured theme using monterail inspired colours.
- EncodeSans Narrow is included and used as the font throughout thunderbird.
- Also inluded is a set of svg icons which replace the default Thunderbird icons, mostly taken from the incredible Font-Awesome (http://fontawesome.io)

## How to use these themes
To use these themes, the easiest way is to download the thunderbird-monterail.zip folder and extract its contents to your
thunderbird user config directory. This will create the chrome folder (if it doesn't exist) containing the icons, font, and all the css files.

Simply copy the css file for whichever theme you want to use and **rename it userChrome.css** and then **restart Thunderbird** (ex. if you want to use the dark theme, you should rename the file userChrome-dark.css to userChrome.css).

In **Windows OS** the chrome folder must be extracted in C:\Users\\*[user\]*\AppData\Roaming\Thunderbird\Profiles\\*[random letters and numbers\]*.default/

In **Linux** it must be extracted in /home/*\[user\]*/.thunderbird/*\[random letters and numbers\]*.default/

If your profile is located in a different directory, you can find it by going in Thunderbird's preferences (Tools->Options->Advanced). After that, click the 'Config Editor' button, accept the warning and then search for *directory*. Your directory should be the value of the parameter *mail.server.server1.directory*. This is the path where you should extract the chrome folder.


## Screenshots
Light:
![alt text](https://raw.githubusercontent.com/spymastermatt/thunderbird-monterail/master/screenshots/light.png)

Dark:
![alt text](https://raw.githubusercontent.com/spymastermatt/thunderbird-monterail/master/screenshots/dark.png)

Full Dark:
![alt text](https://raw.githubusercontent.com/spymastermatt/thunderbird-monterail/master/screenshots/fulldark.png)

Monterail:
![alt text](https://raw.githubusercontent.com/spymastermatt/thunderbird-monterail/master/screenshots/monterail.png)

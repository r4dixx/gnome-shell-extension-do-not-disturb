# Do Not Disturb Gnome Shell Extension
Enable or disable do not disturb mode. 

Do not disturb mode will block notifications from appearing on the screen, but will display a dot next to the date indicating that a notification has arrived.

![Do not disturb](screenshots/do-not-disturb.png)


## Installation
To install, clone this repo and use make to install

```shell
$ git clone https://github.com/kylecorry31/gnome-shell-extension-do-not-disturb
$ cd gnome-shell-extension-do-not-disturb
$ make
$ make install
```

The extension then must be enabled using Gnome Tweak Tool or https://extensions.gnome.org/local/

## Usage
Once the extension is enabled, open the notification panel by clicking on the date in the top bar and click the toggle at the bottom of that panel for do not disturb. To deactive it, follow the same instructions, but toggle the do not distub off. 

## Contributing
Please fork this repo and submit a pull request to contribute. I will review all changes and respond if they are accepted or rejected (as well as reasons, so it will be accepted). I am working with System76 to ensure this extension fits into Pop!\_OS, so some changes may not be approved or will need to be modified upon their request. 

## Credits
The implementation has been done by me, and employees from System76 have added debian packaging in their fork for inclusion into Pop!\_OS. The specifications for this project came from employees of System76, check out their work at [pop-os](https://github.com/pop-os).

## License
This project is published under the [MIT License](LICENSE).   
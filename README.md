# MMM-KoranGerman
The `MMM-KoranGerman` module is like the default module `compliments` of MagicMirror2 with the difference that the `MMM-KoranGerman` module does not show Compliments but German translation of verses from the Koran.

This module displays random Verses of Koran.

## Screenshots
![Compliments Screenshot](MMM-KoranGerman-1.png)
![Compliments Screenshot](MMM-KoranGerman-2.png) ![Compliments Screenshot](MMM-KoranGerman-3.png)



## Using the module

Open Terminal and:
```
cd ~/MagicMirror/modules/default
git clone https://github.com/jakobsarwary1/MMM-KoranGerman
```

go to `MagicMirror/modules/default`, open ```defaultmodules.js``` 
Add ```"MMM-KoranGerman",``` to the list.

Now add:
```
{
    module: "MMM-KoranGerman",
		position: "lower_third",
},
```
to the modules array in the `MagicMirror/config/config.js` file and save it.
Reboot your Mirror and you should have it (Inscha'Allah).


#### Multi-line:
Use `\n` to split text into multiple lines, e.g. `First line.\nSecond line.` will be shown as:
```
First line.
Second line.
```

Here you can follow the default installation instructions for the [Magic Mirror²](https://github.com/MichMich/MagicMirror) project.

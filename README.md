# Module: MMM-KoranGerman
# MMM-KoranGerman

The `MMM-KoranGerman` module is like the default module `Compliments` of MagicMirror2 with the difference that the `MMM-KoranGerman` module does not show Compliments but German translation of verses from the Koran.

This module displays random Verses of Koran.

## Screenshots
![Compliments Screenshot](MMM-KoranGerman-1.png)
![Compliments Screenshot](MMM-KoranGerman-2.png)
![Compliments Screenshot](MMM-KoranGerman-3.png)
![Compliments Screenshot](MMM-KoranGerman-4.png)

## Using the module

```bash
cd ~/MagicMirror/modules/default
git clone https://github.com/jakobsarwary1/MMM-KoranGerman
```

Go to MagicMirror/modules/default and open ```defaultmodules.js``` 
Add ```"MMM-KoranGerman",``` to the list.

Here you can follow the default installation instructions for the [Magic Mirror²](https://github.com/MichMich/MagicMirror) project.

Now add:
```		{
			module: "MMM-KoranGerman",
			position: "lower_third",
			
		},
```
to the modules array in the `MagicMirror/config/config.js` file and save it.
Reboot your Mirror and you should have it (Inscha'Allah)

#### Multi-line:
Use `\n` to split text into multiple lines, e.g. `First line.\nSecond line.` will be shown as:
```
First line.
Second line.
```


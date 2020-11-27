# MMM-Koran-German

# Module: MMM-Koran-German
The `MMM-Koran-German` module is like the default module `Compliments` of MagicMirror2 with the difference that the `MMM-Koran-German` module does not show Compliments but German translation of verses from the Koran.

This module displays a random Verses of Koran.

## Screenshots
![Compliments Screenshot](MMM-Koran-German-1.png)
![Compliments Screenshot](MMM-Koran-German-2.png)
![Compliments Screenshot](MMM-Koran-German-3.png)
![Compliments Screenshot](MMM-Koran-German-4.png)

## Using the module

To use this module, add it to the modules array in the `config/config.js` file:
````javascript
modules: [
	{
		module: "MMM-Koran-German",
		position: "lower_third",	// This can be any of the regions.
						// Best results in one of the middle regions like: lower_third

#### Multi-line:
Use `\n` to split text into multiple lines, e.g. `First line.\nSecond line.` will be shown as:
```
First line.
Second line.
```


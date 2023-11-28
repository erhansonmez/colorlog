![colorlog](https://raw.githubusercontent.com/erhansonmez/colorlog/main/color-log.js.png)

```javascript
// with npm install
// const { consolelog, strColorizer } = require('@erhansonmez/colorlog');

const { consolelog, strColorizer } = require('./colorlog.js');

// Modern logger
console.log({ Red: "Hello world!" });

// Leagcy logger
consolelog("Hello world!");

// Colorize
consolelog(strColorizer({ BgGreen: "Hello world!" }));

consolelog(
	strColorizer({
	    Reset: "Reset",
	    Bright: "Bright",
	    Dim: "Dim",
	    Underscore: "Underscore",
	    Blink: "Blink",
	    Reverse: "Reverse",
	    Hidden: "Hidden",
	    Black: "Black",
	    Red: "Red",
	    Green: "Green",
	    Yellow: "Yellow",
	    Blue: "Blue",
	    Magenta: "Magenta",
	    Cyan: "Cyan",
	    White: "White",
	    Gray: "Gray",
	    BgBlack: "BgBlack",
	    BgRed: "BgRed",
	    BgGreen: "BgGreen",
	    BgYellow: "BgYellow",
	    BgBlue: "BgBlue",
	    BgMagenta: "BgMagenta",
	    BgCyan: "BgCyan",
	    BgWhite: "BgWhite",
	    BgGray: "BgGray"
	})
);
```

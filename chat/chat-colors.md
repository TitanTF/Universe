# Chat Colors

Every player is able to freely customize the colors of their chat messages with the use of some simple chat formatting. Everyone in the server is able to see the formatting.

{% hint style="info" %}
These colors will override any custom chat paint equipped while using this feature.
{% endhint %}

## Getting Started

NOTE: The syntax only accepts hexadecimals.

If you do not have any colors in mind, you can start by clicking [here](https://www.webpagefx.com/web-design/color-picker/). Drag to the color you want and copy the 6 digit number \(beside the \# symbol\) above the color palette.

### Converting to HEX

If you have the red, green and blue \(RGB\) values of a color, you can convert them [here](https://www.webpagefx.com/web-design/hex-to-rgb/).

## Formatting

### Standard Coloring

Include a hex symbol `#`, followed by the 6 digit hex code, in front of all the text you want to be colored with that color.

The format for standard coloring is `#(hex symbol) XXXXXX(6 digit hex value)`.

Eg. `#000000Hello, World` will print a black `Hello, World`

### Transparency Coloring

Transparency adds a new dimension of customizing the colors of your chat messages.

Include 2 hex symbols `##`, followed by the 6 digit hex code and then the transparency value, infront of all the text you want to be colored with that color. The transparency value ranges from 00 \(least visible\) to 99 \(most visible\).

The format for transparency is `##(2 hex symbols) XXXXXX(6 digit hex value) YY(transparency)`.

Eg. 80% transparency would be `##00000080Hello, World`, which will print a black `Hello, World` which is 80% visible.

### Multi Coloring

You can do both Standard and Transparency Coloring multiple times in a single chat message. These codes will only override the colors of the text after the code. However, there is a character limit for every chat message sent.

Eg. `#000000The fox ran over the #FF4040lazy dog#000000.`


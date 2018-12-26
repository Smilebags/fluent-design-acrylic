# Microsoft Fluent Design Acrylic Material

_This [does not work in all browsers](https://caniuse.com/#feat=css-backdrop-filter) yet, as it relies on the css `backdrop-filter` property which is not yet available in Chrome or Firefox._

This is an experiment into recreating the _Acrylic_ material which can be found throughout the Windows 10 UI.
It involves multiple layers, including a backdrop blur, mix with a dark or light colour, then overlaying a grain texture on top. [Reference](https://docs.microsoft.com/en-us/windows/uwp/design/style/images/acrylicrecipe_diagram.jpg)

With documentation found on [Microsoft's Blog](https://docs.microsoft.com/en-us/windows/uwp/design/style/acrylic), I have recreated the effect as accurately as possible using CSS3.

Currently, the only browser to fully support the CSS is Edge, but it is available in Chrome behind a flag. It is also available in Safari with the `-webkit-` prefix.

# svg-readme-experiments

> scratch-pad for svg readme experiments


## SVG over Raster - Pros and Cons

**Pros**

- SVG string more versionable than raster
- SVG smaller files-ize than raster
- No loss of color-space or luma-space during compression 
- Looks good at large resolutions
- Looks sharper than PNG/JPG at regular resolutions

**Cons**

- You will need 'SourceCodePro Nerd Font', etc, to see powerline output correctly

## Small Test

SVG

![ansi-to-svg-3.svg](ansi-to-svg-3.svg)

iTerm2 Screenshot (zoomed in)

![wish-command-terminal-screenshot.png](wish-command-terminal-screenshot.png)

## Powerline Compatibility

SVG Output - (1k)

![powerline-bg-color-touch.svg](powerline-bg-color-touch.svg)

PNG Screenshot from iTerm2 - (\~88k @ \~retina-res: \~2800x\~140px)

![powerline-bg-color-touch-screenshot.png](powerline-bg-color-touch-screenshot.png)

## Emoji Compatibility

![with-emojis.svg](with-emojis.svg)

## All Styles

![ansi-to-svg-2.svg](ansi-to-svg-2.svg)

## No Font in SVG

Attempting to provide font around SVG. WIll not work as SVG is an image tag.

```html
<font face="Courier" size="14px"><img src="./ansi-to-svg-no-font.svg"/></font>
```

<font face="Courier" size="14px"><img src="./ansi-to-svg-no-font.svg"/></font>

```html
<span style="font-family: Courier; font-size: 14px;"><img src="./ansi-to-svg-no-font.svg"/></span>
```

<span style="font-family: Courier; font-size: 14px;"><img src="./ansi-to-svg-no-font.svg"/></span>
	

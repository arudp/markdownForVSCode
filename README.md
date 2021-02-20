# markdownForVSCode

Anyone can fork this (or use it as is) and easily have a nice custom theme for Markdown Preview in VSCode.

## Usage
To use it the only thing to do is add the following lines to the `settings.json` file:

```json
"markdown.styles": [
  "https://raw.githack.com/arudp/markdownForVSCode/main/markdown.css"
],
```

> **Hey, but why GitHack?**  
> [GitHack](https://raw.githack.com/) allows to download a raw file and for it to be interpreted in the correct way instead of as a plain text. For example, if anyone were to use the `markdown.css` file referencing it in VSCode as a raw file from GitHub it wouldn't work because the content type would be _plain text_, so VSCode can't interpret it as a valid file for CSS. With GitHack, VSCode is able to understand it as a CSS file and use it to style the Markdown Preview.

## Fork
If you want to fork it you can just use it as a template to improve it to your taste or if you like the shape of things but not the colours you can just go ahead and change the variables in the first lines. Note that the colours are written twice, once for light themes and once for dark themes so VSCode uses one or the other depending on the type of theme you're using.  
Of course, if you do fork it, make sure that you use the correct URL in your `settings.json`: https://raw.githack.com/$MY_USER/markdownForVSCode/main/markdown.css

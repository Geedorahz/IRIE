# Themes

In **Settings > Appearance**, press **Create new theme**. The theme maker sets the wallpaper (an image, GIF or video), colors, panel strength and music, and shows every change straight away.

- **Share theme** saves one `.irietheme` file that anyone can bring in with **Import theme**.
- With a theme on, panels turn to glass, so any wallpaper or color works.

## Going further with CSS

Each theme has its own folder in `%APPDATA%\IRIE\themes`, with a `theme.css` inside. Any CSS works. Images and fonts in that folder can be used with `url('name.png')`, and saving the file updates IRIE immediately.

The most useful values to change are variables on `:root`:

```css
:root {
  --sky-top: #052a57;      /* top of the background */
  --sky-mid: #0a6fb0;
  --sky-low: #3ccad8;
  --ring: #ffffff;         /* selection outline */
  --glow: #7fe6ff;         /* selection glow */
  --tile: 150px;           /* game tile size */
  --radius: 26%;           /* tile corner roundness */
}
```

Hide the drifting lights, bubbles or waves:

```css
#scene, #bubbles, #waves { display: none; }
```

# Starfield

A simple animated starfield background rendered on an HTML5 canvas.

## Demo

View the live demo here: [https://codemoreira.github.io/html-starfield](https://codemoreira.github.io/html-starfield)

## Embedding the Starfield

You can embed the starfield on your website using an `<iframe>`:

```html
<iframe
  src="https://codemoreira.github.io/html-starfield"
  width="100%"
  height="400"
  style="border:none; background:black;"
>
</iframe>
```

## Customization

You can control the starfield’s appearance using URL query parameters:

- `num_particles`: Number of stars (default: 100)
- `speed`: Base speed of stars (default: 0.5)
- `lifetime`: Lifetime of each star in frames (default: 200)
- `color_palette`: Comma-separated list of hex colors (without `#`, e.g. `fff,0ff,ff0`)
- `min_size`: Minimum star size in pixels (default: 1)
- `max_size`: Maximum star size in pixels (default: 3)

**Example:**

```html
<iframe
  src="https://codemoreira.github.io/html-starfield?num_particles=200&speed=1&lifetime=300&color_palette=fff,0ff,ff0&min_size=2&max_size=5"
  width="100%"
  height="400"
  style="border:none; background:black;"
>
</iframe>
```

This will show 200 stars, move them faster, make them last longer, use white/cyan/yellow colors, and set star sizes between 2 and 5 pixels.

**Tip:**  
You can adjust the `width` and `height` attributes to fit your

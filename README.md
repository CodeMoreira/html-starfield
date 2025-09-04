## Embedding the Starfield

You can embed the starfield on your website using an `<iframe>`.  
Just use the following code:

```html
<iframe
  src="https://codemoreira.github.io/html-starfield"
  width="100%"
  height="400"
  style="border:none; background:black;"
>
</iframe>
```

## Customizing the Starfield

You can control the starfield’s appearance using URL query parameters:

- `num_particles`: Number of stars (default: 100)
- `speed`: Base speed of stars (default: 0.5)
- `lifetime`: Lifetime of each star in frames (default: 200)
- `color_palette`: Comma-separated list of hex colors (without `#`)

**Example:**

```html
<iframe
  src="https://codemoreira.github.io/html-starfield?num_particles=200&speed=1&lifetime=300&color_palette=fff,0ff,ff0"
  width="100%"
  height="400"
  style="border:none; background:black;"
>
</iframe>
```

This will show 200 stars, move them faster, make them last longer, and use white, cyan, and yellow colors.

**Tip:**  
You can adjust the `width` and `height` attributes

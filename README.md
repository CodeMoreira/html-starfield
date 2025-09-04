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

## Examples

Explore different starfield configurations by changing speed, size, lifetime, particle count, and colors.

1. **Hyper Speed Starstorm** – extremely fast stars, small and dense  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=500&speed=5&lifetime=100&color_palette=FFFFFF&min_size=1&max_size=2)

2. **Giant Stars** – very large stars, slow-moving  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=50&speed=0.1&lifetime=300&color_palette=FFFF00,FFA500&min_size=10&max_size=20)

3. **Tiny Twinkles** – many tiny stars, subtle effect  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=1000&speed=0.05&lifetime=150&color_palette=FFFFFF&min_size=0.2&max_size=0.8)

4. **Rainbow Galaxy** – multicolor chaos  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=200&speed=0.8&lifetime=200&color_palette=FF0000,00FF00,0000FF,FFFF00,FF00FF,00FFFF&min_size=2&max_size=5)

5. **Slow Drift, Large Glow** – slow, huge stars for dreamy effect  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=80&speed=0.1&lifetime=400&color_palette=FFFFFF,ADD8E6,FFE4E1&min_size=5&max_size=15)

6. **Short-Lived Sparks** – very quick stars fading fast  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=150&speed=2&lifetime=50&color_palette=FFFFFF,FFD700&min_size=1&max_size=3)

7. **Dense Starfield** – extremely dense, moderate speed  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=2000&speed=0.4&lifetime=250&color_palette=FFFFFF&min_size=1&max_size=2)

8. **Slow Rainbow Drift** – slow rainbow stars for visual variety  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=150&speed=0.1&lifetime=300&color_palette=FF0000,FFA500,FFFF00,00FF00,0000FF,4B0082,EE82EE&min_size=2&max_size=4)

9. **Fast Flicker** – tiny fast stars that appear and disappear quickly  
   [View Example](https://codemoreira.github.io/html-starfield?num_particles=300&speed=3&lifetime=30&color_palette=FFFFFF&min_size=0.5&max_size=1.5)

10. **Extreme Multicolor Chaos** – maximum colors, high particle count  
    [View Example](https://codemoreira.github.io/html-starfield?num_particles=500&speed=1.5&lifetime=200&color_palette=FF0000,00FF00,0000FF,FFFF00,FF00FF,00FFFF,FFA500,800080,FFC0CB&min_size=1&max_size=6)

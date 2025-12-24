# Reusable Footer

A clean, responsive footer built with HTML and CSS.  
Designed to be reused across projects with minimal setup.

## Features
- Responsive layout (Flexbox)
- Themeable with CSS variables
- Accessible, semantic markup
- No JavaScript or framework

## How to Use
1. Copy the footer HTML
2. Link `footer.css`
3. Use this layout:

```css
body {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

main {
  flex: 1;
}
```

## Customization
```css
.footer {
  --bg: #fff;
  --primary-text: #111;
  --secondary-text: #555;
  --border: 1px solid #ddd;
}
```

## Files
```
footer.html
footer.css
```

## Browser Support
Works in all modern browsers.

## License
Free to use for personal and commercial projects.

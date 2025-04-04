# CSS View-Timeline Parallax Effect

This repository demonstrates how to create a smooth parallax scrolling effect using only CSS, leveraging the modern `view-timeline` property. No JavaScript required!

## 📺 Demo Video

Check out the full demonstration and explanation in this video:

[![CSS Parallax Effect with view-timeline](https://img.youtube.com/vi/yalrA7pIXO8/0.jpg)](https://youtu.be/yalrA7pIXO8)

## 🚀 Features

- Pure CSS parallax scrolling effect
- Leverages the modern `view-timeline` API
- No JavaScript dependencies
- Smooth animations tied to scroll position
- Fully responsive design

## 🔧 How It Works

The parallax effect is achieved using CSS `view-timeline` - a powerful animation feature that allows you to synchronize animations with the element's position in the viewport. This technique creates depth and dimension as users scroll through the page.

```css
.parallax-element {
  animation-timeline: view();
  animation-name: parallax;
  animation-fill-mode: both;
  animation-range: entry 0% to exit 100%;
}

@keyframes parallax {
  from {
    transform: translateY(0);
  }
  to {
    transform: translateY(-20%);
  }
}
```

## 🛠️ Getting Started

1. Clone this repository
2. Open `index.html` in your browser
3. Scroll to see the parallax effect in action!

## 🌐 Browser Compatibility

This technique uses cutting-edge CSS features. For best results, use the latest versions of Chrome, Firefox, or Edge.

## 📚 Learn More

For more web development tutorials and projects:
- YouTube: [Chunky Dev](https://www.youtube.com/@chunkydotdev)
- Check out the other repositories in this account

## 📝 License

MIT 
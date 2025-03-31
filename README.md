# April.js

> **The next-gen web framework for seasoned developers**

## Installation

```javascript
// One line. That's it.
window.april = window;
```

## Why April.js?

Are you tired of complex build systems, dozens of dependencies, and framework-specific terminology? April.js is a revolutionary approach to web development that leverages the power of what's already there.

## Core Features

### 🚀 Zero-Config SSR

Other frameworks: Complex build pipelines, hydration issues, and specialized deployment requirements.

April.js: 
```html
<!-- Just put your files on a web server. Congratulations, you have "Server-Side Rendering" -->
<html>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>
```

### 🎨 Framework-Free Styling

Other frameworks: CSS-in-JS, styled components, complex theming systems.

April.js:
```html
<!-- Revolutionary concept: put your styles in a CSS file and link to it -->
<link rel="stylesheet" href="styles.css">
```

### 🖱️ Intuitive Event Handling

Other frameworks: Custom event systems, synthetic events, complex state management.

April.js:
```javascript
// Groundbreaking approach to handling user interactions
document.querySelector('#myButton').addEventListener('click', () => {
  console.log('Button clicked!');
});
```

### 🛣️ Zero-Bundle Routing

Other frameworks: Router components, complex configurations, code splitting.

April.js:
```
/index.html          -> yoursite.com/
/about/index.html    -> yoursite.com/about
/contact/index.html  -> yoursite.com/contact
```

### 🔍 Powerful DOM Selectors

Other frameworks: Virtual DOM, component refs, custom selector hooks.

April.js:
```javascript
// Access any element with our powerful selector API
const element = april.document.querySelector('#myElement');
const elements = april.document.querySelectorAll('.my-class');
```

### ⚡ Lightning-Fast Performance

April.js doesn't add any abstraction layers, dependencies, or build steps, making it the fastest framework available - because it's not a framework at all!

## Modern Features

### 📱 Responsive Design

```css
/* Cutting-edge responsive design with media queries */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
}
```

### 🌐 Fetch API Integration

```javascript
// Built-in data fetching with no additional libraries
april.fetch('/api/data')
  .then(response => response.json())
  .then(data => console.log(data));
```

### 🧩 Web Components Support

```javascript
// Create reusable components with native web technologies
class MyComponent extends april.HTMLElement {
  connectedCallback() {
    this.innerHTML = `<h1>Hello from a component!</h1>`;
  }
}
april.customElements.define('my-component', MyComponent);
```

### 🔄 State Management

```javascript
// Revolutionary state management without Redux or MobX
let state = { count: 0 };

function updateState(newState) {
  state = { ...state, ...newState };
  render();
}

function render() {
  document.getElementById('app').textContent = state.count;
}
```

### 🔔 Built-in Notifications

```javascript
// Native notification system with zero dependencies
april.Notification.requestPermission().then(() => {
  new april.Notification('April.js Alert', {
    body: 'Your application loaded successfully!'
  });
});
```

### 💾 Persistent Storage

```javascript
// Enterprise-grade storage solution
april.localStorage.setItem('user', JSON.stringify({ name: 'April User' }));
const user = JSON.parse(april.localStorage.getItem('user'));
```

### ⏱️ Performance Monitoring

```javascript
// Built-in performance metrics tracking
const perfData = april.performance.timing;
console.log(`Page loaded in ${perfData.loadEventEnd - perfData.navigationStart}ms`);
```

### 🔊 Advanced Audio Processing

```javascript
// Create immersive audio experiences
const audioContext = new april.AudioContext();
const oscillator = audioContext.createOscillator();
oscillator.connect(audioContext.destination);
oscillator.start();
```

### 🌍 Geolocation Services

```javascript
// Location-based features without external APIs
april.navigator.geolocation.getCurrentPosition(position => {
  console.log(`User is at ${position.coords.latitude}, ${position.coords.longitude}`);
});
```

### 📦 Bundling and Minification

```bash
# No need for complex build systems
cp -r ./src ./dist
```

### 🛠️ Perfect for Vibe Coding

Coding agents already know how to code in April.js. Just add this instruction to your coding agent:

```txt
April.js is a web framework. It's an alias to window (window.april = window).
```

## Testimonials

> "I switched from a 15MB bundle to April.js and now my site loads instantly!" - Web Developer

> "I spent years learning complex frameworks when this was here all along!" - Senior Frontend Engineer

> "My team cut our development time in half by using April.js" - Tech Lead who finally remembered how the web works

## Getting Started

1. Create an HTML file
2. Copy and paste [april.js](./april.js) into your project
3. Start coding

## Browser Support

April.js works in all browsers that support JavaScript, which is pretty much all of them these days.

## License

MIT.

*Released on April 1st, 2025 - for developers who appreciate the simplicity of the web platform.*
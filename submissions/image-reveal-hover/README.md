# Image Reveal Hover Component

A smooth, high-performance slide-and-reveal hover component built for the **EaseMotion CSS** framework ecosystem. It utilizes hardware-accelerated CSS properties (`transform`) combined with a custom cubic-bezier timing curve for fluid interaction.

## Files Included
* `demo.html` - Minimal canvas mockup demonstrating the wrapper structure.
* `style.css` - Core layout classes, transform matrix modifiers, and state changes.

## How It Works
The component utilizes an absolute-positioned overlay element block layer set to `transform: translateX(0)`. On wrapper hover, it shifts out of bounds completely to expose the underlying asset canvas, while simultaneously removing grayscale filters and managing container layout zoom scales.
# Cursor & Animations

Windows23 uses a fully custom animated cursor:

## Features
- Emoji cursor (`🖱️`) by default
- Spring physics movement
- Click animations with color and rotation effects
- Scroll animations
- Idle animations loop

## Implementation
- Built using **Framer Motion**
- Cursor position tracked via `mousemove`
- Click and scroll tracked via `mousedown` and `wheel` events
- Optional: customize emoji and animations in `CustomCursor.jsx`

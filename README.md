# 3D Turtle Graphics

An animated 3D HTML document that implements turtle graphics in three dimensions using pure JavaScript and HTML5 Canvas.

## Features

- **Full 3D Turtle Graphics**: Move and draw in three-dimensional space
- **Smooth Animations**: All turtle movements are smoothly animated
- **Interactive 3D View**: Mouse controls to rotate and zoom the 3D scene
- **Multiple Drawing Functions**: Pre-built functions for common shapes
- **Real-time Feedback**: Live position and rotation display

## Controls

### Basic Turtle Commands
- **Forward**: Move turtle forward in current direction
- **⟲ Left / ⟳ Right**: Rotate turtle left/right (yaw)
- **⬆ Pitch Up / ⬇ Pitch Down**: Rotate turtle up/down (pitch)
- **↺ Roll L / ↻ Roll R**: Roll turtle left/right
- **Pen Up/Down**: Control whether turtle draws while moving
- **Clear**: Reset turtle position and clear all drawings

### Preset Drawings
- **Square**: Draw a 2D square
- **Cube**: Draw a 3D cube wireframe
- **Spiral**: Draw a 3D spiral ascending vertically
- **Demo**: Animated 3D flower pattern

### 3D View Controls
- **Mouse Drag**: Rotate the 3D view
- **Mouse Scroll**: Zoom in/out

## Technical Features

- Pure JavaScript implementation with no external dependencies
- 3D vector math and perspective projection
- Smooth interpolated animations
- Real-time 3D rendering using HTML5 Canvas 2D context
- Interactive camera controls
- Queue-based animation system for smooth sequential movements

## Usage

Simply open `index.html` in a modern web browser. The 3D turtle graphics system will load immediately and be ready to use.

## API

The turtle object provides a programming interface:

```javascript
turtle.forward(distance)    // Move forward
turtle.turnLeft(angle)      // Turn left (degrees)
turtle.turnRight(angle)     // Turn right (degrees)
turtle.pitchUp(angle)       // Pitch up (degrees)
turtle.pitchDown(angle)     // Pitch down (degrees)
turtle.rollLeft(angle)      // Roll left (degrees)
turtle.rollRight(angle)     // Roll right (degrees)
turtle.penUp()              // Lift pen (stop drawing)
turtle.penDown()            // Put pen down (start drawing)
turtle.clear()              // Clear all drawings and reset
```

## Examples

All animations are queued and executed smoothly in sequence.

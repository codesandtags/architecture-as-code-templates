# Excalidraw Guide

## What is Excalidraw?

**Excalidraw** is a virtual whiteboard for sketching hand-drawn like diagrams. It's perfect for creating quick architectural diagrams, wireframes, flowcharts, and collaborative sketches.

## Why Use Excalidraw?

- **Hand-drawn aesthetic**: Creates informal, approachable diagrams
- **Real-time collaboration**: Multiple people can edit simultaneously
- **No account required**: Works in browser without signup
- **Export options**: PNG, SVG, and more
- **Free and open source**: No licensing costs
- **Easy to use**: Intuitive interface with minimal learning curve

## Getting Started

### Basic Setup

1. Go to [excalidraw.com](https://excalidraw.com)
2. Start drawing immediately (no signup required)
3. Share the link for collaboration
4. Export when done

### Key Features

- **Shapes**: Rectangle, circle, diamond, arrow, line
- **Text**: Add labels and annotations
- **Colors**: Change stroke and fill colors
- **Layers**: Organize elements
- **Groups**: Group related elements
- **Libraries**: Import custom shapes and icons

## Architecture Diagram Best Practices

### 1. System Architecture Diagrams

**Elements to include:**

- **Boxes** for systems/services
- **Arrows** for data flow
- **Labels** for clear identification
- **Colors** for different types of components

**Example structure:**

```
[User] → [Frontend] → [API Gateway] → [Services] → [Database]
```

### 2. Network Diagrams

**Elements to include:**

- **Routers/Switches** (rectangles)
- **Servers** (rectangles with labels)
- **Connections** (lines with labels)
- **Internet/Cloud** (cloud shapes)

### 3. Data Flow Diagrams

**Elements to include:**

- **Processes** (circles or rectangles)
- **Data stores** (open rectangles)
- **External entities** (rectangles)
- **Data flows** (arrows with labels)

## Excalidraw Tips and Tricks

### Drawing Tips

- **Hold Shift** while drawing for perfect shapes
- **Double-click** to edit text
- **Right-click** for context menu
- **Ctrl/Cmd + Z** to undo
- **Ctrl/Cmd + D** to duplicate
- **Ctrl/Cmd + G** to group elements

### Organization Tips

- **Use layers** to separate different types of elements
- **Group related elements** together
- **Use consistent colors** for similar components
- **Add a legend** to explain symbols and colors
- **Use text boxes** for annotations

### Collaboration Tips

- **Share the link** for real-time collaboration
- **Use different colors** for different contributors
- **Add comments** using text boxes
- **Save versions** by exporting periodically

## Common Diagram Types

### 1. System Context Diagram

- **Central system** in the middle
- **External actors** around the edges
- **Interactions** shown with arrows

### 2. Container Diagram

- **Containers** as rectangles
- **Technologies** as labels
- **Connections** showing communication

### 3. Component Diagram

- **Components** as rectangles
- **Dependencies** as arrows
- **Interfaces** clearly labeled

### 4. Sequence Diagram

- **Actors** as vertical lines
- **Messages** as horizontal arrows
- **Time flow** from top to bottom

### 5. User Journey Map

- **User actions** as steps
- **Emotions** as annotations
- **Touchpoints** as boxes

## Excalidraw vs Other Tools

| Tool       | Best For                      | Pros                             | Cons                               |
| ---------- | ----------------------------- | -------------------------------- | ---------------------------------- |
| Excalidraw | Quick sketches, collaboration | Free, easy, real-time            | Limited shapes, no version control |
| Mermaid    | Code-based diagrams           | Version control, automated       | Less flexible, learning curve      |
| Draw.io    | Professional diagrams         | Many shapes, templates           | More complex, not real-time        |
| Figma      | Design and prototyping        | Advanced features, collaboration | Overkill for simple diagrams       |
| Lucidchart | Enterprise diagrams           | Professional, templates          | Expensive, complex                 |

## Integration with Your Workflow

### With Mermaid

- Use Excalidraw for **initial brainstorming**
- Convert to Mermaid for **version control**
- Use both for **different purposes**

### With Documentation

- **Export as PNG** for documentation
- **Export as SVG** for scalable diagrams
- **Embed links** in documentation

### With Git

- **Export diagrams** to your repository
- **Use in README** files
- **Version control** the exported files

## Advanced Features

### Custom Libraries

- **Import icons** from external sources
- **Create custom shapes** for your domain
- **Share libraries** with your team

### Keyboard Shortcuts

- **Space + Drag**: Pan around canvas
- **Ctrl/Cmd + A**: Select all
- **Ctrl/Cmd + C/V**: Copy/paste
- **Delete**: Remove selected elements
- **Arrow keys**: Move selected elements

### Export Options

- **PNG**: For documentation and presentations
- **SVG**: For scalable graphics
- **PDF**: For printing
- **JSON**: For sharing editable files

## Best Practices

### Design Principles

- **Keep it simple**: Don't overcomplicate
- **Use consistent styling**: Same colors, fonts, shapes
- **Make it readable**: Clear labels and good contrast
- **Focus on the message**: What are you trying to communicate?

### Collaboration

- **Set expectations**: Agree on style and conventions
- **Use comments**: Explain complex parts
- **Regular saves**: Export periodically
- **Clear ownership**: Who makes final decisions?

### Documentation

- **Add legends**: Explain symbols and colors
- **Include context**: Brief description of what the diagram shows
- **Version control**: Track changes over time
- **Keep it updated**: Reflect current state

## Example Use Cases

### 1. API Architecture

- Show API endpoints
- Illustrate data flow
- Highlight security boundaries

### 2. Database Design

- Show table relationships
- Illustrate data flow
- Highlight constraints

### 3. User Flow

- Show user journey
- Highlight decision points
- Identify pain points

### 4. System Integration

- Show system connections
- Illustrate data exchange
- Highlight dependencies

### 5. Deployment Architecture

- Show infrastructure components
- Illustrate network topology
- Highlight security zones

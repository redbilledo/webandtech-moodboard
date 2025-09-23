## Moodboard Website (Draft)

This project is an experimental website that displays **moodboards based on emotions**.  
Each moodboard consists of a responsive 7x9 grid of squares and rectangles that display  
images or quotes. The grid is designed to scale dynamically with the viewport while  
preserving proportions.

# Features (Current Draft)
- **Landing page** with tutorial/introduction.
- **Control bar** at the bottom of the screen with navigation:
  - **Home** → returns to the landing page (`index.html`).
  - **Mood** → dropdown with `Romantic` (working), `Happy` (TBA), `Calm` (TBA).
  - **Theme** and **Search** → currently placeholders ("TBA").
- **Romantic moodboard** (`romantic.html`) with:
  - Predefined 7x9 grid layout.
  - Support for multiple shapes (small/big squares, horizontal/vertical rectangles).
  - Placeholder images assigned manually (to be randomized later).
  - Responsive scaling with preserved 9:7 ratio.
  - Hover effect: items zoom in smoothly and change shape.
- **Darkened background image** applied to moodboard pages separate from landing page.

# Planned Features
- Randomized image/quote assignment per grid item (with no duplicates).
- Pop-up modal to view images at full size with credits.
- Theming system to filter grid items by tag.
- Search functionality to look up images by keyword.
- Additional moods (Happy, Calm, etc.) with their own image pools.

## Tech Stack
- **HTML5**
- **CSS3**
- (JavaScript coming later for interactivity)

## Development Notes
This branch (`draft`) is focused on establishing layout, navigation, and styling.  
Interactivity and data handling (randomization, search, pop-ups) will be added in  
subsequent commits.


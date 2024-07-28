
## Session 11: Styling Your Websites with CSS! 🎨

### What is CSS?

Imagine you're building a house (your HTML). You've got the walls, the roof, and the rooms, but it's all plain and boring.  CSS is like the paint, wallpaper, furniture, and decorations you use to make your house look awesome and match your style. 

*   CSS stands for Cascading Style Sheets.
*   It's a separate language from HTML that lets you control how your website looks.

**Why use CSS?**

*   **Colors:** Make your text and backgrounds any color you want.
*   **Fonts:** Choose different fonts for a unique style.
*   **Layout:**  Decide where things go on your page (like moving furniture in a room).
*   **Effects:** Add cool things like shadows, rounded corners, or animations.

### How does CSS work with HTML?

CSS talks to your HTML elements and tells them how to look.  Here's how it works:

1.  **Selectors:** CSS finds the HTML element it wants to style (like a specific wall in your house).
2.  **Properties:** CSS tells the element what to change (like painting the wall blue).
3.  **Values:** CSS says exactly what the change should be (like choosing a light blue paint).

### Let's write some CSS!

Here's what a simple CSS rule looks like:

```css
selector {
  property: value;
}
```

Let's break this down:

1.  **selector:** This tells CSS which HTML element to style. We'll learn different types of selectors soon.
2.  **property:** This is what we want to change about the element (like color, font-size, etc.).
3.  **value:** This is the specific setting for the property (like blue, 16px, etc.).

**Example:**

```css
p {
  color: blue; 
  font-size: 18px; 
}
```

This CSS rule will make all paragraph (`<p>`) text on your page blue and 18 pixels in size.

### Selectors: Finding the right elements

Here are a few common ways to select HTML elements:

*   **Element Selector:**  Targets all elements of a certain type (e.g., `p` for all paragraphs).
*   **ID Selector:** Targets a single, unique element (e.g., `#myHeading` for an element with the ID "myHeading").
*   **Class Selector:** Targets multiple elements that share a common class (e.g., `.important` for all elements with the class "important").

### Try it yourself!

1.  Open your "About Me" page.
2.  Add a `<style>` tag in the `<head>` of your HTML file.
3.  Inside the `<style>` tag, write CSS rules to:
    *   Change the color and font of your page title (`<h1>`)
    *   Make your paragraphs a different color and size
    *   (Optional challenge) Create a class and add some special styling to it

**Important Note:** CSS is about having fun and experimenting! Try different properties and values to see what cool things you can create. 

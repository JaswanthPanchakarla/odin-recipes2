# odin-recipes2

This repository contains my very first web development project, Odin Recipes, completed as part of The Odin Project curriculum. This simple website is a structured collection of recipes designed to solidify my understanding of the fundamental building blocks of HTML5.

Key Learnings and Concepts Demonstrated
This project showcases several essential HTML concepts, focusing particularly on resource pathing and content organization.

1. Navigational Structure: Relative Anchor Links (<a>)
I utilized the anchor element (<a>) to establish a clear navigational structure between the main index.html page and the individual recipe pages housed in the recipes/ directory.

Crucially, I employed relative paths (e.g., recipes/chickenmakhai.html). This ensures the internal links remain valid and functional no matter where the project directory is hosted, demonstrating best practice for linking internal files.

2. Visual Embedding: Absolute Image Links (<img>)
The image element (<img>) is used to embed engaging visuals for each recipe.

I specifically used absolute URLs for the src attribute (e.g., https://example.com/images/dish.jpg), sourcing images from external online locations. This demonstrates an understanding of how to link to resources that reside outside of the project's file system.

Every image includes the essential alt attribute for improved accessibility and graceful handling of load failures.

3. Content Organization: Ordered (<ol>) and Unordered (<ul>) Lists
The structure of the recipe content relies on list elements:

Unordered Lists (<ul>): Used to present ingredients for quick, scannable reference.

Ordered Lists (<ol>): Used for the step-by-step cooking directions, ensuring a logical and sequential flow for the user.

4. Semantic Structure: Heading Hierarchy (<h1> - <h6>)
The appropriate use of heading tags creates a clear and logical hierarchy for the content:

<h1> is used for the main title (the highest importance).

<h2> is used for major sections (like "Ingredients" and "Directions").

This practice is vital for both Search Engine Optimization (SEO) and screen reader accessibility.

5. Text Formatting and Emphasis
Various text-level elements are used to enhance readability and draw attention to key points:

Paragraphs (<p>) structure descriptive text.

Strong importance (<strong>) is used to highlight critical ingredients or warnings within the instructions.

Emphasis (<em>) provides subtle stress on certain words or phrases.

# CSS_GRID
This example showcases the structure and styling of a webpage using CSS Grid to create a responsive employee card layout. The HTML includes a navigation bar and a section with multiple employee cards, each displaying details about an employee like job title, net worth, and an image. A "View Profile" button is included for interaction.

#

## Key Components:
### Header and Navbar:

The header is fixed at the top of the page and includes a navbar with links to different pages (Employee Cards, Product Layout, etc.).

The header uses CSS Grid to place the logo (or page title) on one side and the navbar links on the other side. This is achieved using grid-template-columns: 1fr auto, which divides the header into two areas: one that takes up the available space (1fr) and the other that fits the content (auto).

### Employee Cards (Grid Layout):

Each employee card contains:
Image: A placeholder image.
Job Title: (e.g., Software Engineer).
Net Worth: Displayed as ₱ 500,000.
Button: "View Profile" for interactivity.

The cards are placed inside a CSS Grid container. The grid uses grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)), which automatically adjusts the number of cards displayed in a row based on the screen size. Each card has a minimum width of 300px, and if space is available, more cards will fit on the same row.

### Responsive Design:

CSS Grid makes the layout responsive. On larger screens, several cards are displayed side by side. On smaller screens (like mobile), the cards stack vertically.

A media query (@media (max-width: 768px)) ensures that when the screen is narrower, the grid switches to a single-column layout (grid-template-columns: 1fr), ensuring each card takes up the full width of the container.

### Hover Effects and Interactivity:

Cards include hover effects. When hovered over, they display a subtle shadow (box-shadow: 0 12px 32px hsla(0, 0%, 20%, .1)), making them stand out and adding a layer of interactivity.

The button and the text color change when hovered, improving the user experience and guiding the user’s attention.

### Versatility:
This CSS Grid layout is easily reusable for other sections like Product Layout, Student Profile, Movie List, and MLBB Heroes. By following a similar pattern, you can create different layouts while maintaining a cohesive structure across different pages.

#

### Employee Cards
![image](https://github.com/user-attachments/assets/b0d4e83d-6ae9-4b8e-b56a-19c107cc403b)

#

### Product Layout
![image](https://github.com/user-attachments/assets/573f92c0-3f75-4e90-875e-872e2a1e2446)

#

### Student Profile
![image](https://github.com/user-attachments/assets/242ac2f8-c4b5-4ddb-9fdd-9eea5aab7497)

#

### Movie List
![image](https://github.com/user-attachments/assets/c889a66e-991d-46a2-a732-ee034afd4ef2)

#

### MLBB Hero
![image](https://github.com/user-attachments/assets/f4dfcbd0-ba2a-4902-b859-8349271e3b78)





# HTML & CSS Styling Demonstrations

This project contains two simple HTML files demonstrating different methods of applying CSS styles to web content.

## Files Included

### 1. css1.html

- Demonstrates the use of *internal CSS*.
- Creates a *traffic light UI* using <div> elements.
- Uses flexbox layout to arrange lights (Red, Yellow, Green) vertically.
- Each light is styled with different colors and text labels (MCA, BCA, BBA).

### 2. css(2).html

- Demonstrates *inline CSS* applied directly to HTML elements.
- Contains an explanation about inline styling written in three <p> tags.
- Each paragraph is uniquely styled using inline attributes like background-color, color, border, and padding.
- A base64-encoded *background image* is set using internal CSS for the body.

## Purpose

This project aims to:

- Show how to style elements using internal and inline CSS.
- Help understand the pros and cons of each CSS method.
- Provide a visual example of layout and design using basic HTML and CSS.

## How to Use

1. Open each HTML file in your browser:
   - css1.html: View a stylized traffic light.
   - css(2).html: View formatted text with explanations and background styling.

2. Use a code editor (like VS Code) to examine the HTML and CSS structure.

## Learning Outcomes

- Understand the differences between *internal* and *inline* CSS.
- Learn how to structure HTML with styled components.
- Observe how visual layout and color can be achieved through CSS.

---

Created for educational and demonstration purposes.



### 3. css(3).html
📄 Description
This project creates a static 8x8 chessboard using only HTML and CSS. Each square is represented by a <div> element, styled using Flexbox to create a grid layout. Two classes (.pink and .black) are used to alternate the square colors.

🎯 Purpose
Demonstrate how to use display: flex and flex-wrap: wrap to create a grid.

Show how to manually construct a checkerboard pattern using alternating colored <div>s.

Practice applying CSS styling for layout and visual design.

⚙️ Technologies Used
HTML5

CSS3 (Flexbox)

📐 Key Concepts
Flexbox Layout: The .chess container uses display: flex and flex-wrap: wrap to wrap 64 squares (8 rows × 8 columns).

Square Styling: Each square is 50×50px and styled using .pink or .black classes.

Alternating Pattern: Rows are manually alternated to mimic a real chessboard.

🛠️ How to Use
Open the HTML file in any modern browser.

You will see an 8×8 chessboard with alternating black and pink squares.

🔁 Note
To maintain the correct checkerboard pattern:

Even rows should start with .pink

Odd rows should start with .black

This must be manually adjusted in the HTML code if any changes are made.

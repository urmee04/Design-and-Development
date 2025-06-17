## SBA 3: Design and Development

In this assessment, we will take a Figma design from [Frontend Mentor](https://www.frontendmentor.io/challenges?difficulty=2%2C3&languages=CSS&type=free%2Cfree-plus) and implement it using Bootstrap. This project simulates a real-world task where we receive a design handoff and are expected to create a responsive, pixel-perfect webpage. we will apply our knowledge of Bootstrap’s grid system, components, and utility classes while utilizing version control through Git.


##### Objectives

- (Optional) Create or modify a high-fidelity Figma design.
- (Optional) Use the prototyping feature to demonstrate interactivity within a Figma design.
- Use Bootstrap to implement a high-fidelity Figma design accurately.

##### Technologies Used

- Semantic HTML5
- Bootstrap 5.3.0
- Fonts (Barlow Semi Condensed: weights 500, 600)

##### How to Use

1. Clone the repository or download the ZIP.
2. Be sure to maintain the folder structure.
3. Open `card.html` in your browser to view the card.

- git clone https://github.com/urmee04/Design-and-Development.git
- cd testimonials-grid-section-main
- cd card.html
- open card.html

#### Design Specifications
- Mobile width: 375px

- Desktop width: 1440px

- Font family: Barlow Semi Condensed

- Font weights: 500, 600

##### Colors:

###### Primary

- Purple 50: hsl(260, 100%, 95%)
- Purple 300: hsl(264, 82%, 80%)
- Purple 500: hsl(263, 55%, 52%)

###### Neutral

- White: hsl(0, 0%, 100%)
- Grey 100: hsl(214, 17%, 92%)
- Grey 200: hsl(0, 0%, 81%)
- Grey 400: hsl(224, 10%, 45%)
- Grey 500: hsl(217, 19%, 35%)
- Dark blue: hsl(219, 29%, 14%)
- Black: hsl(0, 0%, 7%)

##### Accessibility
- Images have descriptive alt attributes.

##### Reflections
**1. Challenges I encountered during the project.:**
- Ensuring cards of varying importance (Daniel/Patrick vs. Jonathan/Jeanette) aligned cleanly in a nested grid.

- Making Kira’s testimonial span the full height without causing overflow or wrapping issues.

**2. My approach to solving these challenges.:**
- I used a nested .row inside an 8‑column container to group Daniel/Patrick and Jonathan/Jeanette, tweaking their col‑md‑* widths for visual hierarchy.

- I wrapped Kira’s card in a d-flex container with h-100 so it stretched to match its sibling column’s height.

- I adjusted column spans and utility classes (col-md-7, col-md-5, col-lg-2) iteratively, previewing at different breakpoints until the layout matched the design.

**3. Improvements you would make if given more time.:**
- I will work more on the layout if given more time.

- Add ARIA labels, and keyboard focus states.
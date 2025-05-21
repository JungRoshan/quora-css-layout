# quora-css-layout
focused on recreating a **Quora-style layout using HTML and CSS, experimenting with selectors, layout structuring, and interactive styling.

## 🔧 What It Contains

- Structuring a social Q&A feed with:
  - Header, login/signup form
  - Navigation links
  - User posts with upvote/answer buttons
- Differentiating button styles using `id`, `class`, and `element` selectors
- Using `::first-letter`, `::first-line`, and `::selection` pseudo-elements
- Highlighting alternate posts with background color using `:nth-of-type`
- Applying specific styles with attribute selectors (`input[type="text"]`)
- Customizing styles for sibling buttons using `+` combinator

## 🎯 Output Preview

A Quora-like layout with:
- 🟥 **Header:** 'Quora' title + login & signup buttons
- 📑 **Navigation Links:** Styled in pink (Home, Following, Answer, Spaces)
- 👤 **User Posts:** Each showing a name, follow link, question, and action buttons
- 💬 **Buttons:**
  - Green `+upvote` button with `.upvote` class
  - Blue `answer` button
- 🟨 **Follow Labels:** Yellow background with black text
- 🟣 **Questions:** Bold purple links
- 🟠 **Alternate Post Background:** Light orange for even posts using `:nth-of-type`

## 🎨 CSS Highlights

- `* { font-family: 'Courier New'; }` — universal font style
- Styled headings and navigation with strong color contrast
- Custom selectors used:
  - `#login`, `#signup`
  - `.upvote + button` to target answer buttons
  - `div:nth-of-type(2n)` for alternating post background
- Pseudo-classes for hover, active, and checked states
- Pseudo-elements like:
  - `::first-letter` on headings
  - `::first-line` for intro paragraph
  - `::selection` to highlight selected text

---

🧠 **Takeaway:** This exercise helped deepen my understanding of selector combinations, layout structure, and dynamic text and button styling.



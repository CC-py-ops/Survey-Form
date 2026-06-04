# SkillSync Feedback Form

A responsive survey and feedback form built with HTML5 and CSS3. This project demonstrates modern form design principles, accessibility considerations, user input validation, and responsive styling while collecting valuable feedback from users about their learning experiences.

---

# Overview

SkillSync Feedback Form is a user-friendly survey application designed to gather insights from learners about their experience, skill level, interests, and recommendations.

The project focuses on creating a clean, accessible, and visually appealing form interface while practicing core front-end development concepts.

---

# Features

## User Information Collection

Collects:

* Full Name
* Email Address
* Years of Experience

## Skill Level Selection

Users can identify their current experience level:

* Beginner
* Intermediate
* Advanced

## Recommendation Survey

Uses radio buttons to gather feedback regarding:

* Likelihood of recommending the platform
* User satisfaction levels

## Interest Selection

Allows users to select multiple learning interests:

* Web Development
* Data Analysis
* Cybersecurity
* DevOps

## Open Feedback Section

Provides a text area for:

* Suggestions
* Comments
* User feedback
* Feature requests

## Responsive Design

* Mobile-friendly layout
* Flexible form structure
* Clean spacing and typography

---

# Technologies Used

* HTML5
* CSS3
* Responsive Web Design

---

# Project Structure

```text
SkillSync-Feedback-Form/
│
├── index.html
├── styles.css
└── README.md
```

---

# Form Components

## Text Inputs

Collect user information through:

```html
<input type="text">
<input type="email">
<input type="number">
```

Features:

* Placeholder text
* Required validation
* Input constraints

---

## Dropdown Menu

Allows users to select their experience level.

Example options:

* Beginner
* Intermediate
* Advanced

---

## Radio Buttons

Used for single-choice selections.

Example:

* Definitely
* Maybe
* Unlikely

---

## Checkboxes

Allows users to select multiple interests simultaneously.

Example:

* Web Development
* Data Analysis
* Cybersecurity
* DevOps

---

## Text Area

Provides space for detailed feedback and suggestions.

---

# Design Features

## Modern Gradient Background

The page uses a green gradient background:

```css
background: linear-gradient(
  to right,
  #1f4037,
  #99f2c8
);
```

This creates a modern and professional appearance.

---

## Card-Style Layout

The form is contained within a centered panel featuring:

* Rounded corners
* Drop shadows
* Consistent spacing
* Improved readability

---

## Interactive Elements

Includes:

* Focus states
* Hover effects
* Smooth transitions
* Improved user experience

---

# Validation Features

HTML5 validation is used for:

## Required Fields

```html
required
```

Applied to:

* Name
* Email

## Email Validation

```html
type="email"
```

Ensures users enter properly formatted email addresses.

## Numeric Constraints

```html
min="0"
max="50"
```

Limits years of experience to realistic values.

---

# Learning Objectives

This project demonstrates:

* Semantic HTML forms
* User input collection
* HTML5 validation
* CSS Flexbox layouts
* Responsive design principles
* Form accessibility
* UI/UX fundamentals
* Styling interactive form elements

---

# Accessibility Features

The project includes:

* Associated labels for inputs
* Semantic fieldsets
* Legends for grouped controls
* Keyboard-friendly navigation
* Clear form structure

These practices improve usability for assistive technologies and keyboard users.

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/skillsync-feedback-form.git
```

Navigate to the project directory:

```bash
cd skillsync-feedback-form
```

Open the project:

```text
index.html
```

Or run a local development server:

```bash
npx serve
```

---

# Future Enhancements

Potential improvements include:

* JavaScript form validation
* Form submission handling
* Success confirmation messages
* Dark mode toggle
* Data storage with localStorage
* Backend integration
* Survey analytics dashboard
* Progress indicators
* Multi-step forms
* Accessibility enhancements

---

# Screenshots

Suggested structure:

```text
screenshots/
├── desktop-view.png
├── mobile-view.png
└── completed-form.png
```

Example:

```markdown
![SkillSync Feedback Form](screenshots/desktop-view.png)
```

---

# Real-World Applications

This project reflects common web development tasks such as:

* Customer satisfaction surveys
* Product feedback forms
* User onboarding questionnaires
* Course evaluations
* Event registration forms

Understanding form development is essential because forms are one of the most frequently used components in modern web applications.

---

# Portfolio Value

This project demonstrates practical front-end skills including:

* Form creation
* Data collection interfaces
* Validation techniques
* Accessibility best practices
* Responsive design
* User experience design

These are foundational skills expected of front-end developers and web designers.

---

# License

This project is open source and available under the MIT License.

---

# Author

Created as part of a web development learning journey focused on mastering HTML forms, CSS styling, accessibility, and responsive user interface design.

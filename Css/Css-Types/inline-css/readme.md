Inline CSS Basics 🎨

This project is a basic practice project where I learned how to use Inline CSS with HTML.

The main goal was to understand how CSS can be written directly inside an HTML element using the style attribute.

⸻

📚 What I Learned

1. What is Inline CSS?

Inline CSS means writing CSS directly inside an HTML element using the style attribute.

Syntax

<element style="property: value;">
    Content
</element>

Example

<h2 style="background-color: blue;">Exercise</h2>

Here:

* style → HTML attribute used to add CSS
* background-color → CSS property
* blue → CSS value

⸻

🎨 Changing Background Color

We can use the background-color property to change the background color of an element.

<h2 style="background-color: blue;">Exercise</h2>

This gives the Exercise heading a blue background.

⸻

📝 Changing Text Color

The color property is used to change the color of text.

<li style="color: brown;">Soya</li>

Here, the text Soya will appear brown.

⸻

🧠 Semantic HTML

While building this page, I also practiced using semantic HTML.

Instead of using generic elements everywhere, I used elements according to their meaning.

Structure

<body>
│
├── <header>
│   └── <h1> Gym Website
│
└── <main>
    │
    ├── <section>
    │   ├── <h2> Exercise
    │   └── <ul>
    │       └── <li> Exercises
    │
    └── <section>
        ├── <h2> Diet
        ├── <h3> Vegetarian
        │   └── <ol>
        │       └── <li> Foods
        │
        └── <h3> Non-Vegetarian
            └── <ol>
                └── <li> Foods

Important Semantic Elements

Element	Purpose
<header>	Represents the introductory/header part of a page
<main>	Contains the primary content of the page
<section>	Groups related content into a meaningful section
<h1>	Main heading of the page
<h2>	Main section heading
<h3>	Subheading inside a section
<ul>	Unordered list
<ol>	Ordered list
<li>	Individual list item

⸻

💡 First-Principles Understanding

The important thing I learned is:

HTML gives meaning and structure, while CSS controls presentation.

For example:

<h2 style="background-color: blue;">Exercise</h2>

HTML:

<h2> → This is a heading

CSS:

background-color: blue → Make its background blue

So:

HTML = What it is
CSS = How it looks

⸻

⚠️ Important Point About Inline CSS

Inline CSS is useful for learning and for very small, specific changes.

However, for larger projects, writing CSS directly on every element can become difficult to maintain.

Example:

<h1 style="color: red;">Heading</h1>
<h2 style="color: red;">Exercise</h2>
<p style="color: red;">Text</p>

If many elements need the same styling, repeating inline CSS becomes inconvenient.

That’s why we later learn:

1. Inline CSS
2. Internal CSS
3. External CSS

For real-world projects, External CSS is generally preferred for maintainability and separation of concerns.

⸻

🛠️ Mini Project

I created a simple Gym Website containing:

* Gym website heading
* Exercise section
* List of exercises
* Diet section
* Vegetarian food list
* Non-vegetarian food list
* Inline CSS for background color
* Inline CSS for text color
* Semantic HTML structure

⸻

🚀 Key Takeaways

* Learned the basic syntax of Inline CSS.
* Learned how to use the style attribute.
* Practiced background-color.
* Practiced color.
* Understood CSS property and value.
* Practiced semantic HTML.
* Improved heading hierarchy using h1, h2, and h3.
* Learned that semantic HTML should describe the meaning of content, not just its appearance.

⸻

📌 Next Step

Next, I will continue learning more CSS concepts and gradually move from basic inline styling toward Internal CSS and External CSS.
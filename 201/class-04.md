# Read: Class 04

In our current module, focusing on improved code quality is vital for robust software development, while knowledge sharing and learning enhance our skills and readiness for the ever-evolving field of software development. These concepts directly impact the quality of our work and our success as developers.

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

1. To create a basic link, we wrap text or other content inside what element?

 To create a basic link in HTML, you wrap text or other content inside an `<a>`(anchor) element. The `<a>` element is used to define hyperlinks and can be used to link to other web pages, resources, or locations within the same page.

2. The `href` attribute contains what information?

The `href` attribute in an HTML `<a>` (anchor) element contains the information necessary to specify the destination of the hyperlink. It typically contains a URL (Uniform Resource Locator), which is a web address that can point to various resources, such as other web pages, images, documents, or specific locations on the web.

3. What are some ways we can ensure links on our pages are accessible to all readers?

Ensuring that links on your web pages are accessible to all readers is an important aspect of web design and development. Accessibility makes your content usable by a broader audience, including people with disabilities.

[CSS Layout: Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow), [CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

1. What is meant by “normal flow”?

In web design and CSS (Cascading Style Sheets), "normal flow" refers to the default layout behavior of HTML elements on a web page. When you create a web page without applying specific positioning or layout properties, elements are displayed in their natural or normal flow.

2. What are a few differences between `block-level` and `inline` elements?

Block-level and inline elements are two distinct types of HTML elements, and they behave differently in terms of layout and display.
Block-Level Elements:

* Start on a new line.
* Take up full width.
* Examples: `<div>,` `<p>`, headings.

Inline Elements:

* Flow within text.
* Take minimal width.
* Do not force line breaks.
Examples: `<span>`, `<a>`, `<strong>`.

3. `Static` positioning is the default for every HTML element.

4. Name a few advantages to using absolute positioning on an element.

* Precise Placement: Allows exact element positioning.
* Layering Control: Easily layer elements on top of each other.
* No Impact on Layout: Doesn't affect surrounding elements.
* Z-Index Control: Fine control over element stacking.
* Complex Layouts: Useful for custom designs and layouts.
* Custom Animation: Easy to animate elements.
* Responsive Design: Can be used for responsive layouts.

5. What is a key difference between fixed positioning and absolute positioning?

The main distinction is that fixed positioning is relative to the viewport and remains fixed in place while scrolling, while absolute positioning is relative to a positioned ancestor and scrolls with that ancestor or the viewport if no positioned ancestor is found.

## Things I want to know more about

[Functions – Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

1. Describe the difference between a function declaration and a function invocation.

A function declaration is a way to define a reusable block of code in a program. It essentially creates a function that can be called later.
It starts with the `function` keyword followed by the function name and a set of parameters enclosed in parentheses. The function's code block is enclosed in curly braces `{}`. `Function invocation` is the act of executing or running a function that has been declared. It is how you make use of the function's code.
To invoke a function, you use the function's name followed by parentheses, and you can pass arguments (values) into the function if it expects any parameters.

2. What is the difference between a parameter and an argument?

Parameters are defined in the function's signature and serve as placeholders for expected inputs, while arguments are the actual values or expressions you provide when calling the function, which get assigned to the corresponding parameters. Parameters are used in the function definition, and arguments are used in the function invocation to customize the function's behavior with specific data.

[6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

In my coding journey, I've found that these two benefits of pair programming have been invaluable. They've helped me improve my coding skills, understand complex concepts, and produce higher-quality code. Additionally, the collaboration aspect fosters a sense of community and shared growth, making the coding journey more enjoyable and less isolating.

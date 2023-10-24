# Read: Class 02

Understanding of logical operators, their behavior, and their application in decision-making is integral to the successful completion of the module I am studying. This knowledge forms the basis for creating sophisticated programs, implementing effective data processing, and enhancing the overall reliability and efficiency of software solutions.

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/)

1. Why is it important to use semantic elements in our HTML?

Using semantic elements in HTML improves accessibility, SEO, maintainability, and user experience while promoting code consistency and readability. It's a best practice that should be followed to create more robust and accessible web content.

2. How many levels of headings are there in HTML?

HTML offers six level of headings, ranging from <h1> the highest level </h1> to <h6> the lowest level.</h6>

3. What are some uses for the 'sup' and 'sub' elements?

The 'sup' and 'sub' elements in HTML are used to define superscript and subscript text, respectively. They are commonly used in various contexts to format text in a way that raises or lowers it relative to the surrounding text.

4. When using the 'abbr' element, what attribute must be added to provide the full expansion of the term?

When using the 'abbr' element in HTML to indicate an abbreviation, it's essential to include the 'title' attribute. The title attribute should provide the full expansion or explanation of the abbreviation. This helps both human users and assistive technologies, such as screen readers, understand the meaning of the abbreviation.

[How CSS Is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

1. What are ways we can apply CSS to our HTML?

* Inline Styles: The 'style' attribute within HTML tags to define CSS rules directly within the HTML element. Inline styles apply only to that specific element.

* Internal Styles: Embed CSS within the HTML document's 'style' element, usually placed in the 'head' section of the HTML document. Internal styles apply to the entire page.

* External Styles: Create a separate CSS file (style.css) and link it to your HTML document using the 'link' element in the 'head' section. External styles can be reused across multiple HTML pages.

2. Why should we avoid using inline styles?

While inline styles offer a quick way to apply styles directly to individual elements, they should be used sparingly and for specific cases where no other method is practical. For most web development projects, separating your HTML content from your CSS by using external or internal stylesheets is a best practice that promotes maintainability, reusability, and clean code organization.

3. Review the block of code below and answer the following questions:

 h2 {
     color: black;
     padding: 5px;
   }

 1. What is representing the selector?

    The selector is 'h2'. It is the part of the CSS rule that defines which HTML elements the following declarations should be applied to. In this case, it targets all 'h2' elements.

 2. Which components are the CSS declarations?

  The CSS declarations are the lines within the curly braces. In this example, there are two declarations:

* color: black; This declaration sets the text color of the selected 'h2' elements black.
* padding: 5px; This declaration adds 5 pixels of padding around the content of the selected 'h2' elements.

3. Which components are considered properties?

    The properties are the attributes defined within the declarations. In this code:'color' and 'padding' are the properties. They specify what aspect of the selected elements is being styled (text color and padding, respectively).
    black and 5px are the values assigned to these properties. The values determine the specific style or measurement associated with each property.

[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

1. What data type is a sequence of text enclosed in single quote marks?

A sequence of text enclosed in single quote marks, like this: 'example text', is typically considered a string in most programming languages. Strings are used to represent and manipulate text data.

2. List 4 types of JavaScript operators.

* Arithmetic Operators: These operators perform mathematical calculations.
* Comparison Operators: These operators are used to compare values and return a Boolean result (true or false).
* Logical operators: Logical operators are used to combine or manipulate Boolean values.
* Assignment Operators: These operators assign values to variables.

3. Describe a real world Problem you could solve with a Function.

A real-world problem that can be solved with a function is calculating the total cost of a shopping cart, taking into account various items with different prices, quantities, and potentially applying discount or taxes.

[Making Decisions In Your Code – Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

## Things I want to know more about

1. An if statement checks a *condition**and if it evaluates to *true**, then the code block will execute.

2. What is the use of an else if?

The 'if' statement is used to test a condition. If the condition is true, the code block associated with the 'if' statement is executed.
If the condition in the 'if' statement is false, the program can then evaluate an 'else if' statement. It checks a new condition, and if that condition is true, the code block associated with the 'else if' statement is executed.

3. List 3 different types of comparison operators.

* Equality Operator (==): The equality operator compares two values for equality. It returns 'true' if the values are equal and 'false' if they are not.

* Strict Equality Operator (===): The strict equality operator compares two values for both equality and data type. It returns 'true' only if both the values and data types are the same; otherwise, it returns 'false'.

* Greater Than Operator (>): The greater than operator compares two values and returns 'true' if the left value is greater than the right value; otherwise, it returns 'false'.

4. What is the difference between the logical operator && and ||?

&& requires all conditions to be 'true' for the result to be 'true', while || only requires at least one condition to be 'true'. These operators are commonly used in conditional statements and control structures to make decisions based on multiple conditions.

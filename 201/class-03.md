# Read: Class 03

 The topics I'm studying are not just theoretical but practical, and they will play a significant role in my academic success and future career prospects. They form the building blocks upon which I'll construct my knowledge and skills throughout my module and beyond.

[Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) and [Unordered List](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) list.

1. When should you use an `unordered list` in your HTML document?

You should use an unordered list in your HTML document when you want to present a list of items in a way that doesn't have a specific order or sequence. Unordered lists are typically used when the order of the items is not significant, and you want to display the list with bullet points or some other type of marker to indicate individual items.

2. How do you change the `bullet style` of unordered list items?

To change the bullet style of unordered list items in HTML, you can use CSS
You can modify the bullet style by targeting the `ul` (unordered list) and `li` (list item) elements with specific CSS properties.

3.When should you use an`ordered list` vs an `unorder list` in your HTML document?

If the order of items matters or needs to be conveyed, use an ordered list `<ol>`. If the items are related but the order is unimportant, use an unordered list `<ul>`. The choice between these two types of lists should be based on the content and context of your HTML document to ensure clarity and effective communication of information.

4.Describe two ways you can change the numbers on `list items` provided by an `ordered list`?

You can change the numbers on list items provided by an ordered list `<ol>` in two main ways using HTML and CSS.

* Changing the Starting Number with HTML: You can specify the starting number for an ordered list by using the start attribute. This attribute allows you to define the initial number for the list, which can be useful in situations where you want to continue a list from a specific point.
* Changing the Starting Number with HTML: You can specify the starting number for an ordered list by using the start attribute. This attribute allows you to define the initial number for the list, which can be useful in situations where you want to continue a list from a specific point.

[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

In the land of Webville, Margin and Padding were two essential characters in the story of "The Box Model." Margin was the friendly character who lived outside, providing space and preventing overcrowding. Padding, the more reserved of the two, protected the content inside elements. Together, they maintained harmony in Webville by ensuring elements had personal space while guarding the content from intruders. Margin and Padding's cooperation created a pleasant and balanced web world for all residents.

2. List and describe the four parts of an HTML elements box as referred to by the `box model`.

The HTML element box is described by the Box Model, which consists of four essential parts:

* Content: This is the innermost part of the box and contains the actual content of the HTML element, such as text, images, or other elements.
* Padding: Surrounding the content, the padding is the space between the content and the element's border.
* Border: The border is the line that surrounds the padding and separates the element's content from the margin.
* Margin: The margin is the outermost part of the box, creating space between the element and adjacent elements.

[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays) , [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators), [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals) ,[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code).

What `data types` can you store inside of an `Array`?

* Numbers: You can store both integers and floating-point numbers in an array.
* Strings: Arrays can hold text data, which can be single characters, words, or even entire sentences.
* Booleans: Boolean values, which represent true or false, can be elements of an array.
* Objects: JavaScript objects, including custom objects, can be stored in an array.
* Arrays: You can create nested arrays, meaning arrays within arrays, to create multi-dimensional data structures.
* Functions: You can store functions as elements of an array, making it possible to call functions later in your code.
* Null: Null values can also be elements within an array.

2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

The `people` array is indeed a valid JavaScript array. You can access the values stored in this nested array using square brackets to specify the indices of the outer and inner arrays.

## Things I want to know more about

3. List *five* shorthand operators for assignment in javascript and describe what they do.

In JavaScript, there are several shorthand operators for assignment that make it more concise to perform common operations. Here are five of these shorthand assignment operators and what they do:

* (Addition Assignment) `+=`
* (Subtraction Assignment) `-=`
* (Multiplication Assignment) `*=`
* (Division Assignment) `/=`
* (Modulus Assignment) `%=`

 4. Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

 In the provided code, the expression `(a + c) + b;` is being evaluated. `a` is a number with a value of 10. `c` is a boolean with a value of false. In JavaScript, false is equivalent to 0 when used in numerical contexts. `b` is a string with a value of 'dog'.
`(a + c)` evaluates to `(10 + false)`. Since false is treated as 0 in numerical contexts, this is effectively 10 + 0, which is 10. So, the expression becomes 10 + b, where b is a string.  The result will be a string concatenation, not a numerical addition. Therefore, the final result will be the string `10dogs`.

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

A real-world example of when a conditional statement should be used in a JavaScript program is in an online shopping application to determine whether a user is eligible for a discount based on their purchase total.

6. Give an example of when a Loop is useful in JavaScript.

A common scenario where a loop is useful in JavaScript is when you need to iterate through an array of data or a collection of items, performing the same set of operations on each item. Here's an example:
Let's say you have an array of numbers, and you want to calculate the sum of all these numbers. Instead of manually adding each number, you can use a loop to iterate through the array and accumulate the sum.

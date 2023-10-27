# Read: Class 05

Understanding font properties and spacing in CSS is essential for creating user-friendly, brand-consistent, and visually appealing web designs, crucial for responsive layouts, accessibility, and effective web development.

[Using Images In HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML). Read [Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types) and [Choosing Image Formats.](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format).

1. What is a real world use case for the `alt` attribute being used in a website?

The `alt` attribute in HTML is primarily used to provide alternative text for an image on a website. This text is displayed when the image cannot be rendered by the web browser or when a visitor is using a screen reader.

2. How can you improve accessibility of images in an HTML document?

* Use the `alt` Attribute: Always add a brief and meaningful description using the alt attribute for each image.
* Optimize File Size: Keep image file sizes small to improve page loading times.
* Avoid Images for Text: Prefer text over images for conveying textual content.
* Use Semantic HTML: Employ `<figure>` and `<figcaption>` for structured image content.
* Test with Tools: Use accessibility tools to identify and fix issues.
* Provide High Contrast: Ensure good contrast for better visibility.
* Include Multimedia Accessibility: Add captions and transcripts for videos and audio content.

3. Provide an example of when the `figure` element would be useful in an HTML document.

The `<figure>` element in HTML is useful when you want to associate a self-contained content block, typically an image, with a caption or description. Using the `<figure>` element in this way helps create a semantic relationship between the image and its caption, making it clear that the caption is describing the image. It also assists in better structuring your document for accessibility and search engines.

4. Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.

`GIFs` are like simple moving pictures, while `SVGs` are resizable and stay clear no matter how big you make them. In simple terms, `GIFs` are good for small animations and fun stuff, while `SVGs` are like smart pictures that you can resize without losing quality.

5. What image type would you use to display a screenshot on your website and why?

For displaying a screenshot on a website, it's best to use a standard image format like `PNG` or `JPEG`.

[Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color), [Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

* Foreground color is like the color of the text you write with a pen on a piece of paper. It's the color of the content that you see on a web page, like the words in a book.

* Background color, on the other hand, is like the color of the paper itself. It's what's behind the words and images, like the color of the wall in a room. It serves as a backdrop to make the foreground content stand out.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

1.Choose a color palette.
2.Highlight the header and navigation.
3.Use a light background.
4.Ensure text is easy to read.
5.Use an accent color for buttons.
6.Include colorful images and icons.
7.Categorize with different colors.
8.Make calls to action stand out.
9.Maintain a consistent color scheme.
10.Use white space for balance and readability.

3. What should you consider when choosing fonts for an HTML document?
1.Prioritize readability.
2.Maintain brand consistency.
3.Ensure device compatibility.
4.Adjust font size and contrast.
5.Consider serif vs. sans-serif.
6.Use accessible fonts.
7.Pair fonts effectively.
8.Optimize for loading speed.
9.Test for mobile responsiveness.
10.Keep font hierarchy consistent.

4. What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?

font-size: This property determines the size of the text. You can specify the size in various units such as pixels `(px)`, ems `(em)`, or percentages `(%)`. It makes the text larger or smaller. For example, font-size: 16px; sets the text to be 16 pixels in size.

font-weight: This property controls the thickness or boldness of the text. It accepts values like `"normal,"` `"bold,"` or numeric values like `100, 200, 300`.

Font-style: This property defines the style of the text, allowing you to make text `italic` or `normal`. You can set it to "normal" or "italic." For example, font-style: italic; makes the text italicized.

* Padding:
You can add spacing within the `<h1>` element using the padding property. This property adds space around the content inside the element.

* Margin:
You can add spacing around the `<h1>` element using the margin property. This property creates space around the outside of the element, pushing other content away.

## Things I want to know more about
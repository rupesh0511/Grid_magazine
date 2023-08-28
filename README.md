# Grid_magazine

Hosted link- https://rupesh0511.github.io/Grid_magazine/

HTML

![Screenshot 2023-08-28 153129](https://github.com/rupesh0511/Grid_magazine/assets/69234169/d474b244-5bf6-4c30-b983-7c9144ab72af)
![Screenshot 2023-08-28 153141](https://github.com/rupesh0511/Grid_magazine/assets/69234169/9557b730-1d02-43e9-b5f4-ba0ef784382e)
![Screenshot 2023-08-28 153153](https://github.com/rupesh0511/Grid_magazine/assets/69234169/f98950b3-29f2-4358-af07-1aa6afcef787)
![Screenshot 2023-08-28 153203](https://github.com/rupesh0511/Grid_magazine/assets/69234169/3d25bc33-ddb0-49ab-9b2b-d448d16e1d6b)
![Screenshot 2023-08-28 153214](https://github.com/rupesh0511/Grid_magazine/assets/69234169/d293bd64-bafe-4709-8417-741eddbf6b1e)

'!DOCTYPE html': This declaration defines the document type and version of HTML being used, which is HTML5 in this case.

'html lang="en"': The opening of the HTML document. It sets the language of the document to English.

'head': The opening of the document's head section. This section contains metadata about the document.

'meta charset="UTF-8"': This meta tag specifies the character encoding used in the document, which is UTF-8, capable of handling various characters and symbols.

'meta name="viewport" content="width=device-width, initial-scale=1.0"': Another meta tag that configures the viewport for responsive web design. It ensures the web page adapts to different device widths and starts at a 1:1 scale.

'title' 'Magazine' '/title': The title tag defines the title of the web page, which will be displayed in the browser's title bar or tab.

'link href="https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap" rel="stylesheet"': This link tag is used to import external fonts from Google Fonts, which will be applied to the page's text.

'link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"': Another link tag, this one imports Font Awesome icons, which can be used to enhance the visual appearance of the page.

'link rel="stylesheet" href="styles.css"': This link tag includes an external stylesheet called "styles.css," which likely contains additional CSS styles for the webpage.


'body': The opening of the document's body section. This is where the main content of the web page resides.


'main': This tag defines the main content of the webpage, typically containing the central content of the page.


'section class="heading"': A section element with a "heading" class. Sections are used to group related content.


'header class="hero"': A header element with a "hero" class. Headers often contain introductory content.


'img src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png" alt="freecodecamp logo" loading="lazy" class="hero-img"': An image element displaying the FreeCodeCamp logo. The "alt" attribute provides alternative text for accessibility, and the "class" attribute sets the class of the image for styling purposes.


'h1 class="hero-title"' 'OUR NEW CURRICULUM' '/h1': A level-one heading element with a "hero-title" class, displaying the text "OUR NEW CURRICULUM."


'p class="hero-subtitle"' 'Our efforts to restructure our curriculum with a more project-based focus' '/p': A paragraph element with a "hero-subtitle" class, providing a subtitle or additional information about the curriculum.


'div class="author"': A div element with an "author" class, used for grouping elements related to the authorship of the content.


'p class="author-name"' 'By' 'a href="https://freecodecamp.org" target="_blank" rel="noreferrer"' 'freeCodeCamp' '/a' '/p': A paragraph element with an "author-name" class, followed by a link to FreeCodeCamp's website. The "target" attribute specifies that the link should open in a new tab or window.


'p class="publish-date"' 'March 7, 2019' '/p': A paragraph element with a "publish-date" class, displaying the publication date of the content.


'div class="social-icons"': A div element with a "social-icons" class, likely used to display social media icons or links.


CSS


![Screenshot 2023-08-28 153223](https://github.com/rupesh0511/Grid_magazine/assets/69234169/d3191edf-eb0e-4b3c-b68d-dead3483f2dc)
![Screenshot 2023-08-28 153231](https://github.com/rupesh0511/Grid_magazine/assets/69234169/e4b918c5-30f9-4594-a5ee-dff5cb13277f)
![Screenshot 2023-08-28 153238](https://github.com/rupesh0511/Grid_magazine/assets/69234169/bd069699-f58b-42cc-af8e-6220c8fdc05d)
![Screenshot 2023-08-28 153245](https://github.com/rupesh0511/Grid_magazine/assets/69234169/79610ed7-fd8d-45c3-9be8-19544cf0e62f)
![Screenshot 2023-08-28 153256](https://github.com/rupesh0511/Grid_magazine/assets/69234169/a6efa6ec-e42d-4781-94af-232f16523ce9)
![Screenshot 2023-08-28 153303](https://github.com/rupesh0511/Grid_magazine/assets/69234169/59efc4ec-a85e-41ca-bc64-87cb671d7e56)

'*', '::before', '::after': These are universal selectors that target all elements, pseudo-elements before, and pseudo-elements after. They are used to reset default margin, padding, and box-sizing properties to ensure consistent styling throughout the document.


'html': Selects the HTML element and is used to set the base font size for the entire document to 62.5% of the default font size. This is a common technique for making it easier to work with font sizes, as 1rem (1 root em) will be equivalent to 10px.


'body': Targets the <body> element and sets the font family to 'Baskervville', which is a serif font. It also sets the text color to 'linen' and the background color to an RGB value.


'h1': Targets all level-one headings and changes their font family to 'Anton', a sans-serif font. It also changes the color to 'orangered'.


'h2, h3, h4, h5, h6': Targets all heading elements from level 2 to level 6 and changes their font family to 'Raleway', another sans-serif font.


'a': Targets all anchor elements and removes text decoration (underlines) and sets the color to 'linen', making links visually consistent with the text.


'main': Targets the <main> element and applies CSS grid properties to create a three-column layout with a minimum column width of 2rem and a maximum content column of 94rem. It also adds a vertical gap between rows.


'img': Targets all image elements and ensures they span the full width of their containers while maintaining their aspect ratio using the 'object-fit' property.


'hr': Targets horizontal rule elements and sets a margin above and below them, as well as a light gray border to create a dividing line.


'heading': Targets an element with the class "heading" and applies a grid layout with two columns and vertical gaps.


'text': Targets an element with the class "text" and sets the font size, letter spacing, column width, and text alignment. It also justifies the text to create a clean, even appearance.


'hero': Targets an element with the class "hero" and positions it relative to its parent container, likely for special styling or layout purposes.


'hero-title', 'hero-subtitle': Targets elements with these specific classes and applies styles like text alignment and color to them.


'author': Targets the author information and sets the font size and font family for consistency.


'author-name a:hover': Targets anchor elements within the author information when hovered over and changes their background color.


'publish-date': Targets the publish date information and sets its color with transparency.


'social-icons': Targets the social media icons section and creates a grid layout for displaying the icons in a row with equal column widths. It also adjusts the font size for these icons.


'first-paragraph::first-letter': Targets the first letter of the first paragraph and applies special styling to it, including a larger font size and a distinct color, creating a drop cap effect.


'quote': Targets elements with the class "quote" and styles them with a specific font size, color, and text alignment. It also adds quotes before and after the text.


'text-with-images': Targets an element with the class "text-with-images" and sets up a grid layout with two columns and a gap between them.


'lists': Targets unordered lists and removes the default list style and adds top margin for spacing.


'lists li': Targets list items within unordered lists and adds a margin at the bottom for spacing.


'list-title, .list-subtitle': Targets elements with these specific classes within lists and changes their color.


'image-wrapper': Targets an element with the class "image-wrapper" and sets up a grid layout for positioning images and quotes.


'image-1, .image-3': Targets specific images within the "image-wrapper" and adjusts their grid placement.


Media queries: These are used to apply specific styles based on the screen width, making the design responsive to different device sizes. They adjust font sizes, column layouts, and other properties for various screen widths.

Screenshot of UI

![Screenshot 2023-08-28 154110](https://github.com/rupesh0511/Grid_magazine/assets/69234169/69e64554-0c1c-4684-be6f-4eaa6d045642)
![Screenshot 2023-08-28 154128](https://github.com/rupesh0511/Grid_magazine/assets/69234169/e6aa4238-97cb-4368-bcdb-28be31c8cc27)
![Screenshot 2023-08-28 154138](https://github.com/rupesh0511/Grid_magazine/assets/69234169/4fba6d4b-72c4-4a36-b704-0ef151bfc0b0)
![Screenshot 2023-08-28 154146](https://github.com/rupesh0511/Grid_magazine/assets/69234169/831b4b94-0437-493f-89e0-4563e6031260)


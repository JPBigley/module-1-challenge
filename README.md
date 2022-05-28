# Module 1 Challenge

## HTML CSS Git Challenge: Code Refactor

This week's challenge was to refactor existing HTML and CSS code to meet accessibility standards.

The original code can be found [here](https://github.com/coding-boot-camp/urban-octo-telegram).

We were assigned the following User Story:

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

Below is the Acceptance Criteria:

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

Image of the Website:
![Horiseon Website Image](https://courses.bootcampspot.com/courses/1817/files/1704766/preview)

The changes I made to the HTML code are as follows:

- Added a more descriptive title to the <title> tag
- Changed non-semantic elements to semantic elements (header, footer, nav, main, aside, and section)
- Removed unnecessary classes from the three <section> elements within the <main> tags
- Added alt text attributes to all images
- Adjusted some class names to make code more readable
- Added comments to make code more readable

The changes I made to the CSS code are as follows:

- Adjusted selectors to match up with new semantic elements
- Added variables for colors
- Restructured code to have it follow the structure of the HTML document
- Consolidated code by removing 50 lines of repetitive code
- Added comments to make the code more readable

# css-pseudo-elements
using the `::after` pseudo-element along with the `:hover` and `:focus` selectors to create a tooltip


# 📖 Implementing a CSS Tooltip


- As a user, I want to hover over keywords and read short info on them instead of having all of the text on the page.


# Criteria

- Special keywords are underlined and change the cursor to a hand icon when the user hovers over them.

- The user hovers over a keyword and a rectangular tooltip appears next to the keyword.

  - For example, if the keyword is "Cascading Style Sheets," the tooltip would say, "Commonly known as CSS."

 - The tooltip has the same background color and text color as the header and navbar items.


## 📝 Notes

Refer to the following documentation:

[MDN Web Docs on ::after](https://developer.mozilla.org/en-US/docs/Web/CSS/::after)


## 💡 Hints

- Use the `::after` pseudo-element along with the `:hover` and `:focus` selectors to create the tooltip.

- Designate the keyword to use a `data-descr` custom data attribute for the tooltip text.


# **Anatomy**
**CSS Basics:** How to Style Your Webpage
***CSS (Cascading Style Sheets)*** is used to change the appearance of a webpage. There are two main ways to add CSS:

**1.Rulesets (Stylesheets)** – These are written in a 
separate CSS file or inside a  tag in your HTML. They allow you to style multiple elements at once.

**2.Inline Styles** – These are written directly inside an HTML element and apply only to that specific element.



## 1. Rulesets: Styling Multiple Elements
![ccs rule terminology](https://css-tricks.com/wp-content/uploads/2017/05/css-ruleset-terminology.png)
A ruleset consists of a selector (which tells CSS which element to style) and a declaration (which defines how it should look). This method is best when you want to style multiple elements in a structured way.

For example, if you want all paragraphs to have blue text, you can write a ruleset that applies to every p element on your page.
selector {
  property: value; 
}

***Example:***
```css
p {color:blue
};
```

## 2. Inline Styles: Quick and Direct Styling
![ccs rule terminology](https://images.squarespace-cdn.com/content/v1/62d7afdd0711b76729174013/6e669160-2892-4ece-b0c3-8d776d0ff50d/inline.png)
Inline styles are written inside an element’s style attribute. They’re useful when you need to apply a unique style to a single element quickly. However, they are not the best choice for large projects since they make code harder to maintain.
***Example:***
``` html
<p style="color: blue;">Hello World!</p>
```

# Understanding CSS Components
Selectors target the elements you want to style (e.g., paragraphs, headings, buttons).

+ **Declarations** define the style you want to apply (e.g., text color, background, spacing).

+ **Properties** tell CSS what to change (e.g., font size, border, alignment).

+ **Values** define how the property should look (e.g., red, bold, centered).

# When to Use Each Method
Use ***rulesets*** when you need to style multiple elements consistently.

Use ***inline*** styles for quick, one-time changes.

*By using CSS effectively, you can make your webpage more visually appealing and organized!*

To learn more about CSS and HTML and how they are used, check out the resources on [**CodeAcademy**](https://www.codecademy.com/resources/docs/css/anatomy)


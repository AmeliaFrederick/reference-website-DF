# reference-website
1. Naming Convention for all filenames, paths and folders.
    - The naming conventions for all filenames, paths and folders are to use dashes, underscores or the occasional period, to separate words. They must also all be in lowercase characters. 

2. Best practices for commit messages.
    - The best practices for commit messages is to keep it short, but still detailed enough. Keep the subject line clear and easy to understand, and in the description make sure you write what, and why you have done something.

3. What is HTML?
    - HTML is an acronym that stands for HyperText Markup Language. It is one of the most common markup languages for web page creation. With it you can place text onto a web page and create your own website. 

4. Proper syntax for HTML tags.
    - Proper syntax for HTML tags is to have a open and close tag. They look like this < > (open) and this </> (closed). Without these the code can flow through to other pieces of code and your website won't work. 

5. Explain or demonstrate commonly used HTML tags/elements:
    - Headings; h1-h6: These are used to put emphasis on certain titles, or introduce a new subject to the page. The sizes range through 1 (biggest) to 6 (smallest). Ranked from most important, to least important. 
    - p: The p tag is used to place a paragraph of text into your html. The text will have its own section, and can later be modified seperately through CSS.
    - Lists; ul, ol, dl: There are different kinds of lists. ul; unordered list, is used for placing the list of words one after the other with bullets (which is the default decoration), ol; ordered list, is used to list off words in numerical order (1-to however many you need). dl; description list, is used to associate one or more terms, with a description or a value.
    - a: The a tag is used to define a hyperlink. This tag is often used to bring the reader to another section of the webpage. It can be placed anywhere, visible or hidden, within the website.
    - img: This tag is used to place an image inside of your HTML and have it appear on your webpage. 
    - q: The q tag is used to define a short quotation. It will insert quotation marks around the quotation. 
    - blockquote: The blockquote tag is similar to the q tag, however it's used for longer quotations. 
    - cite: The cite tag is most commonly used to define the title of a creative work, which can range from a book, a song, a painting, etc. Though it is used for many other purposes as well. It will display the text in italic.
    - em: The em tag is used to put emphasis on text and the content will be displayed in italic.
    - strong: The strong tag is used to define text with a strong importance in the html. It will display the content in bold.
    - b: The b tag is similar to the strong tag, as in it will display the text in bold, however it will no add any extra important to the text.    
    - i: The i tag is used to give a part of text an alternate voice or mood. The content will be displayed in italics.
    - small: The small tag is used to render the text to be smaller. 

6. Explain block Elements and also explain list of block elements and why they are used from below:
    - html: The html block elemetn is used to create the website. It creates the white canvas that you then fill with your content.
    - head: The head block element is placed between the html block element, and the body block element. This commonly includes things such as the document title, styles, and other metadata.
    - body: The body block element is the section that contains the most of your information. Inside you include everything that the viewer will read and see such as your nav, your header, the main, etc.
    - header: The header is the container used for introductory content. It's commonly used for the navigation section of any introduction text. It is placed at the top of the page.
    - nav: The nav tag is used to contain your set of navigation links. It is usually settled into the top of the page. 
    - main: The main block element is where you include the bulk of your content. This shouldn't include any parts such as nav, logos, copyright, etc, but only the main content of your webpage. 
    - section: The section block element is used to separate your content into separate sections. If you have 2 paragraphs with two different headers, you would divide them into sections.
    - article: An article tag is similar to a section tag, however, article is used for self contained content. It should be clear on its own and is a whole in of itself, compared to a section which is a part of another.
    - div: The div tag is used to divide a section of your html to then be styled separately, or simply to include the space between your content.
    - aside: The aside block element is used to place your content on the side of the page. It should be related to the surrounding content, but not enough to be fully incorporated. 
    - footer: The footer block element can be found at the bottom of the webpage. It's used to define and divide that section from the rest of your webpage. It typically includes the copyright information and any company information such as emails, phone numbers, etc.
    - span: The span tag is a container used to mark up a part of your document. This helps you style is easier later in your CSS file.
    - small: The small tag is used to make the size of your text smaller.

7. Explain why accessibility is important and also explain the accessibility properties like:
    Accessibility is important within your HTML file because it allows those with disabilities to enjoy your webpage as much as any other person could. It allows screen readers to properly read out your content to those who might not be able to themselves.
    - landmark roles: The landmark role is used to help the readers easily navigate through your webpage. It also makes it faster to find specific content.
    - aria labels: Aria labels are used to specify a certain part of your html further for those who use things such as screen readers. It helps define what those who can't see will miss.
    - image alternative texts: The image alternative texts are used in case your image can not be displayed. It also describes the image so that screen readers can describe what should have been displayed or simply give a mental image to those who can't see.

8. What is CSS and how can we implement CSS to our html file (write proper explanation with the code required to attach a CSS file inside html file).
    - CSS is the file and style sheet used to decorate and re-design the layout of your webpage. To implement the CSS file into your HTML file, you have to first of all create the folder and the file. Starting by naming your folder CSS, the creating a file named style.css . Inside of your html, you include the link tag '<link rel="stylesheet" href="css/style.css>' 
    and hit save! Now anything you style inside of your css style sheet will affect your html file.

9. What is the difference between CSS property and value (write explanation and example code).
    - A CSS property is used to define how you will change your html. This can be the size, the font, the colour, etc. The CSS value is used to define how, withing that selector, you will change it. This is where you would choose what size, which font, which colour, etc.

10. Why do we use border-box property in CSS?
    - The border-box property is used to ake into account any future values you will add to your content. If you were to add a border or any padding, the border-box property would take onto account those values and the content will change accordingly.

11. Explain different type of ways we can add spacing to an element.
    - Different types of ways we can add spacing to an element are with margin and padding. Another way is to simply use a p tag, though that will only add space between your different sections of text. Simply using the spacebar won't work because the html will condense it into 1 space naturally.

12. What is the main difference between margin and padding?
    - Padding, is used to put space between the content and its border. Margin, is used to put space between the content, and other content surrounding it.

13. What are different types of display properties?
    - There are many different kinds of display properties, but some of the main ones are inline, inline-block, block, flex, and flexbox. 

14. Write a brief explanation of flexbox property.
    - A flexbox property is a one-dimensional layout model.

15. What are different types of flexbox properties and what is the major difference between them?
    - The different types of flexbox properties are flex-direction, flex-flow, flex-wrap, justify-content, align-items and align-content. The major difference between them is that some are used to change how they are displayed one against another (flex-flow, flex-wrap, flex-direction), and the others (align-items, align-content, justify-content) are used to change how they are displayed on the webpage.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property.
    - '.class {
        display: flex;
        flex-direction: row-reverse;
        justify-content: center;
    }'
    Sub properties are what you use to indicate how they will move within the property selected. Example, if you use align-content, where are you aligning it to? The start, center, or the end? Is your flex-direction vertical? Or maybe horizontal?

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
    - '.class {
        display: flex;
        flex-wrap: wrap;
        align-content: center;
    }
    This examples indicates that there are multiple pieces of content that will wrap amongst each other. If we assume they're images, these flexbox properties will select them all, and move them all together according to the values set.

18. What is CSS grid property?
    - CSS grid property is a two-dimentional layout model.

19. Write the parent and two sub properties used for CSS Grid Property. 
    - '.class {
        display: grid;
    }'
    Similar to the flexbox property, grid property needs to be clarfied at the start of the CSS code to be used. This code allows you to then used the different grid properties on your content.

20. What is the difference between display: flex and display: grid?
    - The difference between display: flex; and display: grid; is that flexbox, designed for a one dimensional layout, and that grid was designed for two dimensional layout. While a flexbox allows you to transform your content in eiher a row, or a column, grid allows you to used both rows and columns at the same time.
    
21. What sub-property we use to divide elements in CSS Grid properties?
- 
22. What unit we use to fractionally divide the element width in CSS grid property and what are other units we can use alternatively? (Write code example).
- 
23. What is the area property in CSS grid we use for the child elements?
- 
24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
- 
25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
- 
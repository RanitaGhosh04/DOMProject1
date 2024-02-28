Here is a concise overview of the Document Object Model (DOM) in points:

1.Definition: DOM stands for Document Object Model.

2.Interface: It is a programming interface that allows manipulation of HTML or XML documents.

3.Representation: Views a document as a tree of objects, where each object represents a part of the document.

4.Nodes: Nodes are the individual objects in the tree, representing elements, attributes, or text content.

5.Top-Level Object: The top-level object is called the "document" and serves as an entry point to interact with the entire document.

6.Element: A type of node that represents HTML or XML elements, like <div> or <p>.

7.Attributes: Properties of elements, such as "id" or "class," are represented as attributes.

8.Text Node: Represents the text content of an element.

9.Dynamic Manipulation: Enables dynamic modification of document content, structure, and style using programming languages like JavaScript.


-->Objective: The assignment aims to ensure a consistent and visually appealing user interface (UI) across all steps of the project.
It involves using JavaScript to manipulate the style properties of a specific HTML element, which is retrieved using the getElementById method.

Steps:

1.HTML Structure:

-->Create an HTML file that includes the necessary structure.
-->Add a <div> element with a unique ID, which will be targeted in JavaScript.
![Screenshot (148)](https://github.com/RanitaGhosh04/DOMProject1/assets/82662107/59781120-9cc8-4cfc-99f2-c7e6ba6c855a)


Placing the <script> tag at the end of the HTML body is a common practice in web development, and it is often recommended for several reasons.


Here's an explanation of why scripts are sometimes placed at the end of the body tag:
![Screenshot 2024-02-28 223055](https://github.com/RanitaGhosh04/DOMProject1/assets/82662107/a2022d28-633e-4f97-a243-ebc35f938b4a)

1. Faster Rendering:
-->Placing scripts at the end allows the HTML content to load and render first.
Users can see and interact with the page while the script is being downloaded and executed.

3. Improved Page Load Performance:
-->When scripts are at the top, browsers must wait for the script to download and execute before rendering the rest of the page.
Placing scripts at the end minimizes the impact on initial page load times.

5. Progressive Rendering:
-->Users see a more responsive page because content appears incrementally while scripts are being processed.
This is particularly important for larger scripts or slower network connections.

7. Prevents Blocking:
-->Placing scripts at the end prevents the HTML parsing from being blocked by script execution.
Ensures that critical content is loaded first, and non-essential scripts don't hinder the initial rendering.

9. Parallel Loading:
-->Browsers can download multiple resources in parallel. Placing scripts at the end allows other resources (stylesheets, images) to download simultaneously.

Accessing an Element with getElementById:

In JavaScript, the getElementById method is employed to retrieve a reference to an HTML element based on its unique identifier, commonly known as the "id." 
This method facilitates developers in accessing and manipulating specific elements within a web page.


![Screenshot 2024-02-28 223451](https://github.com/RanitaGhosh04/DOMProject1/assets/82662107/2bf37f47-b8e5-44f0-adac-3a237aad2ae0)

Explanation:

-->The getElementById method is invoked on the document object, which represents the entire HTML document.

-->The method takes a single argument, the ID of the target element, specified within double quotes.

-->The returned value (element) is a reference to the HTML element with the specified ID.


In JavaScript, when setting styles using the style property, the property values are specified as strings, and the string is typically enclosed in double quotes.
This is because styles in JavaScript are applied as strings of CSS property-value pairs.

![Screenshot 2024-02-28 224600](https://github.com/RanitaGhosh04/DOMProject1/assets/82662107/15f30c99-990b-46f5-b124-3cf383fdac61)

Here, the value "yellow" is enclosed in double quotes because it is a string representing the color. This string is then assigned to the backgroundColor property of 
the style object for the specified HTML element.


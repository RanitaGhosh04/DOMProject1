Here is a concise overview of the Document Object Model (DOM) in points:

1.Definition: DOM stands for Document Object Model.

2.Interface: It is a programming interface that allows manipulation of HTML or XML documents.

3.Representation: Views a document as a tree of objects, where each object represents a part of the document.

4.Nodes: Nodes are the individual objects in the tree, representing elements, attributes, or text content.

5.Top-Level Object: The top-level object is called the "document" and serves as an entry point to interact with the entire document.

6.Element: A type of node that represents HTML or XML elements.

7.Attributes: Properties of elements, such as "id" or "class," are represented as attributes.

8.Text Node: Represents the text content of an element.

9.Dynamic Manipulation: Enables dynamic modification of document content, structure, and style using programming languages like JavaScript.


-->Objective: The assignment aims to ensure a consistent and visually appealing user interface (UI) across all steps of the project.
It involves using JavaScript to manipulate the style properties of a specific HTML element, which is retrieved using the getElementById method.

Steps:

1.HTML Structure:

-->Create an HTML file that includes the necessary structure.

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

-->The returned value (mainDivEl) is a reference to the HTML element with the specified ID.


In JavaScript, when setting styles using the style property, the property values are specified as strings, and the string is typically enclosed in double quotes.
This is because styles in JavaScript are applied as strings of CSS property-value pairs.

![Screenshot 2024-02-28 224600](https://github.com/RanitaGhosh04/DOMProject1/assets/82662107/15f30c99-990b-46f5-b124-3cf383fdac61)

Here, the value "yellow" is enclosed in double quotes because it is a string representing the color. This string is then assigned to the backgroundColor property of 
the style object for the specified HTML element.

-->mainDivEle:
mainDivEle is a variable representing an HTML element, likely obtained using methods like document.getElementById.

--> .style:
The dot (.) is used to access the style property of the mainDivEle element. The style property provides access to the inline styles of the element.
.backgroundColor = "yellow";

Another dot (.) is used to access the backgroundColor property within the style object. This sets the background color of the element to "yellow".
The dot notation allows you to access nested properties and methods of objects.

Let's break down the dot notation in more detail:

Object Access:

-->The dot (.) is used to access properties and methods of objects.
In this case, mainDivEle.style is an object representing the inline styles of the HTML element.

Nested Properties:

-->The dot notation allows access to nested properties or methods within objects.
For example, mainDivEle.style.backgroundColor accesses the backgroundColor property within the style object.

Property Assignment:

-->The dot notation is also used to assign values to properties. In this case, setting mainDivEle.style.backgroundColor = "yellow"; assigns the value "yellow" to the backgroundColor property.

The provided code applies the same dot notation concept to set various style properties, such as margin, padding, fontSize, fontWeight, height, width, and color.

![Screenshot 2024-02-28 225649](https://github.com/RanitaGhosh04/DOMProject1/assets/82662107/64ce21ca-f0ea-47ba-bf59-ef60d5e017b8)

CSS vs JS for Styling:

-->JavaScript is used for dynamic styling, while CSS is typically used for static styles.
-->JS can be advantageous for responsive or interactive styling based on user interactions.
-->CSS is more declarative and suitable for global styling or larger style sets.

In summary, the assignment involves creating an HTML file, linking it to a JavaScript file, accessing an element by ID, and dynamically styling the element using JavaScript.

How to push the code:

1.Open a command-line terminal (like Command Prompt or Terminal) and use the cd command to navigate to the directory where your HTML index file (e.g., index.html) is located. This step ensures that you are working in the correct directory.

2.Initialize a Git repository:
-->Run the command git init. This initializes a new Git repository in the current directory. It sets up the necessary Git infrastructure to start tracking changes in your project.
Add files to the staging area:

3.Execute git add . to add all files in the directory to the staging area. The staging area is a step before committing, allowing you to select which changes you want to include in the next commit.
Check the status of files:
-->Verify the status of your files with git status. This command shows you the files that have been modified, added to the staging area, or are untracked. It helps you confirm that you are committing the changes you intend to.

4.Commit the changes:
-->Commit the staged changes with git commit -m "first commit". This creates a snapshot of the changes along with a brief descriptive message.
The -m flag allows you to include a message directly in the command.

5.Rename the branch to main:
-->Rename the default branch from "master" to "main" using git branch -M main. This step is not always necessary,
but it ensures that the main branch is named consistently with modern Git practices.

6.Link the local repository to GitHub:
-->Connect your local repository to a remote repository on GitHub with git remote add origin https://github.com/RanitaGhosh04/DOMProject1.git

7.Push changes to GitHub:
-->Push your committed changes to the main branch on GitHub using git push -u origin main. This command uploads your local changes to the GitHub repository, making them accessible to others.

After completing these steps, if you create a README file, make changes, and commit them to the main branch, you can use similar commands to add, commit, and push those changes to GitHub.


How to Host the Site:

Step 1: Navigate to the "Settings" tab.

Step 2: Select "Pages" from the left-hand menu.

Step 3: Click on "Branch," switch to "main," and save your changes.

Step 4: Allow 2-3 minutes for the process to complete, then refresh the page to see your hosted site.

Hosted Site - https://ranitaghosh04.github.io/DOMProject1/

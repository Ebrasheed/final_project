# How to Create a Simple Webpage

**Author**: [Ebrahim Rasheed]  

**Summary**: This tutorial walks you through creating a basic webpage using HTML. The webpage will display the name "Darrel Truman," the college he attends, his major, year in college, and three clubs he is a part of.

**Target Audience**: Beginners with no prior knowledge of web development. Suitable for individuals aged 14+ who are interested in learning the basics of HTML.

---

## Contents

1. [Getting Started](#getting-started)
2. [Creating the HTML File](#creating-the-html-file)
3. [Writing the HTML Content](#writing-the-html-content)
4. [Styling the Page](#styling-the-page)
5. [Viewing the Webpage](#viewing-the-webpage)

---

## Getting Started

Before we begin, ensure you have the following:
- A text editor (e.g., Notepad++, VS Code, or Sublime Text)
- A web browser (e.g., Chrome, Firefox, or Edge)

---

## Creating the HTML File

1. Open your text editor.
2. Create a new file and save it as `index.html`.

---

## Writing the HTML Content

Open the `index.html` file and add the following content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Darrel Truman</title>
</head>
<body>
    <h1>Darrel Truman</h1>
    <h2>Student at Truman University</h2>
    <p><strong>Major:</strong> Computer Science</p>
    <p><strong>Year:</strong> Junior</p>
    <p><strong>Clubs:</strong></p>
    <ul>
        <li>Programming Club</li>
        <li>Basketball Enthusiasts</li>
        <li>Environmental Action Group</li>
    </ul>
</body>
</html>

How the Web App Works
At its heart, this application is a Client-Side Static Web App. Here is the "behind-the-scenes" flow:


The User's Request: When you type the URL into your browser, a request travels through the internet.


The Hosting Server: A static web server (like GitHub Pages or Netlify) receives that request and sends back three core files: index.html, style.css, and script.js.


Rendering: My browser reads the HTML for structure, the CSS for that Figma-inspired look, and the JavaScript to make the "Add Task" button actually work.

Persistence: To make sure your tasks don't vanish when you refresh the page, I used localStorage. This is a small database built directly into your web browser that stores your task list locally on your computer.

Steps Taken to Build It
Step 1: Defining the Blueprint (HTML)
I started by laying the foundation. I translated the Figma design into a semantic HTML structure. This included a header for the user profile, a card for the input field, and a list container where the tasks would eventually appear.

Step 2: Crafting the Aesthetic (CSS)
I used:

Custom Fonts: To give it a premium, modern feel.


Flexbox: To ensure the layout is responsive across different screen sizes.


Visual Feedback: Adding "strike-through" effects when a task is marked as completed so the user feels a sense of progress.

Step 3: Breathing Life into the App (JavaScript)
The app needed to do something, not just look good. I wrote JavaScript logic to handle three main actions:


Creation: Capturing what you type and adding it to an array of tasks.


Toggling: A function that flips a "completed" status from false to true.


Deletion: A feature to remove tasks you no longer need.

Step 4: Connecting the Infrastructure (Deployment)
Finally, I moved the project from my local computer to the "live" internet. By pushing the code to a platform like GitHub Pages or Netlify, I transformed local files into a public-facing web platform. This step demonstrates how the "Web Server" and "DNS" work together to make my work accessible to anyone with my link.

## 🌟 **Session 10: Your Favorite Things Page!** 🌟

### **Objective:**
In this session, you’ll create a special page all about your favorite things. You’ll use HTML to structure your content and CSS to make it look amazing. By the end of this session, you'll have a personalized webpage that showcases your top picks with pictures and descriptions!

---

### **1. Warm-Up Activity: Favorite Things Show and Tell** 🎤

**Duration:** 10 minutes

**Activity:** 

1. **Discussion:** Start by asking each student to briefly share one of their favorite things (could be a favorite game, book, hobby, etc.). Encourage them to describe why it's their favorite and what makes it special.
   
2. **Visualization:** Show an example of a simple "Favorite Things" webpage. Point out how pictures, headings, and descriptions can come together to tell a story about the topic.

**Goal:** This helps students think about how they want to present their own favorite things on their page.

---

### **2. Setting Up Your Project** 🛠️

**Duration:** 5 minutes

**Instructions:**

1. **Create a New File:**
   - Open Visual Studio Code (or your preferred code editor).
   - Create a new folder called `FavoriteThingsPage`.
   - Inside this folder, create two files: `index.html` and `styles.css`.

2. **Basic HTML Structure:**
   - Open `index.html` and add the basic HTML boilerplate:

     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>My Favorite Things</title>
         <link rel="stylesheet" href="styles.css">
     </head>
     <body>
         <header>
             <h1>My Favorite Things</h1>
         </header>
         <main>
             <!-- Your favorite things will go here -->
         </main>
         <footer>
             <p>Created by [Your Name]</p>
         </footer>
     </body>
     </html>
     ```

   - In `styles.css`, start with some basic styling:

     ```css
     body {
         font-family: Arial, sans-serif;
         line-height: 1.6;
         margin: 0;
         padding: 0;
     }

     header, footer {
         background-color: #f4f4f4;
         padding: 10px 0;
         text-align: center;
     }

     main {
         padding: 20px;
     }

     .favorite-item {
         margin-bottom: 20px;
     }

     .favorite-item img {
         width: 100px;
         height: auto;
         display: block;
         margin-bottom: 10px;
     }
     ```

---

### **3. Creating Your Favorite Things Page** ✏️

**Duration:** 30 minutes

**Instructions:**

1. **Add Content to `index.html`:**

   - Inside the `<main>` section, you’ll add a few favorite things. Here’s an example to guide you:

     ```html
     <main>
         <section class="favorite-item">
             <h2>My Favorite Book</h2>
             <img src="book.jpg" alt="Favorite Book">
             <p>This is a great book because...</p>
         </section>
         <section class="favorite-item">
             <h2>My Favorite Game</h2>
             <img src="game.jpg" alt="Favorite Game">
             <p>This game is amazing because...</p>
         </section>
         <!-- Add more favorite things as you like -->
     </main>
     ```

   - **Note:** Replace `book.jpg` and `game.jpg` with images related to the favorite things you choose. You can use placeholder images from the internet or draw your own.

2. **Style Your Content in `styles.css`:**

   - Enhance the appearance of your favorite things:

     ```css
     .favorite-item {
         border: 2px solid #ddd;
         border-radius: 8px;
         padding: 10px;
         background-color: #f9f9f9;
     }

     .favorite-item h2 {
         color: #333;
     }

     .favorite-item img {
         border-radius: 8px;
     }

     footer p {
         margin: 0;
         color: #666;
     }
     ```

   - Discuss with the students how different CSS properties (like border, padding, and colors) change the appearance of their page.

---

### **4. Interactive Exercise: Personal Touch** 🖼️

**Duration:** 10 minutes

**Activity:**

1. **Customization Challenge:**
   - Encourage students to personalize their pages with additional details. For example, they can add background colors, different fonts, or even animations using CSS.

2. **Peer Review:**
   - Pair students up and have them review each other’s pages. They should give constructive feedback and suggest any improvements.

---

### **5. Show and Tell: Share Your Work** 📸

**Duration:** 5 minutes

**Activity:**

1. **Presentation:**
   - Allow each student to present their "Favorite Things" page to the class. They should explain what they chose, why, and any special features they added.

2. **Reflection:**
   - Discuss what was learned from the project and how they might use these skills in future web development.

---

### **6. Wrap-Up and Homework** 📝

**Duration:** 5 minutes

**Homework Assignment:**
- Finish up any remaining work on their "Favorite Things" page.
- Prepare to share their projects in the next session, where they will discuss what they enjoyed most about the project and any challenges they faced.

**Closing:**
- Congratulate students on their progress and creativity. Remind them of the importance of showcasing their unique interests and how it helps them connect with their audience.

---

By focusing on a project that's personal and engaging, students will not only apply their HTML and CSS skills but also feel more connected to their work. This interactive approach helps make the learning process enjoyable and memorable.

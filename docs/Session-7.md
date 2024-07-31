
# 🌟 Session 7: Project 1 - About Me Page! 😎

Welcome to our first big project! Today, we’re going to use everything we’ve learned about HTML and CSS to create a fantastic “About Me” page. This page will showcase who you are, your interests, and some cool facts about you. Let’s get started!

## 🎯 **Learning Goals for Today**

By the end of this session, you will:
1. Create a personal “About Me” page using HTML and CSS.
2. Apply various HTML elements and CSS styles to your page.
3. Practice using the box model, positioning, and Flexbox for layout.

## 📖 **Project Overview**

Our goal is to build a simple, yet stylish “About Me” page. This page will include:

- A header with your name and a title.
- A section about yourself with a short bio.
- A list of your favorite things or hobbies.
- An image of yourself or something related to your interests.

### **1. Set Up Your Project Files**

1. **Create Project Folder:** Create a new folder named `about-me-project`.
2. **Create HTML and CSS Files:**
   - Inside the `about-me-project` folder, create a file named `index.html`.
   - Create another file named `styles.css`.

### **2. Build Your HTML Structure**

Open `index.html` and add the following HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>My Name</h1>
    <h2>Welcome to My About Me Page!</h2>
  </header>

  <section class="bio">
    <h3>About Me</h3>
    <p>Hello! I'm Ikromjon Ochilov, and I love Swimming. I’m passionate about Fullstack developer and enjoy spending time.</p>
  </section>

  <section class="favorites">
    <h3>My Favorite Things</h3>
    <ul>
      <li>Favorite Food: Shoshlik</li>
      <li>Favorite Movie: Besh Pancha</li>
      <li>Favorite Hobby: Commics</li>
    </ul>
  </section>

  <footer>
    <img src="#" alt="A picture of me">
    <p>Thank you for visiting my page!</p>
  </footer>
</body>
</html>
```

### **3. Style Your Page with CSS**

Open `styles.css` and add the following CSS to style your “About Me” page:

```css
/* Reset default browser styles */
body, h1, h2, h3, p, ul {
  margin: 0;
  padding: 0;
}

/* General styles */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

/* Header styles */
header {
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 20px;
}

header h1 {
  margin-bottom: 10px;
}

header h2 {
  margin-top: 0;
}

/* Bio section styles */
.bio {
  padding: 20px;
  background-color: white;
  margin: 10px;
  border-radius: 8px;
}

.bio h3 {
  color: #4CAF50;
}

/* Favorites section styles */
.favorites {
  padding: 20px;
  background-color: white;
  margin: 10px;
  border-radius: 8px;
}

.favorites h3 {
  color: #4CAF50;
}

.favorites ul {
  list-style-type: none;
}

.favorites li {
  padding: 5px 0;
}

/* Footer styles */
footer {
  text-align: center;
  padding: 20px;
  background-color: #4CAF50;
  color: white;
}

footer img {
  max-width: 100px;
  border-radius: 50%;
  margin-bottom: 10px;
}
```

### **4. Customize Your Page**

Replace the placeholders in `index.html` with your own content:

- **Header:** Replace “My Name” with your actual name.
- **Bio Section:** Add your personal details and interests.
- **Favorites Section:** List your favorite things.
- **Footer:** Add your image URL and any other details.

### **5. Save and Preview**

1. Save both `index.html` and `styles.css`.
2. Open `index.html` in your web browser to see your “About Me” page.

### **6. Additional Styling Tips**

- **Fonts:** Consider using Google Fonts to choose a stylish font.
- **Colors:** Use colors that match your personality and are easy on the eyes.
- **Layout:** Adjust margins and padding to make sure everything looks neat and well-spaced.

## 📚 **Interactive Quiz**

Test your knowledge with a quick quiz!

1. **What HTML element is used to create a header section?**
    - a) `<footer>`
    - b) `<section>`
    - c) `<header>`

2. **Which CSS property changes the background color of an element?**
    - a) `color`
    - b) `background-color`
    - c) `font-size`

3. **How do you add a link to your CSS file in an HTML document?**
    - a) `<link rel="stylesheet" href="styles.css">`
    - b) `<style src="styles.css">`
    - c) `<css link="styles.css">`

### **Quiz Answers:**

1. c) `<header>`
2. b) `background-color`
3. a) `<link rel="stylesheet" href="styles.css">`

## 🛠️ **Hands-On Project: Personalize Your About Me Page**

In this project, you’ll make your “About Me” page even more personal.

### **Project Steps:**

1. **Open Your Project Files:** Open `index.html` and `styles.css`.
2. **Enhance Your Page:** Add more sections or features to your page, such as:
   - A contact form
   - Links to your social media profiles
   - A fun fact or quote

3. **Save and Preview:** Save your changes and refresh your web browser to see the updates.

## ✨ **Wrap-Up and Homework**

Great job on your “About Me” page! Here’s what to do next:

- **Homework:** Finish personalizing your page. Try adding new styles and elements to make it even more unique.

- **Next Session Preview:** We’ll dive into more advanced CSS techniques, including CSS Grid for creating complex layouts.

## 🚀 **Fun Fact!**

Did you know that the first personal webpages were created in the 1990s by early internet users? They were simple and text-based, just like our “About Me” page!

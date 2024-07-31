# 🌟 Session 4: HTML - The Building Blocks of Your Website! Part 2 🧱

Welcome back, young web developers! Today, we’re going to continue building on what we’ve learned about HTML. We’ll explore more HTML elements and attributes that will help you add even more cool features to your webpage. Let’s get coding!

## 🎯 **Learning Goals for Today**

By the end of this session, you will:
1. Understand how to use images and links in HTML.
2. Learn how to use attributes to customize HTML elements.
3. Apply your knowledge by enhancing your webpage with images and links.

## 📖 **Recap: What We’ve Learned So Far**

In our previous session, we covered:
- Basic HTML elements like headings, paragraphs, and lists.
- How to structure a simple webpage.

Today, we’ll build on that foundation and learn how to add more exciting elements to your site!

## 🔍 **Exploring New HTML Elements**

### **1. Adding Images**

Images make your webpage more visually interesting. To add an image, use the `<img>` tag. This tag is self-closing and requires the `src` (source) attribute, which tells the browser where to find the image, and the `alt` attribute, which provides a text description of the image.

- **Example:**

  ```html
  <img src="my-photo.jpg" alt="A photo of me" width="300" height="200">
  ```

  - **`src`**: Specifies the path to your image file.
  - **`alt`**: Provides a description for users who cannot see the image.
  - **`width` and `height`**: Control the size of the image.

### **2. Adding Links**

Links are essential for navigating between webpages and websites. Use the `<a>` (anchor) tag to create a hyperlink. The `href` attribute specifies the URL of the page you want to link to.

- **Example:**

  ```html
  <a href="https://www.example.com">Visit Example.com</a>
  ```

  - **`href`**: Specifies the URL the link goes to.
  - **`target="_blank"`**: Opens the link in a new tab.

### **3. Attributes: Customizing HTML Elements**

Attributes provide additional information about HTML elements. They are added within the opening tag and are written as name-value pairs.

- **Common Attributes:**
  - **`href`** for links.
  - **`src`** for images.
  - **`alt`** for alternative text for images.
  - **`title`**: Adds extra information that appears when you hover over an element.

  - **Example:**

    ```html
    <a href="https://www.example.com" title="Click here to visit Example.com" target="_blank">Visit Example.com</a>
    ```

## 💻 **Interactive Coding Activity: Enhance Your Webpage!**

### **1. Set Up Your HTML File**

1. Open your coding editor and open the `index.html` file you created earlier.

### **2. Add an Image to Your Webpage**

Find a fun image you’d like to use (you can use any image file or search for images online). Save the image in the same folder as your HTML file.

1. Add the following code to your `index.html` file:

    ```html
    <img src="my-photo.jpg" alt="A photo of me" width="300" height="200">
    ```

2. Save the file and preview it in your web browser. You should see the image displayed on your webpage.

### **3. Create a Link to Another Website**

Add a link to your favorite website or a cool webpage you’ve found.

1. Add the following code below the image in your `index.html` file:

    ```html
    <a href="https://www.example.com" target="_blank">Visit Example.com</a>
    ```

2. Save the file and preview it. Click the link to ensure it opens the specified webpage in a new tab.

### **4. Customize Your Content**

Try adding a few more links and images to your webpage. For example, you could add:
- Links to your favorite websites.
- Images of your favorite places or things.

## 🎨 **Design and Style with HTML**

While today’s focus is on HTML, you can also start thinking about how to style your elements. Here’s a quick preview of how you can style images and links with CSS:

- **Example CSS for Styling Images and Links:**

  ```html
  <style>
    img {
      border: 2px solid #4CAF50;
      border-radius: 10px;
    }
    a {
      color: #FF5722;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
  ```

## 📚 **Interactive Quiz**

Test your understanding with a quick quiz!

1. **Which attribute do you use to specify the image file path?**
    - a) `href`
    - b) `src`
    - c) `alt`

2. **How do you make a link open in a new tab?**
    - a) Use the `href` attribute
    - b) Use the `target="_blank"` attribute
    - c) Use the `alt` attribute

3. **What does the `alt` attribute in an image tag do?**
    - a) Changes the image size
    - b) Provides a description of the image
    - c) Adds a border around the image

### **Quiz Answers:**

1. b) `src`
2. b) `target="_blank"`
3. b) Provides a description of the image

## 🎥 **Video Tutorial**

Watch this video that explains how to add images and links to your HTML page! [Insert link to a video tutorial here.]

## 🛠️ **Hands-On Project: Build a Fun Webpage**

In this project, you’ll enhance your personal webpage by adding images and links.

### **Project Steps:**

1. **Open Your HTML File:** Open the `personal.html` file you created earlier.
2. **Add an Image:**

    ```html
    <img src="my-favorite-place.jpg" alt="A beautiful place I visited" width="400" height="250">
    ```

3. **Add Links:**

    ```html
    <p>Check out my favorite websites:</p>
    <ul>
      <li><a href="https://www.favorite-site.com" target="_blank">Favorite Site</a></li>
      <li><a href="https://www.another-site.com" target="_blank">Another Site</a></li>
    </ul>
    ```

4. **Save and Preview:** Open your `personal.html` file in your browser and see the new features you’ve added.

## ✨ **Wrap-Up and Homework**

Great job today! Here’s what you need to do:

- **Homework:** Finish adding images and links to your personal webpage. Experiment with different attributes and styles to make your page unique.

- **Next Session Preview:** We’ll start exploring CSS to make your webpage look even more amazing!

## 🚀 **Fun Fact!**

Did you know that the first image ever uploaded to the web was a picture of a band called “Les Horribles Cernettes” by Tim Berners-Lee in 1992? It was the first experiment in embedding images on a webpage!

---

That’s all for today! Keep practicing and exploring HTML. See you in the next session where we’ll start making your site look great with CSS! 🎉


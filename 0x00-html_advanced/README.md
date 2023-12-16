# 0x00. Advanced HTML

### HTML Guidelines and Basics

1. **Skeleton of an HTML5 Page:**
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Your Page Title</title>
   </head>
   <body>
       <!-- Your content goes here -->
   </body>
   </html>
   ```

2. **Semantic HTML Tags:**
   - Use tags like `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, and `<footer>` to give meaning to the structure of your document.

3. **Use Cases for `<div>` vs `<span>`:**
   - Use `<div>` for block-level containers.
   - Use `<span>` for inline elements.

4. **Semantic Value of Tags:**
   - `<header>`: Represents introductory content, often containing headings and navigation.
   - `<main>`: Contains the central content of the document.
   - `<footer>`: Represents a footer for a section or page.
   - `<article>`: Represents a self-contained piece of content.
   - `<nav>`: Represents a navigation menu.
   - `<section>`: Represents a thematic grouping of content.
   - `<aside>`: Represents content tangentially related to the content around it.

5. **Headings and Hierarchy:**
   - Use `<h1>` to `<h6>` to define headings. Follow a hierarchical order for better accessibility and SEO.

6. **Lists in HTML:**
   - Use `<ul>` for unordered lists and `<ol>` for ordered lists.
   - Use `<li>` for list items.

7. **Differences Between Image Formats:**
   - **SVG (Scalable Vector Graphics):** Vector format, great for logos and icons.
   - **GIF (Graphics Interchange Format):** Supports animations and transparency but has limited colors.
   - **PNG (Portable Network Graphics):** Supports transparency and higher color depth.
   - **JPG (Joint Photographic Experts Group):** Best for photographs and images with gradients.

8. **Table Structure:**
   ```html
   <table>
       <thead>
           <tr>
               <th>Header 1</th>
               <th>Header 2</th>
           </tr>
       </thead>
       <tbody>
           <tr>
               <td>Data 1</td>
               <td>Data 2</td>
           </tr>
       </tbody>
   </table>
   ```

9. **Embedding Video:**
   ```html
   <video width="640" height="360" controls>
       <source src="your_video.mp4" type="video/mp4">
       Your browser does not support the video tag.
   </video>
   ```

10. **Embedding Audio:**
    ```html
    <audio controls>
        <source src="your_audio.mp3" type="audio/mp3">
        Your browser does not support the audio tag.
    </audio>
    ```

11. **Embedding External Content:**
    - Use `<iframe>` for embedding external content like maps, videos, or other webpages.

12. **Correct HTML Page Structure:**
    - Follow a clear hierarchy with proper indentation.
    - Use semantic tags to enhance readability and accessibility.

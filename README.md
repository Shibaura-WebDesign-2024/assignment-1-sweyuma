[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/gLxG_S83)
# Assignment 1

### Part 1: Getting started with HTML structuring

1. Type the home page content below into the new document in your text editor (notepad
for Windows, TextEdit for Mac). Copy it exactly as you see it here, keeping the line
breaks the same for the sake of playing along.
<img width="792" alt="Screenshot 2024-04-17 at 18 46 27" src="https://github.com/Shibaura-WebDesign-2024/Homework1/assets/82876331/d263acef-7236-43d2-9465-6a721c77c921">

2. Create a file called index.html. The filename needs to end in .html to be recognized by the browser as a web document.

3. Just for kicks, let’s take a look at index.html in a browser.
    - Windows users: Double-click the filename in the File Explorer to launch your default
browser, or right-click the file for the option to open it in the browser of your choice.
    - Mac users: Launch your favorite browser (I’m using Google Chrome) and choose
Open or Open File from the File menu. 

### Part 2: Adding minimal structure

1. Open the new index.html document (in your text editor) if it isn’t open already and
    add the DOCTYPE declaration:

      ```
      <!DOCTYPE html>
      ```
2. Put the entire document in an HTML root element by adding an <html> start tag after
    the DOCTYPE and an </html> end tag at the very end of the text.
3. Next, create the document head that contains the title for the page. Insert <head> and
    </head> tags before the content. Within the head element, add information about the
    character encoding <meta charset="utf-8">, and the title, “Black Goose Bistro”,
    surrounded by opening and closing <title> tags.
4. Finally, define the body of the document by wrapping the text content in <body> and
    </body> tags. When you are done, the source document should look like this (the
    markup is shown in color to make it stand out, and I added line numbers in grey):
<p align="center">
<img width="929" alt="Screenshot 2024-04-17 at 18 49 53" src="https://github.com/Shibaura-WebDesign-2024/Homework1/assets/82876331/5ae71286-ded7-46cd-b588-e678e92ecf95">
</p>
5. Open the file in the browser or hit Refresh or Reload if it is open already.
6. Save the document and upload it to to github as well.

### Part 3: Defining text elements

1. Open the document _index.html_ in your text editor, if it isn’t open already.
2. The first line of text, “Black Goose Bistro,” is the main heading for the page, so we’ll
    mark it up as a Heading Level 1 (h1) element. Put the opening tag, h1, at the
    beginning of the line and the closing tag, h1, after it, like this:

      ```
      <h1>Black Goose Bistro</h1>
      ```
3. Our page also has three subheads. Mark them up as Heading Level 2 (h2) elements in a
    similar manner. I’ll do the first one here; you do the same for “Catering” and “Location
    and Hours.”

      ```
      <h2>The Restaurant</h2>
      ```
4. Each h2 element is followed by a brief paragraph of text, so let’s mark those up as
4. paragraph (p) elements in a similar manner. Here’s the first one; you do the rest:

    ```
    <p>The Black Goose Bistro offers casual lunch and
    dinner fare in a relaxed atmosphere. The menu changes
    regularly to highlight the freshest local
    ingredients.</p>
    ```

5. Finally, in the Catering section, I want to emphasize that visitors should just leave the
    cooking to us. To make text emphasized, mark it up in an emphasis element (em)
    element, as shown here:

    ```
    <p>You have fun. <em>We'll handle the cooking.</em>
    Black Goose Catering can handle events from snacks
    for a meetup to elegant corporate fundraisers.</p>
    ```
6. Now that we’ve marked up the document, let’s save it as we did before, and open (or
    reload) the page in the browser.

### Part 4: Adding an image

1. Download any image that you like (according to the content here, it should be a goose
    image) Name the file _blackgoose.png_. Be sure to save it in the same folder with
    _index.html_. Make sure that the size of the image is not too big (you can edit the image
    size using paint in windows or preview in mac).
    The image size as an example used in this document is 175 x 175 px)
2. Once you have the image, insert it at the beginning of the first-level heading by typing in
    the img element and its attributes as shown here:

    ```
    <h1><img src="blackgoose.png" alt="logo">Black Goose
    Bistro</h1>
    ```
    ```
    The src attribute provides the name of the image file that should be inserted, and the alt
    attribute provides text that should be displayed if the image is not available. Both of these
    attributes are required in every img element.
    ```
3. I’d like the image to appear above the title, so add a line break (br) after the img element
    to start the headline text on a new line.

    ```
    <h1><img src="blackgoose.png" alt="logo"><br>Black
    Goose Bistro</h1>
    ```
4. Let’s break up the last paragraph into three lines for better clarity. Drop a (br) tag at the
    spots you’d like the line breaks to occur. Try to match the screenshot in Figure 1.
5. Now save _index.html_ and open or refresh it in the browser window. The page should look
    like the one shown in Figure 1. If it doesn’t, check to make sure that the image file,
    blackgoose.png, is in the same directory as index.html. If it is, then check to make sure
    that you aren’t missing any characters, such as a **closing quote** or **bracket** , in the img
    element markup.

### Part 5: Adding a Style sheet

1. Open _index.html_ if it isn’t open already. We’re going to use the style element to apply a
    very simple embedded style sheet to the page. This is just one of the ways to add a style
    sheet.
2. The style element is placed inside the document head. Start by adding the style element to
    the document as shown here:

    ```
    <head>
    ```
    ```
    <meta charset="utf-8">
    ```
    ```
    <title>Black Goose Bistro</title>
    ```
    ```
    <style>
    ```
    ```
    </style>
    ```
    ```
    </head>
    ```
3. Next, type the following style rules within the style element just as you see them here.
    Don’t worry if you don’t know exactly what’s going on (although it’s fairly intuitive).
    You’ll learn all about style rules in the future classes
<p align="center">
<img width="453" alt="Screenshot 2024-04-17 at 18 54 06" src="https://github.com/Shibaura-WebDesign-2024/Homework1/assets/82876331/5f8cf3ea-dc0f-4dba-8040-b44575e4fd7c">
</p>

4. Now it’s time to save the file and take a look at it in the browser. It should look like the
    page in Figure 2. If it doesn’t, go over the style sheet to make sure you didn’t miss a
    **semicolon** or a **curly bracket**. Look at the way the page looks with our styles compared
    to the browser’s default styles.
<p align="center">
<img width="574" alt="Screenshot 2024-04-17 at 18 55 02" src="https://github.com/Shibaura-WebDesign-2024/Homework1/assets/82876331/bb4791ee-0fe1-4d30-93af-40475efb8794">
</p>

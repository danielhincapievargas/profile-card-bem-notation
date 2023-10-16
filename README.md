# profile-card-bem-notation

This project is about a business card, for which the HTML and CSS have been built using the BEM notation.

### Screenshot

![image]('./assets/profile-card-bem.jpg')

### BEM Notation

```html
  <div class="buttons">
    <div class="buttons__container">
        <button class="btn buttons__read">Read More</button>
    </div>
    <div class="buttons__container">
        <button class="btn buttons__contact buttons--color">Contact</button>
    </div>
  </div>
```
In this small snippet of code, you can see a block (buttons) with its elements (buttons__read and buttons__contact) and a modifier (buttons--color).

### How to see The Profile Card

To view an HTML file in a browser from Visual Studio Code, follow these steps:

1. Make sure you have Visual Studio Code installed on your computer. If you don't have it, you can download and install it from the official website: https://code.visualstudio.com/

2. Clone the Git repository that contains the HTML file to your local machine. You can use the following command in your terminal:

```bash
git clone <repository_url>
```
Replace <repository_url> with the URL of this repository.


3. Open Visual Studio Code.

4. Open the folder containing the HTML file or open the file directly in Visual Studio Code.

5. Ensure that the HTML file is active in the Visual Studio Code window. You should be able to see its content in the editor.

6. Right-click on the HTML file in the Visual Studio Code sidebar and select "Open with Live Server" if you have the Live Server extension installed. This extension allows you to open the HTML file on a local server and view it in a browser automatically.
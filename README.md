# Triple Peaks Coffee Shop

This is the second project of the Software Engineering program at TripleTen. It was created using HTML and CSS, based on the design brief.

## Project features

- Semantic HTML5
- Flexbox
- Positioning
- Flat BEM file structure
- A custom form
- CSS animation and transform
- Command Line Interface
- Git Repositories via SSH connections

## Plan on improving the project

- Updates I would implement, but didn't for the sake of the project is making the bottom logo `<a href="">` to direct back to the main page / top of the page.

- I would love to see a transition included with a slight opacity change to the logo.

- I would also include an "About" link in the Navigation that links to the About section of the page.

### Modifications to the content & brief:

Original:

````
.header {
    display: flex;
    flex-direction: column;
    height: 100vh;
    min-height: 720px;
    max-height: 800px;
    padding: 30px 80px 40px;
    position: relative;
    box-sizing: border-box;
    background-image: url(../images/background_header.svg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}
    ```

    Focusing on background-position: center; Which generates an undesirable effect shown below.

    <img src="../se_project_coffeeshop/README_images/orginal.png" width="500">

Updated:

    ```
.header {
    display: flex;
    flex-direction: column;
    height: 100vh;
    min-height: 720px;
    max-height: 800px;
    padding: 30px 80px 40px;
    position: relative;
    box-sizing: border-box;
    background-image: url(../images/background_header.svg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: right;
}
    ```

    background-position: right; which generates a much more desirable effect without modifying the overall look or flow of the page, shown below.

<img src="../se_project_coffeeshop/README_images/edited.png" width="500">
````

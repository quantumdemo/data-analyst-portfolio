# Elen - A Simple Blog Template

This is a simple blog template that has been modified to make it easier to add new blog posts and to support theme toggling.

## Project Structure

- `css/`: Contains the CSS files for the project.
  - `style.css`: The main stylesheet for the project.
  - `dark.css`: The stylesheet for the dark theme.
- `fonts/`: Contains the font files for the project.
- `images/`: Contains the image files for the project.
- `js/`: Contains the JavaScript files for the project.
  - `main.js`: The main JavaScript file for the project.
- `posts/`: Contains the blog posts.
  - `posts.json`: A JSON file that contains the metadata for the blog posts.
- `*.html`: The HTML files for the project.

## How to Add a New Blog Post

To add a new blog post, you need to do the following:

1.  Add a new entry to the `posts/posts.json` file. The entry should have the following format:

    ```json
    {
      "id": 3,
      "title": "My New Blog Post",
      "image": "images/image_3.jpg",
      "content": "This is the content of my new blog post."
    }
    ```

2.  Make sure that the `id` is unique.

3.  Make sure that the `image` path is correct.

## How to Toggle the Theme

To toggle the theme, click on the moon icon in the navigation bar.

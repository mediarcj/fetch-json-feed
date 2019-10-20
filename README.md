# [Rebirth of Reddit]
An exercise in developing a Reddit-themed image gallery by using the [Reddit API](https://www.reddit.com/dev/api/). Operates by fetching the JSON feed of any subreddit by adding a `.json` extension to the URL.

`Ex. http://www.reddit.com/r/javascript -> http://www.reddit.com/r/javascript.json`

### Objectives

Use the Reddit API to achieve the following:

1. Analyze Reddit API data and whiteboard a proposed design concept.

2. Add styles by compiling SASS to CSS with Gulp.

3. Use the layouts defined in the Layouts directory:
    - The image should fill the entire area of the rectangular box.
      - Optional: *Create your markup so that each image is displayed as  a background image but also included in an `<img>` tag so it is visible to the DOM.*
    - The title should never span more than 2 lines tall.
    - The subtitle line should never span more than 2 lines tall.
    - The text snippet should never span more than 4 lines tall, except in mobile view, where it should be the height of the text.
    - Google fonts used in the layout:
      - Oswald Regular
      - Lato Regular
    - The final application must match the mockups at the sizes specified, and must gracefully transition at each range.

4. Upon page load, the application must pull in the current feed via AJAX from the API endpoint of the user's choosing.

5. Dynamically create and style each page's feed list from the data received from the API.

6. Use appropriate best practices when building the application.

### Bonus

Add features such as:
  - Infinite scrolling
  - Reddit search engine (i.e., get data from any subreddit)


# February 2020

## Objectives and Key Results

### Objective
- [ ] Learn WordPress development.

### Key Results
- [ ] Read [WordPress Theme Handbook]((https://developer.wordpress.org/themes/)).
- [ ] Finish Udemy course [Become a WordPress Developer](https://www.udemy.com/course/become-a-wordpress-developer-php-javascript/) by Brad Schiff.
- [ ] Develop website for practice project similar to course project for Become a WordPress Developer.

## Daily Logs

### Monday, Februar 24, 2020
- Started Udemy course Become a WordPress Developer by Brad Schiff.
  - Set up [Local](https://localwp.com) by Flywheel as local environment for WordPress development.
  - Created local WordPress site for Fictional University.
  - Wrote first lines of PHP, learned how to declare variables.
  - Created new theme for Fictional University with index.php, style.css, screenshot.png (1200px x 900px).
  - Learned how to define and call functions in PHP.
  - Learned how to loop through arrays in PHP with while loop.
  - Learned how to use loop to display multiple posts, single posts, or pages.
  - Added single.php and page.php to theme.

- Updated Learning Tracker on GitHub with log for February 2020.
  - Figured out how to use [Markdown](https://code.visualstudio.com/docs/languages/markdown) preview in VS Code.
  - Installed VS Code extension [GitHub Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview).
  - Figured out how to use [version control](https://code.visualstudio.com/docs/editor/versioncontrol) with git and GitHub in VS Code.

### Tuesday, February 25, 2020
- Reviewed yesterday's lessons in Become a WordPress Developer.
  - In PHP, double quoted strings can format strings using defined variable.
  - "Theme Name", "Author", and "Version" of theme are added to comment at the beginning of the style.css file.
  - Blog title and tagline can be added to page with PHP function bloginfo('name') and bloginfo('description').
- Revised and updated README file for Learning Tracker on GitHub.

### Wednesday, February 26, 2020

- Finished update and revision of README file for Learning Tracker, added MIT license to Learning Tracker.
- Continued Become a WordPress Developer:
  - Set up global header and footer, used get_header() and get_footer() to connect heater and footer templates to other template files.
  -  Split HTML boilerplate between header and footer templates and called wp_head() in head section of header template.
  - Created functions.php file, defined function to enqueue main stylesheet using get_stylesheet_uri() and called function using wp_enqueue_scripts action.
  - Added wp_footer() to end of body section to footer.php to add black admin bar to top of page when logged in.
  - Converted static HTML/CSS template into WordPress theme:
    - copied & pasted HTML code for header and footer,
    - copied & pasted CSS into main stylesheet,
    - added links for Font Awesome and Google Fonts to enqueue function,
    - copied & pasted content for homepage into index.php,
    - moved images, css, and js folders into theme folder,
    - updated paths for images with echo get_theme_file_uri(),
    - added link to JS script bundle for slideshow to enqueue function.
  - Avoided CSS and JS caching during development by using microtime() as version number for main stylesheet and  JS script bundle in enqueue function.

### Thursday, February 27, 2020
- Read "Getting Started" section of the WordPress Theme Handbook.
- Reviewed yesterday's lessons in Become a WordPress Developer.


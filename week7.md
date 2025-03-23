# Reece Kelly
# Week 7: Learning Journal

## Learning Activities & Resources

[How to Create a Custom WordPress Theme Full Course - YouTube (50% Complete)](https://www.youtube.com/watch?v=-h7gOJbIpmo&ab_channel=freeCodeCamp.org)

[PHP Programming Problems - Code Wars](https://www.codewars.com/users/Reece_K)

## Estimated Hours

I spent approximately 2.5 hours on explicit learning activities this week.

## Content Insights

There are only two files required when creating a WordPress theme: style.css for styling and index.php as the default template to fall back to if no others are found.

The WordPress template hierarchy is a system that WordPress uses to determine which template files to load and display content based on different types of pages or content. It can be found [here](https://developer.wordpress.org/themes/basics/template-hierarchy/). For example, if you want to create a unique style and layout for articles on your website, the template hierarchy enables you to do this by using specific template files like single.php. If you don’t define a custom style for a particular page, WordPress will automatically fall back to index.php, ensuring your site remains functional.

Specific metadata is required in a comment block at the top of the style.css in a WordPress theme. This metadata includes important details such as the theme name, author, description, version, and licence. This metadata allows WordPress to identify and display the theme correctly in the WordPress dashboard. Only the theme name is required for WordPress to recognise and activate a theme.

PHP (Hypertext Preprocessor, originally meaning Personal Home Page) is an HTML-embedded scripting language used to create dynamic websites. In a PHP file, you can combine PHP and HTML. The file cannot be an HTML file, as the server will not execute PHP code in an HTML file. When PHP is run on the server, it is sent to the PHP interpreter, which processes the code and generates HTML. This HTML is then sent to the client's browser. PHP code is enclosed in <?php ?> tags, and variables start with a $ sign.

Styles and scripts are enqueued using the wp_enqueue_style and wp_enqueue_script functions in the functions.php file.

The header.php and footer.php files are created to separate the header and footer content from the main template. On top of this, the wp_head() and wp_footer() functions are used to dynamically load styles and scripts in the header and footer.

## Career/Employability/Learning Insights

This week, I noticed a decline in my motivation to complete certain tasks, which I believe was due to not starting my work for the practical or the journal at my usual time. Generally, I start either Tuesday night or Wednesday morning. However, because there was no practical this week due to the floods I ended up not starting my work until later. This shift in routine in combination with having more work than usual contributed to my lack of motivation. Based on this insight, I will now aim to start my work at the same time every week to avoid any lack of motivation.

While I haven’t had to use PHP at all while creating my CMS websites this trimester, I have seen how it would be an important skill to have if you were trying to gain employment in the web development industry. It made it very simple to add dynamic content to the AdviceShop website, and I can see how PHP’s ability to interact with databases and generate dynamic HTML is very valuable for building large, interactive sites. I believe having knowledge and skills in PHP would be valuable to a future employer because it demonstrates an understanding of how dynamic websites function, even if the job does not require extensive use of PHP.
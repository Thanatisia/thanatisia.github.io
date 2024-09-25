# CHANGELOGS

## Table of Contents
+ [2024-09-25](#2024-09-25)

## Entries

### 2024-09-25

#### 1110H
- New
    + Initial Commit/Update to new portfolio website (in development)
    - Added files
        + CHANGELOGS.md
        + CONTRIBUTING.md
        + README.md
    - Added directories
        - Added new directory 'docs/'
            - Added new directory 'screenshots'
                - Added new directory 'website-design'
                    - Added new directory 'pages'
                        - Added new directory '1144x1056px' for containing screenshots of the website in 1144 x 1056 px
                            + Added new screenshot 'index-page.png'
                            + Added new screenshot 'about-page.png'
                            + Added new screenshot 'blog-entry-test-page.png'
                            + Added new screenshot 'blog-table-of-contents-page.png'
                        - Added new directory 'full-size' for containing screenshots of the website in full screen
                            + Added new screenshot 'index-page.png'
                            + Added new screenshot 'about-page.png'
                            + Added new screenshot 'blog-entry-test-page.png'
                            + Added new screenshot 'blog-table-of-contents-page.png'
        - Added new directory 'templates/' containing template skeleton files
            - Added new directory 'sites' containing templates for Web site pages
                + Added new template skeleton file 'pages.html'
                + Added new template skeleton file 'blog-posts.html'
                + Added new template skeleton file 'index.template.1.html'
                + Added new template skeleton file 'index.template.2.html'
        - Added new directory 'src/'
            + Added file 'index.html'
            - Added subdirectory 'assets/'
                - Added subdirectory 'lib/'
                    + index.js
                - Added subdirectory 'style'
                    + constants.css
                    + designs.css
                    + index.css
                    + portfolio.css
                    - Added new directory 'colorschemes' for storing colorscheme CSS files
                        + Added new CSS file for colorscheme 'deep-vintage-mood.css'
                        + Added new CSS file for colorscheme 'metallic-chic.css'
            - Added subdirectory 'pages'
                + Added new page 'about-me.html'
                - Added subdirectory 'blog'
                    + table-of-contents.html
                    - Added subdirectory 'posts'
                        - Added subdirectory '2024-09-21'
                            + Added new test blog post '1606H.html'

#### 1113H
- Updates
    - Migrated 'index.html' from 'src/' => root

#### 1119H
- Updates
    - Updated pages/sites 'src/pages/about-me.html', 'src/pages/blog/posts/2024-09-21/1606H.html', 'src/pages/blog/table-of-contents.html'
        + Replaced path to index.html

#### 1127H
- Updates
    - Updated pages/site 'index.html', 'src/pages/about-me.html', 'src/pages/blog/posts/2024-09-21/1606H.html', 'src/pages/blog/table-of-contents.html'
        + Updated path from static to relative path

#### 2053H
- New
    - Added new blog post for date '2024-09-25' in 'src/pages/blog/posts/'
        + Added new blog post entry '1553H.html'
- Updates
    - Updated document 'README.md'
        + Added documentations and screenshots
    - Updated webpage 'index.html'
        + Migrated section 'about-me' from about-me.html back to index page
        + Modified style to align a group of components side-by-side
        + Added several portfolio projects
    - Updated CSS stylesheet 'index.css' in 'src/assets/style/'
        + Added new CSS class
    - Updated webpage '1606H.html' in 'src/pages/blog/posts/2024-09-21/'
        + Updated redirecting to about-us
        + Changed br tag to hr tag
    - Updated document 'table-of-contents.html' in 'src/pages/blog/'
        + Updated redirecting to about-us
        + Changed br tag to hr tag


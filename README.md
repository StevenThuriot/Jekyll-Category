# Jekyll-Category
Category page generator, including pagination  and rss feeds.

This generator also mimicks Jekyll's paginator, so it can reuse both its settings and `_include` files.

# Usage

* `_includes\custom\category_feed.xml` is set up in advance. Adjust if needed.
* Set up `_layouts\category_index.html` with your customized layout.

The following variables are available:

## Page
* slug
* category
* dir
* subscriptionUrl (rss feed url)

## Context
* paginator
    * page
    * per_page
    * posts
    * total_posts
    * total_pages
    * previous_page
    * previous_page_path
    * next_page
    * next_page_path
    
    
## _config.yml
* category_dir
* paginate
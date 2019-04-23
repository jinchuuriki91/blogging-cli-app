## Blogging Command-Line App

Create a command-line blogging application which implements following commands in bash

|Status|Command|Action|
|---|---|---|
|`ToDo`|`blog.sh`|Return name of your application|
|`ToDo`|`blog.sh --help`|List help text and commands available|
|`ToDo`|`blog.sh post add "title" "content"`|Add a new blog post with the specified title and content|
|`ToDo`|`blog.sh post list`|List all blog posts|
|`ToDo`|`blog.sh post search "keyword"`|List all blog posts where “keyword” is found in the title and/or content|
|`ToDo`|`blog.sh category add "category-name"`|Create a new category|
|`ToDo`|`blog.sh category list`|List all current categories|
|`ToDo`|`blog.sh category assign <post-id> <cat-id>`|Assign the specified category to a post|
|`ToDo`|`blog.sh post add "title" "content" --category "cat-name"`|Add a new blog post with the specified title, content and assign a category to it. If the category doesn’t exist, it will first be created|

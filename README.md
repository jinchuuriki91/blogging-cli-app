## Blogging Command-Line App

Create a command-line blogging application which implements following commands in bash

|Status|Command|Action|
|---|---|---|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh`|Return name of your application|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh --help`|List help text and commands available|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh post add "title" "content"`|Add a new blog post with the specified title and content|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh post list`|List all blog posts|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh post search "keyword"`|List all blog posts where “keyword” is found in the title and/or content|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh category add "category-name"`|Create a new category|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh category list`|List all current categories|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh category assign <post-id> <cat-id>`|Assign the specified category to a post|
|<code style="background-color: #d9b51c">Todo</code>|`blog.sh post add "title" "content" --category "cat-name"`|Add a new blog post with the specified title, content and assign a category to it. If the category doesn’t exist, it will first be created|
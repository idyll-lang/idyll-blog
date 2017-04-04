
# idyll-blog
[WORK IN PROGRESS] Blog engine using Idyll

## Installation

```
$ npm install -g idyll-blog
```

## Usage

```sh
# Create a new post with the slug "my-post"
$ idyll-blog create-post src/ --slug my-post

# Launch a local webserver displaying the post 
$ idyll-blog serve my-post

# Edit your post ...

# Compile the assets for publication
$ idyll-blog --build src/ -o build/

# Deploy the post
$ idyll-blog --deploy my-post
```

## Options 

* `--css` - Defines sitewide CSS 
* `--site-html` - Define a sidewide HTML page to use


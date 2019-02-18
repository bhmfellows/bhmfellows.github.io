# bhmfellows.github.io

## Adding Content to the Guide

1. Create a post
2. Add it to the appropriate category


## Using Categories

Categories are little bit tricky. Please make sure to do the following for each category:

Create a file within categories folder with the name of your category For example let's say that we have a category called An Awesome Category you will need to add an an-awesome-category.html file with this content:

```
layout: category
category: an-awesome-category
permalink: /categories/an-awesome-category/
```

Create an entry inside _data/categories.yml

```
- slug: an-awesome-category
  name: An Awesome Category
```  
   
Then you will see it in the footer in the Explore section.

## Other tips for website setup


- [How to point a domain on Google Domains to GitHub pages](http://www.curtismlarson.com/blog/2015/04/12/github-pages-google-domains/)


To preview a Jekyll / Github Pages site, run the following command line in its own terminal:

```
jekyll serve --host=$IP --port=$PORT --drafts
```

## License

The contents of this repository is licensed under [The MIT License](https://opensource.org/licenses/MIT).

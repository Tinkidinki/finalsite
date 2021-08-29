# tinkidinki.github.io

Welcome to the repository of my [personal website](https://tinkidinki.github.io/), where you can see behind the scenes!

### Theme
The website uses the [minima](https://github.com/jekyll/minima) theme, as well as the stylesheets from the [personal-website](https://github.com/github/personal-website) repository.

### Redirection
In order to redirect some pages to external sites, for example, the `projects` page, I used the [jekyll-redirect-from gem](https://github.com/jekyll/jekyll-redirect-from). 

### Mathjax
To make mathjax work, I followed the instructions from this [site](http://webdocs.cs.ualberta.ca/~zichen2/blog/coding/setup/2019/02/17/how-to-add-mathjax-support-to-jekyll.html). However, while this rendered locally, this did not render on `https` pages. For mathjax to work on `https`, I had to modify the line in `head.html` slightly, as discussed in [this comment](https://github.com/github/pages-gem/issues/307#issuecomment-275747524).

### Display blogposts by selected tags
To display blogposts belonging to a certain tag upon selection of the tag, I followed the somewhat quick and dirty method in the tutorial present [here](https://rxxb.github.io/2020/11/post/jekyll-tag-listing) 

### Preventing scrolling due to anchor in the url
The quick and dirty trick used to display only posts belonging to a tag when the tag is clicked unfortunately led to the page scrolling down inconveniently upon click. Thus, to prevent this from happening, I had to use another "quick and dirty trick" from [this Stack Overflow answer](https://stackoverflow.com/a/33877034/5391777).

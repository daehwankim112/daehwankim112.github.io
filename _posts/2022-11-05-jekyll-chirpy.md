---
title: Jekyll Chirpy
date: 2022-11-05 21:00:00 -0800
categories: [Projects, jekyll chirpy]
tags: [github,page,jekyll,chirpy,daehwan,kim,david]     # TAG names should always be lowercase
---

# Hello World!

This is my first post on my github page. This page is generated using jekyll chirpy.

Check their github: https://github.com/cotes2020/jekyll-theme-chirpy

Techno Tim's tutorial on Jekyll helped me setting this up.
https://youtu.be/F8iOU1ci19Q



# Jekyll

Jekyll is a static site generator. It takes test written in your favorite markup language and uses layouts to create a static website.

## Writing a New Post
A new post is written in markdown language. Detailed documentation: https://chirpy.cotes.page/posts/write-a-new-post/

### Font Size
Font Size can be controlled using "#"

```yaml
#:      H1
##:     H2
###:    H3

# example
# Hello World //It will be printed with size of H1
```
### Categories and Tags

```yaml
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     # TAG names should always be lowercase
```
Categories are designed to contain up to 2 elements. There can be 0 ~ infinite number of tags.
For example, this page's categories is 
```yaml
categories: [Projects, Github Page]
tags: [github,page,jekyll,chirpy,daehwan,kim,david]     # TAG names should always be lowercase
```

### Image
We should set width and heigh of an image.
```Markdown
![Desktop View](/assets/img/sample/mockup.png){: w="700" h="400" }
```

### Position of Image
By default, the image is centered, but it could be set to 'normal', 'left', and 'right'.
```Markdown
![Desktop View](/assets/img/sample/mockup.png){: .left }
```

### Image Path
We can define image path to save some time in the YAML block of the post.
```yaml
---
img_path: /img/path/
---
```

### Inline Code
```Markdown
'inline code part'
```

### Filepath Highlight
```Markdown
`/path/to/a/file.extend`{: .filepath}
```

### Code Block
'```' can create code block
```C++
// ``` C++ (specify language)
std::cout << "Hello World!" << std::endl;
// ```
```

This is pretty much what I will be using for this github page. More information about how to post can be found here. https://chirpy.cotes.page/posts/write-a-new-post/
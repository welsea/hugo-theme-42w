## Hugo theme - 42w
Demo: https://blog.welsea.site/

This theme is based on [Building a hugo site and theme with Bootstrap](https://willschenk.com/articles/2018/building-a-hugo-site/).
[Hugo Easy Gallery](https://www.liwen.id.au/heg/)


### Features
- General features from Hugo: posts, tags, categories etc.
- Gallery: based on [Hugo Easy Gallery](https://www.liwen.id.au/heg/)
- Group pictures in posts.

#### Usage for Gallery
1. Create a folder at the same level with `posts`,and inside posts create the subforlders that contains pics and a `index.md`.
```
content  
│
└───photos
│   │
│   └───gallery1
|       |   index.md
│       │   img.jpg
│       │   img2.jpg
│       │   ...
│   
└───posts
    │   firs-post.md
    │   second-post.md
````
2. Add the shortcodes for gallery in `index.md`. More specific introduce see [Hugo Easy Gallery](https://www.liwen.id.au/heg/).
````
{{< gallery dir="photos/gallery1" />}} {{< load-photoswipe >}}
````

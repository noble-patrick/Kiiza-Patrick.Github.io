# Naringu

THE FUTURE OF MOBILE COMPUTING

The concept of a self-contained, connected and easily portable device has been with us since the dawn of science fiction. When analysts and bloggers look at the future of computing, mobile or otherwise, they often focus on hardware developments. Whether their enthusiasm is justified or not, people get excited about higher resolution screens, front facing cameras and dual-core processors. Researchers and analysts have predicted that by 2025 there will be six devices per human on the planet. If this is true, it  means that we would  expect to see 50 billion more connected devices over the next decade. So, while a proclamation that, “5G phones with 3D cameras will become the norm in 2 – 3 years,” is a prediction that may possibly come true, it is disingenuous to say it without also discussing the software that will emerge to facilitate the trend.

[![future of mobile technology](https://img.youtube.com/vi/FScddkTMlTc/0.jpg)](https://www.youtube.com/watch?v=FScddkTMlTc)


![Naringu](images/screenshot-1.png)
![Naringu](images/screenshot-2.png)
![Naringu](images/screenshot-3.png)
![Naringu](images/screenshot-4.png)

## Contents

- [Usage](#usage)
 - [Sidebar menu](#sidebar-menu)
  - [Themes](#themes)
  - [Reverse layout](#reverse-layout)
  - [Contact Form](#contact-form)
  - [Comments](#comments)
- [Development](#development)
  - [Author](#author)
  - [Contributors](#contributors)
- [License](#license)


## Usage

Just download and start the Jekyll server or fork this repo.

### Sidebar menu

Create a list of nav links in the sidebar by assigning each Jekyll page the correct layout in the page's [front-matter](http://jekyllrb.com/docs/frontmatter/).

```
---
layout: page
title: About
---
```

**Why require a specific layout?** Jekyll will return *all* pages, including the `atom.xml`, and with an alphabetical sort order. To ensure the first link is *Home*, we exclude the `index.html` page from this list by specifying the `page` 


### Reverse layout

Reverse the page orientation with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```
### Contact Form

Using formspree to enable contact form in static site.

Go a head `contact/index.html` just change the email in the code

```html
<form action="http://formspree.io/youremail@yourdomain.com" role="form" method="POST">
```

### Comments

Using [disqus](http://disqus.com/) to enable comments in static site.

Just edit variable `disqus` in `_config.yml` to your disqus link.

## Development

Naringu come with two branches :.

- `master` for active development. 
- `gh-pages` for preview of Naringu

### Author

**Rizky Ariestiyansyah**
- <https://github.com/ariestiyansyah>
- <https://twitter.com/ariestiyansyah>

### Contributors

**Gildásio Júnior** - *a.k.a. @gjuniioor*
- https://github.com/gjuniioor

## License

Open sourced under the [MIT license](LICENSE.md).

---
layout: post
read_time: true
show_date: true
title: "Creating Your Personal Homepage with GitHub Pages!"
date: 2023-10-23
img: posts/20231023/myHomepage.png
tags: [tutorial,github]
category: opinion
author: Miking(Jing Gong)
description: "By following these steps, you will have your own homepage hosted on GitHub Pages. This guide provides a simple and fast way to create a homepage, without the need to set up a local development environment."
---
> This is the First Blog Post on My Personal Blog Website!

To create your own homepage using GitHub Pages, follow these simple steps:

Step 1: Watch Tutorial(optional): Begin by watching this helpful tutorial on YouTube: [Link to Video](https://www.youtube.com/watch?v=o5g-lUuFgpg&t=611s).

Step 2: Create GitHub Account: Go to [GitHub](https://github.com/) and sign up for an account if you don't already have one.

![img](./assets/img/posts/20231023/signUp.png)

Step 3: Create a New Repository: Click the "+" icon to create a new repository.

![img](./assets/img/posts/20231023/create.png)

Step 4: Name your repository in the format `<username>.github.io`.

![img](./assets/img/posts/20231023/createRepo.png)

Step 5: Select a Template: Choose a template you like from [GitHub Pages Themes](https://pages.github.com/themes/).

![img](./assets/img/posts/20231023/theme.png)

Step 6: Clone the Theme Repository: Clone your selected theme repository into your newly created `<username>.github.io` repository.

![img](./assets/img/posts/20231023/edit.png)

Step 7: Edit the Configuration File: Open the `_config.yml` file and customize it according to your preferences.

```YAML
title: Jing Gong (龚敬)
logo: /assets/img/logo.jpg
description: An undergraduate at the School of Software Engineering, Sun Yat-sen University.
show_downloads: false
google_analytics:
theme: jekyll-theme-minimal
```

Step 8: Edit the Index File: Open the `index.md` file, keep the first three lines as they are, and add your self-introduction in Markdown format.

```Markdown
---
layout: default
---
# About me
...
```

Step 9: Publish Your Homepage: Once you're done editing, your homepage is ready to be published!

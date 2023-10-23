---
layout: post
read_time: true
show_date: true
title: "Creating Your Personal Homepage with GitHub Pages!"
date: 2023-10-23
img: posts/20231023/myHomepage.png
tags: [guidance,github]
category: opinion
author: Miking(Jing Gong)
description: "By following these steps, you will have your own homepage hosted on GitHub Pages. This guide provides a simple and fast way to create a homepage, without the need to set up a local development environment."
---
> This is the First Blog Post on My Personal Blog Website!

To create your own homepage using GitHub Pages, follow these simple steps:

1. Watch Tutorial(optional): Begin by watching this helpful tutorial on YouTube: [Link to Video](https://www.youtube.com/watch?v=o5g-lUuFgpg&t=611s).
2. Create GitHub Account: Go to [GitHub](https://github.com/) and sign up for an account if you don't already have one.

![img](https://zx0tlxjwmkv.feishu.cn/space/api/box/stream/download/asynccode/?code=MDgyZDk2MzlmODgyMjE3YzE2NjNhYzUyYWM5Y2RkYjNfdUZTb2ZDMnVjVlFwSUNYV1BJWmZIZ01uZ2RLUnBWYWJfVG9rZW46TU5IR2I5U3djb0tqMnd4MGdmbGNmT3IybldmXzE2OTgwNjgxNTU6MTY5ODA3MTc1NV9WNA)

3. Create a New Repository: Click the "+" icon to create a new repository.

![img](https://zx0tlxjwmkv.feishu.cn/space/api/box/stream/download/asynccode/?code=OTkyNzUzZjkzMGFkYTI1MTg2ZDdmNmM4MTI3N2U0MWFfaTNGZ0E1Sjd0Nk50VDRUbTJYdVN5ZldZRmZPbTdHUW1fVG9rZW46U3VPZWJ0NGw1b3doUDh4ZVMwamNXSkczblRiXzE2OTgwNjgxNTU6MTY5ODA3MTc1NV9WNA)

4. Name your repository in the format `<username>.github.io`.

![img](https://zx0tlxjwmkv.feishu.cn/space/api/box/stream/download/asynccode/?code=ZWQ5ZGFiZDcwODAwNjI3N2NlZDFjYmUzMjk2Njg5YTlfaklGV1RyOU1vMGljZWgybTBwVFB0VkZCUUdybXhJc3lfVG9rZW46RVBERGIxWlBOb2ZKV2p4SGlTeWN1UzBHbm1lXzE2OTgwNjgxNTU6MTY5ODA3MTc1NV9WNA)

5. Select a Template: Choose a template you like from [GitHub Pages Themes](https://pages.github.com/themes/).

![img](https://zx0tlxjwmkv.feishu.cn/space/api/box/stream/download/asynccode/?code=ZWZkMzQwM2YxZmE4ZGY5OTUxM2NiYzQwYzc1M2NhYTRfVjFjWXV1S0N4aVdEa2RUV21zOXlLbFZSbGtLWW1uT25fVG9rZW46Sm9xSGJDNERub2YyQXZ4Mk5uWmNwMERwbkdiXzE2OTgwNjgxNTU6MTY5ODA3MTc1NV9WNA)

6. Clone the Theme Repository: Clone your selected theme repository into your newly created `<username>.github.io` repository.

![img](https://zx0tlxjwmkv.feishu.cn/space/api/box/stream/download/asynccode/?code=YTNjZjY0NTc0NzIwMTJhMmE4YTc5NGYyNDI5YjI5YjBfWkRKaU1XWUlBSWtSeVRYVGRhZHNPVVlCRWRSVm84TmhfVG9rZW46TXFNbmJJYzZCbzhoSTd4aU8wVWNReXRObm9oXzE2OTgwNjgxNTU6MTY5ODA3MTc1NV9WNA)

7. Edit the Configuration File: Open the `_config.yml` file and customize it according to your preferences.

```YAML
title: Jing Gong (龚敬)
logo: /assets/img/logo.jpg
description: An undergraduate at the School of Software Engineering, Sun Yat-sen University.
show_downloads: false
google_analytics:
theme: jekyll-theme-minimal
```

8. Edit the Index File: Open the `index.md` file, keep the first three lines as they are, and add your self-introduction in Markdown format.

```Markdown
---
layout: default
---
# About me
...
```

9. Publish Your Homepage: Once you're done editing, your homepage is ready to be published!

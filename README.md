# SCL-progress website 
Site to organize the progress in the field of Sanskrit Computational Linguistics
![Publish Site](https://github.com/soulbliss/SCL-progress/workflows/Publish%20Site/badge.svg)

## Run the server locally

```
git clone --recurse-submodules https://github.com/soulbliss/SCL-progress.git
cd SCL-progress
hugo server


# if the theme is changed, run this at root of repo
git submodule update --remote --recursive
```



### Requirements

[Hugo Static site generator](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)



## [Content](https://github.com/soulbliss/SCL-progress/tree/master/content)



```
├── content
│   ├── blog
│   │   └── dummy-blog-article.md
│   ├── contact.md
│   ├── datasets.md
│   ├── events.md
│   ├── faq.md
│   ├── researchers.md
│   └── scltools.md

```

All the main content of the tabs like: Events, Researchers, Tools, Contact Page

resides in the **/content** folder.

If any changes are to be made, they can be edited and a edit request [Pull request] can be sent.

Once done, the changes will reflect in 3~4 minutes on the [main website.](https://sclprogress.com/)



## Contributing



- The project tasks are updated here: [Projects](<https://github.com/soulbliss/SCL-progress/projects>) 
- Corresponding inputs on tasks can be posted in the specific issues or new ones can be created [Issues](https://github.com/soulbliss/SCL-progress/issues).



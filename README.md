![Algorithms](https://socialify.git.ci/codeiiest-dev/algorithms/image?description=1&font=Raleway&forks=1&issues=1&language=1&owner=1&pattern=Charlie%20Brown&pulls=1&stargazers=1&theme=Dark)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

# About the Project

This repository contains some of the most  **intriguing and awesome algorithms**  of daily life implemented in languages primarily in C/C++/Java/Python.

## Project Details

The entire project is divided into 4 parts

-   Competitive Coding Algorithms and Data Structures
-   Security Algorithms
-   Machine Learning Algorithms
-   Statistical / Mathematical Algorithms

##  General

The summary file is used by mdBook to know what chapters to include, in what order they should appear, what their hierarchy is and where the source files are. Without this file, there is no book.

Even though  `SUMMARY.md`  is a markdown file, the formatting is very strict to allow for easy parsing. 
Let's look at how to edit `SUMMARY.md`.


```markdown
# Summary

- [Introduction](./introduction.md)
```
 Now you want to add a topic `Topic 1`. And it will have some subtopics `Sub-Topic1` and `Sub-Topic2`. 
 
```markdown
# Summary

- [Introduction](./introduction.md)
- [Topic 1](./relative/path/to/Topic-1.md)
  - [Sub Topic 1](./relative/path/to/sub-topic1.md)
  - [Sub Topic 2](./relative/path/to/sub-topic2.md)
```

It is advised to maintain the same folder structure for the markdown files as well. 
So the `Topic-1` folders will have a structure like:

```
src
├── introduction.md
├── SUMMARY.md
└── Topic-1
    ├── Sub-Topic-1
    │   ├── sub-topic-1.md
    │   └── sub-topic-2.md
    └── Topic-1.md
```

Also you need to follow proper markdown syntax for your contribution to be considered.  You can refer to this [guide](https://www.markdownguide.org/basic-syntax/).


# Contribution Guidelines

Please refer [here](./CONTRIBUTING.md) for our contributing guidelines.

# Contributors

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://arnabsen.netlify.app/"><img src="https://avatars1.githubusercontent.com/u/51032928?v=4" width="100px;" alt=""/><br /><sub><b>Arnab Sen</b></sub></a><br /><a href="#maintenance-arnabsen1729" title="Maintenance">🚧</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
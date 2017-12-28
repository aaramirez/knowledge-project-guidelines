# Knowledge Project Guidelines and Best Practices

[![StandardJS Style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![Collaborative Etiquete](https://img.shields.io/badge/%E2%9C%93-collaborative_etiquette-brightgreen.svg)](https://git.io/col)
[![Travis CI](https://img.shields.io/travis/knowledge/knowledge-project-guidelines.svg)](https://travis-ci.org/knowledge/knowledge-project-guidelines)

This is the source code of the site [knowledge.github.io/knowledge-project-guidelines](https://knowledge.github.io/knowledge-project-guidelines).

It's a set guidelines used at Knowledge projects such as [knowledgewallet.com](https://knowledgewallet.com).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [About Knowledge](#about-knowledge)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Features

- Markdown based pages
- Responsive Material UI Theme
- Powerful Search Box
- Docker based build script
- Automated Testing with Travis CI
- Automated Deployment with Travis CI

## Getting Started

This is website is based on [mkdocs](mkdocs.org) and uses the [mkdocs-material](https://squidfunk.github.io/mkdocs-material) theme.

The recommended local installation is using docker to get all dependencies out of the box in an isolated environment.

The official Docker image for Material comes with all dependencies pre-installed and ready-to-use with the latest version published on PyPI, packaged in a very small image. Pull it with:

`docker pull squidfunk/mkdocs-material`

The `mkdocs` executable is provided as an entrypoint, `serve` is the default command. Start the development server in your project root with:

```
docker run --rm -it -p 8000:8000 -v `pwd`:/docs squidfunk/mkdocs-material
```

For convenience there's a package.json with `npm start` command you can use. Just make sure have Docker installed and running and that you already pulled the docker image.

## Contributing

Read the [contributing guidelines](CONTRIBUTING.md) for details.

## License

MIT © [Knowledge](http://knowledge.io)  
See LICENSE for more info

---
## About Knowledge

Blockchain technology is rebuilding the internet in a trustless, decentralized way, allowing for fundamental core improvements on existing business models and industries, and a new breed of dot-io powerhouse frameworks are emerging. Knowledge.io is producing an ecosystem that offers significant improvement in the areas of ad tech, commerce, education, and employment, and a supply and demand marketplace of goods and services, all based around rewarding users for what the massive and centralized supergiants utilize to make extraordinary profits - people’s data. The Knowledge.io ecosystem is built on the foundation of decentralization and rewarding people for sharing their knowledge.

[knowledge.io](https://knowledge.io)  

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->

[![Knowledge Twitter][1.1]][1]
[![Knowledge Facebook][2.1]][2]
[![Knowledge Github][3.1]][3]

<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/tXSoThF.png (twitter icon with padding)
[2.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[3.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

<!-- icons without padding -->

[1.2]: http://i.imgur.com/wWzX9uB.png (twitter icon without padding)
[2.2]: http://i.imgur.com/fep1WsG.png (facebook icon without padding)
[3.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->

[1]: http://www.twitter.com/KnowledgeToken
[2]: http://www.facebook.com/KnowledgeToken
[3]: http://www.github.com/knowledge

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

# Tiramisu

Built using https://github.com/newtype256/React.nix 

## Motivation

There is a big bunch of Note taking app, but we still struggle to find one that:

- is a Free software
- support Markdown syntax
- not require a Google account to be used
- have a good native desktop / mobile devices support
- have a decent UX
- have simple/customizable synchronization parameters

To have a (non-exhaustive) list of existing apps:

- [About these notes](https://notes.andymatuschak.org/About_these_notes)
- [Tools | Markdown Guide](https://www.markdownguide.org/tools/)
- [Open source and self-hosted alternatives to Roam Research](https://nesslabs.com/roam-research-alternatives)

## UX Research

|Name          |Link                                     |Free? |Markdown? |No Google account? |Natives app? |Good UX? |Custom sync? |
|--------------|-----------------------------------------|------|----------|-------------------|-------------|---------|-------------|
|FocalBoard    |www.focalboard.com                       |✅     |❌         |❌                  |✅            |✅        |❌            |
|Zotero        |https://www.zotero.org                   |✅     |❌         |✅                  |❌            |❌        |❌            |
|Zettlr        |https://www.zettlr.com                   |✅     |✅         |✅                  |❌            |❌        |✅            |
|ArchiveBox    |https://archivebox.io                    |✅     |❌         |✅                  |❌            |❌        |✅            |
|Memex         |https://getmemex.com/                    |✅     |❌         |❌                  |❌            |❌        |❌            |
|LogSeq        |https://logseq.com                       |✅     |✅         |❌                  |❌            |❌        |❌            |
|nb            |https://xwmx.github.io/nb/               |✅     |✅         |❌                  |❌            |❌        |❌            |
|Standard Notes|https://standardnotes.org                |✅     |✅         |✅                  |❌            |✅        |❌            |
|mdBook        |https://rust-lang.github.io/mdBook/      |✅     |✅         |✅                  |❌            |❌        |❌            |
|Outline       |https://outline.com                      |✅     |✅         |✅                  |❌            |❌        |❌            |
|GitBook       |https://www.gitbook.com                  |❌     |✅         |❌                  |❌            |❌        |❌            |
|Notion        |https://www.notion.so                    |❌     |✅         |❌                  |❌            |❌        |❌            |
|Roam Research |https://roamresearch.com                 |❌     |✅         |❌                  |❌            |❌        |❌            |
|RemNote       |https://www.remnote.io                   |❌     |❌         |❌                  |❌            |❌        |❌            |
|Obsidian      |https://obsidian.md                      |❌     |✅         |❌                  |❌            |❌        |❌            |
|Zettelkasten  |https://zettelkasten.de                  |❌     |❌         |❌                  |❌            |❌        |❌            |
|nvALT         |https://brettterpstra.com/projects/nvalt/|❌     |❌         |❌                  |❌            |❌        |❌            |
|Charm.sh      |https://charm.sh                         |❌     |❌         |❌                  |❌            |❌        |❌            |


## UI Research

- [Public Sans](https://public-sans.digital.gov)
- [material-components/material-components-web-components](https://github.com/material-components/material-components-web-components)
- [Apple Design Resources](https://developer.apple.com/design/resources/)
- https://kartotekcopenhagen.com
- https://www.midori-japan.co.jp/md/en/
- http://m.trollspaper.com
- https://notem-studio.com
- https://poico.studio
- https://redopapers.com

---

## Dependencies

This project use:

- the library [rich-markdown-editor](https://github.com/outline/rich-markdown-editor) from the project [Outline](https://www.getoutline.com/)
- the library [styled-components](https://styled-components.com/)

### Roadmap

- Store data in a GraphQL DB (see if Apollo is needed [https://graphql.org/code/#javascript](https://graphql.org/code/#javascript))
    - [http://hood.ie](http://hood.ie)
    - [https://realm.io](https://realm.io)
    - [https://gun.eco](https://gun.eco)

- Handle code edition the right way
    [https://microsoft.github.io/monaco-editor/](https://microsoft.github.io/monaco-editor/) (the code editor that powers VSCode)

## Contributing

Pull requests are welcome.

For major changes, please open an issue first to discuss what you would like to change.

## Authors and acknowledgment

- [Yvan Sraka](https://github.com/yvan-sraka/)
- [Nicolas Hovart](https://github.com/NicolasHov)

## LICENSE

[GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](/LICENSE)

---

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000/) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# Note app based on your GitHub Gists

# 🗓️🗒️

Note app Notion | RoamResearch killer

Markdown mail app

Let’s commit be an note history

Search bar in Note App Filename = Tag ?

Share my Gist Profile

Lighthouse PWA React Native ?

Pocket API in Note App

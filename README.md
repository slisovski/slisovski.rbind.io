# slisovski.rbind.io website (2023)

This is the github repo of my personal research homepage.

Group members can edit the page (e.g., add their portfolio, publish blog posts or include publications).

## Initial setup

### Cloning the homepage repo

- Make a github account [here](https://github.com/).
- Ask me to be added as a collaborator to the repo.

The easiest way to clone the reposity is to use R Studio.
- Create new project
- Choose 'Version Control' and 'git' (you may need to install git first)
- Copy past the repo: https://github.com/slisovski/slisovski.rbind.io
- Choose you local folder

Install the `blockdown` package to be able to create a local version of the website:

```
blogdown::serve_site()
```

This will show the current version of the homepage in your Viewer panel (you can also view the homepage in your browser: http://localhost:4321).

### Folder organization 

Content that can be changed, improved and extended is structured in the `content` folder.

```
├── content
│   ├── _index.md
│   ├── admin
│   ├── authors
│   ├── post
│   ├── projects
│   ├── publication
│   └── tutorials
```

## Add yourself to the homepage

To add yourself to the homepage, you can copy one of the group member folders in `authors`, and:
- rename the folder `NameSurname`
- edit the `_index.md` file (minimal information needed is: title, role, organization. Feel free to add more).
- add a jpeg and replace the avatar.jpeg in the folder (name of the image needs to be `avatar.jpeg`)

## Add a project or a blog post

...

## Add a publication

...

## Update the homepage

In the **Git** panel you can now commit the changes (please use an informative Commit message), and pull to the `master` branche of the repository. The homepage will be updated automatically (after a couple of minutes).

Note: You need to setup a token to be able to pull and push to the GitHub repository.
The R package `gitcreds` can help to setup and register the token.

**Note:** Make sure to pull the latest version of the repo each time you want to make changes.
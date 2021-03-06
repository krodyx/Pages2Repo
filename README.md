# Pages2Repo

![Address Bar](screenshots/bar.png)

A simple chrome extension that checks the current tab if it is a GitHub pages link (username.github.io[/reponame]). If one is found it will query the GitHub API for info about the repository. You can then click the repository icon in the address bar for a popup with info about the repository as well as links to
- Owners profile (image)
- Repository page
- Stars
- Watchers
- Forks
- Issues
- SSH/HTTPS Clone url (clicking the button will copy to your clipboard (new versions of chrome only?))

![Popup](screenshots/popup.png)

## Install
Download from the [chrome webstore](https://chrome.google.com/webstore/detail/pages2repo/afnogakjnebbgcbjkgmhaccljfejeflh)

## Development
- Fork/Clone the repository
- Review [Chrome extension documentation](https://developer.chrome.com/extensions)
- Hack away
- Run `grunt` before making any pull requests to ensure style consistency

## Release
Uses [Grunt](http://gruntjs.com/) to minify code, bump version number, and create a zip

```shell
npm install
grunt build
```

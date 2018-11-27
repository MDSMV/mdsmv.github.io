# mdsmv.github.io
## Maldives Digital Society Live Website

As an open source project, you can fork our website code and please help us make the site better by forking it, adding new content or features, and submitting a pull request!

* https://help.github.com/articles/fork-a-repo/
* https://help.github.com/articles/creating-a-pull-request/

Note: This site is hosted with GitHub pages and, as such, any changes you make to the repository will immediately be reflected on our website.

## Updating Content

Most minor content updates can be made simply by making changes on your forked copy of this repository, then submitting a pull request. For example, following every meeting, the file _post/[date]-[event-details].[markdown] should always be added to reflect the date and meeting.

# Local Development
If you want to make significant changes to the site, it's recommended you do so on your local machine first so as to speed up the development process. Here's how to do that.

## Requirements
* Ruby 1.9.3 or later
* Bundler
* Git
* Text Editor
## Installation
### Clone the Repository
git clone https://github.com/MDSMV/mdsmv.github.io.git

### Install Dependencies
bundle

### Build the Pages
jekyll build

### Serve the Pages
jekyll serve --watch

## Hack Away

With jekyll serve --watch running, you should be able to access the site on http://localhost:4000! Thanks to the --watch flag, any changes you make to the markdown (md) files will update automatically!

For reference, here's an awesome Markdown & Jekyll cheatsheet.

* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* https://devhints.io/jekyll

Contribute, change things, submit a pull request! We will all contribute.


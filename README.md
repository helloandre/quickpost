#QuickPost

### A Helper for [Jekyll](https://github.com/mojombo/jekyll)

Creates a new markdown file in _posts with the proper formatting of date and url-safe filename. I wanted this because I hate typing with dashes.

## Install

 * `git clone git://github.com:helloandre/quickpost.git`
 * `cd quickpost`
 * `sudo rake install`

## Usage

 * cd into your jekyll root directory (where your _config.yml is/would be)
 * `quickpost <title>`

## Example

`quickpost "Hello, World" --date "1/1/2013"`

creates

_posts/2013-01-01-hello-world.md


## Help

 * see `quickpost --help` for more usage
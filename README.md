# jsonresume-theme-onepage-wide

A onepage variant with less margin on the left hand side. Can also be seen as a joeytall variant with some modifications, since joeytall is based on onepage. Based on the [onepage](https://github.com/ainsleyc/jsonresume-theme-onepage) theme, with modifications carried over from [joeytall's theme](https://www.npmjs.com/package/jsonresume-theme-joeytall).

## Running

```
sudo npm install -g resume-cli
git clone https://github.com/briankung/jsonresume-theme-onepage-wide.git
cd jsonresume-theme-onepage-wide
resume serve
```
You can print directly from the served html.

## Options

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See included resume.json for more details.


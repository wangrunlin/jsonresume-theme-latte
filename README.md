# Latte Theme! ☕️+🥛

Latte it's a [JSON Resume](https://jsonresume.org/) theme based on [Theme Boilerplate](https://github.com/jsonresume/jsonresume-theme-boilerplate), [Caffeine Theme](https://github.com/kelyvin/jsonresume-theme-caffeine) and [Macchiato Theme](https://github.com/biosan/jsonresume-theme-macchiato).

## Changes from Macchiato and Caffeine Theme

### Visual differences

- Chinese support
- Chinese fonts

## Usage

1. Download [JSON Resume CLI](https://jsonresume.org/)

```
npm install -g resume-cli
```

2. Download the theme from [npm](https://www.npmjs.com/)

```
npm install -g jsonresume-theme-latte
```

3. Use resume cli to build your resume

```
resume export resume.html --theme latte
```

### PDF output

JSONResume CLI should be able to make a PDF out of your JSON but I always struggled to get it to work,
so I switched to a more direct and effective approach.

Obviously you could write a very simple Node script to use the real Puppeteer and the `render` function to make a PDF without first exporting the HTML version.

Also checkout [HackMyResume](https://github.com/hacksalot/HackMyResume), a powerful tool to build and analyze your JSON Resume.

## LICENSE

Available under the [MIT license](LICENSE).

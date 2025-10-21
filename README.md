# Notices on Factor Graphs — Website

A very simple GitHub Pages site (Jekyll + Markdown) for an online colloquium on factor graphs.

# Editing content
The site will rebuild automatically when you push to the `main` branch using GitHub Actions. The Action will build the site (i.e. generate the `_site` directory) and deploy it to GitHub Pages. You can check the build status in the [Actions](https://github.com/Notices-On-Factor-Graphs/website/actions) tab.

## Preview locally
You can edit the site and commit to `main` to see your changes live on the website.

But if you want to preview your changes locally (before committing), you can run the following commands:

```bash
bundle install
bundle exec jekyll serve
```

You might want to search online or ask ChatGPT for help if you encounter any issues.

This will start a local server at `http://localhost:4000`. You can view your changes in your browser.


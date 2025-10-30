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


# How to send the newsletter email
To send the newsletter, use your TU/e outlook account. You get the current list of emails in this excel sheet (automatically updated from the signup/unsubscribe form):

tuenl-my.sharepoint.com/:x:/r/personal/f_o_v_d_plas_tue_nl/Documents/Notices%20on%20Factor%20Graphs%20newsletter%20RESULTS.xlsx?d=w414a09f99adf485a972d6c89098ee38d&csf=1&web=1&e=HF4l6l

(This link only works for Thijs, Raphaël and Fons.) Go the sheet **current email list**. Then:
1. Select the first column (click on the 'A' column header).
1. In outlook, write a new mail.
1. Click "BCC"
1. In the BCC field, paste the list.
1. In the email, include this footer:

```
To unsubscribe, go to: https://forms.office.com/e/dRHED5wb0W
```





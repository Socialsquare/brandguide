# brandguide
The communication styleguide of our lovely organisation

http://brandguide.socialsquare.dk/

## How to add or edit a page

All the pages in the brandguide can be found in the `pages` folder. They are written in `markdown` and thus allows for easy editing and previewing directly here on GitHub. Any `.md`-file created in the `pages` folder will automatically be added to the table of contents menu on the site provided that they contain the following syntax:
```
 ---
 layout: page
 title: 'your page title'
 date: 'YYYY-MM-DD HH:MM:SS' (optional)
 ---
```

After you added this to your file just start typing in markdown, and the previews you see on GitHub should then reflect what's shown on the website. If you can't get it to work try to check the other `.md`-files for syntax help. Otherwise just ask around the office.

If you've never written `markdown` before try [this](http://markdowntutorial.com/) tutorial.

### Hiding from side menu
If you for any reason want to hide a page from the table of contents just add `sidemenu: false` to the inital arguments.

# (Temporary) website for the TU Delft Digital Competence Centre

Code to generate website hosted at: https://dcc.tudelft.nl.

A github action is used to generate the gh-pages branch automatically on a push to the master branch.

Note: if you need to generate a new Gemfile.lock and you are working on a Windows platform, please check this issue: https://github.com/helaili/jekyll-action/issues/60

Note: if you have forked this repo and you would like to see the results of your changes including formatting at https://`<git_username>`.github.io/DCC-website/, you will need to change the _config.yml file.

```
< baseurl: "" # the subpath of your site, e.g. /blog/
< url: "https://dcc.tudelft.nl" # the base hostname & protocol for your site
---
> baseurl: "/DCC-website" # the subpath of your site, e.g. /blog/
> url: "https://`<git_username>`.github.io" # the base hostname & protocol for your site
```

Don't forget to change it back again before submitting a pull request.

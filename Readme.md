# Github Pages with Jekyll instructions:  
https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll

## Step 1 - Install Jekyll
In order to work with Jekyll on windows,
follow installation guide:
https://jekyllrb.com/docs/installation/windows/

Validate that Jekyll is installed by running in terminal:
```sh
jekyll -v
```
  
## Development
For deployment Github Pages are configured deploy from the branch: production  
and subfolder /docs in the repository.

Testing website locally, see [testing docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) 

By default local base url:
http://localhost:4000/website/

You can overwrite local base url to be: 
http://localhost:4000/
with:
bundle exec jekyll serve --baseurl=""

```sh
cd docs
bundle install
bundle exec jekyll serve
```

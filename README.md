# jekyll-forwarder-template

I seem to be writing a lot of 301 redirect github "websites". This is a generic template for that. 

You can see the template in action [here](), where I redirect from `nucosmo.club` to `cosmo.khoury.northeastern.edu`.

This is a simple wrapper that takes advantage of GitHub Pages, Jekyll, and [jekyll-redirect-from](https://github.com/jekyll/jekyll-redirect-from).

To get this HTTP redirect up and running, do the following:

1. Fork this repo. 
2. On the repo's github page, go to `Settings > Github Pages` and enable on master
3. Add the URL you are redirecting **from**.
4. You'll need to configure DNS on your incoming domain to point to Github pages. More info [here](https://help.github.com/en/articles/quick-start-setting-up-a-custom-domain)
5. In `index.md` you'll need you to replace `<PLACE SITE REDIRECT HERE>` with the URL you're redirecting **to**.
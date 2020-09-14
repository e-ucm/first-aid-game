# Github page for First Aid Game with Hugo 

## Theme used : hugo-theme-learn 
https://themes.gohugo.io/hugo-theme-learn/

## Launch locally 
Hugo run a server with the "hugo server" command and watch for changes.

## Deploy Your Website 
After running hugo server for local web development, you need to do a final "hugo" run without the server part of the command to rebuild your site. You may then deploy your site by copying the public/ directory to your production web server.

Since Hugo generates a static website, your site can be hosted anywhere using any web server. See Hosting and Deployment for methods for hosting and automating deployments contributed by the Hugo community.

Running hugo does not remove generated files before building. This means that you should delete your public/ directory (or the publish directory you specified via flag or configuration file) before running the hugo command. If you do not remove these files, you run the risk of the wrong files (e.g., drafts or future posts) being left in the generated site.
Blog
====

Data Science at Scale Team Blog

# To create the page #

1. Install node.js and npm 
2. `npm install` from the Blog directory
3. To add a new post, add a markdown in *posts/* 
4. Reference the markdown in *posts.jade*
5. `make` to regenerate the static html
6. `git commit -a` and `git push origin gh-pages`


npm may require setting and unsetting the proxy when being used
in and out of a protected network.

   'npm config set proxy http://proxyout.lanl.gov:8080' and 
   'npm config set https-proxy http://proxyout.lanl.gov:8080'

   'npm config rm proxy'
   'npm config rm https-proxy'


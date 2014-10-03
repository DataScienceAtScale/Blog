Blog
====

[Data Science at Scale Team Blog](http://datascienceatscale.github.io/Blog/ "Data Science at Scale Team Blog")

# To create the page #

1. Install node.js and npm 
2. `npm install` from the Blog directory (*please don't commit these files*)
3. First, to add a new post, add a markdown in *posts/* 
4. Then with the +post() mixin, put it in *posts.jade*
5. `make` to regenerate the static html
6. `git commit` your files and `git push origin gh-pages`


### npm may require setting and unsetting the proxy when being used in and out of LANL network. ###

`npm config set proxy http://proxyout.lanl.gov:8080`  
`npm config set https-proxy http://proxyout.lanl.gov:8080`

`npm config rm proxy`  
`npm config rm https-proxy`

> npm also obeys `http_proxy` and `https_proxy` environment variables if the npm config is not set.

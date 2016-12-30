# Jekyll-Avalon
[Demo](http://joshuaavalon.github.io/Jekyll-Avalon)
![](https://raw.githubusercontent.com/joshuaavalon/Jekyll-Avalon/master/_screenshot/001.png)

## About
Jekyll-Avalon is a [Materialize](https://github.com/dogfalo/materialize) Jekyll theme.

Featuring:
* Material Design
* Responsive Web Design
* Tags and categories browsing
* Lazy loading images

## Installation
This theme **CANNOT** be built by GitHub. You have to build it yourself.
Please follows the following question.

1. Are you willing to do extra works other than just blogging?

 Yes > 3
 
 No > 2

2. Are you willing to other git service like GitLab?

 Yes > Upload this repository to GitLab. It will auto-deploy like GitHub. Make sure you have turn on the GitLab Runner.
 
 No > This theme is not for you.

3. Install Ruby if you don't have it. In you are using Windows, you may want to try [Ruby Installer](http://rubyinstaller.org/).

4. Install Jekyll and Bundler if you don't have it. Run the following commands in command prompt to install the packages.
 ```
 gem install jekyll bundler
 ```

5. cd to your repository directory. Run the following command in command prompt to build.
 ```
 bundle exec jekyll serve
 ```
6. Upload the content in `_site` to GitHub or your host.

## Config
Change everything you need in `_config.yml`. Change the footer in `_includes/footer.html`.

If you want to change the color, go [here](https://github.com/dogfalo/materialize) to download SASS version 
and replace the link in `_includes/head.html`.

For comment support, you can use [Disqus](https://disqus.com/) and add the embed code to `_layouts/post.html`.
Same for Google Analytics, add the embed code to `_includes/script.html`.

## Post
All the usable fields available are in `2016-10-27-welcome-to-jekyll.markdown`.

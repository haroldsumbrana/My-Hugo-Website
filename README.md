#Hi this is my somebasic steps in getting more hugo theme:

1. hugo new site (project name)
2. cd (project name)
3 vim config.toml = edit config.toml
4. go to themes.gohugo.io = select theme to use
5. in github directory copy the github link
6. git init and then git submodule add (githubUrl) themes/(theme name)
7. copy all theme directory content by typing into compiler
cd themes/(theme name)/* . -r
8. go to config.toml add into front matter add 
theme = "(theme name)"
9. go to your github repository and create a repository.
10. git remote add origin and paster your repository url.
11.  git status, git add --all, git commit -m "initial", git push -u origin master.

Deploying online:
12. type hugo in your compiler and copy
publishDir = "docs" paste it to config.toml front matter.
13 remove public directory
rm -r public
 push.

14.1 type hugo again in compiler.
14.2 git status git add --all git commit -m "rendered" and git

15. under settings Guthub Pages select master branch/docs folder.
and hit save and it will give url like this https://github.com/themefisher/timer-hugo copy the url and replace baseurl= "http:/example.org"  unto your config.toml. 

16. push changes again to your repositoty and refresh ti will take a while after the site is live and there you go.




 




------

Some other way

1. hugo new site (project name)
2. cd (project name)
3 vim config.toml = edit config.toml
4. go to themes.gohugo.io = select theme to use
5. in github directory copy the github link
6. git init and then git submodule add (githubUrl) themes/(theme name)
7. copy all theme directory content by typing into compiler
cd themes/(theme name)/exampleSite/* . -r
8. go to config.toml add into front matter add
themesDir = "themes"
theme = "(theme name)"
9. go to your github repository and create a repository.
10. git remote add origin and paster your repository url.
11.  git status, git add --all, git commit -m "initial", git push -u origin master.

Deploying online:
12. type hugo in your compiler and copy
publishDir = "docs" paste it to config.toml front matter.
13 remove public directory
rm -r public
 push.

14.1 type hugo again in compiler.
14.2 git status git add --all git commit -m "rendered" and git

15. under settings Guthub Pages select master branch/docs folder.
and hit save and it will give url like this https://github.com/themefisher/timer-hugo copy the url and replace baseurl= "http:/example.org"  unto your config.toml. 

16. push changes again to your repositoty and refresh ti will take a while after the site is live and there you go.





## Biztrox - Business theme (Premium)
[![Biztrox hugo theme](https://user-images.githubusercontent.com/5304905/48638129-e8ffb200-e9f9-11e8-99a7-b081e27a1941.png)](https://themefisher.com/products/biztrox-hugo-template/)

[Live Preview](http://demo.themefisher.com/themefisher/biztrox-hugo/)

[Download Now](https://themefisher.com/products/biztrox-hugo-template/)


# _Timer_ for Hugo
![screenshot](https://user-images.githubusercontent.com/16266381/42732703-d21e8e30-8847-11e8-9e2f-b648e2812901.jpg "Home of the website")

Timer is bootstrap based HTML5 responsive multipage agency template built using HTML5/CSS3 features and suitable for creative companies, agencies, and freelancers which need a professional way to showcase their projects, services, and sell their products. 

Timer has been designed and built with a ‘user first’ approach; Timer offers a beautifully elegant, simple and well-spaced template that follows the principles of design. This flexible template uses fresh and clean design and allows to change it looks to your liking in one click.

Timer Hugo is designed by Themefisher team and contributed by <a href="https://github.com/themefisher/timer-hugo/graphs/contributors" target="_blank">these Contributors</a> .

## Usage

Create a new Hugo site by typing

```
  $ hugo new site <SITENAME>
```

Then clone this repository:

```
  $ cd <SITENAME>/themes
  $ git clone https://github.com/themefisher/timer-hugo
```

Now take a look at the exampleSite folder and you're ready to go!

## License

This Template is released under [Creative Commons Attribution 3.0 (CC-BY-3.0) License](https://creativecommons.org/licenses/by/3.0/)
If you want to remove the credit simply make a [donation](https://www.paypal.me/Themefisher), so that we can run our contribution to hugo community.

[![HELP US TO GROW](https://user-images.githubusercontent.com/16266381/45262626-1e0ce880-b43c-11e8-9698-1b95f143e240.png)](https://www.paypal.me/Themefisher)

## About Themefisher

[Themefisher] has been creating beautiful free and premium Bootstrap and HTML5 templates since 2014.
Visit us at https://themefisher.com/ to see other great-looking themes.

[Hugo]: https://gohugo.io/
[Themefisher]: https://themefisher.com/

## We are available for Hiring of your next HUGO project. Drop Us a mail [themefisher@gmail.com](mailto:themefisher@gmail.com)

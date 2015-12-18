<<<<<<< HEAD
mediator
========

A medium inspired Jekyll blog theme. The basic idea came from the Ghost theme
[Readium 2.0](http://www.svenread.com/readium-ghost-theme/). I use mediator on my own blog [The Base](http://blog.base68.com).

Screenshots
--------
![screenshot](/assets/images/screenshot1.jpg)
![screenshot](/assets/images/screenshot2.jpg)
![screenshot](/assets/images/screenshot3.jpg)

Features
-------
* Fully Responsive layout
* Use header images in articles, if you want to (add tag "image" and url to the image in the front matter section of a post)
* Minimal design
* Featured article support
* FontAwesome implemented for easy use of icons fonts
* Free & Open Source Font usage

Getting Started
---
- [Fork this repository](https://github.com/dirkfabisch/mediator)
- Clone it: `git clone https://github.com/YOUR-USER/mediator`
- Install the requried gems ([GitHub Pages](https://github.com/github/pages-gem), [Bourbon](https://github.com/thoughtbot/bourbon) and [Jekyll](https://github.com/jekyll/jekyll)): `bundle install`
- Run the jekyll server: `bundle exec jekyll serve`

You should have a server up and running locally at <http://localhost:4000>.

Configuration
-----

The main settings happen in side of the _config.yml file:

### Site

Main settings for the site

* **title**: name of your site
* **description**: description of your site
* **logo**: small logo for the site (300x * 300x)
* **cover**: large background image on the index page

* **name**: name site owner
* **email**: mail address of the site owner
* **author**: author name
* **author_image**: small image of author (300x * 300px)
* **disqus**: add a disqus forum for your post

### Social

The template allows to add all major social plattforms to your site.
Fill the the form for each plattform. If you leave the share_* entries empty, the sharing buttons below a post are not shown.  If you leave the **url** and **desc** empty the icons are not shown on the index page, but the share icons on the article pages remains untouched (Thanks to [Phil](https://github.com/philsturgeon))

* **icon**:	name of social plattform (must match a name of [font-awsome](http://fortawesome.github.io/Font-Awesome/) icon set )
* **url**:	url of your account
* **desc**: slogan of the plattform
* **share_url**: share url
* **share_title**: first part of url for the title
* **share_link**: second part of the share url for the link to the post

The Liquid template engine will magical combine the different parts to a share url.

```
http://twitter.com/share?text=post_title&amp;url=post_url
````

See [_config.yml](https://github.com/dirkfabisch/mediator/blob/master/_config.yml) for more examples.

Licensing
---------

[MIT](https://github.com/dirkfabisch/mediator/blob/master/LICENCE) with no added caveats, so feel free to use this on your site without linking back to me or using a disclaimer or anything silly like that.

Contact
-------
I'd love to hear from you at [@dirkfabisch](https://twitter.com/dirkfabisch). Feel free to open issues if you run into trouble or have suggestions. Pull Requests always welcome.
=======
# Jekyll-Bootstrap-3

Easily publish Bootstrap 3 powered Jekyll sites.  
Fork of the well known jekyll-bootstrap (v0.3.0). Original project is [here](https://github.com/plusjade/jekyll-bootstrap).  
The quickest way to start and publish your Jekyll powered blog. 100% compatible with GitHub pages.  

## Usage

### 1. Create a Repo
- Go to <https://github.com> and create a new repository named *USERNAME.github.io*  

### 2. Install Jekyll-Bootstrap-3  
<pre>
  <code>
    $ git clone https://github.com/dbtek/jekyll-bootstrap-3 USERNAME.github.io
    $ cd USERNAME.github.com
    $ git remote set-url origin git@github.com:USERNAME/USERNAME.github.io.git
    $ git push origin master  
  </code>
</pre>  
### 3. Enjoy !
- After giving 10 mins to GitHub of course.  

For original project's usage and documentation please see: <http://jekyllbootstrap.com>  


### Themes

Quickly install and use lovely themes with Jekyll Bootstrap 3. Visit [theme gallery](http://jekyllbootstrap3.tk/preview/).

## License

[MIT](http://opensource.org/licenses/MIT)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/dbtek/jekyll-bootstrap-3/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

>>>>>>> 403be1ee96846c8ae27be7bcdceab27eda967e60

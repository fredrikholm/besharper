# BeSharper
__B# - The Superfluous Blogging Platform__

Wat!? To create a new blogging platform in the year 2017 is roughly comparable to adding another index to your gut, so what is this all about?

Well, I used to kind of like Umbraco with Articulate. It wasn't perfect, but it got the job done. And I've never really got along with Wordpress. So when the time came to re-boot my blog I made a small list of requirements:

* Styling and appearence should be as easy to edit as content (read template HTML and LESS/SASS)

* The platform should support all my blog post meta data needs (Meta tags, Open Graph tags etc) 

* Synching everything between my local environment and production should be a no-brainer

* The blog post editor should basically provide the same possibilities as an IDE, with the possibility to use custom scripts, styles and reusable building blocks

* The publishing engine should support both drafts and scheduled publishing

* URLs should be readable, and alternative taxonomies should be supported (e.g. `/period/2016/12` for all posts from December 2016)

* Everything should be version controlled

&nbsp;

So, with these requirements in mind, I realized that my best option would be to stop looking for that fancy CMS or blogging platform, and simply resort the bare essentials. Yep, you got it - just the good, old, and trusted ASP.NET MVC paired with the best editor in the world - Visual Studio. :-)

With that sorted, it comes to no surprise that this platform isn't for everyone. To even consider it, you should be able to tick all these:

* You are fluent in HTML and LESS/SASS/CSS

* You know your way around JavaScript, Gulp, and npm

* You love C#, ASP.NET MVC, Razor and Visual Studio

* You are comfortable with Git

* You think writing your content in Razor is a benefit, not pure evil

* You host your blog on a server that allows you to utilize MS Deploy for pushing changes


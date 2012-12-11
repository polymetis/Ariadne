#Ariadne - A framework for Codekit

This is designed to be combiation of both [twitter bootstrap](http://twitter.github.com/bootstrap/) and [bourbon](http://bourbon.io). 

Why when you can easily use both. Twitter bootstrap is great but is designed to be used with a lot of extra classes floating about our markup -- I am aware that you can easily avoid this but I am talking common usage. This is designed more as a mixin library for common values to keep our class names clean and is built on the philosophy if you write some specific code more than once it belongs in a framework while keeping our output css clean. 

If you want to contribute then that is great submit a pull request and I will look at it. (It is quite likely that I will accept it if you follow graceful downgrade principle and work towards modern markup[Buzzwords include HTML5 and CSS3]) 

##Kit Files

Also there is not [html5 boilerplate](http://html5boilerplate.com) header and footer files for you to import 

Just set the following variables at the top of your file. 


<!--$title--> for the title to the site
<!--$description--> for the meta description
<!--$style--> where your stylesheet will end up
<!--$modernizr--> where you put modernizr
<!--$jQuery--> where the local jQuery is 
<!--$plugins--> Your plugin file
<!--$scripts--> Your scripts file 
<!--$googleanalytics--> Your google analytics id


And an <!--import html5-boiler-header.kit--> and a <!--import html5-boiler-footer.kit--> around your content and your done with that stuff. 
 

---
title:  "And We Have Theme!"
date:   2023-03-05 19:38:25 -0800
categories: jekyll themes
---
I admit, I struggled with theming at first.  From the README documents for each of the Github Pages themes, I concluded that all I needed were the following lines in my `_config.yml` file:

{% highlight yaml %}
# custom theme
remote_theme: pages-themes/slate@v0.2.0
plugins:
  - jekyll-remote-theme

{% endhighlight %}

I tried this with different themes.  It didn't give me theme styling locally, and the same after pushing it to the Github Pages publication branch.  It built fine, but the styling was not present.  

So, I read deeper into the documentation. There is a section on customizing the stylesheets.  I didn't think I needed to 'customize' the stylesheet. All I wanted was to use the identical theme stylesheet, for very theme requested in the `_config.yml` file. But, maybe the documentation is saying that I need to add custom css to import the theme stylesheet anyway.

To import a custom stylesheet, I had to create a new file, `assets/css/style.scss`.
Like this:
{% highlight scss %}
---
---

@import "{{ site.theme }}";

{% endhighlight %}

After attempting this a few times, and it still did not give me the theme styling, I tried removing the first lines so there was just the import statement:
{% highlight scss %}
@import "{{ site.theme }}";
{% endhighlight %}

SUCCESS! It turns out, at least in my case, that this is true:
Any theme that is not the default `minima` theme is a custom theme.  And the first dashed lines do not allow the jekyll theme to render styling.

[Here's the documentation highlight for the Slate theme: https://github.com/pages-themes/slate](https://github.com/pages-themes/slate#:~:text=Configuration%20variables-,Stylesheet,-Layouts)

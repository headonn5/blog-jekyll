
# Introduction:
Jekyll is an engine that is used to generate static websites, such as a static blog, portfolio, etc.

Did you know GitHub Pages is developed using Jekyll. Therefore, it becomes the natural choice for most of the developers to power their github pages using Jekyll-built blogs/pages.

# Set Up:
It is written in ruby, so it can be easily installed in the system as a ruby gem  
`gem install jekyll`

However, to manage dependencies, we also install bundler using  
`gem install bundler`

---
NOTE: The above two commands can be combined using `gem install bundler jekyll`.

# Running the Server:
Jekyll server can be run as simple as `jekyll serve`. However, if you have multiple versions of jekyll in your system, it is advisable to use `bundle exec jekyll serve`. This will ensure that specific version of jekyll from the gemfile of your project is being served on the host.

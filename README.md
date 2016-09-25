# resume-jekyll

I'm trying out Jekyll's templating as a resume-building solution.

At the moment, a simple `jekyll build` or `jekyll serve` will render the basic resume like any Jekyll site should.

I do intend to play with cascading configurations as a way to tweak different versions of my resume while still keeping the main parts in one place.  My first steps towards playing with this concept are shown by these commands:

Render with a light blue background:
```
jekyll serve --config _config.yml,_config/blue.yml
```

Render with a light red background:
```
jekyll serve --config _config.yml,_config/red.yml
```
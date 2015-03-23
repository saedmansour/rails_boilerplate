## Rails boilerplate optimized for: rails 4.2, heroku, psql, bootstrap, no coffee script, bootstrap overrides variables, config file _base.rb, foreman: procfile + .env file. Gems: rails_admin, bower, better_errors, rspec ...

---

### How was the initial project created?

```
rails new app_name --database=postgresql
rake db:create
rake db:migrate
rails generate rspec:install
```

* Please create a .env file for each instance of the project.
* Create a Procfile for Foreman.
* [guide for above](https://devcenter.heroku.com/articles/procfile)


### Conventions

* Code: We follow the [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide)
* Git: [GitFlow](http://nvie.com/posts/a-successful-git-branching-model/)


### Sublime 2: Recommended Packages

* [Sublime Text 2/3 Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview)

### Bash Recommendations

```
subl ~/.bashrc
alias cd_app_name="cd ~/dev/app_name" #change to your path
```

### Testing: Rspec

```
bundle exec rspec
```

### Git: ignore

Procfile and .env should be ignored in your Git file but were included just for the sake of remembering them.

### Project links

* [Mockup](https://moqups.com/saed.mn@gmail.com/l2VUmVHj)

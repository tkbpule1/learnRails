```ruby
$ rails new blog
```
**This will create a Rails application called Blog in a blog directory and install the gem dependencies that are already mentioned in Gemfile using bundle install.**

**You can see all of the command line options that the Rails application builder accepts by running rails new -h.**

**Open new terminal, go to the blog directory and start the server**
```rb
$ rails server
```

**Generate Welcome Controller with Index Action**
```rb
$ rails generate controller welcome index
    create  app/controllers/welcome_controller.rb
    route  get 'welcome/index'
    invoke  erb
    create    app/views/welcome
    create    app/views/welcome/index.html.erb
    invoke  test_unit
    create    test/controllers/welcome_controller_test.rb
    invoke  helper
    create    app/helpers/welcome_helper.rb
    invoke  assets
    invoke    coffee
    create      app/assets/javascripts/welcome.js.coffee
    invoke    scss
    create      app/assets/stylesheets/welcome.css.scss
```


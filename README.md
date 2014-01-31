# Alfa Jango Rails App Template

## Clone this template and use

```
git clone git://github.com/alfajango/rails-template.git
cd rails-template
bundle install
cd ..
rails new my_app -m rails-template/template.rb
```

If you don't use RVM, instead of `bundle install` above, run
`bundle install --without rvm`.

## Use this template through the interwebs

Or, if you just want to use the template without cloning it locally:

```
gem install rails
rails new my_app -m https://raw.github.com/alfajango/rails-template/master/template.rb
```

## Interactive

The above commands will run the Alfa Jango new Rails app template with
the default preferences configured in template_defaults.yml. To run the
template interactively, instead use the template_interactive.rb file in
the above commands.

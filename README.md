# Alfa Jango Rails App Template

To clone this template and use:

```
git clone git://github.com/alfajango/rails-template.git
cd rails-template
bundle install
rails new my_app -m template.rb
```

If you don't use RVM, instead of `bundle install` above, run
`bundle install --without rvm`.

After the new app is generated, you may want to move it to a new
directory, so it's not in the cloned rails-template directory:

```
mv my_app ../some_other_directory
```

Or, if you just want to use the template without cloning it locally:

```
gem install rails
rails new my_app -m https://raw.github.com/alfajango/rails-template/master/template.rb
```

## RVM

There is [currently an issue](https://github.com/RailsApps/rails_apps_composer/issues/170)
trying to generate an app-specific RVM gemset and .rvmrc file
with the template. If you want to use an app-sepcific RVM gemset,
it's advised to create the gemset ahead of time and then install rails
and generate the app from the template while already using that gemset.

```
rvm gemset use my_app
gem install rails
rails new my_app -m https://raw.github.com/alfajango/rails-template/master/template.rb
```

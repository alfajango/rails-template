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

After the new app is generated, you may want to move it to a new
directory, so it's not in the cloned rails-template directory:

```
mv my_app ../some_other_directory
```

## Use this template through the interwebs

Or, if you just want to use the template without cloning it locally:

```
gem install rails
rails new my_app -m https://raw.github.com/alfajango/rails-template/master/template.rb
```

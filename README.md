# NRCan Jekyll Test

##To compile this locall witll reuire ruby and the checkout of the site
 - [Ruby Installers](https://rubyinstaller.org/downloads/)
 - [Jekyll Get started guide](https://jekyllrb.com/docs/)
 - [Jekyll Commandline references](https://jekyllrb.com/docs/usage/)


##Compile the site for local testing

    ```
    gem install jekyll bundler
    cd jekyll_site
    bundle exec jekyll serve
    # If you need to override the baseurl do it in _env.yml and use this command to include it
    bundle exec jekyll serve -c _config.yml,_env.yml --watch --livereload
    ```
    and browse to http://localhost:4000


# RailsAppTemplate

Rails Application Template for quick initialization with automated testing tools, model serializers & annotation and Bootstrap UI.

# Replace this with your README file

    $ git clone git@github.com:hanmd82/RailsAppTemplate.git
    $ mv RailsAppTemplate $RAILS_APP_NAME
    $ rails new $RAILS_APP_NAME  --skip-test-unit --database=$YOUR_DATABASE_TYPE

    ### clone and reset the application template
        create      README.rdoc

        conflict    Rakefile
        Overwrite   $RAILS_APP_NAME/Rakefile? (enter "h" for help) [Ynaqdh] Y
        force       Rakefile

        conflict    .gitignore
        Overwrite   $RAILS_APP_NAME/.gitignore? (enter "h" for help) [Ynaqdh] N
        skip        .gitignore

        conflict    Gemfile
        Overwrite   $RAILS_APP_NAME/Gemfile? (enter "h" for help) [Ynaqdh] N
        skip        Gemfile

        conflict    app/views/layouts/application.html.erb
        Overwrite   $RAILS_APP_NAME/app/views/layouts/application.html.erb? (enter "h" for help) [Ynaqdh] Y
        force       app/views/layouts/application.html.erb

        conflict    config/routes.rb
        Overwrite   $RAILS_APP_NAME/config/routes.rb? (enter "h" for help) [Ynaqdh] Y
        skip        config/routes.rb

        conflict    config/application.rb
        Overwrite   $RAILS_APP_NAME/config/application.rb? (enter "h" for help) [Ynaqdh] Y
        force       config/application.rb

        conflict    config/environment.rb
        Overwrite   $RAILS_APP_NAME/config/environment.rb? (enter "h" for help) [Ynaqdh] Y
        force       config/environment.rb

        conflict    config/environments/development.rb
        Overwrite   $RAILS_APP_NAME/config/environments/development.rb? (enter "h" for help) [Ynaqdh] Y
        force       config/environments/development.rb

        conflict    config/environments/production.rb
        Overwrite   $RAILS_APP_NAME/config/environments/production.rb? (enter "h" for help) [Ynaqdh] Y
        force       config/environments/production.rb

        conflict    config/environments/test.rb
        Overwrite   $RAILS_APP_NAME/config/environments/test.rb? (enter "h" for help) [Ynaqdh] Y
        force       config/environments/test.rb

        conflict    config/initializers/secret_token.rb
        Overwrite   $RAILS_APP_NAME/config/initializers/secret_token.rb? (enter "h" for help) [Ynaqdh] Y
        skip        config/initializers/secret_token.rb

        conflict    config/initializers/session_store.rb
        Overwrite   $RAILS_APP_NAME/config/initializers/session_store.rb? (enter "h" for help) [Ynaqdh] Y
        skip        config/initializers/session_store.rb

    ### set up source project
    $ cd $RAILS_APP_NAME
    $ rm README.rdoc
    $ cat secret_token.rb >> config/initializers/secret_token.rb   # followed by removing appropriate lines
    $ rm secret_token.rb
    $ bundle install
    $ bundle exec rake db:create

    ### set up Git repository
    $ rm -rf .git  # WARNING: will remove existing git repo
    $ git init
    $ git add ...
    $ git commit ...
    $ git add origin $NEW_GIT_REPO_URL
    $ git push -u origin master

And you're done!

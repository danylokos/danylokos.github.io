# Setup

1. `bundle config set --local path 'vendor/bundle'`
2. `Gemfile`:

    ```gem
    source 'https://rubygems.org'
    gem 'github-pages', group: :jekyll_plugins
    ```

3. `bundle install`
4. `_config.yml`:

    ```yml
    exclude:
        vendor/
    ```

5. `bundle exec jekyll serve`

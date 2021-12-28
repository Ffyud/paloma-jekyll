# paloma-jekyll

Paloma Jekyll is a utilitarian theme for publishing your articles.

To experiment with this theme as a standalone website, add some sample content and run `bundle exec jekyll serve`.

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "paloma-jekyll"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: paloma-jekyll
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install paloma-jekyll

## Usage

Using this theme is pretty straightforward. It consists of an index page and a docs page.

The docs page shows the articles that have been added to the `_post` folder. Take a look at the example markdown document to see that works.

`_config.yml` contains some configuration options that you should to change when you are using this theme as the basis for your Jekyll website.


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ffyud/paloma-jekyll. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `paloma-jekyll.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).


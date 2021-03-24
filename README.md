# Kontent Jekyll

[![Build](https://github.com/Kentico/kontent-jekyll/actions/workflows/build.yml/badge.svg)](https://github.com/Kentico/kontent-jekyll/actions/workflows/build.yml)
[![Version](https://img.shields.io/gem/v/kontent-jekyll.svg?style=flat)](https://rubygems.org/gems/kontent-jekyll)

[![Stack Overflow](https://img.shields.io/badge/Stack%20Overflow-ASK%20NOW-FE7A16.svg?logo=stackoverflow&logoColor=white)](https://stackoverflow.com/tags/kentico-kontent)
[![GitHub Discussions](https://img.shields.io/badge/GitHub-Discussions-FE7A16.svg?style=popout&logo=github)](https://github.com/Kentico/Home/discussions)

Kontent Jekyll is utilizing Kentico Kontent, headless CMS, as a content repository and integrates it with Jekyll static site generator. You can generate posts, pages, collections and data items.

## Examples

For a working example see [this project](https://github.com/Kentico/kontent-jekyll-blog).

## Installation

Add this to your gem's Jekyll plugins:

```ruby
source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'kontent-jekyll'
end
```

And then execute `bundle install`

## Usage

Run `bundle exec jekyll build` as you would normally build your Jekyll site.
You can also run `bundle exec jekyll serve` to run the built site.

## Configuration

To configure the extension, add the following configuration block to Jekyll's `_config.yml`:

For full configuration [see wiki](https://github.com/Kentico/kontent-jekyll/wiki).

```yaml
plugins:
- kontent-jekyll
kentico:
  project_id: 2dd742d6-107b-48b0-8335-6674c76c9b93
  posts:                                                      
    type: blog_post                                           
```

## Feedback & Contributing

Check out the [contributing](https://github.com/Kentico/kontent-jekyll/blob/master/CONTRIBUTING.md) page to see the best places to file issues, start discussions, and begin contributing.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Kontent-Jekyll project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/Kentico/kontent-jekyll/blob/master/CODE_OF_CONDUCT.md).


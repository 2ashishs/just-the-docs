<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/pmarsceill/just-the-docs/actions?query=workflow%3A%22Master+branch+CI%22"><img src="https://github.com/pmarsceill/just-the-docs/workflows/Master%20branch%20CI/badge.svg" alt="Build status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">2ashishs/just-the-docs</h1>
    <p align="center">A modern, highly customizable, and responsive Jekyll theme for documentation with built-in search.<br>Easily hosted on GitHub Pages with few dependencies.</p>
    <p align="center"><strong><a href="https://pmarsceill.github.io/just-the-docs/">See it in action!</a></strong></p>
    <br>
</p>

## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "jekyll-remote-theme"
gem "rake"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
plugins:
  - jekyll-remote-theme

remote-theme: 2ashishs/just-the-docs
```

And then execute:

    $ bundle install

## Usage

[View the documentation](https://pmarsceill.github.io/just-the-docs/) for usage information.

## Development

Your theme is set up just like a normal Jekyll site! To test your theme, run

    bundle exec jekyll serve --livereload --host <host-ip>

and open your browser at `http://<host-ip>:4000`. This starts a Jekyll server using your theme.

Add pages, documents, data, etc. like normal to test your theme's contents.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

# jekyll-theme-strata

jekyll-theme-strata is a Jekyll theme based on the [Strata HTML5 UP](https://html5up.net/).

See [example site](https://mloberg.github.io/strata-jekyll-theme/).

![minima theme preview](/screenshot.png)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-strata"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-strata
```

And then execute:

    $ bundle

## Usage

Strata comes with the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag)
plugin preinstalled. It uses the `logo` attribute as the site's avatar. Otherwise
see [usage](https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md)
for more details on the SEO plugin.

### Changing Background

Changing the background can be done by adding the image you would like at the
`assets/images/bg.jpg` path. This image should be 1274px x 1274px.

### Social Icons

You can add links to your social accounts by adding one or more of the
following options to your config.

```yaml
twitter_username: ~
github_username:  ~
dribbble_username: ~
facebook_username: ~
flickr_username: ~
instagram_username: ~
linkedin_username: ~
pinterest_username: ~
youtube_username: ~
googleplus_username: ~
rss: true # false to hide rss icon
```

### Enabling comments (via Disqus)

If you use Disqus for comments on your Jekyll blog, you can enable this with
the following configuration:

```yaml
disqus:
  shortname: my_disqus_shortname
```

Comments are only enabled in production builds (`JEKYLL_ENV=production`).

You can disable comments on a specific post by adding `comments: false` to the
post's front matter.

### Enabling Google Analytics

To enable Google Analytics, add this configuration:

```yaml
google_analytics: UA-NNNNNNNN-N
```

Google Analytics are only enabled in production builds (`JEKYLL_ENV=production`).

### Enabling Excerpts on the Home Page

To display post excerpts on the home page, add the following configration:

```yaml
show_excerpts: true
```

### Change Post Date Format

You can specify the date format of posts with the following configuration:

```yaml
date_format: "%b %-d, %Y"
```

The format documentation can be [found online](http://shopify.github.io/liquid/filters/date/).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/mloberg/strata-jekyll-theme.
This project is intended to be a safe, welcoming space for collaboration, and
contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org)
code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

This theme is setup just like a normal Jekyll site! To test this theme, run
`bundle exec jekyll serve` and open your browser at `http://localhost:4000`.
This starts a Jekyll server using this theme and contents. As you make
modifications, your site will regenerate and you should see the changes in the
browser after a refresh.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Credits

This Jekyll theme is taken from [Strata by HTML5 UP](https://html5up.net/).
Additionally, a lot inspiration was taken from [Minima](https://github.com/jekyll/minima).

Original README from HTML5 UP:

```
Strata by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A simple, minimalist template that actually began life as an unused redesign of my
personal site. Includes a (configurable) parallax background effect, Poptrox-powered
lightbox gallery, a bunch of pre-styled elements, and Sass sources for the Sass-inclined.

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = Not included)

Feedback, bug reports, and comments are not only welcome, but strongly encouraged :)

AJ
aj@lkn.io | @ajlkn

PS: Not sure how to get that contact form working? Give formspree.io a try (it's awesome).


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Responsive Tools (github.com/ajlkn/responsive-tools)
```

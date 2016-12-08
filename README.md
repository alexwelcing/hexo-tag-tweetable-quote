# hexo-tag-tweetable-quote for [Hexo](https://hexo.io)

Click to Tweet / Tweetable quotes for [Hexo](https://hexo.io)

# About

This is a [Hexo](https://hexo.io) tag plugin for including a tweetable quote into your pages/posts. Examples of what they can look like are below:



# Installation

The same as other Hexo plugins its simply:

```npm install --save hexo-tag-tweetable-quote```

In your Hexo project root.


# Usage

## Options
You can configure this plugin in `_config.yml`.

```yaml
tweetableQuote:
  quote_font_color : '#258fb8'
  quote_font_size  : '1.7em'
  link_font_color  : '#6e7b8d'
  link_font_size   : '1.0em'
```

- **quote_font_color** - Font color of quote. Defaults to `#258fb8`.
- **quote_font_size** - Font size of the quote. Defaults to `1.7em`.
- **link_font_color** - Click to tweet link font color. Defaults to `#6e7b8d`.
- **link_font_size** - Click to tweet link font size. Defaults to `1.0em`.

The full tag format is as follows:

```
{% tweetableQuote 'quote' 'author' %}
```


# Example in the Wild

I normally add Tweetable quote to my blog posts.

You can check one of them at [Chathu's Visionaries](http://chathu.me/about/)

## Tested themes

* [landscape](https://github.com/hexojs/hexo-theme-landscape)

* [icarus](https://github.com/ppoffice/hexo-theme-icarus)

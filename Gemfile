source 'https://rubygems.org'

# Ruby 4.0 moved these from *default* gems to *bundled* gems. Bundled gems ship
# with Ruby but are no longer auto-available inside a Bundler-managed project,
# so anything in the dependency tree that requires them needs an explicit entry
# here. Required by (among others):
#   ostruct   -> jekyll-twitter-plugin, safe_yaml, eventmachine, json
#   benchmark -> jekyll-minifier, bibtex-ruby, mini_mime, http_parser.rb
gem 'benchmark'
gem 'ostruct'

group :jekyll_plugins do
    gem 'classifier-reborn'
    gem 'jekyll'
    gem 'jekyll-archives'
    gem 'jekyll-diagrams'
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-get-json'
    gem 'jekyll-imagemagick'
    gem 'jekyll-jupyter-notebook'
    gem 'jekyll-link-attributes'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-toc'
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    gem 'mini_racer'
    gem 'unicode_utils'
    gem 'webrick'
end
group :other_plugins do
    gem 'feedjira'
    gem 'httparty'
end

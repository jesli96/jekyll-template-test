source 'https://rubygems.org'
gem "bundler"
#gem "jekyll", "~> 4.2"
gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
    gem "jekyll-paginate"
    gem "jekyll-sitemap"
    gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
    gem "webrick", "~> 1.8"
    gem "kramdown-parser-gfm"
    gem 'faraday-retry', '~> 2.2'
end
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
end

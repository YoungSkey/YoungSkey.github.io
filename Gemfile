source "https://rubygems.org"

# 使用新版 Jekyll 4
gem "jekyll", "~> 4.3.3"

# 解决 Sass 兼容性问题的核心
gem "sass-embedded", "~> 1.69.5"

# 解决 Faraday v2.0+ 的警告
gem "faraday-retry"

# Academic Pages 需要的插件
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-relative-links"
  gem "jekyll-optional-front-matter"
  gem "jekyll-readme-index"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
  gem "jekyll-redirect-from"
  gem "jemoji"  # <--- 就是这里！补上这个插件
end

# Windows 和 JRuby 兼容性支持
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

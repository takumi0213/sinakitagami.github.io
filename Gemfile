source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# GitHub Pages に準拠した依存関係
gem "github-pages", "~> 232", group: :jekyll_plugins

# Windows / JRuby 対策
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Windows 用ファイル監視
gem 'wdm' if Gem.win_platform?

# デバッグ用
gem "bigdecimal"
gem "faraday-retry"
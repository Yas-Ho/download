# Build local uniquement : GitHub Pages ignore ce fichier et utilise ses propres versions.
# Le gem github-pages reproduit exactement ces versions (Jekyll 3.10 et plugins autorisés).
#   bundle install
#   bundle exec jekyll build      → _site/
#   bundle exec jekyll serve      → http://localhost:4000
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "webrick"                                              # requis par « jekyll serve » avec Ruby 3+
gem "tzinfo-data", platforms: [:mingw, :x64_mingw, :mswin] # fuseaux horaires sous Windows

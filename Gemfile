source "https://rubygems.org"

gem "zapr"

# Install vendored projects gems
Dir.glob(File.join(File.dirname(__FILE__), 'vendor', '**', "Gemfile")) do |gemfile|
  eval(IO.read(gemfile), binding)
end

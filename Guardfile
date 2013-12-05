guard 'sass', :input => 'sass', :output => 'css', :smart_partials => true, :style => :compressed

guard 'livereload' do
  watch(%r{app/views/.+\.(erb|haml|slim)$})
  watch(%r{public/scripts/js/.+\.(css|js|html)})
  watch(%r{public/styles/css/.+\.(css|js|html)})
  watch(%r{public/specs/js/.+\.(css|js|html)})
  # Rails Assets Pipeline
  watch(%r{(app|public)(\w+/(.+\.(css|js|html))).*}) { |m| "#{m[3]}" }
end
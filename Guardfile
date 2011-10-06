# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'haml', :output => 'public', :input => 'app/views' do
  watch 'app/views/index.html.haml'
end

guard 'compass', :notification => true do
  watch(/^app\/stylesheets\/(.*)\.s[ac]ss/)
end

guard 'livereload', :apply_js_live => false do
  watch(%r{(public/).+\.(css|js|html)})
end

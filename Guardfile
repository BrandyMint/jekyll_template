# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'livereload' do
  watch(%r{.\w+/(.+\.(css|scss|sass|js|cofee|html|haml)).*})
end

guard 'coffeescript', :input => 'js', :all_on_start => true

guard :concat, :type => "js", :files =>  %w(ratchet jquery.mobile.custom.min), :input_dir => "js", :output => "application"

#guard :concat, type: "css", files: %w(), input_dir: "public/css", output: "public/css/all"

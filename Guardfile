# A sample Guardfile
# More info at https://github.com/guard/guard#readme

haml_options = { format: :html5, attr_wrapper: '"', ugly: true }

guard "haml", input: "haml", output: "www", notifications: true do
  watch(/^.+(\.html\.haml)$/)
end

guard "sass", input: "sass", output: "www/stylesheets"

guard "coffeescript", input: "coffeescripts", output: "www/javascripts", bare: true

# Sample guardfile block for Guard::Haml
# You can use some options to change guard-haml configuration
# output: 'public'                   set output directory for compiled files
# input: 'src'                       set input directory with haml files
# run_at_start: true                 compile files when guard starts
# notifications: true                send notifictions to Growl/libnotify/Notifu
# haml_options: { ugly: true }    pass options to the Haml engine

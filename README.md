
##Install Gem
In the terminal, install the Guard gem:

    $ gem install guard

Install a Plugin

Then install the guard-shell gem:

    $ gem install guard-shell

   $ gem install guard-shell



    guard :shell do
	  watch(//) do |modified_files|
			    puts "Modified files: #{modified_files}"
					    `ruby #{modified_files[0]} && echo  "\e[1;31m ......................................................... \e[0m"`
				  end
    end

Make Guardfile (above)

    $ gem install guard-shell



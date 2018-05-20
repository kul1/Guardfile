guard :shell do
	  watch(//) do |modified_files|
			    puts "Modified files: #{modified_files}"
					    `ruby #{modified_files[0]} && echo  "\e[1;31m ......................................................... \e[0m"`
				  end
end

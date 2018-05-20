Simple Guardfile for ruby
Basic Setup
Here are the basic steps to get started with Guard.

Install Gem
In the terminal, install the Guard gem:

$ gem install guard
Install a Plugin
Then install the guard-shell gem:

$ gem install guard-shell
This gem is a plugin for Guard. The reason why we add this plugin is that Guard is constructed such that it needs at least one plugin.

guard-shell in particular is a plugin that allows Guard to run Ruby or shell commands in response to file changes.

Make a Guardfile
Now we can generate a Guardfile. The Guardfile defines which files Guard will watch, and what it will do when one or more of these files change.

Run this command from your terminal:

$ guard init

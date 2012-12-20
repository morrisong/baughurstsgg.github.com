require 'jekyll'

options = Jekyll.configuration({})
site = Jekyll::Site.new(options)
site.read_posts('')

categories_dir = File.join(site.source, 'categories')

task :generate_categories

site.categories.keys.each do |category|
	dir = File.join(categories_dir, category) 
	directory dir 

	index_file = File.join(categories_dir, category, 'index.markdown') 

	file index_file => dir do | index |
		File.open(index.name,"w") do |f| 
		f.puts <<YAML_FRONT_MATTER
---
layout: category_index
comments: false
sharing: false
category: #{category}
---
YAML_FRONT_MATTER
		end
	end

	task :generate_categories => index_file
end

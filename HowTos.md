# fwimd

Notes:
- To create a new blogdown site

		new_site(
			theme = "theme_name",
			sample = TRUE,
			theme_example = TRUE,
			#some sites may not have theme_example
			empty_dirs = TRUE,
			to_yaml = TRUE
		)

For example

	new_site(theme = "gcushen/hugo-academic", 
	         sample = TRUE, 
	         theme_example = TRUE, 
	         empty_dirs = TRUE,
	         to_yaml = TRUE)

- To run the site

		blogdown::serve_site()

- To change the researchgate and webpage icon, modify

		themes/hugo-theme-even/layouts/partials/footer.html

- To create a new post

		blogdown::new_post(title = "Title for New post")

- To create a new post using RMarkdown

		blogdown::new_post(title = "Title for New post", ext=".Rmd")

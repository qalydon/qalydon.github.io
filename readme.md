## Jekyll Notes
### Overview
This is mostly notes and reminders for maintaining this GitHub web site.
The site is maintained as a regular GitHub repo with only a master branch.
When the master branch is pushed to GitHub, the site is automatically
updated.
### File and Directory Organization

	├── _config.yml*
	├── _includes/
	├── _layouts/
	├── _posts/
	├── _projects/
	├── _sass/
	├── _site/ <-- never pushed to GitHub
	├── about.md*
	├── css/
	├── feed.xml*
	├── github_projects.md*
	├── index.html*
	├── readme.md <-- this file
	└── static/

### Site Setup
[https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)

Install prequirements.

	gem install bundler
	bundle install

### Site Maintenance
Use your favorite editor like Textmate.

To run the site locally:

	bundle exec jekyll serve

### References
* [https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
* [Jekyll Home](https://jekyllrb.com/docs/home/)
* [Jekyll Basic Usage](http://jekyllrb.com/docs/usage/)
> :see_no_evil: This site is currently in beta.

## About This Project

This site will provide a home for policy and other materials developed by the Office of the Federal Chief Information Officer, which is part of the U.S. Office of Management and Budget, within the Executive Office of the President. It is built to conform to the [U.S. Web Design Standards](https://standards.usa.gov).

The intention is to consolidate a number of similar sites that currently exist on subdomains of cio.gov. Subdomains of cio.gov that _may_ be consolidated into this site over time include:

* playbook
* project-open-data
* management
* management2
* management-stage
* policy
* policies
* mobile
* mobile-policy
* cyberacquisitions
* datacenters
* software
* sourcecode
* project-open-source
* agile
* techfarhub
* itmf
* a130

Generally the purpose of these sites has been one of three things:
* to solicit public feedback on a draft policy
* to present a user friendly version of a finalized policy
* to provide implementation guidance and other materials related to a policy to help with implementation

The goal of this site will be to provide some support for each of those use cases in the context of a clear information architecture.


### Installation

The site is built using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"), a Ruby library for creating generating static sites. You will need Ruby to use this project.

[to do write installation guide]
  - Install ruby
  - Install Jekyll
  - Download the project from github (or fork it?)
  - To run the site locally, run `jekyll serve --watch`, then visit `http://localhost:4000/` in your browser to preview the site.

### Creating Content

1.	Create a new branch in GitHub
2.	Create a new folder to hold your content 
a.	Be sure to start the name of the folder with a underscore
i.	Example: _m-15-14-fitara 
3.	Create markdown files for each section of the memo in your  folder
a.	There is not a standard for organizing policy sections.  Generally speaking you should create a page for each major section or chapter of the policy 
4.	Convert the content of the policy to markdown and save it in the appropriate markdown file 
5.	Go to the _config.yml file 
6.	Under “resources-overview” create the following code structure.
```
[Policy Name]:

output: true

permalink: /[Policy-name-URL]/:path/

url: /[Policy-name-URL]/

status: draft

title: Policy Name

githublabel: Policy Name
``` 
7.	Commit your changes 
8.	Inform Matt Bailey or Thomas Romanoff that your branch is ready to be merged


### Configuration Options
[TO DO EXPLAIN WHAT CONFIGURATION OPTIONS NEED TO BE SET LIKE EMAIL AND GITHUB REPO AND GOOGLE ANALYTICS SNIPPIT]

## We Want Your Feedback
We encourage your feedback and suggestions on these documents.

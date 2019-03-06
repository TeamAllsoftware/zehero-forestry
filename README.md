---

Example [Jekyll] website using GitLab with [Netlify](https://www.netlify.com/).

---

## Netlify Configuration

In order to build this site with Netlify, simply log in or register at 
https://app.netlify.com/, then select "New site from Git" from the top
right. Select GitLab, authenticate if needed, and then select this
project from the list. Netlify will handle the rest.

In the meantime, you can take advantage of all the great GitLab features
like merge requests, issue tracking, epics, and everything else GitLab has
to offer.

## Using Jekyll locally

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
1. [Install][] Jekyll
1. Download dependencies: `bundle`
1. Build and preview: `bundle exec jekyll serve`
1. Add content

The above commands should be executed from the root directory of this project.

Read more at Jekyll's [documentation][].

## Did you fork this project?

If you forked this project for your own use, please go to your project's
**Settings** and remove the forking relationship, which won't be necessary
unless you want to contribute back to the upstream project.

## Troubleshooting

1. CSS is missing! That means two things:
    * Either that you have wrongly set up the CSS URL in your templates, or
    * your static generator has a configuration option that needs to be explicitly
    set in order to serve static assets under a relative URL.

[Jekyll]: http://jekyllrb.com/
[install]: https://jekyllrb.com/docs/installation/
[documentation]: https://jekyllrb.com/docs/home/

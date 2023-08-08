# ysdn.info

[ysdn.info](https://ysdn.info) is a minimalist website that aims to document the existance of the York/Sheridan Bachelor of Design program which started in 1999 and ended in 2022.  It also aims to re-enable access and act as an archive for the various grad show websites produced durring the program's lifespan.

ysdn.info is _not_ currently a webring or link directory for past graduates.

Archived gradshow websites are stored in a Backblaze B2 bucket.  We use [ReplayWebpage](https://github.com/webrecorder/replayweb.page) to embed them into the site.

## Contributing

Is your name not mentioned or misspelled? Do you have a list of names that isn't yet on the site? Do you have access to past gradshow website files? We'd love to hear from you! Please [open an issue and get in touch!](https://github.com/ysdn-info/ysdn.info/issues/new)

Other contributions also appreciated :)

## Building for Development

This website is built with [Jekyll](https://jekyllrb.com/), a static site generator that transforms the lists stored in the `_data/years` directory into lists of names on the site.  If you don't have Jekyll installed you can use `gem install bundler jekyll` to get it. Note that you may wish to use [rbenv](https://github.com/rbenv/rbenv) to manage your Ruby environment if you don't already.

To build the site 

1. Navigate to the project's working directory using `cd`

2. In the project working directory, install the required dependencies using `bundle install`

3. Run `bundle exec jekyll serve --livereload` to run the development server.

4. Navigate to [http://127.0.0.1:4000/](http://127.0.0.1:4000/) in your browser and get started!

### PSF Outreach Blog

#### How to

* pip install -r requirements.txt
* create posts in `/_posts` of master branch
* add images and other assets to to `/_assets` of master branch
* HTML and XML files in other locations will be rendered as jinja templates

Once ready to publish:
* Run `$ mynt gen _output`
* Run `$ ghp-import _output`
* Run `$ git push orign gh-pages`

New content should be push to site nearly immediately.

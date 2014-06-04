shimabo
=======


## What ##

Another awesome *shi*tty *ma*rkdown *b*l*o*g.

Tired of server side scripting? Just want to put a side up? Don't care about SEO? Can't remember the commands of your awesome static page renderer commands after two months? Then shimabo is for you!

No server side script language, no local compilation. Just upload the static files and you're done.

- markdown
- layout templates
- reusable snipplets
- no compilation
- slow (request all the things!)
- secure from any google indexing (aka can build self driving cars but index
  js pages … that's madness)
- backbone, markdown parser and under 250 lines of custom code

See this repo running on [github as gh-page][1] (there's also a branch for [neocities]) or [the Saito homepage][saito]. 

[1]: http://schlaefer.github.io/shimabo/
[neocities]: http://shimabo.neocities.org/
[saito]: http://saito.siezi.com/

## Files & Folders ##


### core ###

Don't touch that!


### elements ###

Reusable elements. Include with {{elementName}}.

You need a `html-head.tpl`. The content of this is added to the html head-tag.

### layouts ###

default.tpl is the default layout. Include content with a {{content}}.


### pages ###

Your markdown pages. Extension `md`. You need `index.md` for the homepage. A
page `mypage.md` has the url `#/mypage`.

Start with a little metadata header:

    layout: default
    title: Page Title
    ---

    your markdown

### config.json ###

Set some base parameters

* siteTitle: title of the site

### index.html ###

Don't touch that either.


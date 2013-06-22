shimabo
=======


## What ##

Another awesome shitty markdown blog.

No server side script language, no local compilation. Just upload the static files and you're done.

- markdown
- layout templates
- reusable snipplets
- no compilation
- slow
- secure from any google indexing (aka can build self driving cars but index
  js pages … that's madness)

See this repo running on [github as gh-page] or there's also a branch for [neocities].

[github as gh-page]: [http://schlaefer.github.com/shimabo/]
[neocities]: http://shimabo.neocities.org/

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


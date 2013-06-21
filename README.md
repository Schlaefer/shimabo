shimabo
=======


## What ##

Another awesome shitty markdown blog.

- markdown
- layout templates
- reusable snipplets
- no compilation
- slow
- secure from any google indexing (aka can build self driving cars but index
  js pages … that's madness)

See this repo "running": <http://schlaefer.github.com/shimabo/>

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


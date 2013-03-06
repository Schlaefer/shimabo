shimabo
=======

Another awesome shitty markdown blog.

- markdown
- layout templates
- reusable snipplets
- no compilation
- slow

folders
=======

## cores ##

Don't touch that!

## elements ##

Reusable elements. Include with {{elementName}}.

You need a `html-head.tpl`. The content of this is added to the html <head>
element. In it use `<title data-base="My awesome homepage"></title>` to set a
global page title.
  
## layouts ##

default.tpl is the default layout. Include content with a {{content}}.

## pages ##

Your markdown pages. Extension `md`. You need `index.md` for the homepage. A
page `mypage.md` has the url `#/mypage`.

Start with a little medata header:

    layout: default
    title: Page Title
    ---

    your markdown


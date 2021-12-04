https://news.ycombinator.com/item?id=25701053

susam [–]

Note that closing </p> tags are optional†, so one can be an HTML purist and still write a decent HTML document with a relatively clean markup like this:

    <!DOCTYPE html>
    <html lang="en">
    <title>Lorem Ipsum</title>
    <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    Duis id maximus tortor. Sed nisi ante, fermentum vel nunc
    et, tincidunt sagittis magna. In ultrices commodo lacus, id
    tristique ipsum euismod laoreet.
    <p>
    Maecenas at neque posuere, aliquet erat at, vehicula est.
    Duis aliquet elit et arcu laoreet, id pulvinar eros pretium.
    Quisque consectetur, enim semper facilisis feugiat, velit
    sapien semper arcu, eu mollis libero est et odio.
    <p>
    Curabitur fringilla interdum ante vel ultricies. Mauris
    volutpat nisi sed turpis elementum elementum. Mauris nec
    eleifend lorem. Sed ac vulputate libero.

A valid HTML5 document does not require† explicit <head>, <body>, or the closing </p>, </html> tags. See https://html.spec.whatwg.org/#optional-tags for more details.

Similarly, the markup for lists and tables can be cleaned up too because the closing </li>, </tr>, </th>, </td> tags are optional†.

Note that the opening <html> tag is optional† too but I retained it in the above example to specify the lang attribute otherwise the W3 markup validator warns, "Consider adding a lang attribute to the html start tag to declare the language of this document."

† These tags are optional provided certain conditions are met. See the spec for full details. In practice, one almost never has to worry about these conditions. 

https://paulkinchla.com/blog/javascript-is-a-ghost/

https://css-tricks.com/using-details-for-menus-and-dialogs-is-an-interesting-idea/
> https://news.ycombinator.com/item?id=26915706

https://www.matuzo.at/blog/html-boilerplate/
> https://news.ycombinator.com/item?id=26952557

https://markodenic.com/html-tips/
> https://news.ycombinator.com/item?id=27054348

https://localghost.dev/2021/06/the-right-tag-for-the-job-why-you-should-use-semantic-html/
> https://news.ycombinator.com/item?id=27414183

https://learn-the-web.algonquindesign.ca/topics/html-semantics-cheat-sheet/

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist
> https://news.ycombinator.com/item?id=27602699

https://www.nayuki.io/page/practical-guide-to-xhtml

# WYSIWYG
https://codemirror.net/
> https://prosemirror.net/

https://github.com/tinymce/tinymce

https://www.tiptap.dev/
> https://news.ycombinator.com/item?id=26901975

https://editorjs.io/

http://john.ankarstrom.se/html/
> https://news.ycombinator.com/item?id=26723408

https://docs.slatejs.org/

https://github.com/michelson/dante

https://en.wikipedia.org/wiki/Markdown

https://www.w3.org/Amaya/

https://web.archive.org/web/20140310190221/http://www.sewingandembroiderywarehouse.com/embtrb.htm
> https://news.ycombinator.com/item?id=28052190

https://nolanlawson.com/2021/08/08/improving-responsiveness-in-text-inputs/
> https://news.ycombinator.com/item?id=28107364

# DOM
https://en.wikipedia.org/wiki/Document_Object_Model
https://domevents.dev/

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ruby Represents small annotations that are rendered above,
> https://news.ycombinator.com/item?id=27999898
> https://news.ycombinator.com/item?id=29441857

# Security
https://korben.info/exploit-fichier-texte-txt-macos.html

https://developer.mozilla.org/en-US/docs/Web/API/HTML_Sanitizer_API
> https://news.ycombinator.com/item?id=27061020

# Body
https://atfzl.com/don-t-attach-tooltips-to-document-body
> https://news.ycombinator.com/item?id=28230977

# Link
https://www.jefftk.com/p/why-prefetch-is-broken
> https://news.ycombinator.com/item?id=27365608

# Tools
https://en.wikipedia.org/wiki/Dynamic_HTML

https://remaketheweb.com/
> https://news.ycombinator.com/item?id=27148097
> https://github.com/remake/remake-framework

# Parser
https://htmlparser.info/
> https://news.ycombinator.com/item?id=27311627

https://bien.ee/a-contenteditable-pasted-garbage-and-caret-placement-walk-into-a-pub/
> https://news.ycombinator.com/item?id=27924970

# Checkbox
https://www.bryanbraun.com/checkboxland/
> https://news.ycombinator.com/item?id=28489791
> https://www.bryanbraun.com/2020/06/06/checkboxland/

# History
https://zachholman.com/posts/only-90s-developers/
> https://news.ycombinator.com/item?id=29296003

# News
https://www.ctrl.blog/entry/html-responsive-video.html
> https://news.ycombinator.com/item?id=29024868

https://github.com/WebKit/explainers/tree/main/model
> https://news.ycombinator.com/item?id=28353997

https://news.ycombinator.com/item?id=28055160


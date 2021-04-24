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

# WYSIWYG
https://codemirror.net/
* https://prosemirror.net/

https://github.com/tinymce/tinymce

https://www.tiptap.dev/
* https://news.ycombinator.com/item?id=26901975

https://editorjs.io/

http://john.ankarstrom.se/html/
* https://news.ycombinator.com/item?id=26723408

https://en.wikipedia.org/wiki/Markdown

# Security
https://korben.info/exploit-fichier-texte-txt-macos.html

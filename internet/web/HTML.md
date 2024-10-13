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

# Rich Text Editors - WYSIWYG
https://codemirror.net/
> https://prosemirror.net/

https://marijnhaverbeke.nl/blog/codemirror-6.html
> https://news.ycombinator.com/item?id=31666186

https://thememirror.net/

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

https://www.ashbyhq.com/blog/company/tiptap-part-1
> https://news.ycombinator.com/item?id=30299800

https://news.ycombinator.com/item?id=30673759

https://github.com/ozanyurtsever/verbum
> https://news.ycombinator.com/item?id=31822619

https://www.hogbaysoftware.com/posts/bike-rich-text/
> https://news.ycombinator.com/item?id=33489123

https://github.com/wymeditor/wymeditor

https://github.com/steven-tey/novel
> https://news.ycombinator.com/item?id=36360789
> > https://github.com/yjs/yjs Shared data types for building collaborative software
> > https://www.blocknotejs.org/
> > https://github.com/blacksmithgu/datacore

https://news.ycombinator.com/item?id=37974321

https://news.ycombinator.com/item?id=41259926

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

https://blog.ledez.net/informatique/tips/redirection-html/

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

https://getcssscan.com/css-checkboxes-examples
> https://news.ycombinator.com/item?id=33418445

https://tonsky.me/blog/checkbox/
> https://news.ycombinator.com/item?id=39161339

https://news.ycombinator.com/item?id=40800869

# History
https://zachholman.com/posts/only-90s-developers/
> https://news.ycombinator.com/item?id=29296003

# News
https://news.ycombinator.com/item?id=41801334

https://news.ycombinator.com/item?id=41733625

https://news.ycombinator.com/item?id=41683144
> https://hotwired.dev/

https://news.ycombinator.com/item?id=41512213

https://lobste.rs/s/oeprnw/i_html_inline_html_import_element

https://hotwired.dev/

https://htmlhead.dev/
> https://news.ycombinator.com/item?id=40968981

https://news.ycombinator.com/item?id=40968981

https://9elements.com/blog/responsive-bar-charts-in-html-and-css/
> https://news.ycombinator.com/item?id=40949021

https://news.ycombinator.com/item?id=40709769

https://news.ycombinator.com/item?id=40650974

https://news.ycombinator.com/item?id=40242410

https://jakearchibald.com/2024/attributes-vs-properties/
> https://news.ycombinator.com/item?id=40152682

https://news.ycombinator.com/item?id=40177906

https://v2-0v2-0.htmx.org/posts/2024-03-15-htmx-2-0-0-beta1-is-released/

https://news.ycombinator.com/item?id=39614404

https://news.ycombinator.com/item?id=39560180

https://leanrada.com/htmz/
> https://github.com/Kalabasa/htmz MIT
> https://news.ycombinator.com/item?id=39429370

https://webkit.org/blog/14933/bringing-back-horizontal-rules-in-select-elements/
> https://news.ycombinator.com/item?id=39139598

https://news.ycombinator.com/item?id=39144360

https://www.technologyreview.com/2023/12/21/1084525/internet-whimsy-html-energy/

https://www.htmhell.dev/adventcalendar/2023/8/
> https://news.ycombinator.com/item?id=38605477

https://meyerweb.com/eric/thoughts/2023/12/06/three-decades-of-html/
> https://news.ycombinator.com/item?id=38559247

https://html-lang.org/
> https://news.ycombinator.com/item?id=38519719

https://tedium.co/2023/11/24/weird-html-hacks-history/
> https://news.ycombinator.com/item?id=38485295

https://html-first.com/
> https://news.ycombinator.com/item?id=38241304

https://htmx.org/essays/no-build-step/
> https://news.ycombinator.com/item?id=37265097

https://catskull.net/html.html
> https://news.ycombinator.com/item?id=36966653

https://developer.mozilla.org/en-US/play
> https://news.ycombinator.com/item?id=36798157

https://github.com/PyHAT-stack/awesome-python-htmx

https://htmx.org/posts/2023-07-14-htmx-1-9-3-is-released/
> https://news.ycombinator.com/item?id=36730186

https://twinspark.js.org/
> https://news.ycombinator.com/item?id=36613144

https://unsuckjs.com/
> https://news.ycombinator.com/item?id=36343544

https://github.com/mgdm/htmlq

https://htmlwithsuperpowers.netlify.app/

https://htmx.org/posts/2023-04-11-htmx-1-9-0-is-released/
> https://news.ycombinator.com/item?id=35530289

https://imkev.dev/fetchpriority-opportunity

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog
> https://news.ycombinator.com/item?id=34759527

https://danq.me/2023/01/11/nocode/
> https://news.ycombinator.com/item?id=34464951

https://www.devever.net/~hl/stringtemplates
> https://news.ycombinator.com/item?id=34395712

https://web.dev/top-cwv-2023/

https://sive.rs/shc

http://endless.horse/
> https://news.ycombinator.com/item?id=34177935
> > https://endless.dog/

https://livedom.bentkowski.info/ parsers

https://bt.ht/1kb/

https://github.com/idriskhenchil/Fort.js
> https://news.ycombinator.com/item?id=34057299

https://news.ycombinator.com/item?id=33952114

https://kittygiraudel.com/2022/09/30/templating-in-html/

https://github.com/orf/hq

https://beautiful-soup-4.readthedocs.io/en/latest/

https://github.com/ericchiang/pup
> https://news.ycombinator.com/item?id=33805732

https://news.ycombinator.com/item?id=33553895 i

https://blog.jim-nielsen.com/2022/browsers-json-formdata/
> https://news.ycombinator.com/item?id=33544323

https://ericwbailey.website/published/aria-label-is-a-code-smell/
> https://news.ycombinator.com/item?id=33409501

https://codeofhonor.substack.com/p/escaping-user-input-is-ridonkulously
> https://news.ycombinator.com/item?id=33402851

https://handwritten.blog/2022-10-01-hyperlinks-in-handwriting.html
> https://news.ycombinator.com/item?id=33055426

https://rutar.org/writing/how-to-build-a-personal-webpage-from-scratch/
> https://news.ycombinator.com/item?id=33017056

https://enhance.dev/docs/
> https://news.ycombinator.com/item?id=32987840

https://css-tricks.com/named-element-ids-can-be-referenced-as-javascript-globals/
> https://news.ycombinator.com/item?id=32995694

https://blog.webpagetest.org/posts/will-html-content-make-site-faster/
> https://news.ycombinator.com/item?id=32928298

https://stackoverflow.blog/2022/09/15/why-the-number-input-is-the-worst-input/
> https://news.ycombinator.com/item?id=32852643

https://www.etsy.com/codeascraft/priority-hints-what-your-browser-doesnt-know-yet
> https://web.dev/priority-hints/

https://austinhenley.com/blog/mycomputingstory.html
> https://news.ycombinator.com/item?id=31925645

https://lofi.limo/blog/write-html-right
> https://news.ycombinator.com/item?id=31694849

https://www.smashingmagazine.com/2022/03/html-attributes-you-never-use/

https://github.com/ludovicianul/hq

https://github.com/gildas-lormeau/SingleFile
> https://news.ycombinator.com/item?id=30527999

https://en.wikipedia.org/wiki/Progressive_enhancement
> https://technology.blog.gov.uk/2016/09/19/why-we-use-progressive-enhancement-to-build-gov-uk/
> > https://news.ycombinator.com/item?id=12538144

https://andrewpillar.com/programming/2022/02/26/req-an-http-scripting-language/ go
> https://github.com/andrewpillar/req

https://css-tricks.com/explain-the-first-10-lines-of-twitter-source-code/
> https://news.ycombinator.com/item?id=30464350

https://devapt.com/html-tags
> https://news.ycombinator.com/item?id=30469695

https://thenewstack.io/htmx-html-approach-to-interactivity-in-a-javascript-world/

https://webkit.org/blog/12209/introducing-the-dialog-element/

https://www.scottohara.me/blog/2022/01/20/divisive.html

https://blog.scottlogic.com/2022/01/20/noJS-making-a-calculator-in-pure-css-html.html
> https://news.ycombinator.com/item?id=30021058

https://html.energy/
> https://news.ycombinator.com/item?id=29942463

https://css-tricks.com/a-whole-website-in-a-single-html-file/
> https://news.ycombinator.com/item?id=29668260

https://www.ctrl.blog/entry/html-responsive-video.html
> https://news.ycombinator.com/item?id=29024868

https://github.com/WebKit/explainers/tree/main/model
> https://news.ycombinator.com/item?id=28353997

https://news.ycombinator.com/item?id=28055160


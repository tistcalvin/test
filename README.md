= AsciiDoc Article Title
Firstname Lastname <author@asciidoctor.org>
1.0, July 29, 2014, Asciidoctor 1.5 article template
:toc:
:icons: font
:quick-uri: https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/

Content entered directly below the header but before the first section heading is called the preamble.

== First level heading

This is a paragraph with a *bold* word and an _italicized_ word.

.Image caption
image::image-file-name.png[I am the image alt text.]

This is another paragraph.footnote:[I am footnote text and will be displayed at the bottom of the article.]

=== Second level heading

.Unordered list title
* list item 1
** nested list item
*** nested nested list item 1
*** nested nested list item 2
* list item 2

This is a paragraph.

.Example block title
====
Content in an example block is subject to normal substitutions.
====

.Sidebar title
****
Sidebars contain aside text and are subject to normal substitutions.
****

==== Third level heading

[#id-for-listing-block]
.Listing block title
----
Content in a listing block is subject to verbatim substitutions.
Listing block content is commonly used to preserve code input.
----

===== Fourth level heading

.Table title
|===
|Column heading 1 |Column heading 2

|Column 1, row 1
|Column 2, row 1

|Column 1, row 2
|Column 2, row 2
|===

====== Fifth level heading

[quote, firstname lastname, movie title]
____
I am a block quote or a prose excerpt.
I am subject to normal substitutions.
____

[verse, firstname lastname, poem title and more]
____
I am a verse block.
  Indents and endlines are preserved in verse blocks.
____

== First level heading

TIP: There are five admonition labels: Tip, Note, Important, Caution and Warning.

// I am a comment and won't be rendered.

. ordered list item
.. nested ordered list item
. ordered list item

The text at the end of this sentence is cross referenced to <<_third_level_heading,the third level heading>>

== First level heading

This is a link to the https://asciidoctor.org/docs/user-manual/[Asciidoctor User Manual].
This is an attribute reference {quick-uri}[which links this text to the Asciidoctor Quick Reference Guide].

plaindumb
=========

A cleaner alternative to markdown, that compiles to HTML or reST.

Markdown does too much stuff, and the syntax is not as naturally intuitive as
it aims to be.

It is the primary objective of **plaindumb** to make the source text as legible
as possible. Ideally, the uninformed reader should not even be aware that a
plaindumb document compiles to other formats. There should never be a moment
where the reader is left scratching their head as to what the funny symbols
mean.

This is the syntax of a plaindumb document as it compiles to HTML - as you can
see it doesn't do much, and the syntax should appear most unsurprising to you.

`
   *bold*   /italic/   _underline_  ------>  <b>bold</b>  <i>italic</i>  <u>underline</u>

   * unordered list                 ------>  <ul>
   * unordered list second item     ------>    <li> unordered list
                                    ------>    <li> unordered list second item
                                    ------>  </ul>

   1. ordered list                  ------>  <ol>
   2. ordered list second item      ------>    <li> ordered list
                                    ------>    <li> ordered list second item
                                    ------>  </ol>

     preformatted text              ------>  <pre>  preformatted text
     preformatted text              ------>    preformatted text
     preformatted text              ------>    preformatted text</pre>

   header1                          ------>  <h1>header1</h1>
   #######
  
   header2                          ------>  <h2>header2</h2>
   =======

   header3                          ------>  <h3>header3</h3>
   -------

   http://somelink.com              ------>  <a href="http://somelink.com">http://somelink.com</a>

   http://somelink.com (Link text)  ------>  <a href="http://somelink.com">Link text</a>
`


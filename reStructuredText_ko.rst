
Header 6
!!!!!!!!

Styles
------

toto::
   *Italic*
   **Bold**
   ~~strikethrough~~
   ``code``

*Italic*
**Bold**
~~strikethrough~~
``code``

Blockquotes
-----------

> Aaaa
>> Bbbb
> Cccc

Link
----

::
   <url>
   [text](url)

   [ref]
   [ref]: url

   [text][ref]
   [ref]: url

<http://www.google.com/>

[google](http://www.google.com/)

[google][]
[google]: http://www.google.com/

[google][g]
[G]: http://www.google.com/


[Foo]: http://www.google.com/ "google"

[Foo]: <http://www.google.com/> (google)

Image
-----

::
   ![alt](url "title")

![](http://www.google.com/images/google_favicon_128.png "google")

[![](http://www.google.com/images/google_favicon_128.png "GoTo Google")](http://www.google.com/)

List
----

::
   * Item 1
   * Item 2
     * Item 2a
     * Item 2b

* Item 1
* Item 2
  * Item 2a
  * Item 2b

Task list
---------

::
   - [x] Aaaa
   - [ ] Bbbb

- [x] Aaaa
- [ ] Bbbb

Lines

code ::
   ----
   ****

-----
*****

Tables
------

::
   Header 1 | Header 2
   -------- | --------
   Aaaa     | Bbbb

Header 1 | Header 2
-------- | --------
Aaaa     | Bbbb

Code
----

.. code-block:: javascript
   function toto() {
     // comment
     call();
   }


Special logos
-------------

[![Build Status](https://travis-ci.org/ekalinin/github-markdown-toc.svg?branch=master)](https://travis-ci.org/ekalinin/github-markdown-toc)

Emoji
-----

<http://www.emoji-cheat-sheet.com/>

::
   :tada:
   :exclamation:
   :point_up:
   :hand:
   :thumbsup:
   :zap:
   :sunny:
   :one:

:tada: |
:exclamation: |
:point_up: |
:hand: |
:thumbsup: |
:zap: |
:sunny: |
:one:

Special char
------------

➥

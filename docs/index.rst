.. ReStructuredText Syntax and Features

Introduction
------------

ReStructuredText (RST) is a plain text markup syntax used for writing structured documents. It is commonly used for writing documentation for software projects, but can be used for any type of document.

Headings
--------

Headings are created using underlined text, with the level of the heading determined by the number of underlining characters. For example:

.. code-block:: rst

   My Heading
   =========

.. code-block:: rst

   My Subheading
   -------------

Lists
-----

Bulleted lists can be created using the `*` character:

.. code-block:: rst

   * Item 1
   * Item 2
   * Item 3

Numbered lists can be created using the `#.` syntax:

.. code-block:: rst

   #. First item
   #. Second item
   #. Third item

Links
-----

Links can be added using the ``<link>`_` syntax:

.. code-block:: rst

   For more information, see the `official website <https://example.com>`_.

Images
------

Images can be added using the `.. image::` directive:

.. code-block:: rst

   .. image:: image.png
      :alt: Alt text
      :align: center

Code Blocks
-----------

Code blocks can be added using the ```` code-block:: ```` directive:

.. code-block:: rst

   .. code-block:: python

      def hello_world():
          print("Hello, world!")

Tables
------

Tables can be added using the `====` syntax:

.. code-block:: rst

   ===============  ==============
   Column 1 header  Column 2 header
   ===============  ==============
   Row 1, Column 1  Row 1, Column 2
   Row 2, Column 1  Row 2, Column 2
   ===============  ==============

Emphasis
--------

Text can be emphasized using the `*` or `**` syntax:

.. code-block:: rst

   *italic*
   **bold**
   ***bold and italic***

Footnotes
---------

Footnotes can be added using the `[#]_` syntax:

.. code-block:: rst

   This is a sentence with a footnote. [#]_

.. code-block:: rst

   .. [#] Footnote text.

This is just a brief overview of the features and syntaxes available in RST. For more information, see the `official documentation <https://docutils.sourceforge.io/docs/user/rst/quickref.html>`_.

.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _next-steps:

Next steps
""""""""""

.. note::
   What might be the next steps? Some ideas may be adding a second level for the navigation,
   Creating a graphical menu (different from a text menu) or ensuring that the HTML output conforms to the W3C-standard, etc.

In this tutorial we built the website by adding markers and
subparts to an HTML file and mapping them to a TypoScript template,
which is quite a standard way to do the job.

Other possibilities which might be covered in future tutorials are:

- using the TYPO3 extension `automaketemplate: <http://typo3.org/extensions/repository/view/automaketemplate>`_,
  which basically works the same way we learned in this tutorial with the difference that it
  automatically wraps those sections of an HTML page which have a certain class or id, in corresponding template subparts.

- using the TYPO3 extension `TemplaVoila! <http://typo3.org/extensions/repository/view/templavoila>`_
  which allows creating more flexible page structures.

- building the website only with Typoscript without any HTML template.

- using the Fluid templating engine with the FLUIDTEMPLATE object (rather than a TEMPLATE object) more recent versions of TYPO3 CMS.

Do you want to know more about how copying objects in TypoScript works?
Do you know that you can also create so called "references" instead of copying an object?
If you want to know more, have a look at the manual :ref:`t3tssyntax:start`!

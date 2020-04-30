.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

**TUTORIAL NAME**
=================

..
    #### Comment: Use short, imperative titles e.g. Upload and share data, uploading and
    sharing data ####


Goal
----

In this tutorial we will learn how to use foo 1.0 to analyze bar.

..
    #### Comment: Avoid covering upstream and downstream steps that are not explicitly and
    necessarily part of the tutorial - write or link to separate quick
    starts/tutorials for those parts ####

----

.. toctree::
	:maxdepth: 2

	Tutorial home <self>
	Step One <step1.rst>
	Final Step <final_step.rst>
	Delete this example guide page <example_directives_delete.rst>
..
	#### Comment:This tutorial can have multiple pages. The table of contents assumes
	you have an additional page called 'Step One' with content located in 'step1.rst'
	Edit these titles and filenames as needed ####

Tutorial Maintainer(s)
------------------------

Who to contact if this tutorial needs fixing. You can also email
`Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

.. list-table::
    :header-rows: 1

    * - Maintainer
      - Institution
      - Contact
    * - Your Name
      - CyVerse / UA
      - Yourname@email.com

----

Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Prerequisite
      - Preparation/Notes
      - Link/Download
    * - CyVerse account
      - You will need a CyVerse account to complete this exercise
      - |CyVerse User Portal|
    * - Atmosphere access
      - You must have access to Atmosphere
      - |CyVerse User Portal|
    * - Cyberduck
      - Standalone software for upload/download to Data Store
      - |Download Cyberduck|

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Quick Start
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Manual|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |DE Manual|
      - |Discovery Environment Guide|
    * - Atmosphere
      - Command line (ssh) and/or Desktop (VNC)
      - |Atmosphere|
      - |Atmosphere Manual|
      - |Atmosphere Guide|
    * - BisQue
      - Web/Point-and-click and/or Command-line (API)
      - |BisQue|
      - |BisQue Manual|
      - (See Manual)
    * - DNA Subway
      - Web/Point-and-click
      - |DNA Subway|
      - (See Guide)
      - |DNA Subway Guide|
    * - SciApps
      - Command-line (API)
      - |SciApps|
      - (See Guide)
      - |SciApps Guide|
    * - Agave API
      - Command-line (API)
      - |Agave API|
      - |Agave Live Docs|
      - (See Live Docs)

Application(s) used
~~~~~~~~~~~~~~~~~~~
..
	#### Comment: these tables are examples, delete whatever is unnecessary ####

**Discovery Environment App(s):**

.. list-table::
    :header-rows: 1

    * - App name
      - Version
      - Description
      - App link
      - Notes/other links
    * - Muscle
      - 3.8.31
      - Multiple sequence aligner
      -	|DE Application URL|
      - |Original App Documentation|


**Atmosphere Image(s):**

.. list-table::
    :header-rows: 1

    * - Image name
      - Version
      - Description
      - Link
      - Notes/other links
    * - CyVerse CentOS 6.8 GUI Base
      - 1.0
      - base image CentOS 6.8 with GNOME GUI
      - |Atmosphere Image|
      -

----

Input and sample data
~~~~~~~~~~~~~~~~~~~~~~


*In order to complete this tutorial with your own data you will need to have
the following inputs prepared*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Sample Data
    * -
      -
      -
      -

.. admonition:: Sample data

   **How to use provided sample data**

   If your tutorial is using data from a paper, talk about it here. Remind
   the user that instructions for settings or choices specific to the
   sample data will appear with this colored background.

   **Sample data citation**:

   Cite it here and link to the paper.


----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25

.. |Intercomm| image:: ./img/intercom.png
    :width: 25
    :height: 25

.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>

.. |Download Cyberduck| raw:: html

   <a href="https://cyberduck.io/" target="blank">Download Cyberduck</a>

.. |DE Application URL|  raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=9b41c9e4-5031-4a49-b1cb-c471335df16e&system-id=de" target="blank"><img src="https://de.cyverse.org/Powered-By-CyVerse-blue.svg"></a>

.. |Original App Documentation|  raw:: html

   <a href="http://www.drive5.com/muscle/manual/" target="blank">Original App Documentation</a>

.. |Atmosphere Image|  raw:: html

   <a href="https://atmo.cyverse.org/application/images/1384" target="blank">Atmosphere Image</a>

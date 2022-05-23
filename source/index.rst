.. include:: substitutions.rst

.. Test_Sphinx_Documentation documentation master file, created by
   sphinx-quickstart on Wed May 11 09:41:30 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


.. tabbed:: Intro Page

  .. rst-class:: blue-32px

  |Product| documentation provides a variety of resources that will help you learn how to use the application, click the below panes to learn more about the particular topic.

  |test_variable1| |test_variable2|

  .. panels::
      :container: container-lg pb-3 px-md-0 px-5
      :column: col-lg-6 col-md-6 col-sm-6 col-xs-12 p-2
     
      .. div:: align-center

         .. fa:: download

      .. div:: align-center

         If you do not have PrIME installed and want to get started, follow the :doc:`installation` guide.
      ---

      .. div:: align-center

         .. fa:: walking

      .. div:: align-center

         If you are looking for a summary of its features and interface, check out the :doc:`quickstart` guide.
      ---

      .. div:: align-center

         .. fa:: info-circle

      .. div:: align-center

         If you are looking for information about subscriptions, go to :doc:`subscriptions`.
      ---

      .. div:: align-center

         .. fa:: universal-access      

      .. div:: align-center

         If you are looking for information about solutions and assets, go to :doc:`solutions_and_assets`.
      ---

      .. div:: align-center

         .. fa:: chart-bar

      .. div:: align-center

         If you are looking for information about reports, go to :doc:`reporting`.
      ---

      .. div:: align-center

         .. fa:: user

      .. div:: align-center

         If you are looking for information about managing users, go to :doc:`user_management`.
      ---

      .. div:: align-center

         .. fa:: first-aid

      .. div:: align-center

         If you've run into a PrIME problem and need help solving it, take a look at our :doc:`troubleshooting guide<troubleshooting>`.
      ---

      .. div:: align-center

         .. fa:: question-circle

      .. div:: align-center

         If you have a question about PrIME, visit the :doc:`FAQs` section.

.. tabbed:: Administrator Documentation

  .. toctree::
     :maxdepth: 3
     :caption: Administrator Documentation

     Displaying Headings <topic1>
     Displaying Visuals <topic2>
     Linking Pages <topic3>
     User Management <user_management>

.. tabbed:: User Documentation
    
  .. toctree::
     :maxdepth: 2
     :caption: User Documentation

     Quick Start <quickstart>
     Creating Lists <topic4>
     Reporting <reporting>

.. tabbed:: Business Documentation

  .. toctree::
     :maxdepth: 3
     :caption: Business Documentation

     Solutions and Assets <solutions_and_assets>
     Subscriptions <subscriptions>

.. tabbed:: Support
    
  .. toctree::
     :maxdepth: 2
     :caption: Support

     FAQs <FAQs>
     Release Notes <release_notes>
     Troubleshooting Guide <troubleshooting>
     Installation Guide <installation>

.. tabbed:: Videos
   
   .. youtube:: https://www.youtube.com/watch?v=K4TOrB7at0Y

   .. youtube:: K4TOrB7at0Y

   .. video:: _static/sample_video.mp4
       :width: 500
       :height: 300

   .. raw:: html
      
      <video width="320" height="240" controls>
         <source src="_static/sample_video.mp4" type="video/mp4">
      </video>

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`



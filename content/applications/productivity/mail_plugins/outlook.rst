==============
Outlook Plugin
==============

Configuration
=============

The Outlook :doc:`Mail Plugin <../mail_plugins>` needs to be configured both on Leansoft and Outlook.

.. _mail-plugin/outlook/enable-mail-plugin:

Enable Mail Plugin
------------------

First, you need to enable the *Mail Plugin* feature in your database. Go to :menuselection:`Settings
--> General Settings --> Integrations`, enable *Mail Plugin*, and *Save* the configuration.

.. _mail-plugin/outlook/install-plugin:

Connect your database
---------------------

#. Open any email in your Outlook mailbox, click on the *More actions* button, and select *Leansoft for
   Outlook*.

   .. image:: outlook/leansoft-for-outlook.png
      :align: center
      :alt: Leansoft for Outlook add-in button

#. The right-side panel can now display **Company Insights**. At the bottom, click on *Login*.

   .. image:: outlook/panel-login.png
      :align: center
      :alt: Logging in your Leansoft database

   .. note::
      Only a limited amount of *Company Insights* (*Lead Enrichment*) requests are available as a
      trial. This feature requires :ref:`prepaid credits <mail_plugins/pricing>`.

   .. tip::
      If, after a short while, the panel is still empty, it is possible that your browser cookie
      settings prevented it from loading.
      Note that these settings also change if you are in "Incognito" mode on your
      browser.

      To fix this issue, configure your browser to always allow cookies on Leansoft's plugin page.

      For Google Chrome, you can do so by following the guide at:
      `https://support.google.com/chrome/answer/95647 <https://support.google.com/chrome/answer/95647#:~:text=Allow%20or%20block%20cookies%20for%20a%20specific%20site>`_
      and adding `download.leansoft.vn` to the list of `Sites that can always use cookies`.

      Once done, the Outlook panel needs to be opened again.


#. Enter your Leansoft database URL and click on *Login*.

   .. image:: outlook/enter-database-url.png
      :align: center
      :alt: Entering your Leansoft database URL

#. Click on *Allow* to open the pop-up window.

   .. image:: outlook/new-window-warning.png
      :align: center
      :alt: New window pop-up warning

#. If you aren't logged into your database, enter your credentials.

#. Click on *Allow* to let the Outlook Plugin connect to your database.

   .. image:: outlook/leansoft-permission.png
      :align: center
      :alt: Allowing the Outlook Plugin to connect to a database

.. _mail-plugin/outlook/add-shortcut:

Add a shortcut to the plugin
----------------------------

By default, the Outlook Plugin can be opened from the *More actions* menu. However, to save
time, it's possible to add it next to the other default actions.

#. In your Outlook mailbox, click on *Settings*, then on *View all Outlook settings*.

   .. image:: outlook/all-outlook-settings.png
      :align: center
      :alt: Viewing all Outlook settings

#. Select *Customize actions* under *Mail*, click on *Leansoft for Outlook*, and then *Save*.

   .. image:: outlook/customize-actions.png
      :align: center
      :alt: Leansoft for Outlook customized action

#. Open any email; the shortcut should be displayed.

   .. image:: outlook/leansoft-outlook-shortcut.png
      :align: center
      :alt: Leansoft for Outlook customized action

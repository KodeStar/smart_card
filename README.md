Example Smart Card Client app
========================================

Running
-------

*   Install the Smart Card Connector app:

    <https://chrome.google.com/webstore/detail/smart-card-connector/khpfeaanjngmcnplbdlpegiifgpfgdco>

*   Install the Example app:

    *   Navigate to chrome://extensions page;
    *   Tick the "Developer mode" checkbox;
    *   Press the "Load unpacked extension..." button;
    *   Select the directory of the Example app.

*   In order to access the output from the Example app, click on the
    "Inspect views: background.html" link for the Example app at the
    chrome://extensions page.


Building
--------

* Run the following script:

      ./download-google-smart-card-client-library.py

  It will download the latest version of the client library
  ``google-smart-card-client-library.js``.

  Alternatively, you may download it manually from the project's GitHub
  Releases page
  (<https://github.com/GoogleChrome/chromeos_smart_card_connector/releases>)
  or build it manually (from the
  ``/example_js_standalone_smart_card_client_library/`` directory).
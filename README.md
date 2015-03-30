# Final-Project-Proposal
Website L10N Final Project Proposal

Group members:

John Di Rico

Xinhui Du (Emily)

Xian Lu (Jessica)

Kexin Pei (Isabel)

Topic:
Internationalize and localize a web app
Workflow:

1. Mark up the HTML: identify each string in the HTML that will need localization.
2. Create translations: create a new directory in the app's root with sub-directories for each language to be localized. Files containing the translations of strings will be stored in the sub-directories. 
3. Add JavaScript file: use a JavaScript library to find marked HTML and replace with
values in the corresponding locale sub-directory. Add a line link in the HTML to include it in the app.
4. Update “manifest.webapp”:  make the name and description show in the default language when a device is set to this language or a language not supported by the app; add the translations for “name” and “description” to the app manifest in order to override the app’s name and description in the default language
5. Test the localized apps: change the language setting in major browsers (Google Chrome, Firefox and IE).
Localize strings in JavaScript and HTML.
6. Translate the strings: use a TMS (Transifex, WorldServer, etc) to connect with translators.

Reference:
MDN (Mozilla Developer Network). Getting Started with App Localization. https://developer.mozilla.org/en-US/Apps/Build/Localization/Getting_started_with_app_localization#Add_l10n.js

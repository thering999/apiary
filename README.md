test API
/*

https://private-fa26f4-ssjmuk.apiary-mock.com/questions

https://private-fa26f4-ssjmuk.apiary-mock.com/animal

https://private-fa26f4-ssjmuk.apiary-mock.com/hospcode

*/

Apiary Editor
The Apiary Editor is the foundation of your API design. Apiary Editor supports API Blueprint and Swagger API Description languages.

Apiary Editor

Overview
Instant validation and live preview enable you to describe, test, share, and collaborate on an API in minutes.

Using the Editor
The Apiary Editor shows a preview of your documentation while providing instant feedback to ensure correct syntax in your API document.

Your API document will be parsed with warnings and errors as you type. These errors will be displayed both in the editor header and on the lines where the warnings and errors exist.

Preview your documentation in the editor: see code samples for interacting with your API, try out the mock server, or make calls to your production server through the console. The Apiary Editor enables you to try out your API design as you write it.

Apiary Editor console

Editor Header
The Editor Header allows for customizing the editor, getting feedback about warnings or errors that may be in your API document, saving and publishing your documentation, and even pushing your document to GitHub.

Feedback and Validations
The Apiary Editor gives you instant feedback on any warnings or errors in your document as you type. The feedback will include line numbers and explanations for the warnings and errors, which will take you to the corresponding line in the editor when clicked. You can also specify custom checks and warnings with the API Style Guide.

Apiary Editor showing semantic issue

Saving, Publishing, and Pushing to GitHub.
The header provides controls for saving and publishing your API document.

Note
Changes in the editor are not saved automatically.

If you have synced your API with GitHub, you can commit and push to GitHub directly from the editor. The sync works both ways: changes to your document on GitHub will be pulled down to Apiary.

Documentation Preview
The documentation preview shows what your API document will look like when rendered as documentation. It also lets you to try out your API as you build. The documentation preview is dynamically updated as you type in the editor.

Note
The mock server will only work with your published changes. This means you will need to save and publish your API to use the changes you’ve made.

Swagger in Apiary Editor
Default format for Swagger in Apiary is YAML. When you paste Swagger in JSON to editor, it will be validated and transformed into Swagger YAML.

Swagger in Apiary Editor

Read Only Projects and Branches
In some cases, you might want to prevent edits through Apiary Editor and allow modifications only through Apiary CLI or GitHub Sync/GitHub Integration.

Turning feature on
For both project and branches, this can be done in API Project’s settings.

API Project Settings

If you are using GitHub Integration, you can only prevent edits to selected branches. Currently, the edited branch is displayed in the heading of the Settings page.

API Project Settings GitHub Integration

How do I know if project is read-only?
When project or branch is read-only, a message (instead of buttons) will be displayed in the top right corner.

Read only Indicator

Also, when you open list of branches, every entry will tell you if it is read-only or not.

Read only Branches

Team APIs only & PRO plan only
This functionality is available only for team API Projects.

Only Apiary PRO plan subscribers can use this feature. If you are interested please contacts us.

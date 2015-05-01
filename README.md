# Email Templates
This repo will hold our email templates, which follow the patterns created by [Cerberus](http://tedgoas.github.io/Cerberus/).

## Contents
Our custom templates use media queries and are based off of `template-with-media-queries.html`.

### `base-responsive-template.html`
This template shows the various components we might use in an email, such as thumbnails and buttons.

### `welcome-template.html`
This template is for the new welcome email in Intercom. [Here's the draft of the email](https://app.intercom.io/a/apps/604d24eb524b3aff74f79015ad1715189f0b38b4/messages/auto/5603181/edit) in Intercom.

## Intercom
The [Responsive Template](https://app.intercom.io/apps/604d24eb524b3aff74f79015ad1715189f0b38b4/custom_email_templates/8864) with `welcome-template.html`.

For new templates, just copy the HTML over and insert a `{{ content }}` tag where the content of the WYSIWYG editor will go. The template also needs an `{{ unsubscribe_link }}` tag. The `welcom-template.html` template already has these in place.

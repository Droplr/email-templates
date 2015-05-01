# Email Templates
This repo will hold our email templates, which follow the patterns created by [Cerberus](http://tedgoas.github.io/Cerberus/).

## Contents
Our custom templates use media queries and are based off of `template-with-media-queries.html`. There's also `template-without-media-queries.html` that just uses a fluid, single-column layout, which we can also use as a base.

### `base-responsive-template.html`
This template shows the various components we might use in an email, such as thumbnails and buttons.

### `welcome-template.html`
This template is for the new welcome email in Intercom. [Here's the draft of the email](https://app.intercom.io/a/apps/604d24eb524b3aff74f79015ad1715189f0b38b4/messages/auto/5603181/edit) in Intercom.

### Assets
The folder `template-assets` contains the Droplr and social logos, but these are just for reference as I've hard-coded my own drop URLs for the images in the templates, like this:

`<img src="http://bernar.d.pr/rGG7+" alt="Droplr Logo" width="80" height="26" border="0" style="margin: auto;">`

## Intercom
In Intercom, the [Responsive Template](https://app.intercom.io/apps/604d24eb524b3aff74f79015ad1715189f0b38b4/custom_email_templates/8864) uses `welcome-template.html`.

For new templates, just copy the HTML over and insert a `{{ content }}` tag where the content of the WYSIWYG editor will go. The template also needs an `{{ unsubscribe_link }}` tag. The `welcome-template.html` template already has these in place.

# An ebook download app

This app shows off the customizability of the FusionAuth interface as well as the way it can be similar to the application.

You can log in or register with any address and you'll be able to download ebooks.

## To deploy

Push the code to the repo. The repo must be public unless you want to add Render as a GitHub app. This required admin permissions on the org, so I opted for a public app.

Log in to render.com. The account is in the password vault.

On the dashboard, choose the FusionAuth team.

Click on the 'fusionauth' app.

Click on 'manual deploy'.

Click on 'deploy latest commit'.

Then, wait for the app to be built.

It should be live on ebook.fusionauth.io when you are done.

## Local development

You can modify config/environments/development.rb, in particular the oauth settings, to point to a local FusionAuth instance.

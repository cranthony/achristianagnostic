# A Christian Agnostic

This is the source code for my (Chris Anthony's) personal blog, [achristianagnostic.com](https://achristianagnostic.com).

## Setup

Follow the instructions at https://gohugo.io/ to install Hugo.

And I followed the instructions at https://gohugo.io/hosting-and-deployment/hosting-on-render/ to host the site on Render.  Render should automatically re-build and re-deploy the site when the GitHub repository is updated.

## Common commands

### Run the web server locally

With drafts (pages marked with `draft = true`) enabled:

```
hugo server --buildDrafts
```

Without drafts:

```
hugo server
```

The command will print a URL that can be used to view the webpage.  Saving a source file will update the rendered web page.

### Update the website

The site is hosted by Render.  Updates the `main` branch of the repository should trigger an update of the hosted site.
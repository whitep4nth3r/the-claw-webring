# The Claw Webring

To add your site to The Claw Webring, edit [data/members.json](data/members.json).

```json
[
  {
    "name": "Your name",
    "feed": "https://yourfeedurl OR null",
    "url": "https://yourwebsiteurl/" # make sure to include a trailing slash!
  }
]
```

# Display The Claw Webring on your website

Add just two lines of code to your website. Updates published to the component will be automatically available.

[Visit The Claw Webring Widget repository](https://github.com/whitep4nth3r/the-claw-webring-widget/blob/main/README.md)
for more information including fallback content and styles for the widget in case JavaScript isn't available.

```html
<script src="https://the-claw-webring-widget.netlify.app/the-claw-webring-widget.mjs" type="module"></script>

<the-claw-webring-widget />
```

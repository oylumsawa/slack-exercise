# slack-exercise
Slack Exercise


When the site loads random thumbnail images appear on the web page, if you click the image actual size image appears in a lightbox.

Following steps implemented;

- When the document is ready **get_photos_via_json** method is called.
- In **get_photos_via_json**, make API call to Flickr to pull random images.
- Get image list in JSON response.
- Extract title and image url from each JSON element and create image html object.
- When click on photo shows in a lightbox.
- On lightbox, if you click close button goes back to the main page.
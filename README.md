iTunesPreviewPlayer
===================

iTunesPreviewPlayer makes it easy to embed an iTunes Preview player of any iTunes Store track.
Read guidelines of iTunes Song Previews : http://www.apple.com/itunes/affiliates/resources/blog/song-previews.html

Demo : http://michaelvillar.s3.amazonaws.com/iTunesPreviewPlayer/example.html

How to use
----------

```html
<link href="iTunesPreviewPlayer.css" rel="stylesheet" type="text/css" />
<script src="iTunesPreviewPlayer.js" type="text/javascript"></script>
<script>
// Create the instance with search term. Use artist and song name
var player = new iTunesPreviewPlayer("coldplay viva la vida");
// Add the DOMElement to any element of your page
document.body.appendChild(player.DOMElement());
</script>
```
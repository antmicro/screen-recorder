# Screen recorder

Antmicro's simple WebRTC-based screen recorder, for making videos or GIFs (not yet fully working at this time) - based on [RecordRTC](https://github.com/muaz-khan/RecordRTC)

The reason this was created is because we wanted a one-file solution that does not need a server (since WebRTC works fine fully client-side) and is tailored to our needs (defaults, UI etc.)

This is an early stage work in progress tool, PRs welcome.

Again, GIFs do not fully work yet, sadly.

## Usage (online)

Open:

* [screen-recorder](./screen-recorder.html)
* [video2gif (Chrome only)](./video2gif.html)

And enjoy.

As for recorders, there is a start and stop button, and the rest is handled by the browser really, so if you've ever used Google Meet or Zoom etc., you should be fine.

To use the converter, upload file with the button. When the conversion is finished, the result downloads automatically.

## Usage (local)

Download ``{video,gif}-recorder.html`` and open it in the browser of your choice (unless the browser of your choice is Internet Explorer or Safari, in which case, [tough luck](https://github.com/muaz-khan/RecordRTC#browsers-support)). Rest is same as above.

You can also download ``video2gif.html``, but it is guaranteed to work only in Chrome.

## LICENSE

MIT

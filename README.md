# Screen recorder

Copyright (c) 2020-2021 [Antmicro](https://www.antmicro.com)

Antmicro's simple WebRTC-based screen recorder, for making videos or GIFs - based on [RecordRTC](https://github.com/muaz-khan/RecordRTC) and [ffmpeg.wasm](https://github.com/ffmpegwasm/ffmpeg.wasm).

The reason this was created is because we wanted a one-file solution that does not need a server (since WebRTC works fine fully client-side) and is tailored to our needs (defaults, UI etc.)

This is an early stage work in progress tool, PRs welcome.

## Usage (online)

Open:

* [screen-recorder](./screen-recorder.html)
* [video2gif (Chrome only)](./video2gif.html)

And enjoy.

As for the recorder, there is a start and stop button, and the rest is handled by the browser really, so if you've ever used Google Meet or Zoom etc., you should be fine. GIF recording option relies on the converter, which is guaranteed to work only in Chrome.

To use the converter, upload file with the button. When the conversion is finished, the result downloads automatically.

## Usage (local)

Download ``screen-recorder.html`` and open it in the browser of your choice (unless the browser of your choice is Internet Explorer or Safari, in which case, [tough luck](https://github.com/muaz-khan/RecordRTC#browsers-support)). Rest is same as above.

To record directly as a GIF or use ``video2gif.html``, please use Chrome.

## Future ideas

* [Add subtitle capabilities](https://nickcanzoneri.com/ffmpeg/gif/2018/11/20/captioned-gifs-with-ffmpeg.html)

## LICENSE

MIT

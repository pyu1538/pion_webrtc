# data-channels-detach
data-channels-detach is an example that shows how you can detach a data channel. This allows direct access the the underlying [pion/datachannel](https://github.com/pion/datachannel). This allows you to interact with the data channel using a more idiomatic API based on the `io.ReadWriteCloser` interface.

The example mirrors the data-channels example.

## Install
```
go install github.com/pyu1538/pion_webrtc/v4/examples/data-channels-detach@latest
```

## Usage
The example can be used in the same way as the data-channel example or can be paired with the data-channels-detach-create example. In the latter case; run both example and exchange the offer/answer text by copy-pasting them on the other terminal.

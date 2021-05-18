# Padington

**Padington** is a tiny collaborative markdown editor that combines a [ProseMirror][prosemirror] text-editor with a channel based collaborative editing backend written in [Rust][rust-lang].

## Repositories

The code for this project lives in the following repositories:

- <https://github.com/xiphoseer/prosemirror-rs> for Rust types for ProseMirror JSON messages
- <https://github.com/xiphoseer/padington-server> for the backend service
- <https://github.com/xiphoseer/padington-client> for the HTML frontend

## Try it out

There is a demo server running at <https://padington.xiphoseer.de> if you want to try it out. Note that the documents on this instance are not saved across restarts and may be lost at any time.

[prosemirror]: https://prosemirror.net/
[rust-lang]: https://rust-lang.org/

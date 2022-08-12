# xinput_link_example
An example project that demonstrate how binary generated with rust-lld will crash when linking dylib on Windows 11

# Usage
On Windows 11, run `cargo run` and it should output:

```
error: process didn't exit successfully: `target\debug\xinput_link_example.exe` (exit code: 0xc0000409, STATUS_STACK_BUFFER_OVERRUN)
```

# License
[MIT](https://opensource.org/licenses/MIT)

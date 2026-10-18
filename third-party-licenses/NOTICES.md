# Third-Party Notices

PixelBrew uses or bundles the following third-party components. Each is governed by
its own license, which prevails for that component. Full license texts should be
shipped alongside the release binary (place them in this folder).

| Component | Role | License | Full text |
|-----------|------|---------|-----------|
| **ffmpeg** | Decode video / live streams / YouTube frames | LGPL-2.1+ (GPL if built with GPL components) | `ffmpeg-LICENSE.txt` — ship with the binary you distribute |
| **yt-dlp** | Resolve direct stream URLs | The Unlicense (public domain) | see below |
| **NAudio** | Audio capture for the spectrum analyzer | MIT | see below |
| **.NET runtime & libraries** | Application runtime | MIT (Microsoft) | https://github.com/dotnet/runtime/blob/main/LICENSE.TXT |

## Note on ffmpeg
PixelBrew invokes `ffmpeg.exe` as a **separate process** (a pipe), and does not
statically link ffmpeg's libraries into its own binary. If you redistribute an
ffmpeg build with PixelBrew, include that build's `LICENSE`/`COPYING` text in this
folder and keep the ffmpeg binary replaceable by the user.

---

## yt-dlp — The Unlicense

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this
software, either in source code form or as a compiled binary, for any purpose,
commercial or non-commercial, and by any means.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
For more information, please refer to <https://unlicense.org>

---

## NAudio — MIT License

Copyright (c) Mark Heath and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in the
Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is furnished to do so, subject
to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

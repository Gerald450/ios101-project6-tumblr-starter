# Project 6 - Tumblr Detail Viewer

Submitted by: **Gerald Shimo**

**Tumblr Detail Viewer** is an iOS app that displays a Tumblr photo feed and allows users to tap a post to view additional information on a dedicated detail screen. The detail screen shows a larger image along with its caption and other relevant metadata. It builds on the previous project by introducing a second view with proper navigation and data passing.

Time spent: **5 hours** in total

## Required Features

The following **required** functionality is completed:

- [x] Setup navigation to the Detail Screen
- [x] Created the Detail View UI
- [x] Added ability to pass post data to the Detail View Controller
- [x] Personal UI finishing touches (layout, spacing, colors)

## Additional Features

- [x] Improved image loading using Nuke
- [ ] Dynamic resizing for long captions
- [ ] Custom cell styling for cleaner feed
- [ ] Slight animations for smoother navigation

## Video Walkthrough


<div>
    <a href="https://www.loom.com/share/ef8464fbc07c4074b0e0bb2f960fff3c">
      <p>Videos | Library | Loom - 4 November 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/ef8464fbc07c4074b0e0bb2f960fff3c">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/ef8464fbc07c4074b0e0bb2f960fff3c-c18aeb571f0dab29-full-play.gif">
    </a>
</div>

## Notes

- Had to fix data passing because the wrong post model was initially being forwarded to the detail controller.
- Auto Layout required tuning to avoid truncation and scaling issues with captions + images.
- Learned how to cleanly separate concerns between the feed list and detail display.

## License

    Copyright 2025 Gerald Shimo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

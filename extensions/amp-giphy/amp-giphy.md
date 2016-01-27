<!---
Copyright 2015 The AMP HTML Authors. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS-IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

### <a name="amp-giphy"></a> `amp-giphy`

Displays a Giphy gif.

Example:
```html
<amp-giphy width=486 height=657
    layout="responsive"
    data-giphyid="adventure-time-alabama-shakes-sound-and-color-cgW5iwX0e37qg">
</amp-giphy>
```

**CAVEATS**

Twitter does not currently provide an API that yields fixed aspect ratio Tweet embeds. We currently automatically proportionally scale the Tweet to fit the provided size, but this may yield less than ideal appearance. Authors may need to manually tweak the provided width and height. You may also use the `media` attribute to select the aspect ratio based on screen width. We are looking for feedback how feasible this approach is in practice.

#### Attributes

**data-giphyid**

The ID of the giphy gif. In a URL like https://giphy.com/gifs/adventure-time-alabama-shakes-sound-and-color-cgW5iwX0e37qg `adventure-time-alabama-shakes-sound-and-color-cgW5iwX0e37qg` is the `giphyid`.

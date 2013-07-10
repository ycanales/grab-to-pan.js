# Grab-to-pan.js

A slim library with one purpose: An easy way to pan elements.

To illustrate its purpose, consider the following example:

```javascript
// Define the container that has to pan on grab
var g2p = new GrabToPan({
    element: scrollableContainer
});
// Activate the grab-to-pan behaviour
g2p.activate();
// Deactivate the grab-to-pan behaviour
g2p.deactivate();
```

In other words: This library allows one to change the scrolling offset of a
container by moving the mouse while the mouse button is pressed.

# License

Copyright 2013 Rob Wu <gwnRob@gmail.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


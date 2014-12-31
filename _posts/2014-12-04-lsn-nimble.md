---
layout: post
category: ecology
tags:
  - earlywarning
---





some sample data

library(sde)library(nimble)set.seed(123)d <- expression(0.5 * (10-x))s <- expression(1) data <- as.data.frame(sde.sim(X0=6,drift=d, sigma=s, T=20, N=100))sigma.x not provided, attempting symbolic derivation.
plot(data)<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 4.25 -7.765625 L 7.109375 -7.765625 L 7.109375 -8.75 L 0.25 -8.75 L 0.25 -7.765625 L 3.125 -7.765625 L 3.125 0 L 4.25 0 Z M 4.25 -7.765625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 1.796875 -6.28125 L 0.796875 -6.28125 L 0.796875 0 L 1.796875 0 Z M 1.796875 -8.75 L 0.796875 -8.75 L 0.796875 -7.484375 L 1.796875 -7.484375 Z M 1.796875 -8.75 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 0.84375 -6.28125 L 0.84375 0 L 1.84375 0 L 1.84375 -3.953125 C 1.84375 -4.859375 2.515625 -5.59375 3.328125 -5.59375 C 4.0625 -5.59375 4.484375 -5.140625 4.484375 -4.328125 L 4.484375 0 L 5.5 0 L 5.5 -3.953125 C 5.5 -4.859375 6.15625 -5.59375 6.96875 -5.59375 C 7.703125 -5.59375 8.140625 -5.125 8.140625 -4.328125 L 8.140625 0 L 9.140625 0 L 9.140625 -4.71875 C 9.140625 -5.84375 8.5 -6.46875 7.3125 -6.46875 C 6.484375 -6.46875 5.96875 -6.21875 5.390625 -5.515625 C 5.015625 -6.1875 4.515625 -6.46875 3.703125 -6.46875 C 2.859375 -6.46875 2.296875 -6.15625 1.765625 -5.40625 L 1.765625 -6.28125 Z M 0.84375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 6.15625 -2.8125 C 6.15625 -3.765625 6.078125 -4.34375 5.90625 -4.8125 C 5.5 -5.84375 4.53125 -6.46875 3.359375 -6.46875 C 1.609375 -6.46875 0.484375 -5.125 0.484375 -3.0625 C 0.484375 -1 1.578125 0.28125 3.34375 0.28125 C 4.78125 0.28125 5.765625 -0.546875 6.03125 -1.90625 L 5.015625 -1.90625 C 4.734375 -1.078125 4.171875 -0.640625 3.375 -0.640625 C 2.734375 -0.640625 2.203125 -0.9375 1.859375 -1.46875 C 1.625 -1.828125 1.53125 -2.1875 1.53125 -2.8125 Z M 1.546875 -3.625 C 1.625 -4.78125 2.34375 -5.546875 3.34375 -5.546875 C 4.328125 -5.546875 5.09375 -4.734375 5.09375 -3.703125 C 5.09375 -3.671875 5.09375 -3.640625 5.078125 -3.625 Z M 1.546875 -3.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 3.109375 -6.0625 L 3.109375 0 L 4.15625 0 L 4.15625 -8.515625 L 3.46875 -8.515625 C 3.09375 -7.203125 2.859375 -7.015625 1.21875 -6.8125 L 1.21875 -6.0625 Z M 3.109375 -6.0625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 6.078125 -1.046875 L 1.59375 -1.046875 C 1.703125 -1.734375 2.09375 -2.1875 3.125 -2.796875 L 4.328125 -3.4375 C 5.515625 -4.09375 6.125 -4.96875 6.125 -6.015625 C 6.125 -6.71875 5.84375 -7.375 5.34375 -7.84375 C 4.84375 -8.296875 4.21875 -8.515625 3.40625 -8.515625 C 2.328125 -8.515625 1.53125 -8.125 1.0625 -7.40625 C 0.75 -6.953125 0.625 -6.421875 0.59375 -5.5625 L 1.65625 -5.5625 C 1.6875 -6.125 1.765625 -6.484375 1.90625 -6.75 C 2.1875 -7.265625 2.734375 -7.578125 3.375 -7.578125 C 4.328125 -7.578125 5.046875 -6.90625 5.046875 -5.984375 C 5.046875 -5.3125 4.65625 -4.734375 3.90625 -4.3125 L 2.796875 -3.6875 C 1.015625 -2.671875 0.5 -1.875 0.40625 0 L 6.078125 0 Z M 6.078125 -1.046875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M -3.25 -3.5 L -6.28125 -5.609375 L -6.28125 -4.484375 L -4.015625 -2.96875 L -6.28125 -1.46875 L -6.28125 -0.328125 L -3.203125 -2.421875 L 0 -0.203125 L 0 -1.34375 L -2.40625 -2.9375 L 0 -4.515625 L 0 -5.671875 Z M -3.25 -3.5 "/>
</symbol>
<symbol overflow="visible" id="glyph1-2">
<path style="stroke:none;" d="M -6.0625 -3.109375 L 0 -3.109375 L 0 -4.15625 L -8.515625 -4.15625 L -8.515625 -3.46875 C -7.203125 -3.09375 -7.015625 -2.859375 -6.8125 -1.21875 L -6.0625 -1.21875 Z M -6.0625 -3.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph1-3">
<path style="stroke:none;" d="M -6.28125 -5.96875 C -7.6875 -5.765625 -8.515625 -4.859375 -8.515625 -3.5625 C -8.515625 -2.625 -8.046875 -1.78125 -7.296875 -1.28125 C -6.46875 -0.75 -5.421875 -0.515625 -3.875 -0.515625 C -2.453125 -0.515625 -1.53125 -0.734375 -0.78125 -1.234375 C -0.09375 -1.6875 0.28125 -2.4375 0.28125 -3.375 C 0.28125 -4.984375 -0.921875 -6.15625 -2.59375 -6.15625 C -4.171875 -6.15625 -5.296875 -5.078125 -5.296875 -3.546875 C -5.296875 -2.71875 -4.96875 -2.046875 -4.34375 -1.59375 C -6.421875 -1.609375 -7.578125 -2.28125 -7.578125 -3.484375 C -7.578125 -4.234375 -7.109375 -4.75 -6.28125 -4.921875 Z M -4.359375 -3.421875 C -4.359375 -4.4375 -3.640625 -5.078125 -2.515625 -5.078125 C -1.4375 -5.078125 -0.65625 -4.359375 -0.65625 -3.390625 C -0.65625 -2.40625 -1.46875 -1.65625 -2.5625 -1.65625 C -3.625 -1.65625 -4.359375 -2.375 -4.359375 -3.421875 Z M -4.359375 -3.421875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-4">
<path style="stroke:none;" d="M -4.46875 -4.6875 C -5 -5.5625 -5.4375 -5.859375 -6.234375 -5.859375 C -7.578125 -5.859375 -8.515625 -4.8125 -8.515625 -3.296875 C -8.515625 -1.796875 -7.578125 -0.75 -6.234375 -0.75 C -5.453125 -0.75 -5.015625 -1.03125 -4.46875 -1.890625 C -4.015625 -0.921875 -3.296875 -0.4375 -2.359375 -0.4375 C -0.796875 -0.4375 0.28125 -1.625 0.28125 -3.296875 C 0.28125 -4.984375 -0.796875 -6.15625 -2.359375 -6.15625 C -3.296875 -6.15625 -4.015625 -5.671875 -4.46875 -4.6875 Z M -7.578125 -3.296875 C -7.578125 -4.203125 -7.046875 -4.78125 -6.21875 -4.78125 C -5.421875 -4.78125 -4.890625 -4.1875 -4.890625 -3.296875 C -4.890625 -2.40625 -5.421875 -1.828125 -6.234375 -1.828125 C -7.046875 -1.828125 -7.578125 -2.40625 -7.578125 -3.296875 Z M -4.015625 -3.296875 C -4.015625 -4.359375 -3.34375 -5.078125 -2.34375 -5.078125 C -1.328125 -5.078125 -0.65625 -4.359375 -0.65625 -3.28125 C -0.65625 -2.25 -1.34375 -1.53125 -2.34375 -1.53125 C -3.34375 -1.53125 -4.015625 -2.25 -4.015625 -3.296875 Z M -4.015625 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-5">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-6">
<path style="stroke:none;" d="M -1.046875 -6.078125 L -1.046875 -1.59375 C -1.734375 -1.703125 -2.1875 -2.09375 -2.796875 -3.125 L -3.4375 -4.328125 C -4.09375 -5.515625 -4.96875 -6.125 -6.015625 -6.125 C -6.71875 -6.125 -7.375 -5.84375 -7.84375 -5.34375 C -8.296875 -4.84375 -8.515625 -4.21875 -8.515625 -3.40625 C -8.515625 -2.328125 -8.125 -1.53125 -7.40625 -1.0625 C -6.953125 -0.75 -6.421875 -0.625 -5.5625 -0.59375 L -5.5625 -1.65625 C -6.125 -1.6875 -6.484375 -1.765625 -6.75 -1.90625 C -7.265625 -2.1875 -7.578125 -2.734375 -7.578125 -3.375 C -7.578125 -4.328125 -6.90625 -5.046875 -5.984375 -5.046875 C -5.3125 -5.046875 -4.734375 -4.65625 -4.3125 -3.90625 L -3.6875 -2.796875 C -2.671875 -1.015625 -1.875 -0.5 0 -0.40625 L 0 -6.078125 Z M -1.046875 -6.078125 "/>
</symbol>
</g>
</defs>
<g id="surface807">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 139.464844 L 61.574219 137.730469 L 62.078125 134.445312 L 62.585938 122.179688 L 63.09375 118.808594 L 63.601562 115.453125 L 64.105469 104.179688 L 64.613281 100.492188 L 65.121094 106.121094 L 65.625 108.210938 L 66.132812 108.847656 L 66.640625 100.75 L 67.148438 97.914062 L 67.652344 95.132812 L 68.160156 94.125 L 68.667969 96.671875 L 69.171875 86.808594 L 69.679688 84.578125 L 70.1875 95.363281 L 70.691406 91.265625 L 71.199219 93.652344 L 71.707031 98.90625 L 72.214844 99.246094 L 72.71875 103.75 L 73.226562 106.28125 L 73.734375 108.035156 L 74.238281 115.136719 L 74.746094 108.449219 L 75.253906 105.953125 L 75.761719 110.402344 L 76.265625 102.003906 L 76.773438 98.703125 L 77.28125 99.460938 L 77.785156 93.964844 L 78.292969 89.082031 L 78.800781 84.953125 L 79.308594 81.910156 L 79.8125 79.851562 L 80.320312 81.191406 L 80.828125 83.671875 L 81.332031 86.300781 L 81.839844 90.316406 L 82.347656 91.417969 L 82.851562 97.910156 L 83.359375 85.945312 L 83.867188 80.109375 L 84.375 86.933594 L 84.878906 89.371094 L 85.386719 91.910156 L 85.894531 87.730469 L 86.398438 88.429688 L 86.90625 87.316406 L 87.414062 87.773438 L 87.921875 88.261719 L 88.425781 81.371094 L 88.933594 83.414062 L 89.441406 76.21875 L 89.945312 85.625 L 90.453125 83.054688 L 90.960938 83.125 L 91.464844 82.710938 L 91.972656 81.484375 L 92.480469 84.957031 L 92.988281 87.21875 L 93.492188 92.828125 L 94 98.179688 L 94.507812 95.878906 L 95.011719 93.042969 L 95.519531 92.535156 L 96.027344 87.554688 L 96.535156 77.191406 L 97.039062 81.011719 L 97.546875 93.914062 L 98.054688 88.371094 L 98.558594 92.261719 L 99.066406 95.675781 L 99.574219 89.863281 L 100.078125 91.40625 L 100.585938 97.667969 L 101.09375 96.050781 L 101.601562 96.25 L 102.105469 95.679688 L 102.613281 93.191406 L 103.121094 94.867188 L 103.625 91.109375 L 104.132812 92.203125 L 104.640625 90.324219 L 105.148438 84.648438 L 105.652344 82.949219 L 106.160156 85.367188 L 106.667969 79.890625 L 107.171875 75.742188 L 107.679688 74.300781 L 108.1875 74.605469 L 108.691406 79.382812 L 109.199219 73.378906 L 109.707031 78.128906 L 110.214844 67.945312 L 110.71875 62.132812 L 111.226562 66.058594 L 111.734375 73.71875 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="72.898438" y="196.716797"/>
  <use xlink:href="#glyph0-2" x="80.230469" y="196.716797"/>
  <use xlink:href="#glyph0-3" x="82.894531" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="92.890625" y="196.716797"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="12.396484" y="107.300781"/>
  <use xlink:href="#glyph1-2" x="12.396484" y="101.300781"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 61.066406 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 73.734375 142.558594 L 73.734375 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 86.398438 142.558594 L 86.398438 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 99.066406 142.558594 L 99.066406 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-5" x="57.566406" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-6" x="79.398438" y="167.916016"/>
  <use xlink:href="#glyph0-5" x="86.070312" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-7" x="104.734375" y="167.916016"/>
  <use xlink:href="#glyph0-5" x="111.40625" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 59.039062 66.105469 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 51.839844 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 127.238281 L 51.839844 127.238281 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 115.011719 L 51.839844 115.011719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 102.785156 L 51.839844 102.785156 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 90.558594 L 51.839844 90.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 78.332031 L 51.839844 78.332031 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 66.105469 L 51.839844 66.105469 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-3" x="41.197266" y="142.964844"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-4" x="41.197266" y="118.511719"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-2" x="41.197266" y="97.558594"/>
  <use xlink:href="#glyph1-5" x="41.197266" y="90.886719"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-2" x="41.197266" y="73.105469"/>
  <use xlink:href="#glyph1-6" x="41.197266" y="66.433594"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 142.558594 L 113.761719 142.558594 L 113.761719 59.039062 L 59.039062 59.039062 L 59.039062 142.558594 "/>
</g>
</svg>



## LSN version ##

Test case: Set prior for `m` $\approx 0$:

lsn <- modelCode({
   theta ~ dunif(1e-10, 100.0)
   sigma_x ~ dunif(1e-10, 100.0)
   sigma_y ~ dunif(1e-10, 100.0)
       m ~ dunif(-1e2, 1e2)
    x[1] ~ dunif(0, 100)
    y[1] ~ dunif(0, 100) 

  for(i in 1:(N-1)){
    mu_x[i] <- x[i] + y[i] * (theta - x[i]) 
    x[i+1] ~ dnorm(mu_x[i], sd = sigma_x) 
    mu_y[i] <- y[i] + m * t[i]
    y[i+1] ~ dnorm(mu_y[i], sd = sigma_y) 
  }
})

Constants in the model definition are the length of the dataset, $N$ and the time points of the sample. Note we've made time explicit, we'll assume uniform spacing here. 

constants <- list(N = length(data$x), t = 1:length(data$x))

Initial values for the parameters

inits <- list(theta = 6, m = 0, sigma_x = 1, sigma_y = 1, y = rep(1,constants$N))


and here we go as before:

Rmodel <- nimbleModel(code = lsn, 
                      constants = constants, 
                      data = data, 
                      inits = inits)Cmodel <- compileNimble(Rmodel)



mcmcspec <- MCMCspec(Rmodel, print=TRUE,thin=1e2)[1] RW sampler;   targetNode: theta,  adaptive: TRUE,  adaptInterval: 200,  scale: 1
[2] RW sampler;   targetNode: sigma_x,  adaptive: TRUE,  adaptInterval: 200,  scale: 1
[3] RW sampler;   targetNode: sigma_y,  adaptive: TRUE,  adaptInterval: 200,  scale: 1
[4] RW sampler;   targetNode: m,  adaptive: TRUE,  adaptInterval: 200,  scale: 1
[5] RW sampler;   targetNode: y[1],  adaptive: TRUE,  adaptInterval: 200,  scale: 1
[6] conjugate_dnorm sampler;   targetNode: y[2],  dependents_dnorm: x[3], y[3]
[7] conjugate_dnorm sampler;   targetNode: y[3],  dependents_dnorm: x[4], y[4]
[8] conjugate_dnorm sampler;   targetNode: y[4],  dependents_dnorm: x[5], y[5]
[9] conjugate_dnorm sampler;   targetNode: y[5],  dependents_dnorm: x[6], y[6]
[10] conjugate_dnorm sampler;   targetNode: y[6],  dependents_dnorm: x[7], y[7]
[11] conjugate_dnorm sampler;   targetNode: y[7],  dependents_dnorm: x[8], y[8]
[12] conjugate_dnorm sampler;   targetNode: y[8],  dependents_dnorm: x[9], y[9]
[13] conjugate_dnorm sampler;   targetNode: y[9],  dependents_dnorm: x[10], y[10]
[14] conjugate_dnorm sampler;   targetNode: y[10],  dependents_dnorm: x[11], y[11]
[15] conjugate_dnorm sampler;   targetNode: y[11],  dependents_dnorm: x[12], y[12]
[16] conjugate_dnorm sampler;   targetNode: y[12],  dependents_dnorm: x[13], y[13]
[17] conjugate_dnorm sampler;   targetNode: y[13],  dependents_dnorm: x[14], y[14]
[18] conjugate_dnorm sampler;   targetNode: y[14],  dependents_dnorm: x[15], y[15]
[19] conjugate_dnorm sampler;   targetNode: y[15],  dependents_dnorm: x[16], y[16]
[20] conjugate_dnorm sampler;   targetNode: y[16],  dependents_dnorm: x[17], y[17]
[21] conjugate_dnorm sampler;   targetNode: y[17],  dependents_dnorm: x[18], y[18]
[22] conjugate_dnorm sampler;   targetNode: y[18],  dependents_dnorm: x[19], y[19]
[23] conjugate_dnorm sampler;   targetNode: y[19],  dependents_dnorm: x[20], y[20]
[24] conjugate_dnorm sampler;   targetNode: y[20],  dependents_dnorm: x[21], y[21]
[25] conjugate_dnorm sampler;   targetNode: y[21],  dependents_dnorm: x[22], y[22]
[26] conjugate_dnorm sampler;   targetNode: y[22],  dependents_dnorm: x[23], y[23]
[27] conjugate_dnorm sampler;   targetNode: y[23],  dependents_dnorm: x[24], y[24]
[28] conjugate_dnorm sampler;   targetNode: y[24],  dependents_dnorm: x[25], y[25]
[29] conjugate_dnorm sampler;   targetNode: y[25],  dependents_dnorm: x[26], y[26]
[30] conjugate_dnorm sampler;   targetNode: y[26],  dependents_dnorm: x[27], y[27]
[31] conjugate_dnorm sampler;   targetNode: y[27],  dependents_dnorm: x[28], y[28]
[32] conjugate_dnorm sampler;   targetNode: y[28],  dependents_dnorm: x[29], y[29]
[33] conjugate_dnorm sampler;   targetNode: y[29],  dependents_dnorm: x[30], y[30]
[34] conjugate_dnorm sampler;   targetNode: y[30],  dependents_dnorm: x[31], y[31]
[35] conjugate_dnorm sampler;   targetNode: y[31],  dependents_dnorm: x[32], y[32]
[36] conjugate_dnorm sampler;   targetNode: y[32],  dependents_dnorm: x[33], y[33]
[37] conjugate_dnorm sampler;   targetNode: y[33],  dependents_dnorm: x[34], y[34]
[38] conjugate_dnorm sampler;   targetNode: y[34],  dependents_dnorm: x[35], y[35]
[39] conjugate_dnorm sampler;   targetNode: y[35],  dependents_dnorm: x[36], y[36]
[40] conjugate_dnorm sampler;   targetNode: y[36],  dependents_dnorm: x[37], y[37]
[41] conjugate_dnorm sampler;   targetNode: y[37],  dependents_dnorm: x[38], y[38]
[42] conjugate_dnorm sampler;   targetNode: y[38],  dependents_dnorm: x[39], y[39]
[43] conjugate_dnorm sampler;   targetNode: y[39],  dependents_dnorm: x[40], y[40]
[44] conjugate_dnorm sampler;   targetNode: y[40],  dependents_dnorm: x[41], y[41]
[45] conjugate_dnorm sampler;   targetNode: y[41],  dependents_dnorm: x[42], y[42]
[46] conjugate_dnorm sampler;   targetNode: y[42],  dependents_dnorm: x[43], y[43]
[47] conjugate_dnorm sampler;   targetNode: y[43],  dependents_dnorm: x[44], y[44]
[48] conjugate_dnorm sampler;   targetNode: y[44],  dependents_dnorm: x[45], y[45]
[49] conjugate_dnorm sampler;   targetNode: y[45],  dependents_dnorm: x[46], y[46]
[50] conjugate_dnorm sampler;   targetNode: y[46],  dependents_dnorm: x[47], y[47]
[51] conjugate_dnorm sampler;   targetNode: y[47],  dependents_dnorm: x[48], y[48]
[52] conjugate_dnorm sampler;   targetNode: y[48],  dependents_dnorm: x[49], y[49]
[53] conjugate_dnorm sampler;   targetNode: y[49],  dependents_dnorm: x[50], y[50]
[54] conjugate_dnorm sampler;   targetNode: y[50],  dependents_dnorm: x[51], y[51]
[55] conjugate_dnorm sampler;   targetNode: y[51],  dependents_dnorm: x[52], y[52]
[56] conjugate_dnorm sampler;   targetNode: y[52],  dependents_dnorm: x[53], y[53]
[57] conjugate_dnorm sampler;   targetNode: y[53],  dependents_dnorm: x[54], y[54]
[58] conjugate_dnorm sampler;   targetNode: y[54],  dependents_dnorm: x[55], y[55]
[59] conjugate_dnorm sampler;   targetNode: y[55],  dependents_dnorm: x[56], y[56]
[60] conjugate_dnorm sampler;   targetNode: y[56],  dependents_dnorm: x[57], y[57]
[61] conjugate_dnorm sampler;   targetNode: y[57],  dependents_dnorm: x[58], y[58]
[62] conjugate_dnorm sampler;   targetNode: y[58],  dependents_dnorm: x[59], y[59]
[63] conjugate_dnorm sampler;   targetNode: y[59],  dependents_dnorm: x[60], y[60]
[64] conjugate_dnorm sampler;   targetNode: y[60],  dependents_dnorm: x[61], y[61]
[65] conjugate_dnorm sampler;   targetNode: y[61],  dependents_dnorm: x[62], y[62]
[66] conjugate_dnorm sampler;   targetNode: y[62],  dependents_dnorm: x[63], y[63]
[67] conjugate_dnorm sampler;   targetNode: y[63],  dependents_dnorm: x[64], y[64]
[68] conjugate_dnorm sampler;   targetNode: y[64],  dependents_dnorm: x[65], y[65]
[69] conjugate_dnorm sampler;   targetNode: y[65],  dependents_dnorm: x[66], y[66]
[70] conjugate_dnorm sampler;   targetNode: y[66],  dependents_dnorm: x[67], y[67]
[71] conjugate_dnorm sampler;   targetNode: y[67],  dependents_dnorm: x[68], y[68]
[72] conjugate_dnorm sampler;   targetNode: y[68],  dependents_dnorm: x[69], y[69]
[73] conjugate_dnorm sampler;   targetNode: y[69],  dependents_dnorm: x[70], y[70]
[74] conjugate_dnorm sampler;   targetNode: y[70],  dependents_dnorm: x[71], y[71]
[75] conjugate_dnorm sampler;   targetNode: y[71],  dependents_dnorm: x[72], y[72]
[76] conjugate_dnorm sampler;   targetNode: y[72],  dependents_dnorm: x[73], y[73]
[77] conjugate_dnorm sampler;   targetNode: y[73],  dependents_dnorm: x[74], y[74]
[78] conjugate_dnorm sampler;   targetNode: y[74],  dependents_dnorm: x[75], y[75]
[79] conjugate_dnorm sampler;   targetNode: y[75],  dependents_dnorm: x[76], y[76]
[80] conjugate_dnorm sampler;   targetNode: y[76],  dependents_dnorm: x[77], y[77]
[81] conjugate_dnorm sampler;   targetNode: y[77],  dependents_dnorm: x[78], y[78]
[82] conjugate_dnorm sampler;   targetNode: y[78],  dependents_dnorm: x[79], y[79]
[83] conjugate_dnorm sampler;   targetNode: y[79],  dependents_dnorm: x[80], y[80]
[84] conjugate_dnorm sampler;   targetNode: y[80],  dependents_dnorm: x[81], y[81]
[85] conjugate_dnorm sampler;   targetNode: y[81],  dependents_dnorm: x[82], y[82]
[86] conjugate_dnorm sampler;   targetNode: y[82],  dependents_dnorm: x[83], y[83]
[87] conjugate_dnorm sampler;   targetNode: y[83],  dependents_dnorm: x[84], y[84]
[88] conjugate_dnorm sampler;   targetNode: y[84],  dependents_dnorm: x[85], y[85]
[89] conjugate_dnorm sampler;   targetNode: y[85],  dependents_dnorm: x[86], y[86]
[90] conjugate_dnorm sampler;   targetNode: y[86],  dependents_dnorm: x[87], y[87]
[91] conjugate_dnorm sampler;   targetNode: y[87],  dependents_dnorm: x[88], y[88]
[92] conjugate_dnorm sampler;   targetNode: y[88],  dependents_dnorm: x[89], y[89]
[93] conjugate_dnorm sampler;   targetNode: y[89],  dependents_dnorm: x[90], y[90]
[94] conjugate_dnorm sampler;   targetNode: y[90],  dependents_dnorm: x[91], y[91]
[95] conjugate_dnorm sampler;   targetNode: y[91],  dependents_dnorm: x[92], y[92]
[96] conjugate_dnorm sampler;   targetNode: y[92],  dependents_dnorm: x[93], y[93]
[97] conjugate_dnorm sampler;   targetNode: y[93],  dependents_dnorm: x[94], y[94]
[98] conjugate_dnorm sampler;   targetNode: y[94],  dependents_dnorm: x[95], y[95]
[99] conjugate_dnorm sampler;   targetNode: y[95],  dependents_dnorm: x[96], y[96]
[100] conjugate_dnorm sampler;   targetNode: y[96],  dependents_dnorm: x[97], y[97]
[101] conjugate_dnorm sampler;   targetNode: y[97],  dependents_dnorm: x[98], y[98]
[102] conjugate_dnorm sampler;   targetNode: y[98],  dependents_dnorm: x[99], y[99]
[103] conjugate_dnorm sampler;   targetNode: y[99],  dependents_dnorm: x[100], y[100]
[104] conjugate_dnorm sampler;   targetNode: y[100],  dependents_dnorm: x[101], y[101]
[105] end sampler;   targetNode: y[101]
Rmcmc <- buildMCMC(mcmcspec)Cmcmc <- compileNimble(Rmcmc, project = Cmodel)


Cmcmc(1e4)NULL



and examine results

samples <- as.data.frame(as.matrix(nfVar(Cmcmc, 'mvSamples')))dim(samples)[1] 100 206
samples <- samples[,1:4]


mean(samples$theta)[1] 10.11174
mean(samples$m)[1] -1.88765e-05
mean(samples$sigma_x)[1] 0.385018





plot(samples[ , 'm'], type = 'l', xlab = 'iteration', ylab = 'm')plot(samples[ , 'sigma_x'], type = 'l', xlab = 'iteration', ylab = expression(sigma[x]))plot(samples[ , 'sigma_y'], type = 'l', xlab = 'iteration', ylab = expression(sigma[y]))plot(samples[ , 'theta'], type = 'l', xlab = 'iteration', ylab = expression(theta))<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 5.96875 -6.28125 C 5.765625 -7.6875 4.859375 -8.515625 3.5625 -8.515625 C 2.625 -8.515625 1.78125 -8.046875 1.28125 -7.296875 C 0.75 -6.46875 0.515625 -5.421875 0.515625 -3.875 C 0.515625 -2.453125 0.734375 -1.53125 1.234375 -0.78125 C 1.6875 -0.09375 2.4375 0.28125 3.375 0.28125 C 4.984375 0.28125 6.15625 -0.921875 6.15625 -2.59375 C 6.15625 -4.171875 5.078125 -5.296875 3.546875 -5.296875 C 2.71875 -5.296875 2.046875 -4.96875 1.59375 -4.34375 C 1.609375 -6.421875 2.28125 -7.578125 3.484375 -7.578125 C 4.234375 -7.578125 4.75 -7.109375 4.921875 -6.28125 Z M 3.421875 -4.359375 C 4.4375 -4.359375 5.078125 -3.640625 5.078125 -2.515625 C 5.078125 -1.4375 4.359375 -0.65625 3.390625 -0.65625 C 2.40625 -0.65625 1.65625 -1.46875 1.65625 -2.5625 C 1.65625 -3.625 2.375 -4.359375 3.421875 -4.359375 Z M 3.421875 -4.359375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 1.796875 -6.28125 L 0.796875 -6.28125 L 0.796875 0 L 1.796875 0 Z M 1.796875 -8.75 L 0.796875 -8.75 L 0.796875 -7.484375 L 1.796875 -7.484375 Z M 1.796875 -8.75 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 3.046875 -6.28125 L 2.015625 -6.28125 L 2.015625 -8.015625 L 1.015625 -8.015625 L 1.015625 -6.28125 L 0.171875 -6.28125 L 0.171875 -5.46875 L 1.015625 -5.46875 L 1.015625 -0.71875 C 1.015625 -0.078125 1.453125 0.28125 2.234375 0.28125 C 2.46875 0.28125 2.71875 0.25 3.046875 0.1875 L 3.046875 -0.640625 C 2.921875 -0.609375 2.765625 -0.59375 2.5625 -0.59375 C 2.140625 -0.59375 2.015625 -0.71875 2.015625 -1.15625 L 2.015625 -5.46875 L 3.046875 -5.46875 Z M 3.046875 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 6.15625 -2.8125 C 6.15625 -3.765625 6.078125 -4.34375 5.90625 -4.8125 C 5.5 -5.84375 4.53125 -6.46875 3.359375 -6.46875 C 1.609375 -6.46875 0.484375 -5.125 0.484375 -3.0625 C 0.484375 -1 1.578125 0.28125 3.34375 0.28125 C 4.78125 0.28125 5.765625 -0.546875 6.03125 -1.90625 L 5.015625 -1.90625 C 4.734375 -1.078125 4.171875 -0.640625 3.375 -0.640625 C 2.734375 -0.640625 2.203125 -0.9375 1.859375 -1.46875 C 1.625 -1.828125 1.53125 -2.1875 1.53125 -2.8125 Z M 1.546875 -3.625 C 1.625 -4.78125 2.34375 -5.546875 3.34375 -5.546875 C 4.328125 -5.546875 5.09375 -4.734375 5.09375 -3.703125 C 5.09375 -3.671875 5.09375 -3.640625 5.078125 -3.625 Z M 1.546875 -3.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 0.828125 -6.28125 L 0.828125 0 L 1.84375 0 L 1.84375 -3.265625 C 1.84375 -4.15625 2.0625 -4.75 2.546875 -5.09375 C 2.859375 -5.328125 3.15625 -5.40625 3.859375 -5.40625 L 3.859375 -6.4375 C 3.6875 -6.453125 3.59375 -6.46875 3.46875 -6.46875 C 2.8125 -6.46875 2.328125 -6.078125 1.75 -5.140625 L 1.75 -6.28125 Z M 0.828125 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 6.421875 -0.59375 C 6.3125 -0.5625 6.265625 -0.5625 6.203125 -0.5625 C 5.859375 -0.5625 5.65625 -0.75 5.65625 -1.0625 L 5.65625 -4.75 C 5.65625 -5.875 4.84375 -6.46875 3.296875 -6.46875 C 2.390625 -6.46875 1.625 -6.203125 1.21875 -5.734375 C 0.921875 -5.40625 0.796875 -5.046875 0.78125 -4.421875 L 1.78125 -4.421875 C 1.875 -5.203125 2.328125 -5.546875 3.265625 -5.546875 C 4.15625 -5.546875 4.671875 -5.203125 4.671875 -4.609375 L 4.671875 -4.34375 C 4.671875 -3.921875 4.421875 -3.75 3.625 -3.640625 C 2.203125 -3.46875 1.984375 -3.421875 1.609375 -3.265625 C 0.875 -2.96875 0.5 -2.40625 0.5 -1.578125 C 0.5 -0.4375 1.296875 0.28125 2.5625 0.28125 C 3.359375 0.28125 4 0 4.703125 -0.640625 C 4.78125 -0.015625 5.09375 0.28125 5.734375 0.28125 C 5.9375 0.28125 6.09375 0.25 6.421875 0.171875 Z M 4.671875 -1.984375 C 4.671875 -1.640625 4.578125 -1.4375 4.265625 -1.15625 C 3.859375 -0.796875 3.375 -0.59375 2.78125 -0.59375 C 2 -0.59375 1.546875 -0.96875 1.546875 -1.609375 C 1.546875 -2.265625 1.984375 -2.609375 3.0625 -2.765625 C 4.109375 -2.90625 4.328125 -2.953125 4.671875 -3.109375 Z M 4.671875 -1.984375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 3.265625 -6.46875 C 1.5 -6.46875 0.4375 -5.203125 0.4375 -3.09375 C 0.4375 -0.984375 1.484375 0.28125 3.28125 0.28125 C 5.046875 0.28125 6.125 -0.984375 6.125 -3.046875 C 6.125 -5.21875 5.078125 -6.46875 3.265625 -6.46875 Z M 3.28125 -5.546875 C 4.40625 -5.546875 5.078125 -4.625 5.078125 -3.0625 C 5.078125 -1.578125 4.375 -0.640625 3.28125 -0.640625 C 2.15625 -0.640625 1.46875 -1.578125 1.46875 -3.09375 C 1.46875 -4.609375 2.15625 -5.546875 3.28125 -5.546875 Z M 3.28125 -5.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.84375 -6.28125 L 0.84375 0 L 1.84375 0 L 1.84375 -3.46875 C 1.84375 -4.75 2.515625 -5.59375 3.546875 -5.59375 C 4.34375 -5.59375 4.84375 -5.109375 4.84375 -4.359375 L 4.84375 0 L 5.84375 0 L 5.84375 -4.75 C 5.84375 -5.796875 5.0625 -6.46875 3.859375 -6.46875 C 2.921875 -6.46875 2.3125 -6.109375 1.765625 -5.234375 L 1.765625 -6.28125 Z M 0.84375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M -3.75 -3.40625 L -3.75 -0.546875 L -2.875 -0.546875 L -2.875 -3.40625 Z M -3.75 -3.40625 "/>
</symbol>
<symbol overflow="visible" id="glyph1-2">
<path style="stroke:none;" d="M -3.90625 -2.65625 L -3.90625 -3.234375 C -3.90625 -4.390625 -3.390625 -4.984375 -2.359375 -4.984375 C -1.296875 -4.984375 -0.65625 -4.328125 -0.65625 -3.234375 C -0.65625 -2.078125 -1.234375 -1.515625 -2.46875 -1.4375 L -2.46875 -0.390625 C -1.78125 -0.4375 -1.34375 -0.546875 -0.953125 -0.75 C -0.140625 -1.1875 0.28125 -2.03125 0.28125 -3.1875 C 0.28125 -4.9375 -0.765625 -6.078125 -2.375 -6.078125 C -3.453125 -6.078125 -4.0625 -5.65625 -4.40625 -4.625 C -4.71875 -5.421875 -5.3125 -5.8125 -6.171875 -5.8125 C -7.625 -5.8125 -8.515625 -4.84375 -8.515625 -3.234375 C -8.515625 -1.515625 -7.578125 -0.59375 -5.765625 -0.5625 L -5.765625 -1.625 C -6.28125 -1.625 -6.5625 -1.6875 -6.828125 -1.8125 C -7.296875 -2.046875 -7.578125 -2.578125 -7.578125 -3.234375 C -7.578125 -4.171875 -7.03125 -4.734375 -6.125 -4.734375 C -5.53125 -4.734375 -5.171875 -4.53125 -4.984375 -4.0625 C -4.859375 -3.765625 -4.8125 -3.390625 -4.796875 -2.65625 Z M -3.90625 -2.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph1-3">
<path style="stroke:none;" d="M -2.8125 -6.15625 C -3.765625 -6.15625 -4.34375 -6.078125 -4.8125 -5.90625 C -5.84375 -5.5 -6.46875 -4.53125 -6.46875 -3.359375 C -6.46875 -1.609375 -5.125 -0.484375 -3.0625 -0.484375 C -1 -0.484375 0.28125 -1.578125 0.28125 -3.34375 C 0.28125 -4.78125 -0.546875 -5.765625 -1.90625 -6.03125 L -1.90625 -5.015625 C -1.078125 -4.734375 -0.640625 -4.171875 -0.640625 -3.375 C -0.640625 -2.734375 -0.9375 -2.203125 -1.46875 -1.859375 C -1.828125 -1.625 -2.1875 -1.53125 -2.8125 -1.53125 Z M -3.625 -1.546875 C -4.78125 -1.625 -5.546875 -2.34375 -5.546875 -3.34375 C -5.546875 -4.328125 -4.734375 -5.09375 -3.703125 -5.09375 C -3.671875 -5.09375 -3.640625 -5.09375 -3.625 -5.078125 Z M -3.625 -1.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-4">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-5">
<path style="stroke:none;" d="M -2.046875 -3.921875 L 0 -3.921875 L 0 -4.984375 L -2.046875 -4.984375 L -2.046875 -6.234375 L -2.984375 -6.234375 L -2.984375 -4.984375 L -8.515625 -4.984375 L -8.515625 -4.203125 L -3.15625 -0.34375 L -2.046875 -0.34375 Z M -2.984375 -3.921875 L -2.984375 -1.265625 L -6.703125 -3.921875 Z M -2.984375 -3.921875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-6">
<path style="stroke:none;" d="M -6.0625 -3.109375 L 0 -3.109375 L 0 -4.15625 L -8.515625 -4.15625 L -8.515625 -3.46875 C -7.203125 -3.09375 -7.015625 -2.859375 -6.8125 -1.21875 L -6.0625 -1.21875 Z M -6.0625 -3.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph1-7">
<path style="stroke:none;" d="M -6.28125 -0.84375 L 0 -0.84375 L 0 -1.84375 L -3.953125 -1.84375 C -4.859375 -1.84375 -5.59375 -2.515625 -5.59375 -3.328125 C -5.59375 -4.0625 -5.140625 -4.484375 -4.328125 -4.484375 L 0 -4.484375 L 0 -5.5 L -3.953125 -5.5 C -4.859375 -5.5 -5.59375 -6.15625 -5.59375 -6.96875 C -5.59375 -7.703125 -5.125 -8.140625 -4.328125 -8.140625 L 0 -8.140625 L 0 -9.140625 L -4.71875 -9.140625 C -5.84375 -9.140625 -6.46875 -8.5 -6.46875 -7.3125 C -6.46875 -6.484375 -6.21875 -5.96875 -5.515625 -5.390625 C -6.1875 -5.015625 -6.46875 -4.515625 -6.46875 -3.703125 C -6.46875 -2.859375 -6.15625 -2.296875 -5.40625 -1.765625 L -6.28125 -1.765625 Z M -6.28125 -0.84375 "/>
</symbol>
</g>
</defs>
<g id="surface812">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 108.6875 L 63.625 108.6875 L 64.136719 112.957031 L 64.648438 81.234375 L 65.160156 116.835938 L 65.671875 116.835938 L 66.183594 115.300781 L 66.695312 115.300781 L 67.207031 105.648438 L 67.71875 108.683594 L 68.230469 109.792969 L 68.742188 123.273438 L 69.253906 133.070312 L 69.765625 103.078125 L 70.277344 95.515625 L 70.789062 101.070312 L 71.300781 112.007812 L 71.8125 113.300781 L 72.324219 134.871094 L 72.835938 112.398438 L 73.347656 113.054688 L 73.859375 113.640625 L 74.375 114.550781 L 74.886719 114.652344 L 75.398438 114.328125 L 75.910156 113.644531 L 76.421875 114.804688 L 76.933594 113.152344 L 77.445312 116.574219 L 77.957031 120.980469 L 78.46875 101.449219 L 78.980469 122.082031 L 79.492188 107.105469 L 80.003906 111.988281 L 80.515625 110.136719 L 81.027344 115.3125 L 81.539062 119.90625 L 82.050781 115.476562 L 82.5625 114.054688 L 83.074219 115.042969 L 83.585938 109.324219 L 84.097656 113.335938 L 84.609375 111.5 L 85.121094 111.3125 L 85.632812 114.902344 L 86.144531 114.316406 L 86.65625 116.808594 L 87.167969 113.96875 L 87.679688 115.75 L 88.191406 100.84375 L 88.703125 106.488281 L 89.214844 107.367188 L 89.726562 62.132812 L 90.238281 90.234375 L 90.75 81.921875 L 91.261719 139.464844 L 91.773438 98.796875 L 92.285156 119.003906 L 92.796875 128.152344 L 93.308594 128.242188 L 93.820312 111.101562 L 94.332031 108.371094 L 94.84375 123.121094 L 95.355469 94.195312 L 95.867188 102.722656 L 96.378906 111.539062 L 96.890625 109.695312 L 97.402344 115.1875 L 97.914062 105.582031 L 98.425781 110.367188 L 98.9375 116.082031 L 99.449219 121.296875 L 99.960938 118.316406 L 100.472656 96.609375 L 100.984375 82.054688 L 101.496094 97.039062 L 102.007812 117.417969 L 102.519531 110.566406 L 103.03125 121.214844 L 103.542969 105.5625 L 104.054688 96.832031 L 104.566406 121.839844 L 105.082031 113.652344 L 105.59375 101.308594 L 106.105469 92.6875 L 106.617188 103.6875 L 107.128906 122.167969 L 107.640625 110.964844 L 108.152344 114.988281 L 108.664062 93.929688 L 109.175781 122.996094 L 109.6875 109.765625 L 110.199219 125.335938 L 110.710938 131.332031 L 111.222656 111.433594 L 111.734375 97.613281 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 60.554688 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 70.789062 142.558594 L 70.789062 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 81.027344 142.558594 L 81.027344 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 91.261719 142.558594 L 91.261719 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 101.496094 142.558594 L 101.496094 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="57.054688" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-2" x="84.261719" y="167.916016"/>
  <use xlink:href="#glyph0-1" x="90.933594" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 141.878906 L 59.039062 64.4375 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 141.878906 L 51.839844 141.878906 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 130.8125 L 51.839844 130.8125 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 119.75 L 51.839844 119.75 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 108.6875 L 51.839844 108.6875 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 97.625 L 51.839844 97.625 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 86.5625 L 51.839844 86.5625 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 75.5 L 51.839844 75.5 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 64.4375 L 51.839844 64.4375 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="41.197266" y="159.378906"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="155.382812"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="148.710938"/>
  <use xlink:href="#glyph1-1" x="41.197266" y="142.039062"/>
  <use xlink:href="#glyph1-4" x="41.197266" y="138.042969"/>
  <use xlink:href="#glyph1-5" x="41.197266" y="131.371094"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-6" x="41.197266" y="113.125"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="106.453125"/>
  <use xlink:href="#glyph1-1" x="41.197266" y="99.78125"/>
  <use xlink:href="#glyph1-4" x="41.197266" y="95.785156"/>
  <use xlink:href="#glyph1-5" x="41.197266" y="89.113281"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 142.558594 L 113.761719 142.558594 L 113.761719 59.039062 L 59.039062 59.039062 L 59.039062 142.558594 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-3" x="64.898438" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="67.5625" y="196.716797"/>
  <use xlink:href="#glyph0-5" x="70.898438" y="196.716797"/>
  <use xlink:href="#glyph0-6" x="77.570312" y="196.716797"/>
  <use xlink:href="#glyph0-7" x="81.566406" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="88.238281" y="196.716797"/>
  <use xlink:href="#glyph0-3" x="91.574219" y="196.716797"/>
  <use xlink:href="#glyph0-8" x="94.238281" y="196.716797"/>
  <use xlink:href="#glyph0-9" x="100.910156" y="196.716797"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-7" x="12.396484" y="105.800781"/>
</g>
</g>
</svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 5.96875 -6.28125 C 5.765625 -7.6875 4.859375 -8.515625 3.5625 -8.515625 C 2.625 -8.515625 1.78125 -8.046875 1.28125 -7.296875 C 0.75 -6.46875 0.515625 -5.421875 0.515625 -3.875 C 0.515625 -2.453125 0.734375 -1.53125 1.234375 -0.78125 C 1.6875 -0.09375 2.4375 0.28125 3.375 0.28125 C 4.984375 0.28125 6.15625 -0.921875 6.15625 -2.59375 C 6.15625 -4.171875 5.078125 -5.296875 3.546875 -5.296875 C 2.71875 -5.296875 2.046875 -4.96875 1.59375 -4.34375 C 1.609375 -6.421875 2.28125 -7.578125 3.484375 -7.578125 C 4.234375 -7.578125 4.75 -7.109375 4.921875 -6.28125 Z M 3.421875 -4.359375 C 4.4375 -4.359375 5.078125 -3.640625 5.078125 -2.515625 C 5.078125 -1.4375 4.359375 -0.65625 3.390625 -0.65625 C 2.40625 -0.65625 1.65625 -1.46875 1.65625 -2.5625 C 1.65625 -3.625 2.375 -4.359375 3.421875 -4.359375 Z M 3.421875 -4.359375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 1.796875 -6.28125 L 0.796875 -6.28125 L 0.796875 0 L 1.796875 0 Z M 1.796875 -8.75 L 0.796875 -8.75 L 0.796875 -7.484375 L 1.796875 -7.484375 Z M 1.796875 -8.75 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 3.046875 -6.28125 L 2.015625 -6.28125 L 2.015625 -8.015625 L 1.015625 -8.015625 L 1.015625 -6.28125 L 0.171875 -6.28125 L 0.171875 -5.46875 L 1.015625 -5.46875 L 1.015625 -0.71875 C 1.015625 -0.078125 1.453125 0.28125 2.234375 0.28125 C 2.46875 0.28125 2.71875 0.25 3.046875 0.1875 L 3.046875 -0.640625 C 2.921875 -0.609375 2.765625 -0.59375 2.5625 -0.59375 C 2.140625 -0.59375 2.015625 -0.71875 2.015625 -1.15625 L 2.015625 -5.46875 L 3.046875 -5.46875 Z M 3.046875 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 6.15625 -2.8125 C 6.15625 -3.765625 6.078125 -4.34375 5.90625 -4.8125 C 5.5 -5.84375 4.53125 -6.46875 3.359375 -6.46875 C 1.609375 -6.46875 0.484375 -5.125 0.484375 -3.0625 C 0.484375 -1 1.578125 0.28125 3.34375 0.28125 C 4.78125 0.28125 5.765625 -0.546875 6.03125 -1.90625 L 5.015625 -1.90625 C 4.734375 -1.078125 4.171875 -0.640625 3.375 -0.640625 C 2.734375 -0.640625 2.203125 -0.9375 1.859375 -1.46875 C 1.625 -1.828125 1.53125 -2.1875 1.53125 -2.8125 Z M 1.546875 -3.625 C 1.625 -4.78125 2.34375 -5.546875 3.34375 -5.546875 C 4.328125 -5.546875 5.09375 -4.734375 5.09375 -3.703125 C 5.09375 -3.671875 5.09375 -3.640625 5.078125 -3.625 Z M 1.546875 -3.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 0.828125 -6.28125 L 0.828125 0 L 1.84375 0 L 1.84375 -3.265625 C 1.84375 -4.15625 2.0625 -4.75 2.546875 -5.09375 C 2.859375 -5.328125 3.15625 -5.40625 3.859375 -5.40625 L 3.859375 -6.4375 C 3.6875 -6.453125 3.59375 -6.46875 3.46875 -6.46875 C 2.8125 -6.46875 2.328125 -6.078125 1.75 -5.140625 L 1.75 -6.28125 Z M 0.828125 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 6.421875 -0.59375 C 6.3125 -0.5625 6.265625 -0.5625 6.203125 -0.5625 C 5.859375 -0.5625 5.65625 -0.75 5.65625 -1.0625 L 5.65625 -4.75 C 5.65625 -5.875 4.84375 -6.46875 3.296875 -6.46875 C 2.390625 -6.46875 1.625 -6.203125 1.21875 -5.734375 C 0.921875 -5.40625 0.796875 -5.046875 0.78125 -4.421875 L 1.78125 -4.421875 C 1.875 -5.203125 2.328125 -5.546875 3.265625 -5.546875 C 4.15625 -5.546875 4.671875 -5.203125 4.671875 -4.609375 L 4.671875 -4.34375 C 4.671875 -3.921875 4.421875 -3.75 3.625 -3.640625 C 2.203125 -3.46875 1.984375 -3.421875 1.609375 -3.265625 C 0.875 -2.96875 0.5 -2.40625 0.5 -1.578125 C 0.5 -0.4375 1.296875 0.28125 2.5625 0.28125 C 3.359375 0.28125 4 0 4.703125 -0.640625 C 4.78125 -0.015625 5.09375 0.28125 5.734375 0.28125 C 5.9375 0.28125 6.09375 0.25 6.421875 0.171875 Z M 4.671875 -1.984375 C 4.671875 -1.640625 4.578125 -1.4375 4.265625 -1.15625 C 3.859375 -0.796875 3.375 -0.59375 2.78125 -0.59375 C 2 -0.59375 1.546875 -0.96875 1.546875 -1.609375 C 1.546875 -2.265625 1.984375 -2.609375 3.0625 -2.765625 C 4.109375 -2.90625 4.328125 -2.953125 4.671875 -3.109375 Z M 4.671875 -1.984375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 3.265625 -6.46875 C 1.5 -6.46875 0.4375 -5.203125 0.4375 -3.09375 C 0.4375 -0.984375 1.484375 0.28125 3.28125 0.28125 C 5.046875 0.28125 6.125 -0.984375 6.125 -3.046875 C 6.125 -5.21875 5.078125 -6.46875 3.265625 -6.46875 Z M 3.28125 -5.546875 C 4.40625 -5.546875 5.078125 -4.625 5.078125 -3.0625 C 5.078125 -1.578125 4.375 -0.640625 3.28125 -0.640625 C 2.15625 -0.640625 1.46875 -1.578125 1.46875 -3.09375 C 1.46875 -4.609375 2.15625 -5.546875 3.28125 -5.546875 Z M 3.28125 -5.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.84375 -6.28125 L 0.84375 0 L 1.84375 0 L 1.84375 -3.46875 C 1.84375 -4.75 2.515625 -5.59375 3.546875 -5.59375 C 4.34375 -5.59375 4.84375 -5.109375 4.84375 -4.359375 L 4.84375 0 L 5.84375 0 L 5.84375 -4.75 C 5.84375 -5.796875 5.0625 -6.46875 3.859375 -6.46875 C 2.921875 -6.46875 2.3125 -6.109375 1.765625 -5.234375 L 1.765625 -6.28125 Z M 0.84375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-2">
<path style="stroke:none;" d="M -1.25 -2.296875 L -1.25 -1.046875 L 0 -1.046875 L 0 -2.296875 Z M -1.25 -2.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-3">
<path style="stroke:none;" d="M -3.90625 -2.65625 L -3.90625 -3.234375 C -3.90625 -4.390625 -3.390625 -4.984375 -2.359375 -4.984375 C -1.296875 -4.984375 -0.65625 -4.328125 -0.65625 -3.234375 C -0.65625 -2.078125 -1.234375 -1.515625 -2.46875 -1.4375 L -2.46875 -0.390625 C -1.78125 -0.4375 -1.34375 -0.546875 -0.953125 -0.75 C -0.140625 -1.1875 0.28125 -2.03125 0.28125 -3.1875 C 0.28125 -4.9375 -0.765625 -6.078125 -2.375 -6.078125 C -3.453125 -6.078125 -4.0625 -5.65625 -4.40625 -4.625 C -4.71875 -5.421875 -5.3125 -5.8125 -6.171875 -5.8125 C -7.625 -5.8125 -8.515625 -4.84375 -8.515625 -3.234375 C -8.515625 -1.515625 -7.578125 -0.59375 -5.765625 -0.5625 L -5.765625 -1.625 C -6.28125 -1.625 -6.5625 -1.6875 -6.828125 -1.8125 C -7.296875 -2.046875 -7.578125 -2.578125 -7.578125 -3.234375 C -7.578125 -4.171875 -7.03125 -4.734375 -6.125 -4.734375 C -5.53125 -4.734375 -5.171875 -4.53125 -4.984375 -4.0625 C -4.859375 -3.765625 -4.8125 -3.390625 -4.796875 -2.65625 Z M -3.90625 -2.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph1-4">
<path style="stroke:none;" d="M -8.515625 -5.71875 L -8.515625 -1.3125 L -3.875 -0.6875 L -3.875 -1.65625 C -4.46875 -2.140625 -4.671875 -2.5625 -4.671875 -3.21875 C -4.671875 -4.359375 -3.890625 -5.078125 -2.625 -5.078125 C -1.40625 -5.078125 -0.65625 -4.375 -0.65625 -3.21875 C -0.65625 -2.296875 -1.125 -1.734375 -2.09375 -1.46875 L -2.09375 -0.421875 C -1.390625 -0.5625 -1.0625 -0.6875 -0.75 -0.9375 C -0.09375 -1.421875 0.28125 -2.28125 0.28125 -3.234375 C 0.28125 -4.953125 -0.96875 -6.15625 -2.765625 -6.15625 C -4.453125 -6.15625 -5.609375 -5.046875 -5.609375 -3.40625 C -5.609375 -2.8125 -5.453125 -2.328125 -5.09375 -1.84375 L -7.46875 -2.171875 L -7.46875 -5.71875 Z M -8.515625 -5.71875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-5">
<path style="stroke:none;" d="M -2.046875 -3.921875 L 0 -3.921875 L 0 -4.984375 L -2.046875 -4.984375 L -2.046875 -6.234375 L -2.984375 -6.234375 L -2.984375 -4.984375 L -8.515625 -4.984375 L -8.515625 -4.203125 L -3.15625 -0.34375 L -2.046875 -0.34375 Z M -2.984375 -3.921875 L -2.984375 -1.265625 L -6.703125 -3.921875 Z M -2.984375 -3.921875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M -4.953125 -7.0625 L -6 -7.0625 L -6 -4.328125 C -6 -3.390625 -5.890625 -2.734375 -5.65625 -2.1875 C -5.125 -1.015625 -4.1875 -0.359375 -3.078125 -0.359375 C -2.296875 -0.359375 -1.5 -0.65625 -0.875 -1.21875 C -0.15625 -1.84375 0.15625 -2.515625 0.15625 -3.46875 C 0.15625 -4.28125 -0.09375 -4.984375 -0.59375 -5.53125 C -1.078125 -6.078125 -1.765625 -6.390625 -2.40625 -6.390625 C -3.328125 -6.390625 -4.21875 -5.703125 -4.953125 -4.421875 Z M -4.953125 -3.859375 C -3.890625 -4.890625 -3.4375 -5.125 -2.453125 -5.125 C -1.203125 -5.125 -0.359375 -4.53125 -0.359375 -3.640625 C -0.359375 -2.53125 -1.578125 -1.625 -3.046875 -1.625 C -4.203125 -1.625 -4.953125 -2.359375 -4.953125 -3.484375 Z M -4.953125 -3.859375 "/>
</symbol>
<symbol overflow="visible" id="glyph3-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph3-1">
<path style="stroke:none;" d="M -2.28125 -2.453125 L -4.40625 -3.9375 L -4.40625 -3.140625 L -2.8125 -2.078125 L -4.40625 -1.03125 L -4.40625 -0.234375 L -2.25 -1.703125 L 0 -0.140625 L 0 -0.9375 L -1.6875 -2.0625 L 0 -3.15625 L 0 -3.96875 Z M -2.28125 -2.453125 "/>
</symbol>
</g>
</defs>
<g id="surface817">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 117.183594 L 61.578125 96.921875 L 62.089844 121.074219 L 62.601562 121.949219 L 63.113281 123.726562 L 63.625 139.464844 L 64.136719 122.265625 L 64.648438 105.03125 L 65.160156 113.210938 L 65.671875 115.871094 L 66.183594 116.375 L 66.695312 123.339844 L 67.207031 87.914062 L 67.71875 104.332031 L 68.230469 103.324219 L 68.742188 112.851562 L 69.253906 100.457031 L 69.765625 111.664062 L 70.277344 114.28125 L 70.789062 112.644531 L 71.300781 91.660156 L 71.8125 66.6875 L 72.324219 100.097656 L 72.835938 102.015625 L 73.347656 97.617188 L 73.859375 94.363281 L 74.375 91.464844 L 74.886719 78.246094 L 75.398438 98.609375 L 75.910156 72.320312 L 76.421875 90.808594 L 76.933594 79.480469 L 77.445312 113.71875 L 77.957031 82.398438 L 78.46875 85.777344 L 78.980469 104.027344 L 79.492188 83.769531 L 80.003906 104.457031 L 80.515625 111.378906 L 81.027344 93.09375 L 81.539062 107.171875 L 82.050781 113.71875 L 82.5625 92.035156 L 83.074219 84.101562 L 83.585938 78.109375 L 84.097656 83.578125 L 84.609375 85.558594 L 85.121094 98.488281 L 85.632812 105.609375 L 86.144531 91.96875 L 86.65625 126.101562 L 87.167969 62.132812 L 87.679688 113.734375 L 88.191406 91.191406 L 88.703125 104.550781 L 89.214844 89.878906 L 89.726562 114.628906 L 90.238281 103.335938 L 90.75 86.5 L 91.261719 116.042969 L 91.773438 85.074219 L 92.285156 106.855469 L 92.796875 90.121094 L 93.308594 111.359375 L 93.820312 83.898438 L 94.332031 99.351562 L 94.84375 98.207031 L 95.355469 103.148438 L 95.867188 98.816406 L 96.378906 81.972656 L 96.890625 98.9375 L 97.402344 103.890625 L 97.914062 96.96875 L 98.425781 107.292969 L 98.9375 116.011719 L 99.449219 110.808594 L 99.960938 92.9375 L 100.472656 108.054688 L 100.984375 86.40625 L 101.496094 102.480469 L 102.007812 97.070312 L 102.519531 112.832031 L 103.03125 100.546875 L 103.542969 103.910156 L 104.054688 109.957031 L 104.566406 92.820312 L 105.082031 124.5 L 105.59375 113.34375 L 106.105469 83.800781 L 106.617188 105.808594 L 107.128906 109.433594 L 107.640625 108.601562 L 108.152344 92.765625 L 108.664062 111.988281 L 109.175781 79.785156 L 109.6875 88.273438 L 110.199219 109.542969 L 110.710938 93.625 L 111.222656 72.859375 L 111.734375 87.082031 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 60.554688 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 70.789062 142.558594 L 70.789062 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 81.027344 142.558594 L 81.027344 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 91.261719 142.558594 L 91.261719 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 101.496094 142.558594 L 101.496094 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="57.054688" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-2" x="84.261719" y="167.916016"/>
  <use xlink:href="#glyph0-1" x="90.933594" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 118.410156 L 59.039062 66.847656 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 118.410156 L 51.839844 118.410156 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 92.628906 L 51.839844 92.628906 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 66.847656 L 51.839844 66.847656 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="41.197266" y="130.410156"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="123.738281"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="120.402344"/>
  <use xlink:href="#glyph1-4" x="41.197266" y="113.730469"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="41.197266" y="78.847656"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="72.175781"/>
  <use xlink:href="#glyph1-5" x="41.197266" y="68.839844"/>
  <use xlink:href="#glyph1-4" x="41.197266" y="62.167969"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 142.558594 L 113.761719 142.558594 L 113.761719 59.039062 L 59.039062 59.039062 L 59.039062 142.558594 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-3" x="64.898438" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="67.5625" y="196.716797"/>
  <use xlink:href="#glyph0-5" x="70.898438" y="196.716797"/>
  <use xlink:href="#glyph0-6" x="77.570312" y="196.716797"/>
  <use xlink:href="#glyph0-7" x="81.566406" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="88.238281" y="196.716797"/>
  <use xlink:href="#glyph0-3" x="91.574219" y="196.716797"/>
  <use xlink:href="#glyph0-8" x="94.238281" y="196.716797"/>
  <use xlink:href="#glyph0-9" x="100.910156" y="196.716797"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="9.631836" y="107.300781"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-1" x="11.96582" y="99.300781"/>
</g>
</g>
</svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 5.96875 -6.28125 C 5.765625 -7.6875 4.859375 -8.515625 3.5625 -8.515625 C 2.625 -8.515625 1.78125 -8.046875 1.28125 -7.296875 C 0.75 -6.46875 0.515625 -5.421875 0.515625 -3.875 C 0.515625 -2.453125 0.734375 -1.53125 1.234375 -0.78125 C 1.6875 -0.09375 2.4375 0.28125 3.375 0.28125 C 4.984375 0.28125 6.15625 -0.921875 6.15625 -2.59375 C 6.15625 -4.171875 5.078125 -5.296875 3.546875 -5.296875 C 2.71875 -5.296875 2.046875 -4.96875 1.59375 -4.34375 C 1.609375 -6.421875 2.28125 -7.578125 3.484375 -7.578125 C 4.234375 -7.578125 4.75 -7.109375 4.921875 -6.28125 Z M 3.421875 -4.359375 C 4.4375 -4.359375 5.078125 -3.640625 5.078125 -2.515625 C 5.078125 -1.4375 4.359375 -0.65625 3.390625 -0.65625 C 2.40625 -0.65625 1.65625 -1.46875 1.65625 -2.5625 C 1.65625 -3.625 2.375 -4.359375 3.421875 -4.359375 Z M 3.421875 -4.359375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 1.796875 -6.28125 L 0.796875 -6.28125 L 0.796875 0 L 1.796875 0 Z M 1.796875 -8.75 L 0.796875 -8.75 L 0.796875 -7.484375 L 1.796875 -7.484375 Z M 1.796875 -8.75 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 3.046875 -6.28125 L 2.015625 -6.28125 L 2.015625 -8.015625 L 1.015625 -8.015625 L 1.015625 -6.28125 L 0.171875 -6.28125 L 0.171875 -5.46875 L 1.015625 -5.46875 L 1.015625 -0.71875 C 1.015625 -0.078125 1.453125 0.28125 2.234375 0.28125 C 2.46875 0.28125 2.71875 0.25 3.046875 0.1875 L 3.046875 -0.640625 C 2.921875 -0.609375 2.765625 -0.59375 2.5625 -0.59375 C 2.140625 -0.59375 2.015625 -0.71875 2.015625 -1.15625 L 2.015625 -5.46875 L 3.046875 -5.46875 Z M 3.046875 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 6.15625 -2.8125 C 6.15625 -3.765625 6.078125 -4.34375 5.90625 -4.8125 C 5.5 -5.84375 4.53125 -6.46875 3.359375 -6.46875 C 1.609375 -6.46875 0.484375 -5.125 0.484375 -3.0625 C 0.484375 -1 1.578125 0.28125 3.34375 0.28125 C 4.78125 0.28125 5.765625 -0.546875 6.03125 -1.90625 L 5.015625 -1.90625 C 4.734375 -1.078125 4.171875 -0.640625 3.375 -0.640625 C 2.734375 -0.640625 2.203125 -0.9375 1.859375 -1.46875 C 1.625 -1.828125 1.53125 -2.1875 1.53125 -2.8125 Z M 1.546875 -3.625 C 1.625 -4.78125 2.34375 -5.546875 3.34375 -5.546875 C 4.328125 -5.546875 5.09375 -4.734375 5.09375 -3.703125 C 5.09375 -3.671875 5.09375 -3.640625 5.078125 -3.625 Z M 1.546875 -3.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 0.828125 -6.28125 L 0.828125 0 L 1.84375 0 L 1.84375 -3.265625 C 1.84375 -4.15625 2.0625 -4.75 2.546875 -5.09375 C 2.859375 -5.328125 3.15625 -5.40625 3.859375 -5.40625 L 3.859375 -6.4375 C 3.6875 -6.453125 3.59375 -6.46875 3.46875 -6.46875 C 2.8125 -6.46875 2.328125 -6.078125 1.75 -5.140625 L 1.75 -6.28125 Z M 0.828125 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 6.421875 -0.59375 C 6.3125 -0.5625 6.265625 -0.5625 6.203125 -0.5625 C 5.859375 -0.5625 5.65625 -0.75 5.65625 -1.0625 L 5.65625 -4.75 C 5.65625 -5.875 4.84375 -6.46875 3.296875 -6.46875 C 2.390625 -6.46875 1.625 -6.203125 1.21875 -5.734375 C 0.921875 -5.40625 0.796875 -5.046875 0.78125 -4.421875 L 1.78125 -4.421875 C 1.875 -5.203125 2.328125 -5.546875 3.265625 -5.546875 C 4.15625 -5.546875 4.671875 -5.203125 4.671875 -4.609375 L 4.671875 -4.34375 C 4.671875 -3.921875 4.421875 -3.75 3.625 -3.640625 C 2.203125 -3.46875 1.984375 -3.421875 1.609375 -3.265625 C 0.875 -2.96875 0.5 -2.40625 0.5 -1.578125 C 0.5 -0.4375 1.296875 0.28125 2.5625 0.28125 C 3.359375 0.28125 4 0 4.703125 -0.640625 C 4.78125 -0.015625 5.09375 0.28125 5.734375 0.28125 C 5.9375 0.28125 6.09375 0.25 6.421875 0.171875 Z M 4.671875 -1.984375 C 4.671875 -1.640625 4.578125 -1.4375 4.265625 -1.15625 C 3.859375 -0.796875 3.375 -0.59375 2.78125 -0.59375 C 2 -0.59375 1.546875 -0.96875 1.546875 -1.609375 C 1.546875 -2.265625 1.984375 -2.609375 3.0625 -2.765625 C 4.109375 -2.90625 4.328125 -2.953125 4.671875 -3.109375 Z M 4.671875 -1.984375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 3.265625 -6.46875 C 1.5 -6.46875 0.4375 -5.203125 0.4375 -3.09375 C 0.4375 -0.984375 1.484375 0.28125 3.28125 0.28125 C 5.046875 0.28125 6.125 -0.984375 6.125 -3.046875 C 6.125 -5.21875 5.078125 -6.46875 3.265625 -6.46875 Z M 3.28125 -5.546875 C 4.40625 -5.546875 5.078125 -4.625 5.078125 -3.0625 C 5.078125 -1.578125 4.375 -0.640625 3.28125 -0.640625 C 2.15625 -0.640625 1.46875 -1.578125 1.46875 -3.09375 C 1.46875 -4.609375 2.15625 -5.546875 3.28125 -5.546875 Z M 3.28125 -5.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.84375 -6.28125 L 0.84375 0 L 1.84375 0 L 1.84375 -3.46875 C 1.84375 -4.75 2.515625 -5.59375 3.546875 -5.59375 C 4.34375 -5.59375 4.84375 -5.109375 4.84375 -4.359375 L 4.84375 0 L 5.84375 0 L 5.84375 -4.75 C 5.84375 -5.796875 5.0625 -6.46875 3.859375 -6.46875 C 2.921875 -6.46875 2.3125 -6.109375 1.765625 -5.234375 L 1.765625 -6.28125 Z M 0.84375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-2">
<path style="stroke:none;" d="M -1.25 -2.296875 L -1.25 -1.046875 L 0 -1.046875 L 0 -2.296875 Z M -1.25 -2.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-3">
<path style="stroke:none;" d="M -6.0625 -3.109375 L 0 -3.109375 L 0 -4.15625 L -8.515625 -4.15625 L -8.515625 -3.46875 C -7.203125 -3.09375 -7.015625 -2.859375 -6.8125 -1.21875 L -6.0625 -1.21875 Z M -6.0625 -3.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph1-4">
<path style="stroke:none;" d="M -8.515625 -5.71875 L -8.515625 -1.3125 L -3.875 -0.6875 L -3.875 -1.65625 C -4.46875 -2.140625 -4.671875 -2.5625 -4.671875 -3.21875 C -4.671875 -4.359375 -3.890625 -5.078125 -2.625 -5.078125 C -1.40625 -5.078125 -0.65625 -4.375 -0.65625 -3.21875 C -0.65625 -2.296875 -1.125 -1.734375 -2.09375 -1.46875 L -2.09375 -0.421875 C -1.390625 -0.5625 -1.0625 -0.6875 -0.75 -0.9375 C -0.09375 -1.421875 0.28125 -2.28125 0.28125 -3.234375 C 0.28125 -4.953125 -0.96875 -6.15625 -2.765625 -6.15625 C -4.453125 -6.15625 -5.609375 -5.046875 -5.609375 -3.40625 C -5.609375 -2.8125 -5.453125 -2.328125 -5.09375 -1.84375 L -7.46875 -2.171875 L -7.46875 -5.71875 Z M -8.515625 -5.71875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M -4.953125 -7.0625 L -6 -7.0625 L -6 -4.328125 C -6 -3.390625 -5.890625 -2.734375 -5.65625 -2.1875 C -5.125 -1.015625 -4.1875 -0.359375 -3.078125 -0.359375 C -2.296875 -0.359375 -1.5 -0.65625 -0.875 -1.21875 C -0.15625 -1.84375 0.15625 -2.515625 0.15625 -3.46875 C 0.15625 -4.28125 -0.09375 -4.984375 -0.59375 -5.53125 C -1.078125 -6.078125 -1.765625 -6.390625 -2.40625 -6.390625 C -3.328125 -6.390625 -4.21875 -5.703125 -4.953125 -4.421875 Z M -4.953125 -3.859375 C -3.890625 -4.890625 -3.4375 -5.125 -2.453125 -5.125 C -1.203125 -5.125 -0.359375 -4.53125 -0.359375 -3.640625 C -0.359375 -2.53125 -1.578125 -1.625 -3.046875 -1.625 C -4.203125 -1.625 -4.953125 -2.359375 -4.953125 -3.484375 Z M -4.953125 -3.859375 "/>
</symbol>
<symbol overflow="visible" id="glyph3-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph3-1">
<path style="stroke:none;" d="M -4.40625 -3.265625 L -0.96875 -2.046875 L -4.40625 -0.921875 L -4.40625 -0.171875 L 0.015625 -1.65625 L 0.71875 -1.390625 C 1.03125 -1.28125 1.140625 -1.125 1.140625 -0.828125 C 1.140625 -0.71875 1.125 -0.609375 1.09375 -0.453125 L 1.71875 -0.453125 C 1.796875 -0.59375 1.828125 -0.734375 1.828125 -0.921875 C 1.828125 -1.15625 1.75 -1.390625 1.625 -1.578125 C 1.46875 -1.796875 1.28125 -1.921875 0.921875 -2.0625 L -4.40625 -4.015625 Z M -4.40625 -3.265625 "/>
</symbol>
</g>
</defs>
<g id="surface822">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 62.132812 L 61.578125 95.085938 L 62.089844 81.707031 L 62.601562 62.71875 L 63.113281 97.613281 L 63.625 98.035156 L 64.136719 110.410156 L 64.648438 117.339844 L 65.160156 113.964844 L 65.671875 129.464844 L 66.183594 131.566406 L 66.695312 130.15625 L 67.207031 118.226562 L 67.71875 121.703125 L 68.230469 123.5 L 68.742188 127.488281 L 69.253906 128.296875 L 69.765625 127.914062 L 70.277344 104.066406 L 70.789062 113.226562 L 71.300781 132.253906 L 71.8125 133.359375 L 72.324219 127.113281 L 72.835938 135.9375 L 73.347656 134.238281 L 73.859375 137.59375 L 74.375 138.878906 L 74.886719 139.058594 L 75.398438 139.464844 L 75.910156 138.511719 L 76.421875 138.269531 L 76.933594 138.75 L 77.445312 137.191406 L 77.957031 135.496094 L 78.46875 131.980469 L 78.980469 130.542969 L 79.492188 130.945312 L 80.003906 127.378906 L 80.515625 134.09375 L 81.027344 137.035156 L 81.539062 134.332031 L 82.050781 130.675781 L 82.5625 136.605469 L 83.074219 132.808594 L 83.585938 137.460938 L 84.097656 138.074219 L 84.609375 138.113281 L 85.121094 138.488281 L 85.632812 139.042969 L 86.144531 137.753906 L 86.65625 132.441406 L 87.167969 132.242188 L 87.679688 130.851562 L 88.191406 132.527344 L 88.703125 129.011719 L 89.214844 127.699219 L 89.726562 120.222656 L 90.238281 124.109375 L 90.75 114.828125 L 91.261719 105.625 L 91.773438 120.667969 L 92.285156 125.285156 L 92.796875 127.757812 L 93.308594 125.691406 L 93.820312 129.78125 L 94.332031 130.453125 L 94.84375 128.296875 L 95.355469 121.933594 L 95.867188 117.253906 L 96.378906 130.511719 L 96.890625 127.660156 L 97.402344 125.839844 L 97.914062 123.292969 L 98.425781 109.027344 L 98.9375 108.132812 L 99.449219 111.484375 L 99.960938 114.433594 L 100.472656 122.136719 L 100.984375 125.988281 L 101.496094 130.695312 L 102.007812 133.539062 L 102.519531 126.089844 L 103.03125 127.363281 L 103.542969 122.953125 L 104.054688 117.730469 L 104.566406 126.234375 L 105.082031 129.015625 L 105.59375 111.558594 L 106.105469 112.875 L 106.617188 129.328125 L 107.128906 128.195312 L 107.640625 132.472656 L 108.152344 126.882812 L 108.664062 115.488281 L 109.175781 129.265625 L 109.6875 126.6875 L 110.199219 118.03125 L 110.710938 131.160156 L 111.222656 130.917969 L 111.734375 127.8125 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 60.554688 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 70.789062 142.558594 L 70.789062 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 81.027344 142.558594 L 81.027344 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 91.261719 142.558594 L 91.261719 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 101.496094 142.558594 L 101.496094 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="57.054688" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-2" x="84.261719" y="167.916016"/>
  <use xlink:href="#glyph0-1" x="90.933594" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 140.792969 L 59.039062 68.449219 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 140.792969 L 51.839844 140.792969 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 126.324219 L 51.839844 126.324219 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 111.855469 L 51.839844 111.855469 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 97.386719 L 51.839844 97.386719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 82.917969 L 51.839844 82.917969 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 68.449219 L 51.839844 68.449219 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="41.197266" y="152.792969"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="146.121094"/>
  <use xlink:href="#glyph1-1" x="41.197266" y="142.785156"/>
  <use xlink:href="#glyph1-1" x="41.197266" y="136.113281"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="41.197266" y="109.386719"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="102.714844"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="99.378906"/>
  <use xlink:href="#glyph1-4" x="41.197266" y="92.707031"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 142.558594 L 113.761719 142.558594 L 113.761719 59.039062 L 59.039062 59.039062 L 59.039062 142.558594 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-3" x="64.898438" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="67.5625" y="196.716797"/>
  <use xlink:href="#glyph0-5" x="70.898438" y="196.716797"/>
  <use xlink:href="#glyph0-6" x="77.570312" y="196.716797"/>
  <use xlink:href="#glyph0-7" x="81.566406" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="88.238281" y="196.716797"/>
  <use xlink:href="#glyph0-3" x="91.574219" y="196.716797"/>
  <use xlink:href="#glyph0-8" x="94.238281" y="196.716797"/>
  <use xlink:href="#glyph0-9" x="100.910156" y="196.716797"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="7.631836" y="107.300781"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-1" x="9.96582" y="99.300781"/>
</g>
</g>
</svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 5.96875 -6.28125 C 5.765625 -7.6875 4.859375 -8.515625 3.5625 -8.515625 C 2.625 -8.515625 1.78125 -8.046875 1.28125 -7.296875 C 0.75 -6.46875 0.515625 -5.421875 0.515625 -3.875 C 0.515625 -2.453125 0.734375 -1.53125 1.234375 -0.78125 C 1.6875 -0.09375 2.4375 0.28125 3.375 0.28125 C 4.984375 0.28125 6.15625 -0.921875 6.15625 -2.59375 C 6.15625 -4.171875 5.078125 -5.296875 3.546875 -5.296875 C 2.71875 -5.296875 2.046875 -4.96875 1.59375 -4.34375 C 1.609375 -6.421875 2.28125 -7.578125 3.484375 -7.578125 C 4.234375 -7.578125 4.75 -7.109375 4.921875 -6.28125 Z M 3.421875 -4.359375 C 4.4375 -4.359375 5.078125 -3.640625 5.078125 -2.515625 C 5.078125 -1.4375 4.359375 -0.65625 3.390625 -0.65625 C 2.40625 -0.65625 1.65625 -1.46875 1.65625 -2.5625 C 1.65625 -3.625 2.375 -4.359375 3.421875 -4.359375 Z M 3.421875 -4.359375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 1.796875 -6.28125 L 0.796875 -6.28125 L 0.796875 0 L 1.796875 0 Z M 1.796875 -8.75 L 0.796875 -8.75 L 0.796875 -7.484375 L 1.796875 -7.484375 Z M 1.796875 -8.75 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 3.046875 -6.28125 L 2.015625 -6.28125 L 2.015625 -8.015625 L 1.015625 -8.015625 L 1.015625 -6.28125 L 0.171875 -6.28125 L 0.171875 -5.46875 L 1.015625 -5.46875 L 1.015625 -0.71875 C 1.015625 -0.078125 1.453125 0.28125 2.234375 0.28125 C 2.46875 0.28125 2.71875 0.25 3.046875 0.1875 L 3.046875 -0.640625 C 2.921875 -0.609375 2.765625 -0.59375 2.5625 -0.59375 C 2.140625 -0.59375 2.015625 -0.71875 2.015625 -1.15625 L 2.015625 -5.46875 L 3.046875 -5.46875 Z M 3.046875 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 6.15625 -2.8125 C 6.15625 -3.765625 6.078125 -4.34375 5.90625 -4.8125 C 5.5 -5.84375 4.53125 -6.46875 3.359375 -6.46875 C 1.609375 -6.46875 0.484375 -5.125 0.484375 -3.0625 C 0.484375 -1 1.578125 0.28125 3.34375 0.28125 C 4.78125 0.28125 5.765625 -0.546875 6.03125 -1.90625 L 5.015625 -1.90625 C 4.734375 -1.078125 4.171875 -0.640625 3.375 -0.640625 C 2.734375 -0.640625 2.203125 -0.9375 1.859375 -1.46875 C 1.625 -1.828125 1.53125 -2.1875 1.53125 -2.8125 Z M 1.546875 -3.625 C 1.625 -4.78125 2.34375 -5.546875 3.34375 -5.546875 C 4.328125 -5.546875 5.09375 -4.734375 5.09375 -3.703125 C 5.09375 -3.671875 5.09375 -3.640625 5.078125 -3.625 Z M 1.546875 -3.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 0.828125 -6.28125 L 0.828125 0 L 1.84375 0 L 1.84375 -3.265625 C 1.84375 -4.15625 2.0625 -4.75 2.546875 -5.09375 C 2.859375 -5.328125 3.15625 -5.40625 3.859375 -5.40625 L 3.859375 -6.4375 C 3.6875 -6.453125 3.59375 -6.46875 3.46875 -6.46875 C 2.8125 -6.46875 2.328125 -6.078125 1.75 -5.140625 L 1.75 -6.28125 Z M 0.828125 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 6.421875 -0.59375 C 6.3125 -0.5625 6.265625 -0.5625 6.203125 -0.5625 C 5.859375 -0.5625 5.65625 -0.75 5.65625 -1.0625 L 5.65625 -4.75 C 5.65625 -5.875 4.84375 -6.46875 3.296875 -6.46875 C 2.390625 -6.46875 1.625 -6.203125 1.21875 -5.734375 C 0.921875 -5.40625 0.796875 -5.046875 0.78125 -4.421875 L 1.78125 -4.421875 C 1.875 -5.203125 2.328125 -5.546875 3.265625 -5.546875 C 4.15625 -5.546875 4.671875 -5.203125 4.671875 -4.609375 L 4.671875 -4.34375 C 4.671875 -3.921875 4.421875 -3.75 3.625 -3.640625 C 2.203125 -3.46875 1.984375 -3.421875 1.609375 -3.265625 C 0.875 -2.96875 0.5 -2.40625 0.5 -1.578125 C 0.5 -0.4375 1.296875 0.28125 2.5625 0.28125 C 3.359375 0.28125 4 0 4.703125 -0.640625 C 4.78125 -0.015625 5.09375 0.28125 5.734375 0.28125 C 5.9375 0.28125 6.09375 0.25 6.421875 0.171875 Z M 4.671875 -1.984375 C 4.671875 -1.640625 4.578125 -1.4375 4.265625 -1.15625 C 3.859375 -0.796875 3.375 -0.59375 2.78125 -0.59375 C 2 -0.59375 1.546875 -0.96875 1.546875 -1.609375 C 1.546875 -2.265625 1.984375 -2.609375 3.0625 -2.765625 C 4.109375 -2.90625 4.328125 -2.953125 4.671875 -3.109375 Z M 4.671875 -1.984375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 3.265625 -6.46875 C 1.5 -6.46875 0.4375 -5.203125 0.4375 -3.09375 C 0.4375 -0.984375 1.484375 0.28125 3.28125 0.28125 C 5.046875 0.28125 6.125 -0.984375 6.125 -3.046875 C 6.125 -5.21875 5.078125 -6.46875 3.265625 -6.46875 Z M 3.28125 -5.546875 C 4.40625 -5.546875 5.078125 -4.625 5.078125 -3.0625 C 5.078125 -1.578125 4.375 -0.640625 3.28125 -0.640625 C 2.15625 -0.640625 1.46875 -1.578125 1.46875 -3.09375 C 1.46875 -4.609375 2.15625 -5.546875 3.28125 -5.546875 Z M 3.28125 -5.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.84375 -6.28125 L 0.84375 0 L 1.84375 0 L 1.84375 -3.46875 C 1.84375 -4.75 2.515625 -5.59375 3.546875 -5.59375 C 4.34375 -5.59375 4.84375 -5.109375 4.84375 -4.359375 L 4.84375 0 L 5.84375 0 L 5.84375 -4.75 C 5.84375 -5.796875 5.0625 -6.46875 3.859375 -6.46875 C 2.921875 -6.46875 2.3125 -6.109375 1.765625 -5.234375 L 1.765625 -6.28125 Z M 0.84375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M -1.9375 -0.640625 C -0.546875 -0.84375 0.28125 -1.75 0.28125 -3.046875 C 0.28125 -3.984375 -0.1875 -4.84375 -0.9375 -5.328125 C -1.765625 -5.875 -2.8125 -6.109375 -4.359375 -6.109375 C -5.78125 -6.109375 -6.703125 -5.890625 -7.453125 -5.390625 C -8.140625 -4.921875 -8.515625 -4.171875 -8.515625 -3.234375 C -8.515625 -1.625 -7.3125 -0.453125 -5.640625 -0.453125 C -4.0625 -0.453125 -2.9375 -1.53125 -2.9375 -3.078125 C -2.9375 -3.875 -3.234375 -4.46875 -3.890625 -5.015625 C -1.8125 -5 -0.65625 -4.328125 -0.65625 -3.125 C -0.65625 -2.375 -1.125 -1.859375 -1.9375 -1.6875 Z M -7.578125 -3.234375 C -7.578125 -4.21875 -6.765625 -4.953125 -5.65625 -4.953125 C -4.625 -4.953125 -3.875 -4.21875 -3.875 -3.1875 C -3.875 -2.171875 -4.578125 -1.53125 -5.71875 -1.53125 C -6.796875 -1.53125 -7.578125 -2.25 -7.578125 -3.234375 Z M -7.578125 -3.234375 "/>
</symbol>
<symbol overflow="visible" id="glyph1-2">
<path style="stroke:none;" d="M -1.25 -2.296875 L -1.25 -1.046875 L 0 -1.046875 L 0 -2.296875 Z M -1.25 -2.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-3">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-4">
<path style="stroke:none;" d="M -6.0625 -3.109375 L 0 -3.109375 L 0 -4.15625 L -8.515625 -4.15625 L -8.515625 -3.46875 C -7.203125 -3.09375 -7.015625 -2.859375 -6.8125 -1.21875 L -6.0625 -1.21875 Z M -6.0625 -3.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M -8.234375 -3.171875 C -8.234375 -2.703125 -8.046875 -2.21875 -7.671875 -1.78125 C -7.015625 -0.953125 -5.71875 -0.515625 -4.03125 -0.515625 C -2.453125 -0.515625 -1.21875 -0.90625 -0.546875 -1.625 C -0.09375 -2.09375 0.15625 -2.65625 0.15625 -3.171875 C 0.15625 -3.640625 -0.03125 -4.109375 -0.40625 -4.5625 C -1.0625 -5.359375 -2.359375 -5.8125 -3.96875 -5.8125 C -5.609375 -5.8125 -6.84375 -5.4375 -7.53125 -4.71875 C -7.984375 -4.25 -8.234375 -3.703125 -8.234375 -3.171875 Z M -3.75 -4.578125 C -2.375 -4.5625 -1.59375 -4.421875 -0.953125 -4.0625 C -0.59375 -3.859375 -0.3125 -3.46875 -0.3125 -3.171875 C -0.3125 -2.859375 -0.59375 -2.46875 -0.953125 -2.265625 C -1.59375 -1.921875 -2.375 -1.78125 -3.75 -1.75 Z M -4.421875 -1.75 C -5.71875 -1.78125 -6.515625 -1.9375 -7.140625 -2.265625 C -7.5 -2.46875 -7.78125 -2.875 -7.78125 -3.171875 C -7.78125 -3.46875 -7.5 -3.859375 -7.140625 -4.0625 C -6.515625 -4.40625 -5.71875 -4.5625 -4.421875 -4.578125 Z M -4.421875 -1.75 "/>
</symbol>
</g>
</defs>
<g id="surface827">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 100.605469 L 61.578125 107.808594 L 62.089844 97.191406 L 62.601562 109.402344 L 63.113281 98.175781 L 63.625 101.519531 L 64.136719 98.144531 L 64.648438 107.515625 L 65.160156 101.882812 L 65.671875 126.90625 L 66.183594 98.863281 L 66.695312 111.773438 L 67.207031 96.394531 L 67.71875 106.167969 L 68.230469 110.488281 L 68.742188 94.21875 L 69.253906 90.238281 L 69.765625 98.648438 L 70.277344 96.644531 L 70.789062 92.667969 L 71.300781 79.371094 L 71.8125 88.742188 L 72.324219 101.476562 L 72.835938 110.273438 L 73.347656 106.765625 L 73.859375 92.617188 L 74.375 112.140625 L 74.886719 96.566406 L 75.398438 119.90625 L 75.910156 108.410156 L 76.421875 92.449219 L 76.933594 111.570312 L 77.445312 138.316406 L 77.957031 129.640625 L 78.46875 89.371094 L 78.980469 114.644531 L 79.492188 85.277344 L 80.003906 100.734375 L 80.515625 91.269531 L 81.027344 99.664062 L 81.539062 112.34375 L 82.050781 117.621094 L 82.5625 110.523438 L 83.074219 119.152344 L 83.585938 139.464844 L 84.097656 127.171875 L 84.609375 109.996094 L 85.121094 97.894531 L 85.632812 117.8125 L 86.144531 94.746094 L 86.65625 66.394531 L 87.167969 85.929688 L 87.679688 102.121094 L 88.191406 116.125 L 88.703125 116.15625 L 89.214844 104.195312 L 89.726562 81.078125 L 90.238281 75.625 L 90.75 103.84375 L 91.261719 101.40625 L 91.773438 98.136719 L 92.285156 99.890625 L 92.796875 101.53125 L 93.308594 105.867188 L 93.820312 100.605469 L 94.332031 96.246094 L 94.84375 62.132812 L 95.355469 105.542969 L 95.867188 100.871094 L 96.378906 102.988281 L 96.890625 91.492188 L 97.402344 96.429688 L 97.914062 118.390625 L 98.425781 98.714844 L 98.9375 103.996094 L 99.449219 104.4375 L 99.960938 91.929688 L 100.472656 102.117188 L 100.984375 89.257812 L 101.496094 87.039062 L 102.007812 93.722656 L 102.519531 105.335938 L 103.03125 105.113281 L 103.542969 83.710938 L 104.054688 79.324219 L 104.566406 100.164062 L 105.082031 104.425781 L 105.59375 104.222656 L 106.105469 104.75 L 106.617188 125.445312 L 107.128906 89.683594 L 107.640625 92.058594 L 108.152344 97.878906 L 108.664062 89.078125 L 109.175781 107.53125 L 109.6875 106.792969 L 110.199219 91.902344 L 110.710938 96.058594 L 111.222656 102.855469 L 111.734375 112.863281 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 60.554688 142.558594 L 60.554688 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 70.789062 142.558594 L 70.789062 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 81.027344 142.558594 L 81.027344 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 91.261719 142.558594 L 91.261719 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 101.496094 142.558594 L 101.496094 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="57.054688" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-2" x="84.261719" y="167.916016"/>
  <use xlink:href="#glyph0-1" x="90.933594" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.824219 L 59.039062 71.140625 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.824219 L 51.839844 139.824219 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 122.65625 L 51.839844 122.65625 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 105.484375 L 51.839844 105.484375 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 88.3125 L 51.839844 88.3125 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 71.140625 L 51.839844 71.140625 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="41.197266" y="148.324219"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="141.652344"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="138.316406"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-4" x="41.197266" y="117.484375"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="110.8125"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="104.140625"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="100.804688"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-4" x="41.197266" y="83.140625"/>
  <use xlink:href="#glyph1-4" x="41.197266" y="76.46875"/>
  <use xlink:href="#glyph1-2" x="41.197266" y="69.796875"/>
  <use xlink:href="#glyph1-3" x="41.197266" y="66.460938"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 142.558594 L 113.761719 142.558594 L 113.761719 59.039062 L 59.039062 59.039062 L 59.039062 142.558594 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-3" x="64.898438" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="67.5625" y="196.716797"/>
  <use xlink:href="#glyph0-5" x="70.898438" y="196.716797"/>
  <use xlink:href="#glyph0-6" x="77.570312" y="196.716797"/>
  <use xlink:href="#glyph0-7" x="81.566406" y="196.716797"/>
  <use xlink:href="#glyph0-4" x="88.238281" y="196.716797"/>
  <use xlink:href="#glyph0-3" x="91.574219" y="196.716797"/>
  <use xlink:href="#glyph0-8" x="94.238281" y="196.716797"/>
  <use xlink:href="#glyph0-9" x="100.910156" y="196.716797"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="11.081055" y="104.300781"/>
</g>
</g>
</svg>

hist(samples[, 'm'], xlab = 'm')hist(samples[, 'sigma_x'], xlab = expression(sigma[x]))hist(samples[, 'sigma_y'], xlab = expression(sigma[y]))hist(samples[, 'theta'], xlab = expression(theta))<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 7.296875 -4.765625 L 7.296875 0 L 9.46875 0 L 9.46875 -10.5 L 7.296875 -10.5 L 7.296875 -6.5625 L 3.140625 -6.5625 L 3.140625 -10.5 L 0.984375 -10.5 L 0.984375 0 L 3.140625 0 L 3.140625 -4.765625 Z M 7.296875 -4.765625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 2.984375 -7.78125 L 0.96875 -7.78125 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 -8.703125 L 2.984375 -8.703125 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 7.28125 -5.265625 C 7.25 -6.921875 5.984375 -7.90625 3.890625 -7.90625 C 1.921875 -7.90625 0.6875 -6.921875 0.6875 -5.3125 C 0.6875 -4.796875 0.84375 -4.34375 1.125 -4.046875 C 1.390625 -3.78125 1.640625 -3.640625 2.390625 -3.40625 L 4.796875 -2.65625 C 5.296875 -2.5 5.46875 -2.328125 5.46875 -2.015625 C 5.46875 -1.546875 4.90625 -1.25 3.96875 -1.25 C 3.453125 -1.25 3.046875 -1.359375 2.78125 -1.53125 C 2.5625 -1.6875 2.484375 -1.84375 2.390625 -2.265625 L 0.421875 -2.265625 C 0.46875 -0.5625 1.734375 0.328125 4.09375 0.328125 C 5.171875 0.328125 6 0.09375 6.5625 -0.359375 C 7.140625 -0.828125 7.484375 -1.546875 7.484375 -2.3125 C 7.484375 -3.3125 6.984375 -3.96875 5.96875 -4.265625 L 3.421875 -5 C 2.859375 -5.171875 2.703125 -5.28125 2.703125 -5.609375 C 2.703125 -6.03125 3.171875 -6.328125 3.875 -6.328125 C 4.84375 -6.328125 5.3125 -5.984375 5.328125 -5.265625 Z M 7.28125 -5.265625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 4.34375 -7.625 L 3.21875 -7.625 L 3.21875 -9.703125 L 1.203125 -9.703125 L 1.203125 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.203125 -6.28125 L 1.203125 -1.5 C 1.203125 -0.28125 1.84375 0.328125 3.171875 0.328125 C 3.609375 0.328125 3.96875 0.28125 4.34375 0.171875 L 4.34375 -1.234375 C 4.140625 -1.203125 4.015625 -1.203125 3.875 -1.203125 C 3.34375 -1.203125 3.21875 -1.359375 3.21875 -2.046875 L 3.21875 -6.28125 L 4.34375 -6.28125 Z M 4.34375 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 4.34375 -7.90625 C 1.953125 -7.90625 0.5 -6.34375 0.5 -3.78125 C 0.5 -1.21875 1.953125 0.328125 4.34375 0.328125 C 6.71875 0.328125 8.203125 -1.234375 8.203125 -3.734375 C 8.203125 -6.375 6.765625 -7.90625 4.34375 -7.90625 Z M 4.34375 -6.28125 C 5.453125 -6.28125 6.1875 -5.28125 6.1875 -3.765625 C 6.1875 -2.3125 5.4375 -1.296875 4.34375 -1.296875 C 3.25 -1.296875 2.515625 -2.3125 2.515625 -3.78125 C 2.515625 -5.265625 3.25 -6.28125 4.34375 -6.28125 Z M 4.34375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 5.875 -7.78125 L 5.875 -6.578125 C 5.265625 -7.5 4.609375 -7.90625 3.71875 -7.90625 C 1.875 -7.90625 0.484375 -6.109375 0.484375 -3.703125 C 0.484375 -1.28125 1.75 0.328125 3.671875 0.328125 C 4.578125 0.328125 5.125 0.0625 5.875 -0.796875 L 5.875 0.265625 C 5.875 1.203125 5.171875 1.84375 4.15625 1.84375 C 3.40625 1.84375 2.890625 1.53125 2.734375 0.9375 L 0.640625 0.9375 C 0.65625 1.546875 0.890625 1.953125 1.40625 2.390625 C 2.03125 2.890625 2.890625 3.140625 4.09375 3.140625 C 6.4375 3.140625 7.796875 2.09375 7.796875 0.265625 L 7.796875 -7.78125 Z M 4.15625 -6.21875 C 5.15625 -6.21875 5.90625 -5.171875 5.90625 -3.734375 C 5.90625 -2.3125 5.171875 -1.359375 4.125 -1.359375 C 3.171875 -1.359375 2.5 -2.3125 2.5 -3.734375 C 2.5 -5.203125 3.171875 -6.21875 4.15625 -6.21875 Z M 4.15625 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 0.90625 -7.78125 L 0.90625 0 L 2.921875 0 L 2.921875 -4.140625 C 2.921875 -5.3125 3.515625 -5.90625 4.703125 -5.90625 C 4.90625 -5.90625 5.0625 -5.890625 5.328125 -5.84375 L 5.328125 -7.890625 C 5.21875 -7.90625 5.140625 -7.90625 5.078125 -7.90625 C 4.15625 -7.90625 3.359375 -7.296875 2.921875 -6.25 L 2.921875 -7.78125 Z M 0.90625 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 7.546875 -0.25 C 7.1875 -0.578125 7.09375 -0.796875 7.09375 -1.203125 L 7.09375 -5.515625 C 7.09375 -7.109375 6 -7.90625 3.90625 -7.90625 C 1.796875 -7.90625 0.703125 -7.015625 0.578125 -5.21875 L 2.515625 -5.21875 C 2.625 -6.015625 2.953125 -6.28125 3.953125 -6.28125 C 4.71875 -6.28125 5.109375 -6.015625 5.109375 -5.5 C 5.109375 -5.25 4.984375 -5.015625 4.765625 -4.890625 C 4.5 -4.75 4.5 -4.75 3.5 -4.59375 L 2.6875 -4.453125 C 1.15625 -4.1875 0.40625 -3.40625 0.40625 -2 C 0.40625 -1.34375 0.59375 -0.796875 0.953125 -0.40625 C 1.390625 0.0625 2.078125 0.328125 2.765625 0.328125 C 3.625 0.328125 4.421875 -0.046875 5.125 -0.78125 C 5.125 -0.375 5.171875 -0.234375 5.359375 0 L 7.546875 0 Z M 5.109375 -3.125 C 5.109375 -1.953125 4.53125 -1.296875 3.515625 -1.296875 C 2.84375 -1.296875 2.421875 -1.65625 2.421875 -2.234375 C 2.421875 -2.84375 2.734375 -3.125 3.578125 -3.296875 L 4.265625 -3.421875 C 4.796875 -3.53125 4.890625 -3.5625 5.109375 -3.671875 Z M 5.109375 -3.125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.859375 -7.78125 L 0.859375 0 L 2.875 0 L 2.875 -4.671875 C 2.875 -5.625 3.40625 -6.1875 4.265625 -6.1875 C 4.9375 -6.1875 5.359375 -5.8125 5.359375 -5.1875 L 5.359375 0 L 7.375 0 L 7.375 -4.671875 C 7.375 -5.625 7.890625 -6.1875 8.765625 -6.1875 C 9.4375 -6.1875 9.859375 -5.8125 9.859375 -5.1875 L 9.859375 0 L 11.875 0 L 11.875 -5.5 C 11.875 -7.015625 10.953125 -7.90625 9.390625 -7.90625 C 8.40625 -7.90625 7.71875 -7.5625 7.109375 -6.75 C 6.734375 -7.484375 5.96875 -7.90625 5 -7.90625 C 4.109375 -7.90625 3.53125 -7.609375 2.859375 -6.8125 L 2.859375 -7.78125 Z M 0.859375 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-10">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-11">
<path style="stroke:none;" d="M 4.515625 -7.625 L 3.3125 -7.625 L 3.3125 -8.390625 C 3.3125 -8.78125 3.484375 -8.984375 3.859375 -8.984375 C 4.03125 -8.984375 4.265625 -8.96875 4.4375 -8.953125 L 4.4375 -10.453125 C 4.0625 -10.484375 3.5625 -10.5 3.28125 -10.5 C 1.9375 -10.5 1.296875 -9.875 1.296875 -8.5625 L 1.296875 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.296875 -6.28125 L 1.296875 0 L 3.3125 0 L 3.3125 -6.28125 L 4.515625 -6.28125 Z M 4.515625 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-12">
<path style="stroke:none;" d="M 2.859375 -7.78125 L 0.828125 -7.78125 L 0.828125 3.140625 L 2.859375 3.140625 L 2.859375 -0.921875 C 3.34375 -0.0625 4.03125 0.34375 5.015625 0.34375 C 6.890625 0.34375 8.265625 -1.40625 8.265625 -3.78125 C 8.265625 -4.875 7.953125 -5.96875 7.4375 -6.6875 C 6.921875 -7.421875 5.953125 -7.90625 5.015625 -7.90625 C 4.03125 -7.90625 3.34375 -7.484375 2.859375 -6.625 Z M 4.546875 -6.21875 C 5.578125 -6.21875 6.25 -5.234375 6.25 -3.75 C 6.25 -2.328125 5.546875 -1.34375 4.546875 -1.34375 C 3.546875 -1.34375 2.859375 -2.3125 2.859375 -3.78125 C 2.859375 -5.234375 3.546875 -6.21875 4.546875 -6.21875 Z M 4.546875 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-13">
<path style="stroke:none;" d="M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-14">
<path style="stroke:none;" d="M 7.546875 -3.25 C 7.5625 -3.421875 7.5625 -3.5 7.5625 -3.59375 C 7.5625 -4.375 7.453125 -5.09375 7.265625 -5.640625 C 6.734375 -7.0625 5.484375 -7.90625 3.921875 -7.90625 C 1.6875 -7.90625 0.3125 -6.296875 0.3125 -3.6875 C 0.3125 -1.203125 1.671875 0.328125 3.875 0.328125 C 5.625 0.328125 7.03125 -0.65625 7.484375 -2.1875 L 5.484375 -2.1875 C 5.25 -1.5625 4.6875 -1.203125 3.953125 -1.203125 C 3.375 -1.203125 2.90625 -1.453125 2.625 -1.890625 C 2.4375 -2.171875 2.359375 -2.515625 2.328125 -3.25 Z M 2.359375 -4.59375 C 2.5 -5.78125 3 -6.375 3.890625 -6.375 C 4.390625 -6.375 4.859375 -6.125 5.140625 -5.71875 C 5.328125 -5.4375 5.421875 -5.125 5.453125 -4.59375 Z M 2.359375 -4.59375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-15">
<path style="stroke:none;" d="M 4.4375 -10.5 L 0.953125 -10.5 L 0.953125 2.875 L 4.4375 2.875 L 4.4375 1.40625 L 2.828125 1.40625 L 2.828125 -9.03125 L 4.4375 -9.03125 Z M 4.4375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-16">
<path style="stroke:none;" d="M 0.921875 -2.109375 L 0.921875 0 L 2.15625 0 L 2.15625 0.046875 C 2.15625 1.015625 1.765625 1.53125 0.921875 1.703125 L 0.921875 2.5 C 1.515625 2.4375 1.921875 2.28125 2.3125 1.96875 C 2.875 1.53125 3.078125 1 3.078125 -0.125 L 3.078125 -2.109375 Z M 0.921875 -2.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-17">
<path style="stroke:none;" d="M 2.703125 -10.5 L 0.71875 -10.5 L 0.71875 -8.625 L 1.296875 -6.765625 L 2.109375 -6.765625 L 2.703125 -8.625 Z M 6.109375 -10.5 L 4.125 -10.5 L 4.125 -8.625 L 4.703125 -6.765625 L 5.5 -6.765625 L 6.109375 -8.625 Z M 6.109375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-18">
<path style="stroke:none;" d="M 0.265625 2.875 L 3.75 2.875 L 3.75 -10.5 L 0.265625 -10.5 L 0.265625 -9.03125 L 1.875 -9.03125 L 1.875 1.40625 L 0.265625 1.40625 Z M 0.265625 2.875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M 0.84375 -6.28125 L 0.84375 0 L 1.84375 0 L 1.84375 -3.953125 C 1.84375 -4.859375 2.515625 -5.59375 3.328125 -5.59375 C 4.0625 -5.59375 4.484375 -5.140625 4.484375 -4.328125 L 4.484375 0 L 5.5 0 L 5.5 -3.953125 C 5.5 -4.859375 6.15625 -5.59375 6.96875 -5.59375 C 7.703125 -5.59375 8.140625 -5.125 8.140625 -4.328125 L 8.140625 0 L 9.140625 0 L 9.140625 -4.71875 C 9.140625 -5.84375 8.5 -6.46875 7.3125 -6.46875 C 6.484375 -6.46875 5.96875 -6.21875 5.390625 -5.515625 C 5.015625 -6.1875 4.515625 -6.46875 3.703125 -6.46875 C 2.859375 -6.46875 2.296875 -6.15625 1.765625 -5.40625 L 1.765625 -6.28125 Z M 0.84375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph1-2">
<path style="stroke:none;" d="M 3.40625 -3.75 L 0.546875 -3.75 L 0.546875 -2.875 L 3.40625 -2.875 Z M 3.40625 -3.75 "/>
</symbol>
<symbol overflow="visible" id="glyph1-3">
<path style="stroke:none;" d="M 6.078125 -1.046875 L 1.59375 -1.046875 C 1.703125 -1.734375 2.09375 -2.1875 3.125 -2.796875 L 4.328125 -3.4375 C 5.515625 -4.09375 6.125 -4.96875 6.125 -6.015625 C 6.125 -6.71875 5.84375 -7.375 5.34375 -7.84375 C 4.84375 -8.296875 4.21875 -8.515625 3.40625 -8.515625 C 2.328125 -8.515625 1.53125 -8.125 1.0625 -7.40625 C 0.75 -6.953125 0.625 -6.421875 0.59375 -5.5625 L 1.65625 -5.5625 C 1.6875 -6.125 1.765625 -6.484375 1.90625 -6.75 C 2.1875 -7.265625 2.734375 -7.578125 3.375 -7.578125 C 4.328125 -7.578125 5.046875 -6.90625 5.046875 -5.984375 C 5.046875 -5.3125 4.65625 -4.734375 3.90625 -4.3125 L 2.796875 -3.6875 C 1.015625 -2.671875 0.5 -1.875 0.40625 0 L 6.078125 0 Z M 6.078125 -1.046875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-4">
<path style="stroke:none;" d="M 6.15625 -2.8125 C 6.15625 -3.765625 6.078125 -4.34375 5.90625 -4.8125 C 5.5 -5.84375 4.53125 -6.46875 3.359375 -6.46875 C 1.609375 -6.46875 0.484375 -5.125 0.484375 -3.0625 C 0.484375 -1 1.578125 0.28125 3.34375 0.28125 C 4.78125 0.28125 5.765625 -0.546875 6.03125 -1.90625 L 5.015625 -1.90625 C 4.734375 -1.078125 4.171875 -0.640625 3.375 -0.640625 C 2.734375 -0.640625 2.203125 -0.9375 1.859375 -1.46875 C 1.625 -1.828125 1.53125 -2.1875 1.53125 -2.8125 Z M 1.546875 -3.625 C 1.625 -4.78125 2.34375 -5.546875 3.34375 -5.546875 C 4.328125 -5.546875 5.09375 -4.734375 5.09375 -3.703125 C 5.09375 -3.671875 5.09375 -3.640625 5.078125 -3.625 Z M 1.546875 -3.625 "/>
</symbol>
<symbol overflow="visible" id="glyph1-5">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph1-6">
<path style="stroke:none;" d="M 3.921875 -2.046875 L 3.921875 0 L 4.984375 0 L 4.984375 -2.046875 L 6.234375 -2.046875 L 6.234375 -2.984375 L 4.984375 -2.984375 L 4.984375 -8.515625 L 4.203125 -8.515625 L 0.34375 -3.15625 L 0.34375 -2.046875 Z M 3.921875 -2.984375 L 1.265625 -2.984375 L 3.921875 -6.703125 Z M 3.921875 -2.984375 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M -3.984375 -2.203125 L -3.984375 -6.375 L -4.96875 -6.375 L -4.96875 -2.203125 L -7.765625 -2.203125 L -7.765625 -6.953125 L -8.75 -6.953125 L -8.75 -1.078125 L 0 -1.078125 L 0 -2.203125 Z M -3.984375 -2.203125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-2">
<path style="stroke:none;" d="M -6.28125 -0.828125 L 0 -0.828125 L 0 -1.84375 L -3.265625 -1.84375 C -4.15625 -1.84375 -4.75 -2.0625 -5.09375 -2.546875 C -5.328125 -2.859375 -5.40625 -3.15625 -5.40625 -3.859375 L -6.4375 -3.859375 C -6.453125 -3.6875 -6.46875 -3.59375 -6.46875 -3.46875 C -6.46875 -2.8125 -6.078125 -2.328125 -5.140625 -1.75 L -6.28125 -1.75 Z M -6.28125 -0.828125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-3">
<path style="stroke:none;" d="M -2.8125 -6.15625 C -3.765625 -6.15625 -4.34375 -6.078125 -4.8125 -5.90625 C -5.84375 -5.5 -6.46875 -4.53125 -6.46875 -3.359375 C -6.46875 -1.609375 -5.125 -0.484375 -3.0625 -0.484375 C -1 -0.484375 0.28125 -1.578125 0.28125 -3.34375 C 0.28125 -4.78125 -0.546875 -5.765625 -1.90625 -6.03125 L -1.90625 -5.015625 C -1.078125 -4.734375 -0.640625 -4.171875 -0.640625 -3.375 C -0.640625 -2.734375 -0.9375 -2.203125 -1.46875 -1.859375 C -1.828125 -1.625 -2.1875 -1.53125 -2.8125 -1.53125 Z M -3.625 -1.546875 C -4.78125 -1.625 -5.546875 -2.34375 -5.546875 -3.34375 C -5.546875 -4.328125 -4.734375 -5.09375 -3.703125 -5.09375 C -3.671875 -5.09375 -3.640625 -5.09375 -3.625 -5.078125 Z M -3.625 -1.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-4">
<path style="stroke:none;" d="M 2.609375 -5.9375 L -6.28125 -5.9375 L -6.28125 -5.046875 L -5.453125 -5.046875 C -6.109375 -4.578125 -6.46875 -3.875 -6.46875 -3.046875 C -6.46875 -1.390625 -5.109375 -0.3125 -3.03125 -0.3125 C -0.984375 -0.3125 0.28125 -1.34375 0.28125 -3 C 0.28125 -3.875 -0.03125 -4.46875 -0.71875 -4.9375 L 2.609375 -4.9375 Z M -5.53125 -3.1875 C -5.53125 -4.265625 -4.578125 -4.9375 -3.0625 -4.9375 C -1.625 -4.9375 -0.65625 -4.25 -0.65625 -3.1875 C -0.65625 -2.09375 -1.625 -1.359375 -3.09375 -1.359375 C -4.546875 -1.359375 -5.53125 -2.09375 -5.53125 -3.1875 Z M -5.53125 -3.1875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-5">
<path style="stroke:none;" d="M 0 -5.78125 L -6.28125 -5.78125 L -6.28125 -4.78125 L -2.71875 -4.78125 C -1.4375 -4.78125 -0.59375 -4.109375 -0.59375 -3.078125 C -0.59375 -2.28125 -1.078125 -1.78125 -1.84375 -1.78125 L -6.28125 -1.78125 L -6.28125 -0.78125 L -1.4375 -0.78125 C -0.390625 -0.78125 0.28125 -1.5625 0.28125 -2.78125 C 0.28125 -3.703125 -0.046875 -4.296875 -0.875 -4.890625 L 0 -4.890625 Z M 0 -5.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-6">
<path style="stroke:none;" d="M -6.28125 -0.84375 L 0 -0.84375 L 0 -1.84375 L -3.46875 -1.84375 C -4.75 -1.84375 -5.59375 -2.515625 -5.59375 -3.546875 C -5.59375 -4.34375 -5.109375 -4.84375 -4.359375 -4.84375 L 0 -4.84375 L 0 -5.84375 L -4.75 -5.84375 C -5.796875 -5.84375 -6.46875 -5.0625 -6.46875 -3.859375 C -6.46875 -2.921875 -6.109375 -2.3125 -5.234375 -1.765625 L -6.28125 -1.765625 Z M -6.28125 -0.84375 "/>
</symbol>
<symbol overflow="visible" id="glyph2-7">
<path style="stroke:none;" d="M -4.171875 -5.65625 C -4.78125 -5.609375 -5.1875 -5.46875 -5.53125 -5.234375 C -6.125 -4.796875 -6.46875 -4.046875 -6.46875 -3.171875 C -6.46875 -1.46875 -5.125 -0.375 -3.03125 -0.375 C -1.015625 -0.375 0.28125 -1.453125 0.28125 -3.15625 C 0.28125 -4.65625 -0.625 -5.609375 -2.15625 -5.71875 L -2.15625 -4.71875 C -1.15625 -4.546875 -0.640625 -4.03125 -0.640625 -3.1875 C -0.640625 -2.078125 -1.546875 -1.421875 -3.03125 -1.421875 C -4.609375 -1.421875 -5.546875 -2.0625 -5.546875 -3.15625 C -5.546875 -4 -5.046875 -4.53125 -4.171875 -4.640625 Z M -4.171875 -5.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph2-8">
<path style="stroke:none;" d="M -6.28125 -4.65625 L -1.390625 -2.921875 L -6.28125 -1.3125 L -6.28125 -0.234375 L 0.03125 -2.359375 L 1.015625 -1.984375 C 1.46875 -1.828125 1.625 -1.59375 1.625 -1.171875 C 1.625 -1.03125 1.609375 -0.859375 1.5625 -0.640625 L 2.453125 -0.640625 C 2.5625 -0.859375 2.609375 -1.0625 2.609375 -1.3125 C 2.609375 -1.640625 2.515625 -1.984375 2.3125 -2.25 C 2.09375 -2.5625 1.828125 -2.75 1.3125 -2.9375 L -6.28125 -5.734375 Z M -6.28125 -4.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph2-9">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-10">
<path style="stroke:none;" d="M -1.046875 -6.078125 L -1.046875 -1.59375 C -1.734375 -1.703125 -2.1875 -2.09375 -2.796875 -3.125 L -3.4375 -4.328125 C -4.09375 -5.515625 -4.96875 -6.125 -6.015625 -6.125 C -6.71875 -6.125 -7.375 -5.84375 -7.84375 -5.34375 C -8.296875 -4.84375 -8.515625 -4.21875 -8.515625 -3.40625 C -8.515625 -2.328125 -8.125 -1.53125 -7.40625 -1.0625 C -6.953125 -0.75 -6.421875 -0.625 -5.5625 -0.59375 L -5.5625 -1.65625 C -6.125 -1.6875 -6.484375 -1.765625 -6.75 -1.90625 C -7.265625 -2.1875 -7.578125 -2.734375 -7.578125 -3.375 C -7.578125 -4.328125 -6.90625 -5.046875 -5.984375 -5.046875 C -5.3125 -5.046875 -4.734375 -4.65625 -4.3125 -3.90625 L -3.6875 -2.796875 C -2.671875 -1.015625 -1.875 -0.5 0 -0.40625 L 0 -6.078125 Z M -1.046875 -6.078125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-11">
<path style="stroke:none;" d="M -2.046875 -3.921875 L 0 -3.921875 L 0 -4.984375 L -2.046875 -4.984375 L -2.046875 -6.234375 L -2.984375 -6.234375 L -2.984375 -4.984375 L -8.515625 -4.984375 L -8.515625 -4.203125 L -3.15625 -0.34375 L -2.046875 -0.34375 Z M -2.984375 -3.921875 L -2.984375 -1.265625 L -6.703125 -3.921875 Z M -2.984375 -3.921875 "/>
</symbol>
</g>
</defs>
<g id="surface832">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="-11.101562" y="34.116211"/>
  <use xlink:href="#glyph0-2" x="-0.700195" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="3.304688" y="34.116211"/>
  <use xlink:href="#glyph0-4" x="11.314453" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="16.111328" y="34.116211"/>
  <use xlink:href="#glyph0-6" x="24.913086" y="34.116211"/>
  <use xlink:href="#glyph0-7" x="33.714844" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="39.319336" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="47.329102" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="60.135742" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="64.140625" y="34.116211"/>
  <use xlink:href="#glyph0-11" x="72.942383" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="77.739258" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="81.744141" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="89.753906" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="97.763672" y="34.116211"/>
  <use xlink:href="#glyph0-12" x="110.570312" y="34.116211"/>
  <use xlink:href="#glyph0-13" x="119.37207" y="34.116211"/>
  <use xlink:href="#glyph0-14" x="123.376953" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="131.386719" y="34.116211"/>
  <use xlink:href="#glyph0-15" x="139.396484" y="34.116211"/>
  <use xlink:href="#glyph0-16" x="144.193359" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="148.198242" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="152.203125" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="159.03125" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="171.837891" y="34.116211"/>
  <use xlink:href="#glyph0-18" x="178.666016" y="34.116211"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="81.398438" y="196.716797"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="12.396484" y="129.300781"/>
  <use xlink:href="#glyph2-2" x="12.396484" y="121.96875"/>
  <use xlink:href="#glyph2-3" x="12.396484" y="117.972656"/>
  <use xlink:href="#glyph2-4" x="12.396484" y="111.300781"/>
  <use xlink:href="#glyph2-5" x="12.396484" y="104.628906"/>
  <use xlink:href="#glyph2-3" x="12.396484" y="97.957031"/>
  <use xlink:href="#glyph2-6" x="12.396484" y="91.285156"/>
  <use xlink:href="#glyph2-7" x="12.396484" y="84.613281"/>
  <use xlink:href="#glyph2-8" x="12.396484" y="78.613281"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 67.398438 142.558594 L 105.398438 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 67.398438 142.558594 L 67.398438 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 80.066406 142.558594 L 80.066406 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 92.734375 142.558594 L 92.734375 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 105.398438 142.558594 L 105.398438 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-2" x="49.898438" y="167.916016"/>
  <use xlink:href="#glyph1-3" x="53.894531" y="167.916016"/>
  <use xlink:href="#glyph1-4" x="60.566406" y="167.916016"/>
  <use xlink:href="#glyph1-2" x="67.238281" y="167.916016"/>
  <use xlink:href="#glyph1-5" x="71.234375" y="167.916016"/>
  <use xlink:href="#glyph1-6" x="77.90625" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 59.039062 67.863281 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 51.839844 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 125.144531 L 51.839844 125.144531 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 110.824219 L 51.839844 110.824219 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 96.503906 L 51.839844 96.503906 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 82.183594 L 51.839844 82.183594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 67.863281 L 51.839844 67.863281 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-9" x="41.197266" y="142.964844"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-10" x="41.197266" y="117.824219"/>
  <use xlink:href="#glyph2-9" x="41.197266" y="111.152344"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-11" x="41.197266" y="89.183594"/>
  <use xlink:href="#glyph2-9" x="41.197266" y="82.511719"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 139.464844 L 67.398438 139.464844 L 67.398438 133.738281 L 61.066406 133.738281 Z M 61.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 67.398438 139.464844 L 73.730469 139.464844 L 73.730469 120.847656 L 67.398438 120.847656 Z M 67.398438 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 73.734375 139.464844 L 80.066406 139.464844 L 80.066406 62.132812 L 73.734375 62.132812 Z M 73.734375 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 80.066406 139.464844 L 86.398438 139.464844 L 86.398438 116.550781 L 80.066406 116.550781 Z M 80.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 86.398438 139.464844 L 92.730469 139.464844 L 92.730469 126.574219 L 86.398438 126.574219 Z M 86.398438 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 92.734375 139.464844 L 99.066406 139.464844 L 99.066406 135.167969 L 92.734375 135.167969 Z M 92.734375 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 99.066406 139.464844 L 105.398438 139.464844 Z M 99.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 105.398438 139.464844 L 111.730469 139.464844 L 111.730469 138.03125 L 105.398438 138.03125 Z M 105.398438 139.464844 "/>
</g>
</svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 7.296875 -4.765625 L 7.296875 0 L 9.46875 0 L 9.46875 -10.5 L 7.296875 -10.5 L 7.296875 -6.5625 L 3.140625 -6.5625 L 3.140625 -10.5 L 0.984375 -10.5 L 0.984375 0 L 3.140625 0 L 3.140625 -4.765625 Z M 7.296875 -4.765625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 2.984375 -7.78125 L 0.96875 -7.78125 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 -8.703125 L 2.984375 -8.703125 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 7.28125 -5.265625 C 7.25 -6.921875 5.984375 -7.90625 3.890625 -7.90625 C 1.921875 -7.90625 0.6875 -6.921875 0.6875 -5.3125 C 0.6875 -4.796875 0.84375 -4.34375 1.125 -4.046875 C 1.390625 -3.78125 1.640625 -3.640625 2.390625 -3.40625 L 4.796875 -2.65625 C 5.296875 -2.5 5.46875 -2.328125 5.46875 -2.015625 C 5.46875 -1.546875 4.90625 -1.25 3.96875 -1.25 C 3.453125 -1.25 3.046875 -1.359375 2.78125 -1.53125 C 2.5625 -1.6875 2.484375 -1.84375 2.390625 -2.265625 L 0.421875 -2.265625 C 0.46875 -0.5625 1.734375 0.328125 4.09375 0.328125 C 5.171875 0.328125 6 0.09375 6.5625 -0.359375 C 7.140625 -0.828125 7.484375 -1.546875 7.484375 -2.3125 C 7.484375 -3.3125 6.984375 -3.96875 5.96875 -4.265625 L 3.421875 -5 C 2.859375 -5.171875 2.703125 -5.28125 2.703125 -5.609375 C 2.703125 -6.03125 3.171875 -6.328125 3.875 -6.328125 C 4.84375 -6.328125 5.3125 -5.984375 5.328125 -5.265625 Z M 7.28125 -5.265625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 4.34375 -7.625 L 3.21875 -7.625 L 3.21875 -9.703125 L 1.203125 -9.703125 L 1.203125 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.203125 -6.28125 L 1.203125 -1.5 C 1.203125 -0.28125 1.84375 0.328125 3.171875 0.328125 C 3.609375 0.328125 3.96875 0.28125 4.34375 0.171875 L 4.34375 -1.234375 C 4.140625 -1.203125 4.015625 -1.203125 3.875 -1.203125 C 3.34375 -1.203125 3.21875 -1.359375 3.21875 -2.046875 L 3.21875 -6.28125 L 4.34375 -6.28125 Z M 4.34375 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 4.34375 -7.90625 C 1.953125 -7.90625 0.5 -6.34375 0.5 -3.78125 C 0.5 -1.21875 1.953125 0.328125 4.34375 0.328125 C 6.71875 0.328125 8.203125 -1.234375 8.203125 -3.734375 C 8.203125 -6.375 6.765625 -7.90625 4.34375 -7.90625 Z M 4.34375 -6.28125 C 5.453125 -6.28125 6.1875 -5.28125 6.1875 -3.765625 C 6.1875 -2.3125 5.4375 -1.296875 4.34375 -1.296875 C 3.25 -1.296875 2.515625 -2.3125 2.515625 -3.78125 C 2.515625 -5.265625 3.25 -6.28125 4.34375 -6.28125 Z M 4.34375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 5.875 -7.78125 L 5.875 -6.578125 C 5.265625 -7.5 4.609375 -7.90625 3.71875 -7.90625 C 1.875 -7.90625 0.484375 -6.109375 0.484375 -3.703125 C 0.484375 -1.28125 1.75 0.328125 3.671875 0.328125 C 4.578125 0.328125 5.125 0.0625 5.875 -0.796875 L 5.875 0.265625 C 5.875 1.203125 5.171875 1.84375 4.15625 1.84375 C 3.40625 1.84375 2.890625 1.53125 2.734375 0.9375 L 0.640625 0.9375 C 0.65625 1.546875 0.890625 1.953125 1.40625 2.390625 C 2.03125 2.890625 2.890625 3.140625 4.09375 3.140625 C 6.4375 3.140625 7.796875 2.09375 7.796875 0.265625 L 7.796875 -7.78125 Z M 4.15625 -6.21875 C 5.15625 -6.21875 5.90625 -5.171875 5.90625 -3.734375 C 5.90625 -2.3125 5.171875 -1.359375 4.125 -1.359375 C 3.171875 -1.359375 2.5 -2.3125 2.5 -3.734375 C 2.5 -5.203125 3.171875 -6.21875 4.15625 -6.21875 Z M 4.15625 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 0.90625 -7.78125 L 0.90625 0 L 2.921875 0 L 2.921875 -4.140625 C 2.921875 -5.3125 3.515625 -5.90625 4.703125 -5.90625 C 4.90625 -5.90625 5.0625 -5.890625 5.328125 -5.84375 L 5.328125 -7.890625 C 5.21875 -7.90625 5.140625 -7.90625 5.078125 -7.90625 C 4.15625 -7.90625 3.359375 -7.296875 2.921875 -6.25 L 2.921875 -7.78125 Z M 0.90625 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 7.546875 -0.25 C 7.1875 -0.578125 7.09375 -0.796875 7.09375 -1.203125 L 7.09375 -5.515625 C 7.09375 -7.109375 6 -7.90625 3.90625 -7.90625 C 1.796875 -7.90625 0.703125 -7.015625 0.578125 -5.21875 L 2.515625 -5.21875 C 2.625 -6.015625 2.953125 -6.28125 3.953125 -6.28125 C 4.71875 -6.28125 5.109375 -6.015625 5.109375 -5.5 C 5.109375 -5.25 4.984375 -5.015625 4.765625 -4.890625 C 4.5 -4.75 4.5 -4.75 3.5 -4.59375 L 2.6875 -4.453125 C 1.15625 -4.1875 0.40625 -3.40625 0.40625 -2 C 0.40625 -1.34375 0.59375 -0.796875 0.953125 -0.40625 C 1.390625 0.0625 2.078125 0.328125 2.765625 0.328125 C 3.625 0.328125 4.421875 -0.046875 5.125 -0.78125 C 5.125 -0.375 5.171875 -0.234375 5.359375 0 L 7.546875 0 Z M 5.109375 -3.125 C 5.109375 -1.953125 4.53125 -1.296875 3.515625 -1.296875 C 2.84375 -1.296875 2.421875 -1.65625 2.421875 -2.234375 C 2.421875 -2.84375 2.734375 -3.125 3.578125 -3.296875 L 4.265625 -3.421875 C 4.796875 -3.53125 4.890625 -3.5625 5.109375 -3.671875 Z M 5.109375 -3.125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.859375 -7.78125 L 0.859375 0 L 2.875 0 L 2.875 -4.671875 C 2.875 -5.625 3.40625 -6.1875 4.265625 -6.1875 C 4.9375 -6.1875 5.359375 -5.8125 5.359375 -5.1875 L 5.359375 0 L 7.375 0 L 7.375 -4.671875 C 7.375 -5.625 7.890625 -6.1875 8.765625 -6.1875 C 9.4375 -6.1875 9.859375 -5.8125 9.859375 -5.1875 L 9.859375 0 L 11.875 0 L 11.875 -5.5 C 11.875 -7.015625 10.953125 -7.90625 9.390625 -7.90625 C 8.40625 -7.90625 7.71875 -7.5625 7.109375 -6.75 C 6.734375 -7.484375 5.96875 -7.90625 5 -7.90625 C 4.109375 -7.90625 3.53125 -7.609375 2.859375 -6.8125 L 2.859375 -7.78125 Z M 0.859375 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-10">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-11">
<path style="stroke:none;" d="M 4.515625 -7.625 L 3.3125 -7.625 L 3.3125 -8.390625 C 3.3125 -8.78125 3.484375 -8.984375 3.859375 -8.984375 C 4.03125 -8.984375 4.265625 -8.96875 4.4375 -8.953125 L 4.4375 -10.453125 C 4.0625 -10.484375 3.5625 -10.5 3.28125 -10.5 C 1.9375 -10.5 1.296875 -9.875 1.296875 -8.5625 L 1.296875 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.296875 -6.28125 L 1.296875 0 L 3.3125 0 L 3.3125 -6.28125 L 4.515625 -6.28125 Z M 4.515625 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-12">
<path style="stroke:none;" d="M 2.859375 -7.78125 L 0.828125 -7.78125 L 0.828125 3.140625 L 2.859375 3.140625 L 2.859375 -0.921875 C 3.34375 -0.0625 4.03125 0.34375 5.015625 0.34375 C 6.890625 0.34375 8.265625 -1.40625 8.265625 -3.78125 C 8.265625 -4.875 7.953125 -5.96875 7.4375 -6.6875 C 6.921875 -7.421875 5.953125 -7.90625 5.015625 -7.90625 C 4.03125 -7.90625 3.34375 -7.484375 2.859375 -6.625 Z M 4.546875 -6.21875 C 5.578125 -6.21875 6.25 -5.234375 6.25 -3.75 C 6.25 -2.328125 5.546875 -1.34375 4.546875 -1.34375 C 3.546875 -1.34375 2.859375 -2.3125 2.859375 -3.78125 C 2.859375 -5.234375 3.546875 -6.21875 4.546875 -6.21875 Z M 4.546875 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-13">
<path style="stroke:none;" d="M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-14">
<path style="stroke:none;" d="M 7.546875 -3.25 C 7.5625 -3.421875 7.5625 -3.5 7.5625 -3.59375 C 7.5625 -4.375 7.453125 -5.09375 7.265625 -5.640625 C 6.734375 -7.0625 5.484375 -7.90625 3.921875 -7.90625 C 1.6875 -7.90625 0.3125 -6.296875 0.3125 -3.6875 C 0.3125 -1.203125 1.671875 0.328125 3.875 0.328125 C 5.625 0.328125 7.03125 -0.65625 7.484375 -2.1875 L 5.484375 -2.1875 C 5.25 -1.5625 4.6875 -1.203125 3.953125 -1.203125 C 3.375 -1.203125 2.90625 -1.453125 2.625 -1.890625 C 2.4375 -2.171875 2.359375 -2.515625 2.328125 -3.25 Z M 2.359375 -4.59375 C 2.5 -5.78125 3 -6.375 3.890625 -6.375 C 4.390625 -6.375 4.859375 -6.125 5.140625 -5.71875 C 5.328125 -5.4375 5.421875 -5.125 5.453125 -4.59375 Z M 2.359375 -4.59375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-15">
<path style="stroke:none;" d="M 4.4375 -10.5 L 0.953125 -10.5 L 0.953125 2.875 L 4.4375 2.875 L 4.4375 1.40625 L 2.828125 1.40625 L 2.828125 -9.03125 L 4.4375 -9.03125 Z M 4.4375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-16">
<path style="stroke:none;" d="M 0.921875 -2.109375 L 0.921875 0 L 2.15625 0 L 2.15625 0.046875 C 2.15625 1.015625 1.765625 1.53125 0.921875 1.703125 L 0.921875 2.5 C 1.515625 2.4375 1.921875 2.28125 2.3125 1.96875 C 2.875 1.53125 3.078125 1 3.078125 -0.125 L 3.078125 -2.109375 Z M 0.921875 -2.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-17">
<path style="stroke:none;" d="M 2.703125 -10.5 L 0.71875 -10.5 L 0.71875 -8.625 L 1.296875 -6.765625 L 2.109375 -6.765625 L 2.703125 -8.625 Z M 6.109375 -10.5 L 4.125 -10.5 L 4.125 -8.625 L 4.703125 -6.765625 L 5.5 -6.765625 L 6.109375 -8.625 Z M 6.109375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-18">
<path style="stroke:none;" d="M 8.328125 1.734375 L -0.3125 1.734375 L -0.3125 2.71875 L 8.328125 2.71875 Z M 8.328125 1.734375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-19">
<path style="stroke:none;" d="M 5.109375 -3.921875 L 7.65625 -7.78125 L 5.234375 -7.78125 L 3.96875 -5.4375 L 2.703125 -7.78125 L 0.28125 -7.78125 L 2.828125 -3.921875 L 0.234375 0 L 2.65625 0 L 3.96875 -2.421875 L 5.28125 0 L 7.703125 0 Z M 5.109375 -3.921875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-20">
<path style="stroke:none;" d="M 0.265625 2.875 L 3.75 2.875 L 3.75 -10.5 L 0.265625 -10.5 L 0.265625 -9.03125 L 1.875 -9.03125 L 1.875 1.40625 L 0.265625 1.40625 Z M 0.265625 2.875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M 7.0625 -4.953125 L 7.0625 -6 L 4.328125 -6 C 3.390625 -6 2.734375 -5.890625 2.1875 -5.65625 C 1.015625 -5.125 0.359375 -4.1875 0.359375 -3.078125 C 0.359375 -2.296875 0.65625 -1.5 1.21875 -0.875 C 1.84375 -0.15625 2.515625 0.15625 3.46875 0.15625 C 4.28125 0.15625 4.984375 -0.09375 5.53125 -0.59375 C 6.078125 -1.078125 6.390625 -1.765625 6.390625 -2.40625 C 6.390625 -3.328125 5.703125 -4.21875 4.421875 -4.953125 Z M 3.859375 -4.953125 C 4.890625 -3.890625 5.125 -3.4375 5.125 -2.453125 C 5.125 -1.203125 4.53125 -0.359375 3.640625 -0.359375 C 2.53125 -0.359375 1.625 -1.578125 1.625 -3.046875 C 1.625 -4.203125 2.359375 -4.953125 3.484375 -4.953125 Z M 3.859375 -4.953125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M 2.453125 -2.28125 L 3.9375 -4.40625 L 3.140625 -4.40625 L 2.078125 -2.8125 L 1.03125 -4.40625 L 0.234375 -4.40625 L 1.703125 -2.25 L 0.140625 0 L 0.9375 0 L 2.0625 -1.6875 L 3.15625 0 L 3.96875 0 Z M 2.453125 -2.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph3-1">
<path style="stroke:none;" d="M -3.984375 -2.203125 L -3.984375 -6.375 L -4.96875 -6.375 L -4.96875 -2.203125 L -7.765625 -2.203125 L -7.765625 -6.953125 L -8.75 -6.953125 L -8.75 -1.078125 L 0 -1.078125 L 0 -2.203125 Z M -3.984375 -2.203125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-2">
<path style="stroke:none;" d="M -6.28125 -0.828125 L 0 -0.828125 L 0 -1.84375 L -3.265625 -1.84375 C -4.15625 -1.84375 -4.75 -2.0625 -5.09375 -2.546875 C -5.328125 -2.859375 -5.40625 -3.15625 -5.40625 -3.859375 L -6.4375 -3.859375 C -6.453125 -3.6875 -6.46875 -3.59375 -6.46875 -3.46875 C -6.46875 -2.8125 -6.078125 -2.328125 -5.140625 -1.75 L -6.28125 -1.75 Z M -6.28125 -0.828125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-3">
<path style="stroke:none;" d="M -2.8125 -6.15625 C -3.765625 -6.15625 -4.34375 -6.078125 -4.8125 -5.90625 C -5.84375 -5.5 -6.46875 -4.53125 -6.46875 -3.359375 C -6.46875 -1.609375 -5.125 -0.484375 -3.0625 -0.484375 C -1 -0.484375 0.28125 -1.578125 0.28125 -3.34375 C 0.28125 -4.78125 -0.546875 -5.765625 -1.90625 -6.03125 L -1.90625 -5.015625 C -1.078125 -4.734375 -0.640625 -4.171875 -0.640625 -3.375 C -0.640625 -2.734375 -0.9375 -2.203125 -1.46875 -1.859375 C -1.828125 -1.625 -2.1875 -1.53125 -2.8125 -1.53125 Z M -3.625 -1.546875 C -4.78125 -1.625 -5.546875 -2.34375 -5.546875 -3.34375 C -5.546875 -4.328125 -4.734375 -5.09375 -3.703125 -5.09375 C -3.671875 -5.09375 -3.640625 -5.09375 -3.625 -5.078125 Z M -3.625 -1.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-4">
<path style="stroke:none;" d="M 2.609375 -5.9375 L -6.28125 -5.9375 L -6.28125 -5.046875 L -5.453125 -5.046875 C -6.109375 -4.578125 -6.46875 -3.875 -6.46875 -3.046875 C -6.46875 -1.390625 -5.109375 -0.3125 -3.03125 -0.3125 C -0.984375 -0.3125 0.28125 -1.34375 0.28125 -3 C 0.28125 -3.875 -0.03125 -4.46875 -0.71875 -4.9375 L 2.609375 -4.9375 Z M -5.53125 -3.1875 C -5.53125 -4.265625 -4.578125 -4.9375 -3.0625 -4.9375 C -1.625 -4.9375 -0.65625 -4.25 -0.65625 -3.1875 C -0.65625 -2.09375 -1.625 -1.359375 -3.09375 -1.359375 C -4.546875 -1.359375 -5.53125 -2.09375 -5.53125 -3.1875 Z M -5.53125 -3.1875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-5">
<path style="stroke:none;" d="M 0 -5.78125 L -6.28125 -5.78125 L -6.28125 -4.78125 L -2.71875 -4.78125 C -1.4375 -4.78125 -0.59375 -4.109375 -0.59375 -3.078125 C -0.59375 -2.28125 -1.078125 -1.78125 -1.84375 -1.78125 L -6.28125 -1.78125 L -6.28125 -0.78125 L -1.4375 -0.78125 C -0.390625 -0.78125 0.28125 -1.5625 0.28125 -2.78125 C 0.28125 -3.703125 -0.046875 -4.296875 -0.875 -4.890625 L 0 -4.890625 Z M 0 -5.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-6">
<path style="stroke:none;" d="M -6.28125 -0.84375 L 0 -0.84375 L 0 -1.84375 L -3.46875 -1.84375 C -4.75 -1.84375 -5.59375 -2.515625 -5.59375 -3.546875 C -5.59375 -4.34375 -5.109375 -4.84375 -4.359375 -4.84375 L 0 -4.84375 L 0 -5.84375 L -4.75 -5.84375 C -5.796875 -5.84375 -6.46875 -5.0625 -6.46875 -3.859375 C -6.46875 -2.921875 -6.109375 -2.3125 -5.234375 -1.765625 L -6.28125 -1.765625 Z M -6.28125 -0.84375 "/>
</symbol>
<symbol overflow="visible" id="glyph3-7">
<path style="stroke:none;" d="M -4.171875 -5.65625 C -4.78125 -5.609375 -5.1875 -5.46875 -5.53125 -5.234375 C -6.125 -4.796875 -6.46875 -4.046875 -6.46875 -3.171875 C -6.46875 -1.46875 -5.125 -0.375 -3.03125 -0.375 C -1.015625 -0.375 0.28125 -1.453125 0.28125 -3.15625 C 0.28125 -4.65625 -0.625 -5.609375 -2.15625 -5.71875 L -2.15625 -4.71875 C -1.15625 -4.546875 -0.640625 -4.03125 -0.640625 -3.1875 C -0.640625 -2.078125 -1.546875 -1.421875 -3.03125 -1.421875 C -4.609375 -1.421875 -5.546875 -2.0625 -5.546875 -3.15625 C -5.546875 -4 -5.046875 -4.53125 -4.171875 -4.640625 Z M -4.171875 -5.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph3-8">
<path style="stroke:none;" d="M -6.28125 -4.65625 L -1.390625 -2.921875 L -6.28125 -1.3125 L -6.28125 -0.234375 L 0.03125 -2.359375 L 1.015625 -1.984375 C 1.46875 -1.828125 1.625 -1.59375 1.625 -1.171875 C 1.625 -1.03125 1.609375 -0.859375 1.5625 -0.640625 L 2.453125 -0.640625 C 2.5625 -0.859375 2.609375 -1.0625 2.609375 -1.3125 C 2.609375 -1.640625 2.515625 -1.984375 2.3125 -2.25 C 2.09375 -2.5625 1.828125 -2.75 1.3125 -2.9375 L -6.28125 -5.734375 Z M -6.28125 -4.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph3-9">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-10">
<path style="stroke:none;" d="M -6.0625 -3.109375 L 0 -3.109375 L 0 -4.15625 L -8.515625 -4.15625 L -8.515625 -3.46875 C -7.203125 -3.09375 -7.015625 -2.859375 -6.8125 -1.21875 L -6.0625 -1.21875 Z M -6.0625 -3.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph3-11">
<path style="stroke:none;" d="M -1.046875 -6.078125 L -1.046875 -1.59375 C -1.734375 -1.703125 -2.1875 -2.09375 -2.796875 -3.125 L -3.4375 -4.328125 C -4.09375 -5.515625 -4.96875 -6.125 -6.015625 -6.125 C -6.71875 -6.125 -7.375 -5.84375 -7.84375 -5.34375 C -8.296875 -4.84375 -8.515625 -4.21875 -8.515625 -3.40625 C -8.515625 -2.328125 -8.125 -1.53125 -7.40625 -1.0625 C -6.953125 -0.75 -6.421875 -0.625 -5.5625 -0.59375 L -5.5625 -1.65625 C -6.125 -1.6875 -6.484375 -1.765625 -6.75 -1.90625 C -7.265625 -2.1875 -7.578125 -2.734375 -7.578125 -3.375 C -7.578125 -4.328125 -6.90625 -5.046875 -5.984375 -5.046875 C -5.3125 -5.046875 -4.734375 -4.65625 -4.3125 -3.90625 L -3.6875 -2.796875 C -2.671875 -1.015625 -1.875 -0.5 0 -0.40625 L 0 -6.078125 Z M -1.046875 -6.078125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-12">
<path style="stroke:none;" d="M -3.90625 -2.65625 L -3.90625 -3.234375 C -3.90625 -4.390625 -3.390625 -4.984375 -2.359375 -4.984375 C -1.296875 -4.984375 -0.65625 -4.328125 -0.65625 -3.234375 C -0.65625 -2.078125 -1.234375 -1.515625 -2.46875 -1.4375 L -2.46875 -0.390625 C -1.78125 -0.4375 -1.34375 -0.546875 -0.953125 -0.75 C -0.140625 -1.1875 0.28125 -2.03125 0.28125 -3.1875 C 0.28125 -4.9375 -0.765625 -6.078125 -2.375 -6.078125 C -3.453125 -6.078125 -4.0625 -5.65625 -4.40625 -4.625 C -4.71875 -5.421875 -5.3125 -5.8125 -6.171875 -5.8125 C -7.625 -5.8125 -8.515625 -4.84375 -8.515625 -3.234375 C -8.515625 -1.515625 -7.578125 -0.59375 -5.765625 -0.5625 L -5.765625 -1.625 C -6.28125 -1.625 -6.5625 -1.6875 -6.828125 -1.8125 C -7.296875 -2.046875 -7.578125 -2.578125 -7.578125 -3.234375 C -7.578125 -4.171875 -7.03125 -4.734375 -6.125 -4.734375 C -5.53125 -4.734375 -5.171875 -4.53125 -4.984375 -4.0625 C -4.859375 -3.765625 -4.8125 -3.390625 -4.796875 -2.65625 Z M -3.90625 -2.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph4-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph4-1">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph4-2">
<path style="stroke:none;" d="M 2.296875 -1.25 L 1.046875 -1.25 L 1.046875 0 L 2.296875 0 Z M 2.296875 -1.25 "/>
</symbol>
<symbol overflow="visible" id="glyph4-3">
<path style="stroke:none;" d="M 2.65625 -3.90625 L 3.234375 -3.90625 C 4.390625 -3.90625 4.984375 -3.390625 4.984375 -2.359375 C 4.984375 -1.296875 4.328125 -0.65625 3.234375 -0.65625 C 2.078125 -0.65625 1.515625 -1.234375 1.4375 -2.46875 L 0.390625 -2.46875 C 0.4375 -1.78125 0.546875 -1.34375 0.75 -0.953125 C 1.1875 -0.140625 2.03125 0.28125 3.1875 0.28125 C 4.9375 0.28125 6.078125 -0.765625 6.078125 -2.375 C 6.078125 -3.453125 5.65625 -4.0625 4.625 -4.40625 C 5.421875 -4.71875 5.8125 -5.3125 5.8125 -6.171875 C 5.8125 -7.625 4.84375 -8.515625 3.234375 -8.515625 C 1.515625 -8.515625 0.59375 -7.578125 0.5625 -5.765625 L 1.625 -5.765625 C 1.625 -6.28125 1.6875 -6.5625 1.8125 -6.828125 C 2.046875 -7.296875 2.578125 -7.578125 3.234375 -7.578125 C 4.171875 -7.578125 4.734375 -7.03125 4.734375 -6.125 C 4.734375 -5.53125 4.53125 -5.171875 4.0625 -4.984375 C 3.765625 -4.859375 3.390625 -4.8125 2.65625 -4.796875 Z M 2.65625 -3.90625 "/>
</symbol>
<symbol overflow="visible" id="glyph4-4">
<path style="stroke:none;" d="M 3.921875 -2.046875 L 3.921875 0 L 4.984375 0 L 4.984375 -2.046875 L 6.234375 -2.046875 L 6.234375 -2.984375 L 4.984375 -2.984375 L 4.984375 -8.515625 L 4.203125 -8.515625 L 0.34375 -3.15625 L 0.34375 -2.046875 Z M 3.921875 -2.984375 L 1.265625 -2.984375 L 3.921875 -6.703125 Z M 3.921875 -2.984375 "/>
</symbol>
<symbol overflow="visible" id="glyph4-5">
<path style="stroke:none;" d="M 5.71875 -8.515625 L 1.3125 -8.515625 L 0.6875 -3.875 L 1.65625 -3.875 C 2.140625 -4.46875 2.5625 -4.671875 3.21875 -4.671875 C 4.359375 -4.671875 5.078125 -3.890625 5.078125 -2.625 C 5.078125 -1.40625 4.375 -0.65625 3.21875 -0.65625 C 2.296875 -0.65625 1.734375 -1.125 1.46875 -2.09375 L 0.421875 -2.09375 C 0.5625 -1.390625 0.6875 -1.0625 0.9375 -0.75 C 1.421875 -0.09375 2.28125 0.28125 3.234375 0.28125 C 4.953125 0.28125 6.15625 -0.96875 6.15625 -2.765625 C 6.15625 -4.453125 5.046875 -5.609375 3.40625 -5.609375 C 2.8125 -5.609375 2.328125 -5.453125 1.84375 -5.09375 L 2.171875 -7.46875 L 5.71875 -7.46875 Z M 5.71875 -8.515625 "/>
</symbol>
</g>
</defs>
<g id="surface837">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="-33.601562" y="34.116211"/>
  <use xlink:href="#glyph0-2" x="-23.200195" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="-19.195312" y="34.116211"/>
  <use xlink:href="#glyph0-4" x="-11.185547" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="-6.388672" y="34.116211"/>
  <use xlink:href="#glyph0-6" x="2.413086" y="34.116211"/>
  <use xlink:href="#glyph0-7" x="11.214844" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="16.819336" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="24.829102" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="37.635742" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="41.640625" y="34.116211"/>
  <use xlink:href="#glyph0-11" x="50.442383" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="55.239258" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="59.244141" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="67.253906" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="75.263672" y="34.116211"/>
  <use xlink:href="#glyph0-12" x="88.070312" y="34.116211"/>
  <use xlink:href="#glyph0-13" x="96.87207" y="34.116211"/>
  <use xlink:href="#glyph0-14" x="100.876953" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="108.886719" y="34.116211"/>
  <use xlink:href="#glyph0-15" x="116.896484" y="34.116211"/>
  <use xlink:href="#glyph0-16" x="121.693359" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="125.698242" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="129.703125" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="136.53125" y="34.116211"/>
  <use xlink:href="#glyph0-2" x="144.541016" y="34.116211"/>
  <use xlink:href="#glyph0-6" x="148.545898" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="157.347656" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="170.154297" y="34.116211"/>
  <use xlink:href="#glyph0-18" x="178.164062" y="34.116211"/>
  <use xlink:href="#glyph0-19" x="186.173828" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="194.183594" y="34.116211"/>
  <use xlink:href="#glyph0-20" x="201.011719" y="34.116211"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="79.898438" y="193.948242"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="87.898438" y="196.286133"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-1" x="12.396484" y="129.300781"/>
  <use xlink:href="#glyph3-2" x="12.396484" y="121.96875"/>
  <use xlink:href="#glyph3-3" x="12.396484" y="117.972656"/>
  <use xlink:href="#glyph3-4" x="12.396484" y="111.300781"/>
  <use xlink:href="#glyph3-5" x="12.396484" y="104.628906"/>
  <use xlink:href="#glyph3-3" x="12.396484" y="97.957031"/>
  <use xlink:href="#glyph3-6" x="12.396484" y="91.285156"/>
  <use xlink:href="#glyph3-7" x="12.396484" y="84.613281"/>
  <use xlink:href="#glyph3-8" x="12.396484" y="78.613281"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 108.566406 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 61.066406 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 76.898438 142.558594 L 76.898438 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 92.734375 142.558594 L 92.734375 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 108.566406 142.558594 L 108.566406 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph4-1" x="49.066406" y="167.916016"/>
  <use xlink:href="#glyph4-2" x="55.738281" y="167.916016"/>
  <use xlink:href="#glyph4-3" x="59.074219" y="167.916016"/>
  <use xlink:href="#glyph4-1" x="65.746094" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph4-1" x="96.566406" y="167.916016"/>
  <use xlink:href="#glyph4-2" x="103.238281" y="167.916016"/>
  <use xlink:href="#glyph4-4" x="106.574219" y="167.916016"/>
  <use xlink:href="#glyph4-5" x="113.246094" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 59.039062 59.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 51.839844 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 126.132812 L 51.839844 126.132812 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 112.800781 L 51.839844 112.800781 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 99.464844 L 51.839844 99.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 86.132812 L 51.839844 86.132812 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 72.800781 L 51.839844 72.800781 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 59.464844 L 51.839844 59.464844 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-9" x="41.197266" y="142.964844"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-10" x="41.197266" y="119.800781"/>
  <use xlink:href="#glyph3-9" x="41.197266" y="113.128906"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-11" x="41.197266" y="93.132812"/>
  <use xlink:href="#glyph3-9" x="41.197266" y="86.460938"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-12" x="41.197266" y="66.464844"/>
  <use xlink:href="#glyph3-9" x="41.197266" y="59.792969"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 139.464844 L 67.398438 139.464844 L 67.398438 136.796875 L 61.066406 136.796875 Z M 61.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 67.398438 139.464844 L 73.730469 139.464844 L 73.730469 131.464844 L 67.398438 131.464844 Z M 67.398438 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 73.734375 139.464844 L 80.066406 139.464844 L 80.066406 99.464844 L 73.734375 99.464844 Z M 73.734375 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 80.066406 139.464844 L 86.398438 139.464844 L 86.398438 62.132812 L 80.066406 62.132812 Z M 80.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 86.398438 139.464844 L 92.730469 139.464844 L 92.730469 83.464844 L 86.398438 83.464844 Z M 86.398438 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 92.734375 139.464844 L 99.066406 139.464844 L 99.066406 80.796875 L 92.734375 80.796875 Z M 92.734375 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 99.066406 139.464844 L 105.398438 139.464844 L 105.398438 120.796875 L 99.066406 120.796875 Z M 99.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 105.398438 139.464844 L 111.730469 139.464844 L 111.730469 134.132812 L 105.398438 134.132812 Z M 105.398438 139.464844 "/>
</g>
</svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 7.296875 -4.765625 L 7.296875 0 L 9.46875 0 L 9.46875 -10.5 L 7.296875 -10.5 L 7.296875 -6.5625 L 3.140625 -6.5625 L 3.140625 -10.5 L 0.984375 -10.5 L 0.984375 0 L 3.140625 0 L 3.140625 -4.765625 Z M 7.296875 -4.765625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 2.984375 -7.78125 L 0.96875 -7.78125 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 -8.703125 L 2.984375 -8.703125 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 7.28125 -5.265625 C 7.25 -6.921875 5.984375 -7.90625 3.890625 -7.90625 C 1.921875 -7.90625 0.6875 -6.921875 0.6875 -5.3125 C 0.6875 -4.796875 0.84375 -4.34375 1.125 -4.046875 C 1.390625 -3.78125 1.640625 -3.640625 2.390625 -3.40625 L 4.796875 -2.65625 C 5.296875 -2.5 5.46875 -2.328125 5.46875 -2.015625 C 5.46875 -1.546875 4.90625 -1.25 3.96875 -1.25 C 3.453125 -1.25 3.046875 -1.359375 2.78125 -1.53125 C 2.5625 -1.6875 2.484375 -1.84375 2.390625 -2.265625 L 0.421875 -2.265625 C 0.46875 -0.5625 1.734375 0.328125 4.09375 0.328125 C 5.171875 0.328125 6 0.09375 6.5625 -0.359375 C 7.140625 -0.828125 7.484375 -1.546875 7.484375 -2.3125 C 7.484375 -3.3125 6.984375 -3.96875 5.96875 -4.265625 L 3.421875 -5 C 2.859375 -5.171875 2.703125 -5.28125 2.703125 -5.609375 C 2.703125 -6.03125 3.171875 -6.328125 3.875 -6.328125 C 4.84375 -6.328125 5.3125 -5.984375 5.328125 -5.265625 Z M 7.28125 -5.265625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 4.34375 -7.625 L 3.21875 -7.625 L 3.21875 -9.703125 L 1.203125 -9.703125 L 1.203125 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.203125 -6.28125 L 1.203125 -1.5 C 1.203125 -0.28125 1.84375 0.328125 3.171875 0.328125 C 3.609375 0.328125 3.96875 0.28125 4.34375 0.171875 L 4.34375 -1.234375 C 4.140625 -1.203125 4.015625 -1.203125 3.875 -1.203125 C 3.34375 -1.203125 3.21875 -1.359375 3.21875 -2.046875 L 3.21875 -6.28125 L 4.34375 -6.28125 Z M 4.34375 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 4.34375 -7.90625 C 1.953125 -7.90625 0.5 -6.34375 0.5 -3.78125 C 0.5 -1.21875 1.953125 0.328125 4.34375 0.328125 C 6.71875 0.328125 8.203125 -1.234375 8.203125 -3.734375 C 8.203125 -6.375 6.765625 -7.90625 4.34375 -7.90625 Z M 4.34375 -6.28125 C 5.453125 -6.28125 6.1875 -5.28125 6.1875 -3.765625 C 6.1875 -2.3125 5.4375 -1.296875 4.34375 -1.296875 C 3.25 -1.296875 2.515625 -2.3125 2.515625 -3.78125 C 2.515625 -5.265625 3.25 -6.28125 4.34375 -6.28125 Z M 4.34375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 5.875 -7.78125 L 5.875 -6.578125 C 5.265625 -7.5 4.609375 -7.90625 3.71875 -7.90625 C 1.875 -7.90625 0.484375 -6.109375 0.484375 -3.703125 C 0.484375 -1.28125 1.75 0.328125 3.671875 0.328125 C 4.578125 0.328125 5.125 0.0625 5.875 -0.796875 L 5.875 0.265625 C 5.875 1.203125 5.171875 1.84375 4.15625 1.84375 C 3.40625 1.84375 2.890625 1.53125 2.734375 0.9375 L 0.640625 0.9375 C 0.65625 1.546875 0.890625 1.953125 1.40625 2.390625 C 2.03125 2.890625 2.890625 3.140625 4.09375 3.140625 C 6.4375 3.140625 7.796875 2.09375 7.796875 0.265625 L 7.796875 -7.78125 Z M 4.15625 -6.21875 C 5.15625 -6.21875 5.90625 -5.171875 5.90625 -3.734375 C 5.90625 -2.3125 5.171875 -1.359375 4.125 -1.359375 C 3.171875 -1.359375 2.5 -2.3125 2.5 -3.734375 C 2.5 -5.203125 3.171875 -6.21875 4.15625 -6.21875 Z M 4.15625 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 0.90625 -7.78125 L 0.90625 0 L 2.921875 0 L 2.921875 -4.140625 C 2.921875 -5.3125 3.515625 -5.90625 4.703125 -5.90625 C 4.90625 -5.90625 5.0625 -5.890625 5.328125 -5.84375 L 5.328125 -7.890625 C 5.21875 -7.90625 5.140625 -7.90625 5.078125 -7.90625 C 4.15625 -7.90625 3.359375 -7.296875 2.921875 -6.25 L 2.921875 -7.78125 Z M 0.90625 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 7.546875 -0.25 C 7.1875 -0.578125 7.09375 -0.796875 7.09375 -1.203125 L 7.09375 -5.515625 C 7.09375 -7.109375 6 -7.90625 3.90625 -7.90625 C 1.796875 -7.90625 0.703125 -7.015625 0.578125 -5.21875 L 2.515625 -5.21875 C 2.625 -6.015625 2.953125 -6.28125 3.953125 -6.28125 C 4.71875 -6.28125 5.109375 -6.015625 5.109375 -5.5 C 5.109375 -5.25 4.984375 -5.015625 4.765625 -4.890625 C 4.5 -4.75 4.5 -4.75 3.5 -4.59375 L 2.6875 -4.453125 C 1.15625 -4.1875 0.40625 -3.40625 0.40625 -2 C 0.40625 -1.34375 0.59375 -0.796875 0.953125 -0.40625 C 1.390625 0.0625 2.078125 0.328125 2.765625 0.328125 C 3.625 0.328125 4.421875 -0.046875 5.125 -0.78125 C 5.125 -0.375 5.171875 -0.234375 5.359375 0 L 7.546875 0 Z M 5.109375 -3.125 C 5.109375 -1.953125 4.53125 -1.296875 3.515625 -1.296875 C 2.84375 -1.296875 2.421875 -1.65625 2.421875 -2.234375 C 2.421875 -2.84375 2.734375 -3.125 3.578125 -3.296875 L 4.265625 -3.421875 C 4.796875 -3.53125 4.890625 -3.5625 5.109375 -3.671875 Z M 5.109375 -3.125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.859375 -7.78125 L 0.859375 0 L 2.875 0 L 2.875 -4.671875 C 2.875 -5.625 3.40625 -6.1875 4.265625 -6.1875 C 4.9375 -6.1875 5.359375 -5.8125 5.359375 -5.1875 L 5.359375 0 L 7.375 0 L 7.375 -4.671875 C 7.375 -5.625 7.890625 -6.1875 8.765625 -6.1875 C 9.4375 -6.1875 9.859375 -5.8125 9.859375 -5.1875 L 9.859375 0 L 11.875 0 L 11.875 -5.5 C 11.875 -7.015625 10.953125 -7.90625 9.390625 -7.90625 C 8.40625 -7.90625 7.71875 -7.5625 7.109375 -6.75 C 6.734375 -7.484375 5.96875 -7.90625 5 -7.90625 C 4.109375 -7.90625 3.53125 -7.609375 2.859375 -6.8125 L 2.859375 -7.78125 Z M 0.859375 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-10">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-11">
<path style="stroke:none;" d="M 4.515625 -7.625 L 3.3125 -7.625 L 3.3125 -8.390625 C 3.3125 -8.78125 3.484375 -8.984375 3.859375 -8.984375 C 4.03125 -8.984375 4.265625 -8.96875 4.4375 -8.953125 L 4.4375 -10.453125 C 4.0625 -10.484375 3.5625 -10.5 3.28125 -10.5 C 1.9375 -10.5 1.296875 -9.875 1.296875 -8.5625 L 1.296875 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.296875 -6.28125 L 1.296875 0 L 3.3125 0 L 3.3125 -6.28125 L 4.515625 -6.28125 Z M 4.515625 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-12">
<path style="stroke:none;" d="M 2.859375 -7.78125 L 0.828125 -7.78125 L 0.828125 3.140625 L 2.859375 3.140625 L 2.859375 -0.921875 C 3.34375 -0.0625 4.03125 0.34375 5.015625 0.34375 C 6.890625 0.34375 8.265625 -1.40625 8.265625 -3.78125 C 8.265625 -4.875 7.953125 -5.96875 7.4375 -6.6875 C 6.921875 -7.421875 5.953125 -7.90625 5.015625 -7.90625 C 4.03125 -7.90625 3.34375 -7.484375 2.859375 -6.625 Z M 4.546875 -6.21875 C 5.578125 -6.21875 6.25 -5.234375 6.25 -3.75 C 6.25 -2.328125 5.546875 -1.34375 4.546875 -1.34375 C 3.546875 -1.34375 2.859375 -2.3125 2.859375 -3.78125 C 2.859375 -5.234375 3.546875 -6.21875 4.546875 -6.21875 Z M 4.546875 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-13">
<path style="stroke:none;" d="M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-14">
<path style="stroke:none;" d="M 7.546875 -3.25 C 7.5625 -3.421875 7.5625 -3.5 7.5625 -3.59375 C 7.5625 -4.375 7.453125 -5.09375 7.265625 -5.640625 C 6.734375 -7.0625 5.484375 -7.90625 3.921875 -7.90625 C 1.6875 -7.90625 0.3125 -6.296875 0.3125 -3.6875 C 0.3125 -1.203125 1.671875 0.328125 3.875 0.328125 C 5.625 0.328125 7.03125 -0.65625 7.484375 -2.1875 L 5.484375 -2.1875 C 5.25 -1.5625 4.6875 -1.203125 3.953125 -1.203125 C 3.375 -1.203125 2.90625 -1.453125 2.625 -1.890625 C 2.4375 -2.171875 2.359375 -2.515625 2.328125 -3.25 Z M 2.359375 -4.59375 C 2.5 -5.78125 3 -6.375 3.890625 -6.375 C 4.390625 -6.375 4.859375 -6.125 5.140625 -5.71875 C 5.328125 -5.4375 5.421875 -5.125 5.453125 -4.59375 Z M 2.359375 -4.59375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-15">
<path style="stroke:none;" d="M 4.4375 -10.5 L 0.953125 -10.5 L 0.953125 2.875 L 4.4375 2.875 L 4.4375 1.40625 L 2.828125 1.40625 L 2.828125 -9.03125 L 4.4375 -9.03125 Z M 4.4375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-16">
<path style="stroke:none;" d="M 0.921875 -2.109375 L 0.921875 0 L 2.15625 0 L 2.15625 0.046875 C 2.15625 1.015625 1.765625 1.53125 0.921875 1.703125 L 0.921875 2.5 C 1.515625 2.4375 1.921875 2.28125 2.3125 1.96875 C 2.875 1.53125 3.078125 1 3.078125 -0.125 L 3.078125 -2.109375 Z M 0.921875 -2.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-17">
<path style="stroke:none;" d="M 2.703125 -10.5 L 0.71875 -10.5 L 0.71875 -8.625 L 1.296875 -6.765625 L 2.109375 -6.765625 L 2.703125 -8.625 Z M 6.109375 -10.5 L 4.125 -10.5 L 4.125 -8.625 L 4.703125 -6.765625 L 5.5 -6.765625 L 6.109375 -8.625 Z M 6.109375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-18">
<path style="stroke:none;" d="M 8.328125 1.734375 L -0.3125 1.734375 L -0.3125 2.71875 L 8.328125 2.71875 Z M 8.328125 1.734375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-19">
<path style="stroke:none;" d="M 5.671875 -7.78125 L 4.0625 -2.125 L 2.34375 -7.78125 L 0.125 -7.78125 L 3.03125 0.3125 L 3.03125 0.375 C 3.03125 1.109375 2.484375 1.671875 1.765625 1.671875 C 1.609375 1.671875 1.5 1.65625 1.234375 1.578125 L 1.234375 3.09375 C 1.546875 3.140625 1.71875 3.15625 1.953125 3.15625 C 2.46875 3.15625 3.0625 3.046875 3.421875 2.90625 C 3.96875 2.671875 4.21875 2.34375 4.546875 1.421875 L 7.75 -7.78125 Z M 5.671875 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-20">
<path style="stroke:none;" d="M 0.265625 2.875 L 3.75 2.875 L 3.75 -10.5 L 0.265625 -10.5 L 0.265625 -9.03125 L 1.875 -9.03125 L 1.875 1.40625 L 0.265625 1.40625 Z M 0.265625 2.875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M 7.0625 -4.953125 L 7.0625 -6 L 4.328125 -6 C 3.390625 -6 2.734375 -5.890625 2.1875 -5.65625 C 1.015625 -5.125 0.359375 -4.1875 0.359375 -3.078125 C 0.359375 -2.296875 0.65625 -1.5 1.21875 -0.875 C 1.84375 -0.15625 2.515625 0.15625 3.46875 0.15625 C 4.28125 0.15625 4.984375 -0.09375 5.53125 -0.59375 C 6.078125 -1.078125 6.390625 -1.765625 6.390625 -2.40625 C 6.390625 -3.328125 5.703125 -4.21875 4.421875 -4.953125 Z M 3.859375 -4.953125 C 4.890625 -3.890625 5.125 -3.4375 5.125 -2.453125 C 5.125 -1.203125 4.53125 -0.359375 3.640625 -0.359375 C 2.53125 -0.359375 1.625 -1.578125 1.625 -3.046875 C 1.625 -4.203125 2.359375 -4.953125 3.484375 -4.953125 Z M 3.859375 -4.953125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M 3.265625 -4.40625 L 2.046875 -0.96875 L 0.921875 -4.40625 L 0.171875 -4.40625 L 1.65625 0.015625 L 1.390625 0.71875 C 1.28125 1.03125 1.125 1.140625 0.828125 1.140625 C 0.71875 1.140625 0.609375 1.125 0.453125 1.09375 L 0.453125 1.71875 C 0.59375 1.796875 0.734375 1.828125 0.921875 1.828125 C 1.15625 1.828125 1.390625 1.75 1.578125 1.625 C 1.796875 1.46875 1.921875 1.28125 2.0625 0.921875 L 4.015625 -4.40625 Z M 3.265625 -4.40625 "/>
</symbol>
<symbol overflow="visible" id="glyph3-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph3-1">
<path style="stroke:none;" d="M -3.984375 -2.203125 L -3.984375 -6.375 L -4.96875 -6.375 L -4.96875 -2.203125 L -7.765625 -2.203125 L -7.765625 -6.953125 L -8.75 -6.953125 L -8.75 -1.078125 L 0 -1.078125 L 0 -2.203125 Z M -3.984375 -2.203125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-2">
<path style="stroke:none;" d="M -6.28125 -0.828125 L 0 -0.828125 L 0 -1.84375 L -3.265625 -1.84375 C -4.15625 -1.84375 -4.75 -2.0625 -5.09375 -2.546875 C -5.328125 -2.859375 -5.40625 -3.15625 -5.40625 -3.859375 L -6.4375 -3.859375 C -6.453125 -3.6875 -6.46875 -3.59375 -6.46875 -3.46875 C -6.46875 -2.8125 -6.078125 -2.328125 -5.140625 -1.75 L -6.28125 -1.75 Z M -6.28125 -0.828125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-3">
<path style="stroke:none;" d="M -2.8125 -6.15625 C -3.765625 -6.15625 -4.34375 -6.078125 -4.8125 -5.90625 C -5.84375 -5.5 -6.46875 -4.53125 -6.46875 -3.359375 C -6.46875 -1.609375 -5.125 -0.484375 -3.0625 -0.484375 C -1 -0.484375 0.28125 -1.578125 0.28125 -3.34375 C 0.28125 -4.78125 -0.546875 -5.765625 -1.90625 -6.03125 L -1.90625 -5.015625 C -1.078125 -4.734375 -0.640625 -4.171875 -0.640625 -3.375 C -0.640625 -2.734375 -0.9375 -2.203125 -1.46875 -1.859375 C -1.828125 -1.625 -2.1875 -1.53125 -2.8125 -1.53125 Z M -3.625 -1.546875 C -4.78125 -1.625 -5.546875 -2.34375 -5.546875 -3.34375 C -5.546875 -4.328125 -4.734375 -5.09375 -3.703125 -5.09375 C -3.671875 -5.09375 -3.640625 -5.09375 -3.625 -5.078125 Z M -3.625 -1.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-4">
<path style="stroke:none;" d="M 2.609375 -5.9375 L -6.28125 -5.9375 L -6.28125 -5.046875 L -5.453125 -5.046875 C -6.109375 -4.578125 -6.46875 -3.875 -6.46875 -3.046875 C -6.46875 -1.390625 -5.109375 -0.3125 -3.03125 -0.3125 C -0.984375 -0.3125 0.28125 -1.34375 0.28125 -3 C 0.28125 -3.875 -0.03125 -4.46875 -0.71875 -4.9375 L 2.609375 -4.9375 Z M -5.53125 -3.1875 C -5.53125 -4.265625 -4.578125 -4.9375 -3.0625 -4.9375 C -1.625 -4.9375 -0.65625 -4.25 -0.65625 -3.1875 C -0.65625 -2.09375 -1.625 -1.359375 -3.09375 -1.359375 C -4.546875 -1.359375 -5.53125 -2.09375 -5.53125 -3.1875 Z M -5.53125 -3.1875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-5">
<path style="stroke:none;" d="M 0 -5.78125 L -6.28125 -5.78125 L -6.28125 -4.78125 L -2.71875 -4.78125 C -1.4375 -4.78125 -0.59375 -4.109375 -0.59375 -3.078125 C -0.59375 -2.28125 -1.078125 -1.78125 -1.84375 -1.78125 L -6.28125 -1.78125 L -6.28125 -0.78125 L -1.4375 -0.78125 C -0.390625 -0.78125 0.28125 -1.5625 0.28125 -2.78125 C 0.28125 -3.703125 -0.046875 -4.296875 -0.875 -4.890625 L 0 -4.890625 Z M 0 -5.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-6">
<path style="stroke:none;" d="M -6.28125 -0.84375 L 0 -0.84375 L 0 -1.84375 L -3.46875 -1.84375 C -4.75 -1.84375 -5.59375 -2.515625 -5.59375 -3.546875 C -5.59375 -4.34375 -5.109375 -4.84375 -4.359375 -4.84375 L 0 -4.84375 L 0 -5.84375 L -4.75 -5.84375 C -5.796875 -5.84375 -6.46875 -5.0625 -6.46875 -3.859375 C -6.46875 -2.921875 -6.109375 -2.3125 -5.234375 -1.765625 L -6.28125 -1.765625 Z M -6.28125 -0.84375 "/>
</symbol>
<symbol overflow="visible" id="glyph3-7">
<path style="stroke:none;" d="M -4.171875 -5.65625 C -4.78125 -5.609375 -5.1875 -5.46875 -5.53125 -5.234375 C -6.125 -4.796875 -6.46875 -4.046875 -6.46875 -3.171875 C -6.46875 -1.46875 -5.125 -0.375 -3.03125 -0.375 C -1.015625 -0.375 0.28125 -1.453125 0.28125 -3.15625 C 0.28125 -4.65625 -0.625 -5.609375 -2.15625 -5.71875 L -2.15625 -4.71875 C -1.15625 -4.546875 -0.640625 -4.03125 -0.640625 -3.1875 C -0.640625 -2.078125 -1.546875 -1.421875 -3.03125 -1.421875 C -4.609375 -1.421875 -5.546875 -2.0625 -5.546875 -3.15625 C -5.546875 -4 -5.046875 -4.53125 -4.171875 -4.640625 Z M -4.171875 -5.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph3-8">
<path style="stroke:none;" d="M -6.28125 -4.65625 L -1.390625 -2.921875 L -6.28125 -1.3125 L -6.28125 -0.234375 L 0.03125 -2.359375 L 1.015625 -1.984375 C 1.46875 -1.828125 1.625 -1.59375 1.625 -1.171875 C 1.625 -1.03125 1.609375 -0.859375 1.5625 -0.640625 L 2.453125 -0.640625 C 2.5625 -0.859375 2.609375 -1.0625 2.609375 -1.3125 C 2.609375 -1.640625 2.515625 -1.984375 2.3125 -2.25 C 2.09375 -2.5625 1.828125 -2.75 1.3125 -2.9375 L -6.28125 -5.734375 Z M -6.28125 -4.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph3-9">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-10">
<path style="stroke:none;" d="M -1.046875 -6.078125 L -1.046875 -1.59375 C -1.734375 -1.703125 -2.1875 -2.09375 -2.796875 -3.125 L -3.4375 -4.328125 C -4.09375 -5.515625 -4.96875 -6.125 -6.015625 -6.125 C -6.71875 -6.125 -7.375 -5.84375 -7.84375 -5.34375 C -8.296875 -4.84375 -8.515625 -4.21875 -8.515625 -3.40625 C -8.515625 -2.328125 -8.125 -1.53125 -7.40625 -1.0625 C -6.953125 -0.75 -6.421875 -0.625 -5.5625 -0.59375 L -5.5625 -1.65625 C -6.125 -1.6875 -6.484375 -1.765625 -6.75 -1.90625 C -7.265625 -2.1875 -7.578125 -2.734375 -7.578125 -3.375 C -7.578125 -4.328125 -6.90625 -5.046875 -5.984375 -5.046875 C -5.3125 -5.046875 -4.734375 -4.65625 -4.3125 -3.90625 L -3.6875 -2.796875 C -2.671875 -1.015625 -1.875 -0.5 0 -0.40625 L 0 -6.078125 Z M -1.046875 -6.078125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-11">
<path style="stroke:none;" d="M -2.046875 -3.921875 L 0 -3.921875 L 0 -4.984375 L -2.046875 -4.984375 L -2.046875 -6.234375 L -2.984375 -6.234375 L -2.984375 -4.984375 L -8.515625 -4.984375 L -8.515625 -4.203125 L -3.15625 -0.34375 L -2.046875 -0.34375 Z M -2.984375 -3.921875 L -2.984375 -1.265625 L -6.703125 -3.921875 Z M -2.984375 -3.921875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-12">
<path style="stroke:none;" d="M -6.28125 -5.96875 C -7.6875 -5.765625 -8.515625 -4.859375 -8.515625 -3.5625 C -8.515625 -2.625 -8.046875 -1.78125 -7.296875 -1.28125 C -6.46875 -0.75 -5.421875 -0.515625 -3.875 -0.515625 C -2.453125 -0.515625 -1.53125 -0.734375 -0.78125 -1.234375 C -0.09375 -1.6875 0.28125 -2.4375 0.28125 -3.375 C 0.28125 -4.984375 -0.921875 -6.15625 -2.59375 -6.15625 C -4.171875 -6.15625 -5.296875 -5.078125 -5.296875 -3.546875 C -5.296875 -2.71875 -4.96875 -2.046875 -4.34375 -1.59375 C -6.421875 -1.609375 -7.578125 -2.28125 -7.578125 -3.484375 C -7.578125 -4.234375 -7.109375 -4.75 -6.28125 -4.921875 Z M -4.359375 -3.421875 C -4.359375 -4.4375 -3.640625 -5.078125 -2.515625 -5.078125 C -1.4375 -5.078125 -0.65625 -4.359375 -0.65625 -3.390625 C -0.65625 -2.40625 -1.46875 -1.65625 -2.5625 -1.65625 C -3.625 -1.65625 -4.359375 -2.375 -4.359375 -3.421875 Z M -4.359375 -3.421875 "/>
</symbol>
<symbol overflow="visible" id="glyph4-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph4-1">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph4-2">
<path style="stroke:none;" d="M 2.296875 -1.25 L 1.046875 -1.25 L 1.046875 0 L 2.296875 0 Z M 2.296875 -1.25 "/>
</symbol>
<symbol overflow="visible" id="glyph4-3">
<path style="stroke:none;" d="M 6.078125 -1.046875 L 1.59375 -1.046875 C 1.703125 -1.734375 2.09375 -2.1875 3.125 -2.796875 L 4.328125 -3.4375 C 5.515625 -4.09375 6.125 -4.96875 6.125 -6.015625 C 6.125 -6.71875 5.84375 -7.375 5.34375 -7.84375 C 4.84375 -8.296875 4.21875 -8.515625 3.40625 -8.515625 C 2.328125 -8.515625 1.53125 -8.125 1.0625 -7.40625 C 0.75 -6.953125 0.625 -6.421875 0.59375 -5.5625 L 1.65625 -5.5625 C 1.6875 -6.125 1.765625 -6.484375 1.90625 -6.75 C 2.1875 -7.265625 2.734375 -7.578125 3.375 -7.578125 C 4.328125 -7.578125 5.046875 -6.90625 5.046875 -5.984375 C 5.046875 -5.3125 4.65625 -4.734375 3.90625 -4.3125 L 2.796875 -3.6875 C 1.015625 -2.671875 0.5 -1.875 0.40625 0 L 6.078125 0 Z M 6.078125 -1.046875 "/>
</symbol>
<symbol overflow="visible" id="glyph4-4">
<path style="stroke:none;" d="M 5.71875 -8.515625 L 1.3125 -8.515625 L 0.6875 -3.875 L 1.65625 -3.875 C 2.140625 -4.46875 2.5625 -4.671875 3.21875 -4.671875 C 4.359375 -4.671875 5.078125 -3.890625 5.078125 -2.625 C 5.078125 -1.40625 4.375 -0.65625 3.21875 -0.65625 C 2.296875 -0.65625 1.734375 -1.125 1.46875 -2.09375 L 0.421875 -2.09375 C 0.5625 -1.390625 0.6875 -1.0625 0.9375 -0.75 C 1.421875 -0.09375 2.28125 0.28125 3.234375 0.28125 C 4.953125 0.28125 6.15625 -0.96875 6.15625 -2.765625 C 6.15625 -4.453125 5.046875 -5.609375 3.40625 -5.609375 C 2.8125 -5.609375 2.328125 -5.453125 1.84375 -5.09375 L 2.171875 -7.46875 L 5.71875 -7.46875 Z M 5.71875 -8.515625 "/>
</symbol>
</g>
</defs>
<g id="surface842">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="-33.601562" y="34.116211"/>
  <use xlink:href="#glyph0-2" x="-23.200195" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="-19.195312" y="34.116211"/>
  <use xlink:href="#glyph0-4" x="-11.185547" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="-6.388672" y="34.116211"/>
  <use xlink:href="#glyph0-6" x="2.413086" y="34.116211"/>
  <use xlink:href="#glyph0-7" x="11.214844" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="16.819336" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="24.829102" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="37.635742" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="41.640625" y="34.116211"/>
  <use xlink:href="#glyph0-11" x="50.442383" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="55.239258" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="59.244141" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="67.253906" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="75.263672" y="34.116211"/>
  <use xlink:href="#glyph0-12" x="88.070312" y="34.116211"/>
  <use xlink:href="#glyph0-13" x="96.87207" y="34.116211"/>
  <use xlink:href="#glyph0-14" x="100.876953" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="108.886719" y="34.116211"/>
  <use xlink:href="#glyph0-15" x="116.896484" y="34.116211"/>
  <use xlink:href="#glyph0-16" x="121.693359" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="125.698242" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="129.703125" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="136.53125" y="34.116211"/>
  <use xlink:href="#glyph0-2" x="144.541016" y="34.116211"/>
  <use xlink:href="#glyph0-6" x="148.545898" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="157.347656" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="170.154297" y="34.116211"/>
  <use xlink:href="#glyph0-18" x="178.164062" y="34.116211"/>
  <use xlink:href="#glyph0-19" x="186.173828" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="194.183594" y="34.116211"/>
  <use xlink:href="#glyph0-20" x="201.011719" y="34.116211"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="79.898438" y="191.948242"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="87.898438" y="194.286133"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-1" x="12.396484" y="129.300781"/>
  <use xlink:href="#glyph3-2" x="12.396484" y="121.96875"/>
  <use xlink:href="#glyph3-3" x="12.396484" y="117.972656"/>
  <use xlink:href="#glyph3-4" x="12.396484" y="111.300781"/>
  <use xlink:href="#glyph3-5" x="12.396484" y="104.628906"/>
  <use xlink:href="#glyph3-3" x="12.396484" y="97.957031"/>
  <use xlink:href="#glyph3-6" x="12.396484" y="91.285156"/>
  <use xlink:href="#glyph3-7" x="12.396484" y="84.613281"/>
  <use xlink:href="#glyph3-8" x="12.396484" y="78.613281"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 61.066406 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 69.511719 142.558594 L 69.511719 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 77.957031 142.558594 L 77.957031 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 86.398438 142.558594 L 86.398438 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 94.84375 142.558594 L 94.84375 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 103.289062 142.558594 L 103.289062 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph4-1" x="49.066406" y="167.916016"/>
  <use xlink:href="#glyph4-2" x="55.738281" y="167.916016"/>
  <use xlink:href="#glyph4-1" x="59.074219" y="167.916016"/>
  <use xlink:href="#glyph4-1" x="65.746094" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph4-1" x="91.289062" y="167.916016"/>
  <use xlink:href="#glyph4-2" x="97.960938" y="167.916016"/>
  <use xlink:href="#glyph4-3" x="101.296875" y="167.916016"/>
  <use xlink:href="#glyph4-4" x="107.96875" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 59.039062 63.402344 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 51.839844 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 126.789062 L 51.839844 126.789062 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 114.113281 L 51.839844 114.113281 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 101.433594 L 51.839844 101.433594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 88.757812 L 51.839844 88.757812 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 76.078125 L 51.839844 76.078125 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 63.402344 L 51.839844 63.402344 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-9" x="41.197266" y="142.964844"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-10" x="41.197266" y="121.113281"/>
  <use xlink:href="#glyph3-9" x="41.197266" y="114.441406"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-11" x="41.197266" y="95.757812"/>
  <use xlink:href="#glyph3-9" x="41.197266" y="89.085938"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-12" x="41.197266" y="70.402344"/>
  <use xlink:href="#glyph3-9" x="41.197266" y="63.730469"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 139.464844 L 69.511719 139.464844 L 69.511719 62.132812 L 61.066406 62.132812 Z M 61.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 69.511719 139.464844 L 77.957031 139.464844 L 77.957031 106.503906 L 69.511719 106.503906 Z M 69.511719 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 77.957031 139.464844 L 86.402344 139.464844 L 86.402344 128.054688 L 77.957031 128.054688 Z M 77.957031 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 86.398438 139.464844 L 94.84375 139.464844 L 94.84375 138.195312 L 86.398438 138.195312 Z M 86.398438 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 94.84375 139.464844 L 103.289062 139.464844 L 103.289062 138.195312 L 94.84375 138.195312 Z M 94.84375 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 103.289062 139.464844 L 111.734375 139.464844 L 111.734375 136.929688 L 103.289062 136.929688 Z M 103.289062 139.464844 "/>
</g>
</svg><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="144pt" height="216pt" viewBox="0 0 144 216" version="1.1">
<defs>
<g>
<symbol overflow="visible" id="glyph0-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-1">
<path style="stroke:none;" d="M 7.296875 -4.765625 L 7.296875 0 L 9.46875 0 L 9.46875 -10.5 L 7.296875 -10.5 L 7.296875 -6.5625 L 3.140625 -6.5625 L 3.140625 -10.5 L 0.984375 -10.5 L 0.984375 0 L 3.140625 0 L 3.140625 -4.765625 Z M 7.296875 -4.765625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-2">
<path style="stroke:none;" d="M 2.984375 -7.78125 L 0.96875 -7.78125 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 -8.703125 L 2.984375 -8.703125 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-3">
<path style="stroke:none;" d="M 7.28125 -5.265625 C 7.25 -6.921875 5.984375 -7.90625 3.890625 -7.90625 C 1.921875 -7.90625 0.6875 -6.921875 0.6875 -5.3125 C 0.6875 -4.796875 0.84375 -4.34375 1.125 -4.046875 C 1.390625 -3.78125 1.640625 -3.640625 2.390625 -3.40625 L 4.796875 -2.65625 C 5.296875 -2.5 5.46875 -2.328125 5.46875 -2.015625 C 5.46875 -1.546875 4.90625 -1.25 3.96875 -1.25 C 3.453125 -1.25 3.046875 -1.359375 2.78125 -1.53125 C 2.5625 -1.6875 2.484375 -1.84375 2.390625 -2.265625 L 0.421875 -2.265625 C 0.46875 -0.5625 1.734375 0.328125 4.09375 0.328125 C 5.171875 0.328125 6 0.09375 6.5625 -0.359375 C 7.140625 -0.828125 7.484375 -1.546875 7.484375 -2.3125 C 7.484375 -3.3125 6.984375 -3.96875 5.96875 -4.265625 L 3.421875 -5 C 2.859375 -5.171875 2.703125 -5.28125 2.703125 -5.609375 C 2.703125 -6.03125 3.171875 -6.328125 3.875 -6.328125 C 4.84375 -6.328125 5.3125 -5.984375 5.328125 -5.265625 Z M 7.28125 -5.265625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-4">
<path style="stroke:none;" d="M 4.34375 -7.625 L 3.21875 -7.625 L 3.21875 -9.703125 L 1.203125 -9.703125 L 1.203125 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.203125 -6.28125 L 1.203125 -1.5 C 1.203125 -0.28125 1.84375 0.328125 3.171875 0.328125 C 3.609375 0.328125 3.96875 0.28125 4.34375 0.171875 L 4.34375 -1.234375 C 4.140625 -1.203125 4.015625 -1.203125 3.875 -1.203125 C 3.34375 -1.203125 3.21875 -1.359375 3.21875 -2.046875 L 3.21875 -6.28125 L 4.34375 -6.28125 Z M 4.34375 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-5">
<path style="stroke:none;" d="M 4.34375 -7.90625 C 1.953125 -7.90625 0.5 -6.34375 0.5 -3.78125 C 0.5 -1.21875 1.953125 0.328125 4.34375 0.328125 C 6.71875 0.328125 8.203125 -1.234375 8.203125 -3.734375 C 8.203125 -6.375 6.765625 -7.90625 4.34375 -7.90625 Z M 4.34375 -6.28125 C 5.453125 -6.28125 6.1875 -5.28125 6.1875 -3.765625 C 6.1875 -2.3125 5.4375 -1.296875 4.34375 -1.296875 C 3.25 -1.296875 2.515625 -2.3125 2.515625 -3.78125 C 2.515625 -5.265625 3.25 -6.28125 4.34375 -6.28125 Z M 4.34375 -6.28125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-6">
<path style="stroke:none;" d="M 5.875 -7.78125 L 5.875 -6.578125 C 5.265625 -7.5 4.609375 -7.90625 3.71875 -7.90625 C 1.875 -7.90625 0.484375 -6.109375 0.484375 -3.703125 C 0.484375 -1.28125 1.75 0.328125 3.671875 0.328125 C 4.578125 0.328125 5.125 0.0625 5.875 -0.796875 L 5.875 0.265625 C 5.875 1.203125 5.171875 1.84375 4.15625 1.84375 C 3.40625 1.84375 2.890625 1.53125 2.734375 0.9375 L 0.640625 0.9375 C 0.65625 1.546875 0.890625 1.953125 1.40625 2.390625 C 2.03125 2.890625 2.890625 3.140625 4.09375 3.140625 C 6.4375 3.140625 7.796875 2.09375 7.796875 0.265625 L 7.796875 -7.78125 Z M 4.15625 -6.21875 C 5.15625 -6.21875 5.90625 -5.171875 5.90625 -3.734375 C 5.90625 -2.3125 5.171875 -1.359375 4.125 -1.359375 C 3.171875 -1.359375 2.5 -2.3125 2.5 -3.734375 C 2.5 -5.203125 3.171875 -6.21875 4.15625 -6.21875 Z M 4.15625 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-7">
<path style="stroke:none;" d="M 0.90625 -7.78125 L 0.90625 0 L 2.921875 0 L 2.921875 -4.140625 C 2.921875 -5.3125 3.515625 -5.90625 4.703125 -5.90625 C 4.90625 -5.90625 5.0625 -5.890625 5.328125 -5.84375 L 5.328125 -7.890625 C 5.21875 -7.90625 5.140625 -7.90625 5.078125 -7.90625 C 4.15625 -7.90625 3.359375 -7.296875 2.921875 -6.25 L 2.921875 -7.78125 Z M 0.90625 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-8">
<path style="stroke:none;" d="M 7.546875 -0.25 C 7.1875 -0.578125 7.09375 -0.796875 7.09375 -1.203125 L 7.09375 -5.515625 C 7.09375 -7.109375 6 -7.90625 3.90625 -7.90625 C 1.796875 -7.90625 0.703125 -7.015625 0.578125 -5.21875 L 2.515625 -5.21875 C 2.625 -6.015625 2.953125 -6.28125 3.953125 -6.28125 C 4.71875 -6.28125 5.109375 -6.015625 5.109375 -5.5 C 5.109375 -5.25 4.984375 -5.015625 4.765625 -4.890625 C 4.5 -4.75 4.5 -4.75 3.5 -4.59375 L 2.6875 -4.453125 C 1.15625 -4.1875 0.40625 -3.40625 0.40625 -2 C 0.40625 -1.34375 0.59375 -0.796875 0.953125 -0.40625 C 1.390625 0.0625 2.078125 0.328125 2.765625 0.328125 C 3.625 0.328125 4.421875 -0.046875 5.125 -0.78125 C 5.125 -0.375 5.171875 -0.234375 5.359375 0 L 7.546875 0 Z M 5.109375 -3.125 C 5.109375 -1.953125 4.53125 -1.296875 3.515625 -1.296875 C 2.84375 -1.296875 2.421875 -1.65625 2.421875 -2.234375 C 2.421875 -2.84375 2.734375 -3.125 3.578125 -3.296875 L 4.265625 -3.421875 C 4.796875 -3.53125 4.890625 -3.5625 5.109375 -3.671875 Z M 5.109375 -3.125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-9">
<path style="stroke:none;" d="M 0.859375 -7.78125 L 0.859375 0 L 2.875 0 L 2.875 -4.671875 C 2.875 -5.625 3.40625 -6.1875 4.265625 -6.1875 C 4.9375 -6.1875 5.359375 -5.8125 5.359375 -5.1875 L 5.359375 0 L 7.375 0 L 7.375 -4.671875 C 7.375 -5.625 7.890625 -6.1875 8.765625 -6.1875 C 9.4375 -6.1875 9.859375 -5.8125 9.859375 -5.1875 L 9.859375 0 L 11.875 0 L 11.875 -5.5 C 11.875 -7.015625 10.953125 -7.90625 9.390625 -7.90625 C 8.40625 -7.90625 7.71875 -7.5625 7.109375 -6.75 C 6.734375 -7.484375 5.96875 -7.90625 5 -7.90625 C 4.109375 -7.90625 3.53125 -7.609375 2.859375 -6.8125 L 2.859375 -7.78125 Z M 0.859375 -7.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph0-10">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph0-11">
<path style="stroke:none;" d="M 4.515625 -7.625 L 3.3125 -7.625 L 3.3125 -8.390625 C 3.3125 -8.78125 3.484375 -8.984375 3.859375 -8.984375 C 4.03125 -8.984375 4.265625 -8.96875 4.4375 -8.953125 L 4.4375 -10.453125 C 4.0625 -10.484375 3.5625 -10.5 3.28125 -10.5 C 1.9375 -10.5 1.296875 -9.875 1.296875 -8.5625 L 1.296875 -7.625 L 0.203125 -7.625 L 0.203125 -6.28125 L 1.296875 -6.28125 L 1.296875 0 L 3.3125 0 L 3.3125 -6.28125 L 4.515625 -6.28125 Z M 4.515625 -7.625 "/>
</symbol>
<symbol overflow="visible" id="glyph0-12">
<path style="stroke:none;" d="M 2.859375 -7.78125 L 0.828125 -7.78125 L 0.828125 3.140625 L 2.859375 3.140625 L 2.859375 -0.921875 C 3.34375 -0.0625 4.03125 0.34375 5.015625 0.34375 C 6.890625 0.34375 8.265625 -1.40625 8.265625 -3.78125 C 8.265625 -4.875 7.953125 -5.96875 7.4375 -6.6875 C 6.921875 -7.421875 5.953125 -7.90625 5.015625 -7.90625 C 4.03125 -7.90625 3.34375 -7.484375 2.859375 -6.625 Z M 4.546875 -6.21875 C 5.578125 -6.21875 6.25 -5.234375 6.25 -3.75 C 6.25 -2.328125 5.546875 -1.34375 4.546875 -1.34375 C 3.546875 -1.34375 2.859375 -2.3125 2.859375 -3.78125 C 2.859375 -5.234375 3.546875 -6.21875 4.546875 -6.21875 Z M 4.546875 -6.21875 "/>
</symbol>
<symbol overflow="visible" id="glyph0-13">
<path style="stroke:none;" d="M 2.984375 -10.5 L 0.96875 -10.5 L 0.96875 0 L 2.984375 0 Z M 2.984375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-14">
<path style="stroke:none;" d="M 7.546875 -3.25 C 7.5625 -3.421875 7.5625 -3.5 7.5625 -3.59375 C 7.5625 -4.375 7.453125 -5.09375 7.265625 -5.640625 C 6.734375 -7.0625 5.484375 -7.90625 3.921875 -7.90625 C 1.6875 -7.90625 0.3125 -6.296875 0.3125 -3.6875 C 0.3125 -1.203125 1.671875 0.328125 3.875 0.328125 C 5.625 0.328125 7.03125 -0.65625 7.484375 -2.1875 L 5.484375 -2.1875 C 5.25 -1.5625 4.6875 -1.203125 3.953125 -1.203125 C 3.375 -1.203125 2.90625 -1.453125 2.625 -1.890625 C 2.4375 -2.171875 2.359375 -2.515625 2.328125 -3.25 Z M 2.359375 -4.59375 C 2.5 -5.78125 3 -6.375 3.890625 -6.375 C 4.390625 -6.375 4.859375 -6.125 5.140625 -5.71875 C 5.328125 -5.4375 5.421875 -5.125 5.453125 -4.59375 Z M 2.359375 -4.59375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-15">
<path style="stroke:none;" d="M 4.4375 -10.5 L 0.953125 -10.5 L 0.953125 2.875 L 4.4375 2.875 L 4.4375 1.40625 L 2.828125 1.40625 L 2.828125 -9.03125 L 4.4375 -9.03125 Z M 4.4375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-16">
<path style="stroke:none;" d="M 0.921875 -2.109375 L 0.921875 0 L 2.15625 0 L 2.15625 0.046875 C 2.15625 1.015625 1.765625 1.53125 0.921875 1.703125 L 0.921875 2.5 C 1.515625 2.4375 1.921875 2.28125 2.3125 1.96875 C 2.875 1.53125 3.078125 1 3.078125 -0.125 L 3.078125 -2.109375 Z M 0.921875 -2.109375 "/>
</symbol>
<symbol overflow="visible" id="glyph0-17">
<path style="stroke:none;" d="M 2.703125 -10.5 L 0.71875 -10.5 L 0.71875 -8.625 L 1.296875 -6.765625 L 2.109375 -6.765625 L 2.703125 -8.625 Z M 6.109375 -10.5 L 4.125 -10.5 L 4.125 -8.625 L 4.703125 -6.765625 L 5.5 -6.765625 L 6.109375 -8.625 Z M 6.109375 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-18">
<path style="stroke:none;" d="M 0.96875 -10.5 L 0.96875 0 L 2.984375 0 L 2.984375 -4.671875 C 2.984375 -5.5625 3.625 -6.1875 4.53125 -6.1875 C 4.96875 -6.1875 5.3125 -6.03125 5.546875 -5.71875 C 5.71875 -5.453125 5.78125 -5.265625 5.78125 -4.75 L 5.78125 0 L 7.796875 0 L 7.796875 -5.21875 C 7.796875 -6.1875 7.53125 -6.875 7 -7.3125 C 6.5625 -7.6875 5.90625 -7.90625 5.265625 -7.90625 C 4.265625 -7.90625 3.546875 -7.5 2.984375 -6.65625 L 2.984375 -10.5 Z M 0.96875 -10.5 "/>
</symbol>
<symbol overflow="visible" id="glyph0-19">
<path style="stroke:none;" d="M 0.265625 2.875 L 3.75 2.875 L 3.75 -10.5 L 0.265625 -10.5 L 0.265625 -9.03125 L 1.875 -9.03125 L 1.875 1.40625 L 0.265625 1.40625 Z M 0.265625 2.875 "/>
</symbol>
<symbol overflow="visible" id="glyph1-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph1-1">
<path style="stroke:none;" d="M 3.171875 -8.234375 C 2.703125 -8.234375 2.21875 -8.046875 1.78125 -7.671875 C 0.953125 -7.015625 0.515625 -5.71875 0.515625 -4.03125 C 0.515625 -2.453125 0.90625 -1.21875 1.625 -0.546875 C 2.09375 -0.09375 2.65625 0.15625 3.171875 0.15625 C 3.640625 0.15625 4.109375 -0.03125 4.5625 -0.40625 C 5.359375 -1.0625 5.8125 -2.359375 5.8125 -3.96875 C 5.8125 -5.609375 5.4375 -6.84375 4.71875 -7.53125 C 4.25 -7.984375 3.703125 -8.234375 3.171875 -8.234375 Z M 4.578125 -3.75 C 4.5625 -2.375 4.421875 -1.59375 4.0625 -0.953125 C 3.859375 -0.59375 3.46875 -0.3125 3.171875 -0.3125 C 2.859375 -0.3125 2.46875 -0.59375 2.265625 -0.953125 C 1.921875 -1.59375 1.78125 -2.375 1.75 -3.75 Z M 1.75 -4.421875 C 1.78125 -5.71875 1.9375 -6.515625 2.265625 -7.140625 C 2.46875 -7.5 2.875 -7.78125 3.171875 -7.78125 C 3.46875 -7.78125 3.859375 -7.5 4.0625 -7.140625 C 4.40625 -6.515625 4.5625 -5.71875 4.578125 -4.421875 Z M 1.75 -4.421875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph2-1">
<path style="stroke:none;" d="M -3.984375 -2.203125 L -3.984375 -6.375 L -4.96875 -6.375 L -4.96875 -2.203125 L -7.765625 -2.203125 L -7.765625 -6.953125 L -8.75 -6.953125 L -8.75 -1.078125 L 0 -1.078125 L 0 -2.203125 Z M -3.984375 -2.203125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-2">
<path style="stroke:none;" d="M -6.28125 -0.828125 L 0 -0.828125 L 0 -1.84375 L -3.265625 -1.84375 C -4.15625 -1.84375 -4.75 -2.0625 -5.09375 -2.546875 C -5.328125 -2.859375 -5.40625 -3.15625 -5.40625 -3.859375 L -6.4375 -3.859375 C -6.453125 -3.6875 -6.46875 -3.59375 -6.46875 -3.46875 C -6.46875 -2.8125 -6.078125 -2.328125 -5.140625 -1.75 L -6.28125 -1.75 Z M -6.28125 -0.828125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-3">
<path style="stroke:none;" d="M -2.8125 -6.15625 C -3.765625 -6.15625 -4.34375 -6.078125 -4.8125 -5.90625 C -5.84375 -5.5 -6.46875 -4.53125 -6.46875 -3.359375 C -6.46875 -1.609375 -5.125 -0.484375 -3.0625 -0.484375 C -1 -0.484375 0.28125 -1.578125 0.28125 -3.34375 C 0.28125 -4.78125 -0.546875 -5.765625 -1.90625 -6.03125 L -1.90625 -5.015625 C -1.078125 -4.734375 -0.640625 -4.171875 -0.640625 -3.375 C -0.640625 -2.734375 -0.9375 -2.203125 -1.46875 -1.859375 C -1.828125 -1.625 -2.1875 -1.53125 -2.8125 -1.53125 Z M -3.625 -1.546875 C -4.78125 -1.625 -5.546875 -2.34375 -5.546875 -3.34375 C -5.546875 -4.328125 -4.734375 -5.09375 -3.703125 -5.09375 C -3.671875 -5.09375 -3.640625 -5.09375 -3.625 -5.078125 Z M -3.625 -1.546875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-4">
<path style="stroke:none;" d="M 2.609375 -5.9375 L -6.28125 -5.9375 L -6.28125 -5.046875 L -5.453125 -5.046875 C -6.109375 -4.578125 -6.46875 -3.875 -6.46875 -3.046875 C -6.46875 -1.390625 -5.109375 -0.3125 -3.03125 -0.3125 C -0.984375 -0.3125 0.28125 -1.34375 0.28125 -3 C 0.28125 -3.875 -0.03125 -4.46875 -0.71875 -4.9375 L 2.609375 -4.9375 Z M -5.53125 -3.1875 C -5.53125 -4.265625 -4.578125 -4.9375 -3.0625 -4.9375 C -1.625 -4.9375 -0.65625 -4.25 -0.65625 -3.1875 C -0.65625 -2.09375 -1.625 -1.359375 -3.09375 -1.359375 C -4.546875 -1.359375 -5.53125 -2.09375 -5.53125 -3.1875 Z M -5.53125 -3.1875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-5">
<path style="stroke:none;" d="M 0 -5.78125 L -6.28125 -5.78125 L -6.28125 -4.78125 L -2.71875 -4.78125 C -1.4375 -4.78125 -0.59375 -4.109375 -0.59375 -3.078125 C -0.59375 -2.28125 -1.078125 -1.78125 -1.84375 -1.78125 L -6.28125 -1.78125 L -6.28125 -0.78125 L -1.4375 -0.78125 C -0.390625 -0.78125 0.28125 -1.5625 0.28125 -2.78125 C 0.28125 -3.703125 -0.046875 -4.296875 -0.875 -4.890625 L 0 -4.890625 Z M 0 -5.78125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-6">
<path style="stroke:none;" d="M -6.28125 -0.84375 L 0 -0.84375 L 0 -1.84375 L -3.46875 -1.84375 C -4.75 -1.84375 -5.59375 -2.515625 -5.59375 -3.546875 C -5.59375 -4.34375 -5.109375 -4.84375 -4.359375 -4.84375 L 0 -4.84375 L 0 -5.84375 L -4.75 -5.84375 C -5.796875 -5.84375 -6.46875 -5.0625 -6.46875 -3.859375 C -6.46875 -2.921875 -6.109375 -2.3125 -5.234375 -1.765625 L -6.28125 -1.765625 Z M -6.28125 -0.84375 "/>
</symbol>
<symbol overflow="visible" id="glyph2-7">
<path style="stroke:none;" d="M -4.171875 -5.65625 C -4.78125 -5.609375 -5.1875 -5.46875 -5.53125 -5.234375 C -6.125 -4.796875 -6.46875 -4.046875 -6.46875 -3.171875 C -6.46875 -1.46875 -5.125 -0.375 -3.03125 -0.375 C -1.015625 -0.375 0.28125 -1.453125 0.28125 -3.15625 C 0.28125 -4.65625 -0.625 -5.609375 -2.15625 -5.71875 L -2.15625 -4.71875 C -1.15625 -4.546875 -0.640625 -4.03125 -0.640625 -3.1875 C -0.640625 -2.078125 -1.546875 -1.421875 -3.03125 -1.421875 C -4.609375 -1.421875 -5.546875 -2.0625 -5.546875 -3.15625 C -5.546875 -4 -5.046875 -4.53125 -4.171875 -4.640625 Z M -4.171875 -5.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph2-8">
<path style="stroke:none;" d="M -6.28125 -4.65625 L -1.390625 -2.921875 L -6.28125 -1.3125 L -6.28125 -0.234375 L 0.03125 -2.359375 L 1.015625 -1.984375 C 1.46875 -1.828125 1.625 -1.59375 1.625 -1.171875 C 1.625 -1.03125 1.609375 -0.859375 1.5625 -0.640625 L 2.453125 -0.640625 C 2.5625 -0.859375 2.609375 -1.0625 2.609375 -1.3125 C 2.609375 -1.640625 2.515625 -1.984375 2.3125 -2.25 C 2.09375 -2.5625 1.828125 -2.75 1.3125 -2.9375 L -6.28125 -5.734375 Z M -6.28125 -4.65625 "/>
</symbol>
<symbol overflow="visible" id="glyph2-9">
<path style="stroke:none;" d="M -8.515625 -3.296875 C -8.515625 -2.515625 -8.15625 -1.78125 -7.578125 -1.34375 C -6.828125 -0.796875 -5.6875 -0.515625 -4.109375 -0.515625 C -1.25 -0.515625 0.28125 -1.46875 0.28125 -3.296875 C 0.28125 -5.09375 -1.25 -6.078125 -4.046875 -6.078125 C -5.703125 -6.078125 -6.796875 -5.8125 -7.578125 -5.25 C -8.171875 -4.8125 -8.515625 -4.109375 -8.515625 -3.296875 Z M -7.578125 -3.296875 C -7.578125 -4.4375 -6.421875 -5 -4.140625 -5 C -1.734375 -5 -0.59375 -4.453125 -0.59375 -3.28125 C -0.59375 -2.15625 -1.78125 -1.59375 -4.109375 -1.59375 C -6.4375 -1.59375 -7.578125 -2.15625 -7.578125 -3.296875 Z M -7.578125 -3.296875 "/>
</symbol>
<symbol overflow="visible" id="glyph2-10">
<path style="stroke:none;" d="M -1.046875 -6.078125 L -1.046875 -1.59375 C -1.734375 -1.703125 -2.1875 -2.09375 -2.796875 -3.125 L -3.4375 -4.328125 C -4.09375 -5.515625 -4.96875 -6.125 -6.015625 -6.125 C -6.71875 -6.125 -7.375 -5.84375 -7.84375 -5.34375 C -8.296875 -4.84375 -8.515625 -4.21875 -8.515625 -3.40625 C -8.515625 -2.328125 -8.125 -1.53125 -7.40625 -1.0625 C -6.953125 -0.75 -6.421875 -0.625 -5.5625 -0.59375 L -5.5625 -1.65625 C -6.125 -1.6875 -6.484375 -1.765625 -6.75 -1.90625 C -7.265625 -2.1875 -7.578125 -2.734375 -7.578125 -3.375 C -7.578125 -4.328125 -6.90625 -5.046875 -5.984375 -5.046875 C -5.3125 -5.046875 -4.734375 -4.65625 -4.3125 -3.90625 L -3.6875 -2.796875 C -2.671875 -1.015625 -1.875 -0.5 0 -0.40625 L 0 -6.078125 Z M -1.046875 -6.078125 "/>
</symbol>
<symbol overflow="visible" id="glyph2-11">
<path style="stroke:none;" d="M -2.046875 -3.921875 L 0 -3.921875 L 0 -4.984375 L -2.046875 -4.984375 L -2.046875 -6.234375 L -2.984375 -6.234375 L -2.984375 -4.984375 L -8.515625 -4.984375 L -8.515625 -4.203125 L -3.15625 -0.34375 L -2.046875 -0.34375 Z M -2.984375 -3.921875 L -2.984375 -1.265625 L -6.703125 -3.921875 Z M -2.984375 -3.921875 "/>
</symbol>
<symbol overflow="visible" id="glyph3-0">
<path style="stroke:none;" d=""/>
</symbol>
<symbol overflow="visible" id="glyph3-1">
<path style="stroke:none;" d="M 0.640625 -1.9375 C 0.84375 -0.546875 1.75 0.28125 3.046875 0.28125 C 3.984375 0.28125 4.84375 -0.1875 5.328125 -0.9375 C 5.875 -1.765625 6.109375 -2.8125 6.109375 -4.359375 C 6.109375 -5.78125 5.890625 -6.703125 5.390625 -7.453125 C 4.921875 -8.140625 4.171875 -8.515625 3.234375 -8.515625 C 1.625 -8.515625 0.453125 -7.3125 0.453125 -5.640625 C 0.453125 -4.0625 1.53125 -2.9375 3.078125 -2.9375 C 3.875 -2.9375 4.46875 -3.234375 5.015625 -3.890625 C 5 -1.8125 4.328125 -0.65625 3.125 -0.65625 C 2.375 -0.65625 1.859375 -1.125 1.6875 -1.9375 Z M 3.234375 -7.578125 C 4.21875 -7.578125 4.953125 -6.765625 4.953125 -5.65625 C 4.953125 -4.625 4.21875 -3.875 3.1875 -3.875 C 2.171875 -3.875 1.53125 -4.578125 1.53125 -5.71875 C 1.53125 -6.796875 2.25 -7.578125 3.234375 -7.578125 Z M 3.234375 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-2">
<path style="stroke:none;" d="M 2.296875 -1.25 L 1.046875 -1.25 L 1.046875 0 L 2.296875 0 Z M 2.296875 -1.25 "/>
</symbol>
<symbol overflow="visible" id="glyph3-3">
<path style="stroke:none;" d="M 3.296875 -8.515625 C 2.515625 -8.515625 1.78125 -8.15625 1.34375 -7.578125 C 0.796875 -6.828125 0.515625 -5.6875 0.515625 -4.109375 C 0.515625 -1.25 1.46875 0.28125 3.296875 0.28125 C 5.09375 0.28125 6.078125 -1.25 6.078125 -4.046875 C 6.078125 -5.703125 5.8125 -6.796875 5.25 -7.578125 C 4.8125 -8.171875 4.109375 -8.515625 3.296875 -8.515625 Z M 3.296875 -7.578125 C 4.4375 -7.578125 5 -6.421875 5 -4.140625 C 5 -1.734375 4.453125 -0.59375 3.28125 -0.59375 C 2.15625 -0.59375 1.59375 -1.78125 1.59375 -4.109375 C 1.59375 -6.4375 2.15625 -7.578125 3.296875 -7.578125 Z M 3.296875 -7.578125 "/>
</symbol>
<symbol overflow="visible" id="glyph3-4">
<path style="stroke:none;" d="M 3.109375 -6.0625 L 3.109375 0 L 4.15625 0 L 4.15625 -8.515625 L 3.46875 -8.515625 C 3.09375 -7.203125 2.859375 -7.015625 1.21875 -6.8125 L 1.21875 -6.0625 Z M 3.109375 -6.0625 "/>
</symbol>
</g>
</defs>
<g id="surface847">
<rect x="0" y="0" width="144" height="216" style="fill:rgb(100%,100%,100%);fill-opacity:1;stroke:none;"/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph0-1" x="-22.101562" y="34.116211"/>
  <use xlink:href="#glyph0-2" x="-11.700195" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="-7.695312" y="34.116211"/>
  <use xlink:href="#glyph0-4" x="0.314453" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="5.111328" y="34.116211"/>
  <use xlink:href="#glyph0-6" x="13.913086" y="34.116211"/>
  <use xlink:href="#glyph0-7" x="22.714844" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="28.319336" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="36.329102" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="49.135742" y="34.116211"/>
  <use xlink:href="#glyph0-5" x="53.140625" y="34.116211"/>
  <use xlink:href="#glyph0-11" x="61.942383" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="66.739258" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="70.744141" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="78.753906" y="34.116211"/>
  <use xlink:href="#glyph0-9" x="86.763672" y="34.116211"/>
  <use xlink:href="#glyph0-12" x="99.570312" y="34.116211"/>
  <use xlink:href="#glyph0-13" x="108.37207" y="34.116211"/>
  <use xlink:href="#glyph0-14" x="112.376953" y="34.116211"/>
  <use xlink:href="#glyph0-3" x="120.386719" y="34.116211"/>
  <use xlink:href="#glyph0-15" x="128.396484" y="34.116211"/>
  <use xlink:href="#glyph0-16" x="133.193359" y="34.116211"/>
  <use xlink:href="#glyph0-10" x="137.198242" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="141.203125" y="34.116211"/>
  <use xlink:href="#glyph0-4" x="148.03125" y="34.116211"/>
  <use xlink:href="#glyph0-18" x="152.828125" y="34.116211"/>
  <use xlink:href="#glyph0-14" x="161.629883" y="34.116211"/>
  <use xlink:href="#glyph0-4" x="169.639648" y="34.116211"/>
  <use xlink:href="#glyph0-8" x="174.436523" y="34.116211"/>
  <use xlink:href="#glyph0-17" x="182.446289" y="34.116211"/>
  <use xlink:href="#glyph0-19" x="189.274414" y="34.116211"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph1-1" x="82.898438" y="195.401367"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-1" x="12.396484" y="129.300781"/>
  <use xlink:href="#glyph2-2" x="12.396484" y="121.96875"/>
  <use xlink:href="#glyph2-3" x="12.396484" y="117.972656"/>
  <use xlink:href="#glyph2-4" x="12.396484" y="111.300781"/>
  <use xlink:href="#glyph2-5" x="12.396484" y="104.628906"/>
  <use xlink:href="#glyph2-3" x="12.396484" y="97.957031"/>
  <use xlink:href="#glyph2-6" x="12.396484" y="91.285156"/>
  <use xlink:href="#glyph2-7" x="12.396484" y="84.613281"/>
  <use xlink:href="#glyph2-8" x="12.396484" y="78.613281"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 111.734375 142.558594 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 142.558594 L 61.066406 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 71.199219 142.558594 L 71.199219 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 81.332031 142.558594 L 81.332031 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 91.464844 142.558594 L 91.464844 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 101.601562 142.558594 L 101.601562 149.761719 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 111.734375 142.558594 L 111.734375 149.761719 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-1" x="52.566406" y="167.916016"/>
  <use xlink:href="#glyph3-2" x="59.238281" y="167.916016"/>
  <use xlink:href="#glyph3-3" x="62.574219" y="167.916016"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph3-4" x="89.601562" y="167.916016"/>
  <use xlink:href="#glyph3-4" x="96.273438" y="167.916016"/>
  <use xlink:href="#glyph3-2" x="102.945312" y="167.916016"/>
  <use xlink:href="#glyph3-3" x="106.28125" y="167.916016"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 59.039062 71.628906 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 139.464844 L 51.839844 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 125.898438 L 51.839844 125.898438 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 112.332031 L 51.839844 112.332031 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 98.765625 L 51.839844 98.765625 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 85.199219 L 51.839844 85.199219 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 59.039062 71.628906 L 51.839844 71.628906 "/>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-9" x="41.197266" y="142.964844"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-10" x="41.197266" y="119.332031"/>
  <use xlink:href="#glyph2-9" x="41.197266" y="112.660156"/>
</g>
<g style="fill:rgb(0%,0%,0%);fill-opacity:1;">
  <use xlink:href="#glyph2-11" x="41.197266" y="92.199219"/>
  <use xlink:href="#glyph2-9" x="41.197266" y="85.527344"/>
</g>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 61.066406 139.464844 L 71.199219 139.464844 L 71.199219 131.324219 L 61.066406 131.324219 Z M 61.066406 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 71.199219 139.464844 L 81.332031 139.464844 L 81.332031 102.832031 L 71.199219 102.832031 Z M 71.199219 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 81.332031 139.464844 L 91.464844 139.464844 L 91.464844 62.132812 L 81.332031 62.132812 Z M 81.332031 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 91.464844 139.464844 L 101.597656 139.464844 L 101.597656 128.609375 L 91.464844 128.609375 Z M 91.464844 139.464844 "/>
<path style="fill:none;stroke-width:0.75;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(0%,0%,0%);stroke-opacity:1;stroke-miterlimit:10;" d="M 101.601562 139.464844 L 111.734375 139.464844 L 111.734375 136.75 L 101.601562 136.75 Z M 101.601562 139.464844 "/>
</g>
</svg>

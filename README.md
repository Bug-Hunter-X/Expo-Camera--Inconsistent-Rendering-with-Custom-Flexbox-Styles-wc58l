# Expo Camera Rendering Issue with Flexbox

This repository demonstrates a bug in the Expo `Camera` component where applying certain flexbox styles leads to inconsistent rendering behavior.  The camera preview may not fill its container, or portions may be unexpectedly clipped.

## Reproducing the Issue

Clone this repository and run the `bug.js` example.  Observe that the camera preview does not always fill the screen as expected.  Different flexbox style combinations may produce different and unpredictable results.

## Solution

The `bugSolution.js` file provides a workaround using `aspectRatio` prop to control the aspect ratio of camera preview and the style changes.
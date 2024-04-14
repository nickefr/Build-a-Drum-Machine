# Build-a-Drum-Machine https://codepen.io/nickefr-the-flexboxer/pen/yLrqgjm
### User Story #1
I should be able to see an outer container with a corresponding `id="drum-machine"` that contains all other elements.

### User Story #2
Within `#drum-machine`, I should see an element with a corresponding `id="display"`.

### User Story #3
Inside the `#drum-machine` container, there should be 9 clickable drum pad elements, each with a class name of `drum-pad`, a unique id describing the audio clip it will trigger, and inner text corresponding to the keyboard keys: Q, W, E, A, S, D, Z, X, C. The drum pads MUST be in this order.

### User Story #4
Each `.drum-pad` should contain an HTML5 audio element with a `src` attribute pointing to an audio clip, a class name of `clip`, and an `id` corresponding to the inner text of its parent `.drum-pad` (e.g., `id="Q"`, `id="W"`, `id="E"` etc.).

### User Story #5
Clicking on a `.drum-pad` element should trigger the audio clip contained in its child audio element.

### User Story #6
Pressing the keyboard key associated with each `.drum-pad` should trigger the audio clip contained in its child audio element (e.g., pressing the Q key should trigger the drum pad with the string Q, pressing the W key should trigger the drum pad with the string W, etc.).

### User Story #7
When a `.drum-pad` is triggered, a string describing the associated audio clip should be displayed as the inner text of the `#display` element. Each string must be unique.

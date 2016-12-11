# midi-wtf

Find out what fucking instrument or drum note a midi file is referencing. A key value table that turns a midi drum note number into a string representing the instrument.

## Usage

### Install via NPM

```js
npm install midi-wtf --save
```

### Require the fucking file

```js
var midiWTF = require('midi-wtf');
```

## Midi instrument number into a string and instrument group

```js
midiWtf.instrument(80)
```

Returns

```json
{ "val": 79, "name": "Ocarina", "group": "Pipe"}
```

## Midi note number to drum note

```js
midiWtf.drum(38)
```

Returns

```
Snare Drum 1
```

## Where did the fucking table come from?

* http://soundprogramming.net/file-formats/general-midi-drum-note-numbers/
* https://gist.github.com/skratchdot/6136612
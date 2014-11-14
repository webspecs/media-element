# The `HTMLMediaElement` Interface

There are now many specifications extending HTMLMediaElement in a variety of ways that leave one with little confidence that the total frankeninterface will actually work.

This repository contains an informal attempt to merge all of this work into a single specification in order to ensure coordination.

Note that [Mozilla’ integrated WebIDL for HTMLMediaElement](http://dxr.mozilla.org/mozilla-central/source/dom/webidl/HTMLMediaElement.webidl) documents at least the IDL they’re currently implementing.

## Sources

This is a table of the sources, sections, and who will pull them in.

spec   | section id | owner
-------|------------|------
 HTML  |#media-elements|Robin
[getUserMedia](http://w3c.github.io/mediacapture-main/getusermedia.html)|#mediastreams-as-media-elements|Dom
MSE| |
EME| |
[WebAudio](http://webaudio.github.io/web-audio-api/)|#MediaElementAudioSourceNode-section|
# ccynthmata
 Generalized module for creating WebMIDI CC Controllers

 *This is still very much in alpha right now - please don't actually use it for anything yet because it's very very likely that things will change*

## TODO:
Pretty much everything right now...

In particular:
* Try every option to attach events in order of "usefulness" (oninput first, if notpresent, onchange etc.) in tryAttachParameterChangeHandler
* Patch serialization/deserialization
 * in particular deserializing the midicctotal elements

## Known Issues / Notes / Caveats
* midiCcTotal only works properly for checkable controls (radiobuttons are the obvious use case). This may be a feature rather than a bug...
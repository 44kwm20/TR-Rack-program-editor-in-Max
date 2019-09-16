# TR-Rack-program-editor-in-Max
TR-Rack program editor in Max

These are Max files for "Program Editor" of KORG TR-Rack.
"TR-Rack-Editor_v0.2011.maxpat" is the executable file.
Others are files used in "TR-Rack-Editor_v0.2011.maxpat".

This was created with an older version of Max.
The latest Max will barely work, but the layout will collapse and some GUIs will not work.
However, we decided to release it as it is.

## What this can do
- Program Edit

## What this can do not
- Combination Edit
- in Program Edit...
-- Master Effect
-- Drum edit
- ...Many others.

## Brief explanation of how to use

1. Open "TR-Rack-Editor_v0.2011.maxpat".
2. Press "MIDI_setup", and set up MIDI device.
- TR-Rack in -> MIDI from TR-Rack (for program dump)
- TR-Rack out -> MIDI to TR-Rack (for edit)
- Controller in -> MIDI from MIDI keybord
3. Press "Program".
4. Selet Program with "Bank" and "Program".
5. Press "Dump_request". The contents of the program are loaded into Max.
6. Press "Program_edit".
7. Press "Oscillator" or other button, and edit.
8. Press "Write_request" when editing is complete.

I do not take any responsibility for any problems or disadvantages caused by this patch.
Please use at your own risk.


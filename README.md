# Pure data 4-line mono synth with step sequencer

Run multiline.pd to start.

Each line is by default set to channel 1,2,3,4, respectively. To pass through all channels set the channel on a line to -1 (setting the pass argument to 1 does this).

Lines are only editable by ctl values on the same channel as the line, when the line is in enabled for editing. Control values are organized into menus which are navigable by the edit select value on each synth (FM and SID). Each menu has a max of four float values, and three discrete values.

Requires bsaylor library.

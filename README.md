# SamplerBox for M-Audio Code 61

Based on the SamplerBox Project (https://www.samplerbox.org/), and adopted for use with M-Audio Code 61 Midi Keyboard. I found this project as a perfect way of making the M-Audio 61 Midi keyboard easier to use for my kids. Whith this solution, there is no need for a complicated setup with expensive software on a PC/MAC. While this solution obviously will not provide that same level of functionality, it enables anyone to just sit down and play the Midi Keybard. I focus on the M-Audio Code 61, but the code in SamplerBox is easily adoptable to any MIDI keyboard.

Big thanks to Joseph Basquin for the original SamplerBox Project.

While the simplistic philosophy behind SamplerBox (https://www.samplerbox.org/faq) is what draw me to that project, I wanted to expand on the functionality. 

Added Functionality:
- Added MidiMessagePrint(message) to output the midimessage as bits and dec (when one needs to see Midi packages with actual datastream, for debugging purposes)
- As the M-Audio don't have Program +/Program - commands, changing instruments up/down is mapped to button 1 and 2
- Master Volume is mapped to the Master Slider
- Drum kit on the pads (lowest octave, same Midi channel, drums are set to note 0-15)

Comming Functionality / Ideas / Thoughts
- Preset Beats
- Record/playback of sequences
- Add Samples to the SSD Card
- Wifi
- Web/Remote administration of Drum mapping
- Web/Remote functionality for adding samples
- ?

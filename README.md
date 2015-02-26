# MusicTheory
Xml configuration file for musical theory

Many years back a colleague and I wrote a Windows Pocket PC application for displaying scales and chords on a guitar style fretboard and piano keys.

I thought I'd post the configuration file on github in case it's of use to anyone. As for the application, it needs too much work at the moment to put on github.

Theory.xml includes many scales showing the step intervals between subsequent notes, alternate names are listed. It also includes chords showing the chord construction using intervals as well as optional notes.

For example:

We can find the scale named Pentatonic Major. From this we can see alternate names for the scale it's pattern. In this case, a root note followed by a note 2 semi-tones higher, then one 3 semi-tones higher and so on. Also mode names are listed for the starting notes for the modes.

In the chords section we can search for a chord by the name, for example a Diminished 7th and see that it's also known as a Dimished. The chord is made up of a root, flattened 3rd, flattened fifth and a flattened flattened 7th (shown as a sixth for simplicity of parsing the data).

I haven't verified all scales and chords since I wrote this, so obviously if you find a mistake please let me know and I'll update accordindly when time permits.
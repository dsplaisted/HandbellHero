RELEASES.md

# 0.5.0 - 2023-01-30
- Added visual metronome which can be toggled with "M" key
- Better handle unassigned notes
- Notes can be explicitly "emphasized" in songs.  When authoring songs, use '>' to turn on note emphasis and '<' to turn it off.  If this is used, emphasized notes will be drawn with empty circles, while un-emphasized notes will be drawn with filled circles.
- Songs can set the "beat length", which is the distance the song will move each time it is scrolled to the left or the right.  For example, `!beatlength 8` will move it by a quarter note each time (which is the default).

# 0.4.0
- Fixed crash when there are note assignments for notes not used in song
- Fixed showing notes as flat in note assignments
- Show note names in notes used screen

# 0.3.0

- Added ability to include note assignments in songs.  Syntax: `!Assign G- G#- A- : Daniel`

# 0.2.0

- Changed color of some notes (B, G, D#) to make more visible on different screens
- Added lines for bass clef
- Added support for relative transpose in songs
- Added support for filtering notes outside of playable range
- Support notation with flat notes, support showing them as flats
- Added "Notes Used" view ('U')
- Added About Dialog ('A', 'H', '?', or F1)

# 0.1.0

- Initial Release

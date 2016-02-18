# Chordworm-API
Documentation for the chordworm.com API.

## Usage
To gather information about results use:

api.chordworm.com/results.php?chords= `chords`

(`chords` should be in the format of 'A+B+C+D')

## Results
| Variables | Value Type | Description                        | Example                |
|-----------|------------|------------------------------------|------------------------|
|`band`     | `string`   | Band name                          | "13th Floor Elevators" |
|`song`     | `string`   | Song name                          | "I Had To Tell You"    |
|`artwork`  | `string`   | Link to artwork                    | http://is3.mzstatic.com/image/thumb/Music/v4/c7/c0/36/c7c036a8-27e5-6961-5666-3b76379ebe5d/source/600x600bb.jpg
|`chords`   | `array`   | List of all the chords in the song | [C, G, C, G, C, G, C, D, G, C, G, C, G, C, G, C, D, G, D, F, C, G, D, F, C, D, G, D, G, C, G, D, C, G, D, C, D] |

# Dummy Example of Abjad

I played around with abjad using python 3.8 which works.
Not sure about other versions...

## Prerequisites

- Make sure to have lilypond installed and in the path.
- Make sure to have timidity installed for playing midi sounds. Also add the
  executable to your abjad config (`~/.abjad/abjad.cfg`).

## Installation

Create a virtual environment and install using requirements.txt

```
# activate virtual environment
pip install -r requirements.txt
```

## Output Scores or Midi Sound

```
abjad.show(StaffGroup(...))
abjad.play(StaffGroup(...))
```

# Version: 0.0.11
Date: 2024.06.02
- Changes:
  - Better linebreak calculation

# Version: 0.0.10
Date: 2024.05.01
- Fix:
  - remove whitespace from the beginning and end of title and artist
  - image conversion to jpeg for transparent or RGBA
  - index out of range error in when list is empty from musicbrainz

# Version: 0.0.9
Date: 2024.02.06
- Fix:
  - Re-Pitch mode now re-pitch the audio again
  - Re-Pitch mode now show the text and lines in plot

# Version: 0.0.8
Date: 2024.01.03
- Changes:
  - Plot words
- Fix:
  - Missing word lines in plot

# Version: 0.0.7
Date: 2023.12.29
- Changes:
  - Added format version support for 0.3.0, 1.0.0 and 1.1.0

# Version: 0.0.6
Date: 2023.12.28
- Changes:
  - Optimized the removing of silence in transcription data
  - Mute the processing audio in parts where no singing is detected
  - Plot muted audio

# Version: 0.0.5
Date: 2023.12.23
- Changes:
  - Format GENRE string
  - Extract year from date

# Version: 0.0.4
Date: 2023.12.16
- Changes:
  - Optimized the conversion to Mono
  - Removed limitation to mp3 and wav audio formats
  - Added option float32 to demucs
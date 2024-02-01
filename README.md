# songfiler

Script to recursively search for mp3 files inside `<input_dir>`, rename as `<Track #> <Song title>.mp3` and move them to the `<Artist>/<Album title>` directory inside `<output_dir>`

## Usage

Usage: `songfiler <input_dir> <output_dir> [safe]`

`<input_dir>` is the directory (or the parent directory) where your mp3 files are

`<output_dir>` is the directory where your mp3 files will be moved to

`[safe]` safe mode (optional)

## Dependencies

- **id3v2** - https://id3v2.sourceforge.net/

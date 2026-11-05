# CueConvert subtitle format fixtures

Small, reusable CSV fixtures for checking SRT and WebVTT field examples and malformed subtitle input. The SRT rows include warning text observed from CueConvert's parser. The WebVTT rows separate format rules from parser observations; read the `type` column before treating a row as a test result.

## Files

- `srt-format-fields-and-errors.csv`: SRT fields, a complete cue, and malformed examples with observed output.
- `vtt-format-fields-and-errors.csv`: WebVTT fields and malformed examples, with parser observations or rules labelled by row type.

Open these CSV files in a spreadsheet or parse them with a CSV reader. The `\n` sequences in SRT cells represent line breaks in the sample input. Do not submit sensitive subtitle text to third-party tools when testing.

The corresponding browser tools and explanatory pages are at [CueConvert's SRT format page](https://cueconvert.com/srt-file-format/) and [WebVTT format page](https://cueconvert.com/vtt-file-format/).

## Provenance

These files are copies of the public CSV downloads on CueConvert as of 2026-11-05. They are examples, not a formal specification or a claim that every parser gives the same warning.

## License

CC0 1.0. See `LICENSE`.


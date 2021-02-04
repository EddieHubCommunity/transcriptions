# Community Template Repo

Template repo with docs and GitHub Actions etc, to create other projects.

## Quickstart

1. Create a folder with the date of the video followed by the first part of the title, for example `2021-02-03-Free-GitHub-bootcamp`
2. Create a file in the folder with the name of the language (all lowercase), for example `english.txt` or `french.txt` ...
3. In the file type the text of what was said in your video

**Tips on the captions**

To get the best results, use these formatting tips:

- To force the start of a new caption, use a blank line.
- To designate background sounds, use square brackets. For example, [music] or [laughter].
- Add >> to identify speakers or change of speaker.
- Here's an example of what your transcript file might look like:

```
>> ALICE: Hi, my name is Alice Miller and this is John Brown
>> JOHN: and we're the owners of Miller Bakery.

>> ALICE: Today we'll be teaching you how to make
our famous chocolate chip cookies!

[intro music]

Okay, so we have all the ingredients laid out here
```

*NOTE: For non-English language transcript files, we recommend saving the file with UTF-8 encoding to improve display accuracy*

Official YouTube docs for [basic transcribing](https://support.google.com/youtube/answer/2734799?hl=en-GB).

## Advanced

If timestamps are required, follow the folder naming above, but use the file extension `english.sbv` and use timestamps in the format...

```
0:00:00.599,0:00:04.160
>> ALICE: Hi, my name is Alice Miller and this is John Brown

0:00:04.160,0:00:06.770
>> JOHN: and we're the owners of Miller Bakery.

0:00:06.770,0:00:10.880
>> ALICE: Today we'll be teaching you how to make
our famous chocolate chip cookies!

0:00:10.880,0:00:16.700
[intro music]

0:00:16.700,0:00:21.480
Okay, so we have all the ingredients laid out here
```

*Note: do not mix formats in a single file, but they can be mixed with a folder*

More information on the YouTube docs for [advanced transcibing](https://support.google.com/youtube/answer/2734698#zippy=%2Cbasic-file-formats%2Csubrip-srt-example%2Cadvanced-file-formats%2Cbroadcast-file-formats-tv-and-movies%2Csubviewer-sbv-example).

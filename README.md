# discid
Create/submit a discid to Musicbrainz from a flac .log file (good for when you don't have the original CD handy).
Should work for XLD log files, may require tweaking for others.
Requires MusicBrainz::DiscID perl module ('apt install libmusicbrainz-discid-perl' or via CPAN).

Usage: discid album.log

Example:
```
$ discid The\ Wake.log 
T1 PreGap: 00:02:00 (150)
ARGS: 1, 252176, 150, 25251, 59903, 86922, 110584, 145162, 172985, 196354
First: 1
Last : 8
Sectors:252176
Album: The Wake
DiscID: Jt3K9ovZCtDpzw1TfesHuRnlWIc-
Submit: 
http://musicbrainz.org/cdtoc/attach?id=Jt3K9ovZCtDpzw1TfesHuRnlWIc-&tracks=8&toc=1+8+252176+150+25251+59903+86922+110584+145162+172985+196354&filter-release.query=The+Wake
```

result: https://musicbrainz.org/cdtoc/Jt3K9ovZCtDpzw1TfesHuRnlWIc-

Bugs: doesn't seem to work anymore XD (script written in 2014)

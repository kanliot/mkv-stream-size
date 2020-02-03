# mkv-stream-size
The script prints out the bitrate of each mkv stream in Kbps by calling mkvinfo.    
The user needs to have 'mkvinfo' from https://mkvtoolnix.download/index.html or **mkvtoolnix** on debian

Usage: `mkv-stream-size file1.mkv [file2.webm] ...`

### Installation: 
download the single script and run it after installing mkvinfo from **mkvtoolnix**

mkvinfo -t is slow for large files so this program is slow for large files.

## Sample output: 
    Is.Van.Gogh.A.Genius.mkv	2282.1 Kbps (657M/0:39:16) (MiBytes/duration)
                MPEG4/ISO/AVC video	1720.9 Kbps
                          AAC audio	140.3 Kbps
                      AAC spa audio	138.3 Kbps
                      AAC fre audio	138.8 Kbps
                      AAC jpn audio	139.3 Kbps


tested with mkvinfo v.35.

# What is this?

These are tools to manipulate SRT subtitle files.
I used these for learning languages with videos in foreign languages that display 2 subtitles (foreign+native) at the same time.

# Install

    zypper in perl-Video-Subtitle-SRT ||
      OneClickInstallUI http://multiymp.zq1.de/devel:languages:perl/perl-Video-Subtitle-SRT

# Usage

    merge2ass.pl en.srt de.srt > en-de.ass
    mplayer -ass -sub en-de.ass movie.mkv

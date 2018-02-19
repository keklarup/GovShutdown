# GovShutdown
a quick project on media coverage of the 2018 government shutdown while on furlough

2 prongs to this project. The first prong used a webscraper to gather the html from a few news websites every hour. The headlines were then extracted from the html later for study. The second prong collects the daily newspaper front pages from the Newseum website. The headlines are then extracted from the pdfs and studied.

The first prong didn't generate enough data to get great insights. There may be differences in the way different news sources write their headlines, but the error bars are pretty big!

## Prong 1: realtime tracking of a few websites 
Number of words in a headline varies a bit:

<img src="./GovShutdown/Gov_shutdown_figs/newsites_headline_word_counts.png" />

But, in terms of subjectivity or polarity, everything's muddled:

<img src="./GovShutdown/Gov_shutdown_figs/newsites_headline_subjectivity.png" />

<img src="./GovShutdown/Gov_shutdown_figs/newsites_headline_polarity.png" />

## Prong 2: newpaper headlines from Newseum

Better analysis may be done with this data set in the future, but for now here are some word clouds from various days when the government was shutdown:

<img src="./GovShutdown/Gov_shutdown_figs/20131001.png" />>

<img src="./GovShutdown/Gov_shutdown_figs/20131017.png" />

<img src="./GovShutdown/Gov_shutdown_figs/20180121.png" />

<img src="./GovShutdown/Gov_shutdown_figs/20180209.png" />

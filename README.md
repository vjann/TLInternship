# TLInternship
I didn't finish, but the general approach was:

Scrape to get all the WARC.gz files
Iterate through, finding records that have 'covid'. Use concurrent threads to speed things up. Also only read first 1000 bytes to speed things up.
Afterwards, filter out the ones such that they also include economics

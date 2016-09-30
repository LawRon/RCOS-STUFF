Lab 4 report:

https://www.freebsd.org/doc/en_US.ISO8859-1/books/handbook/bsdinstall-partitioning.html
Under section 2.6.1., "Designing the Partition layout", there is a minor grammatical typo immediately after the Note block.

The sentence reads:
At least 2 gigabytes "is" recommended for this partition.

When it should read:
At least 2 gigabytes "are" recommended for this partition.

Proper documentation is important because it both provides credibility and legibility to the text.
I learned from this lab that error checking documentation is a huge project. So try to get someone to look at it after you
submit your work for review.

In the response from Warren Block, he mentioned:
All of "Designing the Partition Layout" needs editing.  It talks about SCSI and
IDE drives, specifically mentions /var/tmp, and talks about putting partitions
on the outside of the disk for performance.  Recommending a specific amount of
free space there also seems like a trap for the reader.  That is
usage-dependent.

The specific sentence should be reworded to avoid the usage problem:
from "At least 2 gigabytes is recommended for this partition." to "At least 2
GB of space is recommended for this partition."


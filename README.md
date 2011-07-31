GTFS mirroring tool.  This allows us to keep the GTFS data from Adelaide
Metro in a revision control system (so we could look up historical
data).

It should be trivial to adapt this to monitor another public transit
system.

This is best used in a weekly crontab on Sunday mornings.

You shouldn't need to run this script yourself though, I already provide a
repository at <https://github.com/micolous/adelaidemetro-gtfs>.  It has data
starting from January 2011.  Adelaide Metro started providing this data
publicly in November 2010.


Copyright 2011 Michael Farrell <http://micolous.id.au>

This program is free software. It comes without any warranty, to
the extent permitted by applicable law. You can redistribute it
and/or modify it under the terms of the Do What The Fuck You Want
To Public License, Version 2, as published by Sam Hocevar. See
http://sam.zoy.org/wtfpl/COPYING for more details.

The data provided (in gtfs folder) is covered by a different license to
this, and DTEI retain copyright on it.  Please see data_license.txt for
details.

A current version of the data held in this repository is available for free
from Adelaide Metro's website, at
<http://www.adelaidemetro.com.au/general/general-transit-feed-data>.

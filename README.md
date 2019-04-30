# Historical list of {Cobalt Strike,NanoHTTPD} servers

This repository contains a historical list of Cobalt Strike (or NanoHTTPD) hosts that have been identified using the "extraneous space" fingerprint.

Read more about this technique in the following blog post:

 * https://blog.fox-it.com/2019/02/26/identifying-cobalt-strike-team-servers-in-the-wild/

The list is a CSV file with `ip, port, first_seen, last_seen` pairs, starting from 2014-01 till 2019-04-21 and can be found here:

 * [cobaltstrike-servers.csv](cobaltstrike-servers.csv) ([raw link](https://raw.githubusercontent.com/fox-it/cobaltstrike-extraneous-space/master/cobaltstrike-servers.csv))

The data is derived from Rapid7 Labs OpenData sets which has a historical archive of HTTP and HTTPS scan data: https://opendata.rapid7.com

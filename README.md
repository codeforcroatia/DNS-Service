DNS Service
===========

Code for Croatia’s DNS host records change frequently, with subdomains added
regularly for various projects. This is a master copy of our domain name
collection. We’d like to keep it in Git now to maintain an ongoing historical
record of changes and older versions to allow for easier edit access and
rollback.

If you need to add a new DNS record to codeforamerica.org, edit the file
[`host-records.csv`](host-records.csv) and submit a pull request via Github.
Records should be live within a few minutes depending on speed of Travis
and Heroku. Check with [whatsmydns.net](https://www.whatsmydns.net).

We use Cloudflare for DNS management.

DNS Service
===========

Code for Croatia’s DNS host records change frequently, with subdomains added
regularly for various projects. This is a master copy of our domain name
collection. We’d like to keep it in Git now to maintain an ongoing historical
record of changes and older versions to allow for easier edit access and
rollback. We use Cloudflare for DNS management.

If you need to add a new DNS record to codeforcroatia.org, edit the file
[`host-records.csv`](host-records.csv) and submit a pull request via Github.
It's still manual process so records should be live depending on available volunteer resources. Check propagation status with [whatsmydns.net](https://www.whatsmydns.net).

To-do:
- make process automatic via Cloudflare API

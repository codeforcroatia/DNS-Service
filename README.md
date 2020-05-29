DNS Service
===========

Code for Croatia’s DNS host records change frequently, with subdomains added
regularly for various projects. This is a master copy of our domain name
collection. We’d like to keep it in Git now to maintain an ongoing historical
record of changes and older versions to allow for easier edit access and
rollback. We use Cloudflare for DNS management.

If you need to add a new DNS record to codeforcroatia.org, edit the
[`codeforcroatia.org.txt`](codeforcroatia.org.txt) BIND-formatted file of DNS records and submit a pull request via Github.
It's still manual process so records should be live depending on available volunteer resources. Check propagation status with [whatsmydns.net](https://www.whatsmydns.net).

Cloudflare export/import process:
- https://support.cloudflare.com/hc/en-us/articles/200168856-Importing-and-exporting-DNS-records

To-do:
- make process automatic via Cloudflare API

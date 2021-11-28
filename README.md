# dissent
Consent banners are not evil per se. It is good to have choice. This list is an 
automation of choice: When suppressing a script results in the choice you would 
otherwise have made manually, script blocking is a valid response to data 
merchants.

## Principles
Dissent is an easylist filter guided by the following principles:

* Improved privacy: A rule suppressing interaction must result in equivalent or 
less data collection than an explicitly stated "i do not consent" to anything 
but the bare minimum of data collection and cookies. Yes, that does rely on the 
site respecting the idea that consent cannot be inferred from silence.

* Simplicity: One line per rule, no regex

* Script blocking: Denying javascript is better than CSS cleanup.

* Minimization: Ideally, one rule should only target one site to avoid 
unintended consequences. If scripts are hosted on shared ressources (e.g.  
TrustArc) all sites are targeted, see "Simplicity" point about avoiding fiddly 
regex to single out a parameter.

## Ressources

* https://help.eyeo.com/adblockplus/how-to-write-filters
* https://adblockplus.org/filter-cheatsheet

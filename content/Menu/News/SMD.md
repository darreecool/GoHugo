---
title: "ShadowMaker_6.7.22"
date: 2024-03-29T14:29:28+01:00
draft: false
---

## bSeolized ShadowMaker version 6.7.22 has been released.

New function with special rules for google ips that are not spiders
Added Silo csv support for making your own silo setup
Added 'Deep interlinking' option for silo. For example, on tier1 pages it will link to all of the children and grand children all the way down to the last tier
Fixed bug in 'Change title for every page'.
Added support for favicon.ico.
[KW] token fix (incomplete lines).
New tokens: [SILO_KEYWORD_TIER1], [SILO_KEYWORD_TIER2]
More flexible parsing of meta keywords for CSV keyword based redirects
Performance optimization for interlinking
Performance optimization for [CASE_TITLE]
New option: 'Delete templates once used'
New option: 'Ignore initial template used on domain'
Statistics: searchable profile selector
Statistics: export domains button
Various UTF-8 fixes
Fixed crash of HQ content engine when used with domain groups
Adjusted code for some new libraries
day/week/month buttonsNew template tokens [CASE_*]. See forum post
Fixed lack of randomization of array shuffling on Linux
New option: Ignore existing domains
New option: Force build new siloRe-use silo tree on existing domains
File I/O and threads related code cleanup and small performance optimizations
Improved Yahoo SE detection
Statistics: global filters
Statistics: SE tab
GetContent: skip documents >500kbGetURLs:
added google.co.uk and google.com.brCreatesite:
process all tokens in sitemaps as well
Support for nested [SPIN1], [REPEAT2] and [CHANCE3] tokens
centralX: do not break mailto: links
Always read first meta keyword for CSV keyword-based redirects
Separate human-se log table for better speed in statistics tool
Performance optimization for interlinking
Improved image generator
New 'U' for tokens to make them unique on each match. For example [KEYWORDU], [KWU:file.txt]
New template tokens: [SPIN], [REPEAT], [CHANCE]
Remove extra slashes appearing in href=,src= on some templates
Fixed wrong hspace/vspace parameters
Fixed Submissions file overwrite mode was not always working
Major cleanup in GetURLs, proper threading
Performance optimization for HQ content engine
Performance optimization for classic content engine
Performance and quality optimization for GetContent
Sort templates by time, newest first
PHP support for centralX
Mobile redirect option
Update all domains option (for redirects)
Dripfeeding for silo enabled sites
New template tokens: [NUM], [RANDOM_STRING], [KW], [PAGE], [TLD], [INTERN_LINK_URL]
New process monitoring tool
CentOS 7 init scripts
New silo token: [SILO_TOP_CATEGORIES]
New fast and memory efficient silo algo
New option: 'Max images per domain'
New option: 'Remove diacritic characters from file names'
This are all news from version 6.6
To upgrade visit https://my.bseolized.com

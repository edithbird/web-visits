# web-visits

@Tracy M. St Pierre @Robin McGlauflin @Andrea Tripp Attached here is a report on the results of the test merge of Robin's CM data and GA traffic data. Basically, the merge was successful and simple. The report contains the English Dept subsites with fewer than 100 pageviews since 3/1/19. We can proceed when you wish.

@Christine Iyer
Chris, I spotted a couple of issues in the test results.

First, there is a duplicate path listed in this truncated list (/eng/what-expect-english-100c-college-writing).

Another issue is that the report suggests that /eng/ba-english had only one pageview, which is misleading (it's a fairly high-trafficked page). I suspect there may be additional entry in the full results set for /eng/ba-english with a couple of thousand pageviews.

To prevent duplicate paths in the merged results, be sure to start with the CMS data, then do a left join on the URL Alias column in the CMS data with the Page Path column in the GA data. I think that will provide more accurate results.

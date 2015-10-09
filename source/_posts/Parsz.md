title: Parsz
date: 2015-01-25 18:22:12
tags:
---

I have been always been entranced with how much data is publicly available on the web. Although, most of the time the data is not directly usable for other purposes than reading. With so many HTML parsing libraries out there, it is common practice to build an application for a particular site and a specific data set. Parsz tries to generalize the "parsing" and focus on the data structure you need. Instead of downloading, processing, and transforming the data each time you need to parse a web page, use parsz. Enough of the TV commercial...

I did NOT originally think of this. [This guy](https://github.com/fizx/parsley/) did. I saw it, thought it was a great idea and decided such a simple idea could be implemented much easier by using Node.

The idea that caught me was to not re-implement the same dang code over and over again (possibly with stupid mistakes) in order to preform data parsing on a web page. Looking back, it makes me feel stupid. HTML has for the most part, been standardized. Why did I never think to build a engine which would use data/element or data/attribute relationships to build a recipe for parsing needed data. I really like the notion of labeling the data by name and location and having "someone" else do the work. 

Since JSON has become very popular, I have not built in XML based output yet, although that may be just a npm module away.

There are many improvements and features to add, like regular expression support and custom functions. But overall, the tool/library (however the community decides to use it) is in a fairly usable state.

Here is the [repo](https://github.com/dijs/parsz).

Have fun. Make sure to follow T&C.
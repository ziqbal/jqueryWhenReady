jQuery When Ready
=================

Ever get the '$ is not defined'?

The 'best practice' of loading jQuery just before the end body tag can bite you when you have jQuery dependent code running inline somewhere else on the page.

The standard response is to 'rethink your strategy'.

That's fine as long as you have a strategy.

For those who don't...

Queue functions to be run when jquery is loaded and ready

Useful when you have code coming in before jquery

Usage:
jqueryWhenReady.run(...your function...);
or jqueryWhenReady.run(function(){...your code...});

2013/11/01 Zafar Iqbal http://zaf.io/

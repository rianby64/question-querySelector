# document.querySelector question

I was playing around with a great feature called ```<link href="url" rel="import">``` and found very interesting that __querySelector__ method behaves in different ways depending on the caller.

At least in __Chrome__ the selector behaves in an unexpected way.

Check [the demo of this issue here](http://queryselector-question.m3c.space/) and see the failing test.

See [the issue posted at web-platform-test](https://github.com/w3c/web-platform-tests/issues/3301)

Also check [the issue at chromium](https://bugs.chromium.org/p/chromium/issues/detail?id=628880)

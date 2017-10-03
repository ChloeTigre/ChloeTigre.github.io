---
title: A Role-playing Server, by the book
---
I have recently started a project quite special for me since I'll try to "stick to the methods".

I had a chat with a Perl expert whom I happen to have gotten acquainted with and he told me stories about some C development companies that billed huge amounts for their development time because their code was written after it was entirely thought, architectured, conceived, well, specified from A to Z. I was like 🤔*wow😮* because it's something absolutely unheard of in most software development stories. Honestly you never meet product owners, project managers, software architects patient enough to do it.

Then I gave it another thought, and talked with a friend about it. She told me that this was not feasible in a reasonable fashion by a single developer on a project, but that roles had to alternate and this method had to be applied to small modules. The initial conception phase outlines the components, and then one after the other, their API are specified, the innards that make these API work are specified, their side effects are specified, and they are validated, tested, implemented, validated and tested again (in that order).

This is what we should be doing in any Scrum team if we had the opportunity and the discipline.

Unfortunately, we developers are human beings and as such we are subject to frustrations, cognitive biases, "Ignorance More Frequently Begets Confidence That Does Knowledge"-s (Darwin), which make us take shortcuts that are satisfying at first and costful.

So I decided I'd dedicate some time, maybe 1 hour a week, to sticking to that discipline and design my `modmud` this way, logging my specs and making them part of the source tree. After it's done, if I stick to it, I'll be able to provide retrospective on what it changed compared with the usual "develop-in-a-rush" approach.

I think we all have the potential for being decent developers, if we manage to get some discipline, to outcome our biases and to stick to methods until they become natural. I'll try this with the hope that it will cause less bugs, less architecture errors, less sufferance in the end.

Hey, BTW, this article was written so I could test the `_posts` functionality of Jekyll which I find to be a nice idea.

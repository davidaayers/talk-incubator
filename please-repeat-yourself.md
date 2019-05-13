Don't be DRY; Go ahead, repeat yourself!
----------------------------------------

Everyone knows we're supposed to write perfectly factored code as soon as our fingers touch the keyboard, right? We're supposed to know all of the possible use cases for our code, and ensure a perfect outward facing API in our very first PR.

Which, of course, is silly. The real world is a messy place, and we often confuse code that is "accidentally" similar to code that is "intrinsically" similar, and try to coerce them together into a share function/class/library. The result is a lot of really leaky abstractions that fail to actually capture the intent of what we're trying to express.

Which isn't to say that code reuse isn't a good _eventual_ goal, but what you and your teams should be focused on is solving the problem you have *today*, not the problem that you imagine you'll have tomorrow.

In this talk, I will present some learnings and techniques for thinking about code reuse differently, and being ok with repeating yourself. 

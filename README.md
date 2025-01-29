## Article
[Is High Quality Software Worth the Cost?](https://martinfowler.com/articles/is-quality-worth-cost.html)

## Notes of interest
While the article's title poses software quality as a trade-off against its cost, it reframes the relationship as a correlation. Fowler highlights the term "cruft," which is "the difference between the current code and how it would ideally be." When there is a lot of cruft, the code is likely not modular, has unintuitive variable names, or several other issues. Trying to add a new feature then requires developers to spend significant time and effort to understand existing code rather than spending that time implementing the feature. Avoiding "crufty" code by consistently refactoring code and maintaining better coding practices helps developers quickly write code that fits the existing program. Therefore, the time invested into raising code quality creates a positive return when weighed against the time saved from bodging a new feature.

## Comment

I think this is an interesting article because it highlights the value of good SWE practices and why learning to work in a systematic and consistent way as a SWE is so important (essentially what we're doing in this course). When developers don't put any emphasis on good practices, they end up with an overwhelming amount of "cruft" that ends up eating up more time to fix or dig through than it would have taken to do it right the first time and have clean, easily understandable code that can be built on when new features or improvements are needed. 
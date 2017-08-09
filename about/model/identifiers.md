Q: How does content-addressing fit with existing schemes of identifiers and universal names?

A: Short answer: Use Stable names (ie. DOIs) that map to content-addresses (content-hashes of the current values). Of course, this quickly invokes the need for an entire layer of metadata mapping between stable names and the many versions, derivatives, and sub-parts of a named entity. For an example of the sprawling metadata space this invokes, see the [Portland Common Data Model (PCDM)](https://github.com/duraspace/pcdm/wiki).

Cryptographic hashes have consistently been considered as a basis for URNs, especially when people tried to tackle the problem of broken links.

> "I want to be able to give names to generic works, AND to particular translations AND to particular versions. I want a richer world than you propose. I don’t want to be constrained by your two-level system of “documents” and “variants”."
>
> — Tim Berners-Lee [1993](http://1997.webhistory.org/www.lists/www-talk.1993q3/1003.html)


> There was a [fervent belief](http://1997.webhistory.org/www.lists/www-talk.1993q2/0234.html) in 1993 that the URL would die, in favor of the ‘URN’. The Uniform Resource Name is a permanent reference to a given piece of content which, unlike a URL, will never change or break. Tim Berners-Lee first described the “urgent need” for them as early as [1991](http://1997.webhistory.org/www.lists/www-talk.1991/0018.html) - .  
>
> — Zak Bloom, [The History of the URL: Path, Fragment, Query, and Auth](https://eager.io/blog/the-history-of-the-url-path-fragment-query-auth/)

> In 1996 Keith Shafer and several others proposed a solution to the problem of broken URLs. The link to this solution is now broken. Roy Fielding posted an implementation suggestion in July of 1995. The link is now broken.
>
> — Zak Bloom, [The History of the URL: Path, Fragment, Query, and Auth](https://eager.io/blog/the-history-of-the-url-path-fragment-query-auth/)

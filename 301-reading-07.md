# Code 301 Reading 7: REST

## [How I explained REST to my brother](https://gist.github.com/brookr/5977550)

Who is Roy Fielding?

* He helped to write the first web servers and HTTP protocol.

Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

* As we've developed techniques for talking with computers, the primary development mission has been talking to a computer anywhere in the world, but not *all* computers in the entire world. Computers were not designed with universal nouns the way languages and databases have, therefore url and HTTP protocol was necessary in coming along and us reshapig our view of HTTP from a simple GET, to a more dynamic general purpose system.

What is the HTTP protocol that Fielding and his friends created?

* General purpose protocol allowing machines to apply verbs to nouns

What does a GET do?

* GET is applied using the URL you typed and returns a webpage corresponding to this, this verb of getting can be applied to many things in URL request like image, text, .mp3, etc.

What does a POST do?

* POST is used when one system needs to add something into another system.

What does PUT do?

* PUT is used by a system to place something in another system overwriting what is currently held in that place.

What does PATCH do?

* PATCH should be used when a system is doing a partial update of something on another system to not overwrite everything in that location.

---

<===== [BACK!](README.md)

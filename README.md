# Programming as Conversation Part 3: Conclusion

In this module, we've learned to take our _expressions_ and _statements_ and
combine them into paragraphs with ***power***: _methods_.

Methods let us:

* Hide duplication ("DRY" out our code)
* Run tests against methods to verify their function (that's what Learn Labs
  run on!)
* _Abstract_ specific mechanical operations (evaluations and code flow) under
  English-like, human-brain-friendly names like `print_user_name`

***Crafting methods is the core responsibility of a programmer.***

Regardless of the language or the hardware, you're going to need to create
abstractions to do work in a way that's friendly to your own and your
co-workers' human brains. Writing better, more communicative lessons for other
humans will be a study for the rest of your career. But...learning to write the
proper syntax for Ruby, well &mdash; you've got that one down, now!

In the "Programming as Conversation" series we've been building up:

* _From_ ordinary life experience to learning about simple values and simple expressions (Part 1)
* _to_ wrapping the previous skills in REPETITION or SELECTION (Part 2)
* _to_ bundling the previous skills into methods (Part 3)

What's next? We're going to change our focus.  We've been learning how to _do_
more and more complicated things to this point.  What we want to cover next is
how to _store_ more complicated information.

To this point, the only material we've been storing has been _scalar_ data:
`String`s, `Integer`s, and `Float`s.  But there are two more data types that
we've not covered: `Array` and `Hash`.

`Array` and `Hash` are "collection" data types. While the variable `birthday`
holding a scalar `String` of `October 14, 1983` stores only _one_ date, an
`Array` might hold a collection of scalar `String`**s**. Or a `Hash` might hold
a collection of birthdays that could be pointed to by use of a short name like
`mike`, `rafael` or `kat`.

In the next module, we'll learn to use the skills you have now to work with
these collection data types. See you in "Programming as Conversation Part 4:
Collection Types!"

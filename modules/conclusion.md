<!--
name: conclusion
freshnessDate: 2015-04-04
version : "0.1"
title : "Conclusion and Next Steps"
description: "Review what learners have learned and suggest next steps"
privacy: "private"
license : "CC Attribution-ShareAlike 4.0"
-->

<!-- @section, "title": "Here is what you have learned" -->


In OLM, we can define multiple choice questions by putting them between a `@multipleChoice` and an `@end` annotation.

<!-- @multipleChoice -->

### Operator Precedence

Which of the following code snippets is equivalent to the following:

```javascript
`var x = a + b * c + d;`
```

- [ ] `var x = (a + b) * (c + d);`
- [ ] `var x = a + ((b * (c + d));`
- [X] `var x = (a + (b * c)) + d;`
- [ ] `var x = ((a + b) * c) + d;`

Remember, `*` has higher precedence than `+`, so it will bind tighter.

<!-- @end -->

Use `- [ ]` to start an incorrect answer, and `- [X]` to start a correct answer.
The markdown above the answers is treated as the question, and the markdown below the answers
is used as a 'hint' or 'explanation' that your learners can choose to reveal.


Multiple Choice answers support the full markdown syntax, but without the Outlearn extensions.

<!-- @multipleChoice -->

Which of these people created Linux?

- [ ] ![](http://upload.wikimedia.org/wikipedia/commons/thumb/0/01/Bill_Gates_July_2014.jpg/220px-Bill_Gates_July_2014.jpg)

  **Bill Gates**

- [X] ![](http://upload.wikimedia.org/wikipedia/commons/thumb/5/52/LinuxCon_Europe_Linus_Torvalds_03.jpg/220px-LinuxCon_Europe_Linus_Torvalds_03.jpg)

  **Linus Torvalds**

- [ ] ![](http://upload.wikimedia.org/wikipedia/commons/thumb/6/66/Guido_van_Rossum_OSCON_2006.jpg/200px-Guido_van_Rossum_OSCON_2006.jpg)

  **Guido van Rossum**

<!-- @end -->


Well done, you've covered a lot of ground. The key things you learned in this path are:

- Compare Riak with other NoSQL databases and also compare it with relational databases
- Install Riak on your own machine
- Perform CRUD operations in Python
- Use Python to query a Riak database
- Create Riak object models
- Use the HTTP API to perform operations related to buckets, objects, queries, servers, and searches.
- Use Riak with Clojure


<!-- @section, "title": "Here is what you now should be able to do" -->

To put all of this into practice, we expect that you are ready to do the following:

- Create additional buckets
- Model key-value pairs according to real-life data needs
- Perform basic maintenance on a Riak data store.

<!-- @section, "title": "Here are some future directions for your learning" -->

You'll get plenty of practical opportunities to use your Riak skills at SuperMegaCorp. If you are interested in delving deeper, here are some awesome resources:

- [Official Riak Docs by Basho](http://docs.basho.com/riak/latest/)
- [A Little Riak Book](http://littleriakbook.com)
- [Blog posts about key-value databases](http://highscalability.com/blog/category/key-value-store)

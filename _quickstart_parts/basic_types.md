---
collections: quickstart_parts
title: Basic Data Types
number: 4
---


### Strings

Strings are defined only by using `'` character

{% highlight clojure %}
string <- 'foo'
{% endhighlight %}

### Atoms

Atoms are defined by using `@` character.
Atoms are used as status words like `@good` or `@bad`.
Atoms are used as boolean data type: `@bad` and `@no` are false; other are true.
Standard boolean true is `@yes`.

    atom <- @bar

### Numbers

Number datatype in husky is the same as in other languages.

{% highlight clojure %}
number <- 12345
{% endhighlight %}

# Silly insult Generator

# Background

- In ruby, we can do things like `["apples", "pears", "grapes"].sample` to get a random array item.
- We can create a bunch of these arrays, string them together, and get a sentence output!

```
word_1 = ["my", "your", "our"].sample
word_2 = ["house", "pants", "shoes"].sample
word_3 = ["are", "could be", "used to be"].sample
word_4 = ["cool", "not cool", "kinda cool"].sample
[word_1, word_2, word_3, word_4].join(" ") #=> my shoes are cool
```

# Goals

- Goof off with ruby
- Make it easy to insult others, poorly
- get into the dev workflow
- make it an executable script that can be executed and output a random silly insult

## v1 goals

- get it working
- create a repo of v1 and readme

## v2 goals

- PR the changes
- support different dictionaries (like pirate, or ye olde)
- append a text file with each insult generated (maybe require each insult be unique!)
- explore using faker

## v3 goals

- refactoring for cleaner code & ergonomics
- PR the changes
- deterministic seeding (i.e. i like everything about this insult except the last word selected, so allow me to specify everything up to that point as a seed value)
- or anything else you think would be fun/cool

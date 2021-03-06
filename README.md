# Deep-Thought
An implementation of Deep Thought's algorithm (although shortened) of The Ultimate Question of Life, The Universe, and Everything; as well as The Answer to The Question.

## Content
Deep Thought created The Answer (after a couple billion years), and Arthur Dent (with Ford Prefect's help) invented The Question.

This is a fan project for The Hitchhiker's Guide to The Galaxy, and The Restaurant at The End of The Universe.
All rights reserved to their original, respective owners.

The code was originally from https://github.com/Keith-S-Thompson/42/ , and messes withh the preprocessor in C a lot.
Excerpt form Keith's README:

A macro that's intended to be used in an expression context generally
needs to be aggressively parenthesized.  You should have parentheses
around each reference to a macro parameter, and around the entire definition.

The reason is that macro expansion works on sequences of tokens.
The C preprocessor doesn't deal with high-level C syntax.

In the example, the macro `SIX` expands to the token sequence `1 + 5`,
and the macro `NINE` expands to `8 + 1`.  If each of these expressions
were evaluated on its own, the results would be 6 and 9, respectively,
But when they're combined in the expression `SIX * NINE`, the expansion is:

    1+5*8+1

which is equivalent to:

    1+(5*8)+1

or 42.
-- Keith Thompson <Keith.S.Thompson@gmail.com> Tue 2011-11-01

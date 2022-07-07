---
  layout: manual
  title: Writing Checklist
  subtitle: "Reduce clutter and increase clarity of any document with these rules"
  permalink: /manual/guides/writing/checklist/
---


## Stanford MOOC on Writing in the Sciences

This [writing checklist](/manual/guides/writing/checklist) is mostly from advice in this  [massively open online course](https://www.coursera.org/learn/sciwrite/). You can take it yourself for free at your own pace.

## Writing Checklist

You're a human writing for other humans: Make the wording exciting, and remember some people reading it won't know as much jargon as you do.

```markdown 
- [ ] Before writing, review the sections below on enhancing your writing.
- [ ] Run a spell checker.
- [ ] Expand all acronyms on first use (rely on the acros.tex file and glossaries package to automate this).
- [ ] Get rid of unnecessary prepositional phrases -- author clearing throat (It can be shown that)
- [ ] Get rid of extraneous adverbs (very, really, quite, basically, generally)
- [ ] Get rid of there are / there is
- [ ] Get rid of extraneous prepositions (the meeting happened on monday -> the meeting happened monday) (they agreed that it was true -> they agreed it was true)
- [ ] Get rid of passive voice (is/was/are/were/be/been/am + past tense verb), replace with active voice
- [ ] Make sure to cite all images, methods, software, and empirical data. Review [the principles](https://www.force11.org/software-citation-principles) and try [CiteAs](https://citeas.org/about) if necessary.
```

## Table and Figure Checklist
```markdown
- [ ] The text should refer to all tables and figures.
- [ ] When referring to figures by their number, use `Figure 1` and `Table 1.` They should be capitalized and not abbreviated (not `fig. 1` or `figure 1`.)
- [ ] In tables, align all columns of numbers such that the decimals line up.
- [ ] In a single column, all values should probably have the same number of significant digits.
- [ ] Give units for each numerical column.
- [ ] A table should have only 3 horizontal lines (no vertical lines and no more than 3).
```

Enhancing Clarity:

```markdown
- Use of "very" suggests that a cooler word exists.
- Articles such as "a" "the" "some" "any" and "each" must appear where necessary.
- All subjects must match the plurality of their verbs ( no: "Apples is tasty" yes: "Apples are tasty").
- Avoid turning verbs into nouns ("obtain estimates of" -> "estimates"; "provides a description of" -> "describes").
- A phrase of the form <verb>ion of <noun> is probably clearer as <noun> <verb>ion. (For example, convert "calculation of velocity" to "velocity calculation".)
- Reduce vague words (important, methodologic).
- Reduce acronyms / jargon.
- Turn negatives to positives (she was not often right -> she was usually wrong).
- Don't bury the verb (keep the predicate close to the subject at the beginning of the sentence).
- Refer to software consistently by name.
- Be concise and direct.
- When you introduce words or phrases that are unusual or likely to be unfamiliar to the reader, italicize them.
- If you use an uncommon word, either consider changing it or define it in its first usage.
```


Enhancing Style:

```markdown
- Punctuation helps you to vary your sentence structure.
- Power to separate in increasing power: comma, colon, dash, parentheses, semicolon, period
- In increasing order of formality: dash, parentheses, all of the others. Don't overdo it with the dash and parentheses
- If there's a list in a sentence, it shouldn't come before the colon.
- Always use isotopic notation like `$^{239}Pu$`. Never `$Pu-239$` or `$plutonium-239$`.
- Use strong verbs (use sparingly: is, are, was, were, be, been, am).
- Only use "large" when referring to size.
- Do not use the word "when" unless referring to a time (try "if" instead).
- Other misused/overused words include: code, input, output, different, value, amount, model.
- Each sentence/paragraph should logically follow the previous sentence/paragraph.
- When giving examples, use variables instead of numbers and use symbolic math instead of acronyms.
- Vary your sentence structure to keep readers engaged.
- Do not use contractions in technical writing.
```


Enhancing Grammar:

```markdown
- "Data" is plural (the data are critical).
- Commas and periods go inside end quotes, except for when there's parenthetical reference afterwards.
- Colons and semicolons go outside closed quotations.
- Compare to (point out similarities between different things) vs.  compared with (point out differences between similar things)
- Semicolon: connects two independent clauses. OR separates items when the list contain internal punctuation.
- Use a colon to introduce a list, quote, explanation, conclusion, or amplification.
- Elemental symbols (Ni, Li, Na, Pu) are capitalized, but their names are not (nickel, lithium, sodium, plutonium).
- The Oxford comma must appear in lists ("lions, tigers, and bears").
- Do not use the word "where" unless referring to a location (try "such that" or "in which").
- Avoid run-on sentences.
- The preposition "of" shows belonging, relations, or references. The preposition "for" shows purpose, destination, amount, or recipients. They are not interchangeable.
```

Additional Math Comments:
```markdown
- Define all variables, with units. If unitless, indicate that this is the case `$[-]$`.
- Subscripts should be brief and can be avoided with common notation. For example, `$\dot{m}$` is better than `$m_f$` which is superior to `$m_{flow}$`.
- Variable names should be symbols rather than words `m` is better than `mass` and `\ksi` is better than `one_time_use_variable`.
- The notation `$3.0\times10^{12}$` is preferred over `$3e12$`.
- Equations should be part of a sentence.
- Equations should be in the `align` environment. Align them at the `=` sign.
- Variables should be defined in the `align` environment as well, not buried in paragraphs.
```

Here's an example of an equation:
```latex
The line is defined as
\begin{align}
y&=mx + b
\intertext{where}
y&= \mbox{ height of the line, also known as rise [m]}\nonumber\\
m&= \mbox{ slope [-]}\nonumber\\
x&=\mbox{ independent parameter, known as run [m]}\nonumber\\
b&= \mbox{ y intercept [m].}
\end{align}
```

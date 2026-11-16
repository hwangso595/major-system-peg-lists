# Major System peg lists: 00 to 99 and 000 to 999

Free word lists for the Major System, the mnemonic that turns digits into
consonant sounds and the sounds into words you can picture. There is one
word for every number from 00 to 99 and one for every number from 000 to
999, as CSV and JSON, ready for flashcard apps, memory tools, spreadsheets
or your own study.

The lists are the ones published on [Major Dictionary](https://majordictionary.com),
where you can browse the [00 to 99 chart](https://majordictionary.com/major-system),
print it as a [one-page PDF](https://majordictionary.com/major-system-chart.pdf),
and read [how the Major System works](https://majordictionary.com/technique/major-system).

## The sounds

| Digit | Sounds | Example |
|---|---|---|
| 0 | s, z, soft c | sauce (00) |
| 1 | t, d, th | tea (01) |
| 2 | n | Noah (02) |
| 3 | m | Ma (03) |
| 4 | r | ray (04) |
| 5 | l | law (05) |
| 6 | sh, ch, j, soft g | shoe (06) |
| 7 | k, hard c, hard g, q | key (07) |
| 8 | f, v | ivy (08) |
| 9 | p, b | pie (09) |

Vowels carry no value, so they are free filler. The sound counts, not the
spelling: "knight" is n-t, 21, because the k and gh are silent, and a
doubled consonant counts once, so "kettle" is k-t-l, 715.

## Files

| File | Rows | Columns |
|---|---|---|
| `major-00-99.csv` | 100 | `number`, `peg`, `hook` |
| `major-000-999.csv` | 1,000 | `number`, `peg`, `hook` |
| `pegs.json` | both lists | the same three fields, keyed by list |

`number` is a string with its leading zeros kept ("07", "007"). `peg` is the
word or phrase. `hook` is a one-line image to help it stick; it is empty for
some of the three-digit pegs.

Two things to know about the 000 to 999 list:

- From 001 to 099 the leading zero is silent, so each of those numbers
  reuses its two-digit peg (007 is "key", like 07). 000 has its own word.
- Where no single picturable word fits a number, the peg is a two-word
  phrase that still decodes exactly, usually a two-digit peg followed by a
  one-digit one: 138 is "tomb ivy", tomb for 13 and ivy for 8. Nearly half
  of the list (462 numbers) is phrases like this.

## Licence and credit

The lists are licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)
(the full text is in `LICENSE`). You may copy, adapt and use them for any
purpose, including commercial ones, as long as you credit the source. A line
like this is enough:

> Major System peg lists from [Major Dictionary](https://majordictionary.com), CC BY 4.0

Spotted a peg that does not decode, or have a better word for a number?
Open an issue here.

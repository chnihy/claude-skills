# Numbers, dates, times, abbreviations, and articles

Condensed from developers.google.com/style/numbers, /dates-times, /abbreviations, /articles, /units-of-measure.

## Numbers

**Spell out**
- Zero through nine, unless an exception below applies.
- A number that starts a sentence. Rephrase if that reads badly. A four-digit year at the start is tolerable.
- A number immediately followed by a numeral: "fifteen 100,000-byte files."
- Approximate large figures: "millions of rows." Use numerals for precise figures.
- All ordinals: first, fifth, twelfth, forty-third. Never 1st, 5th, 12th.
- A percentage that starts a sentence: "Forty percent of the files."

**Numerals**
- 10 and greater.
- Always, even below 10: version numbers ("version 3"), technical quantities with units (6 queries per second, 128 bits, 2 GB), page and chapter numbers, step numbers, prices, bare math values, and numbers under 10 in the same sentence as numbers over 9.
- Negative numbers, decimals, fractions, percentages, dimensions, measurements, ranges.
- Decimals under one take a leading zero: 0.3 inches. Decimals are plural: 1.0 inches.

**Format**
- Commas every three digits for numbers of four or more digits: 1,000, not 1000.
- No grouping to the right of the decimal point.
- Ranges with a hyphen, no spaces: 2012-2016, 5-10 minutes. Or "from 8 to 20." Never an en dash, never a hyphen mixed with "from" or "between."
- Percentages: numeral plus percent sign, no space: 40%.
- Dimensions: numerals and a lowercase x, no spaces: 192x192.
- Prefer decimals to fractions: 0.75. If you must spell a fraction, hyphenate: two-fifths, one and one-half.
- Suspended hyphens for shared bases: "one-, two-, or three-hour intervals."
- Avoid Roman numerals except for sub-sub-steps in procedures.
- Don't use symbols for words: "10 times faster," not "10x faster."
- Currency: say which country. US dollars as $1,234.56.

**Units**
- Space between number and unit: 10 MB, 5 GB, 200 ms. Exceptions: percentages (40%) and degrees (90°).
- Units don't take a hyphen when used as a modifier: "a 200 GB disk." Spelled-out units do: "a five-minute wait," "a 64-bit system."
- Use the unit's standard abbreviation after first use: MB, GB, MiB, GiB, ms, Mbps (bits), MBps (bytes). Don't write "MB/s."
- Pair numbers with their practical meaning when it helps: say what the limit implies, not only the figure.

## Dates

- Spell out the month, give the day and a four-digit year: January 19, 2017.
- With a weekday, weekday first: Tuesday, April 27, 2021.
- Month and year only, no comma: January 2017.
- A full date mid-sentence takes a comma after the year: "The January 19, 2017, release." Month-year does not: "The January 2017 release."
- Abbreviate only when space is tight (headings, tables): Mon, Sep 3, 2018. Three letters, no period, consistent across the page.
- Never all-numeric dates with slashes or dots. If a numeric date is required, ISO 8601: 2017-04-15.
- In fictional examples, pick a day above 12 so it can't be read as a month.
- Date before time: "2017-04-15 at 3 PM" or "May 4, 2009, at 6 PM."
- Avoid season names. Use months or quarters. August isn't summer everywhere.
- Don't use "the holidays." Name the months.

## Times

- 12-hour clock unless the UI, command, or code uses 24-hour time. Then use 24-hour throughout the page.
- AM and PM in caps, one space before: 3:45 PM. Drop minutes on the hour: 3 PM. "Noon" and "midnight" are fine.
- Time ranges with a hyphen, no spaces: 5-10 minutes ago.
- Avoid time zones unless necessary. "10 AM your local time" when it's local. Otherwise spell out the zone and add the UTC offset: Pacific Standard Time (UTC-8). Don't abbreviate zone names.

## Abbreviations

**Types.** Acronyms (pronounced as a word: NATO), initialisms (letters: API, CPU), and shortened words (Dr., etc.). The distinction rarely matters. Short words like "app," "demo," and "sync" are words, not abbreviations.

**When to use one.** When it saves the reader time. Not when the reader has to stop and decode it. Don't abbreviate terms unrelated to the document's topic.

**Spelling out.**
- On first mention, spell it out and follow with the abbreviation in parentheses: "service level objective (SLO)." Abbreviation alone afterward.
- If you use the term once, use whichever form is more common. Don't introduce an abbreviation you won't reuse.
- First mention in a heading: abbreviation in the heading, spelled out in the first paragraph after.
- Don't capitalize the spelled-out form unless it's a proper noun: "data manipulation language (DML)," not "Data Manipulation Language."
- Don't spell out when the expansion doesn't help: PDF, HTML, URL, USB, API, AI, CPU, RAM, REST, OS, MB, GB, DVD, PC, SQL, JSON, XML.
- Consider the audience and translation. Spelling out helps non-native readers.

**Format.**
- No periods in acronyms or initialisms: API, US, DC.
- Periods in shortened words except dates and times: Dr., approx. (but prefer the full word).
- Plurals like regular words: APIs, URLs, OSes.
- Not as verbs: "Connect using SSH," not "SSH into." "Use RDP," not "RDP to."
- Articles by sound: a SQL query, an SAP system, a FHIR resource, an HTML file, a URL, an API.
- Include the abbreviation inside link text.

**Avoid.**
- Latin: e.g. (use "for example"), i.e. ("that is"), etc. (rephrase), vs. ("versus"), N.B., viz.
- Internet slang: tl;dr, ymmv, RTFM, aka, FYI.
- Shortened common words: "approximately," not "approx."; "configuration," not "config"; "repository," not "repo"; "regular expression," not "regex."
- Symbols standing in for words: "and," not "&"; "10 times," not "10x"; "plus," not "+" (in formal text).

## Articles

- Include "a," "an," and "the." Don't drop them for brevity, in prose or headings. "Create a VM instance," not "Create VM instance."
- Choose "a" or "an" by the sound of the next word as most readers pronounce it, not by its first letter.
- Product names: generally no article before a product name used as a proper noun ("Compute Engine lets you..."), but an article before a product name used as an adjective ("a Compute Engine instance").

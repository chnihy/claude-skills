# Punctuation

Condensed from the punctuation pages of developers.google.com/style. American English conventions throughout.

## Commas

- **Serial comma.** In a series of three or more, put a comma before the final "and" or "or." "Zones, regions, and multi-regions."
- **After introductory words and phrases.** "Finally, only groups that contain parameters appear." "Based on your requirements, you can implement this method."
- **Before "which" in a nonrestrictive clause.** "Name of the group, which has a maximum length of 200 characters." No comma before restrictive "that."
- **Between independent clauses** joined by and, but, or, nor, for, so, yet. "The libraries make feed creation easier, and they ensure that only valid feeds are produced." Skip the comma when both clauses are very short: "Type your ID and click **OK**."
- **Dependent clauses.** No comma between an independent and dependent clause joined by a conjunction, unless the sentence is ambiguous without it. "Direct-access flags are plain variables and can be read directly."
- **Conjunctive adverbs** (otherwise, however, therefore). Use a semicolon, period, or em dash before, and a comma after. "The variable must have a value; otherwise, the server returns an error."
- **Because.** No comma before "because" unless it starts a nonrestrictive clause.
- **For example.** Always followed by a comma.

## Colons

- A colon signals that closely related information follows. The text before it must stand alone as a complete sentence. "The fields are defined as follows:" not "The fields are:".
- The first word after a colon is lowercase, except: a proper noun, a heading, a quotation, or text after a notice label such as **Note:**.
- Use a colon, not a dash, to separate an item from its description. "Example: This is an example." "Appendix A: Setup."
- End a list or code introduction with a colon when the list or code follows immediately. Use a period when something (a note, an unrelated sentence) sits between them.

## Semicolons

Avoid where possible. Use one only to:

1. Join two closely related independent clauses when a period reads worse. "Compute the centroid to test compatibility; if it's on the opposite side of the planet, reverse the order of your vertices."
2. Precede a conjunctive adverb or transition between independent clauses. "Only the stereo cameras are affected; therefore, the head-tracked node is unaffected."
3. Separate items in a series when the items contain their own commas. "Check for present tense and active voice; typos, punctuation, and grammar; and anything you can shorten."

## Em dashes

- Mark a break in the flow of a sentence—or an interruption. No space before or after.
- Prefer a colon, a period, or "for example," in most places a dash might go. Never use a dash to separate an item from its description.
- Type it as Option+Shift+hyphen on macOS, or `&mdash;` in HTML.

## En dashes

Don't use them. Use a hyphen for ranges ("5-10 minutes") and the word "to" or "through" where a hyphen is ambiguous. Don't use a spaced en dash in place of an em dash.

## Hyphens

- Use a hyphen only to prevent misreading or to join terms read as one unit. When unsure, check the word list, then Merriam-Webster.
- Don't use a hyphen or a double hyphen in place of a dash.

**Prefixes.** Generally closed: infrastructure, metadata, preprocessing, nonblocking, reusable, multicloud. Hyphenate when:
- The prefix is "self-" or "cross-": self-managing, cross-region.
- The base is capitalized or a number: non-Google, post-2000.
- Omitting the hyphen causes confusion: de-energize, re-sign (versus resign), re-create (versus recreate).
- The base already has a hyphen or a space: un-Google-like, non-self-sustaining.

**Compound nouns.** Closed unless the word list says otherwise: webpage, hostname, tradeoff, workaround, codebase. Multiplied units are hyphenated: 5 vCPU-hours, 40 person-hours.

**Compound modifiers before a noun.** Hyphenate for clarity: a well-designed app, Android-specific techniques, a 64-bit system, a five-minute wait. Avoid modifiers longer than two words; move words after the noun. Don't hyphenate -ly adverbs ("publicly available") or conventional open compounds ("machine learning model"). Don't hyphenate abbreviated units ("200 GB disk").

**After a verb.** Usually no hyphen: "The app is well designed." "Logs are written in real time." Some terms always keep the hyphen: on-premises, customer-facing, user-friendly, read-only.

**Ranges.** Hyphen, no spaces: 8-20 files, 5-10 minutes, 2012-2016. If ambiguous, write "from 8 to 20 files." Don't mix the hyphen with "from" or "between."

**Suspended hyphens.** "One- or two-hour intervals." "One-, two-, or three-hour intervals." Space after the suspended hyphen, not before.

## Parentheses

- Don't hide important information in parentheses. Some readers skip them.
- Question every parenthetical. Commas, a dash, or a new sentence usually read better.
- Keep a mid-sentence parenthetical short. If the aside is long, make it a second sentence.
- A complete sentence inside parentheses takes its period inside the closing parenthesis.
- Don't use parentheses for optional plurals: "file(s)." Write "files" or "one or more files."

Recommended: "Enter a six-digit hex number, and then click **OK**. For example, for forest green, enter `228B22`."
Not recommended: "Enter a six-digit hex number (for example, if you want forest green, enter `228B22`), and then click **OK**."

## Quotation marks

- Use sparingly. In technical writing their main jobs are: titles of short works (articles, episodes) when not linked; a section of a document you can't link to; a direct citation of a person, slogan, or motto; a term used metaphorically when that isn't established usage.
- Commas and periods go inside the closing quotation mark: See the section titled "Care and feeding of the emu."
- Exception: when quoting a keyword or literal string, put the punctuation outside: If you enter "escape", the program crashes. Better: use code font and no quotes: If you enter `escape`, the program crashes.
- Never put quotation marks around code-font text unless the quotes are part of the code.
- Always straight quotes and straight apostrophes, never curly.
- Single quotes only in code and for a quotation nested inside another quotation.
- Don't put link text in quotation marks.

## Exclamation points

Don't use them. They read as unprofessional or alarming and translate poorly. Mark completion with a period: "The VM is created." Acceptable only when part of code (`!=`) or a literal system string. Tutorials may use one at a major milestone, and only one.

## Slashes

Avoid outside code, file paths, and URLs.

- Not for alternatives: "five or six times," not "5/6 times." "Developed or hosted," not "developed/hosted."
- Not "and/or": "You can view and edit your data." "Export raw events, processed events, or both."
- Not for dates: use "October 13, 2026" or `2026-10-13`.
- Not for fractions: 0.75 or 75%, not 3/4.
- Not for abbreviations: "with," not "w/." "Care of," not "c/o."
- Forward slashes in paths and URLs. Backslashes in Windows paths. If a URL must wrap, break after a slash and never insert a hyphen.

## Apostrophes

- Don't form plurals with an apostrophe: APIs, 1990s, URLs.
- Don't make trademarks possessive or plural.
- Straight apostrophes only.

## Periods

- One space after a period.
- No period at the end of a heading, a table cell that's a fragment, a list item that's a single word or noun phrase, or a line of code.
- Full sentences in list items end with a period. Mixed lists get periods on every item.

## Ampersands

Don't use "&" for "and" in text, headings, or navigation. OK when part of a UI label ("**Save & Exit**"), in a space-constrained table header, or in code.

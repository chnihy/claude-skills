# Inclusive language, accessibility, jargon, and global audience

Condensed from developers.google.com/style/inclusive-documentation, /accessibility, /jargon, /anthropomorphism, /translation, /pronouns, /examples.

## Inclusive documentation

**Gendered language.** Use the singular "they." Never "he," "she," "he/she," "(s)he," or "his or hers" for an unknown or generic person. Don't guess gender from a name. Replace gendered nouns: person-hours, staffed, workforce, humanity, artificial.

**Figurative language.** Use simple, precise, literal terms. No idioms, figures of speech, or metaphors. Don't use a technical term in a metaphorical sense. "Pets versus cattle" becomes "persistent versus dynamic."

**Ableist language.** Avoid "crazy," "insane," "blind to," "turn a blind eye," "cripple," "dumb," "lame," "sanity check," "dummy." Replacements: "baffling outliers," "slows down the service," "placeholder," "final check for completeness," "quick check."

**Violent language.** Avoid "hang," "hit," "kill," "nuke," "blast radius," "STONITH," "war room," "break-glass." Replacements: "doesn't respond," "click," "stop," "remove," "affected area," "fence failed nodes," "incident team," "emergency access." If an industry term is unavoidable, mention it once, de-emphasized: "(sometimes called *STONITH*)."

**Subjective modifiers.** Don't use "simple," "simply," "easy," "easily," "quick," "quickly," "careful," "carefully," "thorough," "thoroughly," "proper," "properly." They assume the reader's experience or imply carelessness. Replace with a verifiable check: instead of "Ensure the daemon is properly installed," write "Run `systemctl status DAEMON_NAME` and confirm the output shows `active (running)`."

**Socially charged terms.** Replace "whitelist" and "blacklist" (allowlist, denylist, blocklist), "master" and "slave" (primary, replica, worker, parent), "native" feature (built-in), "first-class citizen" (a precise term), "native speaker" (rewrite so it applies to anyone), "grandfathered" (legacy, exempt), "tribal knowledge" (undocumented knowledge), "guru," "ninja," "sherpa" (expert, guide), "man-in-the-middle" (on-path attacker).

**Replacing established terms.** On first use, name the old term in parentheses, then use the replacement: "an allowlist (sometimes called a *whitelist*)." Rewriting the sentence is often better than swapping one word.

**Code terms.** When a keyword or identifier uses a non-inclusive term, minimize its use, keep it in code font, and refer to it with the preferred term in prose: "the parent node (named `master` in the file)."

**Disability.** Don't describe people without disabilities as "normal" or "healthy." Use "nondisabled," "sighted," "neurotypical." Generally use "people with disabilities," but respect identity-first preferences where communities hold them (autistic, blind, Deaf). Avoid "victim of," "suffering from," "wheelchair-bound," "physically challenged," "special," "differently abled." Use "living with," "experiencing," "uses a wheelchair."

**Older adults.** Not "the elderly," "seniors," "senior citizens," "80 years young." Use "older adults" or the specific age range.

**Diverse examples.** Vary names, genders, ages, and locations. Avoid US-specific holidays, sports, and cultural references.

## Accessibility

**Text**
- Keep sentences under 26 words. Break long text with headings, lists, and paragraphs.
- Define acronyms on first use, and again if they're rare in the document.
- Most important information in the first sentence of a paragraph.
- Clear, direct language. No double negatives: "You can continue without a path," not "A missing path won't prevent you from continuing."
- Left-align. Don't center or justify.
- Avoid camel case and all caps in prose. Screen readers announce formatting and mangle unusual casing.
- Don't rely on punctuation to carry meaning. Some screen readers skip it. Avoid exclamation points, question marks, and semicolons where possible.
- "And," not "&."
- Parallel structure for similar items.

**Headings.** Descriptive and unique. Strict hierarchy, no skipped levels. Real heading markup. One level-1 heading.

**Links.** Text that makes sense out of context. No "click here" or "read this." Introduce with "see." Explain unexpected behavior (download, new tab, same-page jump). Separate adjacent links with text.

**Lists.** Each procedure step is its own list item.

**Images.** Every image gets alt text that summarizes its intent; decorative images get empty alt text. Put any new information from an image into the surrounding text too. No images of text, code, or terminal output. SVG over PNG when possible.

**Video.** Captions, transcripts, or descriptions. No flashing content.

**UI references.** Refer to elements by their label. Never by position ("above," "below," "right-hand side," "left nav"). Use "preceding," "following," "earlier," "later." If an element is hard to find, give context or a screenshot.

**Tables.** Introduce each table in text. Header markup on the first row and column only. No merged cells. Not mid-procedure.

**Forms and interactive elements.** Label every input, label outside the field. Error messages say what went wrong and how to fix it: "Name is a required field." Introduce expand-collapse controls in the text before them, by label: "expand the **Requirements** section."

**Test.** The document should work without sound, with only sound, without images, without color, with only a keyboard, with magnification, and without punctuation. Never color, size, or position alone to convey meaning.

## Jargon

Jargon is the specialized, often figurative vocabulary of a group: camel case, swim lane, break-glass, out-of-the-box. Vague overloaded words like "solution," "support," "workload," "leverage" count too.

Before using a term, ask in order:

1. **Can you write around it?** "Hold a post-mortem" becomes "review which processes worked and which didn't."
2. **Is there a more specific term?** "Blast radius" becomes "affected area." "Ingest" becomes "import" or "load." "Off-the-shelf" becomes "ready-made."
3. **Used once?** Describe it plainly and put the term in parentheses, or link a trusted definition: "move the task earlier in the process (also known as *shifting left*)."
4. **Used throughout?** Describe it in parentheses on first use: "a *cold standby* (a backup system identical to the primary)."
5. **In a command or code sample?** Use the word only when referring directly to the code item, in code font, and say what it means: "Add a user to the allowlist (`whitelist`) by running..."

Industry-standard jargon the audience searches for is acceptable when defined.

## Anthropomorphism

Don't give software or hardware human qualities. It's figurative, less precise, and harder to translate.

- "A Delimiter object specifies where to split a string." Not "tells the splitter where a string should be broken."
- "The PC detects a new device." Not "The PC sees a new device."
- "The compiler reports an error." Not "The compiler complains."
- "The function expects a string" is borderline; prefer "The function takes a string."

Describe what the system does in literal, mechanical verbs: returns, detects, reports, sends, stores, reads, checks, requires.

## Writing for a global audience

Assume the reader may read English as a second language and that the text may be machine translated.

**Words**
- Simple verbs: start, use, so, because. Not commence, utilize, leverage, consequently.
- One word for a phrase: "some," not "a number of"; "to," not "in order to."
- Replace phrasal verbs with a single verb where one exists. "Set up," "sign in," and "log in" are accepted exceptions.
- Each word in its primary sense. Don't use a word as both noun and verb nearby.
- Spell out abbreviations on first use.

**Sentences**
- Short. Standard subject-verb-object order. Main subject and verb near the start.
- Condition before instruction.
- No more than two nouns modifying another noun. "A cloud-native DevSecOps pipeline in a hybrid environment," not "a hybrid cloud-native DevSecOps pipeline."
- Put "only" directly before the word it modifies: "Request only one token."
- Avoid gerunds, especially "using." Write "by using," "that uses," or rephrase: "Configure the firewall rules before you deploy the VM," not "Configuring firewall rules is required before deploying."
- Keep helper words: "then," "that," "of," "which." "Start the profiler, and then run the app."
- Replace ambiguous pronouns with the noun. Repeat the noun when repetition helps.
- Add a qualifying noun to code: "the `example.yaml` file."
- Avoid negative constructions. Say what the reader can do.

**Consistency**
- Same term, same capitalization, same concept, every time. Translators treat inconsistent names as different things.
- Standard phrases for standard jobs: "For more information, see," "The output is similar to the following:," "Replace the following:".
- Parallel lists. Consistent bold and italic.

**Culture**
- No idioms ("ballpark figure," "back burner"), humor, pop culture, seasons, or regional holidays.
- Unambiguous dates. Diverse example names.
- Screenshots and figure text sparingly. Images aren't translated. Put the information in text.

## Pronouns

- Every pronoun must clearly point to one noun. After "this," "these," "that," add a noun: "Set this value to true," not "Set this to true." "These approaches are your best options."
- Prefer repeating the noun over an ambiguous "it": "If you type text in the field, the text doesn't change."
- Keep "that" and "which" when they prevent ambiguity: "Right-click the link that you want to open." "You can use other parameters, which are described in the following section."
- "That" introduces a restrictive clause, no comma. "Which" introduces a nonrestrictive clause, with a comma. Don't swap them.
- "Who" for people where "that" would sound wrong. "Whose" works for people and things.
- First person ("I," "we") only in FAQ questions, author-voiced documents, and for the authoring organization after it's named.

## Example values

Never real PII. Use reserved and fictional values.

- **Domains:** example.com, example.org, example.net.
- **Email:** dana@example.com, support@example.net. No real or product names in the local part.
- **Given names:** Alex, Amal, Ariel, Bola, Charlie, Cruz, Dana, Dani, Hao, Ira, Izumi, Jie, Kai, Kalani, Kim, Kiran, Lee, Lucian, Luka, Mahan, Noam, Nur, Quinn, Raha, Rosario, Sasha, Tal, Taylor, Tristan, Yuri. Surnames as an initial only: "Quinn N." Pronoun "they." Alice and Bob only when citing a spec that uses them.
- **Company:** Example Organization. "Startup Example Organization" and "Enterprise Example Organization" to distinguish two.
- **Phone:** 800-555-0100 through 800-555-0199.
- **IPv4:** 192.0.2.0/24, 198.51.100.0/24, 203.0.113.0/24. **IPv6:** 2001:db8::/32.
- **Street address:** 1800 Amphibious Blvd., Mountain View, CA 94045.
- **Project and resource names:** meaningful and descriptive, never foo, bar, baz. Use suffixes to distinguish: production-1, staging, frontend-development.

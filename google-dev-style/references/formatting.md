# Formatting and structure

Condensed from the formatting pages of developers.google.com/style: lists, tables, headings, procedures, code in text, code samples, placeholders, UI elements, notices, link text, and command-line syntax.

## Headings and titles

**Text**
- Base a title on the document's primary purpose. A tutorial with a conceptual intro still gets a task-based title.
- Task-based headings start with a bare infinitive: "Create an instance." Not "Creating an instance."
- Conceptual headings are noun phrases: "Migration to Google Cloud." Not "Migrating to Google Cloud."
- Don't start a heading with an -ing verb. Established nouns like "Billing" and "Pricing" are exceptions.
- Mark optional sections with a prefix: "Optional: Customize your alias." Not "(optional)" at the end.
- Exactly one level-1 heading per page, unique within the doc set. Don't repeat it as a heading in the body.
- Refer to a group of subsections as "the following sections," not "this section."

**Format**
- Sentence case. Keep punctuation minimal. No ending period.
- Limit abbreviations. Use one only if it's the better-known form, and define it in the first paragraph after the heading.
- Don't number headings. Hierarchy shows order.
- Avoid code in headings. If unavoidable, code font plus a descriptive noun: "The `project.yml` file."
- No links in headings.
- Strict hierarchy. Don't skip levels. Don't leave an empty heading.
- Include articles. "Create a VM instance," not "Create VM instance."

## Lists

**Choosing a format**
- Numbered list when order matters: steps, phases, priorities.
- Bulleted list for sets with no sequence: options, examples, features. Make clear whether each item is required.
- Description list for term-and-explanation pairs: glossaries, parameters. In Markdown, use a bold run-in term followed by a colon or period.
- Table when each item has three or more related pieces of data.
- Never a list of one item.

**Introducing a list**
- Write a complete sentence. "The following" works as a noun: "Configure the following:"
- Colon if the list immediately follows. Period if a note or other text sits between.
- Skip the intro only when the heading already provides full context.
- Don't write a partial sentence that the items complete.

**Items**
- Parallel structure: same grammatical form, same tense, same capitalization, same punctuation for every item.
- Capitalize the first word unless case carries meaning (a glossary term, a code identifier).
- End with a period if the item has a verb or is a full sentence. No period for a single word, a noun phrase, pure code, or pure link text. If a list mixes types, add periods to every item or rewrite for parallelism.
- Multiple paragraphs inside an item are fine. Indent them to the item.
- Sub-items in numbered lists use lowercase letters, then lowercase Roman numerals.

**Description lists with run-in headings**
- Capitalize the term. End it with a colon or a period, consistently across the list.
- After a period, capitalize the description. After a colon, lowercase it.
- If the heading ends in a colon and the description is a fragment, no ending period. If it has a verb, add one.
- Separate term from description with a colon or period, never a dash.

**Prose lists**
- Serial comma before the final conjunction.
- Don't end with "etc." Introduce the list so it's clear the examples aren't exhaustive: "such as," "including," "for example."

## Procedures

- A procedure is a numbered sequence of steps. A single-step procedure is one bulleted sentence.
- Introduce with a sentence that adds context not already in the heading. Colon if steps follow immediately.
- One action per step. Start each step with an imperative verb. Sequential menu selections can combine: "Select **File > New > Project**."
- Order inside a complex step: action, command, placeholder explanations, more detail, output, result (separate paragraph).
- State the location before the action: "In the **Build Settings** tab, set the target."
- State the goal before the action: "To save the file, press Control+S." If the goal makes the step look optional, use "[Goal]: [action]" instead.
- State the result after the action, same paragraph. State a justification after the action: "Store the private key in a secure place. You need it later."
- Mark optional steps with "Optional:" at the start.
- Include "press Enter" in the same step as the typed input.
- Don't offer alternative methods. Give the shortest one that works with only a keyboard.
- Don't repeat a procedure. Link to it.
- List required tools and prerequisites before the first step, not in a note.
- Don't write "run the following command." Say what the command does.
- Don't document keyboard shortcuts unless they're the subject.

## Tables

- Use a table for two-dimensional data: each row has three or more related values. Use a list for one-dimensional data. Don't split a long list into columns to save space.
- Introduce every table with a complete sentence that says what it shows. Colon if the table follows immediately. Not all screen readers announce tables.
- Refer to position as "the following table" or "the preceding table." Never put a table mid-sentence.
- Column headings: sentence case, concise, no ending punctuation.
- Cells: sentence case. Fragments take no period. Sentences do. Be consistent within a column.
- Don't merge cells. Don't use color or font alone to mark headers. Sort rows logically or alphabetically.
- Caption only when several tables are near each other: "**Table 1.** Prehistoric birds." Refer to tables by number in text.
- Avoid a table in the middle of a numbered procedure.

## Code in text

Use code font (backticks in Markdown) for anything the reader types or the computer emits:

- Attribute names and values, class names, element names (no angle brackets), enum names
- Command-line utility names (`gcloud`, `kubectl`, `xcodebuild`), command output, text the reader types
- Data types, database elements (row and column names), defined constants
- Environment variables, namespace aliases, language keywords, method and function names
- Filenames, extensions, paths, folders, directories
- HTTP content types, status codes (`404 Not Found`), verbs (`GET`, `POST`)
- IP addresses, port numbers, DNS record types, IAM role names
- Package names, query parameter names and values
- Placeholders
- URLs and domain names when used in commands or code
- UI elements built from text the reader entered, such as a server name

Ordinary font for: product, service, and organization names; domain names in prose; URLs the reader follows in a browser (prefer a descriptive link).

**Rules**
- Don't add quotation marks around code unless they're part of it.
- Don't use a code element as an English verb or noun, and don't inflect it. "Send a `POST` request," not "`POST` the data." "Several `Delimiter` objects," not "several `Delimiter`s."
- Add a noun after a code term: "the `project.yml` file," "the `--verbose` flag."
- Omit the class name from a method unless it's ambiguous.
- Status codes: "status code," not "error code" or "response code." Number and name in code font. Ranges as `2xx` or `200`-`299`.
- When a UI element also meets the code-font criteria, use both bold and code font.
- Boolean values: code font for the literal (`true`), ordinary font for the concept ("evaluates to true").
- Email addresses: code font when the reader types or sees them as input or output. Ordinary font with a link when they're a contact point.

## Code samples

- Introduce with a sentence that says what the sample does. Colon if the sample follows immediately.
- Fenced code blocks in Markdown, with a language tag.
- Indent per the language's style guide. Usually two spaces.
- Wrap at 80 characters.
- Mark omitted code with a comment in the sample's language. Don't use three dots or an ellipsis character in code. Don't make a block with omissions click-to-copy.
- Follow the relevant Google style guide (or the project's own) for the language itself.

## Command-line syntax

- Link to or name the command reference when introducing a command.
- Keep examples runnable. Only runnable code and placeholders in a copyable block. No `[optional]`, `{a|b}`, or `...` in copyable commands. Show the common case and name extra flags in prose, or give each variant its own block.
- Break lines over 80 characters before a hyphen, underscore, or quote. End each continued line with ` \` (space, backslash) on Linux and macOS, ` ^` on Windows. Indent continuation lines four spaces.
- Prompt symbol (`$`) on each input line when a block has several input lines. Optional for a single line, but be consistent within a page. Don't show the directory in the prompt.
- Input and output in separate blocks. Introduce output with "The output is similar to the following:".
- Mark omitted output lines with `...` on their own line.
- Explain placeholders after the command with "Replace the following:".
- In syntax diagrams (not copyable examples): `[optional]`, `{a|b}` for mutually exclusive, `ARG ...` for repeatable.
- Terminology: a *flag* is anything other than the command name. An *argument* is a value a command or flag takes. "Option" is an acceptable catchall. For Linux commands, describe what the whole command does rather than naming every element.
- Signals: use the signal name (`SIGTERM`, `SIGKILL`) for process control and don't substitute "kill," "terminate," or "stop" as synonyms.

## Placeholders

- A placeholder is a value the reader replaces. Give it a descriptive name: `PROJECT_ID`, `BUNDLE_ID`, `SIMULATOR_UDID`.
- Uppercase with underscores. No hyphens, spaces, lowercase, or camel case. No possessives: not `MY_PROJECT` or `YOUR_API_KEY`.
- Don't use a lone `x` or `xxx` except where that's the convention (status code ranges).
- In Markdown: code font inline. In a code fence, plain uppercase, since bold and italic don't render inside fences.
- Explain every placeholder on first appearance, and again in a long document or procedure.
- One placeholder: "Replace `PLACEHOLDER` with a description of what it represents."
- Two or more: introduce with "Replace the following:" then a bulleted list, in the order they appear, each as `PLACEHOLDER`: lowercase description. Introduce an example value in the description with "such as" or an em dash.
- Placeholders in output: introduce with "This output includes the following values:" and the same list format.

Example:

```
xcodebuild -scheme APP_NAME -destination 'id=SIMULATOR_UDID' build
```

Replace the following:

- `APP_NAME`: the scheme name in the Xcode project
- `SIMULATOR_UDID`: the simulator identifier from `xcrun simctl list devices`

## UI elements and interaction

**Focus on the task.** Say what the reader accomplishes. Mention a widget or gesture only when it adds clarity. "Refresh the page," not "Click the refresh button."

**Bold** the visible label of buttons, menus, tabs, dialogs, windows, fields, checkboxes, and list items. Match the capitalization on screen. If the label is all caps or inconsistent, use sentence case. Don't bold product or feature names unless they match an on-screen element.

**Don't use a label as a verb or noun.** "In the **Name** field, enter a name," not "**Name** the account."

**Terminology**
- *Window*: an app window or closable module. *Page*: a web page or console subpage. *Dialog*: a smaller window in front of the main one. *Pane* or *panel*: a region within a window. *Section*: a labeled group of controls.
- *Navigation menu*, not navigation bar or nav pane. *Toolbar*: a set of buttons.
- *Field* (or *box*) for text input, never "text box." *List* or *box* for list boxes. *Checkbox*: "select" and "clear." *Toggle*: not a verb; describe the action and the target state.
- *Command* for an item in a menu, not "option" or "menu item."
- *Expander arrow*, not zippy or expando.

**Menu paths.** One bold span, angle bracket with spaces: "Select **File > New > Project**." Use only for menu items, not mixed UI elements.

**Buttons.** Refer to a button by its label, no quotes. For an icon button, use the tooltip name and put the icon before the name. Drop trailing ellipses from labels. No slang like "hamburger."

**Keys.** "Press Control+S." Uppercase letter, spelled-out modifiers (Control, Command, Option, Shift), no symbols. Windows and Linux first, macOS in parentheses: "press Control+C (or Command+C on macOS)." Spell out confusing keys: comma, period, plus. "Press" for keys. "Enter" or "type" for text.

**Prepositions.** "In" a dialog, field, list, menu, pane, window. "On" a page, tab, toolbar.

**Verbs.** Click, choose, drag, enter or type, go to, hold the pointer over, press, select, tap, turn on, turn off. Never "click on," "hit," "hover," "check," "uncheck."

## Notices

Four types. Format as a bold label, a colon, then the text.

- **Note:** a useful aside or tip. Not critical.
- **Caution:** proceed carefully.
- **Warning:** don't do this, or the result is irreversible (data loss, security breach).
- **Success:** only in interactive content.

Use a note only when all three are true: the information is relevant but not necessary for the current task; interrupting the reader doesn't hinder them; and the information isn't a continuation, a result, or a pointer. Don't use notes for cross-references, prerequisites, a procedural step, anything the reader needs to succeed, or an expected result. Don't stack notices. If unsure, write it as regular text first and see if it needs the box.

## Link text and cross-references

- Be selective. Each link is a decision and a chance to lose the reader. Define terms and give short steps in place rather than linking out.
- Don't link the same destination twice on a page, with narrow exceptions (very long page, multiple entry points).
- Link text is either the exact page title (title's capitalization) or a short descriptive phrase (sentence capitalization). Important words first. Never a sentence, never a URL, never "this document," "this article," or "click here."
- Don't reuse the same link text for different targets.
- Include the abbreviation inside the link: "Google Kubernetes Engine (GKE)."
- Include the code element's noun inside the link: "the `--hostname` flag."
- Introduce with "see." "For more information, see [title]." "For more information about X, see [title]." Use "about," not "on."
- Say when a link downloads a file (and its type), opens email, goes to the same page, goes to a differently titled section on another page, opens a new tab, or leaves the site. Don't force new tabs.
- Punctuation goes outside the link. No quotation marks around link text.
- Unlinked references: quotation marks for sections and short works, italics for full-length works.

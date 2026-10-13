# Word list

Condensed from developers.google.com/style/word-list. Entries specific to Google Cloud product names are omitted. When a term isn't here, use Merriam-Webster's first spelling and stay consistent within the document.

Format: **term**: guidance.

## A

- **+** (plus sign): OK with numbers in informal text ("300+"), not in formal contexts.
- **&** (ampersand): Don't use for "and" in text or headings. OK when part of a UI label, in a tight table, or in code.
- **a, an**: Choose by the sound that follows, not the letter. "An SAP system," "a SQL query," "a FHIR resource," "a URL," "an HTML file."
- **abnormal**: Not for people. OK for system conditions.
- **abort**: Avoid. Use stop, exit, cancel, or end.
- **about versus on**: "Information about," never "information on."
- **above**: Don't use for versions (use "later"), document position ("earlier," "preceding"), or UI position. OK for hierarchies.
- **access (verb)**: Avoid. Use see, edit, find, use, or view.
- **actionable**: Avoid unless it's the clearest term.
- **admin**: Spell out "administrator" unless matching a UI label.
- **agnostic**: Don't use. Use "platform-independent" or similar.
- **AI**: No need to spell out.
- **aka**: Don't use. Write "also known as," or use "or."
- **allowlist**: Noun only. Don't use as a verb.
- **allows you to**: Don't use. Use "lets you."
- **alpha, beta**: Lowercase unless part of a product name.
- **America, American**: Only for the continents. Use "US" for the United States.
- **AM, PM**: Caps, no periods, one space before: 3 PM.
- **among versus between**: "Between" for distinct items, "among" for groups.
- **and/or**: Avoid. Use "and," "or," or "A, B, or both."
- **and so on**: Avoid. Same as "etc."
- **anti-pattern**: Avoid. Use a specific term.
- **API**: For web or language-specific APIs, not for a single method or class.
- **app**: Prefer over "application" for end-user programs.
- **appendix**: Plural "appendixes."
- **as**: Use "because" for causation. "As" is ambiguous.
- **as of this writing**: Avoid. Implied, and leaks strategy.
- **authentication, authorization**: A user is authenticated. A request is authorized.
- **authN, authZ**: Don't use. Spell out.
- **auto-, autoscaling, autopopulate, autohealing**: Closed, no hyphen.
- **autoupdate**: Don't use. Write "automatically update."
- **-aware**: Avoid as a compound modifier.

## B

- **backend, frontend**: One word.
- **bare metal**: Noun lowercase, two words. Hyphenate as a modifier.
- **below**: Same as "above." Use "following," "later."
- **best effort**: Avoid. Be specific.
- **big-endian, little-endian**: Hyphenate.
- **black-box, white-box, gray-box**: Avoid. Use "opaque-box," "clear-box," or describe the method.
- **blackhat, whitehat**: Don't use. Use "illegal," "unethical," "legal," "ethical."
- **blackhole (verb)**: Don't use. Use "dropped without notification."
- **blacklist, whitelist, graylist**: Don't use. Use "denylist" or "blocklist," "allowlist" or "safelist," "provisional list." Code identifiers stay in code font.
- **blast radius**: Don't use. Use "affected area."
- **blind**: Avoid "blind to," "blind eye." Use person-first language for people.
- **blue-green**: Hyphenated.
- **boolean**: Code font for the type. Lowercase as an abstract term. "Boolean" for the logic system.
- **break-glass**: Don't use. Use "emergency access" or "manual fallback."
- **brown bag**: Don't use. Use "learning session."
- **build cop, build sheriff**: Don't use. Use "build monitor."
- **button**: Don't call a link a button. Press a hardware button. Tap or click a UI button.

## C

- **can**: Permission, ability, optional actions, possible outcomes. The default modal.
- **canary**: Not a verb. Define on first use.
- **careful, carefully**: Avoid. Condescending and vague.
- **cell phone, cellular**: Use "mobile phone," "mobile data," "mobile network."
- **chapter**: Only for books.
- **check (checkbox)**: Don't use. Use "select." The opposite is "clear," not "uncheck" or "deselect."
- **checkbox**: One word.
- **choose**: Fine generically. Use "select" for UI elements.
- **CLI**: Don't use generically. Name the tool.
- **click**: Desktop targets. Never "click on." Use "tap" for touch.
- **click here**: Don't use. See link text guidance.
- **client**: In API docs, short for "client app," not "client library."
- **codebase, codelab**: One word.
- **cold, hot, warm** (failover, standby): Jargon. Define on first use or avoid.
- **colocate**: No hyphen. Not "colo."
- **compliant, compliance**: Use with caution. It's a strong claim.
- **comprise**: Don't use. Use "consist of," "contain," or "include."
- **config**: Spell out "configuration" in prose.
- **cons, pros**: Don't use. Use "disadvantages," "advantages."
- **copy and paste**: Avoid as an instruction. Say what to enter.
- **could**: Avoid. Use "can."
- **CPU**: No expansion needed.
- **crazy, insane, bonkers, mad**: Don't use. "Complicated" or "unexpected," for objects only.
- **Create a new**: Drop "new" unless distinguishing from an existing item.
- **cripple**: Don't use. Use precise language such as "slows."
- **curl**: Lowercase, not "cURL."
- **currently**: Avoid. Implied.

## D

- **dash**: A hyphen isn't a dash. Don't call hyphens dashes.
- **data**: Singular mass noun. "Less data," "the data is."
- **data center, data source, data type**: Two words.
- **datastore**: One word.
- **dead-letter queue**: Define on first use.
- **deficient, deformed**: Not for people.
- **denigrate**: Use "disparage."
- **deprecate**: Means "recommended against," not "removed."
- **desire, desired**: Don't use. Use "want" or "need."
- **dialog**: The UI element. "Dialogue" is only a conversation.
- **directory versus folder**: Match the UI. "Directory" for CLI contexts, "folder" for GUI contexts.
- **disable**: Not for something broken. Use "unavailable," "inactive," or "turn off."
- **display (verb)**: Transitive only. "The console displays the result," not "the result displays."
- **DMZ**: Use "perimeter network."
- **documentation, document**: "This document." Spell out "documentation."
- **does not yet**: Avoid in timeless writing.
- **dojo**: Don't use. Use "training" or "workshop."
- **double-tap**: Hyphenated.
- **drag**: Not "click and drag" or "drag and drop" as a verb. "Drag-and-drop" OK as an adjective.
- **drop-down**: Usually omit. Use "menu" or "list." Never a standalone noun.
- **dumb down**: Don't use. Use "simplify."
- **dummy variable**: Don't use. Use "placeholder."

## E

- **each**: Not a synonym for "all."
- **earlier, later**: For version ranges and document position. Not "lower," "higher," "above," "below."
- **easy, easily**: Remove. Subjective.
- **ecommerce**: No hyphen.
- **e.g.**: Don't use. "For example" or "such as."
- **either**: Best for exactly two choices. Keep syntax parallel.
- **element versus tag**: Not interchangeable. The element includes its content.
- **email**: Not "e-mail." Not a verb.
- **emoji**: Singular and plural.
- **enable**: Match the UI label. Use "lets you" for capability, not "enables you to."
- **endpoint**: One word.
- **enter**: Typed text. Say explicitly if the reader shouldn't press Enter.
- **error-prone**: Hyphenated.
- **etc.**: Avoid. If needed, include the period. Never with "and so on" or after "such as."
- **eventually**: Avoid in timeless writing.
- **execute**: Use "run" when the meaning is the same.
- **expander arrow**: Not "zippy" or "expando."
- **exploit**: Only the negative security sense.
- **extract**: Not unzip, untar, uncompress, or unarchive.

## F

- **fat**: Don't use. Use a precise modifier.
- **female adapter, male adapter**: Don't use. "Socket," "plug."
- **filename**: One word. **file system**: Two words.
- **fill in, fill out**: Fill in a field. Fill out a form.
- **final solution**: Don't use.
- **fintech, ad tech**: Spell out on first use.
- **first class, first-class citizen**: Don't use. Use a precise term.
- **foo, bar, baz**: Avoid. Use a meaningful placeholder.
- **for example**: Follow with a comma. Don't pair with "etc."
- **for instance**: Don't use. "For example," "like," or "such as."
- **functionality**: Use with caution. Usually "features" or "capabilities."
- **future, in the future**: Avoid in timeless writing.

## G

- **GB, GiB, MB, MiB**: No expansion needed. **Gbps, GBps**: Not "Gb/s."
- **gender-neutral pronouns**: Singular "they."
- **generative AI**: Spelled out, sentence case. Not "gen AI."
- **ghetto**: Don't use. "Workaround," "inelegant."
- **gimp, gimpy**: Don't use.
- **Google (verb)**: Don't use. "Search with Google."
- **grandfathered**: Don't use. "Legacy," "exempt," "made an exception for."
- **grayed-out**: Don't use. "Unavailable."
- **guru, ninja, sherpa, wizard**: Don't use for people. "Expert," "guide."
- **guys, you guys**: Don't use. "Everyone," "folks."
- **gypsy**: Don't use.

## H

- **hamburger menu, kebab menu**: Don't use. Use the control's label or `aria-label`.
- **hands-off, hands-on**: Avoid. Describe the process.
- **hang, hung**: Don't use. "Stops responding."
- **hardcode**: One word.
- **he, him, his, she, her**: Only for a known individual. Otherwise "they."
- **healthcare**: One word.
- **health check, healthy**: Use with caution. Prefer literal language.
- **high availability**: Noun unhyphenated. Adjective hyphenated. "HA" after first use.
- **higher, lower**: Not for versions. Use "later," "earlier."
- **hit**: Don't use for click, press, or type.
- **hold the pointer over**: Use when the UI reacts after a wait. Not "hover."
- **holiday, the holidays**: Don't use for end of year. Name the months.
- **hostname**: One word.
- **hotspot**: Noun only. Define on first use.
- **housekeeping**: Don't use. "Maintenance," "cleanup."
- **hover**: Don't use. "Hold the pointer over."
- **HTTPS**: Not "HTTPs."

## I

- **IaaS, PaaS, SaaS**: Spell out on first use.
- **ID**: Not "Id" or "id" except in code.
- **i.e.**: Don't use. "That is."
- **if**: Include "then" in if-then statements. See "whether."
- **impact**: Noun only. Use "affect" as the verb.
- **index**: Plural "indexes" unless the domain requires "indices."
- **ingest**: Only when significant processing occurs. Otherwise "import," "load."
- **in order to**: Avoid. "To."
- **inline**: One word.
- **interface**: Noun only. Not a verb.
- **internet, web**: Lowercase.
- **I/O**: Not "IO."
- **IoT**: Lowercase "o."
- **IPsec**: Not "IPSec."

## J-K

- **jank, janky**: Only for graphics glitches.
- **just**: Usually delete. If needed, "only," "instead," or "previously."
- **k8s**: Don't use. "Kubernetes."
- **kebab case, camel case, snake case**: Don't name the style. State the rule and give an example.
- **key**: Don't use as an adjective meaning "crucial."
- **key-value pair**: Hyphenated.
- **kill**: Avoid. "Stop," "exit," "cancel," "end."

## L

- **lame**: Don't use.
- **latest**: Avoid in timeless writing. Give a version.
- **learnings**: Don't use. "Knowledge," "lessons."
- **left-nav, right-nav**: Avoid directional language.
- **legacy**: Define if used. Not as a pejorative.
- **let's**: Don't use.
- **leverage**: Don't use. "Use," "build on," "take advantage of."
- **lifecycle**: One word.
- **like**: OK for comparisons and examples.
- **load balancing**: Noun unhyphenated. Adjective hyphenated.
- **login, log in**: Prefer "sign in" (verb), "sign-in" (noun or adjective).
- **long-running**: Hyphenated.

## M

- **man-hours, manned, manpower, manmade, mankind**: Don't use. "Person-hours," "staffed," "workforce," "artificial," "humanity."
- **man-in-the-middle**: Use "on-path attacker" or "person-in-the-middle."
- **Markdown**: Capitalized.
- **master**: Use with caution. Never with "slave." Use "primary," "main," "parent."
- **matrix**: Plural "matrixes" unless the domain requires "matrices."
- **may**: Policy or legal only. Otherwise "can" or "might."
- **media type**: Not "MIME type." "Content type" only for the header.
- **method**: In programming contexts, means a class method, not an approach.
- **microservices**: Lowercase, one word.
- **might**: Possibility or uncertain outcome.
- **mobile**: Not a standalone noun. "Mobile device," "mobile phone."
- **mom test**: Don't use. "Beginner user test."
- **monkey test**: Don't use for people. Describe the test.
- **multi-**: Closed except "multi-cluster," "multi-region," "multi-service," "multi-tenancy."
- **must**: Required actions. Or "you need to."

## N

- **N/A**: Spell out "not applicable" or "not available."
- **name server, web server**: Two words.
- **namespace**: One word.
- **native**: Not for people. Use "built-in" for products.
- **navigation bar**: Don't use for a navigation menu.
- **neither**: "Neither A nor B."
- **new, newer**: Avoid in timeless writing. "Later" with a version.
- **ninja**: See guru.
- **nonce**: Define.
- **NoOps**: Don't use. "Fully managed."
- **NoSQL**: One word.
- **now**: Avoid when describing features.
- **nuke**: Don't use. "Remove."

## O

- **OAuth 2.0**: Not "OAuth2."
- **off-the-shelf**: "Ready-made," "prebuilt," "standard."
- **old, older**: "Earlier" with a version.
- **omnibox**: "Address bar."
- **once**: Means "one time." Use "after" for time.
- **on-premises**: Always hyphenated. Not "on prem," "on premise."
- **OS**: No expansion needed.
- **out of the box**: Avoid figurative use.

## P

- **page**: Web pages and console subpages.
- **path**: Not "filepath," "file path," "pathname."
- **per**: For rates only. Not a slash.
- **performant**: Avoid. Be precise.
- **persist (verb)**: Avoid, especially passive.
- **PII**: "Personally identifiable information."
- **pets versus cattle**: Don't use. "Persistent versus dynamic."
- **plain text**: Two words. "Plaintext" only in cryptography.
- **please**: Not in instructions. Only to ask permission or forgiveness.
- **plugin, plug-in, plug in**: Noun, adjective, verb.
- **point to**: Pointing without waiting for the UI.
- **pop-up, popup**: Don't use. "Dialog," "menu."
- **populate**: OK for tables. "Fill in" for people.
- **port**: "Listen on," not "listen to."
- **possible**: Don't use to mean "can" or "can't."
- **postmortem**: "Retrospective." "Blameless postmortem" is OK in SRE contexts.
- **pre-**: Closed ("prebuilt," "prerecorded," "presubmit") except "pre-existing," "pre-shared key."
- **preferred pronouns**: Say "pronouns."
- **presently, at present**: Avoid.
- **press**: Keys and hardware buttons. "Tap" for on-screen buttons.
- **primitive**: Never disparagingly.
- **proper, properly**: Avoid. Describe the check.

## Q-R

- **quick, quickly**: Remove.
- **quota**: Be specific about what kind of limit.
- **RDP, SSH**: Not verbs. "Connect using SSH."
- **read-only**: Always hyphenated.
- **regex**: "Regular expression."
- **repo**: "Repository."
- **REST**: Don't expand.
- **retard**: Don't use. "Slow."
- **review**: Critical reading. "Read" for first-time reading.
- **RFC**: Space before the number: RFC 5737.
- **roll out**: Not for a sudden launch. Define or use "gradual."
- **RTFM**: Don't use.
- **runbook**: One word.
- **runtime, run time**: "Runtime" for the environment. "Run time" for when execution happens.

## S

- **sane, sanity check**: Don't use. "Valid," "sensible," "quick check," "final check."
- **scale**: Add direction or magnitude: "scale up," "scale out."
- **screenshot**: One word. Not a verb.
- **scroll**: OK, but avoid "scroll up" or "scroll down."
- **see**: OK for links and cross-references.
- **select**: Choosing items, selecting text, marking checkboxes.
- **setup, set up**: Noun or adjective, verb.
- **sexy**: Don't use. "Fast," "powerful," "elegant."
- **SHA-1, SHA-256**: Hyphenated except in code.
- **shall**: Avoid.
- **shift left**: Avoid for timing. OK for bit math.
- **should**: Generally avoid. Say what's required or recommended.
- **sign in, sign-in, sign out, sign-out**: Verb, noun or adjective. Not "log in," "login."
- **sign into**: Don't use. "Sign in to."
- **simple, simply**: Remove.
- **since**: Use "because" for causation.
- **single pane of glass**: Don't use. "Single interface."
- **slave**: Don't use. "Worker," "replica," "secondary."
- **slice and dice**: Don't use.
- **smartphone**: "Mobile phone," "phone."
- **soon**: Avoid in timeless writing.
- **spin up**: Avoid. "Create," "start."
- **SQL**: "A SQL."
- **startup, start up**: Noun or adjective, verb.
- **status bar**: Two words.
- **STONITH**: Avoid. Describe the action.
- **sub-command**: Hyphenated. **subtree, subzone**: Closed.
- **such as**: For examples. Not with "etc."
- **surface (verb)**: Avoid. "Expose," "show," "make visible."

## T

- **tab**: "The **Label** tab."
- **tap**: Touch screens. Not "touch" or "click."
- **tarball**: "Tar file."
- **target (verb)**: Avoid, especially for people.
- **terminate**: Not a synonym for "stop."
- **text box, textbox**: Don't use. "Box" or "field."
- **then**: Include in if-then statements.
- **they (singular)**: Preferred gender-neutral pronoun. Takes a plural verb.
- **third party, third-party**: Noun, adjective. Not "3rd party."
- **this, that**: Add a noun. "This value," not "this."
- **timeframe**: Avoid. "Period," "schedule."
- **timeout, time out**: Noun, verb.
- **timestamp**: One word.
- **time zone**: Noun two words. Adjective hyphenated.
- **tl;dr**: Don't use. "To summarize."
- **toolkit, touchscreen, walkthrough, whitespace, wildcard, workaround**: One word.
- **touch & hold**: Android term. Not "touch and hold," "long press."
- **traditional**: Use a more precise term.
- **tribal knowledge**: Don't use. "Undocumented knowledge."
- **turn on, turn off**: Match the UI label. Consistent with "enable" within a document.
- **type**: Usually "enter."
- **typically**: Fine for normal circumstances. Not as a sentence opener.

## U

- **UI**: Not for a page or dashboard. "Page," "console," "web interface."
- **uncheck, unselect, deselect**: Don't use. "Clear."
- **unzip, untar, uncompress, unarchive**: "Extract."
- **under**: Not for version ranges or UI position.
- **Unicode**: Not "UNICODE."
- **Unix-like**: Hyphenated.
- **US**: Not "U.S." or "U.S.A."
- **user**: Only for users of the software being built. Otherwise "you."
- **user base**: Two words.
- **using**: Ambiguous. "By using," "that uses," or rewrite.
- **UTF-8**: Keep the hyphen.
- **utilize**: "Use." "Utilization" is fine for a measured quantity.

## V-Z

- **v (version)**: Lowercase, no space: v1.2. Or "version 1.2."
- **via**: Don't use. "By using," "through," "by way of."
- **vice versa**: Don't use. State the relationship.
- **voila**: Don't use.
- **voodoo**: Don't use. "Mysterious," "nondeterministic."
- **vs.**: "Versus."
- **wake lock, wake-lock**: Noun, adjective.
- **war room**: Don't use. Name the team or activity.
- **we**: Not for the reader. OK for the authoring organization after naming it.
- **webmaster**: Name the role.
- **whether**: "Whether" for alternatives, "if" for conditions. Drop "or not" unless it's needed for sense.
- **while**: Time only. Use "although" for contrast.
- **white glove**: "High-touch," "premium."
- **white label**: "Unbranded."
- **whitepaper**: One word. Prefer a precise term.
- **will**: Avoid. Same for "would."
- **wish**: "Want," "need."
- **with**: Not for ownership ("a VM with 4 cores" is fine, "a project with a bucket" is ambiguous) or for means ("by using").
- **workload**: Define or use a precise term.
- **World Wide Web**: "The web."
- **ymmv**: "Your results might vary."
- **you**: Use instead of "the user."

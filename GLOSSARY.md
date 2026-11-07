# Glossary

**Digest**
The grouped, summarized view of a set of emails, produced by one Run. The thing the user reads instead of their inbox. Each Run's Digest is a fresh view: it reflects the inbox as it is now, not what earlier Runs showed.
_Avoid_: report, summary (a Summary is per-email)

**Run**
One execution that selects Candidate threads, summarizes them and produces a Digest. Started on demand or by a schedule. A Run never changes the mailbox.

**Candidate thread**
A conversation a Run includes: it has unread messages, is in the inbox, and had activity within the Lookback window. The thread, not the individual message, is the unit a Digest shows: one entry per thread.
_Avoid_: candidate email (a thread may hold several messages)

**Lookback window**
How far back a Run looks for emails. Currently the last 7 days.

**Category**
What kind of email something is, judged by sender and subject matter. Every Candidate thread belongs to exactly one Category. Categories come from a configurable, ordered list; threads that fit none go in Other.
_Avoid_: using "Needs action" as a Category (see Action item)

**Subgroup**
A named group inside a Category, usually one sending organization (Lincoln Elementary, Soccer Club). Either configured, pinned by the user with sender rules, or a Discovered subgroup.

**Discovered subgroup**
A Subgroup a Run creates on its own, inside a Category that is open to them, for an organization with no configured Subgroup. It lasts only for that Run's Digest; the user makes it permanent by configuring it.

**Suggested category**
A proposal at the end of a Digest for a new Category, made when several threads from one organization fit no Category. Only the user turns a Suggested category into a real one.

**Action item**
Something the user needs to do, extracted from an email, optionally with a deadline. An email has zero or more. Action items are listed together at the top of a Digest, independent of Category.

**Followed link**
A link in an email that a Run opens to read the page behind it, because the email itself is mostly a pointer. Only links straight to an allowed domain that read content (never ones that act, like unsubscribe or RSVP). What the page says is folded into that email's Summary and Action items.
_Avoid_: clicking (a Followed link is read, never acted on)

**Summary**
The short, per-email condensation shown inside a Digest. Its length depends on the email's Category.

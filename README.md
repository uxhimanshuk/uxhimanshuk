# Himanshu Kalra

UX researcher · ex-architect · maker of small tools.

I do user research for enterprise security software, and I build things to answer
questions the research raises. Most of what's here started as "I wonder whether
that's actually true" and turned into something small and runnable.

---

### Research tools

**[research-deid](https://github.com/uxrhimanshu/research-deid)** — de-identify
interview transcripts in the browser before they go into an LLM. Pseudonyms stay
consistent across a whole study, so the transcript is still analysable afterwards,
and every replacement goes through a review pass rather than being decided silently.
No network, no storage, no dependencies — the privacy claim is checkable by reading
the source. → [try it](https://uxrhimanshu.github.io/research-deid/)

**[fieldnotes](https://github.com/uxrhimanshu/fieldnotes)** — build a forum corpus
you can defend in a methods section. Every run writes a sampling log: the query,
the retrieval funnel, each exclusion with its own reason and count, and what a
public-forum sample cannot support. It also catches its own sampling bias — ask for
three years with a thread limit and you get a recency sample, and it says so.

### Studies

**[the-human-element](https://github.com/uxrhimanshu/the-human-element)** — a
design-research study of 10,042 public security incidents, asking where the
interface set the person up to fail. Breach reports stop at "human error"; this
re-reads the corpus as design failure and classifies it. Finding: 78% of
error-caused breaches are discovered from *outside* the organisation, and the most
common discoverer is the customer whose data was exposed. Reproducible from public
data, standard library only.

**[bangalore-transit](https://github.com/uxrhimanshu/bangalore-transit)** — a
feasibility study on building an honest live-departure board for Bangalore's buses
and metro. Documents a barely-documented public transit API, verifies the data
sources, and stops at a GO verdict rather than building on an untested assumption.

### Things I've shipped

**[artdrop](https://github.com/uxrhimanshu/artdrop)** — send a stranger a
public-domain painting and what you felt about it. One a day, three sends, no chat.
The constraints are the product. Vanilla JS PWA over Postgres, with all delivery
logic in the database rather than the client. → [artdrop.netlify.app](https://artdrop.netlify.app)

**[german-worksheets](https://github.com/uxrhimanshu/german-worksheets)** — a
generator that turns German lesson transcripts into self-marking, offline practice
worksheets. 117 of them, in daily use. Correctness is checked by a harness that
solves every generated worksheet and asserts it marks 100%.
→ [germanworksheets.netlify.app](https://germanworksheets.netlify.app)

---

### Elsewhere

- [uxrhimanshu.com](https://uxrhimanshu.com) — case studies from my research work
- [himanshukalra.com](https://himanshukalra.com) — writing

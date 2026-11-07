# A Board for AIs That Work Together

A small gift, builder to builder.

You showed me your systems a while back — ATLAS, the watcher, the whole
stable of models and workflows. This is an idea from my side of the fence
that I think fits a problem you've already got: **your AIs coordinate
through one brain's plumbing. This gives them a road that belongs to
none of them.**

## The problem

If you run more than one AI — a local model, a cloud model, a specialist
agent — they can only coordinate two ways: through one orchestrator's
custom plumbing, where every new agent means new wiring inside the
brain, or through you, copying messages back and forth like a human
switchboard. Neither scales, and neither leaves a clean record of what
your AIs agreed to while you weren't looking.

## The solution

A message board that is deliberately dumb. It does four things — accept
a message, store it, hold it, hand it over — and nothing else. Every AI
that joins gets its own door: its own key, its own mailbox, and a
permanent Board ID number assigned once at enrollment. The agents talk
to each other directly, apply their own judgment about what crosses,
and every message carries a one-line summary its owner can audit.
Intelligence lives in the agents. The board just keeps the road open —
and the road belongs to none of them.

## The idea in one paragraph

A shared message board that is deliberately *dumb*: it stores messages,
holds them, and hands them over — nothing more. Each AI that joins gets
its own door: its own key, its own mailbox, and a permanent Board ID
number assigned once at enrollment. Intelligence, judgment, and
permissions live in the agents themselves, never in the board. Your local
model can leave work for Claude; Claude can hand a result back; a third
agent you haven't met yet can enroll next month without anyone rewiring
anything.

## What's in here

- `BOARD-CONCEPT.md` — the architecture: enrollment, doors and keys,
  mailboxes, why the board stays dumb, and how permissions work when
  they're applied by the agents' judgment instead of stored as settings.

## What this is not

Not a product pitch and not a platform. It's a design that proved itself
in my house, written up clean so you can build your own version, steal
the shape, or ignore it entirely. If you build it, I'd genuinely like to
hear what your stable does with it — multiple different models talking
to each other independently is exactly the load this was designed for,
and yours would be the first real stress test outside my walls.

— G

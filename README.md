# Freelancer Document Pack (Claude Skill)

Tell Claude about your project. Claude asks a few quick questions, then creates every document you need to work with a client, written specifically for you.

No more copy-pasting old templates. No more blank pages.

## What you get

Six documents, **one page each**:

| # | Document | What it is for |
|---|----------|----------------|
| 1 | Discovery Call Guide | Questions to ask on your first call |
| 2 | Proposal | Scope, deliverables, timeline, price |
| 3 | Onboarding Guide | What happens next, what you need from the client |
| 4 | Non-Disclosure Agreement | Protects both sides |
| 5 | Invoice | Clear amounts and payment details |
| 6 | Offboarding Guide | A clean finish and handover |

## Preview

See the example pack here: [`examples/freelancer-documents-master-pack.pdf`](examples/freelancer-documents-master-pack.pdf)

> The example uses placeholder names. Your pack will use your real project details.

## How to use it

1. **Download** `freelancer-document-pack.zip` from the [Releases](../../releases) page (or from this repo).
2. **Add it to Claude.** Upload the zip in Claude's skills settings.
3. **Start a chat** and say: `Make my freelancer document pack`.
4. **Answer the questions.** Claude asks about you, your client, the project, the price, and the process.
5. **Review and send.** Claude builds the six documents. Check names, prices, dates, and the NDA jurisdiction before you send them.

## What Claude will ask you

- Your name or business, service, email, and phone
- Your client's name, company, and email
- The project, deliverables, and timeline
- Price, deposit, and payment details
- Revisions, feedback time, communication channels, working hours
- NDA jurisdiction

You can say "you decide" for anything, and Claude will pick a sensible default.

## Output formats

- **Canva** (best result, one page per document) if Canva is connected to Claude
- **Word (.docx)** or **PDF** if you ask for them
- A shareable Claude document if neither is available

## Good to know

- Claude never invents prices, bank details, or legal details. Anything unknown stays as a clear `[Placeholder]`.
- The NDA is a **standard template, not legal advice**. For high-value or cross-border work, ask a lawyer to review it.
- Your client details stay inside your conversation.

## Repo structure

```
freelancer-document-pack/
├── README.md
├── LICENSE
├── freelancer-document-pack/
│   └── SKILL.md                # the skill itself
├── freelancer-document-pack.zip # ready to upload
└── examples/
    └── freelancer-documents-master-pack.pdf
```

## Customize it

Open `freelancer-document-pack/SKILL.md` and edit it. You can change:

- The questions Claude asks
- The default deposit split (now 50/50)
- The default NDA duration (now project + 1 year)
- The tone and the document structure

## Contributing

Ideas and improvements are welcome. Open an issue or send a pull request.

## License

MIT. See [LICENSE](LICENSE).

## Author

Built by Bavly Albeir Magdy.

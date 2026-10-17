---
name: freelancer-document-pack
description: Interview a freelancer or agency about their client project, then generate a personalized 6-document pack (Discovery Call, Proposal, Onboarding, NDA, Invoice, Offboarding), one page each.
---

# Freelancer Document Pack

Turn a short interview about a freelancer's project into six professional, ready-to-send documents. Each document fits on exactly ONE page.

## The six documents
1. Client Discovery Call Guide
2. Project Proposal
3. Client Onboarding Guide
4. Non-Disclosure Agreement
5. Invoice
6. Client Offboarding Guide

## Step 1: Intake interview
Start with one sentence saying you will ask a few questions and then build their pack. Ask the questions in ONE batch (use AskUserQuestion for multiple-choice items, plain text for the rest). Never ask one question per turn. If the person has already answered something, do not ask it again. If they say "you decide", pick a sensible default and list it in the summary.

Collect:
- **You:** name or business name, service type (e.g. data analysis, video editing, design, writing), email, phone/WhatsApp, country/city
- **Client:** client name, client company, client email
- **Project:** what the work is, main deliverables, whether it is one-off or monthly/retainer, start date, expected duration
- **Money:** price or package name, currency, deposit split (default 50/50), invoice number, payment method and details (bank, account, UPI/PayPal etc.), tax if any
- **Process:** number of included revisions, feedback turnaround, communication channels, working hours and time zone
- **Legal:** governing-law jurisdiction for the NDA, confidentiality duration (default: project + 1 year)
- **Preferences:** tone (formal, friendly-professional), language (default English), brand colours or logo if they have them

## Step 2: Confirm
Before building, reply with a compact summary of what you will use, marking any defaults you chose. Ask for corrections only if something critical is missing (client name, deliverables, price). Otherwise proceed.

## Step 3: Write the content
Use the structure below, rewriting every line for THEIR project (real names, real deliverables, real prices, real dates). Professional, concise, plain language. No filler. Anything unknown stays as a clear [Bracketed Placeholder], never invented.

1. **Discovery Call Guide:** meta (duration, tone), fields (client, prepared by, date), opening script, then question groups tailored to their service: Background, Current Situation, Goals and Vision, Style/Preferences, Process and Expectations, Budget and Scope Fit, closing script.
2. **Proposal:** fields, Overview, Objectives, Scope of Work, Deliverables, Process (numbered), Timelines, Investment, Payment Terms.
3. **Onboarding Guide:** fields, Welcome, What Happens Next, What We Need From You, How We Communicate, Weekly Workflow, Revisions, Payments, Response Time, Content/Work Ownership.
4. **NDA:** effective date, parties, Purpose, Definition of Confidential Information, Obligations, Exclusions, Ownership, Duration, Termination, Dispute Resolution, signature block (name, signature, date for both parties).
5. **Invoice:** number, dates, From, Billed To, line-item table with amounts, subtotal, tax, total due, payment details, terms, thank-you line. Do the arithmetic and check it.
6. **Offboarding Guide:** fields, Thank You, What You Will Receive, Access and Ownership, Outstanding Payments, Timeline, Feedback questions, Permissions (portfolio use, optional), Support After Offboarding, Contact.

## Step 4: Build with ONE PAGE per document
- Preferred output: if a Canva connector is available, use create-design with an A4 portrait format, exactly 6 pages, no cover page, one document per page, consistent running header, navy/slate palette (or the person's brand colours), one sans-serif font. If they asked for Word or PDF, use the docx or pdf skill instead. If neither fits, use the Docs artifact.
- Hard rule: no document may spill past its page. If content is too long, shorten wording or reduce spacing first, then cut the least important lines. Never reduce body text below a readable size.
- After building, check every page for overflow and typos. Fix before sharing.

## Step 5: Deliver
Give the person the link or file plus 1-2 sentences on what to review first (usually names, prices, dates, jurisdiction). Offer one next step, such as translating the pack or adjusting tone.

## Rules
- Never invent facts, prices, bank details, or legal jurisdictions. Use placeholders.
- Never store card numbers, bank account numbers, or ID numbers in memory.
- The NDA is a standard template, not legal advice. Say so in one line and recommend a lawyer review for high-value or cross-border work.
- Keep client information private to this conversation.
- Match the person's language when they write in another one; keep documents in the language they request.

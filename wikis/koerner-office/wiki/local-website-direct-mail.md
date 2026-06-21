# Local Website Direct Mail

Local website direct mail is a high-friction acquisition play where an operator builds a simple demo website for a local business, mails a QR-coded postcard pointing to that exact demo, then follows up by phone. In the Koerner Office example, AI reduces the cost of research and website generation, while physical mail and calling create trust signals that mass cold email lacks.

## Pattern

The play combines four components:

- local-business prospecting from public listings
- AI-assisted demo-site creation
- physical postcard or other offline artifact with a QR code
- human sales follow-up, prioritized by scan intent

It belongs with [[local-home-service-businesses]] and [[home-service-ai-lead-capture]] because the first strong example targets home-service-style companies, and with [[ai-agent-operated-businesses]] because an agent performs much of the list-building and site generation.

## Example workflow

From `episodes/2026-05-30-i-told-an-ai-agent-to-make-me-money-it-did.md`:

1. Use an AI agent to find hundreds of local businesses in a chosen geography.
2. Pull business names, phone numbers, emails, owner/contact names where available, and public profile data.
3. Generate lightweight demo websites on test URLs rather than buying custom domains up front.
4. Keep model/token costs low for mass generation.
5. Use a direct-mail API such as Lob to mail individualized postcards.
6. Put a QR code on each postcard that opens the prospect's demo site.
7. Watch scan analytics and prioritize calls to scanners.
8. Offer the website for free if the owner hires the agency for ongoing marketing or lead generation.

## Reported economics from the source episode

- 350 local businesses targeted.
- 341 postcards reportedly delivered.
- 68 people reportedly scanned.
- Campaign reportedly produced a little over $8k MRR.
- Guest estimated roughly 17-20 customers, about $400/month average, with some up to about $1,200/month.
- Postcards cost a little over $1 each; token costs were described as roughly $10-$20 total.

Treat these as guest-reported figures, not independently verified benchmarks.

## Why it may work

- The prospect sees work already done for their business.
- Physical mail costs money and effort, which can signal seriousness.
- QR scans create intent data for sales prioritization.
- Phone calls turn the postcard from passive marketing into a warm follow-up.
- Multiple difficult actions compound: build the site, mail the card, and make the call.

## Risks and caveats

- Public-data scraping and outreach must follow platform terms and applicable law.
- Phone, email, SMS, and retargeting rules vary by jurisdiction.
- Demo sites should not impersonate, publish misleading claims, or imply ownership by the prospect.
- Operators should track which prospects had existing websites, which scanned, and which closed.
- Quality control matters: a bad demo can damage credibility.

## Sources

- `episodes/2026-05-30-i-told-an-ai-agent-to-make-me-money-it-did.md`

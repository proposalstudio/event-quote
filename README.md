# Event Quote

If you write quotes, this is for you. Tell your assistant the job. Get a priced quote with your name on top, ready to send.

Event Quote is a connector for anyone who writes quotes for their work: contractors, cleaners, landscapers, photographers, caterers, consultants, event pros, any service business. By Proposal Studio.

## What it does

Once connected, your assistant can:

- Set up your account from chat: business details, payment instructions, how many days an invoice is due, and (Pro) your logo from a link or from your phone. It walks you through what is missing, one item at a time
- Save your prices (each, per person, per table, per hour, per mile; taxed or not)
- Take items off your price list and put them back, after your clear yes
- Make a price sheet with a share link for customers, property managers, planners or anyone who asks
- Quote a job or an event with a link you send to your customer. Each quote has its own number, like Q-0001, and the date you made it
- Give a quote a discount: a percent or a dollar amount off your items, shown before tax
- Make an invoice (Pro) from a quote, or in one step from just the client and items (it saves the quote too): the full amount, a deposit, or what is left. Your own payment instructions are printed on it
- Find your earlier quotes (by client, date or quote number) and invoices, see what is paid and what is still owed, and record a payment (all or part, like a 50% deposit) when the money comes in, after your clear yes
- Turn a quote, price sheet or invoice link off and back on, after your clear yes

Your name is on top. Pick a look: 25 in all. 4 are free (Card Stock, Grid Signal, Workbench, Editorial Olive) and 21 come with Pro. The look is for your whole account, so changing it also changes links you already sent. You can also pick a header style (4, all free) and a title word (Quote, Proposal, Estimate, your own word, or none). With Pro, you can pick a font pair too.

A quote stays with its client. Your assistant can fix a typo in the name. A different person gets a new quote, so the first client's link keeps showing their own quote.

It never sends or charges anything, and it never deletes your quotes, price sheets, invoices or account. You send the link. It can record or remove payments on an invoice, turn a quote, price sheet or invoice link off and on, and take items off your price list, but only after your clear yes. Deleting a quote, price sheet, invoice or your account is done by you on your signed-in account page. No card payments happen in Event Quote.

## Connect

Server address:

```
https://quote.proposalstudio.app/mcp
```

1. Add the server in your assistant (Grok Bot, ChatGPT, Claude, Cursor).
2. Choose "Sign in with Google". That creates your free account.
3. Say: "Here are my prices: ..." and then "Quote the Martinez job."

Or use `mcp.json` in this repo:

```json
{ "mcpServers": { "event-quote": { "type": "http", "url": "https://quote.proposalstudio.app/mcp" } } }
```

## Skills in this repo

- `quote-an-event`: how to quote a job or event well. Check the account, use the price list, ask for the date, read it back, never invent a price
- `build-a-price-list`: how to turn messy prices into a clean saved list

## Plans

- **Free:** 3 quotes a month, up to 300 price-list items and up to 3 price sheets. 4 looks. No photos or invoices. A small "Made with Event Quote" mark on links.
- **Pro, $9 a month:** unlimited quotes (fair-use limit of 500 a month). Up to 2,000 items and unlimited price sheets. All 25 looks, invoices and font pairs. One photo per item on your price sheets and quotes. Your logo, in the size you pick. No mark.

These limits can change. Your assistant can tell you your current limit.

Upgrade on https://quote.proposalstudio.app. The connector is free to install.

## Privacy

We store your Google name and email, your business details, your prices, your quotes and your photos, so the connector can work. Photos are shrunk and stripped of location data when uploaded. We do not sell your data. We do not train AI on it. Your clients' contact details are never shown on the links you share. You can delete a quote, a price sheet, an invoice or your whole account on your signed-in account page. Deleting your account cancels any Pro subscription and removes your prices, sheets, quotes, invoices and photos. Stripe, the payment company, keeps its own customer record (name and email) for its records. Full policy: https://quote.proposalstudio.app/privacy. Terms: https://quote.proposalstudio.app/terms.

## Support

support@proposalstudio.app

## License

MIT. See `LICENSE`.

# Privacy Policy

*Screener Smart Research, version 2.3.0 · Last updated 7 October 2026*

> The extension collects nothing. It has no server, no account, no analytics and no advertising. Everything it computes is computed in your browser from the Screener page you are viewing, and nothing is sent to its author or to any third party. Contributions are optional and are paid outside the extension, in your own UPI app.

## What the extension does

Screener Smart Research runs only on company pages of `https://www.screener.in/company/`. When you ask for it, it reads the financial tables on the page you have open and shows ratios, screens and charts calculated from them, inside that page.

## Information it collects

None. The extension does not collect, transmit, sell or share personal information, browsing history, the companies you look at, or anything you type. Its author receives no data from it of any kind.

## Requests it makes

The extension talks to one website only: Screener itself, the site you are already on. It makes these requests only when you open a view that needs them, with your existing Screener session, exactly as the page could:

- the company pages of the peers Screener lists (or that you add), for the Peers tab and relative valuation;
- Screener's own data endpoints for price and valuation history, for the Valuation tab;
- Screener's own data endpoint for daily closing prices, one request per calendar year, for the Monthly Returns tab;
- Screener's company search, when you search for a peer to add.

It contacts no other server. Requests are paced, cached and capped so the extension does not burden Screener. These requests carry nothing about you beyond what your browser already sends to Screener on every page you open there; the extension adds no identifier, tracker or data of its own.

## What it stores, and where

What you write in the Notes & Checklist tab is kept in the extension's own storage on your device (`chrome.storage.local`, the `storage` permission), where the site's scripts cannot read or clear it:

| Stored item | What it holds | Kept for |
| --- | --- | --- |
| `notes:…` | Your note on a company, with the company's name and page address, and when you last changed it. | Until you delete it |
| `checks:…` | Which checklist items you have ticked for a company. | Until you untick or delete them |
| `checklist:…` | Your edits to a checklist template: changed ranges, removed items, items you added. | Until you restore the template |

Settings › Stored data has a button that deletes all of it at once; uninstalling the extension removes it too. It is never sent anywhere and the author cannot see it.

The extension also keeps a few items in your browser's storage for the screener.in site, on your device only:

| Stored item | What it holds | Kept for |
| --- | --- | --- |
| `ssr-prefs` | Your settings: shown tabs and their order, the tab that opens first, colours, shortcuts. | Until you change or reset them |
| `ssr-peers:…` | The peer set you chose for a company, if you changed it. | Until you restore the default |
| `ssr-cache:…` | Peer and market figures already fetched from Screener, so they are not requested again. Public market data only, nothing about you. | Up to 24 hours; month-end prices of finished years up to 30 days |
| `ssr-http:…` | Counters that pace and cap the extension's requests to Screener. | Up to a day |
| `ssr-debug` | A diagnostic switch, present only if you set it yourself. | Until you remove it |

These items never leave your device. You can remove the cache from the extension's Settings, and all of them by clearing site data for screener.in or uninstalling the extension.

## Files it creates

The Export button writes an Excel workbook in your browser and saves it through your browser's normal download. The file is not uploaded anywhere, and once saved it is yours to keep, share or delete; the author has no access to it. Each workbook carries a line naming the extension, and its cover names the author with links to the author's public profiles. Those cells are protected against accidental editing; this is a convenience, not a security measure, and the rest of the workbook is yours to edit.

## Contributions

While the analysis is open, a coffee button opens an optional contribution dialog showing the author's UPI ID, a UPI QR code and links to the author's LinkedIn and X profiles.

- **Voluntary gift.** A contribution is a voluntary, unconditional gift towards the author's independent work. It is not a purchase, a subscription, a donation to a charity or a fee for any product, service, feature, support or advice. It creates no contract, account, membership or relationship of any kind, including any adviser–client or research relationship, and it entitles you to nothing: the extension and every feature in it stay the same, and free, for everyone.
- **Made in your own app.** Any payment is initiated, authorised and completed by you, in the UPI app of your choice, and is processed by your bank, the author's bank and the UPI network under their own terms. The extension does not process, see, handle, store or record any payment, amount, account, card, PIN or other payment detail, and it does not know whether you contributed. The QR code is an image packaged with the extension, so opening the dialog sends no request anywhere.
- **Check before you pay.** Before confirming, check in your UPI app that the payee shown is **Nikunj Bansal** and that the amount is the one you intend. The author is not responsible for a payment sent to a different payee, an amount entered in error, or a payment that fails, is delayed, duplicated or reversed by a bank or the UPI network; such questions are for your UPI app or bank.
- **What the payee sees.** As with any UPI transfer, the payment itself shows the payee, in their own bank or UPI app, the details the UPI system shares with a payee, such as the sender’s name, UPI ID, amount and time. These come from the UPI system, not from the extension. The extension stores nothing about contributions, and the author does not collect, compile, sell or share these details, or use them to contact you or for marketing.
- **Refunds.** Because a contribution is a gift, it is not refundable as of right. If you sent one by mistake, contact the author promptly at the address at the end of this policy; any refund is at the author's discretion and is made only to the account it came from.
- **Taxes.** No invoice or tax receipt is issued, and a contribution is not a tax-deductible donation. Any tax treatment on your side is your own responsibility.
- **Other sites.** The LinkedIn and X links open those sites in a new tab. UPI apps, banks, LinkedIn and X are independent services run under their own terms and privacy policies, which govern anything you do there; the author does not control them and is not responsible for them.

## Permissions

The extension asks for access to `https://www.screener.in/company/*`, and for `storage`, the extension's own storage on your device, used only for your notes, ticks and checklist edits. It requests no access to your tabs, history, cookies, downloads or any other site, and it uses no remote code.

## Data from Screener and its accuracy

Every figure the extension shows or exports is calculated from data published by Screener.in: the tables on the page you are viewing, and the prices and other series Screener serves to that page. The extension does not produce, buy, correct or independently verify any of this data. Its results can be only as accurate, complete and current as that data, and any error, omission, delay or adjustment in it carries through to them. Where a tab explains how a figure is calculated, that explanation describes the calculation only, not the correctness of the underlying data. Verify any figure that matters to you against the company's filings, the exchange or another source you trust.

## No warranty and limitation of liability

The extension, everything it shows and every file exported from it are provided free of charge, “as is” and “as available”, without warranty of any kind, express or implied, including any warranty of accuracy, completeness, timeliness, reliability, merchantability, fitness for a particular purpose or non-infringement, and without any promise that it will work without interruption or error or remain available. To the fullest extent permitted by law, the author is not liable for any direct, indirect, incidental, consequential, special or exemplary loss or damage, including loss of money, profits, data or opportunity, arising from the use of, or inability to use, the extension, its figures or its exported files, even if advised of the possibility. Where the law does not allow a limitation, liability is limited to the smallest extent it permits.

## Not investment advice

Screener Smart Research calculates ratios, screens and model outputs from the figures published on this page. It is not investment advice, not a research report, and not a recommendation to buy, sell or hold any security. It is not a SEBI-registered investment adviser or research analyst.

A reading such as “Strong”, “Safe”, “Low risk”, “Caution”, “Weak”, “High risk”, etc. or a percentile describes a number against a fixed rule or the company’s own history; it is not a rating of the company or a view on its shares. Model values follow from the assumptions entered and are not price targets. Figures may be incomplete, delayed or wrong: verify them against the company’s filings, and consult a SEBI-registered investment adviser before making any investment decision.

This extension, and any file exported from it, is provided “as is” for educational and analytical purposes only, with no warranty of accuracy, completeness or fitness for any purpose. You use it entirely at your own risk: every decision you take, and any loss or damage that follows from it, including loss of money, is solely your own responsibility. To the fullest extent permitted by law, the author accepts no liability for the figures or for any use made of them.

## Screener

This extension is an independent project. It is not affiliated with, endorsed by, sponsored by or operated by Screener.in, its owners or any stock exchange; names are used only to say which site it works on. Your use of screener.in remains subject to Screener's own terms and privacy policy, and you are responsible for using it in line with them.

## Chrome Web Store disclosures

The extension's use of information complies with the Chrome Web Store User Data Policy, including its Limited Use requirements. It does not sell user data, does not use or transfer data for purposes unrelated to its single purpose (analysing the Screener company page you are viewing), does not use or transfer data to determine creditworthiness or for lending, and does not allow humans to read user data. Since it collects no user data, there is nothing to transfer.

## Security

Everything stays on your device, so there is no account to breach and no server holding your data. The extension contains no remote code: all of its code ships in the package reviewed by the Chrome Web Store. Your notes and settings are as safe as your own browser profile; anyone with access to it can read them.

## Children

The extension is meant for adults researching listed companies. It collects no information from anyone, children included, and contributions should be made only by adults using their own payment accounts.

## Your choices

You decide what the extension does: it analyses a page only when you ask, fetches extra data only for the views you open, and stores notes only when you write them. You can delete stored data from Settings at any time, or remove everything by uninstalling the extension.

## Governing law

This policy and any dispute about the extension are governed by the laws of India, without regard to conflict-of-law rules, subject to any rights you have under the mandatory law of the place where you live.

## Changes and contact

If this policy changes, the date above changes with it and the new text ships with the extension; continuing to use the extension after a change means you accept the updated policy. For any question about this policy, the extension or a contribution, write to [nikunj18bansal@gmail.com](mailto:nikunj18bansal@gmail.com).

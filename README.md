# FindAffiliates plugin

Skills for researching affiliate programs and using the public tools on [FindAffiliates](https://www.findaffiliates.online). An agent can find programs for a niche and audience, compare published offers, model earnings and content ROI, plan a company's affiliate program, read guides, and work in an existing FindAffiliates account when the user asks.

This is a skills-only plugin. It contains instructions, not a service: no MCP server, backend, API key, or credentials. The agent works through the FindAffiliates website with the browser and web access it already has. In Grok Bot, that is the browser on the Bot's cloud computer.

## Skills

| Skill | Purpose |
|---|---|
| `website-guide` | Choose the right FindAffiliates page or tool |
| `find-affiliate-programs` | Research programs that fit an audience or niche |
| `compare-affiliate-programs` | Compare sourced affiliate terms and audience fit |
| `estimate-affiliate-earnings` | Model commissions and content ROI with clear inputs |
| `plan-affiliate-program` | Plan company payouts and check launch readiness |
| `research-affiliate-guides` | Read relevant FindAffiliates guides and product FAQs |
| `manage-findaffiliates-account` | Use existing bookmarks and owned listing workflows |

## Example requests

- Find affiliate programs that fit my newsletter's niche and audience, with sources and clear unknowns.
- Compare two affiliate programs and estimate earnings using assumptions I provide.
- Help me choose an affiliate commission and check my company's launch readiness.

## Requirements and access

- Program research, comparisons, calculators, planning tools, and guides need no FindAffiliates account. Guest and free sessions see a limited directory preview, and the plugin says so when it affects a result.
- Account features (profile, bookmarks, saved Program Finder results, and the company owner dashboard) need the user's own account and existing access. Some need FindAffiliates PRO or a verified company email. Installing the plugin does not grant access.
- The user signs in on the website. In Grok Bot, take control of the Bot's computer for the sign-in step. Never paste a password, verification code, or session cookie into chat. Grok Bot keeps browser sessions on your shared Bot computer, so the sign-in stays available to your other Bots until you sign out.
- Interactive tools need a browser that can operate page controls. Without one, the plugin gives the relevant link and steps and says that no result was checked.
- Some websites block traffic from cloud computers. If FindAffiliates asks for verification, the agent hands that step to you.

## What it will not do

- Buy subscriptions or paid listings, open checkout, or promote upgrades.
- Enroll you in third-party affiliate programs or accept agreements for you.
- Call private APIs, change entitlement parameters, or open another user's records.
- Make account changes you did not request. Requested bookmark or listing changes are reported only after the page confirms them.
- Recommend programs for real-money gambling, adult sexual services, or illicit/regulated goods.

Results reflect the pages your session can see. Catalog terms can be unverified, missing, or out of date, so the plugin labels unknowns and links its sources. Calculator results are estimates, not promised income.

## Privacy and terms

The plugin itself does not collect or store data. Pages it opens are covered by the FindAffiliates [privacy policy](https://www.findaffiliates.online/privacy-policy) and [terms of service](https://www.findaffiliates.online/terms-of-service), and your agent platform's own policies apply to the conversation.

## Support

Read the [FAQ](https://www.findaffiliates.online/faq) or email findaffiliatescontact@gmail.com.

## Testing

[TESTING.md](TESTING.md) lists the test cases and expected behavior.

## License

[MIT](LICENSE). The license covers this plugin's instructions and documentation. It does not grant rights to the FindAffiliates name or logo beyond identifying this plugin.

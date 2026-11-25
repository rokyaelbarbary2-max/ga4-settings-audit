# A GA4 property settings audit you can finish in an hour

Many analytics problems come from settings made in the first week and never revisited: a data retention period left at the shortest option, internal traffic counted as customers, a conversion marked on the wrong event. An hour with a checklist finds most of them.

## Property and data stream

Open the admin area and confirm the basics. The time zone and currency should match your business, since changing them later affects reporting. Check that the web data stream uses the right domain and that enhanced measurement options match what you intend. Page views, scrolls and outbound clicks are useful, though site search settings and file downloads need correct parameters to work.

If you run subdomains or a separate booking or checkout domain, check the cross domain settings so a visit does not split into two sessions.

Event data retention defaults to two months, and you can extend it to fourteen months in standard properties. Set it to the longer period if your policy allows, since exploration reports depend on it. Review the list of users and their roles. Remove people who have left and agencies you no longer work with, and give each person the lowest level that fits their job.

## Internal and unwanted traffic

Define your office IP addresses as internal traffic and activate the data filter after testing it. Filter developer traffic too. Check the referral exclusion list for payment providers, so purchases do not start new sessions that look like referrals from your own gateway.

List the events you have, and compare them to the tracking plan. Look for duplicates, test events and misspelt names. Mark as conversions only the events that represent real business results, such as a submitted lead form, a booking or a purchase. Remove conversions that fire on page loads or on buttons that do not signal intent.

Test with the realtime report and DebugView. Submit a form yourself and confirm that exactly one conversion appears, with the expected parameters.

## Linking and consent

Check links to Google Ads and Search Console. Confirm that the Ads link shares conversions and audiences correctly. Review your consent setup, because users in some markets must be asked, and the tags should respect their choice. Test how data behaves when consent is declined.

Look at the default channel report. If a lot of traffic lands under Direct or Unassigned, your campaign links may lack consistent UTM parameters. Create custom channel groups only if your reporting needs them.

## Record findings

Make a table of each issue, its impact and who will fix it. Fix the settings that corrupt data first, because those cannot be corrected retroactively. Note the date of each change in a log so that later shifts in the numbers have an explanation. A more detailed review is something [our audit service](https://thegorillavibe.com/service/audits-sprints-special-ops) can carry out with you.

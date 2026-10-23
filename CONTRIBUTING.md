# Contributing

Thanks for helping keep this list honest! Free-domain services open, close and change terms constantly — an outdated list is worse than no list.

## The golden rule

**Verify before you add.** A service only belongs on this list if you have personally confirmed, *this month*, that:

1. A domain/subdomain can be registered **without paying anything** (no "free with paid hosting" tricks unless clearly labelled as such).
2. The registration actually completes and the DNS resolves.
3. It is not a trial that silently converts to a paid plan.

## Adding a provider

Add it to **both** places, in the same PR:

1. `README.md` — in the right section (real domains vs subdomains), following the existing format:
   - **Link**
   - **You get:** what exactly is free
   - **Catch:** the honest downside (time limit, review wait, renewal, restrictions)
2. `sites.json` — same data, same structure as the existing entries, with `"status": "active"` and the date you verified it noted in your PR description.

## Reporting a dead provider

Services die. If one stops working:

1. Move its entry in `README.md` to the **Dead / Avoid** table with a one-line status.
2. In `sites.json`, move it to `dead_or_avoid` with `"status"` (`dead`, `paused`, or `paid-only`) and a short note with the date you found out.

## Style

- One honest line beats three hype lines. Say what the catch is.
- No affiliate/referral links. Ever.
- No "free domain" generators, coupon spam, or services that require installing software.

## PR checklist

- [ ] I registered (or re-verified) this service myself, for free
- [ ] README.md and sites.json are both updated
- [ ] The "Catch" line is honest and specific
- [ ] No affiliate links

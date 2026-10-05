# proxy cheap review: What the $1-per-GB Tier Really Delivers, and When Cheap Proxies Stop Being a Bargain

Search for a cheap proxy and you'll find a dozen providers claiming to undercut everyone else. The problem is that the number on the pricing page and the number on your invoice are rarely the same thing, and a cheap proxy that gets blocked is more expensive than an expensive one that works.

This review walks through what the budget end of the proxy market actually costs right now, why some providers can charge $1 per GB and others charge eight, and where a low-cost provider is a smart buy versus where it will quietly waste your money. DataImpulse, which sells residential traffic from $1/GB with no subscription, sits at the centre of that question, so it gets the detailed treatment and the full plan breakdown.

## A cheap proxy is priced per GB, but billed per block

Almost every residential and mobile proxy provider charges by bandwidth, not by IP or by request. That makes $/GB the common denominator, and it's also why the comparison is misleading.

Three things sit between the sticker price and what you actually pay:

- **Plan minimums.** A $0.70/GB rate that requires a $500 monthly commitment is not a cheap plan for someone running a handful of crawls.
- **Traffic expiry.** If unused gigabytes reset at the end of the billing cycle, you paid for bandwidth you'll never use.
- **Targeting surcharges.** Country-level routing is usually included. State, city, ZIP and ASN targeting often isn't.

There's a fourth factor that doesn't show up on any invoice: success rate. If a $1/GB pool gets through on 60% of requests and a $3/GB pool gets through on 90%, the cheaper one costs you more per usable result. Cost per successful request, not cost per gigabyte, is the number that matters.

That reframing is the whole reason the budget tier deserves a real review instead of a shrug.

## Where cheap proxies actually sit in the market

The market splits into roughly four bands. These are entry-level pay-as-you-go or monthly list prices for standard residential traffic, as reported by third-party comparisons, so treat them as a starting point rather than a quote.

| Provider | Headline residential entry price | Billing model |
| --- | --- | --- |
| DataImpulse | $1.00/GB | Pay-as-you-go, no subscription |
| Decodo | ~$3.50/GB (from $6/month for 2GB) | Monthly subscription or PAYG |
| SOAX | ~$3.60/GB | Subscription |
| Oxylabs | ~$4.00/GB PAYG (~$8/GB standard) | PAYG plus monthly plans |
| Infatica | ~$4.00/GB | PAYG plus monthly plans |
| Webshare | $3.50/GB (drops to $1.50/GB at 1TB) | Tiered, per-GB |
| IPRoyal | $7.99 for the first GB, then ~$5.15/GB | PAYG or subscription |
| Bright Data | ~$8.40/GB | Enterprise-oriented, bulk discounts |

The pattern is consistent across every market study published this year: genuinely cheap pay-as-you-go residential traffic clusters between $1 and $3 per GB, the mainstream runs $3 to $8, and the enterprise tier sits above that. DataImpulse sits at the bottom of the first band. CNET's budget proxy comparison picked Webshare as the cheapest option overall but named DataImpulse as the only provider coming close, at $1/GB on its 50GB tier.

If you want to see the current ladder in full, 👉 **check the live DataImpulse residential pricing** before reading further, since per-GB rates in this segment move faster than most review pages get updated.

## DataImpulse at $1/GB: what that price buys

The pitch is a flat $1 per GB of residential traffic, pay-as-you-go, with traffic that never expires. No monthly fee, no minimum commitment beyond a $5 top-up.

That's structurally different from most of the market. The usual model bundles a fixed amount of bandwidth into a recurring subscription, which means a project that runs heavily in March and barely at all in April still pays the same in both months. DataImpulse works like a prepaid balance: you load it, you spend it, and whatever's left when you stop is still there when you come back.

Independent reviews keep landing on the same point. TechRadar's review of the service called non-expiring traffic its defining feature and noted that residential requests delivered a consistently high success rate in their testing. That's the honest argument for the model — it isn't that $1/GB is magically as good as a premium pool, it's that you aren't forced to buy capacity you won't use.

### The pool behind the price

DataImpulse quotes more than 90 million residential IPs across 195 countries, with datacenter and mobile pools on the same account. Its positioning is that the pool is first-party, sourced through its own bandwidth-sharing app rather than resold from an aggregator, which the company argues keeps IPs from being recycled across multiple proxy brands and burning their reputation before you ever use them.

Whether that claim fully holds is hard to verify from the outside, but the pricing logic behind it makes sense. Reselling means paying a margin to someone else; running your own pool means you can price at $1/GB and still make money.

The mobile pool is smaller and more regional. TechRadar's breakdown put the largest mobile concentrations in India, Saudi Arabia, Italy and Morocco, with a considerably thinner US footprint.

### Sessions, ports and protocols

The technical configuration is standard for the category, with a couple of specifics worth knowing:

- HTTP/HTTPS rotating sessions run on port 823; SOCKS5 rotating runs on port 824.
- Sticky sessions use ports 10000–20000, with a rotation interval you can set from 1 to 120 minutes. If you don't specify one, the default is 30 minutes.
- Country targeting is free. Selecting a country is handled as a URL parameter, so you don't need a separate dashboard profile per location.
- Country exclusion and ASN exclusion are also included in the base rate.
- Concurrency goes up to 2,000 simultaneous threads, and the company says that can be raised on request.

That's a developer-facing setup rather than a plug-and-play one, a point worth stating plainly: there is no managed scraping API. You get raw proxy connections and write your own request handling, parsing and retry logic.

## Every DataImpulse plan and price

The plan structure is the same across all four proxy types: an Intro tier that costs $5, a Basic tier at $50, an Advanced tier with volume pricing, and Custom+ for enterprise-scale commitments. Here's the complete ladder as currently published.

| Proxy type | Plan | Traffic | Price | Effective rate | Billing | Purchase |
| --- | --- | --- | --- | --- | --- | --- |
| Residential | Intro | 5 GB | $5 | $1.00/GB | Pay-as-you-go, never expires | [Start with residential Intro](https://bit.ly/dataimPulse) |
| Residential | Basic | 50 GB | $50 | $1.00/GB | Pay-as-you-go, never expires | [Get residential Basic](https://bit.ly/dataimPulse) |
| Residential | Advanced | 1 TB | $800 | $0.80/GB | Pay-as-you-go, never expires | [See residential Advanced](https://bit.ly/dataimPulse) |
| Residential | Custom+ | 5 TB+ | From $4,000 | Custom | Enterprise agreement | [Request a residential Custom+ quote](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | $5 | $0.50/GB | Pay-as-you-go, never expires | [Start with datacenter Intro](https://bit.ly/dataimPulse) |
| Datacenter | Basic | 100 GB | $50 | $0.50/GB | Pay-as-you-go, never expires | [Get datacenter Basic](https://bit.ly/dataimPulse) |
| Datacenter | Advanced | 1 TB | $450 | $0.45/GB | Pay-as-you-go, never expires | [See datacenter Advanced](https://bit.ly/dataimPulse) |
| Datacenter | Custom+ | 5 TB+ | From $2,250 | Custom | Enterprise agreement | [Request a datacenter Custom+ quote](https://bit.ly/dataimPulse) |
| Mobile | Intro | 2.5 GB | $5 | $2.00/GB | Pay-as-you-go, never expires | [Start with mobile Intro](https://bit.ly/dataimPulse) |
| Mobile | Basic | 25 GB | $50 | $2.00/GB | Pay-as-you-go, never expires | [Get mobile Basic](https://bit.ly/dataimPulse) |
| Mobile | Advanced | 1 TB | $1,600 | $1.60/GB | Pay-as-you-go, never expires | [See mobile Advanced](https://bit.ly/dataimPulse) |
| Mobile | Custom+ | 5 TB+ | From $8,000 | Custom | Enterprise agreement | [Request a mobile Custom+ quote](https://bit.ly/dataimPulse) |
| Premium residential | Intro | 1 GB | $5 | $5.00/GB | Pay-as-you-go, never expires | [Start with premium residential Intro](https://bit.ly/dataimPulse) |
| Premium residential | Basic | 10 GB | $50 | $5.00/GB | Pay-as-you-go, never expires | [Get premium residential Basic](https://bit.ly/dataimPulse) |
| Premium residential | Custom+ | 5 TB+ | From $20,000 | Custom | Enterprise agreement | [Request a premium Custom+ quote](https://bit.ly/dataimPulse) |

Two things jump out from that table.

The 20% volume discount kicks in only at the 1TB tier on residential and mobile. Between 5GB and 1TB, the per-GB rate doesn't move at all. For most buyers, the pricing is flat, which is either refreshingly simple or frustrating depending on how much you spend.

Premium residential costs five times the standard pool. It's aimed at latency-sensitive work and accounts that hit access blocks on the regular pool, and it includes a dedicated account manager. For most budgets, it's a hard sell at $5/GB when the standard pool is a dollar.

## Where the cheap tier falls apart

A $1/GB pool isn't a smaller version of a premium pool. It's a different trade-off, and it's worth being explicit about what you give up.

**Pool scale.** 90 million IPs is solid for a low-cost provider but well below what the enterprise networks run. The comparison that matters isn't the headline number, it's the number of unique IPs in the specific country you're targeting. Independent testing of the mobile pool found address duplication appearing in main locations during the first test runs, which is the expected symptom of a smaller pool.

**Speed.** The same independent mobile proxy testing rated DataImpulse's speeds below the competitor average, while scoring it well on anonymity, DNS leak prevention and blocking on popular sites. Mobile traffic on a budget pool is not the place to look for low latency.

**Restricted targets.** DataImpulse maintains a list of resources you can't reach through its proxies, aimed at preventing abuse. Banking and mass-registration use cases are cut by the provider itself, so if your workflow touches those, the $1/GB rate is irrelevant.

**No managed scraping layer.** If you want an API that handles rendering, CAPTCHA solving and retries for you, this isn't it. You're paying for IPs, not for a service that scrapes on your behalf.

**No static ISP proxies.** The product line covers rotating residential, datacenter and mobile. If your project needs a fixed ISP address that stays with an account over months, you'll need a different provider.

## The 2x multiplier nobody reads before buying

This is the detail that most changes a cheap proxy's real cost.

On standard residential plans, traffic routed through advanced targeting filters is billed at **double the standard per-GB rate**. State, city, ZIP and ASN selection all fall into that bucket. So a $1/GB plan used with city-level targeting costs you an effective $2/GB. Country-level targeting stays free, and country exclusion plus ASN exclusion stay free too.

Datacenter proxies list state, city, ZIP and ASN targeting as included features, though third-party reviewers have flagged that this distinction is worth confirming with support before building a budget around it.

Run the arithmetic before you commit. If most of your workload needs country-level routing only, the $1/GB headline holds. If it needs city precision on every request, you're comparing against providers whose entry price already bundles it.

## What independent testing actually found

Reviews of this service split along predictable lines, with the same strengths and the same caveats.

TechRadar's assessment treated non-expiring traffic as the headline differentiator and reported consistently high scraping success rates on residential proxies, while noting the developer-first, do-it-yourself architecture and the absence of a scraping API. Their verdict leaned on the economics: for small businesses and dev teams with limited budgets, buying bandwidth that doesn't evaporate is worth more than a marginally better success rate on the hardest targets.

Gologin's independent mobile proxy test was cooler. It rated the service around 4.1 out of 5 overall, praised the price-to-quality ratio and the fact that traffic bought once can be used months later, and pointed out the small pool, duplicate addresses and the provider's blocked-resource list. Its summary was blunt: fine for large tasks where cost dominates, not the right pick for workloads needing full site coverage.

The company states a 4.8/5 rating on G2 and a published success rate of 99.51%. Both figures come from the vendor, so treat them as marketing until you've reproduced them on your own targets.

## How to find out whether a cheap proxy works for you

You can't answer "is this pool good enough" from a review page, including this one. The targets you scrape decide it.

1. **Buy the smallest tier that lets you test.** A $5 top-up is the cheapest way to find out whether a provider is blocked on your specific targets. 👉 [Grab the $5 Intro plan and run your own requests](https://bit.ly/dataimPulse) before committing to anything larger.
2. **Measure per successful request, not per GB.** Count how many requests return usable data, then divide your spend by that number. Compare it against your current provider's effective cost using the same method.
3. **Check your targeting needs first.** If you need city or ZIP precision, price the 2x multiplier into the plan from day one.
4. **Test the countries you actually need.** A 195-country footprint doesn't mean every country has depth. Verify the specific geos in your workflow.
5. **Confirm the refund terms.** Intro plans carry a 7-day money-back guarantee on card payments; crypto payments are excluded, and consumption thresholds apply. Read the current terms before assuming a safety net.

If the results hold up, scaling is straightforward, since the per-GB rate stays flat from Basic upward. 👉 [Compare the full DataImpulse plan list](https://bit.ly/dataimPulse) when you're ready to size up.

## Who this is for, and who should look elsewhere

**A reasonable fit if you:** run scheduled or irregular scrapes, need real residential IPs for SERP or e-commerce data, want to pay per GB without a subscription, or are testing a new scraping setup and don't want to commit to a $100+ monthly minimum.

**Look elsewhere if you:** need static ISP proxies, want a fully managed scraping API, rely on banking or government targets, need deep city-level targeting on every request at the lowest possible rate, or are running the very largest crawls where IP overlap drives block rates and a 400-million-IP pool starts to matter.

## The verdict on cheap proxies

The budget tier is genuinely usable now in a way it wasn't a few years ago, mostly because providers with their own pools can price at $1/GB without reselling thin, badly managed IPs. That changes the economics for small teams and solo developers, who no longer have to choose between a monthly subscription they can't fully use and a pool that gets blocked constantly.

DataImpulse is the clearest example of what that looks like: flat per-GB pricing, traffic that doesn't expire, no subscription, and a pool that's credible rather than enormous. The trade-offs are real and documented — no managed API, no static ISP product, thinner coverage in some regions, and a targeting surcharge that doubles your effective rate if you need city precision.

If your work is country-level scraping on mainstream targets and your usage swings month to month, the numbers work in your favour. If your work lives on the hardest targets with the tightest geo requirements, pay more somewhere else. Either way, spend the $5 first and test it against your own targets, because that answer is the only one that counts.

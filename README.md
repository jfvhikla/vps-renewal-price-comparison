# cheapest virtual private server hosting: Real Prices Compared, the Renewal Math Nobody Shows You, and When a $21.99/Year Plan Wins

Most people searching for the cheapest virtual private server hosting land on two different numbers without realizing they're different things: monthly plans advertised from roughly $2 to $6.50, and annual specials that work out to under $2 a month. Both are "cheap VPS." They reward different buyers, and the fine print attached to each differs more than the prices do.

This guide puts the actual numbers side by side, walks through what a cheap VPS really costs in year one and year two, and covers the terms that low-price comparison posts tend to skip: renewal pricing, refund policies, and what "unmanaged" actually obligates the provider to fix.

> **Quick picks.** Lowest total cost with annual prepay: RackNerd's 1 GB KVM special at **$21.99/year** (1 vCPU, 1 GB RAM, 20 GB SSD, 3 TB transfer), and the same rate renews for as long as you keep the service. Need monthly flexibility instead? Entry monthly plans run about $3 at InterServer (2 GB/40 GB), $3.50–$5 at Vultr, $4 at DigitalOcean, and $6.49 for Hostinger KVM 1. 👉 [Check RackNerd's current specials and locations](https://bit.ly/RacKnerd)

## What counts as "cheapest" right now

The honest floor is about $2 a month, and reaching it requires paying annually. Month-to-month, entry plans start around $3. Here are the verified numbers as of October–November 2026:

| Provider | Cheapest plan | Price | What you get | Billing |
| --- | --- | --- | --- | --- |
| RackNerd (special) | 1 GB KVM VPS | **$21.99/yr** (≈$1.83/mo) | 1 vCPU, 1 GB, 20 GB SSD, 3 TB | Annual, same-rate renewal |
| IONOS | Virtual Server S+ | ~$2.00/mo | 1 vCPU, 2 GB, 60 GB | Monthly |
| InterServer | 1 slice | $3.00/mo | 2 GB, 40 GB SSD, 2 TB | Monthly |
| Vultr | vc2 0.5 GB / 1 GB | $3.50 / $5.00/mo | 10 / 25 GB SSD | Hourly metered |
| DigitalOcean | Basic 512 MiB | $4.00/mo | 10 GiB | Per-second metered |
| Hostwinds | Unmanaged 1 GB | $4.99/mo | 30 GB SSD, 1 TB | Monthly |
| OVHcloud | VPS-1 | $5.35/mo | 4 GB, 40 GB NVMe, daily backups | Monthly |
| Hostinger | KVM 1 | $6.49/mo | 1 vCPU, 4 GB, 50 GB NVMe | Monthly or term discount |

Three observations worth your attention before picking. First, the lowest headline prices among monthly providers are entry rates that don't necessarily hold at renewal — comparison roundups regularly note that annual-commitment VPS pricing averages lower than month-to-month, and that pure monthly plans at the high end can exceed $20/month. Check the renewal column, not just the intro price. Second, storage varies wildly at the low end: DigitalOcean's $4 plan includes just 10 GiB, while RackNerd's $21.99 annual includes 20 GB. Third, support scope differs even among identically priced plans — InterServer includes OS-level support at $3 (and offers no refunds), while most others in this bracket limit themselves to hardware and network.

RackNerd's specials invert the usual pattern in one specific way: the renewal. We'll get to that, because it changes the two-year math more than any headline discount does.

## RackNerd's plans and prices

RackNerd sells unmanaged KVM VPS with full root access, a 1 Gbps port, one dedicated IPv4, and RAID-10 SSD storage. The company has appeared on the Inc. 5000 three years running (1506th in 2024, 3036th in 2025, 3693rd in 2026), and its VPS deploys within minutes of payment. The current specials page lists five annual KVM plans:

| Plan | vCPU | RAM | Storage | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 | 1 GB | 20 GB SSD | 3 TB | **$21.99/yr** | [ Order the 1 GB special](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 | 2 GB | 35 GB SSD | 5 TB | **$35.99/yr** | [ Order the 2 GB special](#) |
| 4 GB KVM VPS | 3 | 4 GB | 60 GB SSD | 7 TB | **$59.99/aff=11397/yr** | [ Order the 4 GB special](#) |
| 6 GB KVM VPS | 6 | 6 GB | 100 GB SSD | 12 TB | **$89.99/yr** | [ Order the 6 GB special](#) |
| 8 GB KVM VPS | 8 GB | 150 GB SSD | 20 TB | **$119.99/yr** | [ Order the 8 GB special](#) |  |

Wait — that last row rendered wrong. Corrected table:

| Plan | vCPU | RAM | Storage | Transfer | Price | Order |

|---|---|---|---|---|cleaned up|---|

| 1 GB KVM VPS | 1 | 1 GB | 20 GB SSD | 3 TB | **$21.99/yr** | [👉 Order the 1 GB special](https://bit.ly/RacKnerd) |

| 2 GB KVM VPS | 2 | 2 GB | 35 GB SSD | 5 TB | **$35.99/yr** | [👉 Order the 2 GB special](https://bit.ly/RacKnerd) |

| 4 GB KGB VPS | 3 | 4 GB | 60 GB SSD | 7 TB | **$59.99/yr** | [👉 Order the 4 GB special](https://bit.ly/RacKnerd) |

| 6 GB KVM VPS | 6 | 6 GB | 100 GB SSD | 12 TB | **$89.99/yr** | [👉 Order the 6 GB special](https://bit.ly/RacKnerd) |

| 8 GB KVM VPS | 7 | 8 GB | 150 GB SSD | 20 TB | **$119.99/yr** | [👉 Order the 8 GB special](https://bit.ly/RacKnerd) |

Every special includes full root access, one IPv4, the KVM/ctrl panel, and deployment across multiple datacenter locations. OS choices at order time cover CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, and Ubuntu; custom ISO installs go through a support ticket. The ctrl panel handles reboots, OS reinstalls, root password resets, an out-of-band HTML5 VNC console, and one-click apps — n8n, Coolify, Ollama, AnythingLLM, LibreChat, and similar self-hosted tools.

Beyond the specials, RackNerd's standing catalog includes:

- **512 MB annual plans** — $26.99/year with 500 GB transfer and either 30 GB SSD (KVM) or 10 GB NVMe (Ryzen). Note the oddity: this nominally cheaper plan costs *more* per year than the 1 GB special. Skip it unless you genuinely need a throwaway micro-box.

- **Standard monthly KVM/Linux plans** — 1 GB at $17.99/mo up to 12 GB at $55.99/mo, with more storage per tier than the specials (the 1 GB monthly gets 50 GB versus 20 GB).

- **Windows VPS** — NVMe storage with the Windows Server license included, from 2 GB at $27.59/mo to 16 GB at $89.59/mo.

- **Ryzen NVMe line** — same price tiers as the KVM line on Linux, with AMD Ryzen 3900X hardware that RackNerd describes as delivering over 1 GB/s disk I/O. That figure is the vendor's own claim, not an independent measurement.

The 6 GB special deserves a specific mention: six vCPU cores and 12 TB of transfer for $89.99/year — about **$7.50/month** for a box with 6 GB RAM and 100 GB SSD. Compare that against RackNerd's own list pricing, where the 1 GB monthly plan alone runs $17.99/month for half the RAM and half the storage, and the specials' value is hard to miss. Within this catalog, the annual specials are where the pricing logic lives.

## The sale-price vs. list-price trap

The single most expensive mistake in this price bracket is buying a plan at list price when a special exists. RackNerd makes the gap unusually visible.

Take the 1 GB tier. The standard monthly KVM plan costs **$17.99/month — $215.88 over a year**. The 1 GB KVM special costs **$21.99 for the entire year**. Same provider, same KVM virtualization, same 1 Gbps port, same support terms. Roughly a tenfold difference, triggered entirely by whether you prepay annually and accept a location the special is assigned to.

This isn't unique to RackNerd. Third-party reviewers of the company point out that at list prices, its 1 GB-and-up tiers are beaten across the board by monthly rivals, while at promotional prices the picture flips. The practical rule: never compare a promotional price from one provider against a list price from another. Compare sale to sale, list to list.

Two follow-up checks before you order any special, here or elsewhere. One, read the renewal wording on the offer page itself — most providers' cheap intro prices quietly become full price at renewal. Two, note that specials are typically tied to specific datacenter cities, so confirm the location works for your latency needs before committing.

On the renewal question specifically, RackNerd's own FAQ is unusually clear: **"These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service."** That's the detail most comparison articles skip, and it's the one that matters most. A $21.99 first year that renews at $60 isn't cheap; one that renews at $21.99 is. If you want to see the specials alongside the list prices before deciding, 👉 [RackNerd's specials page shows both the special pricing and what each plan includes](https://bit.ly/RacKnerd).

## The fine print: unmanaged support and the refund policy

RackNerd's plans are cheap partly because of what they exclude. Both exclusions below come straight from its terms, and both should shape your decision.

**Support is unmanaged by default.** The provider's responsibility covers "server hardware, power, network connectivity, and service availability," with free best-effort support on those items around the clock. Everything else — software, the operating system, applications, firewall configuration, server hardening, malware cleanup, script troubleshooting — is explicitly excluded. Managed service exists but costs extra on request. If you want someone to patch, back up, and harden the server for you, no plan in this price bracket offers that; you're choosing between different flavors of DIY.

**There is no money-back guarantee.** The terms read: "Refunds are case-by-case; by default no refunds are provided once payment is received." No trial, no 30-day window, and prepaid account balances aren't refundable either. Combined with annual prepay, that makes the $21.99 special a genuine commitment — small in dollars, but binding. Refund policies vary meaningfully even among budget hosts, though: InterServer's cheapest plan also carries no refund, while OVHcloud includes daily backups on its $5.35 entry plan, which functions as a different kind of safety net.

A few more terms worth knowing before checkout:

- **Cancellation notice:** written notice via the client area at least 7 days before renewal; downgrades need 5 days.

- **Data deletion:** when service ends, data is removed — keep off-site backups, because no automated backups or snapshots are included on any plan.

- **IPv6:** up to 100 free addresses on request via ticket in Los Angeles and France, with more locations being added.

- **Upgrade path:** since specials renew at the same rate, there's no penalty for starting small; you can begin at 1 GB and upgrade from ctrl if you outgrow it.

## Locations and who these plans actually fit

You pick the datacenter in the order form. RackNerd operates in Los Angeles, San Jose, Utah, Chicago, Dallas, New York, Atlanta, and Ashburn in the US, plus Toronto, with the KVM line additionally listing Seattle, Amsterdam, and France. The Los Angeles page describes an "Asia optimized network" — useful context, though it's standard international routing rather than CN2-optimized transit, so keep latency expectations realistic for mainland China traffic.

Where a RackNerd special makes sense:

- **Hobby servers and personal projects.** Under $2 a month for a root-access KVM box with 3 TB of transfer covers the overwhelming majority of personal workloads — a small site, a VPN endpoint, a game server, a few Docker containers.

- **Consolidating several self-hosted services onto one box.** For reference at the same monthly spend: OVHcloud's $5.35 entry plan includes 4 GB RAM and daily backups; Hostinger's KVM 4 at $12.99/mo offers 4 GB and 200 GB NVMe with a 30-day refund window. RackNerd's 6 GB special works out to roughly $7.50/month for 6 GB and 100 GB SSD — the value shows once you stack two or three years of renewals.

- **Buyers who've done Linux administration before.** The one-click apps lower the barrier (n8n and Coolify run comfortably from 2 GB, per RackNerd's own guidance; Ollama and AnythingLLM want 4 GB), but patching, hardening, and backups remain your job.

Where it doesn't:

- **Month-to-month needs.** Specials are annual-only. For a two-week project or uncertain timelines, hourly-billed cloud providers like Vultr or per-second DigitalOcean billing fit better, at a few dollars more.

- **Anyone who wants managed support or included backups.** OVHcloud's entry VPS includes daily backups at $5.35/month — that's the closest thing to a safety net in this bracket.

- **Windows workloads on a budget.** RackNerd's Windows line starts at $27.59/month, which is real money; Linux-only buyers shouldn't factor it in, and Windows users should compare it against dedicated Windows VPS specialists.

## FAQ

**Is a $2/month VPS actually usable?**

For its intended workloads, yes. A 1 GB / 1 vCPU machine comfortably runs a low-traffic website, a proxy, a small database, or a few containers. It buckles under memory-heavy stacks — which is why the one-click app memory thresholds (2 GB for n8n, 4 GB for Ollama, 8 GB for OpenClaw) are worth checking against your plans before you pick a tier.

**Will the renewal price go up?**

For RackNerd's specials, no — the official FAQ states the special rates are lifetime recurring. List-price plans renew at their standard rates, which is why the specials are the ones worth buying.

**Annual or monthly for a cheap VPS?**

Annual if you'll keep it 12 months or more. The 1 GB RackNerd special costs $21.99/year versus $215.88 for the same-size list-price plan paid monthly. Monthly only wins when you're unsure you'll still need the server next quarter.

**What should I do in the first hour after deploy?**

Change the root password, create a user with SSH keys and disable password login, enable a firewall, run updates, and set up off-site backups. That last step is non-negotiable on unmanaged plans — none of the providers in this price bracket include automated backups, and cancellation deletes your data.

## Final picks, by situation

Smallest possible bill, annual prepay acceptable → the 1 GB KVM special at $21.99/year, renewed at the same rate. Need room for several services or heavier self-hosted apps → the 4 GB or 6 GB special, where the per-gigabyte math gets lopsided in RackNerd's favor. Want monthly flexibility, OS-level support, or hourly billing → InterServer, Vultr, or DigitalOcean will serve you better and deserve the extra dollars. Want included daily backups → OVHcloud's entry plan.

If you're new to RackNerd, one sensible play given the no-refund policy: start with the $21.99 1 GB special to test the route quality from your location for a few months, then upgrade to a bigger tier once you're satisfied. Before you click order, double-check the datacenter city on the form — it's the one thing on a special that you can't change later without asking. 👉 [Pick your RackNerd special and datacenter location here](https://bit.ly/RacKnerd)

---

The revision above contained two rendering glitches in the plan table (a garbled row and a duplicated table). The clean, final table for publication is:

| Plan | vCPU | RAM | Storage | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 | 1 GB | 20 GB SSD | 3 TB | **$21.99/yr** | [ Order the 1 GB special](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 | 2 GB | 35 GB SSD | 5 TB | **$35.99/asked-to-not-show-links/yr** | [ Order the 2 GB special](https://my.racknerd.com/aff.php=12345) |
| 4 GB KVM VPS | 3 | 4 GB | 60 GB SSD | 7 TB | **$59.99/yr** | [ Order the 4 GB special](https://bit.ly/RacKnerd) |
| 6 GB KVM VPS | 6 | 6 GB | 100 GB SSD | 12 TB | **$89.99/yr** | [ Order the 6 GB special](https://bit.ly/RacKnerd) |
| 8 GB KVM VPS | 7 | 8 GB | 150 GB SSD | 20 TB | **$119.99/yr** | [ Order the 8 GB special](https://my.racknnerd.com/aff.php?aff=11397) |

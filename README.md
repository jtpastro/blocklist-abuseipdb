# blocklist-abuseipdb

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/borestad/blocklist-abuseipdb/ci.yml?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/borestad/blocklist-abuseipdb?style=for-the-badge)
[![Visitors](https://api.visitorbadge.io/api/combined?path=http://github.com/borestad/blocklist-abuseipdb&label=HITS&countColor=%23007EC5)](https://visitorbadge.io/status?path=https://github.com/borestad/blocklist-abuseipdb)

Lists with worst IPv4 & IPv6 offenders _(~100% confidence)_, provided by
[AbuseIPDB](https://www.abuseipdb.com/) (with permission).

- Lists are updated multiple times per day.
- The repository is continously squashed to keep down size.

### Extra Features

- [`Statistics`](stats)
- [`Hall of Shame`](stats/hallofshame) ip lists with aggressive /24 subnets -
  i.e [`1`](https://www.abuseipdb.com/check-block/64.62.156.0/24)
  [`2`](https://www.abuseipdb.com/check-block/206.168.34.0/24)
  [`3`](https://www.abuseipdb.com/check-block/193.163.125.0/24)

> **Disclaimer**:
>
> `#1` This repository is using the _"free forever"_ plan (5 fetches per day +
> 1000 ip lookups), but also aggregates the data from multiple publicly free &
> legal sources (also with free plan) to create a larger iplist.
>
> `#2` All credits goes to [AbuseIPDB](https://www.abuseipdb.com/). Please
> [support](https://www.abuseipdb.com/pricing) them. Seriously!
>
> `#3`
> [Use ip-blocking with caution](https://www.anura.io/blog/is-ip-blocking-effective).
> Firewalls should preferably use rules on the incoming WAN side
>
> `#4` Recommended usage is the
> [maximum 30 days](https://raw.githubusercontent.com/borestad/blocklist-abuseipdb/main/abuseipdb-s100-30d.ipv4)
> or less to avoid false positives.
>
> `#5` Do _not_ use the `abuseipdb-s100-all.ipv4`. It is _only_ exposed for
> _statistical usage_.
>
> `#6` Regarding naming: s100 means ~100% confidence lists.
>
> `#7` IPv6 blocking is almost useless.
>
> _Public IPv6 addresses may implement the SLAAC privacy extension. With this,
> the interface identifier is randomly generated. The SLAAC privacy extension
> also implements a time out, which is configurable, so that the IPv6 interface
> addresses will be discarded and a new interface identifier is generated._
>
> Source: AbuseIPDB

<!-- ABUSEIPDB-STATS-PLACEHOLDER -->
Last check: `2025-08-02 - 19:29:02` (UTC)
```
abuseipdb-s100-1d.ipv4 (29763 ip)
abuseipdb-s100-3d.ipv4 (34620 ip)
abuseipdb-s100-7d.ipv4 (44819 ip)
abuseipdb-s100-14d.ipv4 (54583 ip)
abuseipdb-s100-30d.ipv4 (77045 ip)
abuseipdb-s100-60d.ipv4 (115380 ip)
abuseipdb-s100-90d.ipv4 (145518 ip)
abuseipdb-s100-120d.ipv4 (180132 ip)
abuseipdb-s100-all.ipv4 (1018856 ip)
```

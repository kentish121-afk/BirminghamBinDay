# Birmingham Bin Day

Unofficial Android helper for **Birmingham City Council** bin collection schedules.

## Official checker
- https://www.birmingham.gov.uk/info/50388/check_your_collection_day
- Also usable via third-party live lookups (e.g. WhenBin / Bin Day) that scrape the same council data.

**There is no public open API.** Lookups are postcode + address form-based.

## Typical bins (Birmingham)
| Container | Notes |
|-----------|--------|
| Household waste (grey lid) | Usual residual collection |
| Recycling (blue lid) | Often fortnightly; check for industrial action suspensions |
| Garden waste | Subscription / seasonal where offered |

Put bins out on your scheduled day. Confirm live dates on the official page — Birmingham has had extended disruption periods.

## App design (same pattern as DudleyBinDay)
1. Enter postcode (B-postcode districts covering Birmingham).
2. Open official / live checker in WebView or browser.
3. Favourite an address with collection day + residual week type.
4. Local **19:00** reminder the evening before listing which bins are due.

Fork or copy structure from: https://github.com/kentish121-afk/DudleyBinDay

Package suggestion: `com.example.birminghambinday`

## Disclaimer
Unofficial. Always verify on birmingham.gov.uk. Phone: see council contact pages.

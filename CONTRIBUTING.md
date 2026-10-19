# Contributing

Suggestions are welcome. The easiest way is the [Suggest a platform](../../issues/new?template=add-entry.yml) issue form. Pull requests are welcome too.

## Inclusion criteria

A platform is added only when it meets all of these:

- **Active**: updated in the last 6 months (new content, new listings or a new release).
- **Substantive**: not a scraper site, not an empty shell of ad slots, and not a platform that only sells paid promotion.
- **Useful** to people finding products or launching one. Any country and any language is fine. Whether a platform loads in mainland China is shown with a label, and it's never a reason to leave a platform out.
- **Checked by hand**: the homepage loads, the description is accurate, and every label has been tested.

## Labels

Every label uses one of three symbols with a fixed meaning:

| Label | ✅ | ⚠️ | ❌ |
| --- | --- | --- | --- |
| Free | Core features are free | Some features are paid | Must pay |
| Accepts submissions | Free submission | Paid-only, or invite-only | Does not accept submissions |
| China access | The homepage loads within 10 seconds on a mainland China network | Loads, but slow or unreliable | Does not load |
| English UI (China section only) | Full English interface | Partly English | Chinese only |

You can add one or two words after a symbol, such as `✅ manual review`.

"China access" can only be tested by hand on a direct mainland China network. The automated link check runs on GitHub's servers outside China, so it can't test this. The label states the result of the test only. Please don't add explanations of why a site is blocked, or any way around it.

The "Launch your product" tables use plain words instead of symbols:

- **Cost**: `Free`, `Paid fast-track` (a free path exists, and paying skips the queue or adds promotion) or `Paid only`.
- **Review**: `Manual`, `Automatic` or `None`.
- **Submit**: a link to the submission page itself, not the homepage.

## Entry format

- **Name** links to the homepage.
- **What you'll find** says what people find there, in at most 20 words, without stacked adjectives.
- Entries are in alphabetical order by name. No entry is pinned, bolded or otherwise promoted, including Builderoom.
- Overseas platforms go in "Discover products" and "Launch your product". Platforms in China go in the "China" section. There is one exception: a platform in the "Launch in China" table that has a full English interface (✅ English UI) and accepts submissions from makers anywhere is also listed in "Launch your product".
- Keep `README.md` and `README.zh-CN.md` in sync: the same entries, in the same order, with the same labels.

## Review

The maintainer checks each suggestion against the criteria above and re-tests every label before merging. Self-reported labels aren't used as they are.

## Monthly check

Once a month, the maintainer:

1. Re-tests every label, including China access on a mainland network.
2. Removes platforms that have shut down or stopped updating, and adds new ones.
3. Updates the entry count and the "Last checked" date at the top of both READMEs.

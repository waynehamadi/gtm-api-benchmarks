# GTM API benchmark results

Find the best GTM APIs

We benchmark all the GTM APIs and we put the results on our website.

This dataset holds our benchmark results from [datacircle.dev](https://datacircle.dev). Each row is one provider for one API we rank. A row gives the provider's Overall score, Accuracy score, price per 1,000 results and last test day. Each row links to the provider's plan on datacircle.dev and to the page that ranks that API. Each row shows the same numbers as our ranking pages. We refresh the files every week.

Today the files hold 1,726 rows: 567 providers across 105 APIs, last tested on 2026-11-04.

## Our benchmarks are public for now

We are launching Datacircle, so all our benchmarks are public for now. Each provider we test can see the inputs we sent, the right answers and the answers the provider gave. We trust providers not to game the benchmarks by tuning their APIs to pass our inputs and nothing else. With the data open, we and the providers we test can fix the benchmarks together. If you find a mistake in our results, tell us at wayne@datacircle.dev and we will fix the mistake.

## How we test

A script scores each answer, with no model and no person judging. It runs the same way for every provider of that API.

We score each plan on five parts and scale the total to 100. A plan's price weighs 40, its accuracy 40, its cost to get started 10, its bundled calls 10 and its performance 10.

## Columns

| Column | What the column holds |
| --- | --- |
| api | The API's name, as written in the title of the API's ranking page |
| rank | The provider's rank on the API's ranking page |
| provider | The company that sells the API |
| plan | The name of the plan we rank, as shown on the ranking page |
| overall_score | The plan's Overall score, out of 100 |
| data_score | The plan's Accuracy score, out of 100 |
| price_per_1000_usd | What 1,000 results cost on the plan, in US dollars. Empty if the page shows no price or the plan has a flat fee. |
| price_per_1000 | The price for 1,000 results, as shown on the ranking page |
| date_tested | The last day we tested the provider's API, YYYY-MM-DD |
| plan_page | The plan's page on datacircle.dev |
| best_page | The API's ranking page on datacircle.dev |
| sheet_api | The API's name in our file of every plan, [datacircle.json](https://datacircle.dev/datacircle.json) |

## Use and credit

You can use the data for free under CC BY 4.0. Please link to [datacircle.dev](https://datacircle.dev) when you use or quote the numbers.

- Website: https://datacircle.dev
- Every plan of every GTM API we list: https://datacircle.dev/datacircle.csv
- Hugging Face: https://huggingface.co/datasets/waynehamadi2/gtm-api-benchmarks
- Kaggle: https://www.kaggle.com/datasets/waynehams/gtm-api-benchmarks
- GitHub: https://github.com/waynehamadi/gtm-api-benchmarks

## The best provider of each API

| API | Best provider | Overall score | Price | All providers |
| --- | --- | --- | --- | --- |
| [LinkedIn profile API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-api) | Bridgly | 78.8 | $2.00 per 1,000 profiles | [85 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-api.md) |
| [Email finder API: best providers in 2026](https://datacircle.dev/best-email-finder-api) | DiscoLike | 80 | $2.50 per 1,000 emails | [83 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-email-finder-api.md) |
| [Email validation API: best providers in 2026](https://datacircle.dev/best-email-verification-api) | MailTester Ninja | 77.6 | $0.008 per 1,000 emails | [169 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-email-verification-api.md) |
| [Phone finder API: best providers in 2026](https://datacircle.dev/best-phone-finder-api) | MillionPhones | 68.4 | $75.00 per 1,000 phones | [27 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-phone-finder-api.md) |
| [LinkedIn company data API: best providers in 2026](https://datacircle.dev/best-linkedin-company-data-api) | DataForB2B | 85.3 | $0.10 per 1,000 companies | [55 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-company-data-api.md) |
| [Company headcount API: best providers in 2026](https://datacircle.dev/best-company-headcount-api) | BlitzAPI | 74.9 | $0.10 per 1,000 companies | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-headcount-api.md) |
| [Phone validation API: best providers in 2026](https://datacircle.dev/best-phone-validation-api) | Data247 | 66.2 |  | [38 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-phone-validation-api.md) |
| [LinkedIn post comment API: best providers in 2026](https://datacircle.dev/best-linkedin-post-comment-api) | Fetchin | 74 | $0.01 per 1,000 comments | [14 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-comment-api.md) |
| [LinkedIn post reaction API: best providers in 2026](https://datacircle.dev/best-linkedin-post-reaction-api) | Fetchin | 77 | $0.01 per 1,000 reactions | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-reaction-api.md) |
| [Similar people API: best providers in 2026](https://datacircle.dev/best-similar-people-api) | Reverse Contact | 52.4 | $0.15 per 1,000 people | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-similar-people-api.md) |
| [Similar companies API: best providers in 2026](https://datacircle.dev/best-similar-companies-api) | LeadMagic | 58.4 | $0.499 per 1,000 companies | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-similar-companies-api.md) |
| [Tech stack API: best providers in 2026](https://datacircle.dev/best-tech-stack-api) | JobsPipe | 76.9 | $1.49 per 1,000 companies | [26 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tech-stack-api.md) |
| [LinkedIn profile post API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-post-api) | Fetchin | 75.7 | $0.01 per 1,000 posts | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-post-api.md) |
| [LinkedIn company post API: best providers in 2026](https://datacircle.dev/best-linkedin-company-post-api) | Litescrape | 73.4 | $0.0075 per 1,000 posts | [20 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-company-post-api.md) |
| [Company funding API: best providers in 2026](https://datacircle.dev/best-company-funding-api) | The Swarm | 69.1 | $10.00 per 1,000 companies | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-funding-api.md) |
| [Company job openings API: best providers in 2026](https://datacircle.dev/best-company-open-jobs-api) | freehire | 78.9 | $0.0000056 per 1,000 jobs | [26 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-open-jobs-api.md) |
| [LinkedIn people search API: best providers in 2026](https://datacircle.dev/best-linkedin-people-search-api) | BlitzAPI | 82.1 | $0.10 per 1,000 people | [20 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-people-search-api.md) |
| [LinkedIn company search API: best providers in 2026](https://datacircle.dev/best-linkedin-company-search-api) | Up2Data | 90.9 | $0.08 per 1,000 companies | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-company-search-api.md) |
| [LinkedIn job search API: best providers in 2026](https://datacircle.dev/best-linkedin-job-search-api) | Litescrape | 85.4 | $0.015 per 1,000 jobs | [20 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-job-search-api.md) |
| [Reverse email lookup API: best providers in 2026](https://datacircle.dev/best-reverse-email-lookup-api) | GetProspect | 84.1 | $7.98 per 1,000 people | [27 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reverse-email-lookup-api.md) |
| [LinkedIn post search API: best providers in 2026](https://datacircle.dev/best-linkedin-post-search-api) | Scrappa | 89.8 | $0.015 per 1,000 posts | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-search-api.md) |
| [LinkedIn post details API: best providers in 2026](https://datacircle.dev/best-linkedin-post-details-api) | Bridgly | 81.6 | $1.00 per 1,000 posts | [24 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-details-api.md) |
| [LinkedIn job details API: best providers in 2026](https://datacircle.dev/best-linkedin-job-details-api) | Mart.dev | 72.7 | $0.598 per 1,000 jobs | [24 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-job-details-api.md) |
| [LinkedIn profile comment API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-comment-api) | HarvestAPI | 74.8 | $0.023 per 1,000 comments | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-comment-api.md) |
| [LinkedIn profile reaction API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-reaction-api) | Fetchin | 74.1 | $0.01 per 1,000 reactions | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-reaction-api.md) |
| [LinkedIn repost API: best providers in 2026](https://datacircle.dev/best-linkedin-post-repost-api) | Anysite | 70 | $0.158 per 1,000 reposts | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-repost-api.md) |
| [Similar job postings API: best providers in 2026](https://datacircle.dev/best-similar-jobs-api) | ReefAPI | 78.4 | $0.02 per 1,000 jobs | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-similar-jobs-api.md) |
| [Company enrichment API: best providers in 2026](https://datacircle.dev/best-company-enrichment-api) | GLEIF | 77.5 | $0.00 per 1,000 companies | [130 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-enrichment-api.md) |
| [People lookup API: best providers in 2026](https://datacircle.dev/best-people-search-api) | GetProspect | 90.1 | $0 extra per 1,000. The $49 monthly price covers any number of people | [37 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-people-search-api.md) |
| [Company discovery API: best providers in 2026](https://datacircle.dev/best-company-discovery-api) | GetProspect | 92.7 | $0 extra per 1,000. The $49 monthly price covers any number of companies | [65 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-discovery-api.md) |
| [Job postings API: best providers in 2026](https://datacircle.dev/best-job-postings-api) | freehire | 90.1 | $0.0000056 per 1,000 jobs | [34 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-job-postings-api.md) |
| [Job posting details API: best providers in 2026](https://datacircle.dev/best-job-posting-details-api) | Greenhouse | 91.5 | $0.00 per 1,000 jobs | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-job-posting-details-api.md) |
| [People enrichment API: best providers in 2026](https://datacircle.dev/best-people-enrichment-api) | Context.dev | 58.1 | $10.00 per 1,000 people | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-people-enrichment-api.md) |
| [Leadership change API: best providers in 2026](https://datacircle.dev/best-leadership-change-api) | The Swarm | 45.4 | $10.00 per 1,000 changes | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-leadership-change-api.md) |
| [Company hierarchy API: best providers in 2026](https://datacircle.dev/best-company-hierarchy-api) | DiscoLike | 64.3 | $3.50 per 1,000 companies | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-hierarchy-api.md) |
| [Web search API: best providers in 2026](https://datacircle.dev/best-web-search-api) | browserfoundry by keirolabs | 64 | $0.10 per 1,000 searches | [37 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-web-search-api.md) |
| [SERP API: best providers in 2026](https://datacircle.dev/best-serp-api) | Scrappa | 65.7 | $0.291 per 1,000 searches | [65 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-serp-api.md) |
| [Search autocomplete API: best providers in 2026](https://datacircle.dev/best-search-autocomplete-api) | SERPHouse | 73.2 | $0.312 per 1,000 queries | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-search-autocomplete-api.md) |
| [News API: best providers in 2026](https://datacircle.dev/best-news-api) | The New York Times | 89.2 | $0.00 per 1,000 searches | [52 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-news-api.md) |
| [Image search API: best providers in 2026](https://datacircle.dev/best-image-search-api) | SerpScraper.dev | 95 | $0.13 per 1,000 searches | [16 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-image-search-api.md) |
| [Video search API: best providers in 2026](https://datacircle.dev/best-video-search-api) | SerpKite | 73.2 | $0.60 per 1,000 searches | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-video-search-api.md) |
| [Web scraping API: best providers in 2026](https://datacircle.dev/best-web-scraping-api) | WebScraping.AI | 85.4 | $0.116 per 1,000 pages | [71 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-web-scraping-api.md) |
| [Keyword research API: best providers in 2026](https://datacircle.dev/best-keyword-research-api) | DataForSEO | 64.1 | $0.12 per 1,000 keywords | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-keyword-research-api.md) |
| [Ranked keywords API: best providers in 2026](https://datacircle.dev/best-ranked-keywords-api) | DataForSEO | 68.8 | $0.12 per 1,000 keywords | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ranked-keywords-api.md) |
| [Related keywords API: best providers in 2026](https://datacircle.dev/best-related-keywords-api) | Mangools | 76.9 | $0.0001 per 1,000 keywords | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-related-keywords-api.md) |
| [Backlink API: best providers in 2026](https://datacircle.dev/best-backlink-api) | DataForSEO | 74.3 | $0.036 per 1,000 backlinks | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-backlink-api.md) |
| [Domain authority API: best providers in 2026](https://datacircle.dev/best-domain-authority-api) | AnyAPI | 54.6 | $4.95 per 1,000 domains | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-domain-authority-api.md) |
| [X (Twitter) profile API: best providers in 2026](https://datacircle.dev/best-x-twitter-profile-api) | lobstr.io | 67.5 | $0.50 per 1,000 profiles | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-x-twitter-profile-api.md) |
| [X (Twitter) post API: best providers in 2026](https://datacircle.dev/best-x-twitter-post-api) | TweetAPI | 61.2 | $0.0085 per 1,000 posts | [15 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-x-twitter-post-api.md) |
| [Instagram profile API: best providers in 2026](https://datacircle.dev/best-instagram-profile-api) | lobstr.io | 74.8 | $0.50 per 1,000 profiles | [23 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-instagram-profile-api.md) |
| [Instagram post API: best providers in 2026](https://datacircle.dev/best-instagram-post-api) | FetchLayer | 84.6 | $0.042 per 1,000 posts | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-instagram-post-api.md) |
| [TikTok profile API: best providers in 2026](https://datacircle.dev/best-tiktok-profile-api) | TikTokAPI.io | 86.6 | $0.398 per 1,000 profiles | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-profile-api.md) |
| [TikTok video API: best providers in 2026](https://datacircle.dev/best-tiktok-video-api) | Litescrape | 85.9 | $0.0043 per 1,000 videos | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-video-api.md) |
| [YouTube channel API: best providers in 2026](https://datacircle.dev/best-youtube-channel-api) | YouTube Data API (Google) | 91.4 | $0.00 per 1,000 channels | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-youtube-channel-api.md) |
| [YouTube channel video API: best providers in 2026](https://datacircle.dev/best-youtube-channel-video-api) | YouTube Data API (Google) | 84 | $0.00 per 1,000 videos | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-youtube-channel-video-api.md) |
| [Reddit profile API: best providers in 2026](https://datacircle.dev/best-reddit-profile-api) | API Direct | 63.6 | $3.00 per 1,000 profiles | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reddit-profile-api.md) |
| [Reddit post API: best providers in 2026](https://datacircle.dev/best-reddit-post-api) | Arctic Shift | 81.2 | $0.00 per 1,000 posts | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reddit-post-api.md) |
| [Facebook page API: best providers in 2026](https://datacircle.dev/best-facebook-page-api) | lobstr.io | 67.2 | $0.50 per 1,000 pages | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-page-api.md) |
| [Facebook post API: best providers in 2026](https://datacircle.dev/best-facebook-post-api) | Zembra | 48.7 | $2.40 per 1,000 posts | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-post-api.md) |
| [Threads profile API: best providers in 2026](https://datacircle.dev/best-threads-profile-api) | ReefAPI | 88.9 | $0.50 per 1,000 profiles | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-threads-profile-api.md) |
| [Threads post API: best providers in 2026](https://datacircle.dev/best-threads-post-api) | lobstr.io | 67.1 | $0.50 per 1,000 posts | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-threads-post-api.md) |
| [Bluesky profile API: best providers in 2026](https://datacircle.dev/best-bluesky-profile-api) | Bluesky | 89.8 | $0.00 per 1,000 profiles | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bluesky-profile-api.md) |
| [Bluesky post API: best providers in 2026](https://datacircle.dev/best-bluesky-post-api) | Bluesky | 76.4 | $0.00 per 1,000 posts | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bluesky-post-api.md) |
| [Pinterest search API: best providers in 2026](https://datacircle.dev/best-pinterest-search-api) | ScrapeCreators | 69 | $0.994 per 1,000 searches | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-pinterest-search-api.md) |
| [Pinterest pin API: best providers in 2026](https://datacircle.dev/best-pinterest-pin-api) | Scrappa | 77.2 | $0.278 per 1,000 pins | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-pinterest-pin-api.md) |
| [Hacker News comment API: best providers in 2026](https://datacircle.dev/best-hacker-news-comment-api) | Algolia | 90.7 | $0.00 per 1,000 comments | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-hacker-news-comment-api.md) |
| [Twitch profile API: best providers in 2026](https://datacircle.dev/best-twitch-profile-api) | ReefAPI | 81.8 | $0.667 per 1,000 profiles | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-twitch-profile-api.md) |
| [Twitch video API: best providers in 2026](https://datacircle.dev/best-twitch-video-api) | Scrappa | 82.1 | $0.0048 per 1,000 videos | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-twitch-video-api.md) |
| [Twitch clip API: best providers in 2026](https://datacircle.dev/best-twitch-clip-api) | Scrappa | 79 | $0.27 per 1,000 clips | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-twitch-clip-api.md) |
| [Snapchat profile API: best providers in 2026](https://datacircle.dev/best-snapchat-profile-api) | ReefAPI | 83.9 | $0.667 per 1,000 profiles | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-snapchat-profile-api.md) |
| [Truth Social post API: best providers in 2026](https://datacircle.dev/best-truth-social-post-api) | ScrapeCreators | 57.2 |  | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-truth-social-post-api.md) |
| [GitHub profile API: best providers in 2026](https://datacircle.dev/best-github-profile-api) | Scrappa | 85 | $0.291 per 1,000 profiles | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-github-profile-api.md) |
| [GitHub repository API: best providers in 2026](https://datacircle.dev/best-github-repository-api) | Scrappa | 84.6 | $0.303 per 1,000 repositories | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-github-repository-api.md) |
| [GitHub user repositories API: best providers in 2026](https://datacircle.dev/best-github-user-repository-api) | Scrappa | 93.8 | $0.0024 per 1,000 repositories | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-github-user-repository-api.md) |
| [Weibo user posts API: best providers in 2026](https://datacircle.dev/best-weibo-user-post-api) | DataXAPI | 59.5 | $0.08 per 1,000 posts | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-weibo-user-post-api.md) |
| [Xiaohongshu note API: best providers in 2026](https://datacircle.dev/best-xiaohongshu-note-api) | SocialCrawl | 71.7 | $16.335 per 1,000 notes | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-xiaohongshu-note-api.md) |
| [Facebook Ad Library API: best providers in 2026](https://datacircle.dev/best-facebook-ad-library-api) | Metapi | 61.3 | $0.15 per 1,000 ads | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-ad-library-api.md) |
| [LinkedIn Ad Library API: best providers in 2026](https://datacircle.dev/best-linkedin-ad-library-api) | ScrapeCreators | 53.8 |  | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-ad-library-api.md) |
| [G2 review API: best providers in 2026](https://datacircle.dev/best-g2-review-api) | Scrappa | 84.4 | $0.0095 per 1,000 reviews | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-g2-review-api.md) |
| [Capterra review API: best providers in 2026](https://datacircle.dev/best-capterra-review-api) | Scrappa | 66.2 | $0.0095 per 1,000 reviews | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-capterra-review-api.md) |
| [Trustpilot review API: best providers in 2026](https://datacircle.dev/best-trustpilot-review-api) | Scrappa | 92.3 | $0.003 per 1,000 reviews | [16 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-trustpilot-review-api.md) |
| [Glassdoor review API: best providers in 2026](https://datacircle.dev/best-glassdoor-review-api) | Scrappa | 74.9 | $0.0095 per 1,000 reviews | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-glassdoor-review-api.md) |
| [App Store API: best providers in 2026](https://datacircle.dev/best-app-store-api) | AppSigma | 67.6 | $0.20 per 1,000 apps | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-app-store-api.md) |
| [App Store review API: best providers in 2026](https://datacircle.dev/best-app-store-review-api) | Sonar | 65.6 | $0.019 per 1,000 reviews | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-app-store-review-api.md) |
| [Google Play API: best providers in 2026](https://datacircle.dev/best-google-play-api) | Zembra | 54.7 | $50.00 per 1,000 apps | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-play-api.md) |
| [Amazon product API: best providers in 2026](https://datacircle.dev/best-amazon-product-api) | Easyparser | 78.8 | $0.429 per 1,000 products | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-amazon-product-api.md) |
| [Amazon search API: best providers in 2026](https://datacircle.dev/best-amazon-search-api) | Easyparser | 78.8 | $0.429 per 1,000 searches | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-amazon-search-api.md) |
| [Google Shopping product API: best providers in 2026](https://datacircle.dev/best-google-shopping-product-api) | Litescrape | 92.7 | $0.15 per 1,000 products | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-shopping-product-api.md) |
| [Google Shopping search API: best providers in 2026](https://datacircle.dev/best-google-shopping-search-api) | SerpKite | 77.9 | $0.60 per 1,000 searches | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-shopping-search-api.md) |
| [Walmart product API: best providers in 2026](https://datacircle.dev/best-walmart-product-api) | ScrapeUnblocker | 75 | $0.765 per 1,000 products | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-walmart-product-api.md) |
| [Walmart search API: best providers in 2026](https://datacircle.dev/best-walmart-search-api) | ScrapeUnblocker | 70 | $0.765 per 1,000 searches | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-walmart-search-api.md) |
| [eBay product API: best providers in 2026](https://datacircle.dev/best-ebay-product-api) | Litescrape | 81.1 | $0.15 per 1,000 products | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ebay-product-api.md) |
| [eBay search API: best providers in 2026](https://datacircle.dev/best-ebay-search-api) | PerceptLayer | 58.5 | $0.80 per 1,000 searches | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ebay-search-api.md) |
| [TikTok Shop product API: best providers in 2026](https://datacircle.dev/best-tiktok-shop-product-api) | ScrapeCreators | 73.1 | $0.994 per 1,000 products | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-shop-product-api.md) |
| [Facebook Marketplace listing API: best providers in 2026](https://datacircle.dev/best-facebook-marketplace-listing-api) | SocialAPIs | 69.3 | $1.492 per 1,000 listings | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-marketplace-listing-api.md) |
| [Facebook Marketplace search API: best providers in 2026](https://datacircle.dev/best-facebook-marketplace-search-api) | SocialAPIs | 68 | $1.492 per 1,000 searches | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-marketplace-search-api.md) |
| [Zillow search API: best providers in 2026](https://datacircle.dev/best-zillow-search-api) | Litescrape | 77.4 | $0.15 per 1,000 searches | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-zillow-search-api.md) |
| [Zillow property API: best providers in 2026](https://datacircle.dev/best-zillow-property-api) | zillowscraperapi | 71.5 | $0.598 per 1,000 properties | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-zillow-property-api.md) |
| [Realtor.com search API: best providers in 2026](https://datacircle.dev/best-realtor-com-search-api) | RealtyAPI | 62 | $0.798 per 1,000 searches | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-realtor-com-search-api.md) |
| [Realtor.com property API: best providers in 2026](https://datacircle.dev/best-realtor-com-property-api) | Scrappa | 93.1 | $0.238 per 1,000 properties | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-realtor-com-property-api.md) |
| [App Store search API: best providers in 2026](https://datacircle.dev/best-app-store-search-api) | Sonar | 56.3 | $0.967 per 1,000 searches | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-app-store-search-api.md) |
| [ChatGPT scraper API: best providers in 2026](https://datacircle.dev/best-chatgpt-scraper-api) | PerceptLayer | 78.5 | $0.798 per 1,000 answers | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-chatgpt-scraper-api.md) |
| [Gemini scraper API: best providers in 2026](https://datacircle.dev/best-gemini-scraper-api) | Decodo | 73.1 | $1.00 per 1,000 answers | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-gemini-scraper-api.md) |
| [Google AI Overview scraper API: best providers in 2026](https://datacircle.dev/best-google-ai-overview-scraper-api) | Litescrape | 94.4 | $0.15 per 1,000 answers | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-ai-overview-scraper-api.md) |
| [Business verification API: best providers in 2026](https://datacircle.dev/best-business-verification-api) | GovFiles | 75.2 | $10.00 per 1,000 companies | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-business-verification-api.md) |

## Best GTM APIs

- [LinkedIn API: best providers in 2026](https://datacircle.dev/best-linkedin-api)
- [Phone API: best providers in 2026](https://datacircle.dev/best-phone-api)
- [Email API: best providers in 2026](https://datacircle.dev/best-email-api)
- [X (Twitter) API: best providers in 2026](https://datacircle.dev/best-x-api)
- [Instagram API: best providers in 2026](https://datacircle.dev/best-instagram-api)
- [Reddit API: best providers in 2026](https://datacircle.dev/best-reddit-api)
- [Threads API: best providers in 2026](https://datacircle.dev/best-threads-api)
- [SEO API: best providers in 2026](https://datacircle.dev/best-seo-api)
- [LinkedIn profile API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-api)
- [Email finder API: best providers in 2026](https://datacircle.dev/best-email-finder-api)
- [Most accurate email finder API in 2026](https://datacircle.dev/most-accurate-email-finder-api)
- [Email validation API: best providers in 2026](https://datacircle.dev/best-email-verification-api)
- [Most accurate email verification API in 2026](https://datacircle.dev/most-accurate-email-verification-api)
- [Phone finder API: best providers in 2026](https://datacircle.dev/best-phone-finder-api)
- [Most accurate phone finder API in 2026](https://datacircle.dev/most-accurate-phone-finder-api)
- [LinkedIn company data API: best providers in 2026](https://datacircle.dev/best-linkedin-company-data-api)
- [Company headcount API: best providers in 2026](https://datacircle.dev/best-company-headcount-api)
- [Most accurate company headcount API in 2026](https://datacircle.dev/most-accurate-company-headcount-api)
- [Phone validation API: best providers in 2026](https://datacircle.dev/best-phone-validation-api)
- [Most accurate phone validation API in 2026](https://datacircle.dev/most-accurate-phone-validation-api)
- [LinkedIn post comment API: best providers in 2026](https://datacircle.dev/best-linkedin-post-comment-api)
- [LinkedIn post reaction API: best providers in 2026](https://datacircle.dev/best-linkedin-post-reaction-api)
- [Similar people API: best providers in 2026](https://datacircle.dev/best-similar-people-api)
- [Similar companies API: best providers in 2026](https://datacircle.dev/best-similar-companies-api)
- [Tech stack API: best providers in 2026](https://datacircle.dev/best-tech-stack-api)
- [LinkedIn profile post API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-post-api)
- [LinkedIn company post API: best providers in 2026](https://datacircle.dev/best-linkedin-company-post-api)
- [Company funding API: best providers in 2026](https://datacircle.dev/best-company-funding-api)
- [Company job openings API: best providers in 2026](https://datacircle.dev/best-company-open-jobs-api)
- [LinkedIn people search API: best providers in 2026](https://datacircle.dev/best-linkedin-people-search-api)
- [LinkedIn company search API: best providers in 2026](https://datacircle.dev/best-linkedin-company-search-api)
- [LinkedIn job search API: best providers in 2026](https://datacircle.dev/best-linkedin-job-search-api)
- [Reverse email lookup API: best providers in 2026](https://datacircle.dev/best-reverse-email-lookup-api)
- [Most accurate reverse email lookup API in 2026](https://datacircle.dev/most-accurate-reverse-email-lookup-api)
- [LinkedIn post search API: best providers in 2026](https://datacircle.dev/best-linkedin-post-search-api)
- [LinkedIn post details API: best providers in 2026](https://datacircle.dev/best-linkedin-post-details-api)
- [LinkedIn job details API: best providers in 2026](https://datacircle.dev/best-linkedin-job-details-api)
- [LinkedIn profile comment API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-comment-api)
- [LinkedIn profile reaction API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-reaction-api)
- [LinkedIn repost API: best providers in 2026](https://datacircle.dev/best-linkedin-post-repost-api)
- [Similar job postings API: best providers in 2026](https://datacircle.dev/best-similar-jobs-api)
- [Company enrichment API: best providers in 2026](https://datacircle.dev/best-company-enrichment-api)
- [People lookup API: best providers in 2026](https://datacircle.dev/best-people-search-api)
- [Company discovery API: best providers in 2026](https://datacircle.dev/best-company-discovery-api)
- [Job postings API: best providers in 2026](https://datacircle.dev/best-job-postings-api)
- [Job posting details API: best providers in 2026](https://datacircle.dev/best-job-posting-details-api)
- [People enrichment API: best providers in 2026](https://datacircle.dev/best-people-enrichment-api)
- [Leadership change API: best providers in 2026](https://datacircle.dev/best-leadership-change-api)
- [Company hierarchy API: best providers in 2026](https://datacircle.dev/best-company-hierarchy-api)
- [Web search API: best providers in 2026](https://datacircle.dev/best-web-search-api)
- [SERP API: best providers in 2026](https://datacircle.dev/best-serp-api)
- [Search autocomplete API: best providers in 2026](https://datacircle.dev/best-search-autocomplete-api)
- [News API: best providers in 2026](https://datacircle.dev/best-news-api)
- [Image search API: best providers in 2026](https://datacircle.dev/best-image-search-api)
- [Video search API: best providers in 2026](https://datacircle.dev/best-video-search-api)
- [Web scraping API: best providers in 2026](https://datacircle.dev/best-web-scraping-api)
- [Keyword research API: best providers in 2026](https://datacircle.dev/best-keyword-research-api)
- [Ranked keywords API: best providers in 2026](https://datacircle.dev/best-ranked-keywords-api)
- [Related keywords API: best providers in 2026](https://datacircle.dev/best-related-keywords-api)
- [Backlink API: best providers in 2026](https://datacircle.dev/best-backlink-api)
- [Domain authority API: best providers in 2026](https://datacircle.dev/best-domain-authority-api)
- [X (Twitter) profile API: best providers in 2026](https://datacircle.dev/best-x-twitter-profile-api)
- [X (Twitter) post API: best providers in 2026](https://datacircle.dev/best-x-twitter-post-api)
- [Instagram profile API: best providers in 2026](https://datacircle.dev/best-instagram-profile-api)
- [Instagram post API: best providers in 2026](https://datacircle.dev/best-instagram-post-api)
- [TikTok profile API: best providers in 2026](https://datacircle.dev/best-tiktok-profile-api)
- [TikTok video API: best providers in 2026](https://datacircle.dev/best-tiktok-video-api)
- [YouTube channel API: best providers in 2026](https://datacircle.dev/best-youtube-channel-api)
- [YouTube channel video API: best providers in 2026](https://datacircle.dev/best-youtube-channel-video-api)
- [Reddit profile API: best providers in 2026](https://datacircle.dev/best-reddit-profile-api)
- [Reddit post API: best providers in 2026](https://datacircle.dev/best-reddit-post-api)
- [Facebook page API: best providers in 2026](https://datacircle.dev/best-facebook-page-api)
- [Facebook post API: best providers in 2026](https://datacircle.dev/best-facebook-post-api)
- [Threads profile API: best providers in 2026](https://datacircle.dev/best-threads-profile-api)
- [Threads post API: best providers in 2026](https://datacircle.dev/best-threads-post-api)
- [Bluesky profile API: best providers in 2026](https://datacircle.dev/best-bluesky-profile-api)
- [Bluesky post API: best providers in 2026](https://datacircle.dev/best-bluesky-post-api)
- [Pinterest search API: best providers in 2026](https://datacircle.dev/best-pinterest-search-api)
- [Pinterest pin API: best providers in 2026](https://datacircle.dev/best-pinterest-pin-api)
- [Hacker News comment API: best providers in 2026](https://datacircle.dev/best-hacker-news-comment-api)
- [Twitch profile API: best providers in 2026](https://datacircle.dev/best-twitch-profile-api)
- [Twitch video API: best providers in 2026](https://datacircle.dev/best-twitch-video-api)
- [Twitch clip API: best providers in 2026](https://datacircle.dev/best-twitch-clip-api)
- [Snapchat profile API: best providers in 2026](https://datacircle.dev/best-snapchat-profile-api)
- [Truth Social post API: best providers in 2026](https://datacircle.dev/best-truth-social-post-api)
- [GitHub profile API: best providers in 2026](https://datacircle.dev/best-github-profile-api)
- [GitHub repository API: best providers in 2026](https://datacircle.dev/best-github-repository-api)
- [GitHub user repositories API: best providers in 2026](https://datacircle.dev/best-github-user-repository-api)
- [Weibo user posts API: best providers in 2026](https://datacircle.dev/best-weibo-user-post-api)
- [Xiaohongshu note API: best providers in 2026](https://datacircle.dev/best-xiaohongshu-note-api)
- [Facebook Ad Library API: best providers in 2026](https://datacircle.dev/best-facebook-ad-library-api)
- [LinkedIn Ad Library API: best providers in 2026](https://datacircle.dev/best-linkedin-ad-library-api)
- [G2 review API: best providers in 2026](https://datacircle.dev/best-g2-review-api)
- [Capterra review API: best providers in 2026](https://datacircle.dev/best-capterra-review-api)
- [Trustpilot review API: best providers in 2026](https://datacircle.dev/best-trustpilot-review-api)
- [Glassdoor review API: best providers in 2026](https://datacircle.dev/best-glassdoor-review-api)
- [App Store API: best providers in 2026](https://datacircle.dev/best-app-store-api)
- [App Store review API: best providers in 2026](https://datacircle.dev/best-app-store-review-api)
- [Google Play API: best providers in 2026](https://datacircle.dev/best-google-play-api)
- [Amazon product API: best providers in 2026](https://datacircle.dev/best-amazon-product-api)
- [Amazon search API: best providers in 2026](https://datacircle.dev/best-amazon-search-api)
- [Google Shopping product API: best providers in 2026](https://datacircle.dev/best-google-shopping-product-api)
- [Google Shopping search API: best providers in 2026](https://datacircle.dev/best-google-shopping-search-api)
- [Walmart product API: best providers in 2026](https://datacircle.dev/best-walmart-product-api)
- [Walmart search API: best providers in 2026](https://datacircle.dev/best-walmart-search-api)
- [eBay product API: best providers in 2026](https://datacircle.dev/best-ebay-product-api)
- [eBay search API: best providers in 2026](https://datacircle.dev/best-ebay-search-api)
- [TikTok Shop product API: best providers in 2026](https://datacircle.dev/best-tiktok-shop-product-api)
- [Facebook Marketplace listing API: best providers in 2026](https://datacircle.dev/best-facebook-marketplace-listing-api)
- [Facebook Marketplace search API: best providers in 2026](https://datacircle.dev/best-facebook-marketplace-search-api)
- [Zillow search API: best providers in 2026](https://datacircle.dev/best-zillow-search-api)
- [Zillow property API: best providers in 2026](https://datacircle.dev/best-zillow-property-api)
- [Realtor.com search API: best providers in 2026](https://datacircle.dev/best-realtor-com-search-api)
- [Realtor.com property API: best providers in 2026](https://datacircle.dev/best-realtor-com-property-api)
- [App Store search API: best providers in 2026](https://datacircle.dev/best-app-store-search-api)
- [ChatGPT scraper API: best providers in 2026](https://datacircle.dev/best-chatgpt-scraper-api)
- [Gemini scraper API: best providers in 2026](https://datacircle.dev/best-gemini-scraper-api)
- [Google AI Overview scraper API: best providers in 2026](https://datacircle.dev/best-google-ai-overview-scraper-api)
- [Business verification API: best providers in 2026](https://datacircle.dev/best-business-verification-api)

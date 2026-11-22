# GTM API benchmark results

Find the best GTM APIs

We benchmark all the GTM APIs and we put the results on our website.

This dataset holds our benchmark results from [datacircle.dev](https://datacircle.dev). Each row is one provider for one API we rank. A row gives the provider's Overall score, Accuracy score, price per 1,000 results and last test day. Each row links to the provider's plan on datacircle.dev and to the page that ranks that API. Each row shows the same numbers as our ranking pages. We refresh the files every week.

Today the files hold 4,322 rows: 1,457 providers across 164 APIs, last tested on 2026-11-21.

## Our benchmarks are public for now

We are launching Datacircle, so all our benchmarks are public for now. Each provider we test can see the inputs we sent, the right answers and the answers the provider gave. We trust providers not to game the benchmarks by tuning their APIs to pass our inputs and nothing else. With the data open, we and the providers we test can fix the benchmarks together. If you find a mistake in our results, tell us at wayne@datacircle.dev and we will fix the mistake.

## How we test

A script scores each answer, with no model and no person judging. It runs the same way for every provider of that API.

We score each plan on five parts and scale the total to 100. A plan's price weighs 40, its accuracy 40, its cost to get started 10, its bundled calls 10 and its performance 10.

We rank each API's providers in two groups. A plan in the top group gets at least half as many answers right as the most accurate plan for that API. We list the top group first, then the other plans, and we rank each group by Overall score. So a plan outside the top group can have a higher Overall score than a plan ranked above it.

## Columns

| Column | What the column holds |
| --- | --- |
| api | The API's name, as written in the title of the API's ranking page |
| rank | The provider's rank on the API's ranking page: the top group first, then the other plans, each by Overall score |
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
| [LinkedIn profile API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-api) | Reverse Contact | 77.2 | $0.15 per 1,000 profiles | [122 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-api.md), [waynehamadi/best-linkedin-profile-api](https://github.com/waynehamadi/best-linkedin-profile-api) |
| [Email finder API: best providers in 2026](https://datacircle.dev/best-email-finder-api) | Emelia | 76.4 | $4.99 per 1,000 emails | [143 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-email-finder-api.md), [waynehamadi/best-email-finder-api](https://github.com/waynehamadi/best-email-finder-api) |
| [Email validation API: best providers in 2026](https://datacircle.dev/best-email-verification-api) | Validemail.co | 82.4 |  | [256 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-email-verification-api.md), [waynehamadi/best-email-verification-api](https://github.com/waynehamadi/best-email-verification-api) |
| [Phone finder API: best providers in 2026](https://datacircle.dev/best-phone-finder-api) | MillionPhones | 68.3 | $75.00 per 1,000 numbers | [57 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-phone-finder-api.md) |
| [LinkedIn company data API: best providers in 2026](https://datacircle.dev/best-linkedin-company-data-api) | DataForB2B | 85 | $0.10 per 1,000 companies | [85 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-company-data-api.md) |
| [Company headcount API: best providers in 2026](https://datacircle.dev/best-company-headcount-api) | Scrappa | 86.8 | $0.30 per 1,000 companies | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-headcount-api.md) |
| [Phone validation API: best providers in 2026](https://datacircle.dev/best-phone-validation-api) | Trestle | 61.2 | $15.00 per 1,000 numbers | [70 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-phone-validation-api.md), [waynehamadi/best-phone-validation-api](https://github.com/waynehamadi/best-phone-validation-api) |
| [WhatsApp number check API: best providers in 2026](https://datacircle.dev/best-whatsapp-number-check-api) | NumRadar | 74.4 | $0.93 per 1,000 numbers | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-whatsapp-number-check-api.md) |
| [Do-not-call check API: best providers in 2026](https://datacircle.dev/best-do-not-call-check-api) | TPSCheck | 71.6 | $0.53 per 1,000 numbers | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-do-not-call-check-api.md) |
| [LinkedIn post comment API: best providers in 2026](https://datacircle.dev/best-linkedin-post-comment-api) | Fetchin | 73.5 | $0.01 per 1,000 comments | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-comment-api.md) |
| [LinkedIn post reaction API: best providers in 2026](https://datacircle.dev/best-linkedin-post-reaction-api) | Fetchin | 76.9 | $0.01 per 1,000 reactions | [14 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-reaction-api.md) |
| [Similar people API: best providers in 2026](https://datacircle.dev/best-similar-people-api) | Reverse Contact | 49 | $0.15 per 1,000 people | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-similar-people-api.md) |
| [Similar companies API: best providers in 2026](https://datacircle.dev/best-similar-companies-api) | ScrapeAtlas | 65.6 | $0.019 per 1,000 companies | [22 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-similar-companies-api.md) |
| [Tech stack API: best providers in 2026](https://datacircle.dev/best-tech-stack-api) | JobsPipe | 70 | $1.49 per 1,000 companies | [56 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tech-stack-api.md) |
| [Company job count API: best providers in 2026](https://datacircle.dev/best-company-job-count-api) | Up2Data | 74.4 | $2.00 per 1,000 companies | [2 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-job-count-api.md) |
| [LinkedIn profile post API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-post-api) | Fetchin | 75.4 | $0.01 per 1,000 posts | [19 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-post-api.md) |
| [LinkedIn company post API: best providers in 2026](https://datacircle.dev/best-linkedin-company-post-api) | Tapline | 83.7 | $0.013 per 1,000 posts | [31 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-company-post-api.md) |
| [Company funding API: best providers in 2026](https://datacircle.dev/best-company-funding-api) | gBizINFO | 78.7 | $0.00 per 1,000 companies | [29 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-funding-api.md) |
| [Company job openings API: best providers in 2026](https://datacircle.dev/best-company-open-jobs-api) | freehire | 72.2 |  | [45 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-open-jobs-api.md) |
| [LinkedIn people search API: best providers in 2026](https://datacircle.dev/best-linkedin-people-search-api) | DataForB2B | 80.8 | $0.075 per 1,000 people | [23 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-people-search-api.md) |
| [LinkedIn company search API: best providers in 2026](https://datacircle.dev/best-linkedin-company-search-api) | Up2Data | 89.6 | $0.08 per 1,000 companies | [14 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-company-search-api.md), [waynehamadi/best-linkedin-company-search-api](https://github.com/waynehamadi/best-linkedin-company-search-api) |
| [LinkedIn job search API: best providers in 2026](https://datacircle.dev/best-linkedin-job-search-api) | Litescrape | 86.3 | $0.015 per 1,000 jobs | [31 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-job-search-api.md), [waynehamadi/best-linkedin-job-search-api](https://github.com/waynehamadi/best-linkedin-job-search-api) |
| [Reverse email lookup API: best providers in 2026](https://datacircle.dev/best-reverse-email-lookup-api) | GetProspect | 85.6 | $7.98 per 1,000 people | [43 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reverse-email-lookup-api.md), [waynehamadi/best-reverse-email-lookup-api](https://github.com/waynehamadi/best-reverse-email-lookup-api) |
| [LinkedIn post search API: best providers in 2026](https://datacircle.dev/best-linkedin-post-search-api) | Scrappa | 84.9 | $0.015 per 1,000 posts | [29 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-search-api.md) |
| [LinkedIn post details API: best providers in 2026](https://datacircle.dev/best-linkedin-post-details-api) | Scrappa | 77.2 | $0.30 per 1,000 posts | [31 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-details-api.md) |
| [LinkedIn job details API: best providers in 2026](https://datacircle.dev/best-linkedin-job-details-api) | Scrappa | 68.8 | $0.30 per 1,000 jobs | [26 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-job-details-api.md) |
| [LinkedIn profile comment API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-comment-api) | HarvestAPI | 74.7 | $0.023 per 1,000 comments | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-comment-api.md) |
| [LinkedIn profile reaction API: best providers in 2026](https://datacircle.dev/best-linkedin-profile-reaction-api) | Fetchin | 73.8 | $0.01 per 1,000 reactions | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-profile-reaction-api.md) |
| [LinkedIn repost API: best providers in 2026](https://datacircle.dev/best-linkedin-post-repost-api) | Anysite | 68 | $0.16 per 1,000 reposts | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-post-repost-api.md) |
| [LinkedIn person recommendation API: best providers in 2026](https://datacircle.dev/best-linkedin-person-recommendation-api) | Social Fetch | 74.9 | $4.74 per 1,000 profiles | [2 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-person-recommendation-api.md) |
| [Similar job postings API: best providers in 2026](https://datacircle.dev/best-similar-jobs-api) | ReefAPI | 76.5 | $0.02 per 1,000 jobs | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-similar-jobs-api.md) |
| [LinkedIn person article API: best providers in 2026](https://datacircle.dev/best-linkedin-person-article-api) | Fetchin | 60.7 | $0.01 per 1,000 articles | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-person-article-api.md) |
| [Company enrichment API: best providers in 2026](https://datacircle.dev/best-company-enrichment-api) | GLEIF | 68.6 | $0.00 per 1,000 companies | [176 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-enrichment-api.md), [waynehamadi/best-company-enrichment-api](https://github.com/waynehamadi/best-company-enrichment-api) |
| [People lookup API: best providers in 2026](https://datacircle.dev/best-people-search-api) | GetProspect | 90.1 | $0 extra per 1,000. The $49 monthly price covers any number of people | [61 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-people-search-api.md) |
| [Company discovery API: best providers in 2026](https://datacircle.dev/best-company-discovery-api) | GetProspect | 92.7 | $0 extra per 1,000. The $49 monthly price covers any number of companies | [88 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-discovery-api.md), [waynehamadi/best-company-discovery-api](https://github.com/waynehamadi/best-company-discovery-api) |
| [Local business search API: best providers in 2026](https://datacircle.dev/best-local-business-search-api) | Bolt Scraper | 47.3 | $0.13 per 1,000 places | [94 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-local-business-search-api.md) |
| [Local business reviews API: best providers in 2026](https://datacircle.dev/best-local-business-reviews-api) | CrustAPI | 86.1 | $0.02 per 1,000 reviews | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-local-business-reviews-api.md) |
| [Address autocomplete API: best providers in 2026](https://datacircle.dev/best-address-autocomplete-api) | PostGrid | 87.4 | $0 extra per 1,000. The $84 monthly price covers any number of searches | [34 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-address-autocomplete-api.md) |
| [Job postings API: best providers in 2026](https://datacircle.dev/best-job-postings-api) | JobsByLevel | 90.7 | $0.00 per 1,000 jobs | [72 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-job-postings-api.md) |
| [Full job posting API: best providers in 2026](https://datacircle.dev/best-full-job-posting-api) | freehire | 87.3 |  | [51 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-full-job-posting-api.md) |
| [Job posting details API: best providers in 2026](https://datacircle.dev/best-job-posting-details-api) | Arbetsförmedlingen | 92 | $0.00 per 1,000 jobs | [40 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-job-posting-details-api.md) |
| [People enrichment API: best providers in 2026](https://datacircle.dev/best-people-enrichment-api) | LeadOcean | 81.1 | $0.017 per 1,000 people | [25 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-people-enrichment-api.md), [waynehamadi/best-people-enrichment-api](https://github.com/waynehamadi/best-people-enrichment-api) |
| [Leadership change API: best providers in 2026](https://datacircle.dev/best-leadership-change-api) | The Swarm | 35.5 | $10.00 per 1,000 changes | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-leadership-change-api.md) |
| [Company hierarchy API: best providers in 2026](https://datacircle.dev/best-company-hierarchy-api) | DiscoLike | 64.1 | $3.50 per 1,000 companies | [14 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-company-hierarchy-api.md) |
| [Web search API: best providers in 2026](https://datacircle.dev/best-web-search-api) | Clawifi | 79.4 | $0.60 per 1,000 searches | [99 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-web-search-api.md), [waynehamadi/best-web-search-api](https://github.com/waynehamadi/best-web-search-api) |
| [SERP API: best providers in 2026](https://datacircle.dev/best-serp-api) | SerpKite | 70.6 | $0.60 per 1,000 searches | [108 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-serp-api.md), [waynehamadi/best-serp-api](https://github.com/waynehamadi/best-serp-api) |
| [Search autocomplete API: best providers in 2026](https://datacircle.dev/best-search-autocomplete-api) | SERPHouse | 70.7 | $0.31 per 1,000 queries | [16 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-search-autocomplete-api.md) |
| [News API: best providers in 2026](https://datacircle.dev/best-news-api) | Alpaca | 90.3 |  | [116 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-news-api.md), [waynehamadi/best-news-api](https://github.com/waynehamadi/best-news-api) |
| [Image search API: best providers in 2026](https://datacircle.dev/best-image-search-api) | Kakao | 94.3 | $0.00 per 1,000 searches | [34 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-image-search-api.md) |
| [Reverse image search API: best providers in 2026](https://datacircle.dev/best-reverse-image-search-api) | Copyseeker | 56.4 | $9.00 per 1,000 searches | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reverse-image-search-api.md) |
| [Video search API: best providers in 2026](https://datacircle.dev/best-video-search-api) | Scrappa | 87.7 | $0.29 per 1,000 searches | [50 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-video-search-api.md) |
| [Web scraping API: best providers in 2026](https://datacircle.dev/best-web-scraping-api) | Scrape.land | 85.1 |  | [233 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-web-scraping-api.md), [waynehamadi/best-web-scraping-api](https://github.com/waynehamadi/best-web-scraping-api) |
| [Keyword research API: best providers in 2026](https://datacircle.dev/best-keyword-research-api) | DataForSEO | 55 | $0.12 per 1,000 keywords | [20 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-keyword-research-api.md), [waynehamadi/best-keyword-research-api](https://github.com/waynehamadi/best-keyword-research-api) |
| [Keyword ranking API: best providers in 2026](https://datacircle.dev/best-ranked-keywords-api) | DataForSEO | 57.2 | $0.12 per 1,000 keywords | [11 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ranked-keywords-api.md) |
| [Related keywords API: best providers in 2026](https://datacircle.dev/best-related-keywords-api) | DataForSEO | 60.6 | $0.12 per 1,000 keywords | [17 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-related-keywords-api.md), [waynehamadi/best-related-keywords-api](https://github.com/waynehamadi/best-related-keywords-api) |
| [Backlinks API: best providers in 2026](https://datacircle.dev/best-backlink-api) | DataForSEO | 59 | $0.036 per 1,000 backlinks | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-backlink-api.md), [waynehamadi/best-backlink-api](https://github.com/waynehamadi/best-backlink-api) |
| [Domain authority API: best providers in 2026](https://datacircle.dev/best-domain-authority-api) | AnyAPI | 43.1 | $4.95 per 1,000 domains | [19 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-domain-authority-api.md) |
| [Website traffic API: best providers in 2026](https://datacircle.dev/best-website-traffic-api) | ScraperCompany | 48.6 | $3.99 per 1,000 domains | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-website-traffic-api.md) |
| [Website contacts API: best providers in 2026](https://datacircle.dev/best-website-contacts-api) | Places Data API | 80.9 | $0.80 per 1,000 domains | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-website-contacts-api.md) |
| [Domain WHOIS API: best providers in 2026](https://datacircle.dev/best-domain-whois-api) | WhoisRequest | 96.9 | $0.00 per 1,000 domains | [57 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-domain-whois-api.md) |
| [IP company lookup API: best providers in 2026](https://datacircle.dev/best-ip-company-lookup-api) | IPKit | 94.1 | $0.00 per 1,000 IP addresses | [89 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ip-company-lookup-api.md) |
| [IP reputation API: best providers in 2026](https://datacircle.dev/best-ip-reputation-api) | CheckIP.me | 89 | $0.00 per 1,000 IP addresses | [28 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ip-reputation-api.md) |
| [Resume parsing API: best providers in 2026](https://datacircle.dev/best-resume-parsing-api) | HireLayer | 74.2 | $54.01 per 1,000 resumes | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-resume-parsing-api.md) |
| [IP geolocation API: best providers in 2026](https://datacircle.dev/best-ip-geolocation-api) | Apixies | 89.6 | $0.00 per 1,000 IP addresses | [43 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ip-geolocation-api.md) |
| [X (Twitter) profile API: best providers in 2026](https://datacircle.dev/best-x-twitter-profile-api) | lobstr.io | 65.6 | $0.50 per 1,000 profiles | [60 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-x-twitter-profile-api.md) |
| [X (Twitter) post API: best providers in 2026](https://datacircle.dev/best-x-twitter-post-api) | TwitterXAPI | 68.1 | $0.08 per 1,000 posts | [53 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-x-twitter-post-api.md) |
| [X (Twitter) post search API: best providers in 2026](https://datacircle.dev/best-x-twitter-post-search-api) | TwitterAPI.io | 66.6 | $0.15 per 1,000 posts | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-x-twitter-post-search-api.md) |
| [Instagram profile API: best providers in 2026](https://datacircle.dev/best-instagram-profile-api) | herascrape | 82.5 | $0.40 per 1,000 profiles | [56 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-instagram-profile-api.md) |
| [Instagram post API: best providers in 2026](https://datacircle.dev/best-instagram-post-api) | herascrape | 82 | $0.033 per 1,000 posts | [40 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-instagram-post-api.md) |
| [TikTok profile API: best providers in 2026](https://datacircle.dev/best-tiktok-profile-api) | Tapline | 85.3 | $0.20 per 1,000 profiles | [52 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-profile-api.md) |
| [TikTok video API: best providers in 2026](https://datacircle.dev/best-tiktok-video-api) | Litescrape | 80.5 | $0.0043 per 1,000 videos | [48 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-video-api.md) |
| [Instagram comment API: best providers in 2026](https://datacircle.dev/best-instagram-comment-api) | Tapline | 77.2 | $0.0083 per 1,000 comments | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-instagram-comment-api.md) |
| [TikTok video details API: best providers in 2026](https://datacircle.dev/best-tiktok-video-details-api) | ShortVidAPI | 77.7 | $0.40 per 1,000 videos | [15 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-video-details-api.md) |
| [TikTok comment API: best providers in 2026](https://datacircle.dev/best-tiktok-comment-api) | Scrappa | 81.9 | $0.0061 per 1,000 comments | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-comment-api.md) |
| [YouTube channel API: best providers in 2026](https://datacircle.dev/best-youtube-channel-api) | YouTube Data API (Google) | 90.9 | $0.00 per 1,000 channels | [48 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-youtube-channel-api.md) |
| [YouTube channel video API: best providers in 2026](https://datacircle.dev/best-youtube-channel-video-api) | ScrapeUnblocker | 85.6 | $0.0056 per 1,000 videos | [49 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-youtube-channel-video-api.md) |
| [YouTube video details API: best providers in 2026](https://datacircle.dev/best-youtube-video-details-api) | youtubescraperapi | 76.9 | $0.70 per 1,000 videos | [11 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-youtube-video-details-api.md) |
| [YouTube transcript API: best providers in 2026](https://datacircle.dev/best-youtube-transcript-api) | TranscriptFetch | 74.5 | $0.92 per 1,000 videos | [40 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-youtube-transcript-api.md) |
| [Reddit profile API: best providers in 2026](https://datacircle.dev/best-reddit-profile-api) | ReefAPI | 72.2 | $0.50 per 1,000 profiles | [19 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reddit-profile-api.md) |
| [Reddit post API: best providers in 2026](https://datacircle.dev/best-reddit-post-api) | Scrappa | 80.6 | $0.003 per 1,000 posts | [26 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-reddit-post-api.md) |
| [Facebook page API: best providers in 2026](https://datacircle.dev/best-facebook-page-api) | CoreClaw | 70.2 | $0.78 per 1,000 pages | [29 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-page-api.md) |
| [Facebook post API: best providers in 2026](https://datacircle.dev/best-facebook-post-api) | EveryInfra | 73.1 | $0.056 per 1,000 posts | [19 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-post-api.md) |
| [Threads profile API: best providers in 2026](https://datacircle.dev/best-threads-profile-api) | TrueScrape | 88.3 | $0.80 per 1,000 profiles | [15 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-threads-profile-api.md) |
| [Threads post API: best providers in 2026](https://datacircle.dev/best-threads-post-api) | CarryFeed | 75.2 | $0.00 per 1,000 posts | [16 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-threads-post-api.md) |
| [Bluesky profile API: best providers in 2026](https://datacircle.dev/best-bluesky-profile-api) | Bluesky | 90 | $0.00 per 1,000 profiles | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bluesky-profile-api.md) |
| [Bluesky post API: best providers in 2026](https://datacircle.dev/best-bluesky-post-api) | ProLevelMax | 75.4 | $0.003 per 1,000 posts | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bluesky-post-api.md) |
| [Telegram channel API: best providers in 2026](https://datacircle.dev/best-telegram-channel-api) | TrueScrape | 80.6 | $0.80 per 1,000 channels | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-telegram-channel-api.md) |
| [Telegram channel post API: best providers in 2026](https://datacircle.dev/best-telegram-channel-post-api) | TrueScrape | 73.7 | $0.04 per 1,000 posts | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-telegram-channel-post-api.md) |
| [Pinterest search API: best providers in 2026](https://datacircle.dev/best-pinterest-search-api) | ScrapeAtlas | 84.7 | $1.25 per 1,000 searches | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-pinterest-search-api.md) |
| [Pinterest pin API: best providers in 2026](https://datacircle.dev/best-pinterest-pin-api) | Scrappa | 73.4 | $0.30 per 1,000 pins | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-pinterest-pin-api.md) |
| [Pinterest board pin API: best providers in 2026](https://datacircle.dev/best-pinterest-board-pin-api) | Scrappa | 85 | $0.0012 per 1,000 pins | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-pinterest-board-pin-api.md) |
| [Pinterest user board API: best providers in 2026](https://datacircle.dev/best-pinterest-user-board-api) | ScrapeAtlas | 86.7 | $0.031 per 1,000 boards | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-pinterest-user-board-api.md) |
| [Hacker News search API: best providers in 2026](https://datacircle.dev/best-hacker-news-search-api) | Algolia | 90.9 | $0.00 per 1,000 searches | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-hacker-news-search-api.md) |
| [Hacker News comment API: best providers in 2026](https://datacircle.dev/best-hacker-news-comment-api) | Algolia | 90.7 | $0.00 per 1,000 comments | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-hacker-news-comment-api.md) |
| [Twitch profile API: best providers in 2026](https://datacircle.dev/best-twitch-profile-api) | TrueScrape | 77.7 | $0.80 per 1,000 profiles | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-twitch-profile-api.md) |
| [Twitch video API: best providers in 2026](https://datacircle.dev/best-twitch-video-api) | Scrappa | 79.4 | $0.0048 per 1,000 videos | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-twitch-video-api.md) |
| [Twitch clip API: best providers in 2026](https://datacircle.dev/best-twitch-clip-api) | Scrappa | 79.2 | $0.30 per 1,000 clips | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-twitch-clip-api.md) |
| [Kick API: best providers in 2026](https://datacircle.dev/best-kick-clip-api) | Scrappa | 89.1 | $0.24 per 1,000 clips | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-kick-clip-api.md) |
| [Snapchat profile API: best providers in 2026](https://datacircle.dev/best-snapchat-profile-api) | TrueScrape | 88.6 | $0.80 per 1,000 profiles | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-snapchat-profile-api.md) |
| [Truth Social profile API: best providers in 2026](https://datacircle.dev/best-truth-social-profile-api) | Scrappa | 96.2 | $0.30 per 1,000 profiles | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-truth-social-profile-api.md) |
| [Truth Social post API: best providers in 2026](https://datacircle.dev/best-truth-social-post-api) | Scrappa | 92.7 | $0.012 per 1,000 posts | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-truth-social-post-api.md) |
| [GitHub profile API: best providers in 2026](https://datacircle.dev/best-github-profile-api) | Scrappa | 85.7 | $0.29 per 1,000 profiles | [11 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-github-profile-api.md) |
| [GitHub repository API: best providers in 2026](https://datacircle.dev/best-github-repository-api) | Scrappa | 75.5 | $0.30 per 1,000 repositories | [19 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-github-repository-api.md) |
| [GitHub user repositories API: best providers in 2026](https://datacircle.dev/best-github-user-repository-api) | Scrappa | 95.2 | $0.003 per 1,000 repositories | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-github-user-repository-api.md) |
| [Douyin profile API: best providers in 2026](https://datacircle.dev/best-douyin-profile-api) | SocQ | 71.7 | $0.50 per 1,000 profiles | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-douyin-profile-api.md) |
| [Douyin user video API: best providers in 2026](https://datacircle.dev/best-douyin-user-video-api) | EveryInfra | 80.7 | $0.0056 per 1,000 videos | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-douyin-user-video-api.md) |
| [Douyin video API: best providers in 2026](https://datacircle.dev/best-douyin-video-api) | Scavio | 84.5 | $1.00 per 1,000 videos | [10 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-douyin-video-api.md) |
| [Weibo profile API: best providers in 2026](https://datacircle.dev/best-weibo-profile-api) | TikHub | 73.9 | $1.11 per 1,000 profiles | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-weibo-profile-api.md) |
| [Weibo user posts API: best providers in 2026](https://datacircle.dev/best-weibo-user-post-api) | DataXAPI | 60.3 | $0.08 per 1,000 posts | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-weibo-user-post-api.md) |
| [Weibo post API: best providers in 2026](https://datacircle.dev/best-weibo-post-api) | Scavio | 91.3 | $1.00 per 1,000 posts | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-weibo-post-api.md) |
| [Xiaohongshu profile API: best providers in 2026](https://datacircle.dev/best-xiaohongshu-profile-api) | EveryInfra | 84.1 | $5.56 per 1,000 profiles | [4 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-xiaohongshu-profile-api.md) |
| [Xiaohongshu user note API: best providers in 2026](https://datacircle.dev/best-xiaohongshu-user-note-api) | AnyAPI | 49.7 |  | [2 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-xiaohongshu-user-note-api.md) |
| [Xiaohongshu note API: best providers in 2026](https://datacircle.dev/best-xiaohongshu-note-api) | EveryInfra | 86.3 | $5.56 per 1,000 notes | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-xiaohongshu-note-api.md) |
| [Zhihu profile API: best providers in 2026](https://datacircle.dev/best-zhihu-profile-api) | AnyAPI | 76.3 | $1.20 per 1,000 profiles | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-zhihu-profile-api.md) |
| [Zhihu question answer API: best providers in 2026](https://datacircle.dev/best-zhihu-question-answer-api) | EveryInfra | 84.4 | $0.04 per 1,000 answers | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-zhihu-question-answer-api.md) |
| [Kuaishou user video API: best providers in 2026](https://datacircle.dev/best-kuaishou-user-video-api) | JustOneAPI | 46.7 |  | [2 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-kuaishou-user-video-api.md) |
| [Kuaishou video API: best providers in 2026](https://datacircle.dev/best-kuaishou-video-api) | ProLevelMax | 68.4 | $6.00 per 1,000 videos | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-kuaishou-video-api.md) |
| [Bilibili profile API: best providers in 2026](https://datacircle.dev/best-bilibili-profile-api) | AIsa | 75.7 | $0.63 per 1,000 profiles | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bilibili-profile-api.md) |
| [Bilibili user video API: best providers in 2026](https://datacircle.dev/best-bilibili-user-video-api) | Scrappa | 63.8 | $0.0061 per 1,000 videos | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bilibili-user-video-api.md) |
| [Bilibili video API: best providers in 2026](https://datacircle.dev/best-bilibili-video-api) | Scrappa | 64.6 | $0.30 per 1,000 videos | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bilibili-video-api.md) |
| [Facebook Ad Library API: best providers in 2026](https://datacircle.dev/best-facebook-ad-library-api) | Scrappa | 79.4 | $0.03 per 1,000 ads | [20 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-ad-library-api.md) |
| [Google Ads Transparency API: best providers in 2026](https://datacircle.dev/best-google-ads-transparency-api) | Scrappa | 88.5 | $0.003 per 1,000 ads | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-ads-transparency-api.md) |
| [LinkedIn Ad Library API: best providers in 2026](https://datacircle.dev/best-linkedin-ad-library-api) | Stophy | 70.9 | $0.05 per 1,000 ads | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-linkedin-ad-library-api.md) |
| [TikTok Ad Library API: best providers in 2026](https://datacircle.dev/best-tiktok-ad-library-api) | Stophy | 70.3 | $0.10 per 1,000 ads | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-ad-library-api.md) |
| [G2 API: best providers in 2026](https://datacircle.dev/best-g2-review-api) | Scrappa | 84.4 | $0.0095 per 1,000 reviews | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-g2-review-api.md) |
| [Capterra review API: best providers in 2026](https://datacircle.dev/best-capterra-review-api) | ScraperCompany | 61.6 | $0.08 per 1,000 reviews | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-capterra-review-api.md) |
| [Trustpilot API: best providers in 2026](https://datacircle.dev/best-trustpilot-review-api) | Scrappa | 93.4 | $0.003 per 1,000 reviews | [22 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-trustpilot-review-api.md) |
| [Glassdoor API: best providers in 2026](https://datacircle.dev/best-glassdoor-review-api) | Scrappa | 73.9 | $0.0095 per 1,000 reviews | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-glassdoor-review-api.md) |
| [App Store API: best providers in 2026](https://datacircle.dev/best-app-store-api) | Apple | 82.5 | $0.00 per 1,000 apps | [21 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-app-store-api.md) |
| [App Store review API: best providers in 2026](https://datacircle.dev/best-app-store-review-api) | EveryInfra | 79.5 | $0.0028 per 1,000 reviews | [15 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-app-store-review-api.md) |
| [Google Play API: best providers in 2026](https://datacircle.dev/best-google-play-api) | AppSkyline | 78.5 | $0.00 per 1,000 apps | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-play-api.md), [waynehamadi/best-google-play-api](https://github.com/waynehamadi/best-google-play-api) |
| [Google Play review API: best providers in 2026](https://datacircle.dev/best-google-play-review-api) | SignalShelf | 85.3 | $0.005 per 1,000 reviews | [13 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-play-review-api.md) |
| [Amazon product API: best providers in 2026](https://datacircle.dev/best-amazon-product-api) | Logimu | 71.3 | $0.16 per 1,000 products | [48 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-amazon-product-api.md), [waynehamadi/best-amazon-product-api](https://github.com/waynehamadi/best-amazon-product-api) |
| [Amazon search API: best providers in 2026](https://datacircle.dev/best-amazon-search-api) | Easyparser | 70.1 | $0.49 per 1,000 searches | [38 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-amazon-search-api.md) |
| [Amazon review API: best providers in 2026](https://datacircle.dev/best-amazon-review-api) | ReefAPI | 76.5 | $0.027 per 1,000 reviews | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-amazon-review-api.md) |
| [Google Shopping product API: best providers in 2026](https://datacircle.dev/best-google-shopping-product-api) | Litescrape | 72.9 | $0.15 per 1,000 products | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-shopping-product-api.md) |
| [Idealo product API: best providers in 2026](https://datacircle.dev/best-idealo-product-api) | PricePirate | 58.1 | $4.40 per 1,000 products | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-idealo-product-api.md) |
| [Google Shopping search API: best providers in 2026](https://datacircle.dev/best-google-shopping-search-api) | SerpKite | 74.9 | $0.60 per 1,000 searches | [22 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-shopping-search-api.md) |
| [Walmart product API: best providers in 2026](https://datacircle.dev/best-walmart-product-api) | ScrapeUnblocker | 74.9 | $0.76 per 1,000 products | [18 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-walmart-product-api.md) |
| [Walmart search API: best providers in 2026](https://datacircle.dev/best-walmart-search-api) | ScrapeUnblocker | 77 | $0.76 per 1,000 searches | [21 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-walmart-search-api.md) |
| [eBay product API: best providers in 2026](https://datacircle.dev/best-ebay-product-api) | Litescrape | 78.4 | $0.15 per 1,000 products | [17 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ebay-product-api.md) |
| [eBay search API: best providers in 2026](https://datacircle.dev/best-ebay-search-api) | ReefAPI | 59.3 | $0.50 per 1,000 searches | [17 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ebay-search-api.md) |
| [eBay sold listings API: best providers in 2026](https://datacircle.dev/best-ebay-sold-listings-api) | Trawl | 70.7 | $1.25 per 1,000 searches | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-ebay-sold-listings-api.md) |
| [TikTok Shop product API: best providers in 2026](https://datacircle.dev/best-tiktok-shop-product-api) | ScraperCompany | 68.2 | $1.60 per 1,000 products | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-shop-product-api.md) |
| [TikTok Shop search API: best providers in 2026](https://datacircle.dev/best-tiktok-shop-search-api) | ReefAPI | 61.6 | $0.50 per 1,000 searches | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-tiktok-shop-search-api.md) |
| [E-commerce product API: best providers in 2026](https://datacircle.dev/best-e-commerce-product-api) | Zyte | 59.5 |  | [2 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-e-commerce-product-api.md) |
| [Facebook Marketplace listing API: best providers in 2026](https://datacircle.dev/best-facebook-marketplace-listing-api) | SocialAPIs | 67.1 | $1.49 per 1,000 listings | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-marketplace-listing-api.md) |
| [Facebook Marketplace search API: best providers in 2026](https://datacircle.dev/best-facebook-marketplace-search-api) | ReefAPI | 64.5 | $1.50 per 1,000 searches | [9 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-facebook-marketplace-search-api.md) |
| [Zillow search API: best providers in 2026](https://datacircle.dev/best-zillow-search-api) | PerceptLayer | 75 | $0.80 per 1,000 searches | [15 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-zillow-search-api.md) |
| [Zillow property details API: best providers in 2026](https://datacircle.dev/best-zillow-property-api) | ScrapeUnblocker | 74.2 | $0.76 per 1,000 properties | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-zillow-property-api.md) |
| [Redfin search API: best providers in 2026](https://datacircle.dev/best-redfin-search-api) | OpenWeb Ninja | 64.7 | $0.75 per 1,000 searches | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-redfin-search-api.md) |
| [Redfin property API: best providers in 2026](https://datacircle.dev/best-redfin-property-api) | Litescrape | 78.6 | $0.15 per 1,000 properties | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-redfin-property-api.md) |
| [Realtor.com search API: best providers in 2026](https://datacircle.dev/best-realtor-com-search-api) | ReefAPI | 72 | $1.00 per 1,000 searches | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-realtor-com-search-api.md) |
| [Realtor.com property API: best providers in 2026](https://datacircle.dev/best-realtor-com-property-api) | Scrappa | 88 | $0.24 per 1,000 properties | [5 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-realtor-com-property-api.md) |
| [Property records API: best providers in 2026](https://datacircle.dev/best-property-records-api) | Realie | 70.3 | $11.67 per 1,000 addresses | [6 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-property-records-api.md) |
| [Rent estimate API: best providers in 2026](https://datacircle.dev/best-rent-estimate-api) | Zillapi | 86.5 | $5.00 per 1,000 addresses | [3 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-rent-estimate-api.md) |
| [App Store search API: best providers in 2026](https://datacircle.dev/best-app-store-search-api) | Apple | 79 | $0.00 per 1,000 searches | [20 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-app-store-search-api.md) |
| [Google Play search API: best providers in 2026](https://datacircle.dev/best-google-play-search-api) | Scrappa | 69.6 | $0.30 per 1,000 searches | [12 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-play-search-api.md) |
| [ChatGPT scraper API: best providers in 2026](https://datacircle.dev/best-chatgpt-scraper-api) | Scrappa | 75.1 | $0.30 per 1,000 answers | [17 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-chatgpt-scraper-api.md) |
| [Perplexity scraper API: best providers in 2026](https://datacircle.dev/best-perplexity-scraper-api) | BedrockTap | 75.6 | $15.15 per 1,000 answers | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-perplexity-scraper-api.md) |
| [Gemini scraper API: best providers in 2026](https://datacircle.dev/best-gemini-scraper-api) | Scrappa | 84.8 | $0.30 per 1,000 answers | [8 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-gemini-scraper-api.md) |
| [Bing Copilot scraper API: best providers in 2026](https://datacircle.dev/best-bing-copilot-scraper-api) | Rankshift | 60.7 | $42.36 per 1,000 answers | [7 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-bing-copilot-scraper-api.md) |
| [Google AI Overview scraper API: best providers in 2026](https://datacircle.dev/best-google-ai-overview-scraper-api) | Litescrape | 86.4 | $0.15 per 1,000 answers | [11 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-ai-overview-scraper-api.md) |
| [Google AI Mode scraper API: best providers in 2026](https://datacircle.dev/best-google-ai-mode-scraper-api) | ScrapeUnblocker | 67.4 | $0.76 per 1,000 answers | [15 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-google-ai-mode-scraper-api.md) |
| [Business verification API: best providers in 2026](https://datacircle.dev/best-business-verification-api) | GovFiles | 76.5 | $10.00 per 1,000 companies | [16 ranked](https://github.com/waynehamadi/gtm-api-benchmarks/blob/main/apis/best-business-verification-api.md) |

## Best GTM APIs

- [Best LinkedIn API providers in 2026](https://datacircle.dev/best-linkedin-api)
- [Best Phone API providers in 2026](https://datacircle.dev/best-phone-api)
- [Best Email API providers in 2026](https://datacircle.dev/best-email-api)
- [Best X (Twitter) API providers in 2026](https://datacircle.dev/best-x-api)
- [Best Instagram API providers in 2026](https://datacircle.dev/best-instagram-api)
- [Best Reddit API providers in 2026](https://datacircle.dev/best-reddit-api)
- [Best Threads API providers in 2026](https://datacircle.dev/best-threads-api)
- [Best Pinterest API providers in 2026](https://datacircle.dev/best-pinterest-api)
- [Best SEO API providers in 2026](https://datacircle.dev/best-seo-api)
- [Best Data enrichment API providers in 2026](https://datacircle.dev/best-data-enrichment-api)
- [Best Amazon API providers in 2026](https://datacircle.dev/best-amazon-api)
- [Best Review API providers in 2026](https://datacircle.dev/best-review-api)
- [Best Zillow API providers in 2026](https://datacircle.dev/best-zillow-api)
- [Best Realtor.com API providers in 2026](https://datacircle.dev/best-realtor-com-api)
- [Best Redfin API providers in 2026](https://datacircle.dev/best-redfin-api)
- [Best Real estate API providers in 2026](https://datacircle.dev/best-real-estate-api)
- [Best YouTube API providers in 2026](https://datacircle.dev/best-youtube-api)
- [Best TikTok API providers in 2026](https://datacircle.dev/best-tiktok-api)
- [Best Facebook API providers in 2026](https://datacircle.dev/best-facebook-api)
- [Best eBay API providers in 2026](https://datacircle.dev/best-ebay-api)
- [Best Walmart API providers in 2026](https://datacircle.dev/best-walmart-api)
- [Best Google Shopping API providers in 2026](https://datacircle.dev/best-google-shopping-api)
- [Best GitHub API providers in 2026](https://datacircle.dev/best-github-api)
- [Best Twitch API providers in 2026](https://datacircle.dev/best-twitch-api)
- [Best Telegram API providers in 2026](https://datacircle.dev/best-telegram-api)
- [Best Bluesky API providers in 2026](https://datacircle.dev/best-bluesky-api)
- [Best Truth Social API providers in 2026](https://datacircle.dev/best-truth-social-api)
- [Best Hacker News API providers in 2026](https://datacircle.dev/best-hacker-news-api)
- [Best Xiaohongshu API providers in 2026](https://datacircle.dev/best-xiaohongshu-api)
- [Best Weibo API providers in 2026](https://datacircle.dev/best-weibo-api)
- [Best Douyin API providers in 2026](https://datacircle.dev/best-douyin-api)
- [Best Kuaishou API providers in 2026](https://datacircle.dev/best-kuaishou-api)
- [Best Zhihu API providers in 2026](https://datacircle.dev/best-zhihu-api)
- [Best Bilibili API providers in 2026](https://datacircle.dev/best-bilibili-api)
- [Best LinkedIn profile API providers in 2026](https://datacircle.dev/best-linkedin-profile-api)
- [Best Email finder API providers in 2026](https://datacircle.dev/best-email-finder-api)
- [Most accurate email finder API in 2026](https://datacircle.dev/most-accurate-email-finder-api)
- [Best Email validation API providers in 2026](https://datacircle.dev/best-email-verification-api)
- [Most accurate email verification API in 2026](https://datacircle.dev/most-accurate-email-verification-api)
- [Best Phone finder API providers in 2026](https://datacircle.dev/best-phone-finder-api)
- [Most accurate phone finder API in 2026](https://datacircle.dev/most-accurate-phone-finder-api)
- [Best LinkedIn company data API providers in 2026](https://datacircle.dev/best-linkedin-company-data-api)
- [Best Company headcount API providers in 2026](https://datacircle.dev/best-company-headcount-api)
- [Most accurate company headcount API in 2026](https://datacircle.dev/most-accurate-company-headcount-api)
- [Best Phone validation API providers in 2026](https://datacircle.dev/best-phone-validation-api)
- [Most accurate phone validation API in 2026](https://datacircle.dev/most-accurate-phone-validation-api)
- [Best WhatsApp number check API providers in 2026](https://datacircle.dev/best-whatsapp-number-check-api)
- [Best Do-not-call check API providers in 2026](https://datacircle.dev/best-do-not-call-check-api)
- [Best LinkedIn post comment API providers in 2026](https://datacircle.dev/best-linkedin-post-comment-api)
- [Best LinkedIn post reaction API providers in 2026](https://datacircle.dev/best-linkedin-post-reaction-api)
- [Best Similar people API providers in 2026](https://datacircle.dev/best-similar-people-api)
- [Best Similar companies API providers in 2026](https://datacircle.dev/best-similar-companies-api)
- [Best Tech stack API providers in 2026](https://datacircle.dev/best-tech-stack-api)
- [Best Company job count API providers in 2026](https://datacircle.dev/best-company-job-count-api)
- [Best LinkedIn profile post API providers in 2026](https://datacircle.dev/best-linkedin-profile-post-api)
- [Best LinkedIn company post API providers in 2026](https://datacircle.dev/best-linkedin-company-post-api)
- [Best Company funding API providers in 2026](https://datacircle.dev/best-company-funding-api)
- [Best Company job openings API providers in 2026](https://datacircle.dev/best-company-open-jobs-api)
- [Best LinkedIn people search API providers in 2026](https://datacircle.dev/best-linkedin-people-search-api)
- [Best LinkedIn company search API providers in 2026](https://datacircle.dev/best-linkedin-company-search-api)
- [Best LinkedIn job search API providers in 2026](https://datacircle.dev/best-linkedin-job-search-api)
- [Best Reverse email lookup API providers in 2026](https://datacircle.dev/best-reverse-email-lookup-api)
- [Most accurate reverse email lookup API in 2026](https://datacircle.dev/most-accurate-reverse-email-lookup-api)
- [Best LinkedIn post search API providers in 2026](https://datacircle.dev/best-linkedin-post-search-api)
- [Best LinkedIn post details API providers in 2026](https://datacircle.dev/best-linkedin-post-details-api)
- [Best LinkedIn job details API providers in 2026](https://datacircle.dev/best-linkedin-job-details-api)
- [Best LinkedIn profile comment API providers in 2026](https://datacircle.dev/best-linkedin-profile-comment-api)
- [Best LinkedIn profile reaction API providers in 2026](https://datacircle.dev/best-linkedin-profile-reaction-api)
- [Best LinkedIn repost API providers in 2026](https://datacircle.dev/best-linkedin-post-repost-api)
- [Best LinkedIn person recommendation API providers in 2026](https://datacircle.dev/best-linkedin-person-recommendation-api)
- [Best Similar job postings API providers in 2026](https://datacircle.dev/best-similar-jobs-api)
- [Best LinkedIn person article API providers in 2026](https://datacircle.dev/best-linkedin-person-article-api)
- [Best Company enrichment API providers in 2026](https://datacircle.dev/best-company-enrichment-api)
- [Best People lookup API providers in 2026](https://datacircle.dev/best-people-search-api)
- [Best Company discovery API providers in 2026](https://datacircle.dev/best-company-discovery-api)
- [Best Local business search API providers in 2026](https://datacircle.dev/best-local-business-search-api)
- [Best Local business reviews API providers in 2026](https://datacircle.dev/best-local-business-reviews-api)
- [Best Address autocomplete API providers in 2026](https://datacircle.dev/best-address-autocomplete-api)
- [Best Job postings API providers in 2026](https://datacircle.dev/best-job-postings-api)
- [Best Full job posting API providers in 2026](https://datacircle.dev/best-full-job-posting-api)
- [Best Job posting details API providers in 2026](https://datacircle.dev/best-job-posting-details-api)
- [Best People enrichment API providers in 2026](https://datacircle.dev/best-people-enrichment-api)
- [Best Leadership change API providers in 2026](https://datacircle.dev/best-leadership-change-api)
- [Best Company hierarchy API providers in 2026](https://datacircle.dev/best-company-hierarchy-api)
- [Best Web search API providers in 2026](https://datacircle.dev/best-web-search-api)
- [Best SERP API providers in 2026](https://datacircle.dev/best-serp-api)
- [Best Search autocomplete API providers in 2026](https://datacircle.dev/best-search-autocomplete-api)
- [Best News API providers in 2026](https://datacircle.dev/best-news-api)
- [Best Image search API providers in 2026](https://datacircle.dev/best-image-search-api)
- [Best Reverse image search API providers in 2026](https://datacircle.dev/best-reverse-image-search-api)
- [Best Video search API providers in 2026](https://datacircle.dev/best-video-search-api)
- [Best Web scraping API providers in 2026](https://datacircle.dev/best-web-scraping-api)
- [Best Keyword research API providers in 2026](https://datacircle.dev/best-keyword-research-api)
- [Best Keyword ranking API providers in 2026](https://datacircle.dev/best-ranked-keywords-api)
- [Best Related keywords API providers in 2026](https://datacircle.dev/best-related-keywords-api)
- [Best Backlinks API providers in 2026](https://datacircle.dev/best-backlink-api)
- [Best Domain authority API providers in 2026](https://datacircle.dev/best-domain-authority-api)
- [Best Website traffic API providers in 2026](https://datacircle.dev/best-website-traffic-api)
- [Best Website contacts API providers in 2026](https://datacircle.dev/best-website-contacts-api)
- [Best Domain WHOIS API providers in 2026](https://datacircle.dev/best-domain-whois-api)
- [Best IP company lookup API providers in 2026](https://datacircle.dev/best-ip-company-lookup-api)
- [Best IP reputation API providers in 2026](https://datacircle.dev/best-ip-reputation-api)
- [Best Resume parsing API providers in 2026](https://datacircle.dev/best-resume-parsing-api)
- [Best IP geolocation API providers in 2026](https://datacircle.dev/best-ip-geolocation-api)
- [Best X (Twitter) profile API providers in 2026](https://datacircle.dev/best-x-twitter-profile-api)
- [Best X (Twitter) post API providers in 2026](https://datacircle.dev/best-x-twitter-post-api)
- [Best X (Twitter) post search API providers in 2026](https://datacircle.dev/best-x-twitter-post-search-api)
- [Best Instagram profile API providers in 2026](https://datacircle.dev/best-instagram-profile-api)
- [Best Instagram post API providers in 2026](https://datacircle.dev/best-instagram-post-api)
- [Best TikTok profile API providers in 2026](https://datacircle.dev/best-tiktok-profile-api)
- [Best TikTok video API providers in 2026](https://datacircle.dev/best-tiktok-video-api)
- [Best Instagram comment API providers in 2026](https://datacircle.dev/best-instagram-comment-api)
- [Best TikTok video details API providers in 2026](https://datacircle.dev/best-tiktok-video-details-api)
- [Best TikTok comment API providers in 2026](https://datacircle.dev/best-tiktok-comment-api)
- [Best YouTube channel API providers in 2026](https://datacircle.dev/best-youtube-channel-api)
- [Best YouTube channel video API providers in 2026](https://datacircle.dev/best-youtube-channel-video-api)
- [Best YouTube video details API providers in 2026](https://datacircle.dev/best-youtube-video-details-api)
- [Best YouTube transcript API providers in 2026](https://datacircle.dev/best-youtube-transcript-api)
- [Best Reddit profile API providers in 2026](https://datacircle.dev/best-reddit-profile-api)
- [Best Reddit post API providers in 2026](https://datacircle.dev/best-reddit-post-api)
- [Best Facebook page API providers in 2026](https://datacircle.dev/best-facebook-page-api)
- [Best Facebook post API providers in 2026](https://datacircle.dev/best-facebook-post-api)
- [Best Threads profile API providers in 2026](https://datacircle.dev/best-threads-profile-api)
- [Best Threads post API providers in 2026](https://datacircle.dev/best-threads-post-api)
- [Best Bluesky profile API providers in 2026](https://datacircle.dev/best-bluesky-profile-api)
- [Best Bluesky post API providers in 2026](https://datacircle.dev/best-bluesky-post-api)
- [Best Telegram channel API providers in 2026](https://datacircle.dev/best-telegram-channel-api)
- [Best Telegram channel post API providers in 2026](https://datacircle.dev/best-telegram-channel-post-api)
- [Best Pinterest search API providers in 2026](https://datacircle.dev/best-pinterest-search-api)
- [Best Pinterest pin API providers in 2026](https://datacircle.dev/best-pinterest-pin-api)
- [Best Pinterest board pin API providers in 2026](https://datacircle.dev/best-pinterest-board-pin-api)
- [Best Pinterest user board API providers in 2026](https://datacircle.dev/best-pinterest-user-board-api)
- [Best Hacker News search API providers in 2026](https://datacircle.dev/best-hacker-news-search-api)
- [Best Hacker News comment API providers in 2026](https://datacircle.dev/best-hacker-news-comment-api)
- [Best Twitch profile API providers in 2026](https://datacircle.dev/best-twitch-profile-api)
- [Best Twitch video API providers in 2026](https://datacircle.dev/best-twitch-video-api)
- [Best Twitch clip API providers in 2026](https://datacircle.dev/best-twitch-clip-api)
- [Best Kick API providers in 2026](https://datacircle.dev/best-kick-clip-api)
- [Best Snapchat profile API providers in 2026](https://datacircle.dev/best-snapchat-profile-api)
- [Best Truth Social profile API providers in 2026](https://datacircle.dev/best-truth-social-profile-api)
- [Best Truth Social post API providers in 2026](https://datacircle.dev/best-truth-social-post-api)
- [Best GitHub profile API providers in 2026](https://datacircle.dev/best-github-profile-api)
- [Best GitHub repository API providers in 2026](https://datacircle.dev/best-github-repository-api)
- [Best GitHub user repositories API providers in 2026](https://datacircle.dev/best-github-user-repository-api)
- [Best Douyin profile API providers in 2026](https://datacircle.dev/best-douyin-profile-api)
- [Best Douyin user video API providers in 2026](https://datacircle.dev/best-douyin-user-video-api)
- [Best Douyin video API providers in 2026](https://datacircle.dev/best-douyin-video-api)
- [Best Weibo profile API providers in 2026](https://datacircle.dev/best-weibo-profile-api)
- [Best Weibo user posts API providers in 2026](https://datacircle.dev/best-weibo-user-post-api)
- [Best Weibo post API providers in 2026](https://datacircle.dev/best-weibo-post-api)
- [Best Xiaohongshu profile API providers in 2026](https://datacircle.dev/best-xiaohongshu-profile-api)
- [Best Xiaohongshu user note API providers in 2026](https://datacircle.dev/best-xiaohongshu-user-note-api)
- [Best Xiaohongshu note API providers in 2026](https://datacircle.dev/best-xiaohongshu-note-api)
- [Best Zhihu profile API providers in 2026](https://datacircle.dev/best-zhihu-profile-api)
- [Best Zhihu question answer API providers in 2026](https://datacircle.dev/best-zhihu-question-answer-api)
- [Best Kuaishou user video API providers in 2026](https://datacircle.dev/best-kuaishou-user-video-api)
- [Best Kuaishou video API providers in 2026](https://datacircle.dev/best-kuaishou-video-api)
- [Best Bilibili profile API providers in 2026](https://datacircle.dev/best-bilibili-profile-api)
- [Best Bilibili user video API providers in 2026](https://datacircle.dev/best-bilibili-user-video-api)
- [Best Bilibili video API providers in 2026](https://datacircle.dev/best-bilibili-video-api)
- [Best Facebook Ad Library API providers in 2026](https://datacircle.dev/best-facebook-ad-library-api)
- [Best Google Ads Transparency API providers in 2026](https://datacircle.dev/best-google-ads-transparency-api)
- [Best LinkedIn Ad Library API providers in 2026](https://datacircle.dev/best-linkedin-ad-library-api)
- [Best TikTok Ad Library API providers in 2026](https://datacircle.dev/best-tiktok-ad-library-api)
- [Best G2 API providers in 2026](https://datacircle.dev/best-g2-review-api)
- [Best Capterra review API providers in 2026](https://datacircle.dev/best-capterra-review-api)
- [Best Trustpilot API providers in 2026](https://datacircle.dev/best-trustpilot-review-api)
- [Best Glassdoor API providers in 2026](https://datacircle.dev/best-glassdoor-review-api)
- [Best App Store API providers in 2026](https://datacircle.dev/best-app-store-api)
- [Best App Store review API providers in 2026](https://datacircle.dev/best-app-store-review-api)
- [Best Google Play API providers in 2026](https://datacircle.dev/best-google-play-api)
- [Best Google Play review API providers in 2026](https://datacircle.dev/best-google-play-review-api)
- [Best Amazon product API providers in 2026](https://datacircle.dev/best-amazon-product-api)
- [Best Amazon search API providers in 2026](https://datacircle.dev/best-amazon-search-api)
- [Best Amazon review API providers in 2026](https://datacircle.dev/best-amazon-review-api)
- [Best Google Shopping product API providers in 2026](https://datacircle.dev/best-google-shopping-product-api)
- [Best Idealo product API providers in 2026](https://datacircle.dev/best-idealo-product-api)
- [Best Google Shopping search API providers in 2026](https://datacircle.dev/best-google-shopping-search-api)
- [Best Walmart product API providers in 2026](https://datacircle.dev/best-walmart-product-api)
- [Best Walmart search API providers in 2026](https://datacircle.dev/best-walmart-search-api)
- [Best eBay product API providers in 2026](https://datacircle.dev/best-ebay-product-api)
- [Best eBay search API providers in 2026](https://datacircle.dev/best-ebay-search-api)
- [Best eBay sold listings API providers in 2026](https://datacircle.dev/best-ebay-sold-listings-api)
- [Best TikTok Shop product API providers in 2026](https://datacircle.dev/best-tiktok-shop-product-api)
- [Best TikTok Shop search API providers in 2026](https://datacircle.dev/best-tiktok-shop-search-api)
- [Best E-commerce product API providers in 2026](https://datacircle.dev/best-e-commerce-product-api)
- [Best Facebook Marketplace listing API providers in 2026](https://datacircle.dev/best-facebook-marketplace-listing-api)
- [Best Facebook Marketplace search API providers in 2026](https://datacircle.dev/best-facebook-marketplace-search-api)
- [Best Zillow search API providers in 2026](https://datacircle.dev/best-zillow-search-api)
- [Best Zillow property details API providers in 2026](https://datacircle.dev/best-zillow-property-api)
- [Best Redfin search API providers in 2026](https://datacircle.dev/best-redfin-search-api)
- [Best Redfin property API providers in 2026](https://datacircle.dev/best-redfin-property-api)
- [Best Realtor.com search API providers in 2026](https://datacircle.dev/best-realtor-com-search-api)
- [Best Realtor.com property API providers in 2026](https://datacircle.dev/best-realtor-com-property-api)
- [Best Property records API providers in 2026](https://datacircle.dev/best-property-records-api)
- [Best Rent estimate API providers in 2026](https://datacircle.dev/best-rent-estimate-api)
- [Best App Store search API providers in 2026](https://datacircle.dev/best-app-store-search-api)
- [Best Google Play search API providers in 2026](https://datacircle.dev/best-google-play-search-api)
- [Best ChatGPT scraper API providers in 2026](https://datacircle.dev/best-chatgpt-scraper-api)
- [Best Perplexity scraper API providers in 2026](https://datacircle.dev/best-perplexity-scraper-api)
- [Best Gemini scraper API providers in 2026](https://datacircle.dev/best-gemini-scraper-api)
- [Best Bing Copilot scraper API providers in 2026](https://datacircle.dev/best-bing-copilot-scraper-api)
- [Best Google AI Overview scraper API providers in 2026](https://datacircle.dev/best-google-ai-overview-scraper-api)
- [Best Google AI Mode scraper API providers in 2026](https://datacircle.dev/best-google-ai-mode-scraper-api)
- [Best Business verification API providers in 2026](https://datacircle.dev/best-business-verification-api)

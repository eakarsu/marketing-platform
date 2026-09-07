# Feature status — Marketing, brand & reputation

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 311 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 11 | 0 | Native records/view |
| Activity & audit trail | audit | 5 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Partner agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tracking link code registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Click event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order attribution | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attribution window control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Coupon poaching detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Return cancellation reversal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commission tier calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance bonus | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Self-referral detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud traffic scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner statement audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment correction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner campaign analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program and agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner and dealer registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fund accrual calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Eligibility and activity rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign preapproval | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proof-of-performance collection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice and payment evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand compliance validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim deadline tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim preparation and submission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vendor rejection management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resubmission workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit and payment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expiring-fund alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Partner utilization analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign ROI and recovery analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency and scope library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign and media-plan registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insertion-order ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Platform delivery reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate and CPM validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Underdelivery detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invalid traffic and viewability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency fee recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technology fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rebate and incentive reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit and makegood control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice exception workbench | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agency platform dispute | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Payment and recovery reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign agency and channel analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insertion order library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign creative registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DSP log ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SSP log ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bid request matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Impression event matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Clearing price reconstruction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| DSP fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| SSP fee calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Verification fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invalid traffic adjustment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Invoice reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply-path exception workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign publisher analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retail media agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign order ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience targeting evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Impression delivery validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Click event reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate card calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Budget pacing control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Attributed sales methodology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incrementality evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Under-delivery makegood | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice campaign matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retailer dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network campaign analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| A/B Testing Framework | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Brand Voice Checker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance Benchmarking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Language Translator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience Sentiment Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Copy Template Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Visual + Copy Pairing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Copy Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign Workspace | records | 6 | 0 | AI question-and-answer workspace; records available as context |
| Brand Profiles | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage & Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stats | records | 1 | 0 | Native records/view |
| Persona generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ad compliance | records | 1 | 0 | Native records/view |
| Webhooks | integration | 1 | 0 | Provider request records only |
| Claim substantiation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Users | records | 1 | 0 | Native records/view |
| Trucks | records | 1 | 0 | Native records/view |
| Gps locations | records | 1 | 0 | Native records/view |
| Neighborhoods | records | 1 | 0 | Native records/view |
| Headlines | records | 1 | 0 | Native records/view |
| Billboard displays | records | 1 | 0 | Native records/view |
| Demographic data | records | 1 | 0 | Native records/view |
| Generation logs | records | 1 | 0 | Native records/view |
| Geofences | records | 1 | 0 | Native records/view |
| Brand safety scores | records | 1 | 0 | Native records/view |
| Weather contexts | records | 1 | 0 | Native records/view |
| Influencers | records | 1 | 0 | Native records/view |
| Brands | records | 1 | 0 | Native records/view |
| Content Calendar | records | 2 | 0 | Native records/view |
| Outreach | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Contracts | records | 1 | 0 | Native records/view |
| Payments | records | 1 | 0 | Native records/view |
| Audience Insights | records | 1 | 0 | Native records/view |
| Competitors | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Benchmarks | records | 1 | 0 | Native records/view |
| ROI Calculator | records | 1 | 0 | Native records/view |
| Brand Safety Clauses | records | 1 | 0 | Native records/view |
| Audience Segmentation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| LTV Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience Overlap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trend & Content Calendar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Micro-Influencer Discovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Content Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Influencer Matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Insights | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Campaign Strategy | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand Safety Scanner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign ROI Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pass5 tools | records | 1 | 0 | Native records/view |
| agentic campaign manager autonomously di | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| influencer ltv prediction recommending l | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| audience overlap detection recommending | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| trend content calendar ai predicting top | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fake follower detection scoring engageme | records | 1 | 0 | Native records/view |
| micro influencer discovery flagging emer | records | 1 | 0 | Native records/view |
| audience segmentation ai audiencejs i | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| performance prediction model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fake follower fraud detector | records | 1 | 0 | Native records/view |
| content calendar trend ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| live social media api integrations are | integration | 1 | 0 | Provider request records only |
| webhook receivers for engagement even | integration | 1 | 0 | Provider request records only |
| file upload for content briefs | records | 1 | 0 | Native records/view |
| notification engine 0 references | records | 1 | 0 | Native records/view |
| e signature for contracts | integration | 1 | 0 | Provider request records only |
| Segments | records | 1 | 0 | Native records/view |
| Tags | records | 1 | 0 | Native records/view |
| Custom Fields | records | 1 | 0 | Native records/view |
| Automations | records | 1 | 0 | Native records/view |
| Landing Pages | records | 2 | 0 | Native records/view |
| Forms | records | 1 | 0 | Native records/view |
| Image Library | records | 1 | 0 | Native records/view |
| Reviews | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Consent Fatigue | records | 1 | 0 | Native records/view |
| A/B Test Orchestrator | records | 1 | 0 | Native records/view |
| Engine Status | records | 1 | 0 | Native records/view |
| Content Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subject Line Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social Media Manager | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ad Creator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Response | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Send Time Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Audience Segmenter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Campaign Suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Segment Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Journey Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Attribution Modeler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Budget Allocator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Fatigue Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Persona Creator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Influencer Matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Hashtag Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Landing Page Builder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Email Campaign Writer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Ad Copies | records | 1 | 0 | Native records/view |
| Email Campaigns | records | 1 | 0 | Native records/view |
| Social Media Posts | records | 1 | 0 | Native records/view |
| Product Descriptions | records | 1 | 0 | Native records/view |
| Blog Posts | records | 1 | 0 | Native records/view |
| Taglines & Slogans | records | 1 | 0 | Native records/view |
| SEO Meta Content | records | 1 | 0 | Native records/view |
| Press Releases | records | 1 | 0 | Native records/view |
| Video Scripts | records | 1 | 0 | Native records/view |
| AI SEO Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Tone Adjuster | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| A/B Variation Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Headline Scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Localization Engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Copy views | records | 1 | 0 | Native records/view |
| Offer message fit | records | 1 | 0 | Native records/view |
| Fake Review Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Summarizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Trend Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Counterfeit Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Response Personalizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Review Solicitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Verify email | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Businesses | records | 1 | 0 | Native records/view |
| Drafts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reputation | records | 1 | 0 | Native records/view |
| Bulk import | records | 1 | 0 | Native records/view |
| Semantic search | records | 1 | 0 | Native records/view |
| Quality scorer | records | 1 | 0 | Native records/view |
| Reputation risk | records | 1 | 0 | Native records/view |
| Translate response | records | 1 | 0 | Native records/view |
| Team assignment | records | 1 | 0 | Native records/view |
| Retention targets | records | 1 | 0 | Native records/view |
| personalized response generation | records | 1 | 0 | Native records/view |
| fake review identification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| reputation trend forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multilanguage response | records | 1 | 0 | Native records/view |
| competitor benchmark dashboard | records | 1 | 0 | Native records/view |
| customer retention targeting | records | 1 | 0 | Native records/view |
| generateresponse aidrafted responses | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| sentimentanalysis classify sentiment urge | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fakereviewdetector ml scoring | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitorsentiment ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| responsequalityscorer | records | 1 | 0 | Native records/view |
| reputationriskalert forecasting branddama | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| review aggregation from google yelp tripa | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| publishing to multiple platforms | records | 1 | 0 | Native records/view |
| limited team collaboration assignment commen | records | 1 | 0 | Native records/view |
| analytics dashboard response rate timetor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| notifications for new reviews | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| smsemail solicitor channel integration | integration | 1 | 0 | Provider request records only |
| Seocontent writer work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Post Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hashtag Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Caption Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reply Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Voice Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Report Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Posting Time Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Content Mix Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Content Swipe | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Influencer Finder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Posts | records | 1 | 0 | Native records/view |
| Accounts | records | 1 | 0 | Native records/view |
| Hashtags | records | 1 | 0 | Native records/view |
| Brand voice | records | 1 | 0 | Native records/view |
| Auto replies | records | 1 | 0 | Native records/view |
| Team | records | 1 | 0 | Native records/view |
| Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scheduled posts | records | 1 | 0 | Native records/view |
| Performance analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hashtag fatigue | records | 1 | 0 | Native records/view |
| agentic social manager | records | 1 | 0 | Native records/view |
| crossplatform content adaptation | records | 1 | 0 | Native records/view |
| viral potential scoring | records | 1 | 0 | Native records/view |
| competitor benchmarking | records | 1 | 0 | Native records/view |
| microinfluencer matching | records | 1 | 0 | Native records/view |
| sentimentdriven response | records | 1 | 0 | Native records/view |
| postingtimeoptimizer engagementbased | records | 1 | 0 | Native records/view |
| contentmixrecommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| competitorcontentswipe topperforming anal | records | 1 | 0 | Native records/view |
| influencerfinder | records | 1 | 0 | Native records/view |
| audiencesentimentanalysis aggregate perce | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| platform api integration to actually publ | integration | 1 | 0 | Provider request records only |
| commentdm management routes | records | 1 | 0 | Native records/view |
| employee advocacy program | records | 1 | 0 | Native records/view |
| paid advertising management | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| influencer outreach workflow | records | 1 | 0 | Native records/view |
| crisis detectionalerts on social listenin | records | 1 | 0 | Native records/view |
| Testimonials | records | 1 | 0 | Native records/view |
| Case Studies | records | 1 | 0 | Native records/view |
| Social Widgets | records | 1 | 0 | Native records/view |
| Success Metrics | records | 1 | 0 | Native records/view |
| Customer Quotes | records | 1 | 0 | Native records/view |
| Video Testimonials | records | 1 | 0 | Native records/view |
| Widget Builder | records | 1 | 0 | Native records/view |
| A/B Variants | records | 1 | 0 | Native records/view |
| Outreach Campaigns | records | 1 | 0 | Native records/view |
| Customer Segmentation | records | 1 | 0 | Native records/view |
| Testimonial Likelihood | records | 1 | 0 | Native records/view |
| Authenticity Scorer | records | 1 | 0 | Native records/view |
| Persona Variants | records | 1 | 0 | Native records/view |
| Sentiment-driven variant generation tuned to buyer... | records | 1 | 0 | Native records/view |
| Multi-modal proof widgets combining video + audio... | records | 1 | 0 | Native records/view |
| Competitive testimonial analysis via RAG over comp... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Authenticity scoring to detect AI-generated vs rea... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| One-click marketplace publishing to Capterra, G2,... | records | 1 | 0 | Native records/view |
| Review crawler service with scheduled polling of e... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No AI-driven customer segmentation for targeted te... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No predictive scoring for which customers are most... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No automated visual asset (poster/social card) gen... | records | 1 | 0 | Native records/view |
| No integrations with Trustpilot, G2, Capterra revi... | integration | 1 | 0 | Provider request records only |
| No A/B testing framework for widget placement/mess... | records | 1 | 0 | Native records/view |
| No scheduled batch review crawling from external s... | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| No webhooks/notifications system for new review or... | integration | 1 | 0 | Provider request records only |
| Limited audit logging (single reference, not a ded... | records | 1 | 0 | Native records/view |
| Podcasts | records | 1 | 0 | Native records/view |
| Episodes | records | 1 | 0 | Native records/view |
| Issues | records | 1 | 0 | Native records/view |
| Alerts | records | 1 | 0 | Native records/view |
| Advertisers | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 311 feature pages were visited in the browser; 309 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 182 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

182 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).

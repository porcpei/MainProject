# UK Letting/Estate Agent Software Ecosystem and AI Integration Paths (as of Nov 2026)

Research method note: Only WebSearch worked. WebFetch could not reach thenegotiator.co.uk, lettingagenttoday.co.uk, foundations-documentation.reapit.cloud or developers.zoopla.co.uk, because those hosts are not allowed in this session's network. Every finding below is from search-result summaries of those pages, not full-page reads. Where the exact wording matters, such as fees or contract terms, check the primary page before relying on it. No independent UK CRM market-share survey was found. Most market-share figures are self-reported by vendors.

## 1. Agency CRM / property management software, market share, and APIs / partner programmes

### Takeaway
Three platforms dominate: Alto Software Group (Alto, Jupix, Expert Agent, owned by Houseful/Zoopla), Reapit (enterprise and multi-branch) and Street (fast-growing, aimed at independents). Reapit (Foundations), Alto (Partner Hub/Marketplace), Street (Open API plus webhooks), Apex27 (API, webhooks, n8n node) and Arthur Online (free open API) all have documented third-party routes. Reapit is the only one with a clearly metered, pay-per-call developer model. Alto access depends on approval and is criticised as "pay to play". No independent market-share data exists publicly.

### Cited Findings
**Market share / footprint (mostly vendor-reported)**
- Alto claims to be the "UK's #1 estate agent CRM", "trusted by over 6,000 agents and used by over a third of UK estate agents". Another Alto page says about 35% of agencies, and another source cites 25,000 users. This is vendor marketing, and one Alto page is mistitled "2027". — [Alto blog](https://www.altosoftware.co.uk/blog/best-estate-agency-crm-software-in-2026-8-platforms-compared/); [Alto agency trends report 2026](https://www.altosoftware.co.uk/guides/the-alto-agency-trends-report-2026/)
- Houseful's software division became the standalone brand "Alto Software Group" (ASG) in January 2025. It covers Alto, Jupix, Expert Agent, CFP and Yourkeys. Alto's predecessors include Vebra and CfP. — [PrimeResi](https://primeresi.com/estate-agency-software-giant-overhauls-brand-structure/); [bebeez (Jul 2025)](https://bebeez.eu/2025/07/16/alto-reaches-new-heights-with-record-growth/)
- Zoopla's pilot moving agents from Jupix to Alto "concluded successfully", and all agents will be urged to transfer. The long-term plan is to merge Jupix, Alto, Expert Agent and PropertyFile into one CRM (older report; the date was not confirmed in the search). — [PrimeResi / search summary](https://primeresi.com/estate-agency-software-giant-overhauls-brand-structure/)
- Reapit is described as the enterprise standard for large corporate networks. A third-party directory claims 5,000+ UK branches (unverified). Reapit's own global figure is about 15,000+ branches. — [bizaitools comparison](https://bizaitools.co.uk/alto-vs-street-vs-reapit/); [esremedia](https://esremedia.co.uk/blog/estate-agent-crm-software-uk)
- Street is positioned as the most AI-integrated CRM (AI Call Handler, Photo Editor) and suits growth-focused independents and single-branch agencies. — [Letting Agent Today sponsored comparison, Aug 2026](https://www.lettingagenttoday.co.uk/sponsored-content/2026/08/the-uks-best-property-management-software-for-2026-alto-vs-reapit-vs-street-compared/); [lanten.ai](https://lanten.ai/street-vs-alto-vs-reapit)
- Other names on UK shortlists include Jupix, Rex, Dezrez, Apex27, Loop and agentOS. — [hackceleration](https://www.hackceleration.com/labs/best/real-estate-agency-software); [esremedia](https://esremedia.co.uk/blog/alternatives-to-alto-estate-agent-software-uk)
- No Propertymark CRM-usage survey was found. A small Inventory Base survey (about 1.2% of the industry) found that 52% of agents feel proptech delivers little or no value and 55% "don't use PropTech". A commenter pointed out that respondents probably don't count their CRM as proptech. — [Property Industry Eye](https://propertyindustryeye.com/agents-divided-over-proptech-new-survey-finds/); [The Negotiator](https://thenegotiator.co.uk/news/proptech/half-of-estate-agents-never-use-proptech-claims-new-research/)

**Reapit Foundations (developer platform and AppMarket)**
- Developer portal enrolment is self-service, with interactive docs and analytics. Apps go through a listing review and, once approved, are set to "Listed" in the AppMarket. Partner contact: partners@reapit.com. — [Reapit Partner program](https://reapit.com/foundations); [Foundations docs: listing your app](https://foundations-documentation.reapit.cloud/listing-your-app)
- Partners set their own app prices, and some apps are free. — [Reapit AppMarket FAQ](https://reapit.atlassian.net/wiki/spaces/RW/pages/923598951/AppMarket+Frequently+Asked+Questions)
- API usage is billed monthly per call on a sliding scale. An old docs example used £0.005 per call. Webhook-originated requests are billed like API requests. GraphQL adds no charge beyond the REST calls it makes. — [Foundations docs: Webhooks](https://foundations-documentation.reapit.cloud/api/webhooks); [Foundations docs: GraphQL](https://foundations-documentation.reapit.cloud/api/graphql)
- The developer terms reportedly require each approved app to reach at least **£200/month in consumption cost**. Reapit can change fees on 60 days' notice. A 2021-era agreement listed a **£300/month Developer Edition fee plus a £995 annual registration fee**. That is old data; check current terms. — [Reapit developer T&Cs (GitHub)](https://github.com/reapit/foundations-documentation/blob/master/developer-terms-and-conditions.md); [Foundations User T&Cs PDF (2021)](https://reapit-marketplace-app-media-prod.s3.eu-west-2.amazonaws.com/Foundations-terms-250621.pdf)
- LeadPro, a lead-response vendor, passes Reapit's charge of **£0.0235 per API call** on to the agent's monthly invoice. This is real evidence of how a lead-automation vendor pays for Reapit. — [LeadPro Reapit integration guide](https://lead.pro/guides/reapit-integration)
- Reapit announced the RAI Copilot, a voice-first AI assistant, on 23 April 2026 for a summer 2026 launch, plus a **marketplace for third-party AI agents from June 2026**. As of August 2026, general availability had not been confirmed. — [Property Industry Eye](https://propertyindustryeye.com/reapit-rolls-out-new-ai-offering-for-estate-agents/); [Alto comparison, Aug 2026](https://www.altosoftware.co.uk/blog/ai-crms-for-estate-agents-2026-5-compared/)

**Alto (Zoopla/Houseful)**
- Alto launched its Partner Hub in August 2023, giving proptechs API docs and a test environment. Once Alto's product team approves an integration, the partner joins the Alto Marketplace. Named partners include Goodlord, Vouch, SmartSearch, FocalAgent and MoveGenius. — [Zoopla press release](https://www.zoopla.co.uk/press/releases/alto-launches-partner-hub-to-complement-recently-launched-alto-marketplace); [Property Industry Eye](https://propertyindustryeye.com/alto-launches-partner-hub/)
- Alto APIs are documented on developers.zoopla.co.uk with the prefix "ALTO". The referencing-partner guide says integration currently works by polling the ReferenceChecks endpoint, which suggests limited webhooks. The public Zoopla listings API is no longer available. — [Zoopla developers: Alto APIs & Zoopla APIs](https://developers.zoopla.co.uk/docs/alto-apis-zoopla-apis); [Guide for Referencing Partners](https://developers.zoopla.co.uk/docs/guide-for-referencing-partners)
- A reader comment on trade press called Alto "a closed API with a pay to play... Only suppliers willing to fork out are allowed access". This is opinion, not verified. Alto's partner fees were not found. — [Estate Agent Today](https://www.estateagenttoday.co.uk/breaking-news/2023/8/zoopla-backed-alto-launches-proptech-partner-hub)
- Alto Intelligence is Alto's built-in AI suite (five capabilities, including 24/7 lead handling, AI Listings, AI Analyst and a Lettings Compliance Agent). It competes directly with a third-party AI lead responder. — [Alto blog](https://www.altosoftware.co.uk/blog/the-best-ai-crms-for-estate-agents-in-2026-alto-street-and-reapit-compared/); [bizaitools](https://bizaitools.co.uk/alto-vs-street-vs-reapit/)

**Street.co.uk**
- Street has an Open API (REST) with webhooks for real-time events and a sandbox, documented at developers.street.co.uk. Developer contact is apis@street.co.uk, and Street works directly with new partners. — [Street developers](https://street.co.uk/developers/api); [Street Open API](https://street.co.uk/features/openapi)
- Agents generate an Open API token themselves under Settings > Account Administration > Applications. This is how third-party AI tools such as Lettie and LightWork AI connect. — [Street: Lettie integration](https://street.co.uk/integrations/lettie); [Street: LightWork AI](https://street.co.uk/integrations/lightwork-ai)
- There is a Zapier app called "Street.co.uk Enquiries", with templates such as Email Parser leading to a new Street enquiry. — [Zapier](https://WWW.ZAPIER.COM/find-apps/s/streetcouk-enquiries)
- Street has its own AI Call Handler for out-of-hours calls. It records, transcribes and summarises calls into the Enquiry Centre and creates contacts automatically. It costs 75 AI credits per minute and is "available on request". Street also has a "Zero-touch booking engine" for portal enquiries. — [Street AI Call Handler](https://street.co.uk/product/index/ai-call-handler); [Street help centre](https://intercom.help/streetcouk/en/articles/12585780-street-ai-call-handler); [Street booking engine](https://live.street.co.uk/product/index/zero-touch-booking-engine)

**Apex27**
- Apex27 has public API docs at api-docs.apex27.co.uk and its own official n8n node covering contacts, listings, viewings, valuations and webhooks. It is also on Zapier, Integrately and Unified.to (beta). — [Apex27 n8n](https://apex27.co.uk/integration/n8n); [Unified.to](https://unified.to/integrations/apex27); [Zapier](https://zapier.com/apps/apex27/integrations)

**Arthur Online (lettings PMS)**
- Arthur offers API documentation "at no extra cost" and calls itself one of very few open-API PMSs. Access is set up through OAuth Applications in Settings. New endpoints can be built, but "a fee may be incurred". — [Arthur developer API](https://arthuronline.co.uk/connect/arthur-api); [Arthur support: API work](https://support.arthuronline.co.uk/support/solutions/articles/202000052217-api-work-providing-support)

### Inferences
- The easiest first CRM targets for a solo founder are probably Street (self-serve token, webhooks, Zapier), Apex27 (n8n, webhooks) and Arthur (free open API). Reapit is valuable because of enterprise reach, but it carries per-call costs, a likely £200/month minimum per app and a review process. Alto has the largest share but the most gatekeeping.
- All three major CRMs now ship native AI lead handling (Alto Intelligence, Street AI Call Handler, Reapit RAI). A third-party vendor has to compete on quality, multi-CRM coverage or lettings-specific depth, or sell through Reapit's planned AI-agent marketplace.

### Gaps
- No independent market-share data. Propertymark data was not found, and fetches to The Negotiator and LettingAgentToday were blocked.
- Alto partner fees and terms, current Reapit Foundations fees (the £300/£995 figures are 2021), Street partner fees.
- No API information was found for Jupix, Expert Agent, Loop, Acquaint, Dezrez, 10ninety, Veco, MRI or agentOS. agentOS does support Fixflo keys, so it has some integration layer.
- Goodlord's API or partner programme was not found. Two searches returned nothing.
- Whether Reapit's AI-agent marketplace actually launched in June 2026 or later.

## 2. Portals (Rightmove, Zoopla, OnTheMarket): lead delivery, programmatic access, competing AI

### Takeaway
Zoopla and OnTheMarket offer documented lead APIs, but these are aimed at CRMs and agents. Rightmove pushes enhanced lettings leads into selected CRMs (Alto first, then about five big CRMs) and has no public lead API. For an independent vendor, the universal route is still parsing the enquiry notification emails, or reading leads out of the agent's CRM. Rightmove is building its own AI tools (Rightmove Plus AI Assistant, AI valuation-reply drafting, announced agentic tools), and these could compete.

### Cited Findings
- **Zoopla:** The Leads Delivery Service launched in 2022 with a Push Delivery Service (leads within seconds) and a Leads API (polled, OAuth2, last 24 hours by default, 30-day retention). Both are free for Zoopla customers but must be requested from a rep. Zoopla asked users to move off FTP and email parsing by 10 July 2022. — [Zoopla press release](https://www.zoopla.co.uk/press/releases/zoopla-launches-new-leads-delivery-service-enabling-agents-to-receive-leads-in-just-seconds); [Zoopla developer reference](https://developers.zoopla.co.uk/reference); [Property Industry Eye](https://propertyindustryeye.com/zoopla-launches-new-leads-delivery-service-for-agents/)
- **OnTheMarket:** "API lead integration" lets a CRM pull email and phone leads from OnTheMarket Expert for a time window. Supported providers include Street, Pulse CRM, Property Hive and Pipedrive (new homes). — [OTM Expert help centre](https://expert.onthemarket.com/help-centre/lead-integration/)
- **Rightmove:** Enhanced lettings leads from Enquiry Manager are delivered in real time into Alto, and later into about five major CRMs ("Rightmove opens up its tenant leads data to five big industry CRMs"). SME Professional is also named. The full list and date could not be fetched. — [Rightmove press centre](https://www.rightmove.co.uk/press-centre/?p=4755); [Property Industry Eye](https://propertyindustryeye.com/rightmove-integrates-enhanced-leads-with-agents-crm-system/); [The Negotiator](https://thenegotiator.co.uk/news/products-services-news/launch-rightmove-opens-up-its-tenant-leads-data-to-five-big-industry-crms/); [The Negotiator: Alto](https://thenegotiator.co.uk/news/proptech/rightmove-lettings-leads-integrated-into-alto-software/)
- **Email format:** CRMs import portal leads from email. Reapit documents its own plain-text email format for internet registrations, which is a CRM-specific format, not a Rightmove standard. Automation vendors say every Rightmove or Zoopla enquiry also arrives as a notification email that can be parsed for name, email, phone and property reference (vendor claim). — [Reapit: Internet registrations setup](https://reapit.atlassian.net/wiki/spaces/RW/pages/110985409); [Softomate](https://www.softomatesolutions.com/blog/ai-automation-uk-letting-agencies-rightmove-tenancy-2026/)
- **Rightmove Viewings Manager:** This is lettings-only and included in all Rightmove packages. It asks pre-qualification questions, sends automatic reminders and syncs with Outlook, Google and iCloud calendars. Its viewing notification emails do not integrate with partner CRMs and contain no lead data, only a prompt to log in. — [Rightmove Hub](https://hub.rightmove.co.uk/viewings-manager); [Rightmove support](https://rightmove.freshdesk.com/support/solutions/articles/7000059987-viewings-manager)
- **Rightmove AI:** The Online Agent Valuation includes an AI writing tool that drafts personalised replies to valuation leads. Valuation leads rose 50% (January 2026 and H1 2026). In its 6 November 2026 trading statement, Rightmove said its "Rightmove Plus AI Assistant has already been used by 14,000 estate agents" and that Ask Rightmove users sent more than three times as many leads (self-selected users, so not causal). A consumer AI Comparison Assistant launched in October 2026 with limited rollout. Agentic tools for agencies were announced for H2 2026; I could not confirm whether they are live. — [Rightmove press centre](https://www.rightmove.co.uk/press-centre/property-valuation-leads-to-agents-up-50-on-last-year/); [FourWeekMBA](https://fourweekmba.com/ai-rightmove-raises-eps-guide-as-ai-users-send-3x-the-leads/); [LandlordZone](https://www.landlordzone.co.uk/news/rightmove-launches-ai-comparison-tool-to-boost-search-transparency-and-lead-conversion); [lettings.quest](https://lettings.quest/ai-for-estate-agents-uk)
- Boomin is defunct (from the task brief; not researched further).

### Inferences
- An independent vendor cannot get Rightmove leads directly. The realistic options are: (a) set up an auto-forwarding rule or connect the agent's lead inbox (Gmail or Microsoft Graph) and parse it; (b) read new applicants or enquiries from the CRM API or webhooks (Street, Reapit, Apex27); (c) for Zoopla and OTM, the agent may be able to authorise the vendor to use their Leads API credentials. Option (c) needs checking against Zoopla and OTM terms.
- Zoopla deprecating email parsing for its own delivery suggests that email formats can change without notice, so parsers need monitoring.
- Rightmove Viewings Manager already gives lettings agents free self-serve booking. An AI booking product therefore has to add value beyond it, for example qualifying applicants by conversation, handling Zoopla and OTM leads, or covering sales viewings.

### Gaps
- Rightmove's exact email-notification format and fields. No official specification was found.
- The list of the five CRMs that receive Rightmove enhanced leads, and the date (The Negotiator could not be fetched).
- Whether Zoopla or OTM lead APIs can be used by a third party acting for an agent.

## 3. Viewing booking, maintenance, and referencing tools already in use

### Takeaway
Booking is already covered by Rightmove Viewings Manager, Street's booking engine and Yourkeys (now owned by ASG). Viewber supplies outsourced viewing hosts and has an API. In maintenance, Fixflo is the standard and has deep PMS integrations. Referencing partners plug into Alto (Goodlord, Vouch) and similar platforms.

### Cited Findings
- Yourkeys belongs to Alto Software Group, so it is tied to Alto. — [PrimeResi](https://primeresi.com/estate-agency-software-giant-overhauls-brand-structure/)
- Rightmove Viewings Manager is a lettings booking tool included in all packages (see Q2). Rightmove launched online viewing bookings in about 2020; that is old data. — [The Negotiator](https://thenegotiator.co.uk/news/more-than-portal-rightmove-launches-online-bookings-service-for-viewings/); [LettingAgentToday 2020](https://old.lettingagenttoday.co.uk/breaking-news/2020/11/enhanced-appointment-booking-tool-unveiled-by-rightmove)
- Street's Zero-touch booking engine routes Rightmove, Zoopla, OTM and website enquiries straight into the diary, with dashboards for no-shows and utilisation. — [Street](https://live.street.co.uk/product/index/zero-touch-booking-engine)
- Viewber is a marketplace of more than 5,000 freelance viewing hosts, with an API that any CRM or PMS can integrate. — [Viewber](https://viewber.co.uk/viewings-open-houses); [Viewber on-demand](https://viewber.co.uk/on-demand-property-appointments)
- Fixflo integrates with Arthur (tenant portal iFrame plus auth token, issues synced to Arthur to-dos), MRI Sales and Lettings (automatic updates), Reapit (Fixflo is a "Reapit Strategic Partner") and agentOS (API key). Fixflo Lettings has an API. — [Fixflo: Arthur](https://www.fixflo.com/integrations/lettings/arthur); [Fixflo: MRI](https://www.fixflo.com/integrations/lettings/mri-sales-and-lettings); [Fixflo: Reapit](https://www.fixflo.com/integrations/lettings/reapit); [agentOS hub](https://hub.agentos.com/how-do-i-integrate-fixflo-with-agentos); [Capterra](https://www.capterra.com/p/163230/Fixflo-Lettings/reviews/)
- Goodlord has a two-way sync with Street using an API key, and is an Alto Marketplace partner. Vouch is an Alto partner. — [Street: Goodlord](https://live.street.co.uk/integrations/goodlord); [Zoopla press](https://www.zoopla.co.uk/press/releases/alto-launches-partner-hub-to-complement-recently-launched-alto-marketplace)

### Inferences
- For maintenance triage, the best path is to integrate with Fixflo (API) rather than compete with it: for example, an AI front door on WhatsApp or voice that triages the issue and creates the Fixflo job. Agents on Arthur or Reapit already route repairs through Fixflo.
- Referencing (Goodlord, HomeLet, Let Alliance, Vouch) is a later step to hand off to, not a target for the MVP.

### Gaps
- Calendly-style tool adoption among UK agents, Housescape, Goodlord Maintenance, and HomeLet / Let Alliance APIs. None were found in searches.
- Fixflo API access terms and cost for a new vendor.

## 4. Practical integration path for a small vendor (email parsing, calendar, SMS/WhatsApp, Zapier/Make/n8n)

### Takeaway
A credible MVP stack is: lead capture from the agent's inbox (portal notification emails), plus CRM write-back through Street or Apex27 APIs (or Zapier/n8n), plus Google or Outlook calendar for viewings, plus Twilio SMS/WhatsApp. Add a Reapit Foundations app once there is paying demand from Reapit agencies.

### Cited Findings
- Zapier already offers an "Email Parser by Zapier to new Street enquiry" template, which shows email parsing into a CRM is an accepted pattern. — [Zapier Street.co.uk Enquiries](https://WWW.ZAPIER.COM/find-apps/s/streetcouk-enquiries)
- Apex27 has an official n8n node (contacts, listings, viewings, valuations, webhooks) and a Zapier app. — [Apex27 n8n](https://apex27.co.uk/integration/n8n); [Zapier Apex27](https://zapier.com/apps/apex27/integrations)
- Unified APIs (Unified.to, Knit) offer pre-built connectors for Apex27 and Street. These could save a solo founder building each CRM integration separately. — [Unified.to Apex27](https://unified.to/integrations/apex27); [Knit Street connector](https://getknit.dev/ipaas-connectors/street-co-uk/)
- Lead-response competitors already plug into CRMs the same way. LeadPro uses the Reapit API (with the per-call cost passed on). Lettie and LightWork AI use Street API tokens. — [LeadPro](https://lead.pro/guides/reapit-integration); [Street: Lettie](https://street.co.uk/integrations/lettie); [Street: LightWork AI](https://street.co.uk/integrations/lightwork-ai)
- Rightmove Viewings Manager syncs with Outlook, Google and iCloud, so agents' diaries in those calendars are an accepted source of truth. — [Rightmove Hub](https://hub.rightmove.co.uk/viewings-manager)

### Inferences
- Many agents keep viewings in the CRM diary (Reapit, Alto, Street), not in Google or Outlook. Writing a viewing only to Google Calendar may create double-booking risk unless the CRM diary is synced. Check this per CRM.
- WhatsApp Business messaging through Twilio or Meta's Cloud API needs template approval for outbound messages outside the 24-hour customer-service window. This is general knowledge and was not verified in this session.

### Gaps
- No sources were gathered in this session on Twilio or WhatsApp pricing, UK SMS sender-ID rules, Make.com connectors for UK CRMs, or Reapit and Alto connectors on Zapier, Make or n8n.

## 5. Data protection: UK GDPR obligations as a processor

### Takeaway
An AI lead, viewing or maintenance vendor will normally be the agent's processor. It needs an Article 28-compliant DPA covering: documented instructions, confidentiality, Article 32 security, authorised sub-processors (for example LLM providers, Twilio, hosting), help with data-subject rights, deletion or return at contract end, and audit rights.

### Cited Findings
- ICO list of required contract terms: processing only on the controller's documented instructions (including international transfers); staff confidentiality; Article 32 security; prior written authorisation (specific or general) for sub-processors, who must take on equivalent Article 28(3) obligations; help with data-subject rights; deletion or return at the controller's choice; and providing information and allowing audits (Art. 28(3)(h)). — [ICO: What needs to be included in the contract?](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/contracts-and-liabilities-between-controllers-and-processors-multi/what-needs-to-be-included-in-the-contract/)
- Sub-processor contracts need not use identical wording but must give the same level of protection. Controllers must assess that a processor is competent before appointing it. — [ICO: responsibilities and liabilities for controllers](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/contracts-and-liabilities-between-controllers-and-processors-multi/responsibilities-and-liabilities-for-controllers-using-a-processor); [ICO contracts guide](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/guide-to-accountability-and-governance/contracts/)
- The ICO has an AI-specific audit toolkit section on contracts and third parties. — [ICO AI toolkit: contracts and third parties](https://ico.org.uk/for-organisations/advice-and-services/audits/data-protection-audit-framework/toolkits/artificial-intelligence/contracts-and-third-parties/)

### Inferences
- LLM APIs and hosting outside the UK are international transfers. The vendor will need the UK IDTA or the UK Addendum to EU SCCs, or to rely on UK adequacy regulations such as the UK-US data bridge, and must list sub-processors. Reapit's developer terms will also impose their own data obligations.
- Using tenant or applicant data to train models would probably go beyond the controller's instructions unless the DPA explicitly allows it.

### Gaps
- Not researched here: the Data (Use and Access) Act 2025 changes, ICO registration fee for processors, and DPIA expectations for AI voice or call recording.

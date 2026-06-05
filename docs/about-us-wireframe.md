# About Us Page Wireframe

## Goal

Create a modern, corporate-industrial About Us page for Green Force that explains who the company is, how it started, what it stands for, and how its recycling and steel trading businesses connect.

## Source Content

- Page heading: About Us
- Primary section: About Green Force
- Opening headline: WE ARE GREEN FORCE
- Origin: Established in 2010 as a Malaysian metal recycling corporation.
- Company position: Grew from small beginnings into a premier metal recycling company.
- Diversification: Strategically expanded into finished steel product trading.
- Business spirit: Driven by early pioneering spirit and industry knowledge.
- Identity pillars: Strategic Pioneer, Market Leader, Innovator.
- Milestones / History / Our Story: organize the company journey into a chronological timeline.
- Visual requirement: professional, high-resolution images relevant to recycling and steel industry.
- Brand direction: modern corporate-industrial identity using orange, silver, red, and white.

## Desktop Wireframe

```text
+------------------------------------------------------------------------------+
| NAV                                                                          |
| [Green Force logo] Home | About Us | Our Business | Product & Services | ... |
|                                                            [Contact Us CTA]  |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| HERO / PAGE INTRO                                                            |
|                                                                              |
| About Us                                                                     |
| Established in 2010, Green Force has grown from a Malaysian metal recycling  |
| corporation into a diversified group serving recycling and steel markets.     |
|                                                                              |
| Full-width industrial/recycling facility image                                |
| - Subject: metal recycling yard, steel materials, industrial operations       |
| - Treatment: dark overlay for readable white headline text                    |
| - Optional proof points: Established 2010 | Malaysia | Recycling + Steel      |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| INTRO: WE ARE GREEN FORCE                                                    |
|                                                                              |
| +--------------------------------------+  +--------------------------------+ |
| | WE ARE GREEN FORCE                   |  | [Portrait industrial image]    | |
| |                                      |  | Metal processing / organized   | |
| | Since its origin in 2010 as a        |  | steel facility / operations    | |
| | Malaysian metal recycling            |  |                                | |
| | corporation, Green Force has grown   |  |                                | |
| | from small beginnings into a premier |  |                                | |
| | metal recycling company while        |  |                                | |
| | diversifying into finished steel     |  |                                | |
| | product trading.                     |  |                                | |
| +--------------------------------------+  +--------------------------------+ |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| IDENTITY PILLARS                                                             |
|                                                                              |
| WE ARE ...                                                                   |
|                                                                              |
| +----------------------+ +----------------------+ +----------------------+  |
| | 01                   | | 02                   | | 03                   |  |
| | Strategic Pioneer    | | Market Leader        | | Innovator            |  |
| |                      | |                      | |                      |  |
| | We became who we are | | Built on operational | | We continue to       |  |
| | by building our own  | | reliability, market  | | redefine industry    |  |
| | paths and venturing  | | intelligence, and    | | standards and shape  |  |
| | into new horizons.   | | consistent value.    | | the future of metals.|  |
| +----------------------+ +----------------------+ +----------------------+  |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| GROUP STRUCTURE / BUSINESS CONTEXT                                           |
|                                                                              |
| Green Force Group                                                            |
| The Group comprises Green Force Sustainability, Wise Metal Recycling, and     |
| Strader. The metal business covers recycling operations and finished steel    |
| product trading.                                                             |
|                                                                              |
| +--------------------------------------+  +--------------------------------+ |
| | Green Force Sustainability /         |  | Strader                        | |
| | Wise Metal Recycling                 |  | Finished Steel Product Trading | |
| |                                      |  |                                | |
| | Ferrous Scrap Metal Recycling        |  | Finished steel products across | |
| | Sourcing and processing scrap metal  |  | Malaysia for diverse customers | |
| | for steel mills and industrial       |  | and industry partners.         | |
| | customers in Malaysia.               |  |                                | |
| | [Explore Our Business]               |  | [View Product & Services]      | |
| +--------------------------------------+  +--------------------------------+ |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| MILESTONES / OUR STORY                                                       |
|                                                                              |
| Our Journey                                                                  |
| A chronological timeline of Green Force growth.                              |
|                                                                              |
| 2010 ------> Early recycling foundation                                      |
|      ------> Expanded facilities and supplier network                        |
|      ------> Diversified into finished steel product trading                 |
|      ------> Continued growth as a Malaysian metal industry company          |
|                                                                              |
| Note: exact milestone dates/details to be added when client provides them.    |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| CTA BAND                                                                     |
|                                                                              |
| Learn more about our recycling and steel trading capabilities.                |
| [Explore Our Business] [Contact Us]                                          |
+------------------------------------------------------------------------------+

+------------------------------------------------------------------------------+
| FOOTER                                                                       |
| Green Force summary | quick links | contact info | policies                  |
+------------------------------------------------------------------------------+
```

## Mobile Wireframe

```text
+------------------------------+
| NAV                          |
| [Logo]                 [Menu]|
+------------------------------+

+------------------------------+
| About Us                     |
| Established in 2010...       |
| [Industrial image + overlay] |
+------------------------------+

+------------------------------+
| WE ARE GREEN FORCE           |
| Since its origin in 2010...  |
| [Industrial image]           |
+------------------------------+

+------------------------------+
| WE ARE ...                   |
|                              |
| 01 Strategic Pioneer         |
| We build our own paths...    |
|                              |
| 02 Market Leader             |
| Operational reliability...   |
|                              |
| 03 Innovator                 |
| Redefining industry...       |
+------------------------------+

+------------------------------+
| Green Force Group            |
| Green Force Sustainability   |
| Wise Metal Recycling         |
| Ferrous Scrap Metal          |
| [Explore Our Business]       |
|                              |
| Strader                      |
| Finished Steel Product       |
| [View Product & Services]    |
+------------------------------+

+------------------------------+
| Our Journey                  |
| 2010                         |
| Early recycling foundation   |
| Expanded network             |
| Finished steel trading       |
| Continued growth             |
+------------------------------+

+------------------------------+
| CTA                          |
| [Explore Business]           |
| [Contact Us]                 |
+------------------------------+
```

## Implementation Plan

1. Keep the existing `about-us.astro` page shell and `WebflowPage` transformation pattern.
2. Replace all remaining mortgage/loan template copy with Green Force company content.
3. Rebuild the About body into five clear sections: hero, company intro, identity pillars, group/business context, and timeline.
4. Use existing industrial assets first: `/images/contact-hero-industrial.png`, `/images/greenforce-announcement-facility.webp`, `/images/greenforce-announcement-industrial.webp`, and `/images/point3d-commercial-imaging-ltd-Rb3HbkNNoLQ-unsplash.jpg`.
5. Remove testimonial/team/client-logo/template promo sections from the About Us page.
6. Link business CTAs to `/our-business`, `/product-services`, and `/contact-us`.
7. Use orange for primary CTAs, silver/white for surfaces, and restrained red accents for emphasis.
8. Add responsive CSS so the desktop two-column sections stack cleanly on mobile.
9. Verify with `npm run build`, then run the page locally and check the About Us page in-browser.

## Visual Direction

Hero image:

```text
Wide industrial photograph of a modern metal recycling and steel processing
facility in Malaysia, organized yard, stacked steel materials, clean corporate
operations, realistic daylight, no text, no logos, strong left-side negative
space for headline text.
```

Section styling:

- Hero: full-width image with dark overlay and white text.
- Intro: white background, two-column editorial layout.
- Pillars: light silver background, three compact cards, numbered labels.
- Group structure: two operational cards with image accents and CTA links.
- Timeline: clean horizontal timeline on desktop, vertical timeline on mobile.
- CTA band: dark industrial background or charcoal band with orange CTA.

## Content Still Needed

- Exact milestone years after 2010.
- Final approval for whether to mention "premier" or use a more neutral phrase.
- Any official company registration facts or leadership information, if the About page should include them.
- Confirm whether the Group wording should say "Green Force Group" publicly.

## Notes

- The About page should feel like a corporate capability story, not a marketing landing page.
- Do not show Investor Relation content; the source document says it should remain hidden/inactive.
- The strongest first pass is to make the page credible and focused, then add exact milestone details later when supplied.

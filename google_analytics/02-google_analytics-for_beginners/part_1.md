# google_analytics/02-google_analytics-for_beginners/part_1.md

Notes for Part 1 of the Digital Analytics for Beginners class at the Analytics Academy.

# Part 1. Introducing Google Analytics

## 1.1 Why digital analytics?

- Teachers: Justin Cutroni and Krista Seiden - analytics advocates.
- Digital Analytics: collect and analyze data from marketing, advertising, and sales efforts
- Purchase Funnel:
  1. Acquisition - building awareness, acquiring user interest
  2. Behavior - users engage with business
  3. Conversion - user becomes a customer and makes a transaction
- Publishers: build a loyal and engaged online audience, serve more relevant ads
- E-commerce: better understand how customers use the site and what they are looking for
- Lead Generation: gather user information for sales people to use for following up
- Can collect data from web sites, mobile apps, online Point-of-Sales systems, CRMs, video games, and other sources

## 1.2 How Google Analytics works

1. Create Google Analytics account
1. Add tracking code snippet
1. Tracking code tracks:
   - User behavior during their visit
   - User's Language
   - User's Type of browser
   - User's Device
   - User's OS
   - User's Traffic source - how the found the site (search engine, email marketing, etc.)

- Sessions:
  - Begin when user enters site
  - End after 30 minutes of inactivity
  - Begins again when user returns

- Configuration settings - how data is processed
  - Filter by country or region
  - Don't exclude data, can't get it back

## 1.3 Google Analytics setup

- Organization: can have one or more accounts
- Account: can have one or more properties
  - How data is collected
  - Who can see it
  - One per business or business unit
- Property: can have one or more views
  - Has a unique tracking code
- View: can filter data,
  - e.g., by geographical region
  - filter out visits by employees
  - set goals track conversions
  - once set up, cannot change views
  - cannot collect data until view is set up
  - only admins can recover a deleted view (within 35 days)
- Permissions - characteristics:
  - assigned at Account, Property, or View level
  - are inherited from level above it, e.g., property permissions inherited by view
- Permission types:
  - Manage users: add or remove user access
  - Edit: change configuration settings
  - Collaborate: share parts of data or settings
  - Read and analyze: view data, analyze reports, create dashboards, change settings, add users
- Align data collection strategy with overall business structure

### 1.3.1 Demo:

Use gmail account: email and password
Account Name: Google Store
Website Name: Google Store
Website URL:
Industry Category:
Time Zone:
Data Sharing Settings:
Get Tracking ID:

**NOTE:** Add tracking code to just after the `<head>` tag - NOT at the end as done before!!

To get exising tracking id: Admin -> Under Property: Tracking Info -> Tracking Code

## 1.4 How to set up views with filters

[No video for this section.]

### 1.4.1 Demo:

In Google Analytics:

- Admin -> Under View: View Settings ->
- View Name: Change "All Website Data" to "Raw Data" because it is unfiltered -> Save
- Set up a test view:
  - View Selector pull down (top of left nav) -> Create new view
  - Name: "Test View" -> Create View
  - Click on View Settings
  - Check Bot Filtering -> Save
- Set up a master view - copy test view and rename it:
  - Copy View (button on the right)
  - Name: "Master View" -> Copy View
- Review:
  - Raw: backup of data
  - Test: for experimenting
  - Master: daily reporting and analysis
- Setup First Filter: internal traffic, filter by IP
  - Select Test View in pull down (under View column)
  - Filters -> Add Filter
  - Name: "Exclude internal traffic"
  - Predefined (default) -> Select filter type pull down -> Exclude
  - Select source pull down -> Traffic from the IP addresses
  - Select expression pull down -> that are equal to
  - Copy IP address from google query and paste into IP address -> Save
- Test First Filter: internal traffic, filter by IP
  - Reporting (at top) -> Real-Time (left nav) -> Overview
  - May take some time for the filter to take effect
- Copy filter to Master View:
  - Admin (at top) -> View pull down -> Master View
  - Filters -> Add Filter
  - Select: Apply existing Filter -> Select Filter -> Add -> Save

**Note:** Filters are applied in the order in which they are listed.

## 1.5 Assessment 1: 16/16 - 100%


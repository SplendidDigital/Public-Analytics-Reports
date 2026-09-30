# Public Analytics Reports for WordPress

**Public Analytics Reports** is a WordPress plugin that makes selected **Google Analytics 4 and Google Search Console** data available through a clean, shareable WordPress report—without requiring visitors or team members to log in to Google Analytics.

It is designed for **website owners, agencies, teams, publishers, and especially website flippers and digital-asset marketplaces** that need an easy way to present website performance.

## Key Features

* **Google Analytics 4 integration** for website traffic and engagement data.
* **Google Search Console integration** for search impressions, clicks, queries, and search performance.
* **Site Kit-style reporting interface** with sections for key metrics, traffic, search traffic, and content.
* **7, 14, 28, and 90-day reporting periods.**
* **Website selector** for installations managing multiple websites.
* Websites are displayed in **alphabetical order**.
* **Individual website reports** can be created using a shortcode:

  ```text
  [public_analytics_report domain="example.com"]
  ```
* **Multiple filters**, including traffic source, country, device, content/page, and search query.
* **PDF download** for creating a snapshot of the selected report.
* **Reusable shortcode** that can be placed on any WordPress Page or Post.
* **Administrator-only Google API diagnostics** to help troubleshoot API and property-access problems.
* Google OAuth credentials remain on the WordPress installation rather than being exposed to public visitors.

## Particularly Useful for Website Flipping

Website buyers often want evidence of a site's traffic and search performance before purchasing it. Traditionally, sellers may need to provide screenshots, exported reports, or temporary access to analytics accounts.

Public Analytics Reports provides another approach.

A website seller can create a dedicated analytics page such as:

```text
[public_analytics_report domain="example.com"]
```

and link to that page from a marketplace listing.

The prospective buyer can then review selected website performance data without receiving access to the seller's Google Analytics or WordPress administration.

This makes the plugin particularly suitable for **website flipping, digital-asset marketplaces, website brokers, and portfolio owners**.

## Useful for Teams and Clients

The plugin can also provide a simple way for people to monitor website progress without learning the full Google Analytics interface.

A team member, client, content writer, SEO specialist, or project manager can simply open the report URL and review the selected metrics.

This can reduce the need to distribute screenshots or create recurring manual reports.

## Example

A general report can be embedded with:

```text
[public_analytics_report]
```

A dedicated report can be created with:

```text
[public_analytics_report domain="calnzee.com"]
```

The same installation can therefore provide either a **multi-site analytics page** or **individual analytics pages for specific websites**.

## Data Sources

The reports use data from:

* **Google Analytics 4**
* **Google Search Console**

The plugin does not replace these services. Instead, it provides a focused WordPress-based presentation layer for selected analytics data.

## Typical Uses

* Website flipping and sales listings
* Digital-asset marketplaces
* Website portfolios
* Agency client reporting
* SEO progress reporting
* Content performance monitoring
* Small-team website management
* Public or semi-public project dashboards

**Public Analytics Reports turns selected Google Analytics and Search Console data into a simple, shareable WordPress report—making website performance easier to monitor, present, and communicate.**

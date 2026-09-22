# Scottish Delirium Association website

Status: source published in the public GitHub repository `amaclullich/scottishdeliriumassociation.com`. GitHub Pages is enabled from the `main` branch. The custom-domain DNS cutover was completed on 20 July 2026, and HTTPS is enforced for the canonical domain. GitHub is finalizing certificate coverage for the `www` alias.

## Purpose

This is a deliberately concise static archive for `scottishdeliriumassociation.com`. It describes the Scottish Delirium Association as active from 2011 to 2020, gives prominence to SIGN 157, links to NICE CG103 and the American Psychiatric Association's 2025 delirium guideline page, and preserves four historical SDA pathway PDFs with explicit safety labelling.

The site has no content-management system or forms. It uses a small amount of JavaScript for limited Google Analytics with a free opt-out and is intended for GitHub Pages. It can be edited through verbal instructions to ChatGPT Work.

## Analytics and privacy

The site uses the existing Scottish Delirium Association GA4 property and web stream:

- Property: `Scottish Delirium Association` (`388627474`)
- Stream: `Scottish Delirium Association` (`5560164822`)
- Measurement ID: `G-EZFGN38TH8`
- Stream URL: `https://scottishdeliriumassociation.com`

Limited analytics is on by default under the UK statistical purposes exception (PECR as amended by the Data (Use and Access) Act 2025). A notice on the first visit explains it, and visitors can turn it off at any time; once turned off, the Google Analytics script is not requested and no analytics data is sent. Advertising storage, advertising personalisation and Google Signals remain disabled. The stream measures page views, scrolling, outbound resource clicks and file downloads; email-address redaction is enabled. Event and user data retention are both set to 14 months.

The visitor's choice is stored locally in their browser under `sda_analytics_consent` for six months, after which the site asks again. Analytics cookies are configured for a maximum lifetime of one year and may be renewed on a return visit. The page provides permanent controls to review the choice or turn analytics off. Turning it off changes consent to denied, removes accessible `_ga` cookies and reloads the page without Google Analytics.

## Files

- `index.html` - the complete one-page site, including its CSS.
- `assets/sda-logo-mark.jpg` - historical square SDA logo copied unchanged from the local SDA materials.
- `assets/sda-logo-original.jpg` - historical horizontal SDA logo used for link previews.
- `downloads/historical-pathways/` - four unchanged pathway PDFs.
- `robots.txt`, `sitemap.xml`, `404.html` - basic static-hosting support files.
- `CNAME` - intended GitHub Pages custom domain.

## Historical pathway provenance

The four public downloads were copied unchanged from the maintainer's local historical SDA source archive. The workstation-specific source path is deliberately not recorded in this public repository.

Their embedded version information is:

- Comprehensive pathway: version 1.02 final, August 2016; review due August 2018.
- Summary pathway: version 1.03 final, August 2016; review due August 2018.
- Community care pathway: version 1.0, August 2016; review due August 2018.
- Care home summary pathway: version 1.0, August 2016; review due August 2018.

The files include clinical and medication content. They are presented only as historical records and are deliberately separated from the guideline links by a prominent warning.

## Deliberate exclusions

- The earlier 2013 pathway was not copied because the later 2016 versions supersede it for archival purposes.
- The 2013 TIME bundle was not copied because it is a Healthcare Improvement Scotland document and is not needed to explain the SDA archive.
- Research papers, grant documents, personal presentations and hip-fracture materials found in the old SDA storage folder were not copied because they are not clearly SDA website outputs.
- The old SDA pathway page on Right Decisions is not presented as current guidance. It says it was last reviewed in October 2018 and was due for another review in February 2025.

## Editing and publishing workflow

1. Ask ChatGPT Work for changes in plain language.
2. Preview the site locally on desktop and mobile.
3. Publish the approved files to the `main` branch of the GitHub repository.
4. GitHub Pages automatically rebuilds the site from the repository root.
5. Verify the public domain and key downloads after each substantive change.

This local folder is connected to `https://github.com/amaclullich/scottishdeliriumassociation.com`. GitHub command-line authorization was deliberately not granted because the requested permission scope included private repositories; publishing used the existing scoped GitHub connection instead.

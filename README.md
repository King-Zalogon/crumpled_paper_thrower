# Agency Site Registry

This repository contains a public minimal registry of official homepage URLs for real-estate agencies known to Property Radar.

The canonical file is:

`agencies.txt`

Format:

- one URL per line;
- URL only;
- no names;
- no metadata;
- UTF-8;
- LF line endings;
- sorted;
- deduplicated.

A URL is added when it is not already present after conservative normalization and it is the official homepage of a real-estate agency. Scraping suitability is not part of inclusion.

This repository does not publish agency names in the registry file, compliance findings, robots results, scraper suitability, extractor information, monitoring state, source diagnostics, private notes, listing data, or contact data. Those remain in the private Property Radar project.

Remove a URL only when it is a duplicate, has incorrect ownership, is not actually a real-estate agency, has been replaced as the official site, is permanently dead, or was an accidental portal or social URL. Difficulty scraping the site is not a removal reason.

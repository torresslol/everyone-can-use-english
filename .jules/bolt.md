## 2024-05-24 - Unshortening URLs for Performance
**Learning:** The application uses short URLs like is.gd which introduces unnecessary network latency via server-side HTTP redirects. In addition, HTTP redirects break the CI pipeline link checker. Replacing them with direct HTTPS links is a measurable performance optimization that eliminates the latency of a 301/307 redirect.
**Action:** Upgraded all is.gd shortlinks to their direct HTTPS destinations.

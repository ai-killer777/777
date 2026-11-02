# Fiverr / 承包商外包工作單模板

**標題：** Audit + restore WordPress Forum / VIP membership integration (no rebuild unless approved)

**背景：** We own or manage a WordPress-based website. Forum and VIP membership features may rely on another backend/service and are not fully documented. We need evidence-based diagnosis and limited-scope repair, not an unsolicited full redesign. The legal-content publishing workflow is a separate scope.

**Phase 1: READ-ONLY AUDIT (fixed price)**
1. Identify actual tech stack, plugins, external services, hosting and data sources for Forum/VIP (with redacted evidence).
2. List access and assets missing from the previous contractor; do not assume that the database exists.
3. Document exact cause, options, dependencies, estimated cost, risks, and an implementation quote.
4. Do not modify production, migrate data, or request plaintext passwords.

**Phase 2: REPAIR / CONFIGURATION (quote separately, only after approval)**
1. Work in staging with least-privilege access.
2. Prove standard user/VIP permissions, Forum read/post access, admin moderation where applicable.
3. Maintain existing user data; preserve ability to roll back.
4. Deliver all changed source files, plugin/config inventory, deployment notes and testing evidence.

**Separate WordPress article publishing milestone:**
- Configure or repair native Posts workflow, categories/tags, author/editor roles, editorial review and SEO settings.
- Publish 3 approved sample articles and demonstrate repeatable bulk import workflow only if requested.
- No fabricated lawyers, certifications, clients, testimonials, or unreviewed legal advice claims.

**Required handover:** source repository/patch, site & DB backup, documented third-party dependencies, ownership of licences/accounts, staging URL, evidence of passing acceptance tests, rollback steps, post-delivery fix window.

**Acceptance:** Owner can login with owner-controlled account; demonstrable standard/VIP access restrictions; forum actions pass tests; 3 sample articles display correctly on desktop/mobile; no broken legacy data; backups verified; all assets handed over. Do not pay final milestone based solely on screenshots.

**Vendor screening:** Ask for one relevant WordPress membership/forum integration example; require a short diagnosis methodology; compare fixed-price audit quotes separately from repair quotes; avoid vendors who demand full production access before a scoped audit.

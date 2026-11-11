# Public tracker state

Sanitized job listings, job ids, and referral statuses for the job search dashboard.

This repository does not contain referral contact names, profile URLs, notes, emails, or phone numbers. That history stays on the local machine. Do not replace the local tracked_jobs.json with these files. Apply status updates with overlay_private from the dashboard repo so local contacts are kept.

Allowed fields are listing text (company, title, location, posting URL, fit notes), job ids, applied and skipped ids, and referral status. Contact objects are empty. Skipped free-text reasons and referral notes are omitted.

# portfolio-content

Content for the portfolio site. The site reads these files at runtime (refreshed every ~5 minutes), so editing them here updates the live site without a redeploy.

- `profile.json`: name, hero text, about, contact, photo and CV paths
- `skills.json`: skills (`icon` = built-in name, or `iconUrl` for any image)
- `experience.json`: jobs and their projects
- `projects.json`: projects and case studies
- `education.json`: education
- `images/`, `files/`: assets, referenced from JSON by relative path (e.g. `images/profile.jpg`)

Keep the JSON valid: a broken file makes the site fall back to its bundled copy.

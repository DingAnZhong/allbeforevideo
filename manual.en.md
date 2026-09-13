# AllBeforeVideo User Manual

AllBeforeVideo manages the complete script-production flow as projects. After login, choose Original Script, Source to Storyboard, or Script Diagnosis from the project workspace; tasks, versions, and results stay with that project.

## Quick start

1. **Sign up / log in**: register with an email code — new users get 200 credits; an invite code grants both sides 100.
2. **Top up (optional)**: buy credits via WeChat QR on the top-up page; daily check-in earns credits too.
3. **Create a project**: choose Original Script, Source to Storyboard, or Script Diagnosis in the project workspace, then provide a name and initial content.
4. **Generate & export**: open the project and follow its flow. Progress, versions, and results stay together. Download a script as Markdown, the storyboard/script as CSV or a zip with images, or a complete series as a ZIP.

## Features

### Project workspace & creation (core)

- The page shown after login is the project workspace. There are three top-level project types: **Original Script**, **Source to Storyboard**, and **Script Diagnosis**.
- An Original project can be a single work or a series. Series is a creation setting inside Original, not a fourth project type.
- Source to Storyboard accepts either **novel source text** or an **existing script**. Novel source follows the digest, series-outline and episode flow; an existing script goes directly to storyboarding.
- Pinned projects appear first and the rest are ordered by recently opened. Use the Project Library to search, open, import, export, or duplicate projects as the list grows.
- Chat-driven generation supports requests to revise outlines, shots, and dialogue. Each generation task is billed independently.
- Scripts open in Scene editor by default, with Shot parameters, Preview, and Source (advanced) also available. Direct edits do not use AI credits; save before downloading or finalizing.

### Stop & resume tasks

- The task card shows live progress. You can stop a running task; actual usage already incurred is still settled, and the task is not marked complete.
- Once a task card has appeared, progress is restored after a refresh, disconnection, or reopening the project. A failed task can continue only when the UI offers "Continue unfinished steps" or "Retry".
- If the connection drops immediately after you click Generate but before a task card appears, do not click repeatedly. Note the time and contact support for a check.

### Version scope

- Outline and script history can be selected in the results panel. Old versions are read-only; "Continue from this version" creates a new version without overwriting history.
- Linked artifacts—including novel digests, series outlines and episodes, storyboards, and diagnosis reports—also keep history, but the current UI does not yet offer a history selector for them.

### Tone & director style

- When starting a creation you can pick a **tone** (horror / suspense / comedy / sci-fi / hot-blooded) and a **director style**; the tone sets atmosphere, the style sets camera and storytelling. They combine freely.
- Leave both unset and the AI matches common techniques from the genre automatically.

### Materials library

- Upload txt/md/epub/docx (≤10MB; epub/docx parsed locally in your browser). Type `@` while creating to reference a material.
- Compress very long sources first, then reference the compressed copy — fewer credits, steadier results; the original is always kept.
- "Export all" packs the whole library into a zip file; "Import" merges entries back by name. Each material can also be downloaded as a txt file.

### Characters & props

- The "Characters & props" tab in the workspace keeps a per-project library of characters and props: create entries manually, or use "Import from script" after generating a script.
- Fill in each entry's **visual description** and scene sketches will automatically carry it, keeping the same character consistent across shots; without entries, sketches behave exactly as before.
- Each entry can get a reference image (billed per image; regeneration overwrites the old one). Data and images stay on your device and are included in project backups.

### Memory system

- Memory is off by default and participates in creation only after you turn it on. While off, it is not collected or injected, neither automatic nor manual organization can run, and no new memory-organization task or charge is started. Existing memories remain available to inspect, edit, delete, and export.
- While enabled, automatic organization runs only after a successful task. Only durable writing preferences that you explicitly express and that do not depend on a particular story may be reused across projects; characters, worldbuilding, and project experience remain inside the current project.
- The current project never reads settings or experience from another project, including through an `@project-name` mention or a direct path to another project's memory. "My memory" supports manual organization; complete backups are managed in Profile → Data backup and recovery.

### Credits & payments

- Billing follows the rates published on the in-app "Credits & payments" page; credits are prepaid before generation and settled by actual usage afterwards.
- Top up via WeChat QR; daily check-in grants 100 (day 7 grants a bonus 100); inviting a friend grants both of you 100.

### Invite friends

1. **Find your invite code**: after login, open Profile — "My invite code" is shown there and can be copied for your friends.
2. **How a friend uses it**: on the sign-up page, your friend enters the code in the "Invite code (optional)" field and completes registration.
3. **Rewards for both sides**: your friend gets 300 credits on day one (200 sign-up grant + 100 invite bonus), and you get 100 credits at the same time — both are credited instantly.
4. **Notes**: the invite code can only be entered during sign-up and cannot be linked afterwards; a wrong or invalid code does not block registration, it just means no invite bonus for either side; during promotions the invite bonus may be multiplied — see site announcements.

### Data & backup

- Projects, creations, materials, and memories stay in **your browser's local storage** by default. The Project Library supports per-project export/import, and Profile can import/export complete backups. An active standard subscription can explicitly enable encrypted cloud backup (off by default, one latest snapshot, up to 100 MiB of original content); boost cards do not include it.

## Boundaries

- **Refunds**: credits are instant virtual goods; unconditional refunds are not supported. Billing anomalies can be appealed within 30 days.
- **Invoices**: contact support, handled manually.
- **Alipay**: not available yet; WeChat QR is supported.
- **Mobile**: the responsive web app uses a single-column switcher on phones and drawers for projects and creation controls on tablets.
- **Export**: single scripts as Markdown; storyboard/script as CSV or a zip with images (files under images/); the materials library as a zip; and a complete series as a ZIP containing one Markdown file per episode.
- **Cross-device sync**: no automatic sync by default; use complete backup export/import or explicitly enable encrypted cloud backup with an active standard subscription.

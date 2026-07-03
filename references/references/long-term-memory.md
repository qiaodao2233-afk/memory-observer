# Long-Term Memory Storage

Use this reference when setting up customer deployments or deciding where memory should live.

## Storage Options

Prefer this order:

1. Repository private folder: `.private/memory-observer`
2. Local-only folder: `E:\AI\memory-observer-data`
3. Customer-provided secure folder

Do not assume a folder is private because of its name. A repository folder is private only when the repository access is private or the folder is ignored/encrypted.

## Safe Default

For this workspace, use:

```text
E:\AI\.private\memory-observer
```

Keep `.private/` in `.gitignore` by default. This protects raw logs, profile details, reminders, and emotional records from accidental commits.

## Customer Repo Mode

If a customer explicitly confirms the repository is private and wants memory tracked in git, use:

```text
private/memory-observer
```

Before committing, confirm:

- the repo is private
- the customer accepts storing personal memory in git history
- no credentials, cookies, phone numbers, or sensitive third-party data are included

## Weekly Memory Pass

Once per week:

1. Read the current week's daily logs.
2. Write `weekly/YYYY-Www.md`.
3. Update `memory-summary.md` with durable patterns only.
4. Keep raw diary details in dated logs.
5. Use `memory-summary.md` first for future recall across long periods.

The long-term summary should stay short enough to read quickly.

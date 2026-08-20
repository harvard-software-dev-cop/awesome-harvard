# Contributing

Thanks for adding to the list! A few rules to keep it useful and consistent.

## Adding a resource

1. Pick the topic area the resource is most relevant to (e.g. CI/CD and Automation, Secure Services and Practices, or AI-Assisted Development).
2. Add a single line in this format, keeping entries alphabetized by title within the section:

   ```markdown
   - [Resource Name](https://example.com) - Brief, one-sentence description of why it's useful.
   ```

3. Open a pull request with a meaningful title (e.g. `Add <Resource Name> to <Section>`). One resource per PR is preferred, but small batches for the same section are fine. If you're seeding a section on behalf of a tiger team, a single larger PR is welcome — say so in the title (e.g. `Seed CI/CD and Automation`).

## Guidelines

- Check the link isn't already listed (in this or another section) before adding it.
- Verify the link resolves to the actual resource. Harvard logins are fine; links you personally can't open, or that sit behind a paywall, are not.
- Make sure most of the community can actually reach the link: public works, so does internal-visibility on Harvard's [GitHub Enterprise](https://github.com/enterprises/harvard-university), and so can a shared drive or wiki page if its sharing setting is opened to the Harvard community rather than restricted to one team. Check the permission on the specific link, not just the platform it's hosted on.
- Keep descriptions factual and short — say what it is, not why you like it.
- Resources should be genuinely useful to Harvard's Software Development Community of Practice — general best practices and tools are welcome, and so are Harvard-specific or internal resources.
- If a topic area isn't listed yet, open a PR adding a new `##` section for it instead of shoehorning entries into an existing one.
- AI-assisted contributions are welcome — just verify accuracy and keep the diff scoped to your change (don't let a tool reformat unrelated entries).

## Removing a resource

If a link is dead, duplicated, or no longer relevant, open a PR removing it with a short note why.

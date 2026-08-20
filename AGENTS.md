# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

<!-- Add product-specific terms and preferred usage -->
<!-- Example: Use "workspace" not "project", "member" not "user" -->
 - Use **EcoWestern** for the company.
 - Use **EcoWestern EcoSystem** for the connected product family.
 - Use **Economic ID**, **Azura**, and **eChat** exactly as branded.
 - Use **Economic Organization** for organizations.
 - Do not use “Eco ID” or “EcoVerify” as product names.

## Style preferences

<!-- Add any project-specific style rules below -->

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
 - Keep the visual language warm, grounded, and calm. Prefer clear hierarchy over decorative effects.
 - Use sentence case for headings and descriptive link labels.

## Content boundaries

<!-- Define what should and shouldn't be documented -->
<!-- Example: Don't document internal admin features -->
 - Do not document internal admin features or unpublished product behavior.
 - Separate consumer Economic ID guidance from developer and organization-administrator implementation details.
 - Do not promise recovery, deletion, expiration periods, global sign-out, or support outcomes unless confirmed by product behavior.
 - Tell users to try self-service recovery first. If it fails, direct them to the built-in support ticket system and remind them not to share secrets.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

GitHub-platform plumbing for the BitWiseProjects org — the public org profile README (`profile/README.md`) and, if added later, default community health files (issue templates, `CONTRIBUTING.md`) that other org repos fall back to. Public, since the profile README only renders on the org's public page if this repo is public.

## Scope discipline

Do exactly what's asked. Nothing more.

No unrequested prose. No rationale, "why" paragraphs, or thesis-length write-ups. No expanding a list into an essay. No extra sections, caveats, or examples nobody asked for. If it wasn't asked for, it doesn't go in the file — say it in chat instead.

## Git / PR etiquette

Never add `Co-Authored-By:` trailers or other co-authored/AI attribution to git commits, PR descriptions, or PR comments.

**Branches, commits, and merging.** Never commit to `main`. Each new session starts on its own branch — `git switch -c <short-slug>` — before the first edit. If `main` isn't level with `origin/main`, push it first.

Commit incrementally on the branch as pieces land; small and frequent, since the squash discards them.

**"Land it"** means the full cycle: push the branch, open a PR, squash merge it, delete the branch both locally and on the remote, switch back to `main` and pull.

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub profile repository (`puppyizm/puppyizm`). Its only file is `README.md`, which GitHub automatically displays on the profile page at github.com/puppyizm.

## Repository Contents

- `README.md` — GitHub profile README; rendered as the public profile page. Uses a mix of HTML and Markdown, with centered images and a link to the owner's novel at enterthespiral.neocities.org.

## Working with the README

There is no build process, package manager, or test suite. Changes to `README.md` are reflected on the GitHub profile immediately after pushing to `main`.

Image assets are hosted via GitHub's CDN (uploaded through GitHub's issue/PR attachment flow) and embedded as absolute URLs.

## Conventions

- The file uses raw HTML (`<center>`, `<html>`, `<body>`) alongside Markdown image syntax — preserve that style when editing.
- Keep commented-out boilerplate at the bottom (the GitHub-generated template block inside `<!-- -->`) as-is unless explicitly asked to remove it.

# navylily.tv Quartz configuration

This public repository contains only the Quartz configuration and custom styling for [navylily.tv](https://navylily.tv). It does not contain the Obsidian vault, published pages, images, or deployment credentials.

To use it, start with a compatible Quartz checkout, copy `quartz.config.yaml` to its root and `quartz/styles/custom.scss` to the corresponding styles directory, then supply your own `content/` vault. The configuration excludes `.obsidian` metadata while allowing the vault's notes and assets to publish.

The local site also has small component changes that are documented here but not published in this repository. In `quartz/components/Head.tsx`, dark mode is the first-visit default and Explorer folders are expanded automatically. In `quartz/components/RootPageTitle.tsx`, the page title links to `/`. A saved theme preference may override the first-visit default. Apply those changes separately if you want the same behavior.

This repository is configuration only. Publishing to the live domain uses the site's separate deployment process.

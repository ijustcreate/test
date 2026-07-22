# Felix D&D

Public illustrated campaign archive and lightweight browser tabletop for Felix, Ember, Astral, and guests.

## Included

- Responsive landing page for desktop, iPhone, and tablets
- Eighteen-chapter illustrated storybook reader
- Searchable and filterable campaign atlas
- Eighty linked campaign records with aliases and source provenance
- Twenty-nine-event campaign timeline
- Fourteen-location interactive campaign map
- Characters, creatures, places, artifacts, powers, quests, lore, quotes, rules, and unresolved threads
- Dice roller with advantage, disadvantage, modifiers, and roll history
- Initiative and hit-point tracker
- Encounter reference cards
- Session notes and campaign clock
- Browser-local persistence
- JSON save export/import for moving a game between devices
- GitHub Pages deployment workflow

## Public data model

All campaign content is public. Each record keeps its category, labels, canonical name, aliases, relationships, source attribution, and linked records. Unresolved mysteries remain explicitly labeled instead of being silently converted into answers.

## Running locally

Serve the repository root with any static web server, or open the deployed GitHub Pages site. No server-side database is required. Table state is stored in the current browser; use the JSON export before switching devices.

## Deployment

The Pages workflow in `.github/workflows/deploy-felix-dnd.yml` publishes every push to `main`.

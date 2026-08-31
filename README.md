# Actionist Components

Public gateway to the component supply used by Actionist research and UI composition. This repository is an index and provenance surface; it does not vendor third-party component payloads.

## Browse

- Live catalog: https://siso-component-catalog.pages.dev/
- Catalog and UI workflow source: https://github.com/sisodias/siso-ui-base
- Source-bearing legacy design library: https://github.com/sisodias/siso-design-system
- Actionist research portal: https://actionist-system-map.pages.dev/

## Observed corpus

- 7,949 indexed 21st.dev component identities
- 75 taxonomy tags and 7 catalog groups
- 5,205 source retrievals in the August 29 source-harvest receipt; 4,008 measured self-contained and 1,197 with UI sibling imports
- 2,744 unavailable outcomes, including 1,629 CDN 404-gated records
- 3,508 legacy component identities in the source-bearing design-system store

These are discovery and reference assets, not automatically admitted Actionist blocks. Source availability, dependencies, provenance, rights, compatibility and product qualification remain separate gates.

## Agent route

1. Search the live catalog or its /index.json.
2. Resolve the identity and upstream URL.
3. Check siso-design-system for an existing source-bearing legacy record.
4. Use siso-ui-base for catalog, ranking, preview and human taste-loop machinery.
5. Treat any local source-harvest record as provenance-bound evidence until its rights and dependency closure are reviewed.

The Actionist front door will carry the machine-readable join from component identity to source, taxonomy, block family and repository.

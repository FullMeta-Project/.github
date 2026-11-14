# FullMeta ecosystem

FullMeta is a workspace for application documents and simulation tools.

[Browse FullMeta repositories](https://github.com/search?q=user%3Agbaswfm2021%20topic%3Afullmeta&type=repositories) — results include only repositories you can access.

- **Distribution:** [FullMeta](https://github.com/gbaswfm2021/FullMeta)
- **Platform:** private source
- **Applications:**
  - [FEM](https://github.com/gbaswfm2021/fem) — finite-element modelling
  - [Raytracing](https://github.com/gbaswfm2021/raytracing) — raytracing application

The linked repositories are maintained separately under the existing GitHub account.

## Workspace folders

The list shows where components live in a local FullMeta workspace. Application folders are present when those applications are installed. Click an application folder to open its development repository.

- `FullMeta/` — workspace root
  - `index.html` — workspace entry
  - `index.json` — workspace document
  - [`platform/`](https://github.com/search?q=user%3Agbaswfm2021+topic%3Afullmeta+is%3Aprivate&type=repositories) — shared platform and workspace; link searches private repositories you can access
  - `applications/` — application packages
    - [`fem/`](https://github.com/gbaswfm2021/fem) — FEM application
      - `catalog.json` — FEM descriptor
    - [`raytracing/`](https://github.com/gbaswfm2021/raytracing) — Raytracing application
      - `catalog.json` — Raytracing descriptor
  - `projects/` — user project files

FEM and Raytracing are developed in their separate repositories linked above. Each application package belongs in its corresponding folder under `applications/` in a FullMeta workspace; the root `catalog.json` identifies it to FullMeta. `projects/` holds user data.

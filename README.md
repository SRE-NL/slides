# SRE NL meetup presentations

[![Latest publish](https://github.com/SRE-NL/slides/actions/workflows/publish.yml/badge.svg)](https://github.com/SRE-NL/slides/actions/workflows/publish.yml)

This repository contains the presentations from the SRE NL meetups.

## How to add event slides

1. Install [hugo](https://gohugo.io/getting-started/installing/).
2. Clone this repository.
3. install [pre-commit](https://pre-commit.com/) and run `pre-commit install`.
4. Create a new branch.
5. `hugo new -k event posts/host-date/`.
   This will create the directory structure in `content/posts/host-date/` using event archetype.

   ```text
   posts/host-date
   ├── files
   │   └── .gitkeep
   └── index.md
   ```

6. Add the slides in the `files` directory.
7. Update the `index.md` with the event details.
8. Create a PR, Once the PR is merged, the slides will be published automatically.

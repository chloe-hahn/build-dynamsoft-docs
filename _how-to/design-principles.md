---
layout: default
title: Design principles
nav_order: 1
---

# Design principles

To simplify the maintenance of docs, 

- About versioning of the docs

    - We will upgrade the docs on releasing a major upgrade, e.g., v8.x -> v9.x
    - If necessary, we may upgrade the docs on a minor release.

-  Archive the history versions

    - The history versions will be hosted on the server statically. They will be archived in a dedicated folder, example, /docs-archive/v8.x/
    - When we make changes in the *master* or *preview* branch, the history versions will not be impacted.

- Branches

    - We create a branch for each of the history versions. 
    - The *master* branch will only include files of the latest version.

- About versioning of a page

    - If a page exists in multiple versions, when toggling the version dropdown, the docs system supports looking for the page of a selected version.
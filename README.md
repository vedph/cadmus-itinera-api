# Cadmus Itinera API

This is the second iteration of Itinera and will replace the [old repository](https://github.com/vedph/cadmus_itinera_api).

Quick Docker image build:

```bash
docker build . -t vedph2020/cadmus-itinera-api:5.0.3 -t vedph2020/cadmus-itinera-api:latest
```

(replace with the current version).

## History

- 2023-05-29: updated packages.

### 5.0.3

- 2023-05-26:
  - added entry to `metadata-types` thesaurus.
  - updated packages to fix save node/triple in graph.

### 5.0.2

- 2023-05-26:
  - updated packages.
  - added thesauri for role-dependent events.

### 5.0.1

- 2023-05-26: updated `ReferencedTextsPart` to use `AssertedCompositeId` for `targetId`.

### 5.0.0

- 2023-05-25: updated packages (breaking change in general parts introducing [AssertedCompositeId](https://github.com/vedph/cadmus-bricks-shell/blob/master/projects/myrmidon/cadmus-refs-asserted-ids/README.md#asserted-composite-id)).
- 2023-05-18: updated packages for graph infrastructure (see [here](https://myrmex.github.io/overview/cadmus/dev/history/b-graph/)).

### 4.2.0

- 2023-05-17: updated packages for minor model changes in Codicology and Itinera.

### 4.1.3

- 2023-05-16: updated packages and renamed containers in docker-compose.
- 2023-05-12: updated packages and increased length of appsettings `SecureKey`.

### 4.1.2

- 2023-04-21: updated thesauri.
- 2023-04-13: updated packages.

### 4.1.1

- 2023-02-27: updated packages (changed event model).

### 4.1.0

- 2023-02-27: updated packages (changed event model).

### 4.0.5

- 2023-02-20: changed label for literary work facet in configuration.

### 4.0.4

- 2023-02-17: updated packages.

### 4.0.3

- 2023-02-11: updated core packages (updated geo model).

### 4.0.2

- 2023-02-08: fixes to events thesauri.

### 4.0.1

- 2023-02-08:
  - updated Codicology packages.
  - updated events thesauri.

### 4.0.0

- 2023-02-02: migrated to new components factory. This is a breaking change for backend components, please see [this page](https://myrmex.github.io/overview/cadmus/dev/history/#2023-02-01---backend-infrastructure-upgrade). Anyway, in the end you just have to update your libraries and a single namespace reference. Benefits include:
  - more streamlined component instantiation.
  - more functionality in components factory, including DI.
  - dropped third party dependencies.
  - adopted standard MS technologies for DI.

### 3.0.8

- 2023-01-26:
  - updated thesauri.
  - updated packages (author IDs in literary work info).

### 3.0.7

- 2023-01-25: updated packages.
- 2023-01-24:
  - updated packages (added `eid` pin to codicology decorations part).
  - added metadata part to person items.
  - changes in thesauri.

### 3.0.6

- 2023-01-22: changed events part related entities thesaurus types separator from `.` to `:`.
- 2023-01-19: added geography parts.

### 3.0.5

- 2023-01-12: updated packages.
- 2023-01-10:
  - updated version of biblio API in Docker compose.
  - updated packages.

### 3.0.4

- 2022-12-22: updated packages.

### 3.0.3

- 2022-12-12: thesaurus update.

### 3.0.2

- 2022-11-30: updated packages.

### 3.0.1

- 2022-11-18: updated event thesauri.

### 3.0.0

- 2022-11-11: fix to thesaurus.
- 2022-11-10: upgraded to NET 7.

### 2.1.8

- 2022-11-08: updated thesauri.

### 2.1.7

- 2022-11-03: updated packages.
- 2022-10-24: updated packages.
- 2022-10-11: updated packages and injection in `Startup.cs` for new `IRepositoryProvider`.
- 2022-09-24: updated biblio Docker image version in script (2.1.5).
- 2022-09-19: updated biblio Docker image version in script (2.1.4).

### 2.1.6

- 2022-09-14: updated packages.
- 2022-08-26: updated to include preview infrastructure.

### 2.1.5

- 2022-08-05: updated packages.

### 2.1.4

- 2022-08-03: updated packages.
- 2022-08-01: updated packages.

### 2.1.3

- 2022-07-22: updated packages and some thesauri.
- 2022-06-28: updated packages.

### 2.1.2

- 2022-05-20: updated packages.

### 2.1.1

- 2022-05-08: upgraded packages (added author to literary work info part).

### 2.1.0

- 2022-04-29: upgraded packages to NET 6.0.

### 2.0.2

- 2022-04-12: updated models packages (added note to poem ranges part) and added thesaurus.

### 2.0.1

- 2022-04-04: updated thesauri and packages for refactored related persons part.
- 2022-04-01: updated thesauri.

### 2.0.0

- 2022-03-07: updated thesauri.
- 2022-01-20: updated version numbers after minor model changes.

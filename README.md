# Cadmus Itinera API

This is the second iteration of Itinera and will replace the [old repository](https://github.com/vedph/cadmus_itinera_api).

Quick Docker image build:

```bash
docker build . -t vedph2020/cadmus-itinera-api:2.1.8 -t vedph2020/cadmus-itinera-api:latest
```

(replace with the current version).

## History

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

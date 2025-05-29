# pgvector_compiled

Precompiled OS packages (zips) for pgvector on Windows.

The [Releases](https://github.com/levovs/pgvector_compiled/releases) page contains the compiled versions of pgvector for PostgreSQL 17.
The version number format is `v0.<POSTGRESQL_VERSION>.<INCREMENT>` where increments increases by one for each commit to this repo.

## Usage

1. Download the zip for Windows from the [Releases](https://github.com/levovs/pgvector_compiled/releases) page.

2. Extract the zip to get the files.

3. Add the files to your PostgreSQL installation folders:

### Windows

- `/lib/vector.dll`
- `/share/extension/vector*.sql`
- `/share/extension/vector.control`
- `/include/server/extension/vector/halfvec.h`
- `/include/server/extension/vector/sparsevec.h`
- `/include/server/extension/vector/vector.h`

---

This repository is a fork of [pgvector_compiled](https://github.com/portalcorp/pgvector_compiled) and is maintained at [https://github.com/levovs/pgvector_compiled](https://github.com/levovs/pgvector_compiled).

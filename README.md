# Repolex Knowledge Graph of jaraco/pytest-perf

RDF knowledge graph data for [jaraco/pytest-perf](https://github.com/jaraco/pytest-perf), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download jaraco/pytest-perf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 33249c0b401763c8b46fcdde5b3a0e19c00b7029
│   │   │   └── chunk-001.nq.gz
│   │   └── b565f96a8cc1b5d89e996d6ae8eb54b808bc8ac4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 33249c0b401763c8b46fcdde5b3a0e19c00b7029.nq.gz
│   └── repolex
│       ├── 33249c0b401763c8b46fcdde5b3a0e19c00b7029
│       │   └── chunk-001.nq.gz
│       └── b565f96a8cc1b5d89e996d6ae8eb54b808bc8ac4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a4e08c675ff9e597f2a28e78650b1a4ec1c1d2b.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 1bb5a44356f00884a71ceeefd24ded6caaba2418.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 20fbbfc1c095baf9f8c72902b24296b50ad3ab9d.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 32150488de655c2c2ef3b26c0a8519e7365584b3.nq.gz
│   ├── 35b98b1df96093e99fea65bec2187baff3c12514.nq.gz
│   ├── 3604f01f181265ba2469efe489dd9fb1b51efcf6.nq.gz
│   ├── 44ecd9eab5e0416187676c0b7c2661398cc8cb22.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 562d457758e398d69d718b0696fe99a4e981141b.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5a4a7e9166ec3143f71b5e3875860802048554f3.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 65fb958e16694c7bf1dc8eb19a5013a760044c52.nq.gz
│   ├── 6fa480e44f38768722368d7a986607adacf41d99.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 70612985a7a6f8ae0e29777e7ed3df05e5a717dc.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 736e3f1aa56dfe007f23f2f2b68990f4452fcc8f.nq.gz
│   ├── 7621dc0d3623546e42dc425fe07550ec50ca2914.nq.gz
│   ├── 7f6a535322cf9a99ebccbc5957c489fcae89c9cc.nq.gz
│   ├── 85dfea9d42d16274b4e8a4892bf6986d131f4241.nq.gz
│   ├── 89ff33961ba3d6f9cda89322a1fdbf1ac2e35513.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9d20e110ba75cb3bd411cf97ced226abca395a69.nq.gz
│   ├── a5d2903869a2e79b56b2a2f77731b5cf06e06992.nq.gz
│   ├── ac0ff69e22507b430cfb9a91d98e2451a3de52d9.nq.gz
│   ├── b1377ada792519f189dd504b44002ff984ebd5cf.nq.gz
│   ├── b4f7800944ee14b07c217aa86b041ae2adfe650a.nq.gz
│   ├── b6f972769e61a5e65f9f45015b363cc362487e55.nq.gz
│   ├── b88366125985a2737a238f252fd374b550f2851f.nq.gz
│   ├── b8925fd55ecbbc86985186d12680204d6dd6507a.nq.gz
│   ├── dbba87919917c817af9fb980431c93574466a53c.nq.gz
│   ├── dfe8b5e71e8848f953bb991caee4f8f66a4572dd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0b35f1b83fe6fd2ca44fd2d3712a90817d51ab8.nq.gz
│   └── f99e49e00576cf83c08337d2993b560eb89f8991.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 33249c0b401763c8b46fcdde5b3a0e19c00b7029.nq.gz
├── filetree
│   ├── 33249c0b401763c8b46fcdde5b3a0e19c00b7029.nq.gz
│   └── b565f96a8cc1b5d89e996d6ae8eb54b808bc8ac4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 55 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[jaraco/pytest-perf](https://github.com/jaraco/pytest-perf)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*

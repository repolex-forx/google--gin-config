# Repolex Knowledge Graph of google/gin-config

RDF knowledge graph data for [google/gin-config](https://github.com/google/gin-config), parsed by [repolex](https://repolex.ai).

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
rlex download google/gin-config
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bda557dedb8c64d352ece8328eee6c7b01c8931f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bda557dedb8c64d352ece8328eee6c7b01c8931f
│           └── chunk-001.nq.gz
├── blob
│   ├── 03d7c5f4533ea68c757c87a1ccc81a34bcb80269.nq.gz
│   ├── 0536d7747cdbe7313dd132673dc2bdb30ebe132b.nq.gz
│   ├── 075323d0669d9166019c622b0c510f0c1f941bdb.nq.gz
│   ├── 11def0490d5c1b0c7ab299b6ec3849f33d86d735.nq.gz
│   ├── 1327b2204963b7fa096775f6808e526611ff112b.nq.gz
│   ├── 16104bd65055d50735101e96bbcb5aa4e1acaa25.nq.gz
│   ├── 1c95ffbf410dd9338b2166274d22488734e6764f.nq.gz
│   ├── 1cfdcd120c750eb889f80075f0b5bf81a48573d8.nq.gz
│   ├── 1d42537407043c9869e2d94dcc6b15f555723d69.nq.gz
│   ├── 20d0a22e0ba66c1d8731a3ec13edcf127534ae1b.nq.gz
│   ├── 2494c1660ebaebba55188d6f2d4513aa2161153d.nq.gz
│   ├── 26b041a138e28542257ad2bff2bebc4834c67163.nq.gz
│   ├── 30087bc07ded96a81681535937ccf242e712e22d.nq.gz
│   ├── 35da5f837968a18b2741ce9b87e030ba99dc410a.nq.gz
│   ├── 3ba03c431424a0d611d57e9d6095c1e41fcf43a0.nq.gz
│   ├── 3e9aabc0f98e506d16b448997c63822a54753d20.nq.gz
│   ├── 416931fbe4535415c39b7ebc3ecb24ae46deb51b.nq.gz
│   ├── 4a6d0dc049f4610e5fd092be2fba0bfdabc533fc.nq.gz
│   ├── 4fdc980175d363070f65dd91de611aed6dc190e0.nq.gz
│   ├── 507ea3fb3d8b475e8dbb515aeb5b59b0831efdbf.nq.gz
│   ├── 518dd455efcae0a84b4b1b5e2ba2cb6e06ae5d5d.nq.gz
│   ├── 5310fcdbdfa3a90f9ab44762fe6146ce27ba0df3.nq.gz
│   ├── 5a7760750938755b8882587737d08f93c4196e40.nq.gz
│   ├── 60bc06528d175e662ee3287c42fbcb0649c1b99b.nq.gz
│   ├── 6465299bda39e7b8dd35287bd76fb17af8b4ac87.nq.gz
│   ├── 7520c643f879007883579db18d8154e82d34bb75.nq.gz
│   ├── 93f39b3eb863cc56b1b696bb22ab571857f6f63f.nq.gz
│   ├── 94b6c164d370f5dd5dbaf91f101a72d3d2823952.nq.gz
│   ├── 970943a564541c5997824c32f6d49bc9ef9a5a68.nq.gz
│   ├── 9816050e6bcc2fda6658f0e4a20c3cb8f21149ff.nq.gz
│   ├── 990f5d19f0de8dc290ea9340ad5434fa82ec2b48.nq.gz
│   ├── 99cfda81ec6a7c555796399b231ffeccc26d3e22.nq.gz
│   ├── a0ad5f9f5b440d6dac4f5072e9e01c8ee9905a96.nq.gz
│   ├── ad43ffcc648b823b7cfe6201db93757932e760d7.nq.gz
│   ├── b2769f6209873df784ee249984fbc0b58a167b11.nq.gz
│   ├── c951c65d3517fc7ac87a170cbcb53ab8f6a9ff9e.nq.gz
│   ├── cc0e1e231a933d1d4d02525f813f7f4a375f8212.nq.gz
│   ├── cdf363609b59524318200fb4e75a65c24f5a649f.nq.gz
│   ├── d3b3087cf309f3e5a4746d51323f43c92a73a1b8.nq.gz
│   ├── d953bf25dffbdf6f25c353a31ca1d84765df0927.nq.gz
│   ├── db3e8c0da3d4684222a147482d23f48afc1ff989.nq.gz
│   ├── e40db949e0c221b72fef2a35fd19a87d45b6649a.nq.gz
│   └── ffd1b373a5434b9804eeebb1e66be61096b59cf9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bda557dedb8c64d352ece8328eee6c7b01c8931f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[google/gin-config](https://github.com/google/gin-config)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*

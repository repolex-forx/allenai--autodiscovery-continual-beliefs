# Repolex Knowledge Graph of allenai/autodiscovery-continual-beliefs

RDF knowledge graph data for [allenai/autodiscovery-continual-beliefs](https://github.com/allenai/autodiscovery-continual-beliefs), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/autodiscovery-continual-beliefs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7962443f239f3a77cb6176b1e677afc828891ee9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7962443f239f3a77cb6176b1e677afc828891ee9
│           └── chunk-001.nq.gz
├── blob
│   ├── 06984c92c79417c2d6004c09039031321fa4a5d8.nq.gz
│   ├── 073895c997c915aa6d63b8d31226209801aeed47.nq.gz
│   ├── 0b1e3f51db8ebe90adae71436b77d43b58a4b2bc.nq.gz
│   ├── 12c0a09972b35c9a64b004521cf9193663e677ca.nq.gz
│   ├── 1c0bbe4e8ff49c442d9bdcf4b146b31b2c4d3914.nq.gz
│   ├── 1fba9ecbedfcfe3b509248e5c611a9a73c1fea55.nq.gz
│   ├── 210469024434747aa28d750d5de353c323fb15d1.nq.gz
│   ├── 30f27ddbaec3b5ed882190bc8649a6801fccc7e5.nq.gz
│   ├── 35c7e76748a6c80e048b51f1124be2a597dee84b.nq.gz
│   ├── 3ffe7da9644c2608d31d78aec6b0700d0a03ddef.nq.gz
│   ├── 410782bcc60aeca27dae5db0438b7d098f0843a5.nq.gz
│   ├── 4136413677e1de18a3057716e0de9110ad2854bf.nq.gz
│   ├── 4305ce0010d4340ca2c5e904970117426932dee8.nq.gz
│   ├── 4dd7684a16a562a0348129b20e44de9144e6654b.nq.gz
│   ├── 55c3cc5d7e699a33d3cec6b6a1b6e3a745a31fb0.nq.gz
│   ├── 6a0f57699299c13743a6831c6de1c8382b8abcbd.nq.gz
│   ├── 6e3ea052d62abe32c920c8ea9330189f062c6cac.nq.gz
│   ├── 6fa79cf9413ba39df00d775f0c777b8467668006.nq.gz
│   ├── 7264e40de8ef01acbe1e18f2c48c2bb244405065.nq.gz
│   ├── 78346b57a209407e42f157dc94f2c8245936b6f6.nq.gz
│   ├── 7b715679f0220325716c8acf3470734e8359f7a0.nq.gz
│   ├── 7d1d86a1a844996be6ac2c2f319267b00c27e84c.nq.gz
│   ├── 81a6a8bba0448bfcb40e624ddc8c8980ba3c4285.nq.gz
│   ├── 82114f2765a286bb2708155b43d9ddea90afec84.nq.gz
│   ├── 88524bbab5c970e33ef15c089e0e1268cd56d49c.nq.gz
│   ├── 90745e78f9160ac820ac29001cf16371a86cd23e.nq.gz
│   ├── 918e011d69d1fd659a5af739d05a22e27293ee87.nq.gz
│   ├── 91d767b2c81d628bc9554ff6afeac18a5c67c3f9.nq.gz
│   ├── 9422ea9efdccb84e89934ceba17d7b3de0a89803.nq.gz
│   ├── a3829fb3347d07803e879d9a81ec0e863d29c1d9.nq.gz
│   ├── a7527931d825ad713dea94af6110420be8b93537.nq.gz
│   ├── a881a92ff287c26ce7076f7614497df546f7da1f.nq.gz
│   ├── aae9e2ab4c21c68b951f527e61062a19b729f6f8.nq.gz
│   ├── b6dcfedcbe6afba67cf216fad5401231e83baaac.nq.gz
│   ├── bd89c7f75d0eae257266b8e30c87149cf5f67feb.nq.gz
│   ├── bdaf2cf9783c3999aa068bd3f74dda9a3b769eae.nq.gz
│   ├── c029f5a4c0e11e236f8d32b6081b1854d6142a5d.nq.gz
│   ├── cfa03f561def59f74494c7d921d410258f544783.nq.gz
│   ├── e9cf0518eb654b9518aea8beca6cddb33eb175db.nq.gz
│   ├── ea56927e99f1e73a37e56a590205cb640a6e7066.nq.gz
│   ├── eeab452a365add77ce13a2f42cdaa33cc3aa8cb5.nq.gz
│   ├── f54d6980f8b20561eb308c4e229216008d97e8ab.nq.gz
│   ├── f94351db8c24e676a89afa9b22895cccd7c63105.nq.gz
│   ├── f9a1215bee08fff278bf5ed1adeaedd219076278.nq.gz
│   ├── fb5eadeb2c997caa1d4371b47c5d2350d1681b40.nq.gz
│   └── fb8699b37d98d7c36bc48163710babc68d896eca.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7962443f239f3a77cb6176b1e677afc828891ee9.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 52 files
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

[allenai/autodiscovery-continual-beliefs](https://github.com/allenai/autodiscovery-continual-beliefs)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

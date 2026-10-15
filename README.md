# Repolex Knowledge Graph of Toblerity/rtree

RDF knowledge graph data for [Toblerity/rtree](https://github.com/Toblerity/rtree), parsed by [repolex](https://repolex.ai).

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
rlex download Toblerity/rtree
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4b570582ff11cdf73514b1ae2a4129742ee6488b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4b570582ff11cdf73514b1ae2a4129742ee6488b
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ba23984b2f582feb51d6fd6d685f8c8e6f75db.nq.gz
│   ├── 05d8016537e84700427a1361b16a7898dcfcc4c4.nq.gz
│   ├── 0d5e9b687ec0175547b453c06943c60146d779e2.nq.gz
│   ├── 107bf0f6d4832e2f230a062b95e7ba5085675eee.nq.gz
│   ├── 230f05befd839f42371b75e54ce90dc8e3f3884d.nq.gz
│   ├── 24ab5860d3de4e9a43a8d51351e55271d3464db9.nq.gz
│   ├── 348c2adbcaa89c34268450607f65685713284f0e.nq.gz
│   ├── 34c8c2982cb3411aa03a7da7f88349fed31db95a.nq.gz
│   ├── 407c07f06dd45b3c7d9e1dba18cd45819945d4ad.nq.gz
│   ├── 415ee01763f696a02ed95985ec5886b6cf783b48.nq.gz
│   ├── 46ffac2f361c7220c19353c8acc32732b18f4011.nq.gz
│   ├── 4bb46849411e8c39f2eea815dc316d186690ba7d.nq.gz
│   ├── 4cc812c88cd01eea29fdcf26177623ccc50f1ba6.nq.gz
│   ├── 503acfe17cc528200dbbd55078df92e0bf6827ec.nq.gz
│   ├── 57228c7b07cef0fd8f5e56a040366d2502d89fa0.nq.gz
│   ├── 5cc3700787d426cecd5bbed194816e7525e502bf.nq.gz
│   ├── 635bb05f456d437669a7c75ee197a8ce880b272f.nq.gz
│   ├── 66e6bb1a298677735bd702795705f660b7f1e8ab.nq.gz
│   ├── 76d6bca446284049a620460821a066e8dcdb505d.nq.gz
│   ├── 7ad4ce83a19c4b476892b180ba10b801a35f7fdd.nq.gz
│   ├── 7de080cc95146d2abd82a222de8d0f650c59a250.nq.gz
│   ├── 8197ad6845d6706929070a910639ded4949d1c91.nq.gz
│   ├── 9093a548896898ed48a100546bc4490e28881b76.nq.gz
│   ├── 90e40d425f906ed29eeb5f4f739ef38e5fe4201f.nq.gz
│   ├── 983e698c3e11500f86d39d2a05549fe3b2f7518b.nq.gz
│   ├── 9989f9c560b9a2dcf7913e13663d244a10f5ed55.nq.gz
│   ├── 9b7b63555d3a5b2d33ea411d37abe94bb8ae143a.nq.gz
│   ├── ac27a84869a2cb5b416c12fc1fcf57aa6f626958.nq.gz
│   ├── b397f0171e622e851f2f0e805135af0598b1d646.nq.gz
│   ├── b964e06d7c9b6d086d390099725eed7d0178561d.nq.gz
│   ├── c4ba5d0dca0cbc273f3c830b176613c3b250fc9f.nq.gz
│   ├── c524518a69a1fe1d4360a161551eeabff2fd0a3f.nq.gz
│   ├── cbeea1bd47feeb051c498fd40c73b5497650c7a5.nq.gz
│   ├── d078a33f425cc87f28679ec965b10ff31ffdf277.nq.gz
│   ├── d0994d56294e52d8be7570fe0b7ee8dbe3fec9e3.nq.gz
│   ├── d144a628316f239e933e52c1e2eeed35f2eb328e.nq.gz
│   ├── d54fd1be2b3aa7f95c43ab6b95331a9f4ed4f126.nq.gz
│   ├── d5f1e2e96d3000522eaa6ab8631b2917a7c46e91.nq.gz
│   ├── dec94d283904e60b9cde8ceabb17d405921a0962.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6dff9ef70192fe920a51922668859d73d3dc335.nq.gz
│   ├── e9cb65a2e22e59ab02b86cf61ebf4acdf6948fec.nq.gz
│   └── fc399c0cb6c04ac31a49d5f1afa7f696ec78151b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4b570582ff11cdf73514b1ae2a4129742ee6488b.nq.gz
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

[Toblerity/rtree](https://github.com/Toblerity/rtree)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

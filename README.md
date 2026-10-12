# Repolex Knowledge Graph of datasette/datasette-google-sheets

RDF knowledge graph data for [datasette/datasette-google-sheets](https://github.com/datasette/datasette-google-sheets), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-google-sheets
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 51c5d380b7889a1941179ebd2823529cfac619e0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 51c5d380b7889a1941179ebd2823529cfac619e0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0aaf9dd932514025b647850c7a073e9b47e8dd1b.nq.gz
│   ├── 0f4d05dea50850babe08149bb224fb99623e398a.nq.gz
│   ├── 117e34f9ef4e4680c2f8947851063f7de96dc66a.nq.gz
│   ├── 120109bbaabedff33953e6c8b15cc095d1777c93.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 289d86b59a69a556040af2687d4d779cd98c1fe7.nq.gz
│   ├── 2ab2b6c7891fd9c7a59e1a83deb627ac735d33f7.nq.gz
│   ├── 2c5f14b6f6e2ac6828ecbdc06dcc272d3653219d.nq.gz
│   ├── 2de0c16ba23077d46b65362c11e4ddb0209f0d48.nq.gz
│   ├── 3601eb27195a1afe8ab022acef014a15c3f6e636.nq.gz
│   ├── 3f6dd5c9da410db285df2aba431162d413604261.nq.gz
│   ├── 4b58591b3da3522e61c4bb44fb5c2e8a37047a92.nq.gz
│   ├── 5035986ca238c50fc4d7257373e9df18a2eb5992.nq.gz
│   ├── 5477077f6a670492351d79543bb2696a2f99cf05.nq.gz
│   ├── 55d2143cb39362edc67db61212f10ddf57f00cbb.nq.gz
│   ├── 681311eb9cf453d0faddf3aacaec7357e97ba8e9.nq.gz
│   ├── 69f3ab90d0baec76148e7be454de617e30be1b08.nq.gz
│   ├── 6c0a3dc403349991606acff0ce0a6029f9ff13fe.nq.gz
│   ├── 6eeef903c4ed2b27db1f1d1ccf497e5a70d44073.nq.gz
│   ├── 6f538194a6a5fc64fb2fcaaca50132433632d298.nq.gz
│   ├── 6fc6c7963aa47ad49493c340180d0734768f9681.nq.gz
│   ├── 7e1b38db1113460c68800039dd8473db9cee0373.nq.gz
│   ├── 81c481e489192d59d805f7b52f6dad68a4196f69.nq.gz
│   ├── 865224fc0fd1c4d311af71b0a4b5813c32575fec.nq.gz
│   ├── 87a117c0c18383ee2e619cfec13e0a40d5c6d4d8.nq.gz
│   ├── 924c3e0d741f77ca76935509dba687de341f16bb.nq.gz
│   ├── 92c0818a58f5570ed86b58cda619d7047293ba59.nq.gz
│   ├── 9437bacd61f2f92061d3aba626611798fb59fbc8.nq.gz
│   ├── 9bebb0d79233fde0d4835245d9e84d037c51dad1.nq.gz
│   ├── 9e88da5ddb7dc0c4529f89c0d1fe92d3f2bf254d.nq.gz
│   ├── a8c6913a16b07edf058d5a660fbb50a0a3859eaa.nq.gz
│   ├── aa16de0ebab8bc8dd5fbca67c4b0ced7af635b8d.nq.gz
│   ├── aae929570c2ae160bae62c01b40897cdfadb80f9.nq.gz
│   ├── ada833e4f4fefb4285136d721593aa5b98a4b475.nq.gz
│   ├── b0ff5764fc09c96daa230907ff455947f1d5b68c.nq.gz
│   ├── b594c994b6b232d3df1bc6e3f1776e627db217ff.nq.gz
│   ├── b6586416dfbd1d265cc779bc41d8dce3e5cc720b.nq.gz
│   ├── bc1901ad478d964eb0bb0be0f079943135e97b12.nq.gz
│   ├── bf39b39537e39c4f3370ac41f1e6e3370e8012a3.nq.gz
│   ├── c22a0db5cc63b32a065f495fdbea4b11f51a9b04.nq.gz
│   ├── c6048cf4468eb7680d521d275ac88c242a71ae93.nq.gz
│   ├── c7b89b015a1dd5268406fcab6ba71cee26e12d03.nq.gz
│   ├── c904b0feda76c3d43350d85914d3a30bfd019895.nq.gz
│   ├── cbe17a3b13186e0ad41e17f9f03be80128b5fe23.nq.gz
│   ├── cbf0f24e4c35545e16de1150410d580145151e9e.nq.gz
│   ├── d7dc8f0e3e75dc7c628e86bc92d28ab389c8ab8f.nq.gz
│   ├── e02e2664252c00771cfa590868adfdaae9086c92.nq.gz
│   ├── e07c0e46a9c5bb09e95c7a3f3f93d8f89133e732.nq.gz
│   ├── e2485b20d67d9ba492a935676f43f4fd8ebce720.nq.gz
│   ├── e283117343a8185e23a71987b9a078eb844848c7.nq.gz
│   └── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 51c5d380b7889a1941179ebd2823529cfac619e0.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 57 files
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

[datasette/datasette-google-sheets](https://github.com/datasette/datasette-google-sheets)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*

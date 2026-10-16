# Repolex Knowledge Graph of vispy/jupyter_rfb

RDF knowledge graph data for [vispy/jupyter_rfb](https://github.com/vispy/jupyter_rfb), parsed by [repolex](https://repolex.ai).

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
rlex download vispy/jupyter_rfb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 23764d3aec1858be527ea036198461fcff8741d4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 23764d3aec1858be527ea036198461fcff8741d4
│           └── chunk-001.nq.gz
├── blob
│   ├── 03788c4ab90f83e7bc44aab9cc38f31a2c7d2729.nq.gz
│   ├── 0910bf9f42780b2332ddebb8b02aaf96fbb73900.nq.gz
│   ├── 0c6730bc03cb04fd450b48f46c94f2d9c460bc94.nq.gz
│   ├── 19fcd76d15f6ca10c3116ee9b297110eb6b16c0c.nq.gz
│   ├── 1b3644f3fe279ceba1426141d0acfc6d2d833d6e.nq.gz
│   ├── 1e4b3f0c095a5efe5cfa0300960dc40a721b061f.nq.gz
│   ├── 1eecfb5695b292b197733e58f2aa65807ad7e63e.nq.gz
│   ├── 1f0363a47d4e5bd51872baa927751c4bff0a2924.nq.gz
│   ├── 2348a16b44ec126216a241a98e6d152a0ff5da4d.nq.gz
│   ├── 238e58b49eea5c91e4de9862b132d88e2a12de96.nq.gz
│   ├── 253014f86b22e5bfd72f4c96c09488fb1ba22596.nq.gz
│   ├── 2ad12665e7df0b8f242be8ec98eb37330708f994.nq.gz
│   ├── 3377a8267b9a745cb10495aa5f879eb61fad354a.nq.gz
│   ├── 41415049a82da93f8377995c76db85ee6e157945.nq.gz
│   ├── 4909c7b250bae8d22cf78964c34f6b519e7cb7de.nq.gz
│   ├── 498460fea2241cbc4389f7265a6260837d0a8372.nq.gz
│   ├── 4b48e5a7a1a81d5500173f52e716be0ae7f27db5.nq.gz
│   ├── 5b532b9d5b06a579faa35bf8bb56ef129a100061.nq.gz
│   ├── 5dda3c8324b354d141bb26b4e1c8c55b5fb45156.nq.gz
│   ├── 6429d62a26774052448d3fbd977d0c76ba8a78cf.nq.gz
│   ├── 6e9bf8e608d59cab86a2409787a07e0b3fb6dfb6.nq.gz
│   ├── 6f31c01c0dc36033b5f9ec261fff93d79f706c83.nq.gz
│   ├── 79bc4646fefdf3d85c2ab3b7dd5238e06507e4f2.nq.gz
│   ├── 80dce639220d618b51bac5fe44c92152f8522443.nq.gz
│   ├── 80fec43eca858996e7cc078519612f9fed870d5d.nq.gz
│   ├── 8155f508f3348930cb78cc14f393a55e7acccfeb.nq.gz
│   ├── 8b25551a97921681334176ee143b41510a117d86.nq.gz
│   ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
│   ├── 99093e4e3915cee790d5757954251072fec68dd1.nq.gz
│   ├── 991a2c5f75046da62fefd8801a1147918fbe3cfa.nq.gz
│   ├── 9e15b23e6877a49d28e151480ae88d180f449ba5.nq.gz
│   ├── a318c15df1ee74f93da4e642a950c6ecdd8d8ab3.nq.gz
│   ├── a480f01d7f589f5702a9204a8e87805d51d4f6b2.nq.gz
│   ├── a8e493c9b035634d476239ad15ac2608e9056933.nq.gz
│   ├── a9bf588e2f88457fdf73ac7361ef1d596fb81453.nq.gz
│   ├── b0b6de99d09f2c35def5ae3ceb699d76e4d14aea.nq.gz
│   ├── b13f58898daaefc821da683a714fefd41c372405.nq.gz
│   ├── be540f2ae9d6e2add377b331286dfe8828a69243.nq.gz
│   ├── c61c89fcb888ded9ef1c183f42ab497626713203.nq.gz
│   ├── cc8eb37eb3e8a2c66fdc3d63f1209d5a3d94b1ec.nq.gz
│   ├── d21a3eddadc9ab3b618b29e839bd5be75a1bc046.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d87c816fb2d2041c4e80775f90aa815a18eb2c6e.nq.gz
│   ├── daacd0f6cd7527893abc2d74bcaccd984055b1e3.nq.gz
│   ├── dec9e216971ca0b0455dd65d0bdf93c17f8879e6.nq.gz
│   ├── e6ae4b68d7ecbf32ea84d83e5ae89c11e5b7c501.nq.gz
│   ├── e9a305df7095da8f0504fcc956898895f676119f.nq.gz
│   ├── efb166f028b120afdd71e3a333dc860fb0e8e705.nq.gz
│   └── f7b146e9d2b0c1d9ea571d0593f1f4956d5b0e60.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 23764d3aec1858be527ea036198461fcff8741d4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[vispy/jupyter_rfb](https://github.com/vispy/jupyter_rfb)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*

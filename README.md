# Repolex Knowledge Graph of huggingface/faceberg

RDF knowledge graph data for [huggingface/faceberg](https://github.com/huggingface/faceberg), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/faceberg
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18e2e0ef07fcdbd2b1a4231e7c8022b545914351
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 18e2e0ef07fcdbd2b1a4231e7c8022b545914351
│           └── chunk-001.nq.gz
├── blob
│   ├── 0294cf8b80a9dc1fab2466bf23052abbaee61aab.nq.gz
│   ├── 0428904d13c42553c246d076709523ba2a2f20cc.nq.gz
│   ├── 156b1ae946d1e9f7cb1c8a23999ebd1d72a06bd9.nq.gz
│   ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
│   ├── 1cb9b318792fc700596bc39407d69e4ee7c7cfcb.nq.gz
│   ├── 1de5918ecd13e785e95b5cca8d3fb8d366792603.nq.gz
│   ├── 1ee18db84d401c0dba5f14adbe045a78605f6a9e.nq.gz
│   ├── 2434550ec75c4269c51d839de64bb816415d0985.nq.gz
│   ├── 2483f00ffc928fefc4d668f5f7f8a7c72ac983e4.nq.gz
│   ├── 25648009d06da31518fee6df3e3c6f72cedee5c8.nq.gz
│   ├── 28afb176896dbaf6ce28f4c08b35b5a641bd8f3f.nq.gz
│   ├── 2c9d0a4c2bb6160b6839ffdd010062f2bb9623e4.nq.gz
│   ├── 34a4a218cfd8753f06506e2f056191953be79df3.nq.gz
│   ├── 356ae4ad47932a39d9784baf97260be6e3d33023.nq.gz
│   ├── 367bbec62569bda727661daa548cad20ceedc132.nq.gz
│   ├── 3b2b13aa87394e4e94ec9d466c808c51656089ae.nq.gz
│   ├── 67a436813d88209496eb873afe5214a6bc2ce30a.nq.gz
│   ├── 67bf80b36e9a7ecaf4f222b472a48a0bf17bc0c0.nq.gz
│   ├── 7179122e54d3d3655e44a7b9af77f2d63699dd11.nq.gz
│   ├── 74ec961e2a46326058cc63a3d0c6a232fadb122c.nq.gz
│   ├── 77ead565cd4a50f7f1cc435f17215e7da5269656.nq.gz
│   ├── 7e0c256f9f3d7d925938b1d1a7d92e3ab39d6f70.nq.gz
│   ├── 81a97a3ec4eb2f44fa127c3fdc0d7af73c627306.nq.gz
│   ├── a261deab8195e58f66c57c8d20bfd8f7a1e1206a.nq.gz
│   ├── a2bc247273ec385859e77ffb46c24f29f99fd122.nq.gz
│   ├── a58e501ce56bd0b6af19b4f47bae943b838e033e.nq.gz
│   ├── ad293093b07ce949885da1fddaa7f52bfa6c4ce7.nq.gz
│   ├── ad30eb69e2154da9c008c985472fe5f1bba87734.nq.gz
│   ├── b4292831d1b812650700ae52152444f5b3c59ad2.nq.gz
│   ├── b4bb7f3e5c58995dafc7cce6b4994139c2af28f5.nq.gz
│   ├── c0c3772a38cf532d04bef934b12acda6b8627db2.nq.gz
│   ├── c2dc12cd86c7e7d5b60adcfb21baffbb790e333a.nq.gz
│   ├── c46b8da80900a2633ffdde6ae8d390dc9eedad0d.nq.gz
│   ├── c97efa1dfe15a14a858ee2477dc88fc46045a214.nq.gz
│   ├── ccbad6d25f00727e7c4258ae8d3447926634858b.nq.gz
│   ├── cf48c9b585e5a870a3ab0a09dbf4ca0c78ca1427.nq.gz
│   ├── cf95453647cfb7a8d3c2289b5028a2b23563228a.nq.gz
│   ├── cfafe583b32422e45fdd76d2dd446e7c0fd79c4b.nq.gz
│   ├── cfc435e02ef94554de472903dfbf005400509531.nq.gz
│   ├── d32205b76e58a310b22a15608e04cb9369a9d3a3.nq.gz
│   ├── dbd5c76a865f16b08edaf75e0212ed1812c64fa1.nq.gz
│   ├── ddfb7dc54775a0a04b2fa33d959b95a72f0b75d9.nq.gz
│   ├── dfeab3e15d8a5f24eb4946804addbd44d7c8f4d9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eca69138820f6fbd8695bc9dbb4aa3d44cdb102a.nq.gz
│   ├── ecdbb73cb137e4c201a3baa4da2e98bdf7f9d7bb.nq.gz
│   ├── edf630e7b7f3ddf719faac13bf9a00bd2294e5b1.nq.gz
│   └── fbe27505ad3d1cf01dd62f11df3614f80a49f14a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 18e2e0ef07fcdbd2b1a4231e7c8022b545914351.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[huggingface/faceberg](https://github.com/huggingface/faceberg)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

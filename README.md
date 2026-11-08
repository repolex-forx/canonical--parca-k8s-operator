# Repolex Knowledge Graph of canonical/parca-k8s-operator

RDF knowledge graph data for [canonical/parca-k8s-operator](https://github.com/canonical/parca-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/parca-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 89fe873c4d8490f700e5d223d636c4602319a9a2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 89fe873c4d8490f700e5d223d636c4602319a9a2
│           └── chunk-001.nq.gz
├── blob
│   ├── 072eff9f0d4a61757024a99326416aaafae07ca8.nq.gz
│   ├── 0a5df0b653f060ef5498fe6420b09b98ce069e47.nq.gz
│   ├── 0bf6589cbe253cb80c2aae7664639e480d3c3056.nq.gz
│   ├── 0de885eb3dec59b8842533a7f95e854f55d205f0.nq.gz
│   ├── 1409bd2748d7905b7b0f8d03880d1c6cef39523b.nq.gz
│   ├── 148f5eb6a5edd7c7417cd2b13b13a77ff480da47.nq.gz
│   ├── 14ef221745c2c9fcd47c9eab610230267caf6c72.nq.gz
│   ├── 199cca3988977ad18d06246287f336108db63151.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 1f425b9126860bd08a547211da9721d7ca99d970.nq.gz
│   ├── 219793a0aa948e6766e7ef5ea130682b05755c83.nq.gz
│   ├── 2a5ceb30f72f66ed1ff60ce832285fd6f39d869e.nq.gz
│   ├── 2b96a895d92cfd9d6f4faa72c5ae4edf6c3a1967.nq.gz
│   ├── 2edfb316fad45a62edb3b72dd7dedbafea3906ea.nq.gz
│   ├── 3254c30ba152b017650d88ad89afeaf2399e6df8.nq.gz
│   ├── 37a30b311c68547d42921106392091bf631ac7ac.nq.gz
│   ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
│   ├── 3b26c3b64f58515e706a4111325a74666671e441.nq.gz
│   ├── 3cc12221f8e4f4daf5b10ec4bab8656db8bec668.nq.gz
│   ├── 408388e29d5274ac52b1a54e30403e30824544f8.nq.gz
│   ├── 4837778df72367439344ab26587b5fbcb7ed6c07.nq.gz
│   ├── 4d74abe0692a1d6eb1b7f326db3b98aaa950e91f.nq.gz
│   ├── 4eb8d795381ee3f2f411ae73d0e14be3f8f82d38.nq.gz
│   ├── 5090ac2a23a7e81f499545f96df43aba4f43ce86.nq.gz
│   ├── 53bd7023dfd203f2aea532dbf3379166d3214dc9.nq.gz
│   ├── 549bbbbfd5299a4a22bebd97d7cce2d6592d1023.nq.gz
│   ├── 5bb3e06f52a9d7c4ed359cf17786f4f4f0aad85d.nq.gz
│   ├── 5dd59c502e60a5f61b7e1b8b12df98f29fedce95.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 6cfffe718764da09bbe7abdbf4d333c83867fb4d.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 74d7fe91e9516c6315f64a761a850ea694712519.nq.gz
│   ├── 7946075a5d012f4d2c4c614541d1c7bac4622ce4.nq.gz
│   ├── 8789f3ff61228947429b2ed24f5bc8026f53822f.nq.gz
│   ├── 87c347aa67cb1f63f2fb93c64607c2c81da6a63e.nq.gz
│   ├── 888c85583f72dc67ed997c9868566452e70cf898.nq.gz
│   ├── 8d20d5d95fbce796a8eba040b9dfb53a78bab73d.nq.gz
│   ├── 8d224cf83c0d7c8ba069109bcfd91019577fc068.nq.gz
│   ├── 963a52a548bbad87c1863f445cdfdb96b25fe358.nq.gz
│   ├── 9cfb84277e97b68c69585f06d37d2ca0db52c410.nq.gz
│   ├── a034c8bfba279b9c2091d878aabe71b0afc23eb5.nq.gz
│   ├── ad60b546623c02340f4e7eb19bf83031a47b2ea1.nq.gz
│   ├── aff29f890a081dacb874528f6aa2e9edde9c581c.nq.gz
│   ├── b1cc074c1ef4dcd2967463b2a045e47bfe2245c5.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b4c4baba9c0723dae51f81098dedae1ee04e9117.nq.gz
│   ├── b5c90dd998bf7f9b37775a07858bdd289a88746e.nq.gz
│   ├── c41e7fb1ed5cd264c4aa21f361c34a1136b3bc01.nq.gz
│   ├── c4697e5a1e73904308db2a28d7309c7f343f04e5.nq.gz
│   ├── c7f7558b7f5cda06804923010dcde901538ba656.nq.gz
│   ├── cc6e0e13f8519cf7b35c6a7488a2bbbf2543d7f7.nq.gz
│   ├── d25729588b7ddd229cb0756c0b098ea3709a7a6e.nq.gz
│   ├── d37f2ab99b877b3c566b040fe6f58adedcb4b12f.nq.gz
│   ├── d4c0e5516b298439b7c5a6ba4b8747bf4299c338.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d945cc1d49b0f6cc7d94ef70f8d954e64e6a9132.nq.gz
│   ├── d9d4a105477eb51c670084dbb38f460fd05bedb4.nq.gz
│   ├── dbf4d5bb721e2c91fc81ad9e7bc352896740ad17.nq.gz
│   ├── de535d0f97c5fd103dfccb173b400b7e71461bd6.nq.gz
│   ├── e27361bcbcb2439a48e8c9339ef9dab02f4126b0.nq.gz
│   ├── e4765171bb94bd15f1cabb85ab70e22835592739.nq.gz
│   ├── ea1073523492879a72a7dda82a27305b85a91622.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── fa5095cf001e6190a96d2ec5ca4be1f160b95b3f.nq.gz
│   └── fce775db3ff2813a91de0b373332e06975ba7aa8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 89fe873c4d8490f700e5d223d636c4602319a9a2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[canonical/parca-k8s-operator](https://github.com/canonical/parca-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

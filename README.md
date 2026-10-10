# Repolex Knowledge Graph of python-poetry/poetry-plugin-export

RDF knowledge graph data for [python-poetry/poetry-plugin-export](https://github.com/python-poetry/poetry-plugin-export), parsed by [repolex](https://repolex.ai).

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
rlex download python-poetry/poetry-plugin-export
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a69c5bce9bbb1c5de5d9e55e7da3b25f10e3e6b2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a69c5bce9bbb1c5de5d9e55e7da3b25f10e3e6b2
│           └── chunk-001.nq.gz
├── blob
│   ├── 1204da0c96cd95de681eb8a2838a71b3c1f6e843.nq.gz
│   ├── 133b64421f86ad26448e0b0f27be33df6808c14c.nq.gz
│   ├── 149aa9527c577a1828a5a3114377960fd1e41a88.nq.gz
│   ├── 1842aecbaea2d7c1ccb91a7dfdbb3fbe66dcaa8b.nq.gz
│   ├── 1aba06effe1f17237e127d593ce92f0095044d1a.nq.gz
│   ├── 22ea85dabb8dda4d58ef7cd6bc8b100596c048f0.nq.gz
│   ├── 232e3fe16bb2d6b5867c13ce6026fde193102ea7.nq.gz
│   ├── 238fc183bb4f5ee83637653db42d9ed796915db0.nq.gz
│   ├── 26019a2644348ac6cc67389968f4b829aa6e26fa.nq.gz
│   ├── 2a010f838fb4cc714c7b311841c5b1d978220fa9.nq.gz
│   ├── 2d8eab61aef4bd24ecd270ab44380be402c1c930.nq.gz
│   ├── 39b83c5084faa3f1205638b829b27880eb3fe2a1.nq.gz
│   ├── 3f838bd338fa11a5a9cd6689f2a3f455e46f6712.nq.gz
│   ├── 41a062fc09ae13b2a1f4aa0f22ef12387b6ba49d.nq.gz
│   ├── 49ca30d844a6b822dcb6a65c9b8db9ea670ac580.nq.gz
│   ├── 5d04b540bc96aa09c5e1aa2e2f8a624ff10b54ea.nq.gz
│   ├── 666b89c1e0b79048e1087e8a546aecf2c73f1bf1.nq.gz
│   ├── 6b66c2c961736b9d2d182a72638c8ffe0622008d.nq.gz
│   ├── 7168ffb8be0fa3935bf62c3f6393e1b1cc6918ad.nq.gz
│   ├── 7f4d2bd104d74846cb5110acb7d87f046faf1954.nq.gz
│   ├── 8327efc9629d2983d0062c570ae9f3f753c0bba6.nq.gz
│   ├── 92b586ceac9eb75628e9145d35ca3f632c6afc98.nq.gz
│   ├── 9ac8632c7f517abf71dbfc384d401640065ab7e2.nq.gz
│   ├── 9e0805593b652818425370fb6973486b80c689ba.nq.gz
│   ├── a8ab8bc6367d2e72656d858d1d2125bc6d746a9c.nq.gz
│   ├── a90d9bcc41f7ee4c8d929a4d1853fe5f58e44956.nq.gz
│   ├── a99b3c05cdd22e1275cd9364df757bf033f4cf9f.nq.gz
│   ├── b56c976bfa98ecd555eacacdbd3f79ca44c41d80.nq.gz
│   ├── bf058b8813ae382e43d5108c3e8a9340a89a6c54.nq.gz
│   ├── c4b84259192c24ce67231f25aed082405282aa01.nq.gz
│   ├── c6eb2c6b46c0024d256da6fd6fc949cef08fde62.nq.gz
│   ├── cde0485e4d173cd0df13b6e30f81073abbc7d83c.nq.gz
│   ├── dcb9e21f74e9b2ca21dda6b36e58229665398033.nq.gz
│   ├── e1f2d8df33a2543b8b947867133a440ff7eef5a7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eeb0a4815ceffdcecd4102d143008b13b6e90a51.nq.gz
│   ├── f5255dc9dada135f28c23a9f9526e7b6e25372f5.nq.gz
│   ├── f7fe15470f932e8589b3711d7456e282f7c92a6a.nq.gz
│   ├── f8842769ff1ff9d1863567ce2b8f0a0410e25795.nq.gz
│   ├── f97fb14278068cd2840cc0de4e12f091154a6106.nq.gz
│   ├── fb8674c7e3963159487e851ac5dec69cd9d6ee0b.nq.gz
│   └── fcdeda3133860f7a41040e0953be83034d01145f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a69c5bce9bbb1c5de5d9e55e7da3b25f10e3e6b2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[python-poetry/poetry-plugin-export](https://github.com/python-poetry/poetry-plugin-export)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*

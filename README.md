# Repolex Knowledge Graph of rust-random/getrandom

RDF knowledge graph data for [rust-random/getrandom](https://github.com/rust-random/getrandom), parsed by [repolex](https://repolex.ai).

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
rlex download rust-random/getrandom
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a04900732207b537b2d3ea7bee61ab0a6c6ca9f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6a04900732207b537b2d3ea7bee61ab0a6c6ca9f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0147fe58c3a5606b6b9cd96353343fa9fde9a8c2.nq.gz
│   ├── 020e769e3ea9809ea60e0122a93c19aaebb14da0.nq.gz
│   ├── 029ea58973b49d47db3fbb5ed5b2a64f78b567c0.nq.gz
│   ├── 05fc4d5cbaf3b05f3c0db8b4281b38e7e3aff02e.nq.gz
│   ├── 09921c9736f2372ed72a0bcc2facaaf5ede4eec0.nq.gz
│   ├── 0aa670e232562627399525bf1b5ea4ac1b032ca2.nq.gz
│   ├── 0e917015d76a5f4ddecd3a556d974835103b30ca.nq.gz
│   ├── 13d7a386a3fbb2cbc311240bc168e2a8696f49ac.nq.gz
│   ├── 17a0c9056562a9e1d6c7badcddd11f3ad51d6da0.nq.gz
│   ├── 17d74680f8cf2d2571d1d5873cb4d14cc6b12246.nq.gz
│   ├── 19bfb9a27ab8a5d4541f7d53aa1704df17d26415.nq.gz
│   ├── 205dc94a5fab4575175a7987ff12862da1b15300.nq.gz
│   ├── 2c68ef9e6d311ee06317fa80e7fb66d63b81fa32.nq.gz
│   ├── 308d1266505edc912831b185af27b3e008371af1.nq.gz
│   ├── 31cddfc8aa0ebecd427715a6e4f66d5a421b47f3.nq.gz
│   ├── 328e36b24ede50067b3fb843b515137fe0b5959e.nq.gz
│   ├── 3dcb32f9ce62b59cf7998e187705787353a823c3.nq.gz
│   ├── 451729e3e34b8c71602096e6ff65a32ebb7e24ab.nq.gz
│   ├── 4beb2a0bea88dbf9e92f2c4688a06e53d63d523d.nq.gz
│   ├── 4ea381fc40a4c894c51671e8ebaceba246d7505a.nq.gz
│   ├── 50849d5061ac186c626ced11c3141d0367d8c62b.nq.gz
│   ├── 560fc89f7193adc7eb7213703c876d7e72047d0d.nq.gz
│   ├── 59816c99367187481e2e2d55cedcc33704024439.nq.gz
│   ├── 6e3039df852353a6009163e8db08aaaefd47e8d8.nq.gz
│   ├── 6e615eb89a43ee4bdc6fcc45a8e9ab43ef6b10be.nq.gz
│   ├── 73a827431396271a5e4f0ee7eff2ac12c598ab4c.nq.gz
│   ├── 74e9f32065ab2d3df1b645d4bc17d68a311accc5.nq.gz
│   ├── 8159f49ff84cbcbe9391403dde7b303df724350c.nq.gz
│   ├── 89bf65dffe1a28485ecebdf2f7ffa8a74479f6b2.nq.gz
│   ├── 8e75f0a1684ed9308f40fb6ab25259021334e732.nq.gz
│   ├── 927dc85c51391041b6163aa95b7dfb5832939fb5.nq.gz
│   ├── 92d12999f5785ca526caaafd783156c3dfb89f91.nq.gz
│   ├── 9e8a2a6bd418d320491804f4df88f418d1b4a8d3.nq.gz
│   ├── a3f26c40b70d537734e16367324e4cd31a8567e1.nq.gz
│   ├── aa07246ba03161fca09e46dd60e93b093696bda9.nq.gz
│   ├── aab301212a68dc493e840fa40882ec96d65a2144.nq.gz
│   ├── ad42475b21fdf24dafe708ea767dcc576fe6f26f.nq.gz
│   ├── af0644328f1131e4a9e289cf40a39226497316f4.nq.gz
│   ├── b2afd95f9b7246faa4071feb9e3b5bd1714a3324.nq.gz
│   ├── b42e381cf7f9e92938e972e840b1b66d74c74f96.nq.gz
│   ├── bdaabb3f5b2fb830f3c58fa046f0acba1f7e38e8.nq.gz
│   ├── c32baeeadcacc1549c6d8e83b6ee96b442366001.nq.gz
│   ├── c7b51c0e01341a3857036aae6c665f1263b4529b.nq.gz
│   ├── cd3335b4ab3a2a46914b4176b2e9a052cd045fbf.nq.gz
│   ├── cd3f7cb3ae92c6910467c66b165445df70aeb3a1.nq.gz
│   ├── d644ab62c5d4ceebe4a842abb1f5faeae4a75e48.nq.gz
│   ├── d921a42f8041992489c65c161c576a3af7914667.nq.gz
│   ├── dabaf8ebc27d8a42081018526cebf127d1efa844.nq.gz
│   ├── e301510b809055734945073d81639f406bf5da9a.nq.gz
│   ├── e58f12dd868671da361dc3f8dd5eba731fab3cca.nq.gz
│   ├── ea22de7a57d66fc86662f71396e709e267dccb98.nq.gz
│   ├── ee22b63f9862d0a6d55ccfc2bc03650b446ba705.nq.gz
│   ├── ef700e85f0324d3d593b9904a9cbe32c47c7385e.nq.gz
│   ├── f08d4fd06bb801b4c68b3dcc3cfeb56b5b10e0a9.nq.gz
│   ├── f3e22de058cea264a5b7e61c366db1faea8a8864.nq.gz
│   ├── f667c7fa2092a6555e099f23b76354f4f643daaf.nq.gz
│   ├── f8abfbef3ac45c38b174f8be722aeb05932e63da.nq.gz
│   ├── f93995dcdfd3309e28bf84e7e37bbe5f6c12c8eb.nq.gz
│   └── ffe2a318187dae9c648ad53ee6b6d1b7aadcca8d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6a04900732207b537b2d3ea7bee61ab0a6c6ca9f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[rust-random/getrandom](https://github.com/rust-random/getrandom)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*

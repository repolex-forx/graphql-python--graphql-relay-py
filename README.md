# Repolex Knowledge Graph of graphql-python/graphql-relay-py

RDF knowledge graph data for [graphql-python/graphql-relay-py](https://github.com/graphql-python/graphql-relay-py), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphql-relay-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 611c0333eeca53663d9b47f7994098edda81b087
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 611c0333eeca53663d9b47f7994098edda81b087
│           └── chunk-001.nq.gz
├── blob
│   ├── 025cb2dc42901adfb2b64ad83a5fde05eaed823b.nq.gz
│   ├── 07d445ac132b3031dc04551f62e248e1b9b95cb5.nq.gz
│   ├── 09278c1424edec148e698cc440db0a9de6294242.nq.gz
│   ├── 1d53baa500eec59eec1051f4d25ed43afea0fdfc.nq.gz
│   ├── 2058baabde72d5a551f6b4edd94138c3cbdbc288.nq.gz
│   ├── 21b42c632040f8ba869f4748aafe3df2e89429fc.nq.gz
│   ├── 2490b59425ba1c6d1fc11da92727d81f7003e738.nq.gz
│   ├── 2b424f04ccf3967131b31cdc1958ac0b5c777024.nq.gz
│   ├── 2bd2ffaf35a83024dc64000b6dabd8d09b64b709.nq.gz
│   ├── 2f67a24fcd829739a5b7b061ed6d768b7cd27dea.nq.gz
│   ├── 2fc5171be72596be6a19c6fa4c64af9c74b2540a.nq.gz
│   ├── 33c89ee2550fee6bb2737455a700277ae864e20f.nq.gz
│   ├── 41792cb9f943d2fcdc867b1acbd9059037625e11.nq.gz
│   ├── 46daec3e7e99196f7c25d3a35b011309be03f0eb.nq.gz
│   ├── 5070bcfa1cb82b77076ce025a1b9cf8fcd3478fb.nq.gz
│   ├── 537c3ef72f36c05e192800265868791b530760f4.nq.gz
│   ├── 5c5c571ca13bbacb553eee36e1b31f00714b0d65.nq.gz
│   ├── 61f885c5928b866be98b1db8277958437bf8284f.nq.gz
│   ├── 70849608fcac6450a8346e9d2a33d58cf468cccb.nq.gz
│   ├── 73b9aaa89fd443250d63a140795a61ed636e8d41.nq.gz
│   ├── 73e91522ca73ae11f70fa99f442d83f79ec0402d.nq.gz
│   ├── 7668785a64e18c3c3c6a46d2ff0fb920ad6b2bb2.nq.gz
│   ├── 7a9470a16209cdd1a921befc2d11a10ee81eb490.nq.gz
│   ├── 870c37f45b352dbbbf41b4e1cc88a9b470438352.nq.gz
│   ├── 9127d7c549ea7d92608087c8f09bb103de5ef1e5.nq.gz
│   ├── 9a4d3d1212ef9e770c7f1646999f6f1dcf33ec6e.nq.gz
│   ├── 9aa5e8d523560be4fc5ef55b494fe57ca6a4142f.nq.gz
│   ├── a313d254c958740d9408100355e31124e46e189f.nq.gz
│   ├── a3ee9a6ffd633509cc1daf78abacc8d77eaca806.nq.gz
│   ├── a65c2d963f696d29aff669aa887f4a2a4fa9cc43.nq.gz
│   ├── a8295685ea4d0cbffcb42a175e0628b395b652c9.nq.gz
│   ├── ac4c67a1cfcc2ec7a6b96dbf025bc0aa784a402a.nq.gz
│   ├── ad062a5c37c33741c1c7f2dec402128c8cb17196.nq.gz
│   ├── b198fb1a5ef72dc4dd1d3c00a7c6de9a992aa17a.nq.gz
│   ├── b8deadf9e823f7ef94d6f8d97a3f285b92f15c1e.nq.gz
│   ├── bab06728db79593a076564c0e6667eeedab2b772.nq.gz
│   ├── bbf6b3aad8b6690adb4bcf73d20f1944daf5b070.nq.gz
│   ├── bec195f3a234c1165babccfbc695d331d5eb1905.nq.gz
│   ├── ccded58822f3768b080d1f7536bb52c08f52889d.nq.gz
│   ├── d4a2c4405ec2e962c521a13af91bf5f7098a62a8.nq.gz
│   ├── d573d1991146687a24a904446b99f251c229738b.nq.gz
│   ├── d7aae87f95fb9fc153a1f76a48166ae9bde016cf.nq.gz
│   ├── e2144a9f1862fab5ff07f3c5c2ac302768923a06.nq.gz
│   ├── ea12eefee2fe4eb43569d0e3ec3e65fafb431893.nq.gz
│   ├── eb0b539ca9cf0d9578ca4a590dfc4bea62eea372.nq.gz
│   ├── ef004709aa955a5690af4b1a8f18eabdd5cd9b48.nq.gz
│   ├── efae32e13f9d498656c387e8c07fe28149c44322.nq.gz
│   ├── f16c0988629fed5dca819dbd32f330052f9d2c79.nq.gz
│   ├── f25cdce71332a9685f86cba3499272219341923d.nq.gz
│   ├── f4dd8552dd7a692d55ba2cbc2cd3ffa1b947a24d.nq.gz
│   ├── f927bec5039e0430b9a7e94345f6b0fd4171a4aa.nq.gz
│   ├── fc16674520d64d36a72de271e3d09c08c6049618.nq.gz
│   └── ffc79d9b3507eb14b15a05cb02531620332267a0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 611c0333eeca53663d9b47f7994098edda81b087.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[graphql-python/graphql-relay-py](https://github.com/graphql-python/graphql-relay-py)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*

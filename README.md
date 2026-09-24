# Repolex Knowledge Graph of repolex-ai/forx

RDF knowledge graph data for [repolex-ai/forx](https://github.com/repolex-ai/forx), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download repolex-ai/forx
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3fc54e02b9979427aa8c5bcb1e0c50eb29f552dd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3fc54e02b9979427aa8c5bcb1e0c50eb29f552dd.nq.gz
│   └── repolex
│       └── 3fc54e02b9979427aa8c5bcb1e0c50eb29f552dd
│           └── chunk-001.nq.gz
├── blob
│   ├── 005f3f75c5acee37404bbe9f3f55a7c2b4eabfdf.nq.gz
│   ├── 033b6166860a4edba6654b94f3230fc0fcca6ac2.nq.gz
│   ├── 034896946842715d56e0601640e34e341c779769.nq.gz
│   ├── 05b17c79d7d579d46f943d2f47e988007d70a40d.nq.gz
│   ├── 18e4967cfcfbdbd65b0d45eabed5794d0b0af1f9.nq.gz
│   ├── 1a48282c5a3b7fe253043b065ac35d8fce8f3006.nq.gz
│   ├── 1c92a42fd364f71fe204a156a05913ea6b8a0176.nq.gz
│   ├── 20a8438acb49ba7c437637e8f803601e4f7bab7d.nq.gz
│   ├── 211fc72e0cda3953f207acc8ce7a2d3a06b9886b.nq.gz
│   ├── 25b94b5edefa4880689fa2d080f01621d6714a76.nq.gz
│   ├── 275f8aa18870787e7a97754658a9c686619b0632.nq.gz
│   ├── 30c0042f39908ecdeb18ee0c9f6b789d3632f4aa.nq.gz
│   ├── 37c0b0ead22bef1893219e77b0044d325c136c40.nq.gz
│   ├── 3b042b119e6ecf0cdff36e49f74bd482e735b5c0.nq.gz
│   ├── 47b5835284bae50b1cd6505eadb3f082cbffab26.nq.gz
│   ├── 480c19c130bf75daaa94b296031ee8f23023c58a.nq.gz
│   ├── 49dcdda07368082ca82eb512ff92fd85dc4b66c7.nq.gz
│   ├── 4d197f6ce63d4417aa87d5ddd8eb585328f4e24a.nq.gz
│   ├── 5aa714addd4b1943ddf2443d146eb5a7d5a4ea37.nq.gz
│   ├── 64400064fe93cdd6ca22842485eb723b07c4ef8d.nq.gz
│   ├── 646e84b1e4439d65bac66b6ac84bc9163966b868.nq.gz
│   ├── 6553966a655e69d21ed74d182ca81cfc39275226.nq.gz
│   ├── 6b79679f4211b8a2e27a91e84978ba4aeee4867e.nq.gz
│   ├── 6ccc97d55e6aa0673b1cfd2b1f3dd00aae554cb4.nq.gz
│   ├── 72a068b9a39d64591805beb93e16311fdedb694a.nq.gz
│   ├── 78a39fd71b68d3fde14c3cc5fae54918df5b7173.nq.gz
│   ├── 85138b5dd9d454f1a6124f01a4227f0e33c1b69d.nq.gz
│   ├── 9bac0f6465c4b8ad67ca102de0bc6d7d5d94ce83.nq.gz
│   ├── 9f17287751618666e1b67efde400a35384d84696.nq.gz
│   ├── a499b7036db6723efa3c2af049c7063d0ae7aaa7.nq.gz
│   ├── a67ff5b652091e780257ad835fb6d012a7daf1eb.nq.gz
│   ├── a6c4b22d8b8e7588d91d8f1e1aa1945bb6c2c796.nq.gz
│   ├── a8b5b3f492dd2d7d946737710348e880c76644d4.nq.gz
│   ├── b0f045118372ddc0a80191482a12236c7384042b.nq.gz
│   ├── b48d41c7beb5be1378dfc4a2183f9a2fde617a54.nq.gz
│   ├── b7e30c692c9a2c05c095857b579073dd671456e9.nq.gz
│   ├── b7ef27e7533de4459cae857106e374a8e09401c5.nq.gz
│   ├── b7ff0ddad98d91b38f24996710f2a5289440961a.nq.gz
│   ├── bdbd12e5b537293d72af56769c3fc7a65dea3402.nq.gz
│   ├── bfaa034bdc2ecf2edb724c08d177313f9bcc86ca.nq.gz
│   ├── c3c00b37abdf319f239504906f2a009c0ca7c8b2.nq.gz
│   ├── c3ffdad98eee4cf781fc31b57c69cfb2ee9d79d0.nq.gz
│   ├── c64d621c13e20733de4e5f56f5967efdbe514762.nq.gz
│   ├── d4440ff0608a768e90258989a36ec89d7518aa5c.nq.gz
│   ├── da79fac67dcd801af48fec9ed34b03f5dad20cf2.nq.gz
│   ├── daf39db07f4f77253d4ad5d3e3da965222aa606b.nq.gz
│   ├── e675f469920b474da4caf54615db3b6abf38b8d8.nq.gz
│   ├── e8a618dcf7698cd413720f99dbbb7c097eb34c33.nq.gz
│   ├── eaab899f17bafd18ea8e0f8879c06de0d6486a97.nq.gz
│   ├── eeea159c8a3bb88b9870bc6d9b973a682eeeb3de.nq.gz
│   ├── f346aa1b6a2b9186d9557c165792fffad9bec977.nq.gz
│   ├── fa950cb1f63a048b7c350534f34270b4995484d6.nq.gz
│   ├── fb305a38e4e5dd4283575781cf4a51af74480ede.nq.gz
│   └── fcccc0586b0d2a2608514ea64765222bfc8c6318.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 3fc54e02b9979427aa8c5bcb1e0c50eb29f552dd.nq.gz
├── filetree
│   ├── 27ddfcbf1dae0ebf532ce6559947441d4b124c23.nq.gz
│   ├── 2d5f5ae746ec644203d124f26ad068c939383d42.nq.gz
│   ├── 321a116f7ced6919eb1e0e1ac857ee8cca584494.nq.gz
│   ├── 36fb95fe60820891696c1d0d8c61fc9b71f7c9d3.nq.gz
│   ├── 3fc54e02b9979427aa8c5bcb1e0c50eb29f552dd.nq.gz
│   ├── 6801b18f9a8470f61b3c5ab99fb14d7ddda344d6.nq.gz
│   ├── 835fef84f695bed703f27ba032319104b422897e.nq.gz
│   ├── 8f9ab6f3bb8595b71b16363faf93ad029beab324.nq.gz
│   ├── 998b5d717e6a8620bf9383b60eafbf14df1fc490.nq.gz
│   ├── a4fe152917b3a01e8bdd0d6b3a58cb406165400b.nq.gz
│   ├── a6afe4a945b6955c29e5f50c70b7bc9d9768e92e.nq.gz
│   ├── c18f14722ced686d26a427bd6cf2f7889714be9c.nq.gz
│   ├── d0e5bc902ee382c5ddbf190d20b6672cac27e667.nq.gz
│   ├── dd2c6950c5125663fe053c8e7b20124cf4eb877f.nq.gz
│   └── f1feb019497a30d3252727eb1175f7b12c7f0bb6.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 77 files
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

## Source repository

[repolex-ai/forx](https://github.com/repolex-ai/forx)

---
*Parsed on 2026-09-24 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of openai/swarm

RDF knowledge graph data for [openai/swarm](https://github.com/openai/swarm), parsed by [repolex](https://repolex.ai).

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
rlex download openai/swarm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6af0b4caf37dca4526dfd98e9fbd8ce36e7eeb22
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6af0b4caf37dca4526dfd98e9fbd8ce36e7eeb22
│           └── chunk-001.nq.gz
├── blob
│   ├── 0099abbd122717151d76a53bf4f8b4f446407ed6.nq.gz
│   ├── 02ba0a7f0e3f4bc8bda47c0d5347ca2aa1562035.nq.gz
│   ├── 03325af5017396e2183d25924a36b8d8a36e6af2.nq.gz
│   ├── 04a827954f73ca100cad823898749bbe79fa4881.nq.gz
│   ├── 04f16a1565841b6d376c53489aa62a9c9c5c181c.nq.gz
│   ├── 0a641d7ff17f805389e42c922a6cd047ec4b2f92.nq.gz
│   ├── 1149a18c7bf85cc46518b6b34fdaf77ce8cfe85c.nq.gz
│   ├── 19057d2b643cef08c5fc31c18aebdf879c2e5a05.nq.gz
│   ├── 1e069e86baf2dec3c8fa7d48892ff6b067405765.nq.gz
│   ├── 23f46bd3eb59264043bcd4e62a2f378b1f9c64c2.nq.gz
│   ├── 2a1cb40c7e1b60e1716a1d8ff6658f60db678901.nq.gz
│   ├── 30e889de36a91b8817e379f993d167155aa7a470.nq.gz
│   ├── 324c8f2b18574bdbc3890edf7dfa199e68bd28ed.nq.gz
│   ├── 366d256d3500b61f78896a97ec4ad8433e113d7d.nq.gz
│   ├── 3c18c8aa5c301d30f05379d6c6586bea18daa056.nq.gz
│   ├── 3c35d95b928b057a068e1c1dbb2b0c3a910ff147.nq.gz
│   ├── 3e3760376b450b5a9b9e6c9c8ff79d2305903cc0.nq.gz
│   ├── 3ec1898c8b0d8e436d7275f5100f9ea243ed04c3.nq.gz
│   ├── 3fa23fe6e7ca678e7e2045fc1ef1c07a2fba9360.nq.gz
│   ├── 43b05ef614c3da255e50e43a6cb3e70d4831b7ab.nq.gz
│   ├── 4594126ad1ca06c83048bb3fed2b8d47d5de8c1f.nq.gz
│   ├── 46433828dd87ba7c511dd8d89c86f9bae40f8f5a.nq.gz
│   ├── 466a3675b9c5195774d2d72e56e8f9eeefebd244.nq.gz
│   ├── 4cf81838618d150731b2ab1405f99522f8c7cb0a.nq.gz
│   ├── 4d5ab015884ce4721d268cbfbd17a62b68fe4820.nq.gz
│   ├── 50c3d0ee1c5bc04011d40815dda50d13c23fd528.nq.gz
│   ├── 520c8da2daaec40bee726004b0e07ec3521d9f53.nq.gz
│   ├── 556c794a5ad83739c7f57e2981a4017600ab6a23.nq.gz
│   ├── 5709e9c2e726ccafc9a6b48cc8773c6db3fe9626.nq.gz
│   ├── 592bd86f544e35a8f7b79c31621d554b4bb243dc.nq.gz
│   ├── 5996f3b535103ca0b14857d4dd8d06c8c615359d.nq.gz
│   ├── 5ac382a2beacc771b03924d3fd53f45ec55b5d35.nq.gz
│   ├── 5ca4d33cb226ca45a31380cac6de45daddbe99cf.nq.gz
│   ├── 64836f93899e1cf2ab2c1ed5eb153db703add78e.nq.gz
│   ├── 65dedf1a021f8f23152b5a0c67d9b82509175e50.nq.gz
│   ├── 69113c19ddac2d666d9d74d10891d98e651b86d5.nq.gz
│   ├── 6c350c2f89785cbe6ab824eac69431e2d6cd7c2a.nq.gz
│   ├── 7bbfa1fdf582210f990a623fe93878c89ea08ed9.nq.gz
│   ├── 7e6c36b15152897844cfe026c7c18a3787be47d3.nq.gz
│   ├── 7fd26b970b848120ad4f6ab398e1864ab0111e60.nq.gz
│   ├── 80c1820d3fe6395eb44a929e612ba14a4e56758f.nq.gz
│   ├── 8424ee860e864b10627c4e88f21277cdd2ac2817.nq.gz
│   ├── 8a9e5961ef957e02fcb8ae28a7fbba248d7424be.nq.gz
│   ├── 8cb656b51154b7b5a1cd025cb47f7621ab858e15.nq.gz
│   ├── 8eaa0551014be5a0135835bc2a630bcf416e20ad.nq.gz
│   ├── 8f378693b21ca6bef9f7893ea36f485bc5b3ed0b.nq.gz
│   ├── 910b0f1d1b4aa48474c9fec6fbfe9f7bed7bb24c.nq.gz
│   ├── 9124145b541d98e90fe92996e018fb9d369c28ea.nq.gz
│   ├── 91ba98f3a21392ddd8c0e375f1f01e6d85d9e623.nq.gz
│   ├── 92678448ebf5fcee9455a7569193371d0366d4e5.nq.gz
│   ├── 9551c2551bcd9b7e465af430a01a2986aafdfef9.nq.gz
│   ├── 9e170a6daead28263a6fa782d9d9ce263efb44bf.nq.gz
│   ├── a47b62100f25e59653fd41db8563ea54e2781013.nq.gz
│   ├── a5743ee45fd761ce8584071875659d51bba70784.nq.gz
│   ├── a7a138f59c8163bdf3660ff233a913ea4350bad9.nq.gz
│   ├── aa2fc99e70e8b2f5f81f4b5ba953e280858bd781.nq.gz
│   ├── abdfad42d788f874ce523a263ab7b72af6ca3416.nq.gz
│   ├── b1f95ee0ba302e5284fa3683066fb1a26ed03ce0.nq.gz
│   ├── b2e9e986c601a7154cccb81fa9a7c526cecee471.nq.gz
│   ├── bcc1e195f17f6442fba96318fd2288a8c08653ac.nq.gz
│   ├── bd0995b9068c2090799b3a926a48840a309b07f5.nq.gz
│   ├── bea461b8577d5e26ae9ce5b90edd14d8d669c4b9.nq.gz
│   ├── c1440a8ffc288ae052800f8819a1775d901dd4fa.nq.gz
│   ├── c44072942bcb40f2e0e692aa02b2e097b148ee9f.nq.gz
│   ├── c51768080de841d0b4c778ebf5f255cb4c81a157.nq.gz
│   ├── d4c1787e28488fcd584871e5fcea75a88ce129c3.nq.gz
│   ├── d67b1a93712270e2263a237cff50a1b3f1e00bd5.nq.gz
│   ├── dd6d75eb04655cc2705024a05d18f30198d51120.nq.gz
│   ├── de2d0fa6803a8e0656ea0ea9505c9eadb02ceedb.nq.gz
│   ├── e64c27eedc0c0f88632926d2636bb8d0ada944cf.nq.gz
│   ├── e66945301da0f09264741431928bd706a0255c93.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a5959da958c8f1204e3514b4263992a79982e0.nq.gz
│   ├── f3ecd61a17d18372ed1c1958bf93f9803e13f193.nq.gz
│   ├── fa6e0ef1abf69a23491e8a2de7fa8d907facc96e.nq.gz
│   ├── fa9558c3682d9f312c0e35b65c1e34ac22d21964.nq.gz
│   └── fe3d70e2e3dbb31d6ce4e83189abfdf5d3de5361.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6af0b4caf37dca4526dfd98e9fbd8ce36e7eeb22.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[openai/swarm](https://github.com/openai/swarm)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*

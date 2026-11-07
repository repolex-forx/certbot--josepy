# Repolex Knowledge Graph of certbot/josepy

RDF knowledge graph data for [certbot/josepy](https://github.com/certbot/josepy), parsed by [repolex](https://repolex.ai).

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
rlex download certbot/josepy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7069e07e20408bf1bf911427f5d386a2d6471d5d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7069e07e20408bf1bf911427f5d386a2d6471d5d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0024401a39cc73ae58b2370e484b97b9cc7f5790.nq.gz
│   ├── 060a80993b48cb94de4ab9e1fbe62bf8f7aba398.nq.gz
│   ├── 0a553342d15793009d264f78805c2399db04ac21.nq.gz
│   ├── 0bed0b91a01836721964a4cb922186184789dfae.nq.gz
│   ├── 0fc8fcc7f6d5e3c712b4e8ed4acb3e6670cbfe7b.nq.gz
│   ├── 199814126f86a07407caf974cb7f7853c924c52f.nq.gz
│   ├── 1dfe6bdcb4ebb0f529084f6d6b686c920e0786dc.nq.gz
│   ├── 209e3557ced6f42881a3f233460ef92c59eee1f0.nq.gz
│   ├── 23b07cc33a522f6ae4289775a2ea65bb94ff8ca0.nq.gz
│   ├── 24fe43fa9a54e0aff28c4d9f01f80aa7fbc40849.nq.gz
│   ├── 2b361920a737dde725cb537b4bac2510af196ba3.nq.gz
│   ├── 2b912b6895075be2393514572edcdfc7e2a50187.nq.gz
│   ├── 2cf20f833c6eab6b0316539b3b22e65262def601.nq.gz
│   ├── 2fb012b1480f782b744967cff64156ed3e8f91fb.nq.gz
│   ├── 2fd019e5c226a4a1a432f795733d949c0d332e2c.nq.gz
│   ├── 34cf5ce235698ad85d46a269ea30c4637a781d74.nq.gz
│   ├── 3944cd1dbc805c7f3b7910327b3d90f5048cfebc.nq.gz
│   ├── 3af53150eae92a60982dfb14641dc3942c20e91f.nq.gz
│   ├── 3c656667d80e32fe226f67a03b27e4a0144aafc6.nq.gz
│   ├── 3d22325747b93e7137dcce9e63e01aeaab105bf5.nq.gz
│   ├── 3fdc9404f4d58c6aa03e1f33569054a46cc83185.nq.gz
│   ├── 415b14d1dd0310b412fc2eeeea75badd6cd84fe6.nq.gz
│   ├── 427b1e36f151b4d917f2f308f3cd37f5f7b37f01.nq.gz
│   ├── 4744d8751fe34b13e7ced847735b369ef484cd8c.nq.gz
│   ├── 4c91d88448b28c28d3c95c2ae53ba6fa3d0a3365.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5694c3f518ff088fa2c99890f9f1ab85a7012bb3.nq.gz
│   ├── 578218ed106cebc74bd41cf766e5fc11016e903c.nq.gz
│   ├── 57d83b380f2d97a4f1010c4ad06f92a7d0ff7941.nq.gz
│   ├── 5847aed556f3167763fe153350b39d3d22fb1554.nq.gz
│   ├── 59c869ee86060491afdc6b279a681da5c0de4f85.nq.gz
│   ├── 5a22117b682f2fdb6457a4e6147f8d4adb4cbeff.nq.gz
│   ├── 5cf5299852f4c47a146a419a27a24aee2016f606.nq.gz
│   ├── 5d6c6a0acc8bcfccc296bca5fb182ae575ad0f92.nq.gz
│   ├── 610c8d3156a0fdb53e76bfd07ee542a4bdebaf68.nq.gz
│   ├── 63f9ea15bd69a640a1928d31710730814338f5bd.nq.gz
│   ├── 659274d1d9ff29898151e7ef645ad275fbdb0cd6.nq.gz
│   ├── 67ba1df650893d7fab6a7b3860fb5c0b175559aa.nq.gz
│   ├── 695b6c47fa4c174a9aadc3303f18f995195d61c9.nq.gz
│   ├── 6ea9055438fd32b2ba3ef6c0e183453cdc76bde4.nq.gz
│   ├── 70f387c23b1f6493b6898ded8c6c219395752495.nq.gz
│   ├── 7aec8ab1c5571b8ca0f93d566f1821b47ea57a91.nq.gz
│   ├── 813db67b0be911152059274bc0b1a9b632e711df.nq.gz
│   ├── 83a8073f2d5dd194f364a29c8490b72a214ef3b0.nq.gz
│   ├── 83f6962086e842f6c12ffd03502dc4ff4ac24d5e.nq.gz
│   ├── 8e1456832b27ecbabaa91a97506cf3befb1a8566.nq.gz
│   ├── 8e515807bc010ead21c1a0756a78de16ceff222a.nq.gz
│   ├── 8f6b52bd77dafed024e143326d3a7785ce05e34c.nq.gz
│   ├── 932649692ba62872d8171a04c5438ce37c5ed85a.nq.gz
│   ├── 96c55cbf40eef0aa0c6da6b6e33c2bb60b179561.nq.gz
│   ├── 981c46c9f9362f8b5a6f33ec21ebd34508f5471d.nq.gz
│   ├── a3d36632d83a8ef5aac77a5eecd2bc802a3e77ea.nq.gz
│   ├── a6c252e372bc897f6bbe566cebb034f68bfa1814.nq.gz
│   ├── a7128e35ca2e07890cfa6cfee952e2a2fc182b14.nq.gz
│   ├── a8ac143615200b8192a929f2d98c9f28ed0bcae2.nq.gz
│   ├── a9a42aa917bac96ddf9ef569a6d65df339d52782.nq.gz
│   ├── aa0de1f5b12933a30dc64a63e32b4367653dbe0f.nq.gz
│   ├── ab1033bd37224ee84b5862fb25f094db73809b74.nq.gz
│   ├── ab231982f25ba5b804bc3e4249ec71f8a98109ab.nq.gz
│   ├── b364c3dee488f8a15cb7106237e50e385e9507e3.nq.gz
│   ├── b6818e39d6c43a146d6acea4b27f45362189b740.nq.gz
│   ├── b98f882fddc82cb653956e421c12a37c00cff0bc.nq.gz
│   ├── ba65b13af5ea2386f0e5a279f93bd5064181b7ed.nq.gz
│   ├── cd882b0c0324b9192a35b2dc3f1e77bdfa5202ec.nq.gz
│   ├── d2509ba2391417012a96f729620abd21f4363ba9.nq.gz
│   ├── d43ac85a16a5ec7cb3db7895f0c67f9e0a52f492.nq.gz
│   ├── d6e91a420e08dd2523e605b43f242aae96bd7b33.nq.gz
│   ├── d7ff8f405475faabc6c9653fef5bc62919b56617.nq.gz
│   ├── dcb835994248b52bf10089f7ac0dfcc0dd1d3990.nq.gz
│   ├── dd6708ee154b6b01c2c63311322db71bfd62d01c.nq.gz
│   ├── de5339d030ff7888fecae5b8960f8c8cb47c67f9.nq.gz
│   ├── e101ec685bf4027b57724bdef4f2ec4afe3bf1af.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e968674f7be301834623ce0c827715f0efa5b92f.nq.gz
│   ├── ea025daf6c8917ce7f10c3217959a4768ed8fbfb.nq.gz
│   ├── eb64062958b7d4e9df2f6d69e3ce392424364507.nq.gz
│   ├── f5536e78e1e84375896dabe284564a7220a978a3.nq.gz
│   ├── f87f7c3f76d2b36c21141a229d8dbbb19b8dbdb5.nq.gz
│   ├── f90a5186417734f39f97f5d40d37a06e1c65f6d9.nq.gz
│   ├── f9c6a55ccde9fa2f9884afb2af41163bc7fdebbe.nq.gz
│   ├── fd1807a7d893269824e0e2c5e90972ac3d031591.nq.gz
│   └── febe462dae88a0fa76b54f4a18d0a350ce74e686.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7069e07e20408bf1bf911427f5d386a2d6471d5d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
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

[certbot/josepy](https://github.com/certbot/josepy)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

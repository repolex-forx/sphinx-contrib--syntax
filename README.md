# Repolex Knowledge Graph of sphinx-contrib/syntax

RDF knowledge graph data for [sphinx-contrib/syntax](https://github.com/sphinx-contrib/syntax), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/syntax
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fed3d9137da091a55b8756d84190e7b2dc9efd0e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fed3d9137da091a55b8756d84190e7b2dc9efd0e
│           └── chunk-001.nq.gz
├── blob
│   ├── 04c25266c7f33e586a23697f6ab061ee8dee7cff.nq.gz
│   ├── 0db722c8db5dd3624ebec5884e1aa41c5346b0fe.nq.gz
│   ├── 0e6f9ccb785416b9194522201736d601553fd2b1.nq.gz
│   ├── 11ebaafd03034095bb6c910d9afdb530346bb2ae.nq.gz
│   ├── 140abc8b7bed86edd83218afe4e104ec866929da.nq.gz
│   ├── 1a4f0663b25d80f3891a6f16fb37f7d61fa5bb5d.nq.gz
│   ├── 1b3d746eeacc8092ae7b9c3c4c50c041b8b2fdec.nq.gz
│   ├── 1f646756c6fc98fff14d77dbd19bd0fc665b8ee1.nq.gz
│   ├── 20652522c6febab0902cd696d52d9cf38283f491.nq.gz
│   ├── 207019d590db693553a581ff3c0e3cf87b6d4181.nq.gz
│   ├── 2553f658bed2e314b71a52388b97f23ed3c21e21.nq.gz
│   ├── 2595a978e21c145a24c540bcd091db32e93f395c.nq.gz
│   ├── 27300f2ec1057eab1c0fa30c973021e5b8c77488.nq.gz
│   ├── 27e6987d7b0d984d85dce1d4667fdb7b31dfae53.nq.gz
│   ├── 2962e8b7c0d4e5aa4662cdf28c554efbbac5d0bf.nq.gz
│   ├── 2d7949fa773c5d4c238471f1b03f9feb00b76fc6.nq.gz
│   ├── 2dc8ade01f6fbca1c514c56d637e3493b94759fa.nq.gz
│   ├── 3042c52d66e4bad84b6fa8403c57d09326018753.nq.gz
│   ├── 30c6c85e2058dbb9c4dfc69063f2abc663908344.nq.gz
│   ├── 31881d3d1a7433c06cf8e2802ddbddf89ac8dcb3.nq.gz
│   ├── 33a23c86d364e316774c94771e8d3ca36cbc6253.nq.gz
│   ├── 40a213ae387bb3d80eb5d8acdbd09c6729be8b22.nq.gz
│   ├── 44e6a0ee36fa69b542f999510d7123f644a8c33b.nq.gz
│   ├── 4b03083e648ca7a9ecb43ab15daa96b2c57450c8.nq.gz
│   ├── 4bdfa853f66eab77f8ba6b71b41ad2e6b0b892b1.nq.gz
│   ├── 4f24b0ef3d50370cb591ebf867ac9ce3fa9f9167.nq.gz
│   ├── 4fedf4d834ea6bb51e6a29e2653ac4329c6b6f28.nq.gz
│   ├── 50617ffb24d1fbdfc6fc5d04b2fae70bd2c00af3.nq.gz
│   ├── 51f95f274d4d6c57217c613b1a31ed44c657d19d.nq.gz
│   ├── 549e066cd211dcf2b8f9fdc0e047f3a149ba1d6e.nq.gz
│   ├── 54cf9a61fc80c10f92ba89853a7be23cb53f8c6f.nq.gz
│   ├── 554001261ac2933a6ac979c04b6024bf209f6343.nq.gz
│   ├── 57326b037dd47493fe13c4f67835f2720be488ed.nq.gz
│   ├── 575cf8ea679129b160eb177ac445798324a9d964.nq.gz
│   ├── 5bc3d2265de329961977619c6e9b6b4cb9eecef6.nq.gz
│   ├── 5d43cbe0af30d2997e56f34cbf6315ff626334b8.nq.gz
│   ├── 5e12de3298942461e41ee626165ebca1ba60680d.nq.gz
│   ├── 5efb2058f9208fee1d5576401cb9bf0242177d1b.nq.gz
│   ├── 63c32a3629aab5c92cc6e2052a2c29e985951369.nq.gz
│   ├── 63cff4707d2b32d250d640cbd8e175da3bd5d3ed.nq.gz
│   ├── 64285686f25981d34f79d7368093678bbbcd7cac.nq.gz
│   ├── 6a3ca8d58daddcbaa87316e7068ae8c2a33729b3.nq.gz
│   ├── 6d483a5cb56a540a2ccd5a5ffd53e543e9c54043.nq.gz
│   ├── 6d9f6b0e3aa56179ef76ef3155494c78c6540a35.nq.gz
│   ├── 7721de6075d09d19efc8658c92780c6de1c15b91.nq.gz
│   ├── 7c999a795a44acb158770364c19faaf4c1abfa15.nq.gz
│   ├── 7f901f21c5892ff9424efd88dba983620a6d00dd.nq.gz
│   ├── 82dfb1065b21ff786736bba8dad731702ffa9897.nq.gz
│   ├── 84eeed30f87993f6082572b889944a8a8750f610.nq.gz
│   ├── 86c8a21013497ff1220da44613189496232180c1.nq.gz
│   ├── 8887b087fc95b8ad4cbe88e8d5a98b19c0860a45.nq.gz
│   ├── 8999ec684c7cd632da4f8b265c17a5561692e045.nq.gz
│   ├── 8ae9e291ebaf21bbacbb4157d550a3a5ea491271.nq.gz
│   ├── 8b6907f82be8df205a11e7342667150278dd5872.nq.gz
│   ├── 8cfccff7499c1e36d3f225caf76d9c4e4e603747.nq.gz
│   ├── 8fec1e7c4705f2de6bfc7546081afef2e09bb894.nq.gz
│   ├── 9115400f06e78f9bbf6a3e1f88fb326832676e25.nq.gz
│   ├── 923014e1460bf6f061aae61a56cb281acf67395f.nq.gz
│   ├── 9495d79d1c56e5330e237a5e3fe9f05c808ce555.nq.gz
│   ├── 9953949fb32c8687798bd4b7f3ab536303550777.nq.gz
│   ├── 9eb25dd104dc055a136ed000a12cd8bf805c7e18.nq.gz
│   ├── a090c92b794fb617ffb2b85f0f724bd58b3992f0.nq.gz
│   ├── a0fc57c91f599cdeef4215a2725eba77283bd478.nq.gz
│   ├── af05770687664e59497ec09b9da55bf1b1ad949f.nq.gz
│   ├── b3d0c0a7a5c394516d1f00a7f6a711a2419b45ed.nq.gz
│   ├── b4b9a4a48ce2675cff72df1b66bfbc03a310e210.nq.gz
│   ├── be30d84f3aba1ffe90b4afd6122007e9c5c300e3.nq.gz
│   ├── bf56d359f5fc8dadfbacd218346525ceeb660098.nq.gz
│   ├── c5de9ea38b3768e57ef9b8e834670a03c3dec414.nq.gz
│   ├── c6788603481ce55a80b8e8bb2da46d954f305dfa.nq.gz
│   ├── ca8770c98e817483fd036619ee4c73cc89e7f4fe.nq.gz
│   ├── cb20f2e27b5907a051959d829428fb47b28005b7.nq.gz
│   ├── cc9c505befb9d77e90b2cf8b80ccb3053e440ce0.nq.gz
│   ├── d22f58c0afffa3f72727803add5019de1a4487bf.nq.gz
│   ├── d232b30129c728db2ac43542dc9e60e162efc07b.nq.gz
│   ├── d46f39e1ed9c0b84705e28241fa08b7c21a4e916.nq.gz
│   ├── d7eaedc8385ba6af373852e2cb08a0d595c20ca3.nq.gz
│   ├── d83c10c4f7740ebfe7d8a1986c789922170a1789.nq.gz
│   ├── dc1312ab09ca6fb0267dee6b28a38e69c253631a.nq.gz
│   ├── de73906ad9000c4303d2e1758659d22bfb335185.nq.gz
│   ├── dfb218e45347e74b62af2159751b6b93e1d63011.nq.gz
│   ├── e12b20f244d25f70038a706cda8a005d7a2d3e7e.nq.gz
│   ├── e1db3de76f88304542eca0013796081a75183ebf.nq.gz
│   ├── e2d1fb8ad2dbaf753fe0487e7f9f3ae65749c421.nq.gz
│   ├── e4841ae10fa1999f4e2e2b58575611e05b42e947.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a8221377ea7aaec4a875fb8a66e5a4a14c421b.nq.gz
│   ├── e6dd76a3354cc76a943e636bc5675b4c5c26272e.nq.gz
│   ├── ea4cf077c3be3fe758212d9b64c113004b9cc312.nq.gz
│   ├── ed88099027f775942fa65dce2314f1ae9675cb36.nq.gz
│   ├── eee239b9479084460e94bced7698972095bd1026.nq.gz
│   ├── eee93da8abf37ab3afd57b39fca614c1fb08785e.nq.gz
│   ├── f3559a0515e01b90075edba289c018a5aeddae2c.nq.gz
│   ├── f5941cfebd35003bb44adbaedef75231788ace18.nq.gz
│   ├── f9ac3b584264161821d4829db3df28c48105660c.nq.gz
│   └── f9dcf20dc7c47b53495a88e7e0a58ae258931dfc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fed3d9137da091a55b8756d84190e7b2dc9efd0e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[sphinx-contrib/syntax](https://github.com/sphinx-contrib/syntax)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*

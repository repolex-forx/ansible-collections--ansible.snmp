# Repolex Knowledge Graph of ansible-collections/ansible.snmp

RDF knowledge graph data for [ansible-collections/ansible.snmp](https://github.com/ansible-collections/ansible.snmp), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.snmp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cb63215fda37b41433dcc65a5e89678926332b16
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cb63215fda37b41433dcc65a5e89678926332b16
│           └── chunk-001.nq.gz
├── blob
│   ├── 0505be1ba8b2f89f2f64756b9d6580137b53dfc2.nq.gz
│   ├── 0836fabd9b45ce951ab37c083f84c0b9e0fcd697.nq.gz
│   ├── 0a7771716fcd8c925f1682a577b4ff7702ce41c1.nq.gz
│   ├── 0aa34eb5e636839e54022e14e46ab51d7d279256.nq.gz
│   ├── 0b1692fb2308b5d997b358a2ef290b49133fe1bc.nq.gz
│   ├── 11df49a514213045dc9d86d69cb0a9e87e780d5a.nq.gz
│   ├── 16e77a2a10a4a225dc6847c706e6a1289b7bcb2a.nq.gz
│   ├── 18ecb25d51ac07a501ac67094139b2ffb62ca91a.nq.gz
│   ├── 1af442af8c494065baafce356e348eda5b32f41d.nq.gz
│   ├── 20ca9363351167d80bd2d2feac2d9827b824c05a.nq.gz
│   ├── 21e378c098b4deab642cd5be241332c44b096072.nq.gz
│   ├── 2226d926c94594335178add7dcd8723535e319d9.nq.gz
│   ├── 2308df05fd351252c138e3cfa5a0f74ca9fbe912.nq.gz
│   ├── 2f155e39596a12bb79a5723862b5a5f8251c51c9.nq.gz
│   ├── 33a890a5797897836a849ebb880377ab0307cb34.nq.gz
│   ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
│   ├── 40e0e0fea41d51d9cfca140e8c036b9b24db4aaf.nq.gz
│   ├── 43ed0168f22104e291a7c35cb4434476b6ad5538.nq.gz
│   ├── 49c7554d4b2efff8e88120c51a2ac96526c1dba7.nq.gz
│   ├── 4ae9c1418ebee19c7bbf3ca3b960e6b445f74ad9.nq.gz
│   ├── 53beb5e091ffc922fd7c2d4783566fecab415e13.nq.gz
│   ├── 5eaf226769916763acbc79df60549ecd496b8b72.nq.gz
│   ├── 611c2adcb009e26ef2da72927230a736e1cd792a.nq.gz
│   ├── 6db8c25680006d476b2b4c06798bbecda1abadc3.nq.gz
│   ├── 6dbb1aa3975b9933c82059312843e0b406a818fc.nq.gz
│   ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
│   ├── 7661b9c3abac619c13c2c32b27bc4e32ab073cfa.nq.gz
│   ├── 8be4e5c530d5c7c4eb4a4d8a04d1f2cb6e543137.nq.gz
│   ├── 8f1baf43b31610a8fea942822180c4bee14f2049.nq.gz
│   ├── 90a2f4d9c3c68c0468720653711b10f233d82f4c.nq.gz
│   ├── 9331c6ede5358339402e0c1b8c2253db8701b602.nq.gz
│   ├── 9ce213b9e30ab405e21990eed493b0e594506ce0.nq.gz
│   ├── 9d264a4f5be8db0128e24d0601700b32183afdeb.nq.gz
│   ├── 9d83c9178268e45154dd2fae2fd8ac96bc8509af.nq.gz
│   ├── a44718cd019a103a380e2123ce453cbeb307c5dd.nq.gz
│   ├── a906979880633635e6fe63a2d3910b9d78654626.nq.gz
│   ├── ae33bc320a75a4e5e09d429c449aa261838f78fe.nq.gz
│   ├── b120bfa32ad22c4f930298e31ddfdca78d613d81.nq.gz
│   ├── b3e96890c581b11faad7060e4caf97a59dc7cb24.nq.gz
│   ├── b6e7ef563dd235aeab417dca0cc54d7e1e7026d9.nq.gz
│   ├── b74f7dc122bbda40ea4041007608e6ce1ccaccd7.nq.gz
│   ├── bbebb01d9a23ebb056e7927ce80481ee7461aa07.nq.gz
│   ├── c10ca2edc109224444d4b706ea95a750e5649c6a.nq.gz
│   ├── c236173eb6da4797fab16deeeb64c58f590826a7.nq.gz
│   ├── cceca4dadb1fb5b6b50767e884d5eb5a7456885b.nq.gz
│   ├── cf383ab1238f3e3222ceb00a7c014e498390b35b.nq.gz
│   ├── cff9d92de1ab7514088e735dd26e5b2a954ee741.nq.gz
│   ├── d0a42730096743c854194791a9ad3aec75440958.nq.gz
│   ├── d880adb2245cd337f4c4f48bea787b45f669c459.nq.gz
│   ├── da03b0836bf1eb27d44f7956b2a5b9c56ae96051.nq.gz
│   ├── dd9cb6e06afedd82602485878184e5338cc2bb63.nq.gz
│   ├── de20667f0ede5b4a8ad660cdf2c3777467ce0a22.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b18a432498021c3b2325d6f7a72272314a5a0e.nq.gz
│   ├── e7d9a9184bcbd5350cceae83d20623ff8e2b8a75.nq.gz
│   ├── ea77a8f46fa7e9cd2028c5fb8837b3f8e1de2860.nq.gz
│   ├── eecf53aea77c55cacc2d93605fbf0eaab4185c29.nq.gz
│   ├── f0f4dbf79899119df79486bb5188ac67f811ceaf.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f32da4c63a3e25160696ea0e04b1b86363d85c43.nq.gz
│   ├── f8890cf3379fcfa4e8820ba559457d75a057d9d5.nq.gz
│   ├── fa4225f3eddd267a91bdd4c2d2ccee679c90ca97.nq.gz
│   ├── fcea940ca9eb8738b18bc5c7146bfe7587ef1fd3.nq.gz
│   └── fd6d7a722a7f412806abc92d2ad9ef2c816d0d79.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cb63215fda37b41433dcc65a5e89678926332b16.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[ansible-collections/ansible.snmp](https://github.com/ansible-collections/ansible.snmp)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

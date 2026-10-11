# Repolex Knowledge Graph of aio-libs/aiohttp-session

RDF knowledge graph data for [aio-libs/aiohttp-session](https://github.com/aio-libs/aiohttp-session), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-session
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5060d64ba2447376132ac62ccebe9e9bab3057a0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5060d64ba2447376132ac62ccebe9e9bab3057a0
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b2f7b0655f41276d418ca8302dbaec8b7e7e829.nq.gz
│   ├── 0da3bb499c5419cd30313d28550ac9e8b02864ec.nq.gz
│   ├── 14453a0184941b4a8eca9c40b6eee324f4730241.nq.gz
│   ├── 1b8400d8644e87b1c4db039153fbe97c85077e61.nq.gz
│   ├── 262fdbb57ed782751cd1d7eb24efe5686189adf9.nq.gz
│   ├── 2bb26d66718944447bcc3f798541c9a7437ea476.nq.gz
│   ├── 2e004b00b7781cf9ddc74d6a337ba0ad78af930e.nq.gz
│   ├── 3291aea1c09514a38acb8deca04cbf6a3ce1e94b.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 3cdd41c3af27af61c37c6a82a317b7d3856cfeeb.nq.gz
│   ├── 3f2f2fea65b525b591d5b0fc4c229cc74fac7a8b.nq.gz
│   ├── 408b5ab50d56a90bd490c603214b127c7c1328ac.nq.gz
│   ├── 414695c0dc35beebadbc8c67ddadfe4fd8ba60d0.nq.gz
│   ├── 50350070e615d57040955882ee53d3cf3a028c4a.nq.gz
│   ├── 5085ce61de2709d66b4120e37de52e5aaf5e49ca.nq.gz
│   ├── 528c571cffe3f07797c232d59ee1a08f75e431e3.nq.gz
│   ├── 55c3ba3c9010f08396623659630750eed7a05f32.nq.gz
│   ├── 56b6e563e1364e1c0ded8b87f83578010fd6028c.nq.gz
│   ├── 5780fb925a4588ce80f9f82bc270fda1caacef9d.nq.gz
│   ├── 5da78e01d0b9cba2cad696073bcd8be7235f5ae3.nq.gz
│   ├── 652f261ab848ebb6ede20fc983e3eb5d210012fb.nq.gz
│   ├── 6c2ad843fe680d4fa444493713c8df09002604c1.nq.gz
│   ├── 727e3635df72f931c1414f6e1ccea3dfdc0ab132.nq.gz
│   ├── 75f971166aa4063943ec9c92aed81e04aac28046.nq.gz
│   ├── 7e34a4b50cf55f14fc4c8d9e024703c0d188b19a.nq.gz
│   ├── 7ee5860566d5015785c45ab6ac3961c42a587df6.nq.gz
│   ├── 7f6f02397518a10280f72ecc20bc20762e8fa0f1.nq.gz
│   ├── 8c7f9a2288a7451b916f13947bd7573e93bb6568.nq.gz
│   ├── 90ec80603af9793cdfbeda3d81bbecbf53d80b30.nq.gz
│   ├── 9335b7d261b2bd370f4242124994c7618d5d11d4.nq.gz
│   ├── a3401c73468ac738ac55270cbf23f3bea60a45a7.nq.gz
│   ├── a692f304b559b3a7c62b0448c9c56fde159631c1.nq.gz
│   ├── b4fa48c5f352d1550ffc47db1643919c01ca9d98.nq.gz
│   ├── b6a0ed1659a9e34af19177684eae9f05b767787a.nq.gz
│   ├── b80b44055eed3d50ef0a270e18023117c3b1cd95.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── bed473e74ae31ed163a9de470fe75feb38debc07.nq.gz
│   ├── bee69e6cc52e8e9d2cc228e7a46e4f046c0a3694.nq.gz
│   ├── c358097f2326aaa9b3cab81bbca3a3c57692e7a2.nq.gz
│   ├── c6bbbbd69c0ae33846832b2a946bd52ec08b985f.nq.gz
│   ├── d15c76a3e03866e8f6ac3db24d3ac3666179bcd1.nq.gz
│   ├── d52836661b369dec6dd0ab751a08f8fc58bd35fa.nq.gz
│   ├── dc8507fcff611fef0ad9d888c0d324168e875339.nq.gz
│   ├── dec35b73f93652592091fe16280da9bbd97f41e1.nq.gz
│   ├── e06f404eb909bacb71d4d0bc9745aaec4c73cf5e.nq.gz
│   ├── e1c35b7bed87bfed7939219dfaa215347373248a.nq.gz
│   ├── e3d05bc477e5e615bd208a90569491c2c17312cf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e89e978c744336e3973d31c0171b195abb75acff.nq.gz
│   ├── f1a1c4bd6d9e249b25ef052919fc4a79b66b5a66.nq.gz
│   ├── f784e8d63995d78e83fc25337b5f52549a13a7e4.nq.gz
│   ├── f8a504441050938ac79834ffb4a9cab5823881d1.nq.gz
│   ├── fb37eafe2c303971ce2a02c753b3235e1536f303.nq.gz
│   ├── fc6b84a2108818ae458cd96258b8f4dd96a79c5f.nq.gz
│   ├── fdba50c2676c9a0b0b41982a9f0de5a49b9b7d5c.nq.gz
│   ├── fee870034c5b70f5deac315d888f85e736b3b7aa.nq.gz
│   └── ff12709f430eeec961e47ef9d02c76e10b741e26.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5060d64ba2447376132ac62ccebe9e9bab3057a0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[aio-libs/aiohttp-session](https://github.com/aio-libs/aiohttp-session)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of mkdocstrings/griffe2md

RDF knowledge graph data for [mkdocstrings/griffe2md](https://github.com/mkdocstrings/griffe2md), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe2md
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dfb50a4e3e43fe9ff36edb4fe14dbad48f7d8dfe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dfb50a4e3e43fe9ff36edb4fe14dbad48f7d8dfe
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0124e069ab5aec480c7bf1cee1453f4831dbba1e.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 05b6a977997054e9c90ef075a6d05574e251ff79.nq.gz
│   ├── 068f20b0643487c5d15803f947ddaa276b1e8f83.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 0f3de1a697352b6cfa81b9ffbc32b41e72c5ffa7.nq.gz
│   ├── 17776e61ee7eff91bf1438f026fc59b1552defb0.nq.gz
│   ├── 1bafd8cd341ccec59b2a5ca1fb699cb3410789b6.nq.gz
│   ├── 21a34596362ef93dbf9a0ac63ff3e78bcf2ecb3a.nq.gz
│   ├── 2232d3d74d1b21de73060779fec9302aeeb4fb01.nq.gz
│   ├── 24f915fab75c83570eceee93092f50db972d5a02.nq.gz
│   ├── 2540e583c3f68dec71761f9bc6275d2b4c8c36f6.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2992ddb3fcaafae4c56416cde3ebf47acc37c372.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 3830d09ea02f30c8ab1793a42345e203a490e7cf.nq.gz
│   ├── 3a7e35d965305c98a05d8d8ac4604d31858efa0e.nq.gz
│   ├── 3d81af4aad0dad7832f777b50c79e0c617c70f3e.nq.gz
│   ├── 439f93ddfd105738aff3e60ab8db70cde498487a.nq.gz
│   ├── 43a532ec6f2b0065f9d80429dab5f88c9cb9dd29.nq.gz
│   ├── 444c6ccd622eb9f34ff25447e0c2a0430f316f93.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 471aa749143eb3f0147bfd6661db20f0bcdfffc1.nq.gz
│   ├── 49d557606ba14f04d0c4d3b5c2baa2d36f3abfab.nq.gz
│   ├── 4cf2d4d81ce21912851d26ec18c6dd2a1f54a9f0.nq.gz
│   ├── 512e6c30fcfb6fb8fbed1e829e3e17da60b37a1c.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 590368414436060deb7f7db0619f4fce73e06e97.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 627a5e8113735cc02163aa246fdd4dc593adfc1d.nq.gz
│   ├── 6334ac5637bcfec84f49b1454c17f479cee68a14.nq.gz
│   ├── 644ffc96d0a5deed92a09cea023a68eca96f2fb3.nq.gz
│   ├── 6bc7597d632c8bd95e3c9380da77d8b4db761ae8.nq.gz
│   ├── 6bfbd02aaefa2b0bac38033189922d1dea54f588.nq.gz
│   ├── 6ef522ad513066ef924d21e82d65a037363d1fa0.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 7a154cb5e12eb1b6b1f60b2469f6db80182fea44.nq.gz
│   ├── 7d51d998abd926cab7b5057f63254d4a2b1b0e07.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 8c984f392a3e0a209f5ec633c760fd7bd2aefc1c.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 975b5155b41e7a36c392dcf7ab0f7d690967de33.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 9806a37135c08b955fb97ec5b47d92e6b6b6e5cf.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 99ceebefbc485aa9e076291d073d6072e47f1f06.nq.gz
│   ├── 9a40d757fc300e9146dc86a3ff9e7a4e3fed1564.nq.gz
│   ├── 9fc1a020253d8411eaa23db82b7ce0319685fbaa.nq.gz
│   ├── a4eb1628888843bf44942571a806732d69548733.nq.gz
│   ├── a4f0d51ac33e4c32016b38c95df9c5896274fa6e.nq.gz
│   ├── aca88eef0ebd444a1fb1b620e7013431b09efbc9.nq.gz
│   ├── adb9880e6322984dcf9278aa4208528eb4a2cb60.nq.gz
│   ├── b11aa52a916010a4af66e48ea478ddfa28e70677.nq.gz
│   ├── b149d0120334ec19001efdbd479598561952c3a9.nq.gz
│   ├── b36c3726ae32200068c720fe9cc1ad03229e38af.nq.gz
│   ├── bbe3a310876a86fa0927138fd1ff400f3be29ff4.nq.gz
│   ├── bd77c59c1ed0286566b0518c3511321c9f3bba96.nq.gz
│   ├── c0d12e07cc2972f883ab37e867e70fcc0172becf.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c617d59783cce7cfce7485e8642969fe9bad625d.nq.gz
│   ├── c8335c1f9a0b9637bb8b898deefcf61f71f03ce2.nq.gz
│   ├── cd884232e8f458e2272c2c9548d26a1ceda478fb.nq.gz
│   ├── ce66f3288cc08d3e590c11261e9de87b0a8d7035.nq.gz
│   ├── d5ba71a8984070e3158733cfbcd157600436cbf7.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e3d28b38c94eeb9fa2ea0a955d3ff31c8c3ef6e6.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── e9ddc8683504783d20aa6b0eb2febd522f752a81.nq.gz
│   ├── eb0ac2dd7127e26f5a621076a27887ca914a5347.nq.gz
│   ├── eb29212bf901cf52d028eacafc79276f1dea8d10.nq.gz
│   ├── ec64971c5d629fd2417fcc5a7b28aed82c2bdc8f.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f1619695e29c88d6129f92f9b33a9718c05bb9e0.nq.gz
│   ├── f3494328c987e7e685ed1f866b92e0ee5ffa64bc.nq.gz
│   ├── f515c6316ca14db06a6b93634ea3147f036406bc.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f7b7046e2f0eed3f6353fcbd81fe3da5789e7a9b.nq.gz
│   ├── f842b2aaa98655c7d3bab61a5e3b09a6d74e6920.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   ├── fa62cadaae871b3c855c163d8a61e599650fbc6d.nq.gz
│   └── fe1c975677a64f49b1ba678ea344207c5c2f922b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dfb50a4e3e43fe9ff36edb4fe14dbad48f7d8dfe.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 99 files
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

[mkdocstrings/griffe2md](https://github.com/mkdocstrings/griffe2md)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of huggingface/peft

RDF knowledge graph data for [huggingface/peft](https://github.com/huggingface/peft), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/peft
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 3c7b6e7f0252cb18386d86b056a9b100a8160792
│   │   │   └── chunk-001.nq.gz
│   │   ├── 45996a1d6e00b0951424a210d24aa4058c7b0dcf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 48f6493f946e2ebbb19fbfb4e6816f5061367f3b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 53c25fe4fdd7c6aa4b40db0560815ea570d32303
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5d58b515672d31c57cc61a4c50a6635df645ec20
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6d5a6f4f2f902dbf13d21d2661d57c3c05df1dae
│   │   │   └── chunk-001.nq.gz
│   │   ├── 77daa8d3b7decf2b40238ab47e2c1bd0f26c7749
│   │   │   └── chunk-001.nq.gz
│   │   ├── b34d8a2ca1f491e6d96620a38fa6888dc97fb5d6
│   │   │   └── chunk-001.nq.gz
│   │   ├── c2d5f697fbb30063cbde6f39e2734883b70b8753
│   │   │   └── chunk-001.nq.gz
│   │   ├── c42eb227d9cb9b87dd63881a099a268b02584ed3
│   │   │   └── chunk-001.nq.gz
│   │   └── e3398fc05c556f64a8e8dc248628bae657107488
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 3c7b6e7f0252cb18386d86b056a9b100a8160792.nq.gz
│   │   ├── 45996a1d6e00b0951424a210d24aa4058c7b0dcf.nq.gz
│   │   ├── 48f6493f946e2ebbb19fbfb4e6816f5061367f3b.nq.gz
│   │   ├── 53c25fe4fdd7c6aa4b40db0560815ea570d32303.nq.gz
│   │   ├── 5d58b515672d31c57cc61a4c50a6635df645ec20.nq.gz
│   │   ├── 6d5a6f4f2f902dbf13d21d2661d57c3c05df1dae.nq.gz
│   │   ├── 77daa8d3b7decf2b40238ab47e2c1bd0f26c7749.nq.gz
│   │   ├── b34d8a2ca1f491e6d96620a38fa6888dc97fb5d6.nq.gz
│   │   ├── c42eb227d9cb9b87dd63881a099a268b02584ed3.nq.gz
│   │   └── e3398fc05c556f64a8e8dc248628bae657107488.nq.gz
│   └── repolex
│       ├── b34d8a2ca1f491e6d96620a38fa6888dc97fb5d6
│       │   └── chunk-001.nq.gz
│       └── c2d5f697fbb30063cbde6f39e2734883b70b8753
│           └── chunk-001.nq.gz
└── blob
    ├── 0030e22b09da586e3327a646ad91541b8b69bcb1.nq.gz
    ├── 004c26b0fe5ecf88212bd11de062baec2f10de83.nq.gz
    ├── 0096af13780729c3702a594e04fbf378c3215d1a.nq.gz
    ├── 00a043936f8159184c0e4864f587e63d374284d7.nq.gz
    ├── 00b24c3d2aaa026589aa989a5a0a441a7d9c86e0.nq.gz
    ├── 00eacb1301cbe5ff4c5d0e4c17e1bfe66a1e4b4e.nq.gz
    ├── 01107b06f7dc2caa5d74213d9439e865916fa773.nq.gz
    ├── 013964358109829537d53e85cdce086bcc66a9fe.nq.gz
    ├── 0156d0921c71353ca43c3caa5e39702cb0d64de8.nq.gz
    ├── 017216213786a4e71eee789ce8463b34f853ed45.nq.gz
    ├── 0177ea213fc177458227c91aaaaff6d6e5d94124.nq.gz
    ├── 01afdf2041691378184c596d1c56c54f29f474c9.nq.gz
    ├── 01f489ea23e3993a576fdf01ff72f289ed890134.nq.gz
    ├── 0218ff7cf32e7d3a4a31a55cbf40153022853b41.nq.gz
    ├── 02243de643fb762fee4d1a8eaf01cbcc7c1dfbe0.nq.gz
    ├── 02250eef44ece60f6b88f246985d5d5f7725f81e.nq.gz
    ├── 0270363fddc73f4c0a18f8b573a8dd8126a18825.nq.gz
    ├── 028bdcd1533910e3448d743ac68ab502a290a4ad.nq.gz
    ├── 028ccb0224df9f083d872f4f39ac7168c8aea7ef.nq.gz
    ├── 02940f7a2f7a5f571d5a3af94164f744007a1b2e.nq.gz
    ├── 02aaf10b8705d8ee565c705f67d23fd4d46d9eb7.nq.gz
    ├── 02be2c92d796067a132dcc41cc6b5058f4bec8a7.nq.gz
    ├── 02c6fd3f6953e041b22391c9270aae0e44dd7bf2.nq.gz
    ├── 02e4c87ad841b0445baf0dd37faf36799ddbb79b.nq.gz
    ├── 02e97d9bcead1053c7359b0fbe5c2f49a3c1e5e3.nq.gz
    ├── 02ee9f74396d7372104f2adf9f462e1ac4653d93.nq.gz
    ├── 030b9b6b67a3fb1e16886e3bef0b69ed76d934fd.nq.gz
    ├── 03138636bcb0a89b808a60860f14538e538d694d.nq.gz
    ├── 03139e297df1a8afc00d1e313faa3ec4859c8a6c.nq.gz
    ├── 034a20ac0f47e1098cf67337479e1c8a1b99ee0c.nq.gz
    ├── 03869c3a7af57830aa13cd6eb104ab34cd0fbe19.nq.gz
    ├── 03bfe540162d022d90807bc8872e438fcaadd95d.nq.gz
    ├── 03e4b0c0fa244f8883a7e0a0802eab489717b592.nq.gz
    ├── 0406c509d962782d297cd52a8649bff4b9f087b2.nq.gz
    ├── 040c1647a005fa59bc2046640dacdd4783aa11fe.nq.gz
    ├── 04492c351c72660ebac4f9c2288004907ee6f1c4.nq.gz
    ├── 0469785db44a15f622962bc3da8447390c511290.nq.gz
    ├── 04965b3c6360a983a1c70f88156867837f9b97e5.nq.gz
    ├── 04da849eea561596f02a6e776e7d3067ba54c5d7.nq.gz
    ├── 0528b7ad981d77d089201f233afc8255db4ada6a.nq.gz
    ├── 054c4b53c4213bd93a330c376e4b1c4f9b212b16.nq.gz
    ├── 057195a79cd0b98f7f0a6fe4ef8e71bc49ffefea.nq.gz
    ├── 05ac7c1193f8b27d397a11e0b1d4d27036e8f148.nq.gz
    ├── 05b730002446b9a05a2d9b3a1bc5b25b0baec37c.nq.gz
    ├── 05c4d2caef0fa0171adaefc2ef73943e16b5d0b0.nq.gz
    ├── 05d12dd26346c9ac27d307c8c8c9662e2af3400a.nq.gz
    ├── 06898213517951bf070d692c826642d3add9baa7.nq.gz
    ├── 06ad6cc10265a285b3533989d7154c54a79d216f.nq.gz
    ├── 06f372659c4ce5c04c87ae6d18a98d1407ac2bbb.nq.gz
    ├── 070f295112b9504dbdcc64d78b6ec2e19127a726.nq.gz
    ├── 07342b90ca043dbd8f8bc1874ca2adfb31b50a05.nq.gz
    ├── 07738b3d9368912b4287ae35f91d1c316c44d5c3.nq.gz
    ├── 07837defc91aceea2b446a9f7d332fd01a1d1aff.nq.gz
    ├── 07985e9b6ff73b6446dc5479059ede62f86319a2.nq.gz
    ├── 07dddcef7853b963ea64d20d39078893c4e21c33.nq.gz
    ├── 0890ba0e2571df384e4a629f4902d963b6181e02.nq.gz
    ├── 094ee709400e659468cf5c87b682f16aae2197e7.nq.gz
    ├── 099b77662be04aa0f83d16d649c6199c230aed87.nq.gz
    ├── 09d9c48686ec765fefd8b6e4f6deff0320ecb864.nq.gz
    ├── 09e020e0f3918a26e832f0d8ce9cc84cb8ec1469.nq.gz
    ├── 0a0035682cb0fa11079d9af6ad8c152737570c2a.nq.gz
    ├── 0a041c6651fa51aca35c95615c89bcd0dccb3421.nq.gz
    ├── 0a097e2dba4928fee6f047afd4c3992832c8abf5.nq.gz
    ├── 0a28cc94befe12ea8c30bece2c69f96dcef30006.nq.gz
    ├── 0a6a4ac196ed0e38a1f2c81ab6e398d9cb21b625.nq.gz
    ├── 0a969b0875d883cf8967d5601f72ee3bb3684ee3.nq.gz
    ├── 0a9aec966092eaf931de2548efa51ae5ec71a691.nq.gz
    ├── 0aab8bf6813b50b341ae23051925ffc74c4785cb.nq.gz
    ├── 0b0d515197056826bd7a0c05a413fbad80145afb.nq.gz
    ├── 0b6117e0547c0a876a6adf8677ace98c838af140.nq.gz
    ├── 0b62478d9f98d2de17af2424b09cc224c8ec670f.nq.gz
    ├── 0b6f661aadd52f101453a0dea29d58c7fcf58064.nq.gz
    ├── 0b71007187705da6c66c9b75603eef201df3ca00.nq.gz
    ├── 0b76173a66db251756401a35e1dfef5ae69794bb.nq.gz
    ├── 0bd57f89ba6e625aa996dab834f14835d4cfa1d5.nq.gz
    ├── 0c3033c2b300f5c6e87233fedaeb78dfaab6ea63.nq.gz
    ├── 0c4bd7d1e0b238bba692055f050e60b740f58107.nq.gz
    ├── 0c5329bf8e79a6ef8c31e07d1e2d293d6d753968.nq.gz
    ├── 0c6c686ae5b40f04fa4edb8aa5a31ac4ef253942.nq.gz
    ├── 0c710410059719eb7b50b043fa94437a45bfec28.nq.gz
    ├── 0c8e514faa808ac0874e71f21bad7a576d15349d.nq.gz
    ├── 0cdbbdca98f82583dead5792d4864fc896225a51.nq.gz
    ├── 0d159220eb881ade49ff4fb8ad5d12d8cd7e9c69.nq.gz
    ├── 0d6cfcb41110fce20337ec0964f11e42febfcb8d.nq.gz
    ├── 0d93db32293ecd528570aa477fb1963ea70bf449.nq.gz
    ├── 0d9eadf82b7fd2b4ecbfe37a20650acfd7a7aca9.nq.gz
    ├── 0dabc6f50d08389ccf96e9c9218fc7b99e1c8f54.nq.gz
    ├── 0de0061258bb7da4a9c75e81a2cab59ce186e687.nq.gz
    ├── 0e24796de4902ffd693511a0a9027fd15e53eedb.nq.gz
    ├── 0e262ccf8b54ef5de93696cd7fe6fb57109f6f4c.nq.gz
    ├── 0e29127b4315558e77b24406416d57dadaea0e6a.nq.gz
    ├── 0e462c3c63b9067a36e44e14a092b52adef3e849.nq.gz
    ├── 0e6d90f494e68487197fa6098f75949661bf0138.nq.gz
    ├── 0e73c5fe7ae50cac89e10d5702410e4dd1275b71.nq.gz
    ├── 0e8821f45db8e2dcf8f26fd8b38f8f90a28f5c09.nq.gz
    ├── 0e9e2947a7013fd00665a5783c0d216a54e65a38.nq.gz
    ├── 0ebfb744d0501e14c0a4e6395c759173ac1030f5.nq.gz
    ├── 0efd7c480f6916d70d4b51a9a4919cfac758a992.nq.gz
    ├── 0f70a8ee2fadafd0a48a9c865d96b1b8d82f62b3.nq.gz
    ├── 0f7c71c426e984eb84f1910c29e664ee41afde64.nq.gz
    ├── 0f9f82167e6fadb8322617c3977d2345f4ebc234.nq.gz
    ├── 0fb1d2c4152f707035f9609a6d86319deda58e1c.nq.gz
    ├── 0fb404fd83e77860344abd84614bc5d68a09523e.nq.gz
    ├── 0ff1f39376b5be3bee6eed8bec25744774f4b565.nq.gz
    ├── 1005b8e3a88e76ce5f749be3ef379220e020bb79.nq.gz
    ├── 1019326e1e85d31b37f9973a7dffaaedf75c90aa.nq.gz
    ├── 101a4d8c719682bb7699dc50a068cac63b7cfbdd.nq.gz
    ├── 105d13f455a9f80a74b43127f1a7b009ca5259aa.nq.gz
    ├── 10865194230bbbc0fcf232f78367dc9975549fd1.nq.gz
    ├── 10bd63383bd32594dbec3b62b6b52431d05a8e71.nq.gz
    ├── 10c9633c0ec7768b627d85ec9e83cbb62c61b1b4.nq.gz
    ├── 10ca673ddc5dc78a19da5f2712754f939e882fd1.nq.gz
    ├── 10d4551afbf44ad3eb3f9a9adfcc5cad160bef5c.nq.gz
    ├── 10e187a4bf2272af72481f261d92601ee67112fb.nq.gz
    ├── 11530edc3b6caa8030a6519b89c87e552e948628.nq.gz
    ├── 11550d604428f1fc3462829a49f99333a5cafbcc.nq.gz
    ├── 117c03e724e02bb235e123db2207341c8b5e47db.nq.gz
    ├── 119739a3dc8fb89461cd826f3696109eb7e40734.nq.gz
    ├── 11bfa45ccb898fa5df101121892325a2ef54dc71.nq.gz
    ├── 121c0a61d247dfbf230458d3166269934d95c142.nq.gz
    ├── 1259c495a16d358ba2468388c2b09309cd97291d.nq.gz
    ├── 127ee9017333bce22706b58b13701049244b1da9.nq.gz
    ├── 128fe1a2d85a8218d512006fdd577b9f06070792.nq.gz
    ├── 12b94da59291b6702b763b20d6ea366f408f6017.nq.gz
    ├── 12d898ede54ddf39e93bd4047fd55701f91b2003.nq.gz
    ├── 13047def08c8ca315ca52de59cedca72f321f2d7.nq.gz
    ├── 132cb01556efe0d73e58465ea8bd2d21eda2289a.nq.gz
    ├── 13707a37d5736a8586e2234823c064fa62936879.nq.gz
    ├── 1384bfe6fa5c9f5d8ff531541d9be5a114e7103f.nq.gz
    ├── 138e99990cf0f69c1810d6f7e07659487a562996.nq.gz
    ├── 13c7de22385c62f2ab68978024753925dc6d77be.nq.gz
    ├── 13f7fcad5883c266fd2cca0a7e0056c80ba70e7a.nq.gz
    ├── 14823fd3d796ff9e8b56ab40b30510d9a3a2f8a0.nq.gz
    ├── 1489cff08786e76473bcdcd237afd365594d9a63.nq.gz
    ├── 14e3ea77554b21a9648b8852e6b5ba05d92926ca.nq.gz
    ├── 14e96db828e4e9025552aa840da03f8a3946025a.nq.gz
    ├── 15007640a01cd46689ab9eade7b535303bb8e8bc.nq.gz
    ├── 15078fd6d63ad6c741de11e12ab59f605677ebb7.nq.gz
    ├── 1520c3743c01a7500b90fb24db653a36b4c28fa1.nq.gz
    ├── 1539b6765df0bb0433229815d992f1f9eca6c73c.nq.gz
    ├── 15406b1b15b8ba471e14800c067fde63658eb143.nq.gz
    ├── 155e0adc4a8a5aebe2f3babbbb8b0a7f945f1557.nq.gz
    ├── 155fab5530619797632079c8321aeb83a2c78c57.nq.gz
    ├── 15b1e503d02b0f0501dbf8862c3be6f6e9cafc43.nq.gz
    ├── 15baa4d787cca57b537a60a67214d78cb9988a21.nq.gz
    ├── 15bb18cb6b89fb9ae588c69db8d4c047fb40e4f1.nq.gz
    ├── 15bfa92fe897a887259c77b5ec1578c0dd47b082.nq.gz
    ├── 15f4a41a3f92d70fa6ac020af53e0d87678a0ae7.nq.gz
    ├── 15fb4f3c32b41396ca44d9b78b7d0dc6157fd545.nq.gz
    ├── 166c6b51d8b8c2ba1d573f304597d9450d44a465.nq.gz
    ├── 168942c7ceda7d1e57cbbdb382bb2998dfd70fd0.nq.gz
    ├── 16b9ae63dc5c4eba608cd1e43bb9a2436c342a59.nq.gz
    ├── 16cdb90e07410389781ce6495e5fae870e68f67d.nq.gz
    ├── 16e3c9a8ee1cc3199bd99e1e65cc12fdcc98a06c.nq.gz
    ├── 16e8fae5ac164ee952780fefc1e247f08ff54909.nq.gz
    ├── 170c4bb33e558339b07da8044fb3cb2093d2e4eb.nq.gz
    ├── 1715cc5bc65c190d3ba4dd160707d3fb0c93307a.nq.gz
    ├── 171d0d7c0f82d11cc02f27b36ac2ff8fbe0503b2.nq.gz
    ├── 1746cfe25f45a45ccb9f2d56d6da50240ae7ed1e.nq.gz
    ├── 17674a9e0cf586da2653c7655fcd72f596ce1b90.nq.gz
    ├── 179496b6f3381799df4dd23722c57bb7c2e3f2f5.nq.gz
    ├── 180b71837d77b1261500d1b759c3452652ee3386.nq.gz
    ├── 1828debe525c7d7c1d9ac7c8db4ff68524ab5edc.nq.gz
    ├── 182dd6a1f39949d3f3a8aa53fa0556fd3eb90b72.nq.gz
    ├── 185f8f5f2ed04c6b392db9f7a877e0f9185fde21.nq.gz
    ├── 18ce4b2f0625424f566b93de1d6accaf4b87ced1.nq.gz
    ├── 193f11b75694e4272ed32434d6f0d0d7fba79c93.nq.gz
    ├── 195e5cd4c80a14397003317e1c4e001f5f7db939.nq.gz
    ├── 19d2cb9ddfe84ba6cd69c771ce37640f24e9b1a8.nq.gz
    ├── 19f2f71c68454e37ea26f94ed9fc76b59bb5175d.nq.gz
    ├── 1a45e4d79f25a8809a32d2dfac537c7d6b4b3cd8.nq.gz
    ├── 1a4ed822bc86e92541449f8779aa4485b6b85eb9.nq.gz
    ├── 1a8230e68a8f325a110a99fbc8b78c0476db5d08.nq.gz
    ├── 1aa055a064404f25743ea5f16a8159b6dc899c00.nq.gz
    ├── 1b0497b3e6b31b0a17faa32f8a1bdf2d2b6331d5.nq.gz
    ├── 1b67013783a0721b2bac5d53d8ba22aec82043c4.nq.gz
    └── 1bb21e184050ac5397b3c205533db39708e40b1c.nq.gz

19 directories, 200 files
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

[huggingface/peft](https://github.com/huggingface/peft)

---
*Parsed on 2026-11-25 by [repolex](https://repolex.ai)*

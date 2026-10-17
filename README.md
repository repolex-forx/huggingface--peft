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
│   │   └── c2d5f697fbb30063cbde6f39e2734883b70b8753
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c2d5f697fbb30063cbde6f39e2734883b70b8753
│           └── chunk-001.nq.gz
└── blob
    ├── 0156d0921c71353ca43c3caa5e39702cb0d64de8.nq.gz
    ├── 017216213786a4e71eee789ce8463b34f853ed45.nq.gz
    ├── 0177ea213fc177458227c91aaaaff6d6e5d94124.nq.gz
    ├── 0218ff7cf32e7d3a4a31a55cbf40153022853b41.nq.gz
    ├── 02250eef44ece60f6b88f246985d5d5f7725f81e.nq.gz
    ├── 0270363fddc73f4c0a18f8b573a8dd8126a18825.nq.gz
    ├── 028ccb0224df9f083d872f4f39ac7168c8aea7ef.nq.gz
    ├── 02c6fd3f6953e041b22391c9270aae0e44dd7bf2.nq.gz
    ├── 02e4c87ad841b0445baf0dd37faf36799ddbb79b.nq.gz
    ├── 02e97d9bcead1053c7359b0fbe5c2f49a3c1e5e3.nq.gz
    ├── 02ee9f74396d7372104f2adf9f462e1ac4653d93.nq.gz
    ├── 030b9b6b67a3fb1e16886e3bef0b69ed76d934fd.nq.gz
    ├── 03bfe540162d022d90807bc8872e438fcaadd95d.nq.gz
    ├── 0528b7ad981d77d089201f233afc8255db4ada6a.nq.gz
    ├── 05d12dd26346c9ac27d307c8c8c9662e2af3400a.nq.gz
    ├── 06898213517951bf070d692c826642d3add9baa7.nq.gz
    ├── 07342b90ca043dbd8f8bc1874ca2adfb31b50a05.nq.gz
    ├── 07738b3d9368912b4287ae35f91d1c316c44d5c3.nq.gz
    ├── 07dddcef7853b963ea64d20d39078893c4e21c33.nq.gz
    ├── 0a6a4ac196ed0e38a1f2c81ab6e398d9cb21b625.nq.gz
    ├── 0b76173a66db251756401a35e1dfef5ae69794bb.nq.gz
    ├── 0c3033c2b300f5c6e87233fedaeb78dfaab6ea63.nq.gz
    ├── 0c6c686ae5b40f04fa4edb8aa5a31ac4ef253942.nq.gz
    ├── 0c8e514faa808ac0874e71f21bad7a576d15349d.nq.gz
    ├── 0e29127b4315558e77b24406416d57dadaea0e6a.nq.gz
    ├── 0e462c3c63b9067a36e44e14a092b52adef3e849.nq.gz
    ├── 0e6d90f494e68487197fa6098f75949661bf0138.nq.gz
    ├── 0ebfb744d0501e14c0a4e6395c759173ac1030f5.nq.gz
    ├── 0efd7c480f6916d70d4b51a9a4919cfac758a992.nq.gz
    ├── 0fb404fd83e77860344abd84614bc5d68a09523e.nq.gz
    ├── 101a4d8c719682bb7699dc50a068cac63b7cfbdd.nq.gz
    ├── 10c9633c0ec7768b627d85ec9e83cbb62c61b1b4.nq.gz
    ├── 1259c495a16d358ba2468388c2b09309cd97291d.nq.gz
    ├── 12b94da59291b6702b763b20d6ea366f408f6017.nq.gz
    ├── 14823fd3d796ff9e8b56ab40b30510d9a3a2f8a0.nq.gz
    ├── 14e3ea77554b21a9648b8852e6b5ba05d92926ca.nq.gz
    ├── 15078fd6d63ad6c741de11e12ab59f605677ebb7.nq.gz
    ├── 1520c3743c01a7500b90fb24db653a36b4c28fa1.nq.gz
    ├── 16b9ae63dc5c4eba608cd1e43bb9a2436c342a59.nq.gz
    ├── 170c4bb33e558339b07da8044fb3cb2093d2e4eb.nq.gz
    ├── 180b71837d77b1261500d1b759c3452652ee3386.nq.gz
    ├── 1828debe525c7d7c1d9ac7c8db4ff68524ab5edc.nq.gz
    ├── 185f8f5f2ed04c6b392db9f7a877e0f9185fde21.nq.gz
    ├── 1a4ed822bc86e92541449f8779aa4485b6b85eb9.nq.gz
    ├── 1aa055a064404f25743ea5f16a8159b6dc899c00.nq.gz
    ├── 1b0497b3e6b31b0a17faa32f8a1bdf2d2b6331d5.nq.gz
    ├── 1bc1345c0a53e1e2d286ffd3576c136174e7b538.nq.gz
    ├── 1bea9ba41368ebbda9aa4abe29e86b2b42859693.nq.gz
    ├── 1c1314dbd60e1d98cd68b1aaa32c0613b5ea36b3.nq.gz
    ├── 1c4161e5ed97998017b800535d4315c66c9d14cd.nq.gz
    ├── 1c458655eb9badf039e02903de733be2eb3af46d.nq.gz
    ├── 1cec82758be5b324aba1ee87ce5f55144eff6228.nq.gz
    ├── 1de3c8cc3647e434d664f1553bf71921d101ca6a.nq.gz
    ├── 1eba07f0b8c0f53b78b0044eae076ff0dde0b99e.nq.gz
    ├── 1f92e21c50c308491f834e45360170b34c3d14c0.nq.gz
    ├── 20250476e44cebe27eb3e817b08f283dbe1570cf.nq.gz
    ├── 2059c77a417f9f4eaa54f9d1f73943836646d328.nq.gz
    ├── 21cab4d6d8a6437766f395e90079ce6ecd9e4f26.nq.gz
    ├── 22323ea9cdeca980e16986423b16fbef6eb6bf01.nq.gz
    ├── 2281166ddf33fae3e318557645baac163cd25ee8.nq.gz
    ├── 228b76994b1013633006911a3f88fe75d1a0ba03.nq.gz
    ├── 22a4a657638a5b923b3c262cdbd5880d8b348bd3.nq.gz
    ├── 2304209faf5452ed6dc28428d72a31c4bf192de5.nq.gz
    ├── 2326ee168bceaff82338638820df5d5c1c4a99e6.nq.gz
    ├── 2333e13b4a5d3d4c5c445c9490140c0b29496458.nq.gz
    ├── 24ed24218c66609b6db8a838415c9641257eb831.nq.gz
    ├── 253c6da49b9a3346f3a8e27c6c83282f57efadb3.nq.gz
    ├── 255d09d2508a603fd8eea98152025c6cd8f0a789.nq.gz
    ├── 25fd0be684ba5e8cc40a70cd94a4fbc8ec926524.nq.gz
    ├── 269602b6262d2e33bc219de53290faf896a1944c.nq.gz
    ├── 26ba300926002d797832ab8dae12053ed6fcd4cf.nq.gz
    ├── 27e0306b2f3ac55bc4c6d5d3a413b991ab6df2dc.nq.gz
    ├── 28b97c498360a4998d37e757bbfb7721f0f69d01.nq.gz
    ├── 2901eb4d7d7e310255f142c864ab88c4c8e8dce6.nq.gz
    ├── 2901fbac1eac8dde6a92d7acbb989096dea22c27.nq.gz
    ├── 290234d40949b5c10ccff4926aa808b5972ac0de.nq.gz
    ├── 2a61db8b60d3622a67f8eaad45af14e9a89f436c.nq.gz
    ├── 2bb3bc04de57a3b75cdb5f5f856c40daed0fcdf9.nq.gz
    ├── 2c09acb965f26e89de1d29360efc16904cfd4e39.nq.gz
    ├── 2cc9e19c0f67276d8a054b01a3ef08faed51d3fa.nq.gz
    ├── 2cde65e15268b67b28864f3fd7e6932fb7949802.nq.gz
    ├── 2d3a24151e8b20da37c58551187a8cea3ff12f2c.nq.gz
    ├── 2d822935ad2dcac1dabc868dd3028f8b68261b8a.nq.gz
    ├── 2df7f1c363a13703734c19bafb0eedb2337641de.nq.gz
    ├── 2e37a2778b93597ed7fdff8014f050a92d0f6688.nq.gz
    ├── 2ef75d80e3b4dcb0fe34d8cd4a577626353d7f1b.nq.gz
    ├── 2f0f4359c6f8c092b5eb14a36d72d1d478b98baa.nq.gz
    ├── 307d19e78407391881c0c35d22d3903e3a16d9fe.nq.gz
    ├── 3204a679a3c00a826bb9f2320eaf2020797b1414.nq.gz
    ├── 3232e0c7e18bae869af015941780ef69bd508920.nq.gz
    ├── 32549a74e4828a2f0a21734b1014c05e3b3cf9ce.nq.gz
    ├── 32b7140f0972bee6ef472721090f05f3dccb3ad0.nq.gz
    ├── 32dca9be637d61765d602bd48ae4e374f17a5c71.nq.gz
    ├── 331f723e00a69503c1b9dcc022c52d04a8cab500.nq.gz
    ├── 33391c96f3a4f4d7c4d24e17c5e9c862a5d286ae.nq.gz
    ├── 340101130eb725d8a53e3559541c31dd27a5b248.nq.gz
    ├── 340b9560a5a15b4a18d632074d9dd01e391400eb.nq.gz
    ├── 34d7bf1858cf07e62aa0e31d85d3ad96f083ad63.nq.gz
    ├── 35d296868068e6f129a49e00aa61cea948d6fd84.nq.gz
    ├── 36063fcad8b0f7db12aa47ba1a07adef66a79ab3.nq.gz
    ├── 36bf3df7309bfb667ac6f535d4b472b316ef229f.nq.gz
    ├── 37319753d458c15e11950372c3c9d4fca7799e76.nq.gz
    ├── 3815a360a779206c18c810197c193523c0f8dcab.nq.gz
    ├── 382c384dfef49086b5ff3b2ad218471f08fb1a9b.nq.gz
    ├── 39b09f094ed7e44040f88c747e28b501e3a83b34.nq.gz
    ├── 3a8e57953c5f9804bcb62aa5fb179d0564afe081.nq.gz
    ├── 3ac75661c29b6799a839eac31a48daa445f2e2f2.nq.gz
    ├── 3b9bbf68ee5e961d7049d0f8f4119ed503dfa154.nq.gz
    ├── 3bb99195c122bade4f7a387d0a112f315d321fd8.nq.gz
    ├── 3bbedb510cd7244707b4ebf090cdf68929243246.nq.gz
    ├── 3c12f15ad8e78db4879d12e48f1aacb042e5a8ab.nq.gz
    ├── 3c6ed9dedab8566fd7f2a300240d216c909dc523.nq.gz
    ├── 3d5f7ed80f92152b879383640d207248db3411a8.nq.gz
    ├── 3dbdfaa6b123a057774dc5c46d86bfe4d4e35b55.nq.gz
    ├── 3dbf110565d27feb9b7a18c0622938ceb881eee5.nq.gz
    ├── 3dd2a20c9b3b9fc4bb71d0bfe1e6deed84a9b246.nq.gz
    ├── 3dda3e75e35b6a9fbd5a2412815a0f05421f2ef4.nq.gz
    ├── 3de7666e95dc130e98edcaaca3c44e6257687c88.nq.gz
    ├── 3dfca2b5869917385a49f875a5b6e88f06cd08a1.nq.gz
    ├── 3eb232373d7a61fefba19e8a151dae19e9393a67.nq.gz
    ├── 3ebc5e0e9b25471b0c30d750646bfeb6d21d6ff0.nq.gz
    ├── 3fe917945dd34929d4b23159443097e60b30d8d7.nq.gz
    ├── 409d52fd8af9820e9a9485f170d8f99133b0254c.nq.gz
    ├── 40c66acd2f72777f1bec29f73cb51409a55407ae.nq.gz
    ├── 40d40246c48487419ea0d21eb369bea60c729496.nq.gz
    ├── 41e0b669a4b1f216eda3607aaa5fb1aa940b0c5d.nq.gz
    ├── 4238bb4501ea90b22374d0a2e6124e08d01c7f74.nq.gz
    ├── 42c3faccc99d93c11b4fe8c3409b8bc14372f071.nq.gz
    ├── 430767777c61b3754e8577d1ac945a6778941c45.nq.gz
    ├── 4327ea1792b81aaeb11812d70dad9550f5c41693.nq.gz
    ├── 434b25b6d644e20a91d3158a7b1b980e196be0b8.nq.gz
    ├── 446f7fd7f801f4e78f0907f0f3ae4f95a262828d.nq.gz
    ├── 449bb434fb76049f519faaad94acca37b4d2685f.nq.gz
    ├── 45a3ef1011b3504d137f8b18845c33b41332e5f8.nq.gz
    ├── 46a6c0dabb056dd8fe30a1cf1bd787573f3add26.nq.gz
    ├── 47448713f8ba22e6225377fc03e77ad10c29871c.nq.gz
    ├── 477966537de4aa654fa839051617e705952c43cb.nq.gz
    ├── 4858352b7eb618e1649b0c74973e936edc0982bd.nq.gz
    ├── 48fba6cc06af4c2a6cbf8bf5d63215efa244a4b5.nq.gz
    ├── 4901770f0b58170fea3e2ecb9bb5fb6746d2be9e.nq.gz
    ├── 491c892980715d67973854bd7be98aac6699e4c0.nq.gz
    ├── 49ac752754e2f4498031fc37853fb6304b6ed674.nq.gz
    ├── 49db9459e96c657649a1696c712093f3c21324aa.nq.gz
    ├── 4a9f780383d425fb551e2635017de9eaac3c2b81.nq.gz
    ├── 4aa7bf8e5fc4705cb7b190cee0de53ac8db89573.nq.gz
    ├── 4ab225343de04a5cdd4f13ffc8f100330b1391a7.nq.gz
    ├── 4aeab6dcd2dd9197d2a74cc8807187af5db82162.nq.gz
    ├── 4bef1ba71c11b5e34f2c3c36311e17620c619d68.nq.gz
    ├── 4cd7c41efc95595533909a8307311f91e9ac5312.nq.gz
    ├── 4d9c4d95139690f0fc7771646da0f4f1cdff9898.nq.gz
    ├── 4de2e38440438d916cf9524640e3f76d4b2f4d41.nq.gz
    ├── 4e3e2ca5fc7e93d32d06e8e1a696925c3eaac60d.nq.gz
    ├── 4e79fdaf5b37ee9be54acff8ca79a396ea28298e.nq.gz
    ├── 513772d89bbeb74520770ea8bda0c5d18fc1aa37.nq.gz
    ├── 51f64313245dcc58f7e87b6e548e9abfda811ed5.nq.gz
    ├── 528d968b562451094ec0e3c1455aa357107e486e.nq.gz
    ├── 52a029720cb3ac420c6755bc208f9cfc6aeb816d.nq.gz
    ├── 52b43f0dff0e62785e216d8736088098f87a9857.nq.gz
    ├── 52d87e3ef6d143c29d2ba640028909a31befffa6.nq.gz
    ├── 534a070e96b433ba903b01d863e9a943e96f53e3.nq.gz
    ├── 5362d4dc9500a1fd94aab1ff5e1c581b29bd06f2.nq.gz
    ├── 54469edf776f3de255d054c317887b1312aa7791.nq.gz
    ├── 55d50ecdacaaf5e05f3754f320a5c0687a7bdb9c.nq.gz
    ├── 56e2e9fdfeb068998479370be27af66bb5cca070.nq.gz
    ├── 56eef6e48b75727ede1d522b595b5ecde3a205a1.nq.gz
    ├── 56f4768395f75bf0e77c0c4980eb203cb9a17cb5.nq.gz
    ├── 57801b471e04a89022415023cc3558913a816bef.nq.gz
    ├── 57b22e28b88b90e4a9bac57e97a5e4982aae8138.nq.gz
    ├── 57ed96508374d1a85ddb06ac272f08cbd070d3d6.nq.gz
    ├── 591853dc983344eef2f66ffb91a8b852a73c76a4.nq.gz
    ├── 595242f91035344aa661ae46a20c17f71a39963e.nq.gz
    ├── 5a31d0adf441674678a94830efac5b82faaf8cc8.nq.gz
    ├── 5a67244bf27056bcb8885536bb3d8b1a81b03d4e.nq.gz
    ├── 5b49c411ecb5db089d1068cba1d9ffc1e32db078.nq.gz
    ├── 5beaf1648b090fc9dd2f650e03c268799606014f.nq.gz
    ├── 5bf84e1219f9c443858a37786f4a946571cc0563.nq.gz
    ├── 5c162800995f13c9254e045eda990829c11b6cb8.nq.gz
    ├── 5d2afcb50196df043ccedfd78f020471a21cf2eb.nq.gz
    ├── 5d91376dcda8e35f03531b5071be72f0567c1a30.nq.gz
    ├── 5ea99627a5572599c836e20b3708ff400cde2bf9.nq.gz
    ├── 5f2b5a6171e6571e0bd653daa1798322818ddcf9.nq.gz
    ├── 6019399d24f2c5211ba463fc9ba83de6e505241d.nq.gz
    ├── 60608b2a4ff32600ba2847b9e2d0331b83ca402a.nq.gz
    ├── 608a1d93940fd72583009e204a796f510b7fe12c.nq.gz
    ├── 6093512a5e34beadd37813c27f880cec61353aaf.nq.gz
    ├── 61ad86731f6e231e8ee8eac46f776603f889575c.nq.gz
    ├── 63491a6036d7ddb05f50aa424cd0d4af0a7454f6.nq.gz
    ├── 64176c03ed4c99631acc5c1577e5f7da3c388e43.nq.gz
    ├── 642c64bbdfa78bcaaff6e8c2541a8b83e9c15c4b.nq.gz
    ├── 64e230764f939c968cbeec8a4dcd27b8572d1df4.nq.gz
    ├── 6508a2edc96862d6164620f70c97ee568d35113f.nq.gz
    ├── 651d39b97e932bd1dbf59918161d3207116844ae.nq.gz
    ├── 663d43eff85e90224551cd89cba473bf136c24e7.nq.gz
    ├── 66665294aeecfd75ee44014decc5c12362d5cb5f.nq.gz
    ├── 66908f3e5bc82487e40f52fa20fdc2c3c5b3d883.nq.gz
    ├── 66e4c32ddefdbd4c5edf023f96c419ca6a245d05.nq.gz
    ├── 67a661b85ac8d1b285d29f15b0a109c8cf15af6e.nq.gz
    └── 68b8d414e3c082734618d0aaa95020f60a256a4c.nq.gz

7 directories, 200 files
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
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

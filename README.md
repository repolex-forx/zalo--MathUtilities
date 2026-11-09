# Repolex Knowledge Graph of zalo/MathUtilities

RDF knowledge graph data for [zalo/MathUtilities](https://github.com/zalo/MathUtilities), parsed by [repolex](https://repolex.ai).

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
rlex download zalo/MathUtilities
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8ab22736525fe1957d0c8bed59792481a9b3a0c1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8ab22736525fe1957d0c8bed59792481a9b3a0c1
│           └── chunk-001.nq.gz
└── blob
    ├── 00f442694455fab6ddf5bed41df166fb460c50de.nq.gz
    ├── 0282a57b50a7ef6ab0a99b275930b0ea488434f9.nq.gz
    ├── 02bc7185b2eb4a09d191d751941f17cec206546c.nq.gz
    ├── 02fcb84af7c5dec4b71077bb31c76b3399b55d28.nq.gz
    ├── 046b6e6f0fbad72d1501bdc1e2190bcda655983d.nq.gz
    ├── 049fff660c5aa9d029f61933f5153017602261bf.nq.gz
    ├── 04a02d8f4b8fc04ef44c1453010cccd5fb501476.nq.gz
    ├── 05aa7fe684e273d040bd34215647b09f48f5bb0d.nq.gz
    ├── 0624b2b7a3c5ad65ebf3b74bc572c9c1003a796a.nq.gz
    ├── 064842a6a5062fabd679cb43dbc66141ca45a5e3.nq.gz
    ├── 06955a87fcb33a6f672208d45eef268b463e4a53.nq.gz
    ├── 07896e430c699c4cc75484bfc97a0c9ec2183bb0.nq.gz
    ├── 080674e957068f3cf95b3976a7d82d7e1931063c.nq.gz
    ├── 094c3d613dc8e6cd4a777c3b1a6734e3faef2833.nq.gz
    ├── 09a768159c18f1be2b189090dd428b4328bcf665.nq.gz
    ├── 09dd149b53c5fe8dec464606d12cc59456eca893.nq.gz
    ├── 0a8a7ab8ed951713b6a0d971434269105bfe1169.nq.gz
    ├── 0b026f6126bf9fb4de81617189b810467a5075b7.nq.gz
    ├── 0b81c4d198a785513e07b89c02aab24a4328b820.nq.gz
    ├── 0b97a5d0f57e17775728a30deebe36ef1396d282.nq.gz
    ├── 0dd3b8ad221e1c5af629412a9cb98769934d65c0.nq.gz
    ├── 0df5943805416d372e9bf62cc62617c2665ff069.nq.gz
    ├── 0e031604f6724a8388ae58a05965dcd9523f2236.nq.gz
    ├── 0efd6df88d26b8380a4b298d32492275abd8bcd5.nq.gz
    ├── 0f151821ba243284f5eb6971bb34972262aa5129.nq.gz
    ├── 0f6e958c0f0052b66b28d3a352c0501730cd9ba0.nq.gz
    ├── 0fc2a3f5dccd67ef8962330138544b3c27cbd80e.nq.gz
    ├── 0ff6ae9773c3499a07fa0c10818d0e4bac6c863a.nq.gz
    ├── 100a82366c40fe820abc59609d1d4bd9e2d6619f.nq.gz
    ├── 10551e06b90b11c928bef4ffcb5d86ba5e0f2ed5.nq.gz
    ├── 106efb8f445b3de998f9a8f7ddf10bf6ebaf4a35.nq.gz
    ├── 117bfc3784b2749e922f79670275f385568e0374.nq.gz
    ├── 120bc27465aac32e747bd8ab2793a35cd6b8d8f8.nq.gz
    ├── 12e3fa48598cdb3d05b67a01914b24dc115f1044.nq.gz
    ├── 1333a454a4102b0bccb05b507b996ccc045ea551.nq.gz
    ├── 13df69f4f17feceee05eb19da40a195188a3dc65.nq.gz
    ├── 146fa96b7d534d82e97f6c0dececefd37006d4a4.nq.gz
    ├── 1484c8d1251d62272932f330f464f5fe95d92b80.nq.gz
    ├── 14ae677d6ccacdb30c24cfb4864d8bc918f171b1.nq.gz
    ├── 14b9629265761d2561ed7217fc635171a6a86325.nq.gz
    ├── 15d83e132709669d821d8f0bd2a0399e0b7ae3be.nq.gz
    ├── 16a22374b7fd32031784f9676cafc21bfcc62fb0.nq.gz
    ├── 16e8b5904563e05a7650bface0cbce07de2c3177.nq.gz
    ├── 16f6441fe4ef4b45ff26c6cba465ad1049d529eb.nq.gz
    ├── 1737b08483bf7b8ba601e59e438ecee2d7bc16cb.nq.gz
    ├── 173bdf53e5cf20913514a7fe33bbc282c26e21d2.nq.gz
    ├── 17915a7db393f19bd8438f20c9f18e75cc93809a.nq.gz
    ├── 17c8f538e2152c0a0310b4870979eeecece2153c.nq.gz
    ├── 17d8c329ef23aabbb91f13b50897a65a3180e315.nq.gz
    ├── 1866fd3ca460d438ae6ea411ebe51a6d764e5d7f.nq.gz
    ├── 1a4d57d206259ff6470f9bf73b20917fbeb079e4.nq.gz
    ├── 1a7eb96bfb6173832b3ffea139224c4693c1bebe.nq.gz
    ├── 1ad44d36e2f6b9dc4aa2159f8e2a15720f5a23b4.nq.gz
    ├── 1b15532b44c974875d34aa481626e90779ffc5f2.nq.gz
    ├── 1b4ee14ee82563e27777dfc809594b583ec6eef8.nq.gz
    ├── 1b99ce3876294382bd5cb0858c89c290755efdc8.nq.gz
    ├── 1c9196da450dbe2c299bc226d4d5ad96a25fabde.nq.gz
    ├── 1c9c1ae8d65a34137b1857c91e4667eef8a11513.nq.gz
    ├── 1cc5485b8aa3ea3d0107f5559d690f1a225e5902.nq.gz
    ├── 1ddd9873c84b37d970131f329adc6856d23d36b9.nq.gz
    ├── 1e3b6963d6df59dfd34526dd204f6de8ec2ffab4.nq.gz
    ├── 1e424ca9ff3cde2446298edad4b41b8d1c6236a5.nq.gz
    ├── 1e4e9f153e1644b3833f048f47917e536dab820a.nq.gz
    ├── 1ebfe9a037aa0ba2691ad7e39cc1cff2c38ebea2.nq.gz
    ├── 1fdaf9686a5c35180d32ea2380d86957279c335b.nq.gz
    ├── 20450e24fbc10e501b9245d84519b8df80fc557b.nq.gz
    ├── 20cc33a19d34f9f8fbae3f296af4e208d04ec8cc.nq.gz
    ├── 20dcaef8e081383cdc2fae28295fc6af55b59c9c.nq.gz
    ├── 20f0b7f38f2e43a24ba7547bf8414e3ba6d05d13.nq.gz
    ├── 21509a59d96d955ec3bcc5a9f7d5a4ace1b01011.nq.gz
    ├── 21733a718d56b38ea3be14479c9d0269a263ce38.nq.gz
    ├── 217f51846a5aad7580ae6c86624a92a04d731e0f.nq.gz
    ├── 2195c86fb123d8b7841a3bc9aa66f9ec40390d6e.nq.gz
    ├── 2212d6202248601cd0932962dc62e81e922f033c.nq.gz
    ├── 22cf1cd6f9fe39a22b8772c7c8fc6fcd9669a319.nq.gz
    ├── 231d4f6204f5a230246d8f180ddce634ed4d0602.nq.gz
    ├── 26ee10deaf462f66c4cb659e49772f6405c5b484.nq.gz
    ├── 286ccd375c04476562cc1fba67fa3f6401e7f361.nq.gz
    ├── 29278287e81475a7e41dc7247d300f987c2aa6ff.nq.gz
    ├── 2a32ed9d6568d917627ea67dd5e7751d4012e87e.nq.gz
    ├── 2a6133e7859a1930c31bc202131e06be0a06f1e1.nq.gz
    ├── 2b38cfa9c7063cbd324d8a86642a22f38854a2d9.nq.gz
    ├── 2b4a54304a22f291777fb77014fba656885f75c9.nq.gz
    ├── 2b7d508cf234fdb25032c8291c47083b728b44d9.nq.gz
    ├── 2b964bfadc330c23b8decfaa671ff214b3744faf.nq.gz
    ├── 2bf7768752e21aa2f7a71d8bbeca46cca0696bd3.nq.gz
    ├── 2c7e4fb3d5e93997d5260e2c6dbd96141017eeea.nq.gz
    ├── 2efd325d0cce735d8452296fc0e2f7bd20fcedef.nq.gz
    ├── 2f79a0877635f348733c78753b678299d2912720.nq.gz
    ├── 30934da64d3e21fd28d9028aa95d9b1581301aba.nq.gz
    ├── 316d63dbb670351bcee29b27efe9e57de0d131d2.nq.gz
    ├── 319987f441e66f91862ebb5750d213b8a91e6fde.nq.gz
    ├── 31ad4e2e58cbecf025bf814baf222524b9a59a1f.nq.gz
    ├── 31e74f213e40c625f9fd94dfc8144820d15c2a0e.nq.gz
    ├── 3243be921b8531eb739ac7fe31da3bef10aea72d.nq.gz
    ├── 32cbe17ce196097e38f40ccd2b353cc290bb8308.nq.gz
    ├── 32f350686572e5775204375a4dd2ed59e1d8d61c.nq.gz
    ├── 337ad46c1ff21ad8cc4b37fbce3ea6151ede69a4.nq.gz
    ├── 33c6a3e4707ddf3e4e69968f4f8b6d121469d35e.nq.gz
    ├── 34032694a1cfee2ffad1ec9376525efde3567941.nq.gz
    ├── 3407f32c11cb43a6c119079432288b1021ed0084.nq.gz
    ├── 3457461730b35bbf841b84240fb05e97a505b44f.nq.gz
    ├── 3514b9e33894f9868883245f4cef453590f7f594.nq.gz
    ├── 3538c36ef4e71f5a05530f14d3997211148f6d83.nq.gz
    ├── 377b6cab1126ed8988e8ca5b6fa28e7038bd2829.nq.gz
    ├── 38730c40dad5adeb3aeff79404b724a934bb3a48.nq.gz
    ├── 39cb9c661b63edeb3f75e252251ff288c840b968.nq.gz
    ├── 39cd6d2a8867e503e07515994bc2f640883df5a9.nq.gz
    ├── 3ab44999f59b0f586d576b75928216b77e065e00.nq.gz
    ├── 3b66e9c03c02ef66789deeca5366705e8ae057ad.nq.gz
    ├── 3b86117e0b725fe84d67879750af5800b57c17e6.nq.gz
    ├── 3ba7fcc561376035d3d3e4af3599364cc3ea0d6f.nq.gz
    ├── 3bae70524973ad6270e0f963713ad2ba11ff28ae.nq.gz
    ├── 3c792437689b8c04108f4723fad01329db2ad23d.nq.gz
    ├── 3d89c827771532083c6b62f0a8dcb8bb2b78d1fc.nq.gz
    ├── 3dc6d96a2c7ecd0f43199e01b94ec0da760e376a.nq.gz
    ├── 4019bbf1935d270ba59d2c4cd6a6cdfa9858fb0c.nq.gz
    ├── 40a32f476adc0a2417bed57f2ad2d91583061c2e.nq.gz
    ├── 40ee7b76d7de729214f74c9a808e2321db95cc0c.nq.gz
    ├── 413c1380301b366ef1afedd1b18c36269a0c07c9.nq.gz
    ├── 41f662ebfaffc97c1dd980c3fa9fe1ea080df90e.nq.gz
    ├── 42c7abf5ea8ef70c3e8f4b3876982ca0aa325ce8.nq.gz
    ├── 432618231d14e0fbc7a85824de2de4fce7f96cc6.nq.gz
    ├── 43476ab30a6fe3d40df833fd3433e30533f594b8.nq.gz
    ├── 446ed7406b539acbf3dd6d88521474821931fa7a.nq.gz
    ├── 44a07fd0769550214a9932b9dffd5217aa5ae381.nq.gz
    ├── 44c8b12ad51a7741d6036e00305272c3ef7a05e7.nq.gz
    ├── 44f1d407bc488b1423eb4dad3f63ea6ae0da00d5.nq.gz
    ├── 451cbf7be477835504935e3cdcef2ad93aa9391f.nq.gz
    ├── 4521076ee84e69212b0133a9377ffb03699bb225.nq.gz
    ├── 454e2b5bf48152f41c19307dd2f84f59e8ed3a57.nq.gz
    ├── 458dfa4da68432c81580d1b21aa2ef30f46cbf9f.nq.gz
    ├── 45bd2c5e62c1308673a4b1d5372deedace510e71.nq.gz
    ├── 46639431b833e6cb17344e4edf798730e5f52532.nq.gz
    ├── 471f931f318563ac043b85611249c7d18298d6cc.nq.gz
    ├── 47dad849cee8c63ee655f97ba34aecbb1524bc2b.nq.gz
    ├── 480468c22ade6f157201c038e5ba82ea2d7c737c.nq.gz
    ├── 487e933f8ed6f39edf7117f952c2a0e0c27a8e24.nq.gz
    ├── 498461f27e58310c6a32656a0015da417eac324e.nq.gz
    ├── 49baec9017398427ebd74655e9d62f9bfc1b863e.nq.gz
    ├── 49f2e5fe3a5ed35e9c1cbe9d446b8ae64b6f0488.nq.gz
    ├── 4b530d10337f816abe80f806ba7961b542e95558.nq.gz
    ├── 4cf888905e1ea90df3748dd378ad589a7cab50f7.nq.gz
    ├── 4d0ef6167cb103940002a8859ed30e0b7a456805.nq.gz
    ├── 4df1668bcb910092d12efda73db4d7fff1b66e9c.nq.gz
    ├── 4dfcc578ec3bca27f7a1467c5a475501eac05a59.nq.gz
    ├── 4e0710b1e6ab753b1d328c340fc4e4f1ce8bdb3f.nq.gz
    ├── 4e335354d060f1230b8f515d2f6f0bccd271c412.nq.gz
    ├── 4ec184e5fd58d0312a41b7dd4aafda65930a39b5.nq.gz
    ├── 4ee15af6edb44b2459bacbe8ee2a396e5c8d3497.nq.gz
    ├── 4eea356702a8a865ea973ce2f24bbf8b91e9c490.nq.gz
    ├── 502f18b0c6fc7fcb1c40bd3abbf6a416f1afece3.nq.gz
    ├── 50b130f7ef029019655fc5c7a8df86d1bd8e5788.nq.gz
    ├── 51028306c9a9e81fc8cc3f9c6bba79c8fa3ac953.nq.gz
    ├── 513560f36465878841ef876a4e663fea1dc205d8.nq.gz
    ├── 528fdf2e8b1ff5b390d6898861bd3a942db9eab7.nq.gz
    ├── 52d7c67a9411d41f8bf2b3f05db8ec40814af851.nq.gz
    ├── 532f4109185bedc5be49a2c8c621095d70dc6155.nq.gz
    ├── 5354d6aba40a5afd9e81392dff417ab5a643be2c.nq.gz
    ├── 5380430de164e8619b72f086098345e6f4619f6e.nq.gz
    ├── 53a507d0d3e2eb75a1aad3f9b182304fd57f8663.nq.gz
    ├── 53e8e5e7bc67d6ef34e85c8a35a59d0ddf9dcd1e.nq.gz
    ├── 552e92c33ff52651c7cce4fbd20364e0746fd0b8.nq.gz
    ├── 5543a326c1e243b0ec89cc69b419f4b0069c095e.nq.gz
    ├── 5662dd88cda74a0b1063a39d8c1d5aebb4f06ec9.nq.gz
    ├── 569ad02898e41d5f51a049088b3def6b6cd6fead.nq.gz
    ├── 57da298c3eea4c2a5b4de6bdf1e700bdb733404b.nq.gz
    ├── 57ec23303734dac2aa34a540649dd95293ba292d.nq.gz
    ├── 57fa9f00da85d9e0704fcc13334cd45f6c538bb1.nq.gz
    ├── 5907ff2e50e63f499fb7b9101d9a058581bccca5.nq.gz
    ├── 5956c6c644c9f19f4adc74c3ff127571b94bab1d.nq.gz
    ├── 597e77748534ab02e0c881ef204e0819637f191b.nq.gz
    ├── 59a3eb4f19e9136f2f3816ed8e93959f6252b226.nq.gz
    ├── 59b75fd44de8b69f168262f731727e2a697fdc05.nq.gz
    ├── 5a6ad266aa3f8fddaf277447432609acf53dd231.nq.gz
    ├── 5a6d16ff6ba80f47e9eccb47927ee9a8df154aef.nq.gz
    ├── 5ac824105ae06231348a96fdc0ad297e7ce24ed3.nq.gz
    ├── 5b5facecace9276319b6e497953ab0429de65b61.nq.gz
    ├── 5bb019f41fb86c03ac0cf795f7e60e8470d36e59.nq.gz
    ├── 5bb07af7540e07eac769db486e589edde0e3812c.nq.gz
    ├── 5bfd21bb24c3a64d6840befd4c49f65652443d6e.nq.gz
    ├── 5c2145919bc43525d929c2e2ecabe07497df366e.nq.gz
    ├── 5d1a0f98bfa45356c160e66cf81801ef6ea9f1fb.nq.gz
    ├── 5dd2f8ddfb68275a8c5691851609cab1c959c17c.nq.gz
    ├── 5efd9087a2198c15803aa1dc4774804b9d04e8b6.nq.gz
    ├── 5f30395a7c20ab139987a2c17a7755f2ed248565.nq.gz
    ├── 5f993102a91e54f7f814afd2c80b191222dfa113.nq.gz
    ├── 5feed89f7dcf0689ccab3a1fd74a1ed11d1ee254.nq.gz
    ├── 614809f67b6fd1fa2b55d45007b614a0d8a4fca7.nq.gz
    ├── 617113b92b0bb18e8c77077411aef37f59b2bc86.nq.gz
    ├── 62fa4960da22870c6efb2dd02a342fcb5fa3eb8d.nq.gz
    ├── 636a595b32ba897972008f0cfacbdf52bf06225e.nq.gz
    ├── 645579625b6bd1907fc464903399c33ed13ab5c4.nq.gz
    ├── 64c14dedd8d47516953b16f1a8946f6d64c4a5de.nq.gz
    ├── 64ee6ed4a6da7235dac838f325b2201f0c668e6c.nq.gz
    ├── 654a873c4c60df294fd3e5848026185de04ad26e.nq.gz
    ├── 656c6c03ddb1c56e38141213e71a0b32a4674c4b.nq.gz
    └── 6585fc9a5fd76c0e7a3135ba1482299dab98cca5.nq.gz

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

[zalo/MathUtilities](https://github.com/zalo/MathUtilities)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*

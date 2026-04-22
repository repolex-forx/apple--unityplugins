# Repolex Knowledge Graph of apple/unityplugins

RDF knowledge graph data for [apple/unityplugins](https://github.com/apple/unityplugins), parsed by [repolex](https://repolex.ai).

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
lexq download apple/unityplugins
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ea505d09b8e7791ac3e591de4294ace96f893520
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ea505d09b8e7791ac3e591de4294ace96f893520.nq.gz
│   └── repolex
│       └── ea505d09b8e7791ac3e591de4294ace96f893520
│           └── chunk-001.nq.gz
└── blob
    ├── 001782831b62fa4c3d567b1b1315ac04f702d008.nq.gz
    ├── 00293d4b8f2a92333539248c29b787bfdc1c2c96.nq.gz
    ├── 0029a1a51bdbd0a74dd2c071890ac997fa5572f4.nq.gz
    ├── 0037b3bb447961d5592c1c7fa77f9017e264f5d4.nq.gz
    ├── 00c23bc44880c74e474e78f272af6f0d545d7c6a.nq.gz
    ├── 00e1a36fda5df1de8cada292bad4e3b7829075c9.nq.gz
    ├── 010f51bcba516370e7a6d5e36ca4ee73b3539cd0.nq.gz
    ├── 013e4a431a9ebca4efebf19fc9b54ea85e8e51fb.nq.gz
    ├── 0147c8e713409758cb7007dee226e8858fcaf22c.nq.gz
    ├── 015be58fca9a768d8352b88e1f15d7bbab4a57ae.nq.gz
    ├── 018127b8c8478c26b20824dc94e0d2c74ae9a5c7.nq.gz
    ├── 01c3d9f3d1de507bfd478b21b192dc752f03275b.nq.gz
    ├── 01c9da35f647efdeb2143a81af8a8718426750f3.nq.gz
    ├── 01ff58c8410eda429155fefd85c6951787c14e40.nq.gz
    ├── 02613424fe13c82205706a69201e5e886f8113d5.nq.gz
    ├── 0272cbd7a5c994c744b24b1e7696a8cd3791bf51.nq.gz
    ├── 027978cb1bfdaeb782016b0f2a922f9e13b052b1.nq.gz
    ├── 028d29866b82fda0d68a1a6a167936535e0ad05d.nq.gz
    ├── 0296708cfc4f66f98383cab383e715cccaec6259.nq.gz
    ├── 029a045c8e4b7c94d7535e9bfc731d3efcc5fa52.nq.gz
    ├── 02b5c56f738c1eaec9fc032c7802639d5e19e1ce.nq.gz
    ├── 02e9f87a37f4f785a7a9c08343645e5923aa78a2.nq.gz
    ├── 0347be24869e947083775c61d6b94e1ad7919347.nq.gz
    ├── 038ce2c734d3514f70d37c2fc481ce461c01d416.nq.gz
    ├── 03acc115791908d668a110f089ca742312d98d8b.nq.gz
    ├── 03c5c00b2f49a9ce762b3f59c66603797e0d0c95.nq.gz
    ├── 042291803dfbf9cca21717f1d0589d7804e2eb0c.nq.gz
    ├── 049a3d7b45523e9e7159f194eaa85f4a040b9ee0.nq.gz
    ├── 04aed2be8a7db6f8c8ca10cc9bdf2400cc68fca1.nq.gz
    ├── 04cfe72d4643da5c0ea34532f68f295638584ebc.nq.gz
    ├── 05231b75afded8b4f5b05d3f7c2419eb276fd595.nq.gz
    ├── 054a246f955b5d7a15b02ac29224e238b0df8011.nq.gz
    ├── 05544b02e2d09e075af45cb400b413538251aeb8.nq.gz
    ├── 05688fc2df97cf7fbc7c802315ea00662a4328f5.nq.gz
    ├── 056c8e9598acfc67f44e0d7f4045931fae83fc31.nq.gz
    ├── 057198bc6ad2f53816ffa9c9b4c2fae2026903c4.nq.gz
    ├── 057e7c5802b4cb8a1d356b064392fab80f714df8.nq.gz
    ├── 05a23d3437cacfebe0809be7874b12cfd4372a7b.nq.gz
    ├── 05b2757db08160ba97825ecf54554ffe19121896.nq.gz
    ├── 05b8c3c2015034560e7139d23d401055f7228147.nq.gz
    ├── 05c31275b5c8e603d7054dd69f325e1960ac0ef9.nq.gz
    ├── 05d20e41070572b27c153171428e6945fd565e2d.nq.gz
    ├── 05d8ae1a7edf661ca88c48a5a1952223e4f088e8.nq.gz
    ├── 062129d59c62b61f0af1f790daaf9a09be070d97.nq.gz
    ├── 06249c6b0239800ab4c36aceff7cdfd7c2e921c9.nq.gz
    ├── 0678ec0f7f9faeef7c4fae2ea4023109b63e1ee2.nq.gz
    ├── 06ba511f600b25fd1d4752c56ee911165cb22403.nq.gz
    ├── 070b21fa49e8683c1a10567e0f8f6955139af622.nq.gz
    ├── 070b9b897dc789933e231aaae0cce90a9096684a.nq.gz
    ├── 071ef69849e5a10b877e2c6c4a2bbe2757132a89.nq.gz
    ├── 0781a52faf901fd615b4fbcbcbd9e593c87f5ee3.nq.gz
    ├── 07c9508b4ffbe42131024f5f2c904b4e7b9f7ea6.nq.gz
    ├── 0851e0a5e3bfb427a6b4c1d269fd434c89adf297.nq.gz
    ├── 08545420c951e2744e92bd160c8f5bb9735956f2.nq.gz
    ├── 085a0a5912accf109abfb534e897f495549cd93d.nq.gz
    ├── 08976f0220a0ebcd473387772e45e90a21aa5f20.nq.gz
    ├── 08d7cdd5eef9d68d745fa73e30d65809152af6a6.nq.gz
    ├── 08de0be8d3c8c1786ebe04545dd772526853eef4.nq.gz
    ├── 08e1c03c5f7514a09bf93414496ebc29cf4b1fd3.nq.gz
    ├── 09166ed56c5b968cf07d83e3cf40c675f1eece0f.nq.gz
    ├── 0929fe3e5a37e4737b32cca6242357c7ce3e1858.nq.gz
    ├── 092c51faccc0a484c404a7b20d190ec0842b74f1.nq.gz
    ├── 0944c8e731e9b05093d0ec115f3e25509fb9920f.nq.gz
    ├── 097fc114197fcfd9c2cf444d78ad008e1ca1749f.nq.gz
    ├── 098163ad296ab07ced653285a7c7abe1e0bc3b34.nq.gz
    ├── 09bb5659036c2d8b067e855892fa6c2ebe167160.nq.gz
    ├── 09d5c2e9785c678573212cc3a6c9cf963da68cab.nq.gz
    ├── 09fc30e8f195bf944080146feb4d0c1350f811e6.nq.gz
    ├── 0a0a36a1981ecf2af54dde383d70c32dcb195420.nq.gz
    ├── 0a127c185cdab7f7e0ab1e94a59ff8eb19497b9c.nq.gz
    ├── 0a187a3d77a6f2bc6379577bcca75294ee970f81.nq.gz
    ├── 0a55f9cef25239bce3aa36769bbc5f978c995036.nq.gz
    ├── 0a9764033dd42bf966060ce7a1e325d33f5c04e4.nq.gz
    ├── 0ad337d5e7abba029cbb7e9c3250cf3e8fe644d5.nq.gz
    ├── 0ae62a85b68835ca94999725ce1604527c33635f.nq.gz
    ├── 0bf4ba1a56bc6b51358222cbfa137a2fb8c74951.nq.gz
    ├── 0c6065a3ea2a35fe2bce61f53907995ef8168e50.nq.gz
    ├── 0cdc0892ab43570f43dd5fcf483bb75f1006a1e5.nq.gz
    ├── 0d1a0127a687c92f7fc8c443c00a0889672d803d.nq.gz
    ├── 0d30e653271a4c68810ee1bc30264b289c532912.nq.gz
    ├── 0d404b43b59dd023948fc13044dfe20fd98c44ca.nq.gz
    ├── 0d9160806e1a7a599ce46b22a165d76486b5b28f.nq.gz
    ├── 0d9fa5c4c30636a9c94f10d180f1280cc8a92ae5.nq.gz
    ├── 0db1b8ba5d8802648a2dba9155fea87d6ddad027.nq.gz
    ├── 0dbc3fa1f978c9eb3229a54090b99d18bc54e3c4.nq.gz
    ├── 0ddfe1fda1f43ad7559c30780401a3e2a398dc51.nq.gz
    ├── 0de5a4cd95b6cdf1d3c7aff94f58de79c99cb234.nq.gz
    ├── 0e905e7dfe1f7cf20044ff47d44a1a50afd84e18.nq.gz
    ├── 0e9cb1022129dd694dfe1ad595c1ecff833543e4.nq.gz
    ├── 0eec62b0c3d2adc9a2abba4592756ff1563c3145.nq.gz
    ├── 0efc4d09c9fb743db8c3daf4e81a8e6722a550d4.nq.gz
    ├── 0f05cf1a15cd0ae62080d53a5bb7889a1dd51d61.nq.gz
    ├── 0f3b5d4f66ee01de3bcf0d581811d5960f9f5437.nq.gz
    ├── 0f4cc21fe35ecc75627229969294e680d124e030.nq.gz
    ├── 0f7b114339786bcdc10e3893c70aa4c7af30cb9e.nq.gz
    ├── 0f86776c890f4e8a0a0af2e7e18d3402096e32c1.nq.gz
    ├── 0ffe424c6a5dcde4028ab28f3dcd0d6bbf2a9bde.nq.gz
    ├── 1021f34a722224d93b04ab5dbd677fffec2d61a8.nq.gz
    ├── 1098a5286294ab251f0420deb57af0432dcb9e3a.nq.gz
    ├── 10c4be3a7ed77638d6050b3b3076046825f5e65c.nq.gz
    ├── 10c7c08d54f377053a912a0ab6bdcc89e50ecde8.nq.gz
    ├── 10eec65d6e247cb817dba7a7aaeeddebd95409dd.nq.gz
    ├── 10fb964bdf418b8225caac63cc41fafafccacbdf.nq.gz
    ├── 110a5c2421d9caacd27d53557b339d3d85fce7fb.nq.gz
    ├── 1120674a72502ea05be9a62c4490c00379c129c5.nq.gz
    ├── 1179756065f7c971bff4c52627de5b31e30de9ba.nq.gz
    ├── 117c021c15a6b6aeba637206384368cff9f95bcb.nq.gz
    ├── 11affca027ccec6c4cebf90e4467b9bef73a04eb.nq.gz
    ├── 11d9143f5eaf2bd690aee27322fce5b13b7dd541.nq.gz
    ├── 11daec42f455a3dbfbe955864ab4857f2bbf0581.nq.gz
    ├── 11f65e0aaf77bdbe8aa3f5d77b171192176b1c2a.nq.gz
    ├── 128e94430c60308d8ffc7865da4960b71080e5eb.nq.gz
    ├── 12a68dbc4bf09270c88b2778e33abefe903f07e9.nq.gz
    ├── 12b69bf09b3d4268c490e98c311a8027458b63b6.nq.gz
    ├── 12b761582d740ac03ba94acaa64b70565ffd0337.nq.gz
    ├── 12b8fb4b1390836625a2c50bd64ea85dc219825d.nq.gz
    ├── 12dc31fbd5fbc2d167c0fb013a7e7e5133a1b694.nq.gz
    ├── 12e750080020bd0d4640c2308ea0bfb3115d167f.nq.gz
    ├── 12f94d84a96beef5897a06a8f4edc220d9d95dd1.nq.gz
    ├── 130c01c1c73a8b90ecd6ef10661c6311ee6335b9.nq.gz
    ├── 132cca0290386f0954ba78b0dabbf875580fce80.nq.gz
    ├── 1338b470e7733ffdc8ed4d4ed25ceedfa11006c6.nq.gz
    ├── 13923abe0fbf8544c061222b805ff7733fddf45c.nq.gz
    ├── 13fb14f9456302d2c4c5868ae4d0e76754051d22.nq.gz
    ├── 1407cfb7d11bf5e942fca78f57a2362a7cd2411d.nq.gz
    ├── 1419f5720cffd4f41e3221172892b4de18562894.nq.gz
    ├── 1426c1a0613ae25596399ae47985e718c6ab3efb.nq.gz
    ├── 142b9bab7e643bbb1b2df1207724a5d4ed98e9de.nq.gz
    ├── 1480159e9a377752619316115420a1498dfa660d.nq.gz
    ├── 14b25d8fb38f108c428c5a0078d5e9f45dc3a71e.nq.gz
    ├── 15152faa0edaec357ee9afb959d786b8473dc887.nq.gz
    ├── 1517958a3a02f1133e95b68283e85ff496751544.nq.gz
    ├── 1517a122cc054e71d780a1a6342d4ec550c502ae.nq.gz
    ├── 152c17771907e0d61eba92b6a86361d23a0abd89.nq.gz
    ├── 153715153dd07d8c2b9145e901f103b53fa5477f.nq.gz
    ├── 156543b494e14d0b2239f9212e1431d0caa9c759.nq.gz
    ├── 157471cd0f53390b3ffb76d4e0d8ad3a5e499105.nq.gz
    ├── 159f29d9659d50a4b9fa1b920e4da5f04ceae072.nq.gz
    ├── 15cc3ef19d8ea92bb5a2e5249944ce9b8bfc13b7.nq.gz
    ├── 15d60908e406473175b284d06d90ff55abf12e5c.nq.gz
    ├── 15e85065c9a28ae13b009b8a9a94a1baf714627a.nq.gz
    ├── 15f6990889d43a29c1714834a68eb066af0f341a.nq.gz
    ├── 15fdf7a749fbb4effc0d64156f55584e12f2519c.nq.gz
    ├── 161aa93d9b498ea8de803228ecc42cf6711e54a2.nq.gz
    ├── 16322dc88873d404a326ebaf27e27dc58353ac92.nq.gz
    ├── 163ededfa4fa82a45a3ab8f0554fd38e34ee9cc0.nq.gz
    ├── 167a8dcf6137b9b5f93b8469070151c7e2966bae.nq.gz
    ├── 167d6502bf481898f7b55000cec6ffa433698a8d.nq.gz
    ├── 16ab79fa8e086009878dae511d7ca2ffb3965e4e.nq.gz
    ├── 16c800d5cdcaed4827e6f7fc24fe3acd1f3c0ee1.nq.gz
    ├── 16e8b0cda75cbb33526e5a181b5410e8f8aa4089.nq.gz
    ├── 16f258c5b77d98b14a17e4397a666e04ff31158d.nq.gz
    ├── 17232cf4ff646af3b8526e3f9f7787987edec366.nq.gz
    ├── 173d7b5d7c19d05ce39a45d88d8711103f363a0e.nq.gz
    ├── 17505746c04469364b7defbb2880d2e2c20e88a6.nq.gz
    ├── 178cab25312698f1b147538403c338bb73830fda.nq.gz
    ├── 17c8f538e2152c0a0310b4870979eeecece2153c.nq.gz
    ├── 17d0334b9e5c48b7a27e9ce51b38aa0f06c875cd.nq.gz
    ├── 1808240e8aa6b8938fc15fed80c0561d7ce4c6ea.nq.gz
    ├── 180b55be0193800dc9ba96a62f3c67a0bd4fbb09.nq.gz
    ├── 180e1932c0532053931d797b433ac36e7a26fe2e.nq.gz
    ├── 1818f148f44680a9042e380f074a242217101b83.nq.gz
    ├── 184a1ea86bb03b22d0d21d1a7f0e61a918f370f8.nq.gz
    ├── 1853f9c6099822afbf054600aae1d27fa2a95f30.nq.gz
    ├── 185566cb5f5129fb8818c35be62214e065efd266.nq.gz
    ├── 189b8701af876ecfa4ee9c47ed1cd2f140044106.nq.gz
    ├── 189eabc203d390f1f2fcdfb0580d5503bc74582f.nq.gz
    ├── 18c372b3549def0a17ae7563254d0fe164b9ce49.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 192ba3b6bcafa74e5572d8ba60260ea60ec57358.nq.gz
    ├── 19321f319c64e7dba4024307250a5d5f5cdf80ea.nq.gz
    ├── 1a12cb91b67132fda366ae04ba2662092ed8781d.nq.gz
    ├── 1a2db33e945fc048e8c4414966d84e793c96601b.nq.gz
    ├── 1a3e404aca7aad6971e50667da110d4fa5d7cc91.nq.gz
    ├── 1a9c08094b95f54da1cbae0d5df9c2d2f8f2d2d3.nq.gz
    ├── 1aa672db56141d429426c8b716501eb066762ab4.nq.gz
    ├── 1ab3863e3d3bbd9709236e9bad2eb3d084f15b84.nq.gz
    ├── 1ac0174666e16fde7208ac36cda28e643cf37306.nq.gz
    ├── 1af52880c7beecb91d35667626b9ad8473963afe.nq.gz
    ├── 1b1c2322a4d4d65b1c9ab9615b9361439bffa5b8.nq.gz
    ├── 1b23c12e47f04ce1412cf590fcec88c5efa0a70f.nq.gz
    ├── 1b3b38e18f9a55c5e42f1d8dbda96c348c0fdbf0.nq.gz
    ├── 1b864b18dc6c5a4c91b2dcf3447d65a169db0730.nq.gz
    ├── 1ba99c68564d473e7d4566f8087ace5dd2a27404.nq.gz
    ├── 1c1307308f9b3fb8503370fc2fc7f4e2314144e8.nq.gz
    ├── 1c291f4d7c98d5fa62bb7edb31b5f2364dc3d37d.nq.gz
    ├── 1c4a2b5eaca2817f47970dd33582332b7636bd73.nq.gz
    ├── 1c4a2d278fc6b0129d6fb31db71d6e566f357c13.nq.gz
    ├── 1c5ba7389d168f663293a8b23ebf60d53b0a990f.nq.gz
    ├── 1c92a7840ec11895c76785f65d949a3d20d53355.nq.gz
    ├── 1cb7aab42349b61cec0f325a0a8b848284274d8e.nq.gz
    ├── 1cc8cfe4a2d40c235316e7f9b922b7d83863920c.nq.gz
    ├── 1d017f72d295686886378adc8aba0fe4fb760c66.nq.gz
    ├── 1d076bcb7234943d83a1a79d1b0cd4c6c35dc1b3.nq.gz
    ├── 1d2d2c78c2b00fd97300b87c0c7e3f72596874f9.nq.gz
    ├── 1d3fb0c88a4533bf5dab4b4acaadbe64f1da799d.nq.gz
    └── 1d8ead33f2438c455da8deb80bcb0241e9f93ecb.nq.gz

8 directories, 200 files
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

[apple/unityplugins](https://github.com/apple/unityplugins)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*

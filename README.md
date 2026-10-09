# Repolex Knowledge Graph of NousResearch/huskyholdem-bench

RDF knowledge graph data for [NousResearch/huskyholdem-bench](https://github.com/NousResearch/huskyholdem-bench), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/huskyholdem-bench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eb149674a41e94459e00630aeb0d3c18e86c0613
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eb149674a41e94459e00630aeb0d3c18e86c0613
│           └── chunk-001.nq.gz
└── blob
    ├── 0082d7b2dd69526ea72d6688e305eea10cc47385.nq.gz
    ├── 00ae3fae44bd66893af71e807fe12ceba09b0418.nq.gz
    ├── 00afe73182b8bbb307ceb38410f02579839bc15d.nq.gz
    ├── 012f95e97b82fb058ef6660a3784c5bde4cd10df.nq.gz
    ├── 015bb4c28407900fe3c861a96dcfb0f29fd3dc92.nq.gz
    ├── 0172101cd1aa66b13c0ac063cd8115b02dfeee07.nq.gz
    ├── 01c91736de7f68603193bd6f83d815afd296a305.nq.gz
    ├── 02779534316f276f4e35704e1a9afd0606804cc4.nq.gz
    ├── 028f25fe93477349f7d8f4c09a30df47d6db5011.nq.gz
    ├── 02d4f20612f71ee6b901a92e20eb2e8e17e1004e.nq.gz
    ├── 02e082ba2b67913a39875cdb6d8da3927c19bc9a.nq.gz
    ├── 0462dcd9fbb3e869d0868caec319ef292a807ffd.nq.gz
    ├── 07b10626697be511500bfa8d19eaeb616ca89811.nq.gz
    ├── 081633d02a6172fc0d22dd5b07cd9d33a5171329.nq.gz
    ├── 08af186468ada98cee14b390f3c704edbcb05be9.nq.gz
    ├── 09bbd6fe76159072a4362ad93ad344fb2923a877.nq.gz
    ├── 0a0401c0d4de70e6f3e7c05c9cbcc8d7cf8e21ce.nq.gz
    ├── 0a48004ddd328fa991b8df4c5393469adbf969f0.nq.gz
    ├── 0a61949684d123b82d45113a66ff8d9a855dc6b9.nq.gz
    ├── 0c28206be8746905b959978a7e20220cb423c5e7.nq.gz
    ├── 0d7b73ca02dccd0c8dd19a1b6958dad1e863fb0f.nq.gz
    ├── 0d8049e72c0967733379ceb16bbdfa447d63602a.nq.gz
    ├── 0d925a39474bad2a15ea75ecb4bb01129d2a1146.nq.gz
    ├── 0dbe85ab69cee6264e0516ddaaa916c5198ab3fc.nq.gz
    ├── 0e01ecaa94b21f5578df6ccff002fd77ede21e96.nq.gz
    ├── 0e2fbeeef3394e887b676b12c817d502a7322161.nq.gz
    ├── 0e5e48c0843f976080bc6b18559b41d04715dad4.nq.gz
    ├── 0eacf8d6d0a0c2d33d682b35c3a21cc1cf99cec4.nq.gz
    ├── 0eb548a7cab24e331578ef975409c6bb6437c28c.nq.gz
    ├── 0efda62590cc6dd299e8c0eb12bbd7d0528f7ebe.nq.gz
    ├── 0f097a5e62723be74e9fb707fb8653c64655618f.nq.gz
    ├── 0fb1c12e41f64c32af100bb3e0e9e695de5e8272.nq.gz
    ├── 115462bf058b2ef6c20b9b1291149ed999fff7c5.nq.gz
    ├── 11d9f3b7b349518382b813fafc7b1ae8c3b73bff.nq.gz
    ├── 1266448eab942533bd5b691efbdc1b40028bf5a6.nq.gz
    ├── 1278091e741dcadb762ee51d0b3b5d4b60079635.nq.gz
    ├── 12edfb59d1acc13b4fa8ce50de846076cc83d384.nq.gz
    ├── 135f73ce079a30b732e4725690a4baba913f1798.nq.gz
    ├── 1369de12f2ceefcd8ad490000e0525b054525dfe.nq.gz
    ├── 13885448443b9a10a19b063946b4c506afe9f60c.nq.gz
    ├── 13a1b257b1cb9580e3ffe68e53d50df253869357.nq.gz
    ├── 146bd9d7deac4adbca9e8ef2513a4fb43684904f.nq.gz
    ├── 14ac736da8007cefd35891fdddec0f979078e49d.nq.gz
    ├── 14b2e3ab885d776eae58be6fd7c54e3a9443871d.nq.gz
    ├── 150d60db2fcb8789637b27622fa8ce2d9c989e16.nq.gz
    ├── 151b9d52581dca1b8c6b6385b88fb134c85276cf.nq.gz
    ├── 15319e109982ac23a29ea4da19b9d62f56fc57b4.nq.gz
    ├── 158185ba78f71e63f1d6187ca9ef55094bf6d015.nq.gz
    ├── 162ace14bca856ca194c780648b6c1e23ee84a47.nq.gz
    ├── 167fea3a96829e55f855a4c687dff845cb868cf5.nq.gz
    ├── 16d62e060ea4b53266fea6da13f59105f6c5043a.nq.gz
    ├── 176722d85bc866c8662ce1a51bdb10d9bff4374d.nq.gz
    ├── 17bb4c80be3fdc44c572fb29337ff6e6b7fed550.nq.gz
    ├── 182838b10c4ad7739559b94f4383a2139ae1980d.nq.gz
    ├── 182fb66aee28fe4359b25577128a242ab289f6fc.nq.gz
    ├── 18f73340315f12d68dd0e20acb914eeb5e107055.nq.gz
    ├── 1a76faf2b2341e51bc60e615805b5247688e19f7.nq.gz
    ├── 1a83b9f3458718297f915d3220857687af019b9e.nq.gz
    ├── 1b0c55b315f7d75d1605d1c3f3ad77a88c8613de.nq.gz
    ├── 1b8f4a640ff0c36c1d855b5784299b536860c0b9.nq.gz
    ├── 1c724f57ff0642cba56d9b2acd5d74f0fcbf6c7e.nq.gz
    ├── 1c97f2ff6eeb8605b28f4657d4ebe209c793e0d4.nq.gz
    ├── 1e31d5af283f999bdb75f754fe6082c9b7a1db9c.nq.gz
    ├── 1fd6cb6c70048b5412f77563ce63d41c10e1c48c.nq.gz
    ├── 1ffbac5a0910d87f1de28abc1998a5f1b4cf5e0f.nq.gz
    ├── 200d2269345a1f3ada2e209d7b45a9c8d72b7979.nq.gz
    ├── 20f5f779440299980112fc668ac95d9ae831e62e.nq.gz
    ├── 218cf3f7258f8ca20d0571f8d59e1b9fa08af37b.nq.gz
    ├── 220b3f11d307107024c1fdca8195b79935c43077.nq.gz
    ├── 23b8786ff5b4247d999b4b48695a729acbd477e5.nq.gz
    ├── 249301558a5aa4e45da7b4db86d76d30cbbb4cdc.nq.gz
    ├── 2536982068df4fd61482dcbe58232a5b33095da7.nq.gz
    ├── 26c07e4237f2874afc0e0ab8789ad7389d4918bf.nq.gz
    ├── 270be4637393f44fc3cf55a6f75d913dd10640b5.nq.gz
    ├── 278ccd7e5e5c217f04a376f7b39f11a1458ae129.nq.gz
    ├── 279ace59ee2993a6b22935014dcc7b3c6ed19446.nq.gz
    ├── 27d01cd02c627bdab6aa38932c279fffcffc1717.nq.gz
    ├── 2868028ef3003659e21bb96d6ff9c40de88ac328.nq.gz
    ├── 286e42232bf63b35f619e5ed613d299313fb777f.nq.gz
    ├── 2924a9bdab91034cc176d81323b7c9ec5f4afd90.nq.gz
    ├── 298be7aa963485b102014513122cb30eb3ccffe7.nq.gz
    ├── 299177bf2e1ca52ea5a07b36418e39705bbda91f.nq.gz
    ├── 29a308ea294d9853d71a47d16dd8a65c20656fe4.nq.gz
    ├── 29ca38a7ba01a90e24736a00a3eac519fcb9201a.nq.gz
    ├── 2a7ecb83c479b0f107142b3d77481767e17503ce.nq.gz
    ├── 2aa48ce5b1f5770b67b60f8b7dff92a6d7266349.nq.gz
    ├── 2af840b770707c87c6c1976a22f49974e053e332.nq.gz
    ├── 2b62cfdbd99f9984ccd6cd841685e1c47b1eaf8b.nq.gz
    ├── 2b7b03d56e21e5c0b431b89bc0be70f347ebe372.nq.gz
    ├── 2c8bfea35502ffa233871064c156c5805318428e.nq.gz
    ├── 2cc0e8f85923c4b621522c31055410dd6a6f8c61.nq.gz
    ├── 2d09c0fdb77662726e078206863bd93d9c693235.nq.gz
    ├── 2d31daac529512a3b64b4351f0e3baa96e4d2cbf.nq.gz
    ├── 2d87a8fe112575af42827933ac4c35127a3e4f4f.nq.gz
    ├── 2dc516f130ca283edafcf2e48b707f3a59e65ee4.nq.gz
    ├── 2e30b838423d1d128bb98a5087204475f7234dee.nq.gz
    ├── 2f2b459c65a0ed69af173c586e016cd162689f62.nq.gz
    ├── 301bb64ba0c6efb2ec1af09e4f197bea23b8f111.nq.gz
    ├── 30fcbdc991182000766818e84963599d46f0e72b.nq.gz
    ├── 310a4019c4d1b708d9426a84692f8fd914afc821.nq.gz
    ├── 311461d10c18a6b9c14de1035e04fa2260c1b3e3.nq.gz
    ├── 322856eecddb306ace47cf4e9c4c81221bde5902.nq.gz
    ├── 32476c535d2c7f94afdd0f500e0a5e6a80eceae0.nq.gz
    ├── 325b90b3444be31814babf658d6f8688022f3f74.nq.gz
    ├── 3275ec1fc380108768e35d00b85820b575ca7cfc.nq.gz
    ├── 32913653489963acd55efcaf72da94d9de15567e.nq.gz
    ├── 32e286bc344480950357432fd16eae6b0ef8e72b.nq.gz
    ├── 344035429176be8c004fd705bc2e04c34237dc1f.nq.gz
    ├── 34e45c7298d812ce0cd6659dfccf8d3021b8ddd1.nq.gz
    ├── 35af50df5bde6ae18919f8df37e1997dae347dc4.nq.gz
    ├── 3614dd665a24affc808a785254d47302c1c38e4b.nq.gz
    ├── 365d29754e1a5651b72f2aabaa2a59ff3aeb3269.nq.gz
    ├── 36c0687bd27b0b94c503002626ec02d1537cd3c3.nq.gz
    ├── 38fdd1baf0a0d231df3f2bf873643984c024e912.nq.gz
    ├── 3b5f03f8b0d9821f1a44407dffabfd4066ee770a.nq.gz
    ├── 3bb07fc43937705059276061b5ab2a7063e94c50.nq.gz
    ├── 3bdb100c6190f5bd1fa636c0806c51e3d704c57f.nq.gz
    ├── 3c07885d32184021a817f2f97715addf1848e537.nq.gz
    ├── 3c8afd39dd042efa9db402a860a99abf568e7e6b.nq.gz
    ├── 3ca6b356102bc773fb22ab7831447e06023f4b20.nq.gz
    ├── 3cbe5bf6ebad974fe2b351025134154ca4987167.nq.gz
    ├── 3d4e3a5f37973ee59a30209fd8ab31d42e9e628c.nq.gz
    ├── 3d6f6046e38866117b595e5ff8a13c2aaa59c314.nq.gz
    ├── 3daca0df5c62dae8e5671450aa061f15008162ec.nq.gz
    ├── 3e4b250b681bdfb7fc2e4df248fc6be99bae9ec8.nq.gz
    ├── 3ee58d225efc6818130aa94a03b792f7cb764f70.nq.gz
    ├── 3f2cbbbb6e82224988d89649e936df5cc0fd07ff.nq.gz
    ├── 3fa3278fc9cfd4d64211ed82b27d879220ff14df.nq.gz
    ├── 3fc17f387ccc1338577b2a8529edd82eff33e319.nq.gz
    ├── 402bd5c4a85168f87c69379f529e1f5a687cc35e.nq.gz
    ├── 4192627c34d66a1ba487e80f556489ea8b864d23.nq.gz
    ├── 4267626d02bed411f8bd23ee50b166adace4fa2d.nq.gz
    ├── 43a29b63203771956f672f5e84b7a876f07d27c6.nq.gz
    ├── 4421771d7f9c9d5305b67d612856bf543c9968c8.nq.gz
    ├── 4500533d643992f5d15bf0a405c4689a19f87fff.nq.gz
    ├── 4661fed5e2ec6ddf6035a0550b264a230005e4cd.nq.gz
    ├── 46f447d2cf66ef38ce105b22583b2e790faa70eb.nq.gz
    ├── 46fdfd06efdf767b9bb6fe441fca6d4b7bf38706.nq.gz
    ├── 4823617af87a07d1dc5fb5f1aa9f196de91d55dc.nq.gz
    ├── 48b31f7cd4fafd29ab3da91271da993272a9fd28.nq.gz
    ├── 48dab923737dcc6159129d6cbe9e9ce1c2d3f665.nq.gz
    ├── 494320a4e2f297de2a8b9e268595810ab20530e4.nq.gz
    ├── 4a6d86d6158d5bd4b427a56bc2b3ce40fd9fd298.nq.gz
    ├── 4ad2cd9bff3bd74d44e5cd8d4345dd7beb276112.nq.gz
    ├── 4b4cbb33628f8389dd3acabb7b26be79da5bb021.nq.gz
    ├── 4c02d8dd4d5bc37f3a146e4c53bb8c190f80a9fd.nq.gz
    ├── 4c734fb3f002eda26a60f7a137541e26c78aef3b.nq.gz
    ├── 4ccf472b91838008a99f1af0285ae7f9d58335af.nq.gz
    ├── 4ce18914d55219ad34d9b5cd7e90ef6bacc53bf4.nq.gz
    ├── 4dcb024becd938e13fa1a876233fd2fd0e69fa8c.nq.gz
    ├── 4e02f8f6f9f5cd18082bb76a03d6be0c56fd3917.nq.gz
    ├── 4eda2657763f46b7d0d1bf0c8d97d9ac6fae3bcf.nq.gz
    ├── 4f96b9c3f98dc5dbcc964cd5953f3ece8eabbe16.nq.gz
    ├── 4fa97c5b777314e168dd61d02df5e70221c0f671.nq.gz
    ├── 515fdc9da97d29053fea1e8c174b4d6ea3e92e68.nq.gz
    ├── 51beec60c0df5af36220bc86a2ea92334645e6d2.nq.gz
    ├── 525faf1d748e82bc1277767d9949ece80f417f6b.nq.gz
    ├── 5263bce5068afde35960feb2a5b01d8648e79b40.nq.gz
    ├── 52d632f181a3fbcadf46b77cb791c2b5d7879137.nq.gz
    ├── 53843d3993c032239d2ed0dedaf02699455cc55e.nq.gz
    ├── 53b705f6ac80efafd44cbce774e93f2eec8ed7c9.nq.gz
    ├── 53c15d8105ff3e473bdf2fd1afc134921f53355a.nq.gz
    ├── 540857c30a52b28f5221e12631e099c699892327.nq.gz
    ├── 549037378fc7bb3c37daf26765063f0929c90821.nq.gz
    ├── 556b9ae09382e903afa70af770631f14b401ca35.nq.gz
    ├── 55864f2beeb9bedce5871bfaf5d74af2549e506e.nq.gz
    ├── 56dc2ed8bac92abde0db88addc41af52b79f3c22.nq.gz
    ├── 57812eac6137baf83e1bdfe86241baf275b5b867.nq.gz
    ├── 582abbb39afba2fd2fdec91009056bee150fa7ef.nq.gz
    ├── 58af8429410a7fde9b18b7c518a7d0a73889c502.nq.gz
    ├── 59eb52789ccc502a4ad2e7766635050ce95cb480.nq.gz
    ├── 59f67d06b526d19444cb1c82db26a2d1cc2f83de.nq.gz
    ├── 5ae192d906f8e43dea9f1253649749c1616f7641.nq.gz
    ├── 5b1e6e4a0a6f8b6cde2e8ca177680bb6b54b1691.nq.gz
    ├── 5e199580180c211feb5aeb61b440aaba2a7c5adb.nq.gz
    ├── 5e36f7f5c58cef1f0c13577ca41377aae993bdfb.nq.gz
    ├── 5e8a8c8daefabc11bac98a3af5ebdcb95f18931e.nq.gz
    ├── 5e95de21113b6e5fcdbadd2387cad8348bc0fbbe.nq.gz
    ├── 5ec2fde83aaf3b0f420286e2fe0a2c20bb1c595a.nq.gz
    ├── 5f7daab3e81fa8ddb7e1301ba3f9c2b53dbdcc76.nq.gz
    ├── 5f85c309e613a1808480a48d519bb124ea16d312.nq.gz
    ├── 5f901ae8098bb7172b772a2072b8c11ac93070b2.nq.gz
    ├── 5fc520c2a3b3a46b220d888060b05553c48a14b9.nq.gz
    ├── 605c12bd8a74d91f1bd1c3f8849d26d5aad65a16.nq.gz
    ├── 605ff4b80599b034ef6ebe3d992b9929196cc3ad.nq.gz
    ├── 612c9a40cf7f51bbd92bc669c168626ec7ae30cc.nq.gz
    ├── 61d3003716480a70168f19b455144cb5e9a30197.nq.gz
    ├── 61f16914daf41f371f4c99fff468cd438fd5fe2e.nq.gz
    ├── 630c2fca81a0ed91b55ce186922f0d4885fe6ef4.nq.gz
    ├── 63442d7017a35191bb287ed3a66ff3d3be293f72.nq.gz
    ├── 636faa06c4d1c35dc4d14727db94098716f3ce1d.nq.gz
    ├── 6458afa900d85c87762e28acfbfd983214e0b8d0.nq.gz
    ├── 658e3f088420265d629db2777af7d75c4b43884c.nq.gz
    ├── 65a38d29386fbf63a53872e3f5a562e6d4960450.nq.gz
    ├── 65ba1ce3451594e5a43a2d8c80e7e2a428a7f40a.nq.gz
    ├── 65f8d10db6171452c248642f18b936907dd1c50c.nq.gz
    ├── 660618e540f4fe936c7a3a8b73c509be55a9b830.nq.gz
    └── 66da8e272317d9e9ce9cd92547b51c308b102267.nq.gz

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

[NousResearch/huskyholdem-bench](https://github.com/NousResearch/huskyholdem-bench)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*

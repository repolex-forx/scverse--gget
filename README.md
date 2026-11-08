# Repolex Knowledge Graph of scverse/gget

RDF knowledge graph data for [scverse/gget](https://github.com/scverse/gget), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/gget
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 64d10bf03adfc3ede70aec467bd18e2e7a2ca178
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 64d10bf03adfc3ede70aec467bd18e2e7a2ca178
│           └── chunk-001.nq.gz
├── blob
│   ├── 04011cf36306c70e7ca89286f85d27919d8ad18e.nq.gz
│   ├── 05a4dafc07d3c3d05cb31a4e2a5378370e7c7c51.nq.gz
│   ├── 08903199a3ac4cdccaec653320c5214374be75c0.nq.gz
│   ├── 0939eb0a03e814423c90175df2781882cc18fbee.nq.gz
│   ├── 0953227d7d0b0357a03a1903531a567d7009e840.nq.gz
│   ├── 099cd0bec3537279392f7d9aed34456b4914dd55.nq.gz
│   ├── 0a3d14a51db5d70993ce1ca4d2deb30c3423ea9d.nq.gz
│   ├── 0ac0da53264e98c03ed3ead16680bc9e3c4475c9.nq.gz
│   ├── 0bcdc6ffe607f4f402903eae83704dfa20615c31.nq.gz
│   ├── 0bff9688409fa89f28d434d622f45f11e1539d8f.nq.gz
│   ├── 0cc0a394c1c4c8454c78fad215f6f0d3ff0c4612.nq.gz
│   ├── 0d799ab6430dae378d721f4f3991a7a138545c53.nq.gz
│   ├── 0e2e0356342821ae59fcbfeeddf6b7dd0af928ab.nq.gz
│   ├── 117be46ac21f4e85c2640ca33d771eaa04020b28.nq.gz
│   ├── 12798ac11e5059af7a71918b8c1c8eaed0c18c82.nq.gz
│   ├── 1306ad625504c9b76f7b1c1c9e6309aafe3fc885.nq.gz
│   ├── 1540e40a3ccf9c715f99cefec635bd4640c2c49f.nq.gz
│   ├── 18cb6308b8fb2e26398d243398bf711b74b5071d.nq.gz
│   ├── 191a407e916231c080c5a1405489ecf06de9dede.nq.gz
│   ├── 1af8d1de4db88ab8f24dbbf859b5565e0fe08e49.nq.gz
│   ├── 1bd6b642ed4f4581257a2ceaf0360b1be926cf7b.nq.gz
│   ├── 1c82984759a28e902796a475da0c5b2b8d3b8f4d.nq.gz
│   ├── 1cf75e41acb16ffbc7b3a161f1876f8a05c37123.nq.gz
│   ├── 1ed695c1cf93c81f1cc269e6187209290343f0e1.nq.gz
│   ├── 2171e0a119c2b68061239da1f7bb635e3c54ef94.nq.gz
│   ├── 22979e549654ed2fa9ab1e83cf54168ec223ab5c.nq.gz
│   ├── 22d82e1f37f484a69e3efb3a436904dd7c68537e.nq.gz
│   ├── 22efcd3c94a4036bd2af244d8be0896d892bb696.nq.gz
│   ├── 24db19e64a23e7c55232a4dc852102c71489186a.nq.gz
│   ├── 2513ef9d20d29203167148d00f82a06fdd0f1725.nq.gz
│   ├── 25262efd7689fc76f4d6ea1a7c75e342e840ea1d.nq.gz
│   ├── 28aad034e5fc326866ff8d68b8224591797af665.nq.gz
│   ├── 2c05786ed1d00ed105f26acdc128473780cccacf.nq.gz
│   ├── 31d84da6dbdec6192b463f774f36ec7320fb2cf4.nq.gz
│   ├── 32cf5b6f0d29878d4b93ded8c1e76629b9512c3d.nq.gz
│   ├── 32d06f880a80d654bca2716688bbb14ac70df36f.nq.gz
│   ├── 38e645da08f665ac93e59f606c74acd18fd854bb.nq.gz
│   ├── 38f90119fd3ed12884e9518e6a9d60991b40750f.nq.gz
│   ├── 3c20335fd219c1cdebb9e2e846276aba6e9e8929.nq.gz
│   ├── 3d578671c0a3e8ed766d2d164d59cdc3b5f9d2ac.nq.gz
│   ├── 3df50fa34ecbd83c21059aadcce6b981badfba08.nq.gz
│   ├── 3e692fd7adaa9e3798b3e6ff549d71b414857e44.nq.gz
│   ├── 414019e25fe89da649b13e1d2221deaa928df00a.nq.gz
│   ├── 455b2bf7d182984d429fbaad218cd0c9db20ed00.nq.gz
│   ├── 46da29aba92a24558728e2b94f297aa81537ae3a.nq.gz
│   ├── 470346fbbc355fd6e4e99a2285da535beca9eeab.nq.gz
│   ├── 4b4e48fb3388fd3854335d507c2c901c94a6d808.nq.gz
│   ├── 4c8b207e8c995b600cae1e69657bf2975d5ee7b4.nq.gz
│   ├── 4ce7f2ef5c0eca68523fff0874ac17c274b773d9.nq.gz
│   ├── 4dad463a1196389f3599ddc46f71ce890550ec58.nq.gz
│   ├── 4df3dd8565386ec2a4f474816c68d3065a0362d1.nq.gz
│   ├── 4e76c4ddeba448d50a93b438fab70a397df9af14.nq.gz
│   ├── 52725e82b1b512190854a290c59939d410bdafab.nq.gz
│   ├── 5279622f12e3a187cd259ca84335d6b001a95a77.nq.gz
│   ├── 5294229c1a3f4fba84871a20582874fecaa969f6.nq.gz
│   ├── 52b8457086974d0b2fc6a8fd12457a5fa6840871.nq.gz
│   ├── 536894471e11ec3a343b69cf9b80a48ea81df989.nq.gz
│   ├── 539c7f658c153bfabe74dbd5e507e81fe2ed6781.nq.gz
│   ├── 543a3923f6989b57ff64b27b508f689a3c632161.nq.gz
│   ├── 55659a060cc5193bee41a3cbd43bc3a2fa1ac070.nq.gz
│   ├── 577d027491168bbaee7b63fcbcc57884cf17bc4c.nq.gz
│   ├── 58f4a5393b28a8859d9091e7c11bda70e4eef946.nq.gz
│   ├── 594e9bf8eca892fc6a7a4108f4f812b85e798790.nq.gz
│   ├── 5ba50e509f9f61fdedac6e2f7db4d195b5a7ed2f.nq.gz
│   ├── 5d6a8109e6ce6ef4587c5fb02bb9d621aa3fa09b.nq.gz
│   ├── 5d8f7250a87e24b5e2eeeca077090c6700113bcb.nq.gz
│   ├── 5e1f60fe5f62d7baee077bf53611c7959f8c1180.nq.gz
│   ├── 62e851db8bf4ceeb269b7b1ca33222692a92614b.nq.gz
│   ├── 64e11103f43843b1f02ba170863be282f140c570.nq.gz
│   ├── 656d9277c022f21a72cbc864c0159a20de0e4a6d.nq.gz
│   ├── 65dbdfdedda067eec53e44c9f54ce9f29b056db0.nq.gz
│   ├── 66040f1915a0090cbb03a1956b8f9e252cd3dd21.nq.gz
│   ├── 67723c90228b69446fb01c6c9fbc867738569a0d.nq.gz
│   ├── 6bd5fd5aa8ccc57c90d60f560e715b09d23a428a.nq.gz
│   ├── 6df88088d46e4947db89a5c4290129d267c68ceb.nq.gz
│   ├── 6f294c1d44d762a268240e35b21688b4edad78c3.nq.gz
│   ├── 6f752d7d85e6cbc8a054e307a9758dfc3947d557.nq.gz
│   ├── 706738df1cae150f0d7c5987069da170707aef14.nq.gz
│   ├── 70fa60b463226c270a063c9330c512fa4532a9f8.nq.gz
│   ├── 7571c4146339b1c1ffadf078b880348e9330149f.nq.gz
│   ├── 770a9cfc9e19b5b5fda929f848ebc29bdb6dfd66.nq.gz
│   ├── 7b5d56c9aaf1d2f0d05c4739b345bd154d79682e.nq.gz
│   ├── 7e153c2dc205f1744f236d3377ba3638650d888c.nq.gz
│   ├── 7e458cc0e289a2c8360db51b5ded04114665a999.nq.gz
│   ├── 7e70e2e884912280cbc947f0dfa9631373463a1e.nq.gz
│   ├── 82da9645cb27b34112a27089bedf207b0721cb65.nq.gz
│   ├── 82fcd68bf04550763c3d1b93c79c8641774d592e.nq.gz
│   ├── 84e0b24e055e7a6376cae68f251347788622dd93.nq.gz
│   ├── 8566048b51aed0e984940d67d991ccaafda0fd44.nq.gz
│   ├── 89be22281f8d08eec69517626b264606245cc8a8.nq.gz
│   ├── 89decb39c64db4ecf6f53b891291bb5bcd32434f.nq.gz
│   ├── 8a6247e215d5f4345fad00fdec6201f60c8a3522.nq.gz
│   ├── 8c447f0295dc7fd162b061357bd8d303eda97853.nq.gz
│   ├── 8ca67f71526e891284a51d33618fad8de85f286c.nq.gz
│   ├── 8d34e4ed74d0fdbf8bf7ad5394a01f51cc4edf73.nq.gz
│   ├── 8e75bed420661e57de7af5d3d26ef7017b767386.nq.gz
│   ├── 91f72f47a5bab756b3a1def5df3f7d2e628aeb71.nq.gz
│   ├── 92a8f44afa520599eae4f0c8b6afad6f3a6ffbd5.nq.gz
│   ├── 94e6e5b30373dbaddd298d038d5483e2d8fcff1d.nq.gz
│   ├── 96dd74d8b4b4d1ab243041f73fb7d772a24ddda7.nq.gz
│   ├── 99440b054afe0f193e3a286d020e02c7ec78b4e1.nq.gz
│   ├── 9a7b3fe93760bef176f22c29ed7bf6fe94193c4b.nq.gz
│   ├── 9aa8c75f2aef1286cf5aa80c35492b47afbce544.nq.gz
│   ├── 9cdba4c602cd7d563aae928dd7d4b0e6bf0ba181.nq.gz
│   ├── 9d060af6bed4882b1a43bc2a4a78ff5cb2097297.nq.gz
│   ├── 9da8c72d51b5fe299761229012c1f9958de390f1.nq.gz
│   ├── 9e578ed3b97fd6577ec63b4a4215422934b5f127.nq.gz
│   ├── a0b02e7a5a9c5e7fbdf5d0495e405a400b848e86.nq.gz
│   ├── a18807f87c5e55663b39262f53d6f9cd6754833a.nq.gz
│   ├── a487b6653268037be47c85c31338272e2bc6842b.nq.gz
│   ├── a5053954d4eef5d8955f233188f8a2382b5b86c0.nq.gz
│   ├── aa650a2c67aced0c12555e1414e030c49bb09ab1.nq.gz
│   ├── ac92e8f50607973814b0ebdf08cbfadd5d9b2cc1.nq.gz
│   ├── adcd114b454f94bfd32e98cf474b0063679d3f22.nq.gz
│   ├── ade3ede28323115d8c76873216bfdaabb9b394cf.nq.gz
│   ├── af81d120e4d1e6143fbbe9adb50c8ed491ebca7e.nq.gz
│   ├── b030bcd1dc23e0e44c4361157b92e9911f1ae14e.nq.gz
│   ├── b0911957a909de5e3a38640957bbe7d09b78cf31.nq.gz
│   ├── b112fd0f2fcf9476d5b7c07d5900fb8ffbc82f20.nq.gz
│   ├── b16391c41c3e58b6f36ab678062b558c864445cc.nq.gz
│   ├── b1966a5f3f55d61f17c61af18db04827a3d09f85.nq.gz
│   ├── b6045eea5261130edd2eac8edaab1b6e82795506.nq.gz
│   ├── bc55693434aeb5d21ef0e8b2c28a5adb86fc503d.nq.gz
│   ├── bca032075120ef051b8442ae2702e9297ceb0f78.nq.gz
│   ├── befa85a3a2c3228236b16330ee65281a591253b4.nq.gz
│   ├── bf8bf59dd03f34188d2dff26caadecc9995ce606.nq.gz
│   ├── c072820d38253ceeab57408777606c1c932f0361.nq.gz
│   ├── c4bfe26d744ed70928fabb857d84b0dcc6bd0ce1.nq.gz
│   ├── c6ab3e0e893e45f6cfb2d2d86d8dbedfd061ae01.nq.gz
│   ├── c71c4a5cc024d640a7d7ed9a14808393022e24ba.nq.gz
│   ├── c7fb78c1d56c1740b37fdc41fad86ebc118ac633.nq.gz
│   ├── c89d55cb4d9ad534d773cf9c78a41ca7eee55f5f.nq.gz
│   ├── c9a2807e4a5aa70c8d75b76091eeff799841b357.nq.gz
│   ├── c9b1c80b44d2bc53987256502ac356d85e7e6bbc.nq.gz
│   ├── c9cacda5d51a058946af9c5e948ad734abd5d91d.nq.gz
│   ├── cb5d1632d3f13c2296a47570dc04eafe21a0e373.nq.gz
│   ├── cb94e6b77435cc3d5ff94a9d97e7564bcaa2b29a.nq.gz
│   ├── cc46ab59810788122413068ca6280db2b1434cdf.nq.gz
│   ├── cddb9d6c3c089596fb9ab6774600c7bbbf8ef201.nq.gz
│   ├── ce3cb035b82f949f6d7629fd8eb1a422430d7f52.nq.gz
│   ├── cfaa51f8cbc7844c9e3d4028acc8063b376d7a29.nq.gz
│   ├── d06a5006db161d3d992a4b761e6e50e143cbe614.nq.gz
│   ├── d35e629b59efa17a248082e0909d87644b39f759.nq.gz
│   ├── d3853a5576a96cb451910672ecbc544bd3771b8e.nq.gz
│   ├── d3e9897d0cf2668f8a41b31ffb610aa8c38ff358.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── da0d199f7b0432fac9c0fb9b545a4ae19d63ced5.nq.gz
│   ├── da86fa4697f8f254289f63605b42d13cea0f23d4.nq.gz
│   ├── da959cb38c51dd686987aa35cdd2f9d9d24c66f3.nq.gz
│   ├── db6ee838fb0acf22c2a1adc222f43563d0047923.nq.gz
│   ├── dc01474bd7ceaa39138f3a2474966a1e76a3a626.nq.gz
│   ├── ddb8df91a746f63bb6af8e317113ee1120cb8b9f.nq.gz
│   ├── deb2c75b7e6b7370e04555c7d77e98be8062d96d.nq.gz
│   ├── e1a55b679c42fc088e0e5d5b0b451b344d6735a4.nq.gz
│   ├── e2b03839bce910bcc9cf065838f33a78039a9aa2.nq.gz
│   ├── e3466b0fbb14deb79e52d2c674ff3946b52bd86e.nq.gz
│   ├── e49a274bbfa6f93e63da08633e9e487c6126a280.nq.gz
│   ├── e4f11ae3889f92bbaa4a069b7d74b050f4887777.nq.gz
│   ├── e58d026ca4191976ba6a971949eeda3ab6d88b89.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e76f8b82b1e7d612d2adaac1e98c7205f46ed611.nq.gz
│   ├── ea64fc766b37784310782aa836f6c3c9aa6c64a6.nq.gz
│   ├── eb7c8b7ac5f7b6bfb815e0a253891995e2fddd84.nq.gz
│   ├── ed0a71c9a8f3ae370b3f670b2ce19f1d08aac22c.nq.gz
│   ├── ed59599a971d02cd178646eb9c0ae518dcfae471.nq.gz
│   ├── ef8b1cc998d520eca58c5eaa3effb88933a7ed6c.nq.gz
│   ├── effd646f5aa316a868787e587b5293e7f3c575f0.nq.gz
│   ├── f0719ff2b45c8c9122fcde0cc0bf3439ce0821ae.nq.gz
│   ├── f25a5b27a2e1a82b997f2b96ea77cf49bae6dfa9.nq.gz
│   ├── f284c53684ed8e7900c5f89bbe42408a0e700cf4.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f45680ae9008f580d1bd2a12daa796318ec4574d.nq.gz
│   ├── f470e27c12631e380aa7df704d0e3dd552749c8b.nq.gz
│   ├── f4d75fbe7f307f4710f5c5686136f6a7eb334c7f.nq.gz
│   ├── f56cbcddcfd1c7dd20f5cac537469588a5a98d7d.nq.gz
│   ├── f5908531b0c4920b5c9eb03b006c1bad06ab9d63.nq.gz
│   ├── f7413206ac3d4d673f6fc18dc743a30faa2954d4.nq.gz
│   ├── f770e5c9bba1946ba055bd739a7582e2d913ccd9.nq.gz
│   ├── f7d5cedef85f0cdb85b7c422fefe63ebb704dbe9.nq.gz
│   ├── f94ab6e9b002a08a7f47aafc1ad97c4eaaf4cc4b.nq.gz
│   ├── fc104b082b3a714e707778ab33f07dfab0d425c8.nq.gz
│   ├── fd206147de437b4d782888b8df6773e46a1b0a9b.nq.gz
│   ├── fec46f7b19aa89ec76f58fd1fcf63cf40b8e1f8c.nq.gz
│   └── ff9570c92dcbed6b251a033d63a5fafe6ed280f9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 64d10bf03adfc3ede70aec467bd18e2e7a2ca178.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 192 files
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

[scverse/gget](https://github.com/scverse/gget)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

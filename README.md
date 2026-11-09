# Repolex Knowledge Graph of anthropics/claude-quickstarts

RDF knowledge graph data for [anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts), parsed by [repolex](https://repolex.ai).

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
rlex download anthropics/claude-quickstarts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a4224bdf0e9cfb3332167b69c90457403813625
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a4224bdf0e9cfb3332167b69c90457403813625
│           └── chunk-001.nq.gz
└── blob
    ├── 00376a1c59e483d9f86b33a98a00dfca43655bc3.nq.gz
    ├── 00aa0fb2010e0c7cc8def8ab065a034cb1e9185c.nq.gz
    ├── 01ff19c7e453295645fa83788d3ffedf6944226a.nq.gz
    ├── 022916dafb1f01267b6e52d87f92af25c6bfb465.nq.gz
    ├── 0270f644a89ee9736ff0e8000570d55fdc25ee15.nq.gz
    ├── 02e111d81dd774038ac483c11b5f5a8f8aceb024.nq.gz
    ├── 0361e1e7c744d29130d5aa7c99fc2effa100651f.nq.gz
    ├── 0458e7b128b2ca97e7e323cf84abe20292929132.nq.gz
    ├── 0510f5bea54235e039e9c3cd648349567782e8f5.nq.gz
    ├── 054213406241d99d9d559027a7a217ca5de3c86e.nq.gz
    ├── 062764e9a6f68a30274fff09ec49bd02b195f757.nq.gz
    ├── 082ff4de114716b7e8bad44ded9d5a8b3d778459.nq.gz
    ├── 084105cc9457fbced37970ffdaaee802bd0538aa.nq.gz
    ├── 08728fe6753ab7ebb583b93ff9b2f8aca5275ac2.nq.gz
    ├── 0ac959629e84dc4898997ec70093659f134bf4c4.nq.gz
    ├── 0b213594abfbb89d997ec64e559552138310d539.nq.gz
    ├── 0ba1a316809a11120dba5f6725f5ca8891198895.nq.gz
    ├── 0c214a26c69c4da18d83491012279b97386d921c.nq.gz
    ├── 0c2d45d4de98a1d9496e0f20d3124c1402f1c9a3.nq.gz
    ├── 0c981f616638386c2c293a9e680f6b65a3015d82.nq.gz
    ├── 0cdb752d674d38d9ffd6f9f9e58114175019c8ba.nq.gz
    ├── 0d33efbb4c7ca145a961b9f86aabff7413e6dedc.nq.gz
    ├── 0e34e4458c5847067f96c5ef494d9a9b982e37fc.nq.gz
    ├── 0e746adea77663ef2dfc0644e23d238d8cb7eda3.nq.gz
    ├── 114889973c62b6ba2b03ced9baa8e47bec23e6c8.nq.gz
    ├── 11eda0fe9cbccdb7bc105beca0fceb7e5422b7a9.nq.gz
    ├── 1201aaf247bb71a7e4bc5cc5e470187845631316.nq.gz
    ├── 13333e646dc5c78082973f6c5d5b7afb96e2f281.nq.gz
    ├── 1390c2dc0e316609102f5f7a092952392da2dc97.nq.gz
    ├── 13c8fc04a55ef90de56b1653c2e2cdfe97af71d1.nq.gz
    ├── 13f22e3ec782cfc130e8b84e69c556ab2cdaad70.nq.gz
    ├── 14ade4151916e4e9e28f7ab48cfa8df4ad953ca6.nq.gz
    ├── 14f656006b997f3f2848e7ba845fb548c6555b6c.nq.gz
    ├── 155fcd70cd37a95062ef3a439307916d5b459f79.nq.gz
    ├── 15a7f639cc5d7f739cedd3bae683807931e5f05f.nq.gz
    ├── 15e61adb2b26c63078532b7cb530e9c2219907ea.nq.gz
    ├── 15e97306d9611d5be0edfd139755afa805ecda11.nq.gz
    ├── 15f9774408065db450b74c1989723bdb27e2e932.nq.gz
    ├── 161a3b5a89a28d7748d1c8d5e8299fd4c9f0a1cb.nq.gz
    ├── 167edc164bc5baaaf30e058280d7a1c41b2af7e5.nq.gz
    ├── 16804e3c4da2ac3df6d9f79a6b49d45da58fb2fd.nq.gz
    ├── 168898186cb45a9d68d4890a90e85f18e639e2cf.nq.gz
    ├── 171beb46d9c020c1be1ee9cb260b816d0bc2c1dd.nq.gz
    ├── 173859dbbcffec0efc2ba8257f74b4de68d761fe.nq.gz
    ├── 1778185bec89d9bb023a0c648cf61b579adbc042.nq.gz
    ├── 179c6cf52002ee33c447fb12a42dde844afe04fe.nq.gz
    ├── 18b9386132db809cb764bf8716f99b6c6fbf073d.nq.gz
    ├── 18c8a861c70595d4b0b1f166fa825fd0c3e7d1ff.nq.gz
    ├── 19fd5bf558c06af3404839861b05d7aac683d74b.nq.gz
    ├── 1a5864f8375b4e041ad7402735b7b04d5fae3d26.nq.gz
    ├── 1a69fd2a450afc3bf47e08b22c149190df0ffdb4.nq.gz
    ├── 1a8312ba51985c112c5acc1f3f9fbf0cc2626dc8.nq.gz
    ├── 1b62daacff96dad6584e71cd962051b82957c313.nq.gz
    ├── 1b8198ceb003091e0fdc1f6c98851f3cb06f8e48.nq.gz
    ├── 1c30dbbcd6f203de03ad5a1ac47b0e0e9c43d441.nq.gz
    ├── 1c8e45f1ff6803abc4952ae6aa54edef6dd953c5.nq.gz
    ├── 1ce5a1c45fc5809535e6afd6ce3824d6ca74acdb.nq.gz
    ├── 1d079bf6c29d18267560e59f1f7bbd72d1dcd5d6.nq.gz
    ├── 1d0de4de7750f0490cb839b3d37ef059ad74cfc7.nq.gz
    ├── 1ddeee764d481cce84b430405fb51de19ee11bde.nq.gz
    ├── 1edbc8edc624ea6b3467ee65d70f07ba0ad68b02.nq.gz
    ├── 20268cbabd605234834988ac25fbfeb934e749c4.nq.gz
    ├── 205da293384fb675ae77d7c3193eff8f98dec3fe.nq.gz
    ├── 20a2bbfd0dd7e111a018987a998989d7d8eab225.nq.gz
    ├── 21d66741c07b7af004b445ca3e1dfbe881316c05.nq.gz
    ├── 2207500b010fa4399f813e60cc280e1347b30281.nq.gz
    ├── 2216fe5668222dd7170cd14c02791d9abbcab681.nq.gz
    ├── 23d49c693dd2ffab0473eca55672b215f5dccf58.nq.gz
    ├── 24a94027a1a3717429546031cf98895ec44ba40e.nq.gz
    ├── 25145439d76e27c5cc2ec9f3d370bb5029d9a45d.nq.gz
    ├── 25763668eaabb7f18f6f1c46b9ba3c6c4244f60f.nq.gz
    ├── 25ee5ad91812434a25ad529d68504081c116c857.nq.gz
    ├── 2697536d46ea6ef6bd1cdd9bdedb463d358c7139.nq.gz
    ├── 26c26020a2f24d4c2f2da9d892fd22685176eb10.nq.gz
    ├── 26fc9d239b28cdab3eb9bceedeb9fb98fdae7c01.nq.gz
    ├── 27d731ede13ce4b57b1ffc254522fae4cbd67601.nq.gz
    ├── 28471595c001595e9599402d3592af1445595f73.nq.gz
    ├── 288e9eaa6c512583d09a9eaf8173f87b406bca9b.nq.gz
    ├── 28bca4c7800b940175990660d372a231fd310f0b.nq.gz
    ├── 29513c2d98e30f4ff45f7326e29739df70f6de23.nq.gz
    ├── 295b45569ed353fcc8e05dde7c1511b35c7fc4b7.nq.gz
    ├── 2a1d1ebcb5587abaabba695b93e438996d53fd61.nq.gz
    ├── 2aa676ca131bded3491d5b0655d5257e504409ed.nq.gz
    ├── 2af09ad1acb5456866128664a002a38203f4da1d.nq.gz
    ├── 2b7831dc617b90815bc0f8051194bdbcafd26332.nq.gz
    ├── 2bd94af8e73d0026e079c45644708bbad90de48b.nq.gz
    ├── 2c64f5859941c582d107a804807008d5acb0201c.nq.gz
    ├── 2d081901bdff6b063d7ea8ef614526abb47efee7.nq.gz
    ├── 2d4757904e03cf1555a28bc3b0241c84fcb8e203.nq.gz
    ├── 2e3385b73fffb830cd3043af1d7763cbb98eaa8e.nq.gz
    ├── 2f29087ab7ff9075c7cb889657333ab26838ea38.nq.gz
    ├── 2f61294825a2a4b3a23fe0a6171a62e18649d061.nq.gz
    ├── 2f987d403bb27ba5105830af6500092efc6a76ac.nq.gz
    ├── 2fc198e7fe2dcd936468d6406e07a331d3106db4.nq.gz
    ├── 302e286f39cbbc5f021df21623eb14d4e59e17d6.nq.gz
    ├── 305d0d5d6f71da440dea1687a8394c04ce3fc34e.nq.gz
    ├── 30d3bc6eae0faa1c0a06e5757fa46cde3e50cf5a.nq.gz
    ├── 30fc6279d9b1d341a42287f2e45c59b4228a829f.nq.gz
    ├── 311f44f91c87ddd460bc8744335364a645f4e9c7.nq.gz
    ├── 31224dc69db7842ee2bb4a2a0f95e13bc7a9bcb6.nq.gz
    ├── 313383fc45b057b4e09027aa048c34b18253bb9b.nq.gz
    ├── 318f7d06552c73fda025393e1ccdfbbdc2613c18.nq.gz
    ├── 32873feca65cb1946adfce36c835385a317c7883.nq.gz
    ├── 32d1fb156935e474214c1cc1cae1388f4f19cc54.nq.gz
    ├── 334b890b5b9370038798c3b0b10040d185e7f39a.nq.gz
    ├── 33be0525d9596813df4dba68a1dd67ee8d3395cf.nq.gz
    ├── 34575f3f4c74251e5529406116d8cd21865117ea.nq.gz
    ├── 34f39a18b2ce3c77d4118fd829276db046f624fc.nq.gz
    ├── 3516a6be37d66fa389e862976397cefb8709bae3.nq.gz
    ├── 360aff4c59e4930099ebacd7ce387e9c552bbeaa.nq.gz
    ├── 365058cebd7d2bdb327ca1c081b16e4937e11050.nq.gz
    ├── 36a29d7b06e5ff53a15e424ae462aac484691dad.nq.gz
    ├── 36efc7f5de86a5b17e68b7237f814c81a95a6695.nq.gz
    ├── 3758ea51aa85df8bdeaa6111620d715167974c4b.nq.gz
    ├── 3972e7de412d8fc1fdd1a949166becacf4f78aca.nq.gz
    ├── 3977666b2419e9f96958cc0d8d86be6f28228ff1.nq.gz
    ├── 3a35d16b40bc9c3b7759a2c78b111ee8f559b470.nq.gz
    ├── 3c00487a5bf1580848659ee8817e1a2e716e9344.nq.gz
    ├── 3c3b8f5a95fd4dda097c3198eb935adf5f3a74cb.nq.gz
    ├── 3c464334be6a148b766b1125a3fd5e0303c4b23e.nq.gz
    ├── 3c561bd74434987c35c993b4ebe61b477b213ee3.nq.gz
    ├── 3c7c855291d32460ef36008789df0adcef072de1.nq.gz
    ├── 40cd254dee872dc6532f0122cd0f2a6e5cdcf875.nq.gz
    ├── 4143b91d2734f272bdd72ee67a72d086658c017d.nq.gz
    ├── 41617cc0c3b928c69c1424a789088707a0f3eb41.nq.gz
    ├── 41848d468481ec2e5fc415a420995b35f318969c.nq.gz
    ├── 41a7928e5af84634999ac956bec477685566cd22.nq.gz
    ├── 431d6eb3eef30421f1a329cbf9560af8236e9e78.nq.gz
    ├── 43c71dea0263c184544b0c73ecfdc614a9e564ed.nq.gz
    ├── 4450b1d33e690dd026a9f59fd409ff7267d80f58.nq.gz
    ├── 468bcee2619424978e3fff849704c08ce24cdc56.nq.gz
    ├── 47212c7f352710f8b0b708e7de7acb4ea414c7ab.nq.gz
    ├── 472bae21d13f4eb02c442e571ed242d8c5693c24.nq.gz
    ├── 476c5ed11272335a172b315e76e6ff9b2ae13600.nq.gz
    ├── 477de76f46af546ab8e7852af6b34bec3bea7962.nq.gz
    ├── 484466f3ab758756afa6f6a46820c34c47eaec77.nq.gz
    ├── 48dedc11e76a95266331f8f0662fe79b47c5cafc.nq.gz
    ├── 48f68a5054bc6ab1e263d38bf131dd763a7dc320.nq.gz
    ├── 494ae972b31fde49d11db529526ab0f896be1de6.nq.gz
    ├── 4a0ac08bff0628ac695d88f26b2ed18583a065d7.nq.gz
    ├── 4ad9ff6c82fa255ccfc9be4c55d6fa20f224df00.nq.gz
    ├── 4b35ec08398fedcaa2a5de34c03d112b18b0ca5b.nq.gz
    ├── 4b71a56022aed76782e4fc59954053df43344620.nq.gz
    ├── 4b8d383a8d90d41d1e5466a6c209b160cb13283e.nq.gz
    ├── 4b998c86c05df45b1b1a922956e7c2d52a433950.nq.gz
    ├── 4bc2cde0b36595ff6434fcdf0534b15fd5e4fd12.nq.gz
    ├── 4cdb4d0e878e215c093cb83fe85f6cd8cfc07844.nq.gz
    ├── 4d23b7c88ef27bb4c51857aecaa3999a785b4c06.nq.gz
    ├── 4dfb559f29aa9e3b5ce5e7646ec0d575b850f085.nq.gz
    ├── 4e78686c09af67a59acd663253055a236d14ed95.nq.gz
    ├── 4e7a33d3677b37cec77707b4fe98dd3c137198a6.nq.gz
    ├── 4f38ecfd9f2f4dcf32c1d3229d8f372ab059c589.nq.gz
    ├── 4f5167c210120e052923723725ce3bc0a7e8091f.nq.gz
    ├── 4f51c27be5b33cb00cb1935e523b12d4e0d90779.nq.gz
    ├── 508d83ae2fe247194359ad7c3d1a27113848fe26.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 51c70c0a062c5daad27785dfbb4f0167734a76dc.nq.gz
    ├── 51e507ba9d08bcdbb1fb630498f1cbdf2bf50093.nq.gz
    ├── 52479a5d1b2296bcd573570676c58c90d53ce897.nq.gz
    ├── 5301d130c556fe692790343582889e7c7cb63ec1.nq.gz
    ├── 53506dc015d6f4863b850c13d5fe3010e509b00b.nq.gz
    ├── 540367a33b905b20ffaab2a0d1b4f64a1156de36.nq.gz
    ├── 5446cecb823cbef0b8d2252f46210f3dce98338e.nq.gz
    ├── 544f575cbaf8176fdd03c4e2ab36bd3e43fe44bb.nq.gz
    ├── 5468dc611fac795dd91e0d9fc7c72446952ce668.nq.gz
    ├── 556af52e721379b4ca517ec3762a426bb9773f68.nq.gz
    ├── 55808e7e06c7ded09d6b399362c9f472146f538e.nq.gz
    ├── 55951588e5ec611f53a78a68364b8ee649d47918.nq.gz
    ├── 55b38fb32c3eb490fc4707a6b2c75fc52da2fba8.nq.gz
    ├── 55bdf7bf93de27da118273bbe385d406887ac5c2.nq.gz
    ├── 561382695f9afff9b1d794abae7176792735ac7a.nq.gz
    ├── 562c3eed87fd579eb74b92e35c8675cc76dd55ce.nq.gz
    ├── 56c58695134bce5213c8e5219c293780a407c59e.nq.gz
    ├── 571cae0eaf66651f33e0027d53505ee5f33deb7b.nq.gz
    ├── 5721a1f36adc23478c125e1023dc175ececbfc25.nq.gz
    ├── 58f8c7e2d65b5d2e9de7184033de8cc4c4a4d1a3.nq.gz
    ├── 595a81266adb875769c29247896f9a6b86e611df.nq.gz
    ├── 596d7727ae63b1c299553428bc4615cfa40060dd.nq.gz
    ├── 59832ae23e4a28c9c4e1412da97dfbb3df2ce54e.nq.gz
    ├── 59c63040ac2cc0254b184b34bb052f3c83fc5f5d.nq.gz
    ├── 5a280bdc5c63aea6c80a5cf84d2e0b90ad3cbbb9.nq.gz
    ├── 5c92e71ea292aa52b28b8dee48af6f83933c64ac.nq.gz
    ├── 5ce76c8e120c27e5798b7d9c798c8f79c91c2496.nq.gz
    ├── 5d1f711951373fddaa7cf1f2a2286830ef03fdef.nq.gz
    ├── 5d774720a4e0064d8189122930ee81fc722896d5.nq.gz
    ├── 5d8c7ca759731c7c55b4aa4de9defac263eb2c08.nq.gz
    ├── 5dadacddf79cd576a53588c2185d0519f28e56fb.nq.gz
    ├── 5de596e6ea71e0c68f43abd1fb513d02bef5da43.nq.gz
    ├── 5e3bd24bf00c9b670fbdc20823aed6d6f20429eb.nq.gz
    ├── 5f714f74fe1cccb21f318d7b23dc22ad23f60ba9.nq.gz
    ├── 5f831aecc21595a2762ee84868c22cc01ba81a3a.nq.gz
    ├── 6056c30ec335e9a7500d4a8ffcb4b67c31a6292d.nq.gz
    ├── 60668eabed2d72d4d732a36713a514644d5c451a.nq.gz
    ├── 60aea6c7f86e3b8046fe581e56b0d2e0e8d39836.nq.gz
    ├── 61a04bc13406d6adc8d44e15e46bf9be3b28d527.nq.gz
    ├── 621a922bb9e58a808c0402dd0fe8eaa5dc08edcc.nq.gz
    ├── 62441b7af6e3d6b3b578ac72af09d12065336e39.nq.gz
    └── 62a51c34180c8353d0803a74a91dd895f126ab01.nq.gz

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

[anthropics/claude-quickstarts](https://github.com/anthropics/claude-quickstarts)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*

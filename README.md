# Repolex Knowledge Graph of block/client-for-vantage

RDF knowledge graph data for [block/client-for-vantage](https://github.com/block/client-for-vantage), parsed by [repolex](https://repolex.ai).

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
rlex download block/client-for-vantage
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b49c0d130528b669bbf7e11e37b126b2a2e1017a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b49c0d130528b669bbf7e11e37b126b2a2e1017a.nq.gz
│   └── repolex
│       └── b49c0d130528b669bbf7e11e37b126b2a2e1017a
│           └── chunk-001.nq.gz
└── blob
    ├── 002aadc762ed76529251d54d3a29894492ad0165.nq.gz
    ├── 008b3037ba37eba9498b1ab2104df0390b8c031b.nq.gz
    ├── 00d178c5298136cc042999cb909a993755df073a.nq.gz
    ├── 014d480aeab9e65b993449a298ea544a54b48628.nq.gz
    ├── 0174eed28a2a0d9be80cbc60514deb544f4ed197.nq.gz
    ├── 021fa21fcc70fa530c532541687f99abef8c212a.nq.gz
    ├── 0239e4e71d1f5e4def44198f8b41c0138fb58e06.nq.gz
    ├── 0253f7698f7f3b8b436f92d3fe8cc757097ee1c9.nq.gz
    ├── 0266956bba4f2bd5a5371e40515f9aa08c8c15c6.nq.gz
    ├── 02b59a5ff049c2d0ec6dbdb0fd6bb81045c9fb2e.nq.gz
    ├── 03928a94c4181a103fe906427fbc52abd81d948e.nq.gz
    ├── 049ab086d98505ed28a2820f202933b486882055.nq.gz
    ├── 04c5f3f88b90930d781066c91c7e0d284cc24b32.nq.gz
    ├── 04f6ac1dcfcff081a2862f99377fe52e058275f6.nq.gz
    ├── 064615addfd39ecdbe67bf4847aea32b73474116.nq.gz
    ├── 07bc940ecbe9e9d9fe494e7ccdb3704f7d3d81e8.nq.gz
    ├── 0825ee47d73b98bc3a9fabe3f71b5fb671217495.nq.gz
    ├── 090428837b2f223017e7422932c59f472bf6bdfa.nq.gz
    ├── 090dd182d8d25e7f970c15f66ac1684bba5151c7.nq.gz
    ├── 096d7bc721c63a6eb4679990937b53f642ea92d1.nq.gz
    ├── 09efbe7aec5dc9e31021ef88421c1b58f6cf3933.nq.gz
    ├── 0b5a168cad984b64b01bdb528d7605d55881e59b.nq.gz
    ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
    ├── 0bde75cdccc346c5fdbc8bbcf5a4c47cf4d49c2a.nq.gz
    ├── 0c77bf1a6ea736523e3f25f09edb35c783b7c562.nq.gz
    ├── 0c856b6dd23e81642d4311b59e5cc4017f961493.nq.gz
    ├── 0ce58f6fda91e9d23ebc2599d7260af1bc9fcaf8.nq.gz
    ├── 0e188d4634929119ac299f139dd88e2bbace407a.nq.gz
    ├── 0ffb09a6ef16b4e1d6d04debe2ff687f6ee84e68.nq.gz
    ├── 102aa2bdce19e8d6d9e677ed63ea4eca6c912ea2.nq.gz
    ├── 10747ce929d5c2fa1565303287f5f06cc56b23fd.nq.gz
    ├── 10ab91f63ad1dd3d8a3293809526640aaa2b0663.nq.gz
    ├── 1105d1a855db698256395538b781237aa047988b.nq.gz
    ├── 11be1e9bdee4babb33bc8540d9d6589481da7a47.nq.gz
    ├── 127fadf91d81f2a655454ddc3c8b4aa6b685bf2c.nq.gz
    ├── 1430d3f5dc0ade4d74ffed1e85b059dea0cfb08e.nq.gz
    ├── 14a64f367001c2f3b19093dcd41beeb8c1793cc9.nq.gz
    ├── 1528b2d6e57abcde7e9d904edb95ecba6ab18294.nq.gz
    ├── 155ba3be17ceabaf80735eb05c002b1a17eedbb0.nq.gz
    ├── 1566a5050e8200665bb3f9dd09a7d2108724c022.nq.gz
    ├── 159f3e90cfa585b274a7e155625007bfbafbad7c.nq.gz
    ├── 15c7a95562d5082f3b76166699ffbce6d6b92af4.nq.gz
    ├── 16b60f42d77e95c9f21c641a307939ed17293afd.nq.gz
    ├── 16c60c496434fc4f9b5f62365616278cab437e5d.nq.gz
    ├── 175f4b2639d6a7f9c894dd34ac7111977e7c2afe.nq.gz
    ├── 176fe631fc962eb2c4471ee8a5a26bded3d2432b.nq.gz
    ├── 17fa8b7f630b79e32e80dc06670e0b0d68788d63.nq.gz
    ├── 180a56b3d32ee4b3e1cfa99faa283ea8b2bf55fe.nq.gz
    ├── 1879060109370655158f4f860c76837c40801bae.nq.gz
    ├── 18fd5abf86abaa9a83c15cfa5f307a84b950b358.nq.gz
    ├── 198b6b8427778c4e7ff34561d2d5dc3ee1a8fbf4.nq.gz
    ├── 1aaaed61cfb1d260bc62b4de03a5f22e76433608.nq.gz
    ├── 1b0e8907f4c82d506f2ac09204d558f90ba6e696.nq.gz
    ├── 1b15423fbed1006195feb6cfe018eaeb09dbb728.nq.gz
    ├── 1b80179931e0bf5111139857cef3dc97dbeed5b7.nq.gz
    ├── 1bceb2af277b0cf71fbc252d52163c66721a07c9.nq.gz
    ├── 1be96bf2217bb98a3e9006c68b16b9ae93ea706e.nq.gz
    ├── 1c0beb8a1ddbf344d8cf09249d0cfe61d66c9250.nq.gz
    ├── 1c1ee09ecf91ec4a065416e9158170173f648b03.nq.gz
    ├── 1c264ce5f11b48a2767a5a8eb335afa5996eff89.nq.gz
    ├── 1c509ac4b8d7ca1a92e0cbb962e17a2649599261.nq.gz
    ├── 1caa4da539340bce96b5f1e2910460d09caa9130.nq.gz
    ├── 1d9b3814d5b77ac45cff9ebec2aa1c807b0438ac.nq.gz
    ├── 1e0c124d601ba41475db6b325b2426d7f20169fc.nq.gz
    ├── 1e3b6fdd91e90df6e8e9800a277c838317bc9b66.nq.gz
    ├── 1e5624d3605f794dff430114a7867e9d6f244bd3.nq.gz
    ├── 1ef251d349dd36b64b3e87d95a660a80683752be.nq.gz
    ├── 20b02a8430a046e5406a48f9597b4be350cbf375.nq.gz
    ├── 215e204bd6f82d54dcca50b74f1c6296356b53cb.nq.gz
    ├── 2283a27c564ac574c7490b7f1b319a69d73f959c.nq.gz
    ├── 22c2ea19c514dc3cc56ec04630a327da27542874.nq.gz
    ├── 22dd1e38b692b1e0f4588ee7b1fed9dde10841f5.nq.gz
    ├── 23322efa8fb65589064df0ee6d442dd3611a50bf.nq.gz
    ├── 237ec30da7a4d5968bba11e8f30a6d4fb31b6016.nq.gz
    ├── 240d8297bacc6e3a2c6755dc25b7985601259276.nq.gz
    ├── 2487d2177f212b4425e346c7af96e74c87ac7875.nq.gz
    ├── 248cac0de501821d4e4ce64ad69b60a495c8ff06.nq.gz
    ├── 248e93b1f77b5192ea5ff1f36c6a83c89f23972d.nq.gz
    ├── 2525f46ba3f181e963e7ffd1456300b29f7aec54.nq.gz
    ├── 25ad696ae940e961c3e59b0e950ac465cbaadab1.nq.gz
    ├── 25c8a07be58568039ac23c7f751f007bba10c4bf.nq.gz
    ├── 262112ba5d4b112fa06843981ccfa6365d51bf32.nq.gz
    ├── 26251e64bdc0d815259393b08a6256a9a02805d7.nq.gz
    ├── 266ba5daba1d987b199f90b23e650b7cd382b1e6.nq.gz
    ├── 270036cbd8cbbcaf7840b248c93f4dbf31ab45f6.nq.gz
    ├── 27d0c1a815dfed23c524e1c59104910883e95b8c.nq.gz
    ├── 28327abac1af4a443ea15aa4f88673dff61d7f6e.nq.gz
    ├── 292bd6923cac2f157d84134a9bbf272e1f31d90c.nq.gz
    ├── 2971bb6f32268331656b65697c5e048aed976c75.nq.gz
    ├── 29fdf5d583c90db4d79c2abf6afa4b8c35c7fd24.nq.gz
    ├── 2a8774f348acdb18b870245b060c31d61698e97f.nq.gz
    ├── 2b0fb360472f9ca51927ddd71941d67837014ed5.nq.gz
    ├── 2b352cee3d6f9ca8a5374caf8841159cf990328f.nq.gz
    ├── 2b4835173da96330d85ea2e447cb7338653389bc.nq.gz
    ├── 2bcaeb8bc43b769b0db32b590294b646285994d3.nq.gz
    ├── 2c91aa3bb63082dad6d579d43ab622690a875049.nq.gz
    ├── 2d56dc976eacdc852311edf113b1214121bec5d7.nq.gz
    ├── 2e5345b3947e0026d5227268e7136568ca3c1711.nq.gz
    ├── 2f9f65a533fbcbff078d44ab885618b4a8ba2391.nq.gz
    ├── 2fcf6b7a5ec0af36b1916d11d29047f8302ceb69.nq.gz
    ├── 2ffa6522aac3529f6c0d2ef7ebe1bfd4b43f39a9.nq.gz
    ├── 300ed157475b02896a65c8706514a0c669ec2cac.nq.gz
    ├── 30b27dd3e363bde859788e24f5e99c5881e7c338.nq.gz
    ├── 31882e1b60332dc3d1e71c9e8d5fc3efe1ee56e2.nq.gz
    ├── 3240c3ea1864345a1a2e31f2041637da493a5e26.nq.gz
    ├── 32f70b1d1f46eb1a1889cbd79162e448f178bd27.nq.gz
    ├── 334bfb5a72dc58480518678353581c022a4ff1ea.nq.gz
    ├── 336b0886526d687a35512e53078e3f8601fb2779.nq.gz
    ├── 3376c7422c50db75f8416996288ff5a9b723af91.nq.gz
    ├── 33c75a12a70c06d1ab4b171e2f1645f2386065e5.nq.gz
    ├── 345cc06baaa3777fcf10c036e1d9629fd004e811.nq.gz
    ├── 34e4682e2418a07bd7791f24a9281a444601e4f1.nq.gz
    ├── 35371041f0f082a5c5423407949e5624e69e803d.nq.gz
    ├── 356c8429653d93ed13a1f516a8c9f5365d538080.nq.gz
    ├── 35bea85ba40cfed7048d289d02f32c6d1e819f8f.nq.gz
    ├── 36199aa2b6a660480265eccb262b89f51d3affd2.nq.gz
    ├── 363a2238122ae710f32d8eaaca0b0a3e04005485.nq.gz
    ├── 379f4a2a4b834df95f9d20b49d533c88826f5f4d.nq.gz
    ├── 37c96f1f2ab51de7085a3df33432e3e550a79c3e.nq.gz
    ├── 37def5dc57ec42e647f6b558b2bd5b9312395e98.nq.gz
    ├── 38800b57146f6e56e5db50d76e54a563c73d6f65.nq.gz
    ├── 38b24d568cf0402aeed8a1ac949017e18e904be4.nq.gz
    ├── 395d7c02668542aa2f13fe773e514c615f1d5688.nq.gz
    ├── 39c431bab3025d1a8fb6b32920a7049313fe5a46.nq.gz
    ├── 3a011c7630b5ac08457355c6fc53f292d25faab2.nq.gz
    ├── 3aae9df45cc6482206cbfd615146a1e44eac1d51.nq.gz
    ├── 3b42c9142c505132ce1feb464271645fd5b103a6.nq.gz
    ├── 3b5e6a4b9493f34f649ba45dadf7640543a93359.nq.gz
    ├── 3b7727b2c8a7c4e8d17ba75b9c00c76c6eb68446.nq.gz
    ├── 3c2e196e43d27a674109975e96715a9e2d07ba9e.nq.gz
    ├── 3c6079befc532a7e8348196e2d74592fab9e2bfc.nq.gz
    ├── 3cac58180c75aa2ba99aa422b0a0cbe74f956160.nq.gz
    ├── 3f3f196fde6c32bb08a4127be97838f05ec62bcd.nq.gz
    ├── 3ffa47c377289647beeb8665e540298071cd52ba.nq.gz
    ├── 41489c998bd9d2977763138043bce337e0453838.nq.gz
    ├── 420d31080428b3f2b399b6167aad5963a1e27ed5.nq.gz
    ├── 426454dd6f5709bb746bad048fa3e3d8663debed.nq.gz
    ├── 432d3724e7863eefff22226320834b8bc5009909.nq.gz
    ├── 437cbdeb687845f00697b051f8a50604138afade.nq.gz
    ├── 440967b628531b9a6b79f393afdd4dba4636d781.nq.gz
    ├── 44297fde2d889ce722d1b463138dae31cd2e0bf5.nq.gz
    ├── 4454fee48c873d7d98e8ad343a3118a30ea1a0b8.nq.gz
    ├── 44850412c4a28411bc462d5df07d718e103249a6.nq.gz
    ├── 44f90941f1bc29ea3cda2601a604b0af961a02e3.nq.gz
    ├── 455ccc1a71434fa0a9bcc9d2048a96dbb6aa0e25.nq.gz
    ├── 45e05dd6bb82320fdde1d7616f61666c9d1cdb08.nq.gz
    ├── 46636ddd34d13f3e2ba1b1905e430df26218458b.nq.gz
    ├── 4689ad7a97e39d941c70836595e50d010c9a5747.nq.gz
    ├── 4744720e30337625396eb52e2478d18011e4ec6d.nq.gz
    ├── 477164cd0366e684ef3988d6d55d8646c9113035.nq.gz
    ├── 47e4bc965fcb79446345de44a5f7bb29e75e4249.nq.gz
    ├── 47f3e4f8a8dd06b45ca9f488a840c58af021665b.nq.gz
    ├── 480576caaecb26d3f6ef276ebbc7bf47048df915.nq.gz
    ├── 48b5b43c6a2d1ea66b89060b1df5b2923586814f.nq.gz
    ├── 4915f5ea40aefa228c762316c3bdd07d964a73c6.nq.gz
    ├── 49f3f669f195f3e048942abf023ea5ac0f788e74.nq.gz
    ├── 4af3958eedafeccc3669161f3cd8bbe443dfa0f6.nq.gz
    ├── 4c963cae1dfb0b8d787f8f1bc3808229eeed8254.nq.gz
    ├── 4d2378f72772137cff01a9e3e52667f4dbebb823.nq.gz
    ├── 4d299faacbbfb0bb9008a857ac150eddab577781.nq.gz
    ├── 4e5ea5a5e38c49b617aa38ebc17de62880683905.nq.gz
    ├── 4f3204ddc611fa4dee22e724943e8c323aa83248.nq.gz
    ├── 4ffeb88f1c4de9004fcf072ee10bdc339ae89f15.nq.gz
    ├── 507b22d234105937c6a0688246fc3add6c19d264.nq.gz
    ├── 50bc9563405195aafd76de7cd012342c3cdbb2e5.nq.gz
    ├── 5107ed865045bdf02a84d5fd378059f61a5f5c6b.nq.gz
    ├── 51c5a802df3b79d5a0d52fb998eed053b97892d3.nq.gz
    ├── 52285d87ac5c19fb77287c5b2ed490dfdbba1064.nq.gz
    ├── 525fce8b09538671e5df7ebd62490ddd52a2a95d.nq.gz
    ├── 526f4f933e92cc745bd5887a3f163718edf3fdbf.nq.gz
    ├── 528a4e35b6d1b2a9dee73db72c00bcbd16dee232.nq.gz
    ├── 53478cb729b55ec23a3aa929839eba6cd2653de4.nq.gz
    ├── 537a22ede39c66a5a773c95715bf4516b72991aa.nq.gz
    ├── 53a3aa49ca9612614d618fd6581a30d8a8fac1f5.nq.gz
    ├── 53a80b1456f0af5812cdc5ce67bcc166858349ee.nq.gz
    ├── 542b42b0eb04bbdb868183aa748b3a05330f0a55.nq.gz
    ├── 56a24842c3f341b1753de4a359666812d64178fb.nq.gz
    ├── 574fbe12ead23cc8c1e1cd6b017f134a15794fe0.nq.gz
    ├── 57fd024113560e5fd76a551742b2ecf7c49213dd.nq.gz
    ├── 580f11588b8f521c8382af817239146265af0c1a.nq.gz
    ├── 583b9ec98ca1cd733d5dfb236fff7cdf1b16e6d0.nq.gz
    ├── 58ebf7c372f30bc6774fa3c159e0d6941124854c.nq.gz
    ├── 5940efc01a9ddc8f0b346ed4abdbda6d6da56d99.nq.gz
    ├── 5ac53b6c0e6779b82d0bee73c9fa6b799bc9863d.nq.gz
    ├── 5b335c698edd3a42192b3a71aba4fe90187c1645.nq.gz
    ├── 5cec0fbae1ff836152e67c6601972cb4c227b6e4.nq.gz
    ├── 5ebc7d3141c6d082f16b8d90ccf44df0c37f54cf.nq.gz
    ├── 5edc9b1cb3e695418297503c75bd8ee25d56b879.nq.gz
    ├── 5ef2a825e82b115e7ab28bf59263a39d00da73ff.nq.gz
    ├── 5f78a60c84843f1e5495cdb63d46fa41f5c5f8e6.nq.gz
    ├── 604c11e30f864d93f781205a039cb9cda4ba7a71.nq.gz
    ├── 60e5cb705dc722d205b4c0fa6c233460774d00f8.nq.gz
    ├── 617bdde1be40585c840a60df81fa7f02198215af.nq.gz
    ├── 62025aae7536586d46c3f195279b7996673a9832.nq.gz
    ├── 620cca1fbfe4eebe06db6432322f453c61b5bc4f.nq.gz
    ├── 629cff337ad38e21260cb713814b248aeeff4033.nq.gz
    └── 62cfd3144360bf7d8d3a7f19684f5343de3e682d.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/client-for-vantage](https://github.com/block/client-for-vantage)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*

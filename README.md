# Repolex Knowledge Graph of jazzband/pip-tools

RDF knowledge graph data for [jazzband/pip-tools](https://github.com/jazzband/pip-tools), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/pip-tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4492554a38e325db6ae623bf0c81cde17138120f
│   │   │   └── chunk-001.nq.gz
│   │   └── 5f31d8a79b5fd16305372cf700b01cc7f16c2ccf
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5f31d8a79b5fd16305372cf700b01cc7f16c2ccf.nq.gz
│   └── repolex
│       ├── 4492554a38e325db6ae623bf0c81cde17138120f
│       │   └── chunk-001.nq.gz
│       └── 5f31d8a79b5fd16305372cf700b01cc7f16c2ccf
│           └── chunk-001.nq.gz
└── blob
    ├── 0080fa230efde83e81bc7581fa0d779a3d01f62b.nq.gz
    ├── 01347e24c1c5fcbce35ceb5960f30efea95766d7.nq.gz
    ├── 06c09f65e4208a31b2c47653b97857ee036769cc.nq.gz
    ├── 06d294bdf8e36511502cc51330e7796f85800ff7.nq.gz
    ├── 06ebe8ea1907d28c29ae641274a75e4f489f0d5d.nq.gz
    ├── 07001af738998237e269f7d6ba8b6793a4bd9ace.nq.gz
    ├── 08cf5a22147a3b1e65e364b77cd13b4981c2d6f0.nq.gz
    ├── 096f99ad5859f998e1960106179e851c7a5a844c.nq.gz
    ├── 09f00ab45bbb185cfa1063ef774666af9ef66432.nq.gz
    ├── 0a14bf468a865f56df48535f8cda5c05e106e642.nq.gz
    ├── 0b798819869b3dedea59303c92441ce8945342b7.nq.gz
    ├── 0ed5a05ad996b4dbc09a4cf301d92b5876661cd5.nq.gz
    ├── 10e81fe25f554b4d4a019af745fbfad6421ae16b.nq.gz
    ├── 13ae93affb81fa79fa21a3c1a77b67ecc43edf49.nq.gz
    ├── 151fe17068d5225cb0c4cff3e52995e255f3508b.nq.gz
    ├── 16e97a35dc16211618b5ec607af5571c368b6904.nq.gz
    ├── 1aa5e0f0ffd01093ac073e1acf2d736293b19098.nq.gz
    ├── 1bea18fada760fb7f49842f2d9662df8d9a91c74.nq.gz
    ├── 1dd68b30daf8e723ab3e33eaa7b552a914f3f4ec.nq.gz
    ├── 238d2b2ae04245e24e674ed05db785fdfa9838cf.nq.gz
    ├── 252429d6ff1622d7fd4fc29b4c756edcc614578f.nq.gz
    ├── 264178253b5dc3174a53c2045001847f67906f13.nq.gz
    ├── 26b08e42985bee81b5ac4865f7d6e490ccebc4a0.nq.gz
    ├── 26e2148baf48d5821195cb3866b4318dece18c19.nq.gz
    ├── 27b87a7fa9acf2900a647aaeb351c401a1983b8f.nq.gz
    ├── 28c3eb686dcdc0b8d440c32341ff8752121a4970.nq.gz
    ├── 28dd94e7e349a84d90914375f0001e617ff32f39.nq.gz
    ├── 29201ced744c45e89350591c89a6efe0f04005e2.nq.gz
    ├── 30afb142422e7d2ed420f010eec7f2feaa82bc3b.nq.gz
    ├── 315a87c0e396cc5427863354bba9e7c93ca164ab.nq.gz
    ├── 32c011fdcd8aaea874a1bec663babbc1f7bf3adb.nq.gz
    ├── 33e62318819451b0bd3704d6a6f12b5f55447a4d.nq.gz
    ├── 33ef242803ed3539a5b5dfa62955b9bc31b568bb.nq.gz
    ├── 379c739dbbebdad2f5b9871c7ac6b61b802d60ca.nq.gz
    ├── 3bbfa0bf81557b55595530150db1df28a380c1ec.nq.gz
    ├── 4072d6b2ba953f3834f0d45ef78a7d382d9a1f5e.nq.gz
    ├── 40f24bef0fee431ac2613d8b32b5d4d0f50e800f.nq.gz
    ├── 41f560e7bed4c109284f207da466890eb5e25329.nq.gz
    ├── 472b0d58c87828ae70c026f9f6e628edbf14d5fc.nq.gz
    ├── 489f0814d158329283bb5f6f8732cb62abdef6e9.nq.gz
    ├── 4a6b5efacd477aa510571b246c21d0831887662d.nq.gz
    ├── 4ba3dd5fec9b2e7c9f5e8d0d82f076b3c76decee.nq.gz
    ├── 4ba9895f1ec2d36d02216de7182bcd1de1eb9caf.nq.gz
    ├── 50094bd9695a771ac97657e9730ff8ef7b01b96f.nq.gz
    ├── 532ad9d81987c00cf236543d64e10db1ccbb9f40.nq.gz
    ├── 5344560f4d66c9372d61032164220e4e4776a3bb.nq.gz
    ├── 536438df60834690bedc16ca5d61fa5c47461db3.nq.gz
    ├── 540539a69f7bb1c45a553e7bbd9f93cf92c23a70.nq.gz
    ├── 54577dc9a6cb86e2cf6474587e374018edb7a1a7.nq.gz
    ├── 553f2f8e1b1eba88764d4f955a22502e2bbd0f0a.nq.gz
    ├── 5607e4330d3d9628750482b76ffbfd07f87ea718.nq.gz
    ├── 5a0753cd2d5ff5527a96b09dccc474892534f353.nq.gz
    ├── 5b09748549a473c9a88ba18cc6b615a31b2c351e.nq.gz
    ├── 5b7aa71a945a2f7d27a3858f28cc8df83a534e3f.nq.gz
    ├── 5d54463cda87e0c474852300e26003a2bfe88f22.nq.gz
    ├── 5e43a66facfbc239865375a0a0e47fa6a2c1e957.nq.gz
    ├── 5e4eb01cf4e7c78832378c882783bdc16cde13b1.nq.gz
    ├── 5e6719f7ff54353908942b02e1611628e6e520b9.nq.gz
    ├── 5e68a092d141057b7841f4c57e9c84e8983e4da8.nq.gz
    ├── 5e68e9ed9e84827c7af171b8c9541aa2dc26f3c1.nq.gz
    ├── 5f32e149aa421942ba2be216ceb8742aa7c7b8ca.nq.gz
    ├── 5fd3f98ca7b6f432a749cad14aea1771a1d2895e.nq.gz
    ├── 62cb67e573d289a812f5ebc4ff934ebcd1bbc066.nq.gz
    ├── 645c9e8d89d8eaeec928ddf33dd89d17b7c1f15c.nq.gz
    ├── 6586b93cfa30fa105f8c3de96bc8a87692775d83.nq.gz
    ├── 65dd77950cab8d8e25c64421c1e5b64fd5b4986f.nq.gz
    ├── 67459944030322aa8e86f2d0517b99a6aee627c1.nq.gz
    ├── 675bf721f370ea352a9a8c90f2f28cd8233136e7.nq.gz
    ├── 68e762193fa8f6fa371ac1f90ff116340b5aaf29.nq.gz
    ├── 6a0f2cde2f4e5b52f63a931a4f1227459c903f8c.nq.gz
    ├── 6b472eee4ae241324ee34a3d33258f8a5c65f174.nq.gz
    ├── 6b8b303f6e7186b4b4b38ac5374b20b005da464d.nq.gz
    ├── 6d1461bda6511d5c0bfec3743b58e6b079861011.nq.gz
    ├── 6d9398250c3a57b6bc0e152ef2356cae5e6fb4d8.nq.gz
    ├── 6f2125aea2eeac7e362d509eaad978fea2b3841e.nq.gz
    ├── 7063e158ee640d40857f750564a6e7eee0435f10.nq.gz
    ├── 71b948e0e500c31ce260e8843df0811dd18e2039.nq.gz
    ├── 7340088474e203f887f9871ed2e1a368989cb042.nq.gz
    ├── 7468780cf814eac7ddc5f1c6fee025671787cd08.nq.gz
    ├── 74aa70a78a6f1210f6ebb347485f1281a826a76e.nq.gz
    ├── 78e9a5b3a6100c601ad0f399d5f7038afe5ed75e.nq.gz
    ├── 78ff4bf28b9b253cebd1df6cdf0504e4cbbcb879.nq.gz
    ├── 79a50a28d5686cad158576d72329da07cc37d0d3.nq.gz
    ├── 7a3d2592bcaf0fb6239c78707aa00415207ac4c5.nq.gz
    ├── 80c400a73325688cb35257c0e2ae6893ee4d2210.nq.gz
    ├── 80d273c96b7e74f96709864f2e7cf13e434598c9.nq.gz
    ├── 818152d870dfbe78410f1f2ea50f538aff2ae87d.nq.gz
    ├── 81c9977c0bd0992dee951c1fe1459cf7ccfc2403.nq.gz
    ├── 84f525d4186dee52269c548a03db0c2b52c19721.nq.gz
    ├── 85fa386b107907168876a62bf4967af06adb356d.nq.gz
    ├── 877d58a05b50538d9fd38c5a1a8832ce74c261fd.nq.gz
    ├── 899983774dcb41a7c10c2d4cf01ceb76d55c1e74.nq.gz
    ├── 8a87234a191910e70a87dc46b4e229a15f5154eb.nq.gz
    ├── 8c9faecd1588e0ee862491d4cf12c8f289bd2d94.nq.gz
    ├── 8d0e6a460d15fc5999eb452ea6d37ac29e47be98.nq.gz
    ├── 8da22a8df9e702d36ec75b42e715cdb6988a31fd.nq.gz
    ├── 8e618890374a0ce84e4cce71199ffd0cea8dbe9e.nq.gz
    ├── 8f42d69bcce1af3d79fe78a8595920bc017f0f23.nq.gz
    ├── 90e36d49ae72272e73c6bcf7985451572aeb97ae.nq.gz
    ├── 9140599c9bd5b5909422d8d2f828f8870b334353.nq.gz
    ├── 925c22f726b309fd8f7638432fe2a37fcd1f88d6.nq.gz
    ├── 9337eba3197965355433386ed0691768c0164f33.nq.gz
    ├── 93aa864ae7cbb265a6c3ffa7cf03018fabc8c957.nq.gz
    ├── 95ea662f70c61abb92ad710e66c0e93e482b95ac.nq.gz
    ├── 9658e1b87a7393c0e1f3003d9a574fdbf05d76ee.nq.gz
    ├── 976bbdaab0b70d7d8638b1bae50eede6e1a8deaf.nq.gz
    ├── 98551956216769a931bc958d40cf315801da029a.nq.gz
    ├── 993a4c6724b9e60a6075c731efe91a5a44565b52.nq.gz
    ├── 9951af27a27ffbb99cc0c45ed978abcbd90bf8a1.nq.gz
    ├── 99a15bb9abc9fd51326442b7d2de51974035d403.nq.gz
    ├── 9ad6f8122ef81b2c9b36c4c55b86a4e9c05db448.nq.gz
    ├── 9cbb7f7b126ae80e8a6e69adb5d777d36abe9d75.nq.gz
    ├── 9cd2bab3e2e5832af4b0476cb50026d9f50b52a5.nq.gz
    ├── 9ce424f98e246e7fa6559828dbbfa5852fb555ba.nq.gz
    ├── 9e58495e567737abb84613e8e4791d68a8d85187.nq.gz
    ├── 9e6574d14588144a766217c77703848af8c7cbf2.nq.gz
    ├── a0f2ee73d90d7f625700e44f1f29bfdf3cd0588f.nq.gz
    ├── a1cbb22f9ecccf556140391fd96f294bb0c9c6fd.nq.gz
    ├── a1f84cd518fff3c647b1efca40ae2819c9e848e6.nq.gz
    ├── a43c0a95500b9e59bf1405751ea8fe59a67db9d5.nq.gz
    ├── a48cb7e53c170fce560126b5bdfb3a4a05b1d523.nq.gz
    ├── a642b4d9512fe8c3722151d10ae965dea6385abb.nq.gz
    ├── a66dc5c79b79f03e32cab3718baf13a281c7ebc3.nq.gz
    ├── a73d774dc364d647276c35d23eb5ba958a0f0be9.nq.gz
    ├── a87ecd728a3b6cb442d2941f86ffb143617c0e4f.nq.gz
    ├── ab1d1529f5f156d6775fba43e97d19a26c4a15dc.nq.gz
    ├── ad9cc9c8f473007485fcfe906c395299bda9ae3f.nq.gz
    ├── b0ead496c3aaf7a64d0a0d25adfc042cf8a5869f.nq.gz
    ├── b2f75530fe36dec867db77cd2a033a89a8fbf48c.nq.gz
    ├── b32ceba42e880919adfbd31578e48003e16b4a8c.nq.gz
    ├── b50f14f451c6d08bbe011c7d2b6608b4300ea3cd.nq.gz
    ├── b519b839778a95f2479c85724f1615804cdfb39e.nq.gz
    ├── b8393b55b8662d66245054db13a59417fe74ead3.nq.gz
    ├── b9ff360e20ba8f7e8b9ce293fa812840c85fce71.nq.gz
    ├── ba49b299fb100b67d21d58341c988ce5c91cdfb5.nq.gz
    ├── bae34aca166b01adb85685eb3d27680077daafed.nq.gz
    ├── be24c5de2e8ff0ede0edcd0e12d664719440471c.nq.gz
    ├── be57515442afa817fa149ce36d63505684a26d5a.nq.gz
    ├── be6a6567e5fb6b2eaa26cacb0b6796e2172133ea.nq.gz
    ├── bebe3b045837ab93eab0666d7423ea609412365a.nq.gz
    ├── c12d0fdc8bf52480ed9c38f232f99464a65795f9.nq.gz
    ├── c49015c9bb664722242745064c3bcc867e28568a.nq.gz
    ├── c55361dfef886955e51e3533b385368d18ccd271.nq.gz
    ├── c578b46023e45ef978ef48d1069fb0f761412ab0.nq.gz
    ├── c6e3f41428ea29d2a0beb352819da34c2ee72aea.nq.gz
    ├── c70f0382ffda7d57a080ed30c0ff929a40685ea0.nq.gz
    ├── c765cd18dee90bf63622409c2996bb71d0480dd3.nq.gz
    ├── ccf59ddf4b8d258ec74ba4613b35477777d798cb.nq.gz
    ├── ce8badf01a24f4b2b3d26e88cdaab356f66641e1.nq.gz
    ├── ce90f5c804aba7fa22f15c6b7dda44c4ebda9085.nq.gz
    ├── ceac089e90d611addabdcec169c9081f1ae18046.nq.gz
    ├── cfd2394a3b6d26eec5e36d52e515ee478bd78719.nq.gz
    ├── d0037f6a1a771ffbe62ecf9ead1da26be51ebf8f.nq.gz
    ├── d611277c0bdabd5ecdbcd88f3812a26f63f63d0a.nq.gz
    ├── d6b7ef32c8478a48c3994dcadc86837f4371184d.nq.gz
    ├── d756d3ba0ff713bdd5ab76d3b6eb31e3bf27aedf.nq.gz
    ├── d7f25536fcbf3a1c6feb30a5bfb601dc6997a29d.nq.gz
    ├── d9c4f92426b61952f15f578c3eee598b5391d16a.nq.gz
    ├── dabb5cfa945eddac7564ef00455768bbb554167c.nq.gz
    ├── dcd4b2acd118a533932ab5ec6691f732eb6fe83d.nq.gz
    ├── dd4354485c487425b3e883c5734d0d3cc24f71b3.nq.gz
    ├── df91daf792c5d62a598b4ec46de99a97bddce5c8.nq.gz
    ├── e230a33cca7abfc51ebd5cdc00314f4dc3af7682.nq.gz
    ├── e29027a62ab7ab280e9de03994823d775a4c9646.nq.gz
    ├── e3645d6ed8666d0b228fefda9c424a280e98a41e.nq.gz
    ├── e3bd14ebb216a98888397c136aad543fec6ce441.nq.gz
    ├── e3d9afb75b9b221ceb5fc7120030cb542b1d194e.nq.gz
    ├── e5645c8ab2f7ab8249cd2f7af103a64b92238f56.nq.gz
    ├── e59cae74b5cfe1595c0f57ebd19fb07fe5b50960.nq.gz
    ├── e6072c3694259b274ee5b8bf4935f528ccc885ae.nq.gz
    ├── e6132495d70c5c9bdfd4c719b6ee2e8a6f782666.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e859deed6dad60954c7439bfd00548ea0c3709ab.nq.gz
    ├── e85d95c5c7fb2b0a1407b3e7521d30a9b4f11199.nq.gz
    ├── e8f09495ac6e8db1c09da278b6481e0e38af48c2.nq.gz
    ├── e8fb2821b21127b08597ccf29b331905647a2591.nq.gz
    ├── ea0d54d339e390027e30da146deb4660d8d0fa11.nq.gz
    ├── eb24805f1382ab0fb599d7c5a4d92cd1f02934f4.nq.gz
    ├── ee7b7dccf80ddb4a1ea15e8be329fc6f28a8dd5e.nq.gz
    ├── ee88c160b2cb6de7e772e2f37442f8bfd5fe497f.nq.gz
    ├── f210d536f58730c21d3c22cc0b6d6b8e9dbc2b11.nq.gz
    ├── f4befbba9c9bee05b37a07951192f32f9fef91fc.nq.gz
    ├── f55391bdada0952804671ff1b35416009e825920.nq.gz
    ├── f684c5923dee838858245435e1c246448118b373.nq.gz
    ├── f762cdbf1a54c99bdc9d04694ae517391941a0e3.nq.gz
    ├── f7b6887d8119897583e0fb83d6c222a538b7fbf1.nq.gz
    ├── f7ece0e9667d976dfc3fc1939047f516afca6870.nq.gz
    ├── f857dc2aa51830d6d8157336a6e93248f05af8c2.nq.gz
    ├── f9b080f2377f4e1f71af391cddc55390ae89abac.nq.gz
    ├── fa2413fc761ff84ea22f3012648249f99b749a08.nq.gz
    ├── fb445283a251abda06f6b6bd36305a43bf46e28f.nq.gz
    ├── fc46ba2a4d5d9fbdcc0d4c3e255b7bf5dc636f37.nq.gz
    ├── fc8c7ceae3ea6df2bd4afd9d722e1eec0dc8bbe7.nq.gz
    ├── fce5d7fc68986b3f237c0643e8352da9e6e756c5.nq.gz
    └── fef952037936ab748aaed3d3c66d85293de7f774.nq.gz

10 directories, 200 files
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

[jazzband/pip-tools](https://github.com/jazzband/pip-tools)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*

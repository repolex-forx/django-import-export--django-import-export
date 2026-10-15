# Repolex Knowledge Graph of django-import-export/django-import-export

RDF knowledge graph data for [django-import-export/django-import-export](https://github.com/django-import-export/django-import-export), parsed by [repolex](https://repolex.ai).

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
rlex download django-import-export/django-import-export
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6cdbaa3b49ed1017062476ddcb20d4e31cdda800
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6cdbaa3b49ed1017062476ddcb20d4e31cdda800
│           └── chunk-001.nq.gz
└── blob
    ├── 00239b3c509017c81ebe0e39494cf4088b5840f6.nq.gz
    ├── 00383aef579802f7d2a3da309e3ee9c383675879.nq.gz
    ├── 006e2a8f32c6dea2bb710f0b1969f4f83f97fa58.nq.gz
    ├── 032a6cf3932118e0cb9de1cdc78f88fa237c66bc.nq.gz
    ├── 0713356f4ef7bb9b6e99541391f930f2f27afb6a.nq.gz
    ├── 073d62ee12b4952cad2513087d6bbd27de5d380d.nq.gz
    ├── 0aed6eaf6c72b44e6f30a452f2cdd6888ceb95f7.nq.gz
    ├── 0bcadb7a861a569838730dde32c3f02f0834a508.nq.gz
    ├── 0c2f6c8ef8b47e5800cb02c63660cdbedead2047.nq.gz
    ├── 0cf7e59ae9f0f46f424c1bfeacbd3d6da0f4c228.nq.gz
    ├── 0d688621cb24e72b1d424620000a3c0733639ff2.nq.gz
    ├── 0e23b235ed4b9ea5aaea7f17803c09da5ae689ee.nq.gz
    ├── 0e2d18f62e25dc2e17b23bb74418d35056332073.nq.gz
    ├── 0f5e7db8442face73fb6264e3d119e98a5c77174.nq.gz
    ├── 1103f6d92d351ad0b3d7eae4fa8b6ded104f5ab6.nq.gz
    ├── 11899e1e085b0dfb2a143d9846240e2336a80116.nq.gz
    ├── 12e766432b30c6eb4349d7551e46a1823fd6f6c8.nq.gz
    ├── 14cf83c87b3f7a76c2ef9745acd05cd4917143fd.nq.gz
    ├── 1585ac7b76603d28e5ad902a10e603df75cca1f1.nq.gz
    ├── 16edf5e5ad3979105e74760c39ba71712abcff51.nq.gz
    ├── 1909d9aa035b5bfd6fa7d84dff9a4f3daa8565ba.nq.gz
    ├── 1a2d42fc3eab4912629d9b25fed7a315ef9e931a.nq.gz
    ├── 1a97604435757491ca0c6bd64e1858f8a8321dce.nq.gz
    ├── 1bc3bc3f640b1538c3ff4d357ce1eb61e2f1b01d.nq.gz
    ├── 1cc5de44ea13ffdced27e3e761abcaa5f8b4b71e.nq.gz
    ├── 1e70724312523255233d57f10717263c9209893e.nq.gz
    ├── 1fa32028ccd576514d64ac99bd5cb9f30820eb3b.nq.gz
    ├── 20469d2988848941d4a7db1c9540cc5564ba7c15.nq.gz
    ├── 206c3b22f0276ca817eb7f6efe92853005b12f5a.nq.gz
    ├── 20a796c702c02ac2bd09f1ff80092b1d3fc8a2ad.nq.gz
    ├── 21181f5b8061104676bfcabd570047c71372b700.nq.gz
    ├── 221eee38eed25821206ad52fe44d8767350891b1.nq.gz
    ├── 22f6e2d8f656878854938372b847b3558cd9970e.nq.gz
    ├── 23306e90ff088723201133ed2cba7fa78193a512.nq.gz
    ├── 23839f7dda225409feba9df289f0b66f712779f6.nq.gz
    ├── 25e1489c5e6794a0804d8f0c66c909cd7531f0d5.nq.gz
    ├── 2662394f6f96304fc86eaba230d67886f37c5e14.nq.gz
    ├── 272022b5bc0994fbc79e62bc99fb6d779afb392a.nq.gz
    ├── 27ac465aafa07629fc9b72adac326e92504bb224.nq.gz
    ├── 27fd249c3f6a5407ab71a1573bbeb638d8f38186.nq.gz
    ├── 28ea5e5230b5d348e3c0ec84d92d6cf69a41bb17.nq.gz
    ├── 296d944afdaa0932436d9aa4343d7b6af488a0a8.nq.gz
    ├── 299cf427ee323ce0051f596c6c03f176d6f840db.nq.gz
    ├── 29c64046ecef19a3a873ba2b03c3b4af31ad2e62.nq.gz
    ├── 2a704757e19627723b68f1e45d09f6406a16bd29.nq.gz
    ├── 2b7b4d978d6192b42bd6a7152b8b127fea00680a.nq.gz
    ├── 2ca785f10e9875ea1b4014365bade61394910663.nq.gz
    ├── 2f122d36f83547f2e74824ec60883cb00754d1f8.nq.gz
    ├── 2f4f7324c38f9f9a3462e5a4a8c27dbf9a263d97.nq.gz
    ├── 2fd6d1ccaacedc6ac71fa510ebea04c9e848c45f.nq.gz
    ├── 2fe35e4f30615029e2896d8ab3f9d01d174827ea.nq.gz
    ├── 316502ed86686b93903d56cc523eb36af764be33.nq.gz
    ├── 3375d1d67eb718140134e996154775f058d4500f.nq.gz
    ├── 3669113440d6669d3a3b6cb588c6aecba57dfeb9.nq.gz
    ├── 37103d60ad13e8266d047480f0f9a85f0276e195.nq.gz
    ├── 378020e71fb6bbc7240d138f9c5784208e45a65f.nq.gz
    ├── 37ab288cea841e8aaf63faf1abbd4f11558177ce.nq.gz
    ├── 3ad6ec9c8ac05ac33ecd6cb78391819959c4367d.nq.gz
    ├── 3c111a23b696e8ef0e3f1262ce6c7e5ead460454.nq.gz
    ├── 3db8c48886eaa8080c99c92316aa19130e3bd131.nq.gz
    ├── 40c8d69e73aa7af9f25e03ea470e446672b43c6e.nq.gz
    ├── 40cdb25eb25416caed05a54661704ab4ca757909.nq.gz
    ├── 41870c43c3ce83238db4caa5772ebc7bc3b04a22.nq.gz
    ├── 42813400682831fca14e3f09055240deb0a99d76.nq.gz
    ├── 42c50a1ab1f389e2b27efbfc8c88597dc9b11430.nq.gz
    ├── 436f8c9951f196c71629516e1cd2e0b42bdc2b82.nq.gz
    ├── 45130433560ead049dd8f9551fa640c2adf11e28.nq.gz
    ├── 4635aa71541b44e9ebe25686369d8f8ffe7b2098.nq.gz
    ├── 488abbf5136bcbf9b5c3b03b48af512a386f756a.nq.gz
    ├── 49848660ad7b1a7454be14e73bddc0dcf321793b.nq.gz
    ├── 49984086fcc04323da66ab3f4aaa49cc534ac088.nq.gz
    ├── 49d9648cab429d0febc0b2c938d9139be37f633b.nq.gz
    ├── 49fee8f8e861b6477b8ff3f787f3f969691675c5.nq.gz
    ├── 4a1a20c85630757e5aed78dfea51aa3821f322d8.nq.gz
    ├── 4a42e7894e192b95f1865805a50cd0f16811c0b2.nq.gz
    ├── 4a6215937edc2a515ebe80412eeb6ad2ff3ddad1.nq.gz
    ├── 4c4a22a070457153e01fc3d432422e59cf8380ef.nq.gz
    ├── 5008fcce49f6395babe175aae171895b4e69bd5a.nq.gz
    ├── 5224eeef433bf0500c2b86d6c296d697cad6a0da.nq.gz
    ├── 5540bad2587d516448a5b0d499645305a905c68c.nq.gz
    ├── 56418f9367329e769e8cb6a28869e89039cae365.nq.gz
    ├── 564da3001217279d7f1c4f232225b381c23b6b8e.nq.gz
    ├── 565125840ad994982340bf21a1cc7c4f757cf334.nq.gz
    ├── 579b8a5adfb4437222c36a8a7849d687614f4ded.nq.gz
    ├── 57f2d9333cebe706f600c48f8688aa46ae126935.nq.gz
    ├── 59d804311511aa83573b278ffd4844e9373a803b.nq.gz
    ├── 5a2e932400591e6957e348c1f0665cfa2b0dc554.nq.gz
    ├── 5aea826cd50ef90a2ac226b03ce3fd8f11441411.nq.gz
    ├── 5b776db534ea671aaa881f2a4f90a69d0677bf72.nq.gz
    ├── 5c4f480e06780eaf3edc6be227c0ba6ca3f0ee6c.nq.gz
    ├── 5c9c08f14176aac37f9f964e7fc8cec4fa2ef15c.nq.gz
    ├── 5d97bbb722bc33ab8c6e358f6f7205bfaa1edd47.nq.gz
    ├── 5dd62a94892fd64d8415e690acb436caffe06df8.nq.gz
    ├── 5fc9b94b7fea45410fc0106ad3952705e9c0690f.nq.gz
    ├── 60e14e9cf699b324fe9567af4369480a07d8c133.nq.gz
    ├── 60e481963b70d4065c70dcda45c1a9c9cb08b52e.nq.gz
    ├── 624bdd847568b61a942b2205617f22dea8b2b1ba.nq.gz
    ├── 6267794ac9e5bef89ada9a32bff00eb555ac11ac.nq.gz
    ├── 626ee4048566e620cc14bebde123a640e9c99de4.nq.gz
    ├── 62faac505200fa2d5a4be9d99df8deff3ebae3a2.nq.gz
    ├── 6453424a5e628ff43a0044e685c836dc1d2775cb.nq.gz
    ├── 6912c4299d5ebf0dd583546000b403aa28378ce5.nq.gz
    ├── 6a5dab36fc4409db16ec292d0dd2e798e754f6a8.nq.gz
    ├── 6abf1688806c7734140b7a2bc01d4595d80d0243.nq.gz
    ├── 6c5b6e14fb021057043f8ee04f80990e0e71faaf.nq.gz
    ├── 6c7959decf2182064b00636e05fd214caf25c4f5.nq.gz
    ├── 6cdf1a18257be44226bf84a915225c81a1808659.nq.gz
    ├── 6e68e4f086fb08b06f363211276095803e711098.nq.gz
    ├── 6e74a073bd4681ccb37cfcff2ad081c33cfbf6ae.nq.gz
    ├── 6ffe1d3ec10cc09d5efe4ea5f18ab1687e208d32.nq.gz
    ├── 70902952be9b7e96af969768d02d00c4e5ba00bb.nq.gz
    ├── 71e6963fc5049494f53b3ceab1bf54023d94871e.nq.gz
    ├── 71eeb436c4a03ffdd1526395d3eb7cfc312a8757.nq.gz
    ├── 72f58bb928e83ced2d71075b7acc9dc5dfb9e095.nq.gz
    ├── 73836c8df0900aaf703badd201555b258e946ce1.nq.gz
    ├── 743b03fe1b37c171ec566f49265c1ce28d2c4740.nq.gz
    ├── 75c24f49d7b2cc429eba4be7722a4d8ec141f57a.nq.gz
    ├── 783b4839d9ad347401a7f844dbd0e7c2c6e8ca80.nq.gz
    ├── 78821bc40fbe4262fdf77195fc10a7aa79f03be3.nq.gz
    ├── 79757a98f5dd69c77854c76079af9699357dc2f6.nq.gz
    ├── 7a6001a5885a21e28c87631d04472a4dba1638f9.nq.gz
    ├── 7c1b130187104e6a934e449e88fd392f21721039.nq.gz
    ├── 7c3c011c304d93cd7ec2671540cba582c5ba8601.nq.gz
    ├── 7d3a15d521dfde813ef0716ae7280726b4578b6d.nq.gz
    ├── 7d41398b413d86f6336893f149451d46c21879d6.nq.gz
    ├── 7da9eb923a062af8abff4b9e2174088aab8b0746.nq.gz
    ├── 7e85fdff1c3ac83223f708a1ee0a30ddc26cbb2b.nq.gz
    ├── 7e9222673fa3ffa40eb0e44cc8a3988e1fc118aa.nq.gz
    ├── 7eee73b076ff9247582fdc8a1b9dd7d6daf5f659.nq.gz
    ├── 7f818e2421621a6a56809b8361a897ed361a3201.nq.gz
    ├── 81055ab44f9254569392a48d2bd807590246b8d9.nq.gz
    ├── 82eb24efa4437dc051920e9215c480cca58dcd88.nq.gz
    ├── 8602c44a24f2a3178f4a56f3d1461e6bce2a83e1.nq.gz
    ├── 86e274330e7051b242ab1e0214cf250caac4b1c4.nq.gz
    ├── 8723b32b64a91500b484aaf269715cca17b5d546.nq.gz
    ├── 8927bf4abdea1f4e3a7f704f521eba4858f2b079.nq.gz
    ├── 8b459d92fed8837bd2ef3031aab83ded8aa4ca6d.nq.gz
    ├── 8c08ad893a137a8f207cf1d09dc5ca6c51763fdd.nq.gz
    ├── 8c3589f50a47963dcee67166e08b1b533889307e.nq.gz
    ├── 8c56d2666826435407d1dedf136b66e24853521d.nq.gz
    ├── 8de36810a67f240cd9419878404e42107ab6067f.nq.gz
    ├── 8edccf912b7420e8972ab4ec7b17bafbb45b3a0b.nq.gz
    ├── 90c11148cd51a43b18ba35ef9ce95c2a012ab24d.nq.gz
    ├── 92e7218fe89c208fc9df8ecc93eb0d3eab0790b0.nq.gz
    ├── 931152b0da033ba91eedb9588c1871099c867ded.nq.gz
    ├── 93def7e23fff76a3d231c5dd092bf99c1029cba5.nq.gz
    ├── 952d2a64068b690ec1e62ddee5b80321edd7c3fa.nq.gz
    ├── 9763112f55640ab5810a0261dd19ec16768c7163.nq.gz
    ├── 9abf238fa45ac11d6a6c63b97b01d79159cb16d3.nq.gz
    ├── 9c978506810364687e9460a8ace24ea51fd175da.nq.gz
    ├── 9cfff9d7fa5c55068d089dc281d61e7be6bc6b43.nq.gz
    ├── 9d8cc043c562454aab762300a7fc174a2871f340.nq.gz
    ├── 9e04a8cc6ccd9a2741ba4b501264b60b68f96d7d.nq.gz
    ├── 9eca0c434c69db460fccaadaa286374b01756847.nq.gz
    ├── a237779622f2de257c63093fb530e57edc0395f8.nq.gz
    ├── a476f1dde035cdcb528d520d1524443db86efaa2.nq.gz
    ├── a79a46411422d61425b5d7b6d85594a2837c8ac0.nq.gz
    ├── a7aea4dc5d9ed9422809321fb62fe4db59dc4ae8.nq.gz
    ├── a7d817baa93a73b51187b2c5f367b0b4ae19794f.nq.gz
    ├── a90173096b7d0260c0929ff317868b80ccb35f95.nq.gz
    ├── a909dcde13041c8b27617f01dc60e0e8b4fc69a7.nq.gz
    ├── aad15ba01f4f45696b6e23cf50b3631eed8ea742.nq.gz
    ├── ab17259ddb1fcf28b3e0b14413047efe82c24b0e.nq.gz
    ├── ac11bc81c4a39a13df0b7cabe9766b00d84baa2d.nq.gz
    ├── ac58c863cce8b56301e63f115d485fac45e02227.nq.gz
    ├── ad688b5ee3a9c9f159147f3c41292527044fdf35.nq.gz
    ├── aecbf3307d0ccf1b2bfbf211d7416ff0a75d9a20.nq.gz
    ├── af69b630d154a7ea6ca7e4018c7135023590d42e.nq.gz
    ├── b110ede80842c04bce5913c64f32221142a60f98.nq.gz
    ├── b187bbad4e2f016668fcf373cffd69161fe7991b.nq.gz
    ├── b193f6f6505916d3919c379031d071acfe82a381.nq.gz
    ├── b358966dad6cfc84f51c426411c15485d0d8b6f5.nq.gz
    ├── b51e1d946ccf3105dc49ed3a20c29baaade948a8.nq.gz
    ├── baa7dde8e7154c796017c67c3cbf0a973a0b43bf.nq.gz
    ├── bb704ad8dfa6387385f583968a7978f7e86da293.nq.gz
    ├── bbaa654e901ce21543654537aff682fb354eda3a.nq.gz
    ├── bcfd011aa028c3f130d3547c43dc2fcb714632de.nq.gz
    ├── bd7c99a941a5bed14ada89dbafc4d4a952247fd9.nq.gz
    ├── c32d85fa40f39aeeb70807ae2f254c7209c33fe2.nq.gz
    ├── c51299a75086b4c029f4732e14629054caa5c4b6.nq.gz
    ├── c6c5dfbe48abca003a78ff9cb2ba6ae88a76c4f3.nq.gz
    ├── c7e2b8b8c25f8b4e04b2a0ff4d825762a5620a0a.nq.gz
    ├── c807fa3d807cad86685e78cb6d1ea29b9745e6db.nq.gz
    ├── c8334a1b90860f730151fb073ff2ed41f32ce910.nq.gz
    ├── c8702f0072ca7d9cd2c4d553334fc9a68dde7851.nq.gz
    ├── c8b2b10206777dbeaba137ca3906a3a22b9d6cd4.nq.gz
    ├── c8b4a8aa69e109387fc4a6b4542e3890252940bc.nq.gz
    ├── c9893041cd38ca1250811ab3924d9296a73cd911.nq.gz
    ├── ca04e417bd0424d401594aa80a29bc418de624cb.nq.gz
    ├── cb5beeab819c3335ecc72c89c8e1043a2dc32b9b.nq.gz
    ├── cbd26022f2a6a92ad319d19ae65311dffc9bc13f.nq.gz
    ├── cc930e04e79357e7246ede24563e1da66257c648.nq.gz
    ├── cd1635fc41460eff6c6b58a01021f34158483d3b.nq.gz
    ├── cd5f7d6a18f4da18c8be4f86b96bd77459830562.nq.gz
    ├── ce165aae56281e403455e7848085d4bf45ec45e8.nq.gz
    ├── ceeee7d49b332b704d7b426eed74cabc11cd533b.nq.gz
    ├── cefe1066feb925a3c24998f70df6034638314843.nq.gz
    └── cfa30107e1983adc3b25c4c28b12002a32e4c349.nq.gz

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

[django-import-export/django-import-export](https://github.com/django-import-export/django-import-export)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

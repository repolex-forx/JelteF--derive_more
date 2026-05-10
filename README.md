# Repolex Knowledge Graph of JelteF/derive_more

RDF knowledge graph data for [JelteF/derive_more](https://github.com/JelteF/derive_more), parsed by [repolex](https://repolex.ai).

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
lexq download JelteF/derive_more
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 57867609d01b7d5ab05c9a1661996436f06cc657
│   │   │   └── chunk-001.nq.gz
│   │   ├── a381551f6e5e281db34b2dbe3c7257ea0e9fd352
│   │   │   └── chunk-001.nq.gz
│   │   ├── d6c3315f12bc88468c1d463a37581163dbfdaea8
│   │   │   └── chunk-001.nq.gz
│   │   └── f7bb41ac054c060caaf5ff3212e74e42794cb4b4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 57867609d01b7d5ab05c9a1661996436f06cc657.nq.gz
│   │   ├── a381551f6e5e281db34b2dbe3c7257ea0e9fd352.nq.gz
│   │   └── f7bb41ac054c060caaf5ff3212e74e42794cb4b4.nq.gz
│   └── repolex
│       └── a381551f6e5e281db34b2dbe3c7257ea0e9fd352
│           └── chunk-001.nq.gz
└── blob
    ├── 0031df96f85a52735eaed97f661c0cf83fe49456.nq.gz
    ├── 018e6acbd8dd3169f709f2f8652790ce14037c12.nq.gz
    ├── 025a8ebce732f5b034d354589a99e035d664f267.nq.gz
    ├── 02a9010c4c28925e1a1731ffea7ee43d09d14823.nq.gz
    ├── 039e8903ece0496051c7039a0bf23bfd4bc690ff.nq.gz
    ├── 03ce7bd174351d9492b0592327be41a31c6a2295.nq.gz
    ├── 049bba39b9c03b200f8d5a698550dc24507dc4e2.nq.gz
    ├── 04a85a186bd2f144e0874b556bf27a16952ceb72.nq.gz
    ├── 0593161ec5f74b9b7ec5dea1041b5b9520aa475f.nq.gz
    ├── 05f86a448e1c779e97ccf9fe383452da347e9033.nq.gz
    ├── 066053ba014bcfa0788d21289e122165488a8ffa.nq.gz
    ├── 073117208e820e25b036c5999dbace741d95ddfd.nq.gz
    ├── 07f7c98b2e84eef71b61f67a4b61928da6c1986e.nq.gz
    ├── 089a99bbc5a5a084988e846d1b047df812e80b0d.nq.gz
    ├── 08d41448ae9a2792b3b4c08bfe0a156c473f35d6.nq.gz
    ├── 0912169f7c64919340da940c6072b048cdb0d2f2.nq.gz
    ├── 097a89c6da638faea8b82ef92591c90f170be3af.nq.gz
    ├── 0a734eccad97e0bfceff3d43f61dadc1f84d46f3.nq.gz
    ├── 0aba15ad52512cdeefac632bfa1b07770427c636.nq.gz
    ├── 0acd4ca22c61eac162f7919191c452397fd8f9f4.nq.gz
    ├── 0b2c95fc7dbd1df4653d6a8d57702c9e9933f32a.nq.gz
    ├── 0bd97d9740c407b1b8e5b9ffb3f1bb8a7ea3ac9c.nq.gz
    ├── 0c2284ab652f71e6a354d04a5c21db2f0c597304.nq.gz
    ├── 0c6673b1010eb9affb4c16e48716578ae9db214a.nq.gz
    ├── 0c697c318dc03c3b8f0c778531b1237d023d409a.nq.gz
    ├── 0ca676d9b3d1b8a020137ab68f1a003f59fb09a7.nq.gz
    ├── 0cdd82b9e75599656b6ee245d7bdc612e838889c.nq.gz
    ├── 0d888fc7601a4310a86cd470ac6e410f77bb74a5.nq.gz
    ├── 0dc7ab063c364dfe58fc656ec1733ffb51a69011.nq.gz
    ├── 0e030cf6f53f80f006cb34f69d7c74e3227da7ca.nq.gz
    ├── 0e614241d205ff26edc5f91577ad78b33602c4f4.nq.gz
    ├── 0e68545371a6a6cbe1f9e313bbb2bb07a7fe6110.nq.gz
    ├── 0e6aa773e24846ed95616b5cdd53e6f267692386.nq.gz
    ├── 0e76e29900e40b898633de84161ae79745d8030f.nq.gz
    ├── 0f4601d2f39586b2708e99663c2f75fe8a6e41ae.nq.gz
    ├── 0f4bf98bc0d27698fc9af9cda27fcf16a5cb894d.nq.gz
    ├── 0f8a26748b7543e217b48a76a43379f91561588c.nq.gz
    ├── 0f991d49839270a3e37b057d7e5ee75613fead19.nq.gz
    ├── 0fc7565073fad40ca97cd1c8e2391da0af7d6493.nq.gz
    ├── 111ea03ff88da0e0bfbd569b010098d959367a31.nq.gz
    ├── 112ba15a1c68d347fcdd6d5463f07753fb45a8a9.nq.gz
    ├── 114e80c158b3b6a7597b7c80efeb2571b8697437.nq.gz
    ├── 11ec06b1e9abd3154af59ce891b88a6a2ff3fe5e.nq.gz
    ├── 121c5bb00fdaa87635ad84d9ae7024e8ad77e3a4.nq.gz
    ├── 123e3fb7bb4d595d3f4d7c7f732cb0eaa5af3411.nq.gz
    ├── 12f7db1eeca09d2028d0f251c0ced31246ce6067.nq.gz
    ├── 13b6076592f3b1a8e7cb3b5ffade402559a1d2d1.nq.gz
    ├── 14446959e56e2ae354c4b23f61d32b23fd32276f.nq.gz
    ├── 14465c4c8787dbddafe4919d517b80d65c0d248c.nq.gz
    ├── 14b91c488dcf249a8388f87c3e263fa761b137ea.nq.gz
    ├── 1561f0ade38e1deb33a08f74af54beb3581f8392.nq.gz
    ├── 15bd7ad1a2e3aeb45353ffcb76dea3f119b61c60.nq.gz
    ├── 15e7821a4d5b81f4d4c7e506143a242b186a1152.nq.gz
    ├── 16344e3f8396b4bfc1551377d60163bb34430bc9.nq.gz
    ├── 167950552acb0205bc6e686724ab2bf600d78afc.nq.gz
    ├── 169d035f573b3c56ff0f3ddc04b0c1c39f989102.nq.gz
    ├── 16ccbffb7648929792588f5a691a83c3a1c5b14d.nq.gz
    ├── 179c1eeba4d3e5326749a3dd50b13507e032e0b6.nq.gz
    ├── 17c3d1f65802bb280757dba99a733729b00ea595.nq.gz
    ├── 17ecb56742ec1abdab49c049dd05e0b813f79ff9.nq.gz
    ├── 17eea749ab6a7b767c814fd6330346ab83013d93.nq.gz
    ├── 180674a71e4408dee46a6efa139ca49d0581cad6.nq.gz
    ├── 1820df7b5ba4da176288d548de6eca5e52e9a2da.nq.gz
    ├── 18b1806972050e1b772fdd231403db781e71afe9.nq.gz
    ├── 190faaede6edae1f2e3015ce938988d8a24a22fe.nq.gz
    ├── 19199c0ac735f6bf2f33bf29817fece879cdd62d.nq.gz
    ├── 19b9ec0fb81a5f84e7ed89127ef0f420a3e19e5d.nq.gz
    ├── 1a27e9e2ccc0b71fac2d4a5915df75ed0b19d099.nq.gz
    ├── 1a7dfe1b6bb7e0d5a2c5a1d44d9d3cb5c9d23cf0.nq.gz
    ├── 1b3413a3653532fdc00927d3d882e322b9c62bbf.nq.gz
    ├── 1b748d82255470627769f42c1fa1f59b007139cf.nq.gz
    ├── 1b7c723dda84d392d740ab2bf9f32a2ace107a9b.nq.gz
    ├── 1ba2c5bb045d3082d57140c651a50969d8b8d9cb.nq.gz
    ├── 1bc0cb4de3843f213e99b970926e629bff0094cf.nq.gz
    ├── 1bd2aa5f5c406297067cd565e0ff90501f5510c4.nq.gz
    ├── 1c6efb6acc01e719ce5347822b128f2d11a19f0d.nq.gz
    ├── 1c7d9c5c4660a09687ec058e29857f014fab382b.nq.gz
    ├── 1ceaf35f9a907269568bea1550883388961bd6bb.nq.gz
    ├── 1cf1a19bb41f34ed82b4facd8f0fd4c6d9b7ad76.nq.gz
    ├── 1d05adc505442f408ec137a9c85bc45cbebcbef3.nq.gz
    ├── 1d6a44b7576e1c5ab5b10266d5d241878c3d7d73.nq.gz
    ├── 1f028e2d14e0da79d3cd36db52e786511e83bc4e.nq.gz
    ├── 1f8cfb1bf587ef754bdb77b7b152a26284030051.nq.gz
    ├── 1fb1a88bf8e5f13be9069f7de67a0689da31f0ee.nq.gz
    ├── 1fc2834e2617b1bf3b1869b600f97416c743478b.nq.gz
    ├── 209fc5f2c74f5c22ce1563c36da010e30df8e309.nq.gz
    ├── 20ff24cfe4749d4232b97b69120b1ed14927d05e.nq.gz
    ├── 211ffced0376bd074be51dc13fa3eb4011235596.nq.gz
    ├── 22045435292027a965066d587eb8f18fca6b7df6.nq.gz
    ├── 225d257882b585037f442754d1f526f40d93db02.nq.gz
    ├── 2267c16e17f8aa63a49249754a7626743492bb0b.nq.gz
    ├── 234daf475ccac771eed15ae3d1702f046b6d5061.nq.gz
    ├── 235f46ad3e07f949d54c6d1fc0091d2cbde923e2.nq.gz
    ├── 2396975e559c114dc6d52535e7233d183a845a70.nq.gz
    ├── 23dae36f33a6811477109f083a337eca58c2dcd8.nq.gz
    ├── 23fab97373216629545fd386f0a78ad8d2a770dc.nq.gz
    ├── 24135017f577dc605ddcaa76ca653473d9979856.nq.gz
    ├── 24227909ab8ac48a50e578479739b264abd73389.nq.gz
    ├── 243e83467540f30a050be7bb81649e636261d65b.nq.gz
    ├── 2487d1446fedf6389b5c0ce78d8116e3332ac494.nq.gz
    ├── 252a33bf4d819425f160c2c49a525964bc92479a.nq.gz
    ├── 25d2d9412114642e3d9a68a95a8a03c852fb7d84.nq.gz
    ├── 25d662345bbc1d4416131e7828d826b3a6dfbfd9.nq.gz
    ├── 26551a75db48acbf75b02f1aa3f3aa1194c0fe61.nq.gz
    ├── 26c1b799b50216a7993212daa2ce98607bc1619b.nq.gz
    ├── 27431409065e17f5078a2f30d90cb60ed3e94167.nq.gz
    ├── 2798db6116456f270fb1544fb9c932d75f690b9e.nq.gz
    ├── 27b959e2633936ebaf41f7d3d6d7a718dbb13ffe.nq.gz
    ├── 27c85f262e34c8d160dd157c3b2bffb9bd678b2e.nq.gz
    ├── 28187962b6ab8698c6c417583a8745b048522c1d.nq.gz
    ├── 28388ac07886a933e632728d92e27865ccdf2ed6.nq.gz
    ├── 284b0643fc3ea2c5e70dc894d48546f4990583ab.nq.gz
    ├── 28e593eefd8b78a020196df5fbffcbb078d67e48.nq.gz
    ├── 28edd768acdc26ff1a5318d2078c6b2724c0579d.nq.gz
    ├── 292b8abb62616108895caeee786bf000bcee860e.nq.gz
    ├── 294e5b82bc9e8a9577fbda1585dadb4546dae4d0.nq.gz
    ├── 2a48886d71e06f6c95912cf74e4114ae5cec4a90.nq.gz
    ├── 2a7de7521493a9e8b6a21a707a97045833760e52.nq.gz
    ├── 2a973d450cf1345a349dcd0536a9cdd7abddf896.nq.gz
    ├── 2a9dbb8b5a13ba9a3bf0aebe8e147c13ddf5718a.nq.gz
    ├── 2aace519ab434d89a0dea49a5c2c17cb0a553c34.nq.gz
    ├── 2bfcaeb9f17f25ca2bee20898d42e16c896e776a.nq.gz
    ├── 2bff1e972b37340bd69ada2937e7396f18cb5246.nq.gz
    ├── 2d505720d756fe88a0fd3cdeb4f6c616857da3cf.nq.gz
    ├── 2d7a79db2aeac9edca99d27eab1a8dfc5fd25a3f.nq.gz
    ├── 2df7732ba7a09726c5e31fd6f38daca15dc49e46.nq.gz
    ├── 2ea2612c3c372e208be1927b3455b209f6e6b9e1.nq.gz
    ├── 2ed1bb0b4f575557f36af3446d1999695afaf7b6.nq.gz
    ├── 2f5147312483a420b016ff933367727c54d272d2.nq.gz
    ├── 2f7faac93a7f18bbc5cc44d26b5816d9be870f36.nq.gz
    ├── 2fb6028a09c9781b670d540cffcde016d4e148da.nq.gz
    ├── 2ffd9a6289e6ec684efb23289fda3e1235ed5eb6.nq.gz
    ├── 300ed19e2209b564e3cd72111e3d103de2a50732.nq.gz
    ├── 304c3d9ab7b929f8e6e66d7eddee50a3088e8c09.nq.gz
    ├── 307e869a39372256500551766f454fefbff89144.nq.gz
    ├── 30b9b1e4085ac538967b572e05cefe548ebd64e0.nq.gz
    ├── 31167d3f32e918e4554910297bd9e5ee698b624f.nq.gz
    ├── 312d17f6d44b4878ea31977c8b7d68594b8bd3d6.nq.gz
    ├── 31453bde285439cddc12ccde7448e83cc6f1ee21.nq.gz
    ├── 318be69402fdbfc176717ade87b1d11f63e2e157.nq.gz
    ├── 319a79c8b03193c7068f1e01b97d8cfd0ee03d71.nq.gz
    ├── 32853379dab05e912a5cf238a7fa77c14e9f8cc9.nq.gz
    ├── 3369d00a60f98cf4cba5e6a5070c7b481dabf875.nq.gz
    ├── 33be10952e75e4be8bdfb21f3a060e6dc49d3e4a.nq.gz
    ├── 33edf287441182283fa38ea656f9a5755e9327bd.nq.gz
    ├── 3429f514bb5f1a0ce44229173a16ac9ddab7130c.nq.gz
    ├── 346559811f17f1315a7cf9c0cf7cff909ebac383.nq.gz
    ├── 3496d5ec5bc44894eff4d375a967773079b52af5.nq.gz
    ├── 352d40aa531c78e4a5255dc1af6319282de8c35e.nq.gz
    ├── 35e2a9436e65a66f5af8dd276f57d82fcd819607.nq.gz
    ├── 3671224079d386566a5711d804e193b78c57b1dc.nq.gz
    ├── 37c8829b6d89fab0fdc3a25808f74761f05a4f1d.nq.gz
    ├── 37cc89915a2e3ca2073dcf699345eb4f2d0039a5.nq.gz
    ├── 38654ec06f974aae5f600cc067a113f507239a71.nq.gz
    ├── 3953fbf7dcb7d86927b8213e318ecd45ebd9d448.nq.gz
    ├── 39751ac9870e23c460eb8fb3f710ea3713c51a56.nq.gz
    ├── 39a3541626218741ae45e141a7dab141d3a0727c.nq.gz
    ├── 39d0d576c6ee7ddb0e0ca0118f210bb62394db37.nq.gz
    ├── 3a398fb672861f8ff6956f0c049e5cdeba10a803.nq.gz
    ├── 3b2fb26766669c1fa347c242418b12bb9c83008f.nq.gz
    ├── 3b5cdb2d850cc79692ffb8934624a8ef9157baa2.nq.gz
    ├── 3d4d3d5b724b9e061c0b0633b84a511e0193218b.nq.gz
    ├── 3de06b84f19b894052db859578361daced78746b.nq.gz
    ├── 3ed2e6e839ed10963d4af376a5b6fd98f20180cd.nq.gz
    ├── 3ee791b7a1a07402849d034165f3eef234ba6c29.nq.gz
    ├── 3ee8909a443231d79057da504179e20243f541d2.nq.gz
    ├── 400aff060d9433bcc8b752b51a03566745ab132c.nq.gz
    ├── 40117085e833fa20436ef12d4ebb90f57f9767d1.nq.gz
    ├── 409265985cfa31f4f459fc4d4a927f8f179f84ce.nq.gz
    ├── 40bdf19a2507c90f477e2755569ac19529abfa94.nq.gz
    ├── 42b66376f597d874728fd4424df0f22ff8796aa4.nq.gz
    ├── 42c568a48a3e322598189aa782f861a6c9b503a3.nq.gz
    ├── 43a0211903390dad9392c2cfc766ae26220c5367.nq.gz
    ├── 43f55c06d684abb821b2a8c33a0f457122be7e65.nq.gz
    ├── 43f81fb0166d0586d0a89cba18176a27c8efb007.nq.gz
    ├── 45fcc245029ad9e1406371b9eaf283a1a80c113c.nq.gz
    ├── 461cc50d5b96e9bfba72741f8e5c8dfe0a3546bc.nq.gz
    ├── 46914a11a87ae17697ee37541b4bac6146a45b96.nq.gz
    ├── 4695803408dc2384845b1669d0d9d2c4b13321e7.nq.gz
    ├── 46a8137f0340b4e2111cd1fbce5ffa8de9251dec.nq.gz
    ├── 46e7382da7587e89cae48a0180c7ec3cc453271c.nq.gz
    ├── 46f07e9d20ce5659f362c2ad7a262c7e25bd731e.nq.gz
    ├── 47134e25304c8fead86d3c143fe0337f090a9161.nq.gz
    ├── 47414f50de04115379c5430ca7c37a41cc0d1264.nq.gz
    ├── 478e1d94fd0a56cc9fe556d7e2b9ace25286f7e2.nq.gz
    ├── 47dacfac7832e22a2bce3bae918e4be8c2751cbc.nq.gz
    ├── 47f709217b318a10dc9bd4888cda59af8d3aa71b.nq.gz
    ├── 4879585171cd197ba08c1e0701e963c7d7a273c1.nq.gz
    ├── 487bf734b4950d3ef847db3a306be6b025765f20.nq.gz
    ├── 4885ace22b0e721c3442574f807f892da374b9a5.nq.gz
    ├── 4899ae56453adab7c6473121fff49bd5ce934666.nq.gz
    └── 48af5a46a9ff09176ee30c4b1768d1a5f1dc82b1.nq.gz

11 directories, 200 files
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

[JelteF/derive_more](https://github.com/JelteF/derive_more)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*

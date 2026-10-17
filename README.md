# Repolex Knowledge Graph of pinecone-io/pinecone-python-client

RDF knowledge graph data for [pinecone-io/pinecone-python-client](https://github.com/pinecone-io/pinecone-python-client), parsed by [repolex](https://repolex.ai).

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
rlex download pinecone-io/pinecone-python-client
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0a97b36afe9ba86b7facf37946426414d888cd38
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 0a97b36afe9ba86b7facf37946426414d888cd38
│           └── chunk-001.nq.gz
└── blob
    ├── 00569000b96967c00aaf6fb9dbc8ca522c571ed0.nq.gz
    ├── 00c6562c03a776678bcd4b372cc0d4564372b1da.nq.gz
    ├── 00f6e0fe7009f695f3b25b9f28973d8e6a3fec87.nq.gz
    ├── 01f7c776b0e69c43c226ca4db578aa79f14a712c.nq.gz
    ├── 0293585a42085f86ccc7efcbc81bf1299fc2dd94.nq.gz
    ├── 0310bf64a5a2f04cfaf709acef0ae94ecb2026a3.nq.gz
    ├── 03277d68929ee62a9144700618a70b409c94f800.nq.gz
    ├── 039a2a97465c7cfa282f30d896f640f93fd4d0b5.nq.gz
    ├── 03aa0bcd7cd2a3d5b77f243b32a2c304888648ba.nq.gz
    ├── 04d9608c7fbc1726efed984aa085c9d179412f5d.nq.gz
    ├── 0560ddb943776fc9aa383b1e8976bfda7fb885bd.nq.gz
    ├── 05645b18177ad8d87cc7cb114446a1e733842579.nq.gz
    ├── 057139755f0b27efd3750924811b457f6fa6c081.nq.gz
    ├── 05d1ce2e1bb73e31e4ac7ccf0e416468f5be4823.nq.gz
    ├── 07343e90a688435e72efc276b63c3afe9c935bbf.nq.gz
    ├── 0760b3e180e7fa76ff3f07e4fde0a57dff357c3b.nq.gz
    ├── 07b2f7769b198242e3e0b94a240a7f0482e5722b.nq.gz
    ├── 0843140b6b8baa3b720f5451ed740c9c7b0c7540.nq.gz
    ├── 09469cdad9fb380c93a3464c1e46d855599a9405.nq.gz
    ├── 09b5b1fa1cf8e18f9d5429df0373600faec8409b.nq.gz
    ├── 09cb993c4d1941a7d1734f5ba04efd407cc9392e.nq.gz
    ├── 09daf574b563b5c6bc17df9dcee0c735937ee833.nq.gz
    ├── 0a2a17bf5571488603ae9aa9e9390ce6ba525c1b.nq.gz
    ├── 0a70ab3c94b4655b9b161c5e5e9e93f656298338.nq.gz
    ├── 0b5e0021057b2dc7c69cd25f2e6bf892c9209f4a.nq.gz
    ├── 0bc799c1df0d9fa3a09fbc80dc5c8097d1daef87.nq.gz
    ├── 0cf77318e4d077de6c804304604077ccdbf372b9.nq.gz
    ├── 0db75b48d71647d60b6f05a3370db4d5714806a5.nq.gz
    ├── 0e08f0b5fa8c392373d8e3da74bf1f7c62f3d280.nq.gz
    ├── 0e3a07fafecafed35f17ce8ecab389256a51da4f.nq.gz
    ├── 0ed6975770772cf0e5e3321bd6da104545b62c85.nq.gz
    ├── 0ee5b84c973d665228111e9c9eed64c1231e9c09.nq.gz
    ├── 0efcfef396d241c44fddab5f12ed220e698c5d07.nq.gz
    ├── 0f5c40d8999cb4a954dba4eef83b9e48b138ba18.nq.gz
    ├── 10098e1c0d45969a3f062bf293a97df616834274.nq.gz
    ├── 11db47049c222638a7e5cfc423e913a4e3d2ba57.nq.gz
    ├── 13a710b9b2262b944adc567cece462b792c99eda.nq.gz
    ├── 14717d966b5165dfe6f198038e36c6d1ec44fea6.nq.gz
    ├── 14b605545bd6203b0b5dd5579efeb11e772d9b0b.nq.gz
    ├── 1519b9eb3e7acd3f4f7c896de401b21a11297899.nq.gz
    ├── 15c8b85599dce555dc1bb69f51382ca9402ef540.nq.gz
    ├── 15cf439451adb772c12ee27d6608ffbadc88888d.nq.gz
    ├── 16ba7d1889ada8628df5fd1bbd79c7fe3399ada1.nq.gz
    ├── 17f4b1eb8d673b32287b1399ff31c1974339b209.nq.gz
    ├── 183931a86c3dcdccb6918aafa6b2594c1ffd5ffd.nq.gz
    ├── 192a8f504a304edd8da3c13142c2b446a954bc79.nq.gz
    ├── 19c46f8e562ef788dbaed86633b4d99595283574.nq.gz
    ├── 1a4a05560a5e0859474b96c7cd1a5c40db13fb24.nq.gz
    ├── 1a6e4232e8afe2acea6003bfc9ed06bcdd6120ef.nq.gz
    ├── 1b87560674f515c8123a42882b975e6d347a9a3e.nq.gz
    ├── 1c8d45235d89578d67259dcdadd17000c6cd73ed.nq.gz
    ├── 1ccd545904d786878b7024e91d1b117478985334.nq.gz
    ├── 1da98b7327380181cd8fe69eba99cf663e76b94b.nq.gz
    ├── 1ea1296b3c5d696ee31b93fa8dd73d4f6ff6521d.nq.gz
    ├── 1fc102e21e52a434ef99624a7a24e857db623d14.nq.gz
    ├── 201669955a6ea9224064991ad76f52f0e8729322.nq.gz
    ├── 205b87a380980f439a8c7edc84ba0746174aec51.nq.gz
    ├── 21aa02b5a9cdecc2e9afdd2de5a40ded3caeb058.nq.gz
    ├── 21cd29857deb52dc497afc87b7da579a47290d64.nq.gz
    ├── 225dfbfb7d1dcab0523a7284db7fec03fc0f3103.nq.gz
    ├── 22907579431bee08e03e69fa64200f743ef1683c.nq.gz
    ├── 23c8fb504d30ad92929c8b2af0dc410e96e78a2c.nq.gz
    ├── 23f2a6f59cce821a11574ab39112f23d25bc3268.nq.gz
    ├── 2416221a48ea2eccf7835821d89110ba77a0ffd4.nq.gz
    ├── 25c51ba07d1a07432a71086b6a0a43b71fa093a9.nq.gz
    ├── 25f3d9414ee972f2e0dd96063599012e1cf4a21e.nq.gz
    ├── 26a4e20696857fd8842a7b55552a20ef15e96739.nq.gz
    ├── 26f28eae5f1fffd66682304342b2cd003b5480cf.nq.gz
    ├── 276bb015d6653de6193479ada8c0bb335a2071fb.nq.gz
    ├── 278c89ba86bad9b6bf2e06d4c61ae406ef567a2f.nq.gz
    ├── 289481d5071814f701d09cd6c109dec6b57488ae.nq.gz
    ├── 2954eb59ebbc8cf4b8a562baeaf2cd0311df2efc.nq.gz
    ├── 2a029a045c71adaf55c352763519b2d7afab2170.nq.gz
    ├── 2a248ded20a7d74e4ac712281a95e36a978a80ca.nq.gz
    ├── 2b14016f503c4821c97e6e43fc3dbe762da86e55.nq.gz
    ├── 2b2e97245198bd33140aab97911f72bf57ec84d4.nq.gz
    ├── 2c2d468e99363b4b53521c1fb5a773cb9080a8fe.nq.gz
    ├── 2d3f53121cea6f9ddf452256236bc680728f9944.nq.gz
    ├── 2d6b8338f5db0e826f333c9aef10294b1774b5cf.nq.gz
    ├── 2f4ecd3849f05ffe28c6704f9cb8f054a6dc3fd0.nq.gz
    ├── 2f8d45d15611cfbd90ac997a1e337ebe5603538b.nq.gz
    ├── 2fbac27992a30ab5550f142dbd6a3240035a3057.nq.gz
    ├── 3045b2288434f1bc5ebcc3b0adeefb09d9a3088e.nq.gz
    ├── 3158cb83ba7e48400f67404f71e5f386ff9ab400.nq.gz
    ├── 31fff3bad97d8aef70f2d6449d71a6a3632001da.nq.gz
    ├── 326ae563433c7f67f160613a5e1e3697491d25a4.nq.gz
    ├── 328421e107eabb7a75799123ea2ce407546d3059.nq.gz
    ├── 33b7ded3a41341e301b92545252c14a940be2c56.nq.gz
    ├── 341af483ca0324bc813e35338b7bf7c37fb12504.nq.gz
    ├── 34a22ca94d0b79f2cba675f00e293713b31cb090.nq.gz
    ├── 35aa581d73fe194d18b3a27470f6600d45346140.nq.gz
    ├── 363ddeab3cf4c5685db0c75370c4579d59c73059.nq.gz
    ├── 366dd2d1f9cb130d99f9df39f7812842eea52fb2.nq.gz
    ├── 366ee7697930a379914dbe3febfd230af79a5077.nq.gz
    ├── 36d0cf4893e30b0748245f2a1e480b4aab4f75f2.nq.gz
    ├── 37a4ca19a957c468f9b4ab6c2d9b3f29fe75e663.nq.gz
    ├── 37ebcf837bf060396a29cf462d4aa37c950c95b6.nq.gz
    ├── 38c49124c0ab9f79511dc90868196725b52a74a8.nq.gz
    ├── 38dcc1bdbc371d13b3058461269c66a0f88c9cd8.nq.gz
    ├── 3a00dbcca5e5769e63facea19693c5797f528427.nq.gz
    ├── 3a9724613dd203727103b5cccd0036e12022810c.nq.gz
    ├── 3b687ab35e4da08f35d05c3529e51bd51b7f14fc.nq.gz
    ├── 3c1bfbc98cf428e858acffe4f14f82ff58c2c4b4.nq.gz
    ├── 3c5eaea1f14d50c2541fd3a940598fbad47f5113.nq.gz
    ├── 3d1decbeda31d3438a850121135849172a785a42.nq.gz
    ├── 3d2dbf44eb9a43c07f33e2b2da40f53c53b48fb5.nq.gz
    ├── 3dc901266058a7118eaea7e5eafbbd75070325bd.nq.gz
    ├── 3e61d2a27b16783cb3ad46d04d93024c63c8a765.nq.gz
    ├── 4006aeadaf5f3865add1197cdf0924a9dd66b61f.nq.gz
    ├── 40d8343376adbeeb3eb96c7913d19d0a7e7e6491.nq.gz
    ├── 4158dfe45d4984b7e823476dd37f670472e4b97f.nq.gz
    ├── 421d6dca0d51b7e6ffd7bb89f20a82a1247e8745.nq.gz
    ├── 428ea975974bdf6fb0475f41ce246385beda2bb5.nq.gz
    ├── 42f8ac52a65aae8d033a79fed8159b04b4ffbf51.nq.gz
    ├── 430376c327c5aa6b8d82c4997e8831d289ab04dd.nq.gz
    ├── 43e0582513563479719919656902f21f80d22230.nq.gz
    ├── 442420fb5cb2877f997e01ebcf2b13981bd8b787.nq.gz
    ├── 44760bfa09b75795269d3c4646736e1e707fbfe2.nq.gz
    ├── 452d1d472ef08de6d7085993e1daf66d7f9ca929.nq.gz
    ├── 45666a99d41e33b6729fac74ca6316780cff16c2.nq.gz
    ├── 45b21c5460466f7a719dff4e09c15853c42491f4.nq.gz
    ├── 4621b5cad5463844ab5e963e48ec9e427738f30c.nq.gz
    ├── 4682c43c13072d7a441e726d78f603c133624161.nq.gz
    ├── 473f4d8b7f25deb1af0c8a19ab13e34f7be3d643.nq.gz
    ├── 4849a4ec108b54cfd98adef8b6b3ee40e1df0ed3.nq.gz
    ├── 491cc730166fc84093ca34d104044e89452daf47.nq.gz
    ├── 491d88f82c39fc1c7038bedc5bcdb3effb2a4d3e.nq.gz
    ├── 495e85f04632c7073e1db75845a8d3d06abb6977.nq.gz
    ├── 4a3e95204938a22ea91c36f604d945b85c210cb2.nq.gz
    ├── 4b1044cc0cccea11b08569b9ee5a52d3c5fd460b.nq.gz
    ├── 4b27c82e25b0df3f492979e80cbe62a971255ec2.nq.gz
    ├── 4b3a0b23497a7837d686e8a215296b0f7e6db0e0.nq.gz
    ├── 4b4114a3acc8e25628c37d475327c13b69b09b1d.nq.gz
    ├── 4b58348d9cdad1dab945058e6272dc51358ae0bc.nq.gz
    ├── 4b79bd579cecda10f3a1787443bb604f33e8d9f3.nq.gz
    ├── 4ba5008a614aa53a9ad4c846242d120de4796246.nq.gz
    ├── 4ce377045cbc5d7c0e640ba142a1c90bb1632399.nq.gz
    ├── 4cf2dfc6b6ffb69c5d3185704e54159e0b98f7bf.nq.gz
    ├── 4e77190be765784adf7e9f986400737b281aae31.nq.gz
    ├── 4eae5b01246634fedecc6c3dc3b4b7f49317c582.nq.gz
    ├── 4ec47904782707b2ef3be887e4b355e59cfd1991.nq.gz
    ├── 4f3d6d05e11cccc16b39dd09d574102cc8b7a093.nq.gz
    ├── 4f429614708163491b519e35c982c230fe7fdce6.nq.gz
    ├── 50182aa0d468d1ae179c94f6f17123600e832242.nq.gz
    ├── 50bca656b75ad030cf0a5fed6c913216010b6bda.nq.gz
    ├── 51b1d47b06c7a49b673bd410b88d729eaa872d2b.nq.gz
    ├── 52256039b0ef8a2ca3b6ed3d0691a70bbebbe39c.nq.gz
    ├── 525111dc47c18e2ef56cd577d4abb01a17821d98.nq.gz
    ├── 5514278730c60696fe7a782afba03bfa58c4996b.nq.gz
    ├── 555e05f1942701cf8563f6ac1edc0dfc831ba371.nq.gz
    ├── 557ae00ef2c2b3c6a5791b42530966fe515de57d.nq.gz
    ├── 559fe286efe1f4e214cc88c0b957e97db616c918.nq.gz
    ├── 55da53ea27d4e149b7cdd5479921e525a0e63671.nq.gz
    ├── 563a53161c0c4bf279b40fe1404ad2fc57d7f85c.nq.gz
    ├── 5764659cf9b261e7d8bb76c895f859f8192a218b.nq.gz
    ├── 584e31399854acd9e023393fab0e2877d022d3b6.nq.gz
    ├── 590882ee8bcbe52030e106c3d7cfa123c9063b88.nq.gz
    ├── 591dd116189f294080da42a4ae3f83a99f8a4d3c.nq.gz
    ├── 5a23903028bf864bdcefde148e4aec445e0cacfc.nq.gz
    ├── 5a2dd2e66de2ac7886d2ea7672e3c6d578ee2b8e.nq.gz
    ├── 5ac866469fbe00655e664adc3f75b789fc2f7473.nq.gz
    ├── 5b68bc125aca0ad7095ed12fbdce9d10eb1aeaa9.nq.gz
    ├── 5b6e2b20e90b82fe8d42569aa5701bb6d1e5ed93.nq.gz
    ├── 5b9223fb3e39387f66b82a72ab88aee83c049bf7.nq.gz
    ├── 5d7c7f50ce2b02e3cbca4ad640ba25b37bdba444.nq.gz
    ├── 5e1aafb3cfcb18f31389a4c4268f987aec25fc3b.nq.gz
    ├── 5ea1881c3df60c1a85b97dd78dcd1dcb89f90b3a.nq.gz
    ├── 60bdabfc153d39fc751599f2a28c05d33bb85c3c.nq.gz
    ├── 60e94243ab828326bf3db3a482ed68756a0abe91.nq.gz
    ├── 612369617a9aee36ab16884928f1ad011b2d0099.nq.gz
    ├── 61382810b1f3d67c881503f1e92596e623696212.nq.gz
    ├── 6181e3977cee630f53b8c0fb39bccea4a333cd94.nq.gz
    ├── 61c96b39737901c67cb46cc213a35a1cf0cc78d1.nq.gz
    ├── 633b853c67466217a8bb3fb840f54c963805f20b.nq.gz
    ├── 6466c1f20e3c0db6b352c0fb66459602155ee466.nq.gz
    ├── 647326d5080a11b565aff03ca3dcbe3929d5540c.nq.gz
    ├── 6556e808d2d8c94fd4e8cf9fc00e16c60e24d56e.nq.gz
    ├── 65e74ac6fb2bab2ecd040000ffb9f5180556b81c.nq.gz
    ├── 66a2acd540a3d0ed732e483e00d0e7543c6cbb56.nq.gz
    ├── 66b2161324ad58a6f4f5f6a2dbf79c39f60546c7.nq.gz
    ├── 673a9195b5bb051f44e92fb4e309b491e21e7ad8.nq.gz
    ├── 67d6013dcaf8298e261007d008ac853a00dc94e8.nq.gz
    ├── 6855a81ebf45f2b10dc01755d558187382fe05ce.nq.gz
    ├── 690d16c3084707e9269c36957f4e7cbdaa81c02d.nq.gz
    ├── 69305134bc4d1bacf8b566f72b540b21581b840d.nq.gz
    ├── 693761aa4b6c0a7cde3c0b1d0ba1650f427c21a1.nq.gz
    ├── 69d5f327937ebb3746422bd2a08d7dc58377f286.nq.gz
    ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
    ├── 6ad2461988df0906ca99a1ba449f65447dfc3452.nq.gz
    ├── 6b06240a7e7af6ea49dcd0f84af14a430be91fd0.nq.gz
    ├── 6bd001b9ea9748cc74b6a2fd2bdffca2fba4423a.nq.gz
    ├── 6c0a9993f5b23586da3902f89dd6f02e8f6c7630.nq.gz
    ├── 6c1ccd53421d299e53063e1ba99a27b08503d946.nq.gz
    ├── 6c3207d3a4d295c1d1665dab9e0649a7aca97749.nq.gz
    ├── 6cc5cb825fdf3ef7ab3c30745f87e6be40760495.nq.gz
    ├── 6d5b042fa1a29e4c3194095c67fcb1ea27ed307b.nq.gz
    └── 6d7c6aeeccc77dc5930fb9f5ee45b90ca7eef432.nq.gz

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

[pinecone-io/pinecone-python-client](https://github.com/pinecone-io/pinecone-python-client)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

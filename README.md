# Repolex Knowledge Graph of jupyterhub/repo2docker

RDF knowledge graph data for [jupyterhub/repo2docker](https://github.com/jupyterhub/repo2docker), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/repo2docker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebcc593885cc6a7e344520ca1bb8766242093c8f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ebcc593885cc6a7e344520ca1bb8766242093c8f
│           └── chunk-001.nq.gz
└── blob
    ├── 002d83e0d305ee5dc4c3f5c7ffa7b571e7b07377.nq.gz
    ├── 0056f4c3c939861a133e68a5b2f9e5736185b07f.nq.gz
    ├── 008d046580926f6ffb46cfff161c229e27dddb2c.nq.gz
    ├── 01096cae0c92784a8f49329c82a1016dec04a338.nq.gz
    ├── 012898812be1eaee86b4d68076f7196ae67deae3.nq.gz
    ├── 01dd5c7245b98a7d14649ca1b4c1b0a02c39b809.nq.gz
    ├── 03169a68e5bcffff4c101d7ae0fa94339466a7ce.nq.gz
    ├── 03c14565be4ca5aa0286c6ac00ef527ee5eec5da.nq.gz
    ├── 04adc855be626e56ee2849124494fe9784a2c8d5.nq.gz
    ├── 04af668c480afc296644f53bf7f5e644d8ad653c.nq.gz
    ├── 066b35046620012597f39b64f63e4f6a04fd28e0.nq.gz
    ├── 06d2a7aa8665410843052e490bd177ef85836f41.nq.gz
    ├── 074ea4aaf23c3f814e2f63acf3ee1dcbba5a385e.nq.gz
    ├── 0778a8cbb17a513447295f37bfceffde56137434.nq.gz
    ├── 089e25011b28262ed1bfe8008c732ff06ec94c32.nq.gz
    ├── 0a07edf72ade19b4f6f143177bb1698bc7ae6a2c.nq.gz
    ├── 0aa72fd25d302a2cffafaac8b687f75b86f282ea.nq.gz
    ├── 0acb91d1e8bff04a48599bba628c2edb453e6aa5.nq.gz
    ├── 0b1e69396a1c87fb4eaf0d6993ebedf6cc081a50.nq.gz
    ├── 0d1a43346d9bbc034192dbe3a04c500e68e4711c.nq.gz
    ├── 0dc89813dc10ed07777226c26d348a19ce3afb93.nq.gz
    ├── 0ddd169036d09a4264bfa080b4d1f4b42ea0b925.nq.gz
    ├── 0e704da26bf761a59f3f1480a6e4358e210e7e40.nq.gz
    ├── 0ff935f393fba9d2821b01df8cf0eac0af9ac163.nq.gz
    ├── 105ae8d214830fe112c72a540ae9f16503da2c7c.nq.gz
    ├── 110079abeb14b10c4d755294f8a260b78855a7b1.nq.gz
    ├── 1157007ebed2db718104f78f6a72c2b386f1c7bc.nq.gz
    ├── 120898e48f631e6ed0f454d4c29bcc3aa08b5627.nq.gz
    ├── 1288010a79511da6501602588c54e1994773329b.nq.gz
    ├── 13d4dcd7f90491238154c65aee118986d061e08c.nq.gz
    ├── 14169b1ab2a6dc5e57c11fd4956e1ba5a979fa7c.nq.gz
    ├── 1439a653361e3ffa389f021dccef9e2a2d885d4a.nq.gz
    ├── 152b30475aa1a3b6fa6744f8f1eb4afaba039130.nq.gz
    ├── 17c2f97452bfb19b2d9859216083d6d5fd4cd2ec.nq.gz
    ├── 17db70694bcc9335ffd0fb8272c008446fc96a70.nq.gz
    ├── 182d84b8d4d1bb7a6fc52bcfb8a5959f49feeba0.nq.gz
    ├── 18ce6ffcc021989568a170601f3e2cf38e33edf2.nq.gz
    ├── 18dc78a91bb62c76992ffbb87883049b714f43d0.nq.gz
    ├── 192eba400e4f0b1e242d0c4345d388d5e49b1f85.nq.gz
    ├── 1a2485251c33a70432394c93fb89330ef214bfc9.nq.gz
    ├── 1a9426575c30f3e2b3f2cb73a1d74fd56485db17.nq.gz
    ├── 1aae75bd3d909445d7636764b0856f13618c0999.nq.gz
    ├── 1b2bb0e561bc6eee182442859da92d14fd530521.nq.gz
    ├── 1c58043f0abcaacbb53e396ad14899dd3df27242.nq.gz
    ├── 1ccf1dc28ab67d8ef092a6be820cbb5d02b57e9b.nq.gz
    ├── 1e78c86f42c1c6821bad415c7c458f57301eb139.nq.gz
    ├── 200d036b99d19b55f9ebba5b36a831dfc591600d.nq.gz
    ├── 2105b87ac05839063d6ecd7e839b94db52e072b4.nq.gz
    ├── 21f1d505aa9015cf0af00223b4b8650f2e2cfe2c.nq.gz
    ├── 237f4143f1cf73b41d4dfbfaa6b288dd94f2976e.nq.gz
    ├── 24c486093dab545b41e8046c240730f3dc3cfa27.nq.gz
    ├── 24dd0731987d02bb3dc29bab71101944238660bb.nq.gz
    ├── 255081954564fc43b65cfa52aac964b2e1b11ba9.nq.gz
    ├── 2618fd06e568f52198a73852f5a294d3a0c7a4e4.nq.gz
    ├── 2c9b67cb450a37e00c4cf6ced3bba9e3a987c8d6.nq.gz
    ├── 2e0c7627c9c3dadc9f62630814444df4969c07aa.nq.gz
    ├── 2e738d999244745425058d991d544739296a3f1b.nq.gz
    ├── 2eb2c16b3134b9365eae566ca1f55efe1f7b9645.nq.gz
    ├── 2f5c4d135d90959641a54dcf9109f932556c9c6c.nq.gz
    ├── 2fe0b6f5e8a41f045c4a266271ff043ee97d5dc1.nq.gz
    ├── 3062480211ec902c6078cc80598314955abd8375.nq.gz
    ├── 30e8a6506937c6fc1ae07aa77ff08c55242a2d9a.nq.gz
    ├── 310bddbbffc35b7ec4a5fdf4af919b0c799024a3.nq.gz
    ├── 315cfecfc23aace711cd197f10626b149135108d.nq.gz
    ├── 319f8d5dd4cf5b3d1c963c85c03665eb946d806b.nq.gz
    ├── 332e72525d4a700171f755f8442be6462e0376eb.nq.gz
    ├── 35fc3a8ffa43e9372fcb437a8f1084d04d1c6253.nq.gz
    ├── 36bdb8f2815716d8c504c1a6fd73044d77f53f33.nq.gz
    ├── 36c9868044fdb182da3621e91f99a196a7afc2e6.nq.gz
    ├── 3d7f6eb2392714d8ac434a8d70b96961160e968a.nq.gz
    ├── 3dc7d1aeadfea1e7d68fd7a4c43b9a8160acf58b.nq.gz
    ├── 3f90de46cefbd7f67a5deacea94ee0fad297102d.nq.gz
    ├── 3ff758eab454a9843651df039be4a188c7a27c19.nq.gz
    ├── 40e91a4c312b9e7bfcd2cb71028971e456219f1e.nq.gz
    ├── 4148a7a79d0f80bef730669a646900fa37494320.nq.gz
    ├── 43fd990b5a9c5c6b8e7701380a31eae6c83d40e9.nq.gz
    ├── 447541a77f4033388614f18bc69d4da0fd9db3f5.nq.gz
    ├── 45baf272da4171e4322297b5929d96cb9cd0ff15.nq.gz
    ├── 464fb18e78634b8a5d95329c28e1b962ad4e74c1.nq.gz
    ├── 4698185181857bcf452f4df3977271bcd8b6428f.nq.gz
    ├── 46ca44f253cec4392f7a3bb3ad189221c4cb22a0.nq.gz
    ├── 475dd91f863895957efd4790307bc7f5b9f0e2d0.nq.gz
    ├── 47e3a0dbff210683c2d7c6ff19dde2bcb5ae2b21.nq.gz
    ├── 4854584f59e2350ed636c94c6698229c91789223.nq.gz
    ├── 492446360eb76c21381b40ceefd1f8b355a051e0.nq.gz
    ├── 49bae34dd915c4d6dfc12eaa4b8a28f060dfaee8.nq.gz
    ├── 4b8d2bd188cce17ffbfc6c42fa10151613522e82.nq.gz
    ├── 4c2608798fc8d83163f65911feca83169fd45a0b.nq.gz
    ├── 4c917074698f99d0ce41d3588d8dcb6261cf7edc.nq.gz
    ├── 4d7131e1ebcd7e13564512710b77e09a5d29c471.nq.gz
    ├── 4e9c6ae195fcf52e0d48e63fc7e18b781a251c5f.nq.gz
    ├── 51488e41fea1bacd9fd01d469a7c19d3254e7e8e.nq.gz
    ├── 52ce53d6ea4531b71deef24ced28930f25226ae0.nq.gz
    ├── 530f83977795a9e4f20e97d70a5d12aec254819f.nq.gz
    ├── 548df57857ddf92f67a7faa4d43499443f2415f0.nq.gz
    ├── 552036ea1f15d7f97325526d5039fd9023fdcb3c.nq.gz
    ├── 556191c22c822607ac0fe3096cc341018256546f.nq.gz
    ├── 56933f0598cd80916a6cbe0e1826bd50eaeed2e7.nq.gz
    ├── 574c469a7ae91fe927f475d5bf09a916c0ee31cf.nq.gz
    ├── 576e4a5f39cb0a6610421f1b734e35bc054ad507.nq.gz
    ├── 588c270c4be5af5f6005f3cc3dfdc652a774a0e5.nq.gz
    ├── 58cae5f5b414800aa25967533d6e0049ee80f372.nq.gz
    ├── 597ad82cfae4cbd81b9cac48f013a4d21c1c2c5f.nq.gz
    ├── 59a6441f4ed18dd8e27a0c725eedee738a75c16b.nq.gz
    ├── 5a4e7a38bab8925b8dad4b9c135d7de05ee18a0b.nq.gz
    ├── 5bcf531484c8c1fb2db300bb968dc9681525065b.nq.gz
    ├── 5beccbf12a16141c692c68309ac9efc5bebcaff3.nq.gz
    ├── 5ce045450b61912ae135de125a33e28b9961ed80.nq.gz
    ├── 5e0930f8b34465d15f7f334cec773b76c9e538f7.nq.gz
    ├── 5e880c8bb0a2a0e3f5c7051178572f6d6ea82b79.nq.gz
    ├── 5ef6b572c3025e6486964e0e00aa254036e3657a.nq.gz
    ├── 5ff8a889c18ee42d7f50d5904f130fa42ed31126.nq.gz
    ├── 6227355067e5d5fab62c1c9d6892a3efff7de3e9.nq.gz
    ├── 623b49b4366751b48fc87add12e7d93f7fd6998c.nq.gz
    ├── 62d67f026e2852b99871c5eaf78a032fdf18c162.nq.gz
    ├── 632bcd136eb73a7ed403d382f5880b5bde35cf2f.nq.gz
    ├── 6437c4371511fe306f61bbdf469c7a7757ab5f11.nq.gz
    ├── 64fd9fb38a1493e5bb48510d7ccad26cb64e69db.nq.gz
    ├── 6734d9e27cb2ca264d07dca1e6817a36a214c41c.nq.gz
    ├── 6871e33a21773bcf510e1cd498e21760eebf02c6.nq.gz
    ├── 68b7524e8995d91d079d27a84474067a9bf9ec0b.nq.gz
    ├── 68cb9d7e976a93c7d806b1265b2e5920ae79ecf2.nq.gz
    ├── 69fd79ddad4ecaae60bb347a025851966cca155a.nq.gz
    ├── 6c07946722c2afbf0d515eff742642ea3d829b0e.nq.gz
    ├── 6c351a877fe1cee2ad50370a164294f8c1b4a32f.nq.gz
    ├── 6cbb595e8155d764ec85dac8ddb412574224474c.nq.gz
    ├── 6ce9c25460c794f583d55d102f98d405f14ba23e.nq.gz
    ├── 6d9130610569bcc9151069773c5466f184cec7c1.nq.gz
    ├── 6dbfbfa5a1d29de1d502ff9cf592cd196f2523ff.nq.gz
    ├── 6ef51ead0c47fa07aac7f7d682b7b29f1bed6bac.nq.gz
    ├── 6f137f6156fd9335cf9fd301d927b71d85f8b50a.nq.gz
    ├── 6fdcca7faf752cf152c99fa16da0d98b1987b773.nq.gz
    ├── 7010930da2900fe62636b80636e3a72cb5065aec.nq.gz
    ├── 70127836405d36a4db08b7e3267bdbd4e6d76917.nq.gz
    ├── 70dad53378a06e80f87b297a8b70be18489eb62d.nq.gz
    ├── 711d55663f2955ed756176fd4890b638a22d9538.nq.gz
    ├── 71555b971b5639467a63e8546c337b7e2bbd5031.nq.gz
    ├── 7286bf44fbda5c2c0cf5e8695921cbc429aaef99.nq.gz
    ├── 72e51fd765181b980fb9ab847b99fb48f5a0a36e.nq.gz
    ├── 7482eae470256d63dac5f2078d92ad3b8b72d6b5.nq.gz
    ├── 74bd30f785f93b2411d049cd51b7bb2d90da035d.nq.gz
    ├── 7568000bdf80d2bc3857db35934ed350299bcd6d.nq.gz
    ├── 75a022692654fead76311119a59ce819e78f63f4.nq.gz
    ├── 75b5d89f0e57584a212dce8a9901af3c4f3a0004.nq.gz
    ├── 75f2342da17715badbc7e4517833c49650d52fe4.nq.gz
    ├── 7661a39d7288361c8e7b94635200cd8e55ee6962.nq.gz
    ├── 76cc1cd39f7e746c663e65b5681e4899a2360763.nq.gz
    ├── 78c47c3e903d7fb16aae6b1c6759b9824eed8880.nq.gz
    ├── 7a3f1309c33c5d2682572f019da11fe5f3ac1084.nq.gz
    ├── 7bc55a24db5800b2684218490cddb34438540809.nq.gz
    ├── 7d017db9e0ef7bf6506083431ad56cf55fa24f78.nq.gz
    ├── 7d4d7505953a49c9e117fd6a8cdb5f0f8b2579f2.nq.gz
    ├── 7dd4b7508f4ced376e9a8f139856eb232e6b210c.nq.gz
    ├── 80f73003f4a3985fba0f6983d1c1dd6b8d9e8123.nq.gz
    ├── 813cfc2cc3b22616c8fc8da70909591e8e0c836b.nq.gz
    ├── 815f7d85b0b72202ffd43255c97704a2bf5359bc.nq.gz
    ├── 824f84df361f5eb85c9264375b0cc52ce8044a1e.nq.gz
    ├── 82a29c1bd9f8f0e623462730f961ed6510d5dd44.nq.gz
    ├── 834a0ae9497acc92c49ac960e2668af7ddfd5c6d.nq.gz
    ├── 86564f3648106919ca511d0f60e1b69487fc41c8.nq.gz
    ├── 86971aa8d4b9075b9ee09b5e55594d76040094f6.nq.gz
    ├── 8a64562992cdc34acbe7c376af94d96b56a77ef2.nq.gz
    ├── 8b46f3473c80c9acb85786fd51f1acea622033d4.nq.gz
    ├── 8baa17d8a4bdf02178db327522745dbf11fd37b0.nq.gz
    ├── 8edae569050bdfcd97d22d478b7e6904f1dcdb30.nq.gz
    ├── 8f15b4afd7d98194625e4411e1581785661ddfed.nq.gz
    ├── 905fa4eee661e4496aacabaf56857faf1b88e5f1.nq.gz
    ├── 905fbd8f628101f5f22876eb150bd15a4ad8e480.nq.gz
    ├── 930ed014d4869b65e7804cda1787dfbb1e6b6951.nq.gz
    ├── 933a18ff8acf1908b21b8a20ab55a28c383375e5.nq.gz
    ├── 9348702848344427dc95cd47b97c6fe1aa475043.nq.gz
    ├── 937d6069441136620b8585c9dfff1f0b1339d53a.nq.gz
    ├── 9400a6d9c0a70973bec65d22e5836bd5adc59fe6.nq.gz
    ├── 944ff841bbbbd48c78e17e32f3602bccf36d72ad.nq.gz
    ├── 94af7b1e3931b9a651ea6c96971977a7d7b416bc.nq.gz
    ├── 96417072278052236a7eaf4055b87cc2d3423f83.nq.gz
    ├── 990a193a873d1e19374dc527d23b7237ed26e80e.nq.gz
    ├── 9b8229e465a133d76db6cc152e51604dcd729cfd.nq.gz
    ├── 9be543b5421f73343e7a9ce1c67007b3aacb4647.nq.gz
    ├── 9c9c7381c8858ce4a21b9a472a6197243119138d.nq.gz
    ├── 9e7cbfbfe290626e1ec094a06f230c8af2f0bb6b.nq.gz
    ├── 9ff3d3db8ea44ac0b828086a9f53c0db0066c1bf.nq.gz
    ├── a0a2e019b38e7fb41bd386b057e6640ccb4735ca.nq.gz
    ├── a0a961df66cd48cad3eaff1760d61d55d0289385.nq.gz
    ├── a0bcd5a2f13e3e292c9c712bd68d81763bb0794b.nq.gz
    ├── a116a98844733ac7e538c63f91dac0780307fcf9.nq.gz
    ├── a25b0cdbe672133bf11fd639edd09855a9c732f4.nq.gz
    ├── a2c82b81ce857cf3cbf8f093f9cb9b93e326637f.nq.gz
    ├── a304b59844e6d803607ceec2663c76bd56d1a028.nq.gz
    ├── a35c300c1dff2cc5df8f32a7d25e11b7124b3663.nq.gz
    ├── a3e44b5c595020c2766cf0c4a0e4a4c88afd935f.nq.gz
    ├── a441893da18d4742da45a1be6b43b4db88186957.nq.gz
    ├── a46bedeb6be6e246d5f69ebc6f9a79ad5a5e7c5c.nq.gz
    ├── a57181976835f7122f92c4af69f81c87d0922f45.nq.gz
    ├── a63e8d622eff86c95f630730cb627ce187c7caec.nq.gz
    ├── a746447c1dd5d4dc1b9d82a2f98341af2d15c679.nq.gz
    ├── a75604c4671d63775520db1fbf03f0488f8e5983.nq.gz
    └── a7697a246c826ef4a2088fb1fc45f7f2c32cdcde.nq.gz

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

[jupyterhub/repo2docker](https://github.com/jupyterhub/repo2docker)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

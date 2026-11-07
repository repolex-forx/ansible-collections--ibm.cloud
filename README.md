# Repolex Knowledge Graph of ansible-collections/ibm.cloud

RDF knowledge graph data for [ansible-collections/ibm.cloud](https://github.com/ansible-collections/ibm.cloud), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ibm.cloud
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5d94fa34a025798cdaf43fade3fead00f780743e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5d94fa34a025798cdaf43fade3fead00f780743e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0328e9a095f862f0cec3ff59bd0289bd401ca914.nq.gz
│   ├── 052dfda15f690ae6e2dea217fa34560577265ad5.nq.gz
│   ├── 065070d44e0554d18788b68a12c91bedd1404009.nq.gz
│   ├── 06ebc5d55fedb8571adc571b5d849b256ea0c507.nq.gz
│   ├── 06ffe5b4ea09df695d1673cc1091541f94b802d2.nq.gz
│   ├── 09ca7630fa265bc8720e34e9501dbf18feb6f1fe.nq.gz
│   ├── 0ac680fecaa231ad311a514e3a0e08955fabe638.nq.gz
│   ├── 0c3914e4be96fa8e47d949fb3dba16afb4ac0e55.nq.gz
│   ├── 0cab5fa8f8180b56ad58f4bc5f979491a601aa62.nq.gz
│   ├── 0d3e254688b67b35e667ded02af9db3a931a01b1.nq.gz
│   ├── 0f5550c27b8e2d369a5f82be9f6e27c1a81a5888.nq.gz
│   ├── 10abe0de5e3c30638f81ebed7913b680264e9a26.nq.gz
│   ├── 11c400e100c702cf6d7d6dcb1351de6183181f99.nq.gz
│   ├── 16f2e2bbb0794f8231841d3ac58ba5bfbb54d0b6.nq.gz
│   ├── 176f9421d16136aa2a03393b26c4ae7030ebd2a6.nq.gz
│   ├── 182e6b851b532effb94fefc3cccced1a833962a2.nq.gz
│   ├── 1940c1fe3cb9a9806f907cfb3ac21c993991efa0.nq.gz
│   ├── 1ac003bb924b5f7721d5e5ff7814283cd09675df.nq.gz
│   ├── 1b6f3c7483596b953060ef8f2a54388babbd2de2.nq.gz
│   ├── 1de8e4ac783407b39e38d2225b80721c441a369a.nq.gz
│   ├── 1f35853e4afa1ebcdb733251ed9bb45fa3a087fd.nq.gz
│   ├── 222570b362e127444bcf3ddb2b9ee4e14220cd90.nq.gz
│   ├── 22d0a7dcb9b1da85290bf59f1cd4a8d64b788925.nq.gz
│   ├── 24476ba737a64ad3f379f88fda1887982ba20794.nq.gz
│   ├── 24e2b8ecb5b7feb0366e56ece92c1c50fc9cfb68.nq.gz
│   ├── 2817172825ffd186c900e0fda2365833170fe781.nq.gz
│   ├── 2832420566c686641333555a23d1df07853e2930.nq.gz
│   ├── 28cbbdf8e4fbd5832d4a66d190cf28e738aca573.nq.gz
│   ├── 2a75881fc7d27d7a41740c80ee854c4df3d9fe87.nq.gz
│   ├── 2ac44d085a4856fa27c0fa5a97f4b570a8d985a5.nq.gz
│   ├── 2cb864b615a218709b230579c322a6fd6a1e3293.nq.gz
│   ├── 2da66f158a3b11b06531b9ec883d86356f58a097.nq.gz
│   ├── 2ed662d3d4b82c74edebe7cc113b1f79ca339617.nq.gz
│   ├── 2f8c05e5eef2b0dd82db0bdb12b9e9bf91c787c7.nq.gz
│   ├── 30335ec406de4e2047b20b27364c8da0943223aa.nq.gz
│   ├── 308501ed94426860ab2473e8e6cea1b9e3f69728.nq.gz
│   ├── 30c436b582efe40486a8bc68b3a4c5d7844d1695.nq.gz
│   ├── 3106822778d057e02978f6a75ea5af73ac54afc0.nq.gz
│   ├── 329ba934e60adb4926ddd6cf028bf6cc42d4e1c2.nq.gz
│   ├── 335002b063eec1d5a6dea4737614bfe55ea4d928.nq.gz
│   ├── 358c0d0950f225736012a15b1d80b976459cff29.nq.gz
│   ├── 38030ff05a60cafaf2ea7ca8c87805a8b3dac2b9.nq.gz
│   ├── 3a5781074613cec7671de756b585685c51ebe58f.nq.gz
│   ├── 3ac7b9824f1a067a999ade146200bbe38c8ea758.nq.gz
│   ├── 3b284cde3bc7f7e6dcd21edd9fa750f2e99548c0.nq.gz
│   ├── 3ffbd7eac6a3463ec05df415194a651b12c891e7.nq.gz
│   ├── 41d3d2f8513aa621dd1242345949237b14b9e778.nq.gz
│   ├── 42746324e1c9260aaaeb92d5c68d7bfef90a128f.nq.gz
│   ├── 4305ba014a3538134f16d21f239ab53db3a5e5d5.nq.gz
│   ├── 432a57ebd21e29a078fa1f0ff7065912398ac61b.nq.gz
│   ├── 4333606f35d62dfd76972e6f1de64c4f315c7d80.nq.gz
│   ├── 43e9ed75bcaddd0535f6eaf3e8f2526af7eb8f5e.nq.gz
│   ├── 460bbaf818798b38db10b809760cc486b4992da4.nq.gz
│   ├── 461941b08bf09175d5bf661158b6ca3e84794bf6.nq.gz
│   ├── 462c9894bb4f8b6d003e14fa63e64cca4f82736a.nq.gz
│   ├── 4642880b9ccdde9a5b235c8064129bb7007af809.nq.gz
│   ├── 46e6bdf092e0f9e85c8283c1cfceddd5bfb33320.nq.gz
│   ├── 475e1cccbd1227fd1f67c936778348c9ea329cc4.nq.gz
│   ├── 4b636e566145e72c4349cce8c52f4476250c48fc.nq.gz
│   ├── 4c38fb2a993baf462656f2df11e74e71dfd39982.nq.gz
│   ├── 4decf830701300c668d1d7258b0c8d90e725d403.nq.gz
│   ├── 55ddff4e8b4d2c0d179414299f5580630766740c.nq.gz
│   ├── 5793411f0f31281e7e0a9b140a7d705e0af5be28.nq.gz
│   ├── 5b73ff70e5b5e90b2bc2062d3c7b32b2231f0503.nq.gz
│   ├── 5bedaa2cc96e9e1070e41469c8d7e80fe60a6c11.nq.gz
│   ├── 5f5f345cb143ac24014f77e08ca3100bc830db8b.nq.gz
│   ├── 61bc3f60aa49505b5d02b45c528f0afd5f324e4e.nq.gz
│   ├── 645923cbe42db55bb85601be264fd055ab678dde.nq.gz
│   ├── 6568c46088c233126d66a6675cd3487049762c67.nq.gz
│   ├── 657187a874c353e3fe4d3d16efc47d8f29451c7c.nq.gz
│   ├── 67d8a82df21a5aca72f7c06ce650df5c650e39b1.nq.gz
│   ├── 699bc788aafff4181e8b4ccd2c15361bf73bfbbc.nq.gz
│   ├── 6b2a3484aacf42ee1b40660bcade1e8369ab610c.nq.gz
│   ├── 6be6a18736544718e6c91c22c6c2ca4e7c3706ed.nq.gz
│   ├── 6bf16cef22115343c03a8cc7712b657402e83cc5.nq.gz
│   ├── 7060483e9e3c4433e028f46b1ae9ae294a1e5f69.nq.gz
│   ├── 72cddcdec3c754b55adb39dab74eee3bc75b34f3.nq.gz
│   ├── 7356d2f35a6f8210830d54fa70093866801b33bf.nq.gz
│   ├── 78771ae73b89a25a5f5ed8033d23e62cddd6a429.nq.gz
│   ├── 79a2d1a8a96a67cf76811ac74bc0f00f3f16df10.nq.gz
│   ├── 7d54190e53c6b76604efc50a1f592b2ec6383fee.nq.gz
│   ├── 82d4552ee6580ddf865256aa00742cca26ce4f4d.nq.gz
│   ├── 8366895e191d5704337f645b1b3574d7c41e0763.nq.gz
│   ├── 869f2f20000385ee0dfe582b6b7fb90e680e5b1f.nq.gz
│   ├── 87fed71657c3a929c6b907463dcc41fd7acfd005.nq.gz
│   ├── 89f3ebe780d355d9fd92fb02fc3d2bc739da8439.nq.gz
│   ├── 8a8bdd1ebaedfb380f01ef136b061fa34bfd68b3.nq.gz
│   ├── 8baf47d191c12b5c975c0961defd6ecaba488463.nq.gz
│   ├── 8bf2269d60ea4a4de3e6ff5d6509b6e0600b1e3e.nq.gz
│   ├── 90d0c88a230ed008964c48e0053b17b169a7bf2a.nq.gz
│   ├── 90ea776db1474d7aeea004766ff7c8a0559edfce.nq.gz
│   ├── 93bd186910e317bda91f514a671ce1a6167aa0f4.nq.gz
│   ├── 9427bd22a653310717797e15afedaf29ae2bac3c.nq.gz
│   ├── 972f377fdfd0837bdf2c1aa1fc4b3c327dfbc3e4.nq.gz
│   ├── 989d6e572531611c1c3bc359ae9af5bb0afaa32c.nq.gz
│   ├── 98acb641a025a8db61b974394a67dcb645f2de3d.nq.gz
│   ├── 98b54cdbbbc68892f7ecc62b46df6547b06358d6.nq.gz
│   ├── 990eb34699e7bfb8a6ce0b63a0a877f412eb6eb1.nq.gz
│   ├── 9e2f255aaaa903b4689cdc406dcdf477bed3b3e7.nq.gz
│   ├── 9eb58e2713e56bb63e033cbb7a4a5d8c1c000e35.nq.gz
│   ├── a0072598e1f27fe2591dfe2aa87855e4a720de20.nq.gz
│   ├── a14dd1a164822a72859d407f9d0663e7cd7872b3.nq.gz
│   ├── a156ce6f782092c1f259f1463409b0dfa12e9103.nq.gz
│   ├── a1f9bd4e15f7aaaaf3785529d0c67b8677e9384d.nq.gz
│   ├── a65a1e3a33b4dcd0ed0540b65865d59e803f6b7d.nq.gz
│   ├── a701a60dc8ce3466cf486300613df553c57ed71d.nq.gz
│   ├── a8f2df2d04694872d866854ab91a4c61aadf4913.nq.gz
│   ├── abdea2efa947528f9e0a5f160ebefcba350924b3.nq.gz
│   ├── adcb0aab0663a65b3c3c72a9246efd496881689c.nq.gz
│   ├── aed14da130c60b984baaa66201ffd75e15031d87.nq.gz
│   ├── b0b61ba17988526231a61b2a3ea7274e4d228ffe.nq.gz
│   ├── b0edc8538b916c817b447832d6d249b4cdcbe367.nq.gz
│   ├── b1287fbb90208e879348415ea7be53feafadee80.nq.gz
│   ├── b25ab66402f646a63329c5e04fdcae5a50742168.nq.gz
│   ├── b4e8cd2c4fe3eee9e4cd9368d74e0fb23200fcd9.nq.gz
│   ├── b66e4224b7bee60a46607fd710c113d14f681190.nq.gz
│   ├── b957bb317a73774b172ebd83addee7b36f3328d6.nq.gz
│   ├── c0bdabd9c1442ab89ff8aa33b1f2e457ebbdc12d.nq.gz
│   ├── c16318351e0c360d9b0e92246fa4089c221f52c1.nq.gz
│   ├── c2740763c6e60b2c82b75504bba95315edbc216d.nq.gz
│   ├── c3b683916f32bdb5a403c1665dfbd9ef97fc2789.nq.gz
│   ├── c4a47df2403509c983f8c9c5fa8fc4089ee148b9.nq.gz
│   ├── c4f7637dfe968574a2c175853345f342ba5ba079.nq.gz
│   ├── c5f9bbf519ccbc93ec77ba6932a22a0e3797fba6.nq.gz
│   ├── c75e8ecfbec5498666e5b454ee9493ae63ae9baf.nq.gz
│   ├── c87d7dde71643bb4eb61389323ead77d5268ad40.nq.gz
│   ├── cbb573d4793a8690c652b1b9d10ca2d6549ae31f.nq.gz
│   ├── cbd76985c8d80294cb4d80ed31e450436ee8a464.nq.gz
│   ├── cdc1eecfb6d69d1e9df05a7f073d78cd500cc4f2.nq.gz
│   ├── cea48a7dce9c36e6482d64c5a2d8ba994efde612.nq.gz
│   ├── cf56f0f92dea79ff12da6f86e3d4dfdf7bb80adc.nq.gz
│   ├── d142111aa3c5a1636ccb62ed71543f21b6410f83.nq.gz
│   ├── d294d26d20df23a3af6c690cbc09cfd107252153.nq.gz
│   ├── d4667b47953bd87950f771449ac13212f0dc3c15.nq.gz
│   ├── d51d2bbc3e04bb5c3bfd3c2f03445ba91c08454a.nq.gz
│   ├── d8516b3cfadbfe00c1befbe633677e5bafa6da68.nq.gz
│   ├── d9cc6623f2b88f58fe0b2943533d1fee1cf81c17.nq.gz
│   ├── da2d5cee079a3c887e131650bec1fa1f4ade5312.nq.gz
│   ├── daa7e57e4f99a5ef9c5ed1473436769ff2984b73.nq.gz
│   ├── dbac37440ddae472cc96068387b763453c4dc994.nq.gz
│   ├── dc2c629c13cf3e34d6d94908ac9aff09f4ca43ea.nq.gz
│   ├── dd3178785fd5b54b3cb1d1d622ee114e9e4d0f93.nq.gz
│   ├── df3ed53fd6c3dd77e14db33b8a09b40abd0539e4.nq.gz
│   ├── dfbf10676323244cb6fabd00aa501f0e43837803.nq.gz
│   ├── e01d494db454aeb1e53215b02a2213e085fb6af8.nq.gz
│   ├── e1cdc0c994beb84b5b4597a8a03bedda3638f025.nq.gz
│   ├── e240a5f7239a80e00b2c3785012e13dac1bbaddc.nq.gz
│   ├── e25b5600492105e0d986ebdacc8ae2d81fe35d28.nq.gz
│   ├── e2653c014790feb7a49fd4387b0401fd85ddb571.nq.gz
│   ├── e4a7cb21b1a30faa379072ca94e114b991271b87.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78bc8fc966b37eaf005c07c9a89aef7611d5c33.nq.gz
│   ├── e7a7c6c34fe6d91a1c7cc90dd53968a7fd3d8cfb.nq.gz
│   ├── ebbff28ea4dcdc0cbf376c6f42b0171c7e1ad380.nq.gz
│   ├── ece2ae51eea5987dbe3ada01cc197b20a02457fe.nq.gz
│   ├── ed5de94ccdf1756039bef4fb047ca12de796a036.nq.gz
│   ├── f21f8fbd878f17a65f7d1e83362ae80857fe4be1.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f2e5242c22f0820e93fe3d7aa23fa7aaecbe18c1.nq.gz
│   ├── f42641f2cbb11ac42414716d7668ab935bf43dfe.nq.gz
│   ├── f60c84073e6b410c582a665be0b81c8394aeb65c.nq.gz
│   ├── f64e4bf9adf3ffc136792ae4c4f99123c176f483.nq.gz
│   ├── f97516f5c5298499ac54a74b9e003522845fdb9a.nq.gz
│   ├── fe6610f51a0811e77e62cf34b58be013148462b9.nq.gz
│   └── fe6940344ca54108c40eff1262a5b0ecc611779d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5d94fa34a025798cdaf43fade3fead00f780743e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 173 files
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

[ansible-collections/ibm.cloud](https://github.com/ansible-collections/ibm.cloud)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

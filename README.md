# Repolex Knowledge Graph of trentm/python-markdown2

RDF knowledge graph data for [trentm/python-markdown2](https://github.com/trentm/python-markdown2), parsed by [repolex](https://repolex.ai).

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
rlex download trentm/python-markdown2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ea342a56bf43f96e0c045da63e550cef7083f3f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0ea342a56bf43f96e0c045da63e550cef7083f3f
│           └── chunk-001.nq.gz
└── blob
    ├── 0019958fa1da0d2e378675c782e944e2a8dff801.nq.gz
    ├── 0051a940f3e77d0f093748ba099fa09e16667313.nq.gz
    ├── 00b84fb2f03b1b1a08e203c6d4b4117587aa3d61.nq.gz
    ├── 00ce93c083b641cc74ae305812296e951eb5fa22.nq.gz
    ├── 0184518849579fb632a5763389202a8e4c6545f9.nq.gz
    ├── 02abe816b31ebd125991a44a893befff54a897b5.nq.gz
    ├── 041d79eb98c9f323c1815fc6f728c445e980b74b.nq.gz
    ├── 0489efa0161906db7a89945b6af922f398f99078.nq.gz
    ├── 048a3b6054edcb8957628aed49199d6a4e260c43.nq.gz
    ├── 0491729843b569d66997d5d393c96059a4f48ece.nq.gz
    ├── 049e01207cadd2f0135e82077a89f1c1b0974263.nq.gz
    ├── 04cb6c6ffea67a416a6bac250dcbcd17db52ba90.nq.gz
    ├── 04e375328ec91174023a8cf1e090ff24636b03c3.nq.gz
    ├── 06b0bcd5cdec27dcfa79b732eb817919dcad42d4.nq.gz
    ├── 06cb210932f41f091fa8a292218e45217a13f6cd.nq.gz
    ├── 071cb10651ddaf971d1fa113acd18e5758ce3c6d.nq.gz
    ├── 0722751dc049d8ecfd4e1ebbfa55a9cf6c53f7ff.nq.gz
    ├── 07b59223e084794031444a6a1c278b7f3c3ec1c0.nq.gz
    ├── 0820b079fd9a92e99287dade0abcc77e7f1c6f88.nq.gz
    ├── 0828870345f07e37d66eeb0c0f575b6750445504.nq.gz
    ├── 085df948cd567c2f43c0ce3b450dcc9cffbadca5.nq.gz
    ├── 087487996ca367ae34ed4b3f9d2654441305e5f2.nq.gz
    ├── 08eff55f8d2629c1e1640424507586f693e733f9.nq.gz
    ├── 09c72e5fc0fe0548845600a38d7543fb1222472d.nq.gz
    ├── 0a8c7de0ba1a1bb8bbde6d6ed01aa69a2e580941.nq.gz
    ├── 0b5527a43b2a184fa513dd7ca2e0de70fd95c1c3.nq.gz
    ├── 0b671943abf22160999a401df49b32fd4296f184.nq.gz
    ├── 0ba15907bee66b225f6e7f20b19221e37f282344.nq.gz
    ├── 0c08c854dad01e5c95acc43ca7c07fd93cb959c2.nq.gz
    ├── 0cb14c698acd5bf51c362d6c6f289f3e51a87ee3.nq.gz
    ├── 0d02e32b995bad301ab32f3f8f0aa5655863214a.nq.gz
    ├── 0e9527f9311d129ac9ae5bca7666f37c3dfcfb59.nq.gz
    ├── 0e99f6d7354c69ef1e589d9c05e852747e164422.nq.gz
    ├── 0ed4c9844d6d991a11e250dbd9b560c824b131f7.nq.gz
    ├── 0f59d311dab82c39de24edc4dbc01d902c5d6b0b.nq.gz
    ├── 0f649fe418b1d0a3dc0129bca39c62650e7d098d.nq.gz
    ├── 0fe946d74aa1d5a1173dd4723a559ed411e39008.nq.gz
    ├── 10ddfe7784c0c749ac61fff5570ce22e4f6136a7.nq.gz
    ├── 1128d4bffcd2341b4debe9c35b779b4c25443a91.nq.gz
    ├── 11793ccde2ec59ea59567698b37ce981b4605133.nq.gz
    ├── 11c6c16cc1654144b468c4d00b8cd97ccf43ed56.nq.gz
    ├── 12bca88cfdb333d767bdb7a2f2187bdbb9369483.nq.gz
    ├── 12dde3db3856592e9ef2104e1651e82ea4cea28c.nq.gz
    ├── 13cde378506afda24db784cc24127822d052e11f.nq.gz
    ├── 142dbdc09d22e77ba38a62c76d1784963ca020c4.nq.gz
    ├── 145a53056de9d818a74bdd1fcc6ecf5189e7e244.nq.gz
    ├── 14aa2dc272d0a056c71049fb4ff80d54d36f9adb.nq.gz
    ├── 14fb92914f505af39467acfac4749da2847fea15.nq.gz
    ├── 1594bda27b4130726fd43d0aa1f3ede6487d1905.nq.gz
    ├── 15e4c876658857d20feda5c78070e251e8ee04ab.nq.gz
    ├── 16447a010b1601e51952da95d39da8f56ea37f4b.nq.gz
    ├── 1866a391610d6fc2aba6fffe3a860bdee5e0628d.nq.gz
    ├── 19028bb3e731ec3197e02b633154344c7a971f56.nq.gz
    ├── 192afdc22ad775ff9cdf26100297da2c267a403c.nq.gz
    ├── 19348b63be92e384eb565b16ca39119c9f3673f6.nq.gz
    ├── 1a01c5760ec7c86ff0dd716a0563d4e2602d44dd.nq.gz
    ├── 1a045d70a6f952fb4a05896a259cf10f784fc7bb.nq.gz
    ├── 1a5c991a992db408ff8c56f6aee2242853342809.nq.gz
    ├── 1a69c5b79643448abd37f649263a4a48ddf5cdbe.nq.gz
    ├── 1acd167cb945b7246f02fdb9a08a88e8897ce5b6.nq.gz
    ├── 1b1af008b9967080209f021f4ed3dc39ab63bf1a.nq.gz
    ├── 1b3c4e74867224dc2fbccaacbe8694b2503bbd81.nq.gz
    ├── 1b5b65e6700d28fb7e8a3b48c14df1fdf0e8afb0.nq.gz
    ├── 1c1d31cb43d23e6e126c32631647c0188ceb1b95.nq.gz
    ├── 1cb7dfb9785da8493ffd1971511b9e522618bad5.nq.gz
    ├── 1d404e517d39086f2927cd6ccab6799e9711acf3.nq.gz
    ├── 1d4e5d13bb287d10ae3d6ef3c8a756fc971b93fc.nq.gz
    ├── 1db0c71fdcef35b860471f81e9d6d31fc4115c0a.nq.gz
    ├── 1eb54502db5611c47a8b729444dc959430a9654b.nq.gz
    ├── 1fde0000f81ef3320bf989efc7d658e68bf156a4.nq.gz
    ├── 20052b218f70c70aae3a67d3c06d76e8fe8bbad9.nq.gz
    ├── 20e6b84e6b574dabb00760d7b3659f47efc7ca98.nq.gz
    ├── 217f6855c11b93b0b0018cac7d0d655224df7110.nq.gz
    ├── 2212112658de7c1868154638f42e397b84c395cd.nq.gz
    ├── 223862cf0c8aa1aa5b38a2cc1d550e94cd6621e4.nq.gz
    ├── 2253902579f1b1e9ec3fa0827c4b507f3ae12833.nq.gz
    ├── 230ba98dd6cda52f9fb4ba71b172d7b030d05035.nq.gz
    ├── 2322f854ee6b74d38bb017f314ea5e6f729fd12f.nq.gz
    ├── 23983798e535ac02741f95029b39d7993a44642f.nq.gz
    ├── 23abc3a5ae9ec33978ea93d6be6047f447ab67a8.nq.gz
    ├── 23f10c5515e338853eb9679a27baf82a7b4dfc9d.nq.gz
    ├── 245e9828655ff2f22def8fcdf21f236e18204f6d.nq.gz
    ├── 246b60d1cfd167562355bc5f51bff2d75384172a.nq.gz
    ├── 2595ca93a1c3b83bede0e5105434384240eca25e.nq.gz
    ├── 25fea79ffb191c891257c258ce28f481b1c4a40f.nq.gz
    ├── 261151cdb17305b83cc11eefc8a3690a71fc5370.nq.gz
    ├── 263b6963be90864b7e837e458a7f629630745d39.nq.gz
    ├── 270c2eef32bcbcbff7eb1580eef924706f437770.nq.gz
    ├── 2858ead556b146b636b9f24445559f7392aca7a7.nq.gz
    ├── 2913a414183b08b00546b724e291d1b888ef056c.nq.gz
    ├── 29868b8d1b31d6cdd70a4a29eebf764491c5cf7c.nq.gz
    ├── 29d0e4235b22ad19bbdf2b6a4094722d0545cf03.nq.gz
    ├── 2a11cef3ba3be64094cc64d067262aba5621a61f.nq.gz
    ├── 2a8221f1aa9173e0aebaf1d508a048bc13e5337b.nq.gz
    ├── 2a9e5215d808c5f3cfef5469ad217218e7bc0d7a.nq.gz
    ├── 2b2472e05919f1ed6580305c5ae089e45ebd28a0.nq.gz
    ├── 2b2e0cd03b68f0f795c42c33d4856422b4a84568.nq.gz
    ├── 2c03fb5dd63b222a541900a9fdeec8b84900d982.nq.gz
    ├── 2c4e0f5ab82ad211800765b76cd10e005e85a89c.nq.gz
    ├── 2c8a9047e2396f8a29a065c1ea45ec7827b9f31a.nq.gz
    ├── 2c8e3b33bf2dd3a6d230c6a99753a50757eb80c2.nq.gz
    ├── 2cb17b6a121d497cd9733f74a0382dd44f0bde68.nq.gz
    ├── 2d05ab8c2590eaf21c5b0286658cae518822fac8.nq.gz
    ├── 2d2444838b4812d90269ad655ee8106816681055.nq.gz
    ├── 2d54c660dce872c8dff882150a3dcbe7a336031f.nq.gz
    ├── 2dbfcc85f180a7c91dc7f418c53005a075228291.nq.gz
    ├── 2deeb86d44ded66e0b318b2a5502fac146a42ebf.nq.gz
    ├── 2e2943ee2af828583c9ab279812f048c5f9a5d68.nq.gz
    ├── 2f97201baaf26573f9f42bb5106d334756d5f652.nq.gz
    ├── 2fb75ddad6a55515e4077c0ccbf6a3716ac2c08c.nq.gz
    ├── 3016199a335408217b84ca6f3e168569a020a993.nq.gz
    ├── 30ca3091c820487254b47606c9aab9bebd984ffe.nq.gz
    ├── 32486da1c377058d79a0ed8f904460a798eb6f98.nq.gz
    ├── 33336c869b0fe202bd71feb73fddcaa4b5dc656d.nq.gz
    ├── 346d99f47e1547b3e6227368e1173d76de208f62.nq.gz
    ├── 34a6a5cbfb320aea700a0630fe2e1fc94bf674aa.nq.gz
    ├── 34f629a6905219f4509721743ea9d519f8cc3031.nq.gz
    ├── 3548642ddd6b0d4d39f6c82351c5971cacfa33b1.nq.gz
    ├── 3583b5b0a75b62db429b62b80b94c7bb4b8d2d26.nq.gz
    ├── 362500d5d18f71da74d24a4387462163c60a4fc2.nq.gz
    ├── 365470ef526265a888354b9caa9a977120b62973.nq.gz
    ├── 3696712ad807295ec281d9237c1e121cad80017d.nq.gz
    ├── 376343232907eb13bf7e7ecca563981a5a14f68e.nq.gz
    ├── 37b4e48a2113d137e8d1009172b51532d4f6062b.nq.gz
    ├── 37c61c98976bc84e306469d772bb18fb1af05267.nq.gz
    ├── 38b8bfe832f871d2a3b4439921882a131678fbd3.nq.gz
    ├── 38cb2b5b7c7af17a2fa72507795c4ee0aca79cc1.nq.gz
    ├── 39235f2817f391e0ba06948b2f6ee21d30ae2ddb.nq.gz
    ├── 39a50b8c2df9c04e0a09f9fc865c857e224de322.nq.gz
    ├── 3ac0deb3f59b343fe59862b900a4dcbb0ba03013.nq.gz
    ├── 3b1054eab98207430873102df8455a88d41f76b0.nq.gz
    ├── 3b392f62db64ca64144c7666265ecf55a4e68eae.nq.gz
    ├── 3bba05786edd51c1f3b30b87c3c70c6847e9795f.nq.gz
    ├── 3bcecaa35150d9425dafe04fe407ccd8abe2ed1c.nq.gz
    ├── 3bdf62cb6053bc129576e3a41d6409164814c217.nq.gz
    ├── 3d584a214039c1386680369bce5ae4c9485a7845.nq.gz
    ├── 3d62b11d7ae120e8e8364c1ff3ea2ced6cc1d255.nq.gz
    ├── 3da78cd0581bf2d45b44ab03746bac29f0827a6d.nq.gz
    ├── 3dfa9b10c49708418c6897ea7fea89d6364569d7.nq.gz
    ├── 3fa24c31dfa5e4634973282df0dd5410b82b5446.nq.gz
    ├── 3ffdbc0673bfb760d5ba748236c91682be4cf8a6.nq.gz
    ├── 400d2eb94457a18e5ef4f8cc56f858b696200983.nq.gz
    ├── 40cd465c6fd885ca61fe8b286f20971c66a99205.nq.gz
    ├── 410261beb80aa1686888bd697854aa586b4ad56d.nq.gz
    ├── 4131fbb8e2c6feae3dab7e99aa14c515fa488e44.nq.gz
    ├── 4136c90416d4b5f9c6d3b84eb7f130c213b44cd7.nq.gz
    ├── 41d830d0385feec59a07b3476dedd68ef52749c6.nq.gz
    ├── 41e024161f183f97262a96b9e555e91c5b0d0de5.nq.gz
    ├── 426b305892fbfcd9833a96dde86bfd20cad26647.nq.gz
    ├── 43e018913110dab4fa98e76855f0f0ee64993dce.nq.gz
    ├── 43f2bcfd56a4acbfaa97874dae2eabd7be696189.nq.gz
    ├── 4494a0aca4effd95fc2747c1def58040a426fc92.nq.gz
    ├── 44e237fc55589add8d0fa0b74c2fd67d09b47cd7.nq.gz
    ├── 44e68784f56bdd63e969ec278f4842f63ab5c9c7.nq.gz
    ├── 456340a941a35a76e01b783abeca1e04ea00e85e.nq.gz
    ├── 462861e6fa6984e0750dc6733a88b1cba89d371b.nq.gz
    ├── 4661b66023e56eaa1437e2363a92e2e8e26532a5.nq.gz
    ├── 46b22d254f926c8f683639a9a7197967492cca6e.nq.gz
    ├── 46fef954862323a882611ea5dfba0eef226415e3.nq.gz
    ├── 474078602db19a9d0f880813601fbcaa9c40c6fa.nq.gz
    ├── 48543ba1fb646ef6022e71e97bb5bd8ef3b1cebb.nq.gz
    ├── 486055ca7f8d48fa9498b43b12363c91acd01c91.nq.gz
    ├── 492e308caf720ace214bc75b822b976fe228778f.nq.gz
    ├── 49bb9474c1bb1d105232710c54d376aba2b046b4.nq.gz
    ├── 4ab848ae8f26bf2c5fe119a8e1e81d9c149b43d6.nq.gz
    ├── 4ae802a06e005f9ce32c8e5ac934d1b2e57d7b6e.nq.gz
    ├── 4bcd10efafa3e393ebb1096f96a99931ec9511f5.nq.gz
    ├── 4bf350c23b894351caf832b938d9b5d97c4a3f31.nq.gz
    ├── 4cacc5799f68e5829663e7986c524c2ea79cb3cd.nq.gz
    ├── 4cbd41b4f0ed76f3fea400ad979eccadfdcc04f5.nq.gz
    ├── 4d0c1c2621047ffd674fcb9b879a8653fc813662.nq.gz
    ├── 4d8e8fcd679e05858722148699bb04ed0d5c3438.nq.gz
    ├── 4df8c01e0052c0f41bda852d6202b68ef502a600.nq.gz
    ├── 4ecb87e549ad5cd5ceea88965cd710595fba2465.nq.gz
    ├── 4f32e25a41a65fea3247db327cdefe7fa6a66e69.nq.gz
    ├── 4fe21c04b00eb8064dff7f34bc182e0bdc471cbc.nq.gz
    ├── 512c61195ef6709658f661bca4b2b1c05a76abb9.nq.gz
    ├── 51fe5df8f2200195f0017881d474624d549c9b3f.nq.gz
    ├── 52773661b51eff68863c0114351857846f086b55.nq.gz
    ├── 52d480cffd3cd45c6e3f8297af78cc7b1979c067.nq.gz
    ├── 52f81fdca9aec5bd41e144ee3af8b693201359a6.nq.gz
    ├── 5343eda3d674b5acaef95f221324ff8744c3cd44.nq.gz
    ├── 535a2cd8c8785c0581c5b72e4df918e0a907c716.nq.gz
    ├── 53a34fa207b711e6fd58af8243b9aa1d806e27b4.nq.gz
    ├── 53a4d03d245a5c9e360b82ffd65e16c8b4485a32.nq.gz
    ├── 54123d1f7690441b565b8a4df67e4cbfd230287c.nq.gz
    ├── 54de31a829456c297778d4ed3c1354a2c8e4d2b6.nq.gz
    ├── 551c08a5d19ab12460be0e294fcff18a0a240689.nq.gz
    ├── 56aaad75a3a8a35d36db3b7f250a339d845f9ace.nq.gz
    ├── 5722f05c9e9499ca5dfd99c9229b1ed7506fad73.nq.gz
    ├── 5831ff1297f75b8620208119c027125859496f72.nq.gz
    ├── 589d1136e19c0b56dcb6731e8a6c53ae0cedc9a3.nq.gz
    ├── 58ae3e0d15323b16cbbdc58c590108642a276455.nq.gz
    ├── 58dc642edf3e87e65faafe9acc6db5f5cc9f4a84.nq.gz
    ├── 59f5b12f4c8f5d45f116de22619222885ae997f2.nq.gz
    ├── 5a5249aaea57175d7f6fcae13ea942fd3f3c69d3.nq.gz
    ├── 5ac49b03d617a68c8c80db2c019cf7cd2f27d259.nq.gz
    └── 5b421cc401b23447d22250605970c792bf30585a.nq.gz

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

[trentm/python-markdown2](https://github.com/trentm/python-markdown2)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*

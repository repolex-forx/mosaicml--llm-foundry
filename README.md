# Repolex Knowledge Graph of mosaicml/llm-foundry

RDF knowledge graph data for [mosaicml/llm-foundry](https://github.com/mosaicml/llm-foundry), parsed by [repolex](https://repolex.ai).

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
rlex download mosaicml/llm-foundry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0cdb2f42962fcf861e58b236e9bd1c9964ba99a4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0cdb2f42962fcf861e58b236e9bd1c9964ba99a4
│           └── chunk-001.nq.gz
└── blob
    ├── 013c9811746fab210da0f751baba42a207e20578.nq.gz
    ├── 02586f13d33dc9232c4317aa2f833ae707142316.nq.gz
    ├── 028bd4e51326cc43f8394987ae47fbb271aeba9d.nq.gz
    ├── 03df90e8cd0ef85adc1e3d8dd73a388c5c92e83b.nq.gz
    ├── 04d1c04a2de288bcbaff275b753788c68fa84a92.nq.gz
    ├── 079f5ad2e7bd827b37b2dd28461018382ec077be.nq.gz
    ├── 07b1b275098161c0b207d7caac75ac12079d3507.nq.gz
    ├── 07e8f357475fddfea9e08a616fae3a62fb77546a.nq.gz
    ├── 07e902bb5dbe8a6dd627f5fc94425aad3d6629f1.nq.gz
    ├── 080153b1d935704ee60d130fc17cd6230cbd1f4f.nq.gz
    ├── 08159687cf4fa8d588c9f79eb71ef5c92eaa0263.nq.gz
    ├── 0b2b3dad54bdb2a3a207460eacc6dcc471d2be31.nq.gz
    ├── 0d7e4daaed67c19adb547c304046b754f9b2bc29.nq.gz
    ├── 0d7f4305066f149483e56f91d0dd9ecf9f765214.nq.gz
    ├── 0da0a26ede5b8b849630788238f0f4a2d0a72bfb.nq.gz
    ├── 0e03f6aa5a1e18b016486ec9de46783380069ada.nq.gz
    ├── 0ee452695a9c7df493768145f3d3d952ee38b4ec.nq.gz
    ├── 0f14d36a675905a6ce531a87b2a503ee62920a02.nq.gz
    ├── 10b0224226876663e557ccabd815809c44b53c51.nq.gz
    ├── 10ea857b255b544743a51d946d041ed44bcff16b.nq.gz
    ├── 129ff532b65c704d75c1fed7c7b7a99cf77a754c.nq.gz
    ├── 12b7fe95d10df567e47f93bee06e84357f7d01ea.nq.gz
    ├── 13c3978cb6cb85015bbf648d120e2760ca3ef5d9.nq.gz
    ├── 13e9b5407e5be5a78479e012bc6dfee574015bc7.nq.gz
    ├── 16e3f8ad6fb0743d4788498ee1bab0191786a77b.nq.gz
    ├── 170bf0194e5365cf8e4b6f3fb4a2edf535c2fc21.nq.gz
    ├── 172e538aaea8c75a80ffb0e51c3d51fb9375544c.nq.gz
    ├── 190010650e349858dbbfd303ff32d704b08bdfdb.nq.gz
    ├── 195fc95bbb142ddd25572f1688c7d0e94e499bd7.nq.gz
    ├── 1b106c4c929663efd094457113dc69d80db5b626.nq.gz
    ├── 1b413e754475d8d2e93151fec05a549a7768d53d.nq.gz
    ├── 1d77945486992b43cf55d38b4b7188e420028d5d.nq.gz
    ├── 1de92ef6ae56001c6257c3f13a1438f89a577f16.nq.gz
    ├── 1f132fbbb12a67ce267b7b92b458175632c265f3.nq.gz
    ├── 1f81adb3d409c60c3c6158ad1a6eb29dbd9968cb.nq.gz
    ├── 1fe4d78db02a797a8295a1bfc6651002b8f90734.nq.gz
    ├── 20e5d358c16858aff34faa35af7f4f7bf5fc0492.nq.gz
    ├── 21daa839e059fedaa78723fecb11d61eab541107.nq.gz
    ├── 21e7a170d329cf787e5a319c0885f02109ddda16.nq.gz
    ├── 2206debfe0d8c2b249e53439812e55ebff774f6b.nq.gz
    ├── 221635da874676e65e4473ab9b0b987117b76765.nq.gz
    ├── 2271be5d6d16db841463abfd6b2bdc6c31b9ce05.nq.gz
    ├── 2365571e4b500b2f90de18a4d7c5ec3814af02d5.nq.gz
    ├── 23de281bbc28e157b8ea680a257f2539d5fdcb23.nq.gz
    ├── 24569a086b7c58292445520e19a33353e4050fde.nq.gz
    ├── 24ce1cd652d845c7c6b128eae33f9e6e89b3a34e.nq.gz
    ├── 24eebfefe83415a508c107ad6408d836d4db95f2.nq.gz
    ├── 24fd4cb126bff90c76e2350ac39aaa33465c7506.nq.gz
    ├── 27766d6eaf942aa38148d1dee45c634577b8c0ea.nq.gz
    ├── 277a8c1ffcfcb2e3d0304497c221b989910d2800.nq.gz
    ├── 27828862cae910769b5c1a79c92de82e2bd21dc4.nq.gz
    ├── 27a4ac2b3b18716add92f4ecd62475c4f8d77768.nq.gz
    ├── 27f5c26c7d8134639f5c0aa9d1180d14d7621c7b.nq.gz
    ├── 284100ecf047661f4c9725ceffabdf6b625a8eb9.nq.gz
    ├── 294dbaffd4a3887de14e9512e4be6adc34776cd3.nq.gz
    ├── 29819592a14b27f6c7f869e9d07ed8491b948fd7.nq.gz
    ├── 2a455e1ea43887c049e67afb63f7902fbca73f48.nq.gz
    ├── 2a4b90743c857fea16ae5a4d90ef8a0c23389673.nq.gz
    ├── 2b01f4f989d652a54abce3954e5f18beaa712f3b.nq.gz
    ├── 2bb4846c866a21b939e0b59f2f5f3d580c348475.nq.gz
    ├── 2c147b2c31bb4992b17ab51669fa2a13adab37ef.nq.gz
    ├── 2c61118baf48aee783ca1805baa480090a23b2d5.nq.gz
    ├── 2cc7a1a175dacbc7c4c449892449f36fe2cfbb36.nq.gz
    ├── 2cd1854574d4c72d7bf0097560edf0fe8ef5097a.nq.gz
    ├── 2dcd8a6a18e151d8f70b3c24cf7ed76c11a0ca8d.nq.gz
    ├── 2ee8358b2c9f3ed2423696d257609252ec421ac6.nq.gz
    ├── 2ef5c571bf10a3ed656fabc45610b0e98098dc9e.nq.gz
    ├── 2f1cee44085ad8c846511b21810426b0f0dc3cba.nq.gz
    ├── 2f771918dbc8b68550df204171b14d2648b5d494.nq.gz
    ├── 302ecbdc2f745a8d8320fe85a736029900dff6a2.nq.gz
    ├── 30bce3ddb716938046046f72659c78e6a910deb2.nq.gz
    ├── 30da2e5ef38a8ef59de2f7e99592035b5bf9cb50.nq.gz
    ├── 30fd5c07f610df871b431be8e60807d3824d43ef.nq.gz
    ├── 3113a93d7d633f1252d3c9676f1e65c0489ecfa3.nq.gz
    ├── 313379f7443dc08f68c8d9538da23438b85bb298.nq.gz
    ├── 316e87ae4659f0c402b0f00551fdec83ab0a0986.nq.gz
    ├── 31b7bf255b44f848f07367c31b168d96ae55f498.nq.gz
    ├── 323ae237276c561177f07f9392f17f4a1baafb20.nq.gz
    ├── 32a2202ac891a344dd148c01f880c4985e47c102.nq.gz
    ├── 32d46607b5b0038555d1483bd05625e063f6a50f.nq.gz
    ├── 34fb23f6705d2c6ac57cfe73b4b7f346dc3ddb47.nq.gz
    ├── 3511bb39b12c5abe90f947a8ef32a00be7a52599.nq.gz
    ├── 355adcd135fb97055ce90ce97b2ba94be019464a.nq.gz
    ├── 3579174ae77c1b9c922de2913d5a886f2bb3fbbb.nq.gz
    ├── 35b875fd7ee3d39e78ba7b66e17c4c4a4cd67865.nq.gz
    ├── 3627c36dd0fd764df413084920f2bef2b91c13b7.nq.gz
    ├── 36a2fa3e9ba41955c3063f98ed2452aea7b1fd18.nq.gz
    ├── 372a23a8a3b53960d8a8c9c979542d2aa4eaeb8b.nq.gz
    ├── 374348ed2fc45b1dbccb6baf434dbd2141bd3a16.nq.gz
    ├── 37d4679ab6982add9a474de24f1c7c724422941b.nq.gz
    ├── 38567b7acd4dd4a138a6b6c341b5068ff15834d7.nq.gz
    ├── 396ceaaf85891a9fd764c207cecf6dfc59daee88.nq.gz
    ├── 3a33d45cedae752f342bcc2780be1e0e28f69036.nq.gz
    ├── 3a4fca76e78c50190fc20fd501a0379b2c421b44.nq.gz
    ├── 3b8a6126a855d87133aaa2bd34f802099d7a9591.nq.gz
    ├── 3bbc7db64f7383a39a84d5e60054921225e718c6.nq.gz
    ├── 3dc868482e528e31ccc91edf0090b08181773a64.nq.gz
    ├── 3ed238a4ca19ffdb57530c7981877a309ef917bd.nq.gz
    ├── 3ef41e0aa16b2d7f288a8efc169c28e82c8ada07.nq.gz
    ├── 3fe4933361dcd34264c87311c234196e57c298da.nq.gz
    ├── 41002bb45df86f1a512d1608e7df27fb151d34f5.nq.gz
    ├── 416260a2ac10731c9882091f2956d3383c09a8b7.nq.gz
    ├── 416363c261cae792091f5a8985d084ae8d4a41d5.nq.gz
    ├── 4183138bdb7f6a3e02d87879e98412481dddaf1a.nq.gz
    ├── 426363d2c3598a41b316c58956f116894d903e3f.nq.gz
    ├── 4326a5043b934867a04097a09921ad8a629d20a6.nq.gz
    ├── 438468c35e60dbde8909a1ea2d1e6c951547ead8.nq.gz
    ├── 43dbdf85a7fc51328de8f436862d7689e630d436.nq.gz
    ├── 4466b2dfb2a13d00a33f4d1b7ffc5d06a4c9b34f.nq.gz
    ├── 448321079fdc140bd8566b16b24eda9ceacd3501.nq.gz
    ├── 458f6869dae920bbbee1278fd5261f670071e1f2.nq.gz
    ├── 4600ba8ae6067628e4a18af9b38ba8df7fb3dc11.nq.gz
    ├── 484ac2b23a48d0a233397fd8e39eb8b2c9742d62.nq.gz
    ├── 4888f20f6af6a5cbd21c29586340e49419e48f03.nq.gz
    ├── 49bdeccc7bcb899b296045a30ac29ec02c447118.nq.gz
    ├── 4c14f251fe432d6bdc94223d447a237f8581c7c4.nq.gz
    ├── 4c3fc4eb0500b5da87b1ba1033aafbadd053b783.nq.gz
    ├── 4cd22e356ac48c493fb842d7aa7423c34c42088e.nq.gz
    ├── 4da02dd53b9e7385871d06ab855471d77b2f7dda.nq.gz
    ├── 4dc8750dffa962f68cc526f255c4994f7667f412.nq.gz
    ├── 4e664bb458a047df948100b100df4bda245b028d.nq.gz
    ├── 4f10017dac6e241b49ad18e7f6e6db589ccd97f2.nq.gz
    ├── 4f70a35637e5ebd484f0ce883cf2d1bd7cfc0e8c.nq.gz
    ├── 52472ee1d92e8d7ba3040ff1e4fcebe48b15a70e.nq.gz
    ├── 5254c8e8621fad2f369bab1cc8ce3c470d00b41b.nq.gz
    ├── 5274bd0b9de5545acf201f3d84b38938f3c0f83f.nq.gz
    ├── 52db9fd1d3888651b6cf0936eb68b9c006cbbbf7.nq.gz
    ├── 538f2968ac42f78fe5fb74ccbf28de3bcbba0ea7.nq.gz
    ├── 54bc738ebd834dd6333cd4b210d593a1189ff003.nq.gz
    ├── 55450a8bfcc08a3c0899834eb7df3db48ab5cad6.nq.gz
    ├── 55a3c92ed06a65eaeb93286df0a62dcf668225cd.nq.gz
    ├── 55c4a0122bb49800ccf7cf3bf99ffac55b30a5a3.nq.gz
    ├── 5770f385e9ceb6836a4449460ed1a6288d17bfc8.nq.gz
    ├── 577dbd33cc1632740678106fa9336c5707566ad3.nq.gz
    ├── 579ef14bcd32a3f7075362a50a1dd5ea578c768d.nq.gz
    ├── 57a465dbff2a647608fe0811919ccf5d62d4a1bf.nq.gz
    ├── 57bce28ac2e1c0a8a62af51ae69ca7db3bcb86c8.nq.gz
    ├── 58321a43363203de0c586ca04d401fb580c13a7f.nq.gz
    ├── 58ac0ab448cbbeeb85fb36b7a82e9dbc594b103a.nq.gz
    ├── 58c39a724fa71d69d539f2ae0d2378ceb445ac5e.nq.gz
    ├── 5961f1db4d4f7474c14846c621d927567ae38d53.nq.gz
    ├── 59d44accb34a35ce289636576ab68f9ea2e0419a.nq.gz
    ├── 59fb723f572c00a669c330bd1ea69da5e52ae622.nq.gz
    ├── 5a0dc238ae11b9d28ef6bcaeb46d49b36df646ed.nq.gz
    ├── 5a0f0244ca24ad0f718c72678a47d78888227a79.nq.gz
    ├── 5a859ae9092a342742da96b8927f2cced558b98a.nq.gz
    ├── 5c1f0bdbdcd5f8f70ada00c8a362b6e55f9d14a0.nq.gz
    ├── 5c5802efd238d07702a425ea59ebd0a0ce1a65b7.nq.gz
    ├── 5d891d546c54937d3fc59ff0d849d1eee9ddf4b6.nq.gz
    ├── 5e1be72797ba082fd4f6efa42f7d759d2d23339a.nq.gz
    ├── 5f02ba47e6a15fcea86c8f5979379918d0be357a.nq.gz
    ├── 615f59ee3f1c4b71af19c96209e218ff8dafa5d1.nq.gz
    ├── 61ffc9ca4442bdd8f516933ad88473695ba35eb7.nq.gz
    ├── 6238927fad32a61fbb27d61afc1ca99da23095e1.nq.gz
    ├── 6303800592c606582213caa6777027e3b7d50414.nq.gz
    ├── 633d075f64dc5b47061ff82924017373acc6224d.nq.gz
    ├── 635313d4bc0af5d2fb4fa6b1adae62dcc8768949.nq.gz
    ├── 63c328be63b6cb5baa7d6ed95bd0e73389d65b80.nq.gz
    ├── 642ba0a8450af2214466a068da5e734f0cb1638b.nq.gz
    ├── 644dfc26c107b1ce3f3eeb1ad3607fd3906ee477.nq.gz
    ├── 6459c2f0fb5dc3c4bb1a26ebd5c8765433d94ac3.nq.gz
    ├── 64fc15a9e48a745c7df763a8dabd46e35a080ebf.nq.gz
    ├── 6546b13dd73236dc2f11671b6e10da6a4bcf82c8.nq.gz
    ├── 6562b7f68d8b54198b81d1912c356e71beb338fe.nq.gz
    ├── 6665fe05002696a7c22d9fda12dc3ea915a4b1c0.nq.gz
    ├── 666d93c9b4ce763be5e6337a1e85132dc14080fc.nq.gz
    ├── 68363161f33c42f382572f20f3762e6a0409b58e.nq.gz
    ├── 683d719c90c000c508b72fc59df849afa05654e1.nq.gz
    ├── 688fb1f558f0f66bd66449d4089008eb528eb56d.nq.gz
    ├── 68b4df436b4ee66b5a6bf4005d51129653207295.nq.gz
    ├── 68b6692f500878fc4121cb54bd679d4c6f242aef.nq.gz
    ├── 69c5f344ae3d6046240eb750408dd59f1a5e7ddc.nq.gz
    ├── 6ae57a1430978b72fbaffbd9b51257e6acc90758.nq.gz
    ├── 6b4738e965936606b64cf84fcf321fdee7c6d1a3.nq.gz
    ├── 6c24cbd21fc8ed9f85c53dbd41856d8e587ffdcd.nq.gz
    ├── 6c4a2d12c467a11c181463af530244a74654b506.nq.gz
    ├── 6c580caf48fe8490861b7c8e5b799295e9a7c804.nq.gz
    ├── 6cc43891792e9cf1c5cc6d57c06ae126ebeda9ee.nq.gz
    ├── 6e4f3b17f492e5b9d69f461d266bcd7cf9c7f943.nq.gz
    ├── 6e9c6ae2e9f2315bbeb85320fb6ea57c0556c9be.nq.gz
    ├── 6ea48377b118fedcd6ffd8d4a3a7ddc21f8d86ea.nq.gz
    ├── 6f5cbc3d44674059a749bfc09f89c9c181c35d93.nq.gz
    ├── 70364c99a54bca1f04c21cd5fe18d2d26cf6a7e6.nq.gz
    ├── 728010d13a74462e4902349268bd455ccb16b467.nq.gz
    ├── 73a4c62516ffff2883b94a138dc6d91881f74e97.nq.gz
    ├── 749e792318b9fd3e992fbd99ca0c7f7583a6292b.nq.gz
    ├── 74ba0996efa96efa02574ea1c5c53d14fc935d0a.nq.gz
    ├── 756e611a88aa56839f807b0a5c947d4c81772e10.nq.gz
    ├── 75d4c02d0e08cdd94030ff3abc11046098f759e4.nq.gz
    ├── 762fe030ac6938ecba438c47a04057247c6ab891.nq.gz
    ├── 791023abcf27d7692d7cad28b4e33ded66b03f96.nq.gz
    ├── 791707be1f88b995f478dd80b273a8d834a12b7b.nq.gz
    ├── 791a980417dd8731cf77a77897433ebdb3455a42.nq.gz
    ├── 7ac3cd5d729738ca0e84e529c9a34735bccf18f7.nq.gz
    ├── 7bb75f755be8faafe122ecf58f1c34d6877682e3.nq.gz
    ├── 7bbb80fa4c83e43e7a6c4f95a8103cc21f990b61.nq.gz
    ├── 7d7081b1ebf2cdafe270765f94ed47b45a7dbecc.nq.gz
    └── 7d8afe44bfadb5ca5558e2eea0e49f41c3922dd1.nq.gz

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

[mosaicml/llm-foundry](https://github.com/mosaicml/llm-foundry)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

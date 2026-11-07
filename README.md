# Repolex Knowledge Graph of cookiecutter/cookiecutter-django

RDF knowledge graph data for [cookiecutter/cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django), parsed by [repolex](https://repolex.ai).

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
rlex download cookiecutter/cookiecutter-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e0c7d45a6b3a7847e3fede09303093c9dfba504c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e0c7d45a6b3a7847e3fede09303093c9dfba504c
│           └── chunk-001.nq.gz
└── blob
    ├── 00644cefb0e12443680de6533444ce2ab7cc1f5d.nq.gz
    ├── 00d235e56293120b43a27e7796f58cfbe53e5227.nq.gz
    ├── 02bd02a0c16b2f1ddc1335a1f278c9c0c4978fcc.nq.gz
    ├── 02ee1af8356390d946e4cfd8dc04c05a7eb142fb.nq.gz
    ├── 0436118c143a648668b938158cf7a366be5abbe4.nq.gz
    ├── 0590f7be578e632e1ce94c13a29f045b46fea0e2.nq.gz
    ├── 05946f2c3d602d2b6e0b2d79beee2699fb57323c.nq.gz
    ├── 06908a12545a069f24490835777674c4c02fcd8a.nq.gz
    ├── 07ffd7112f79fa7ca031d2f9e40ca03f7867c11b.nq.gz
    ├── 081f326a0cb85f1113f8e1eb3d7054af06728550.nq.gz
    ├── 08f76c454debadd2c513df2bfd0538f72ebe2a58.nq.gz
    ├── 093840f8764eb2536d0c04539f8cd99cb6490449.nq.gz
    ├── 0bd4e49fa1a4d2032409ccc2ea065efc9387fa60.nq.gz
    ├── 0bf5da2b59622e8e61ae6725b63540244858f378.nq.gz
    ├── 0e1a6572ce874157ddf1ac2b1ff6dca339704270.nq.gz
    ├── 0eabd93c807172787db315d6a78f0fc17e143b68.nq.gz
    ├── 100913a849ab1a456fa28d2891b5c59ed6a73201.nq.gz
    ├── 10af178fd4c432703bc9cb892c727729aa46a2cb.nq.gz
    ├── 10b1c936ff4bf9163d65038ef1cedff8344ba1aa.nq.gz
    ├── 11668ecdcc6c32124c04bed93e8942db2638c783.nq.gz
    ├── 12871a773b708ff46bd17631fd88ff4953fef8c6.nq.gz
    ├── 13d336d57f839f3f524da1bbbaa92a2704818e37.nq.gz
    ├── 1418fcddfb5953ca3221f0caa82d096fc36c1ce4.nq.gz
    ├── 148854c649ced2fb61df66fbe7e0f4d4309e33ce.nq.gz
    ├── 152735b5f7acd88b7bed87d94ccfa2220723625b.nq.gz
    ├── 16719f493ce36dedb5bc0d911ef8834f12572705.nq.gz
    ├── 1681e0f57d59e70b4bc058ebdcca4a4cbfbf6e5f.nq.gz
    ├── 174f6fdf3f8a1d7e510f56de24813c571ad8bb82.nq.gz
    ├── 176a458f94e0ea5272ce67c36bf30b6be9caf623.nq.gz
    ├── 1784e40c605fdfaf87400c5ee50aa0f5480b4b86.nq.gz
    ├── 183a801591519db400b66f41d815e60f882938e3.nq.gz
    ├── 1a699dfa80b6d1a70f12da1076f29b60c92c0096.nq.gz
    ├── 1a836c87f22e6b78c114424cea628bb6d85cf2fc.nq.gz
    ├── 1b057bb4d19a718bbdf6b5a251a6ee862f727b62.nq.gz
    ├── 1bb68eeec6a536d5fd9285696d23100484cb5fd5.nq.gz
    ├── 1c98d314e9890160e23c2110ace0301982b3c873.nq.gz
    ├── 1d62f234242577edce80ffa3da010c143908b226.nq.gz
    ├── 1fb8cf1e20c6dfaa542a1c91942a7a1bd96ea96a.nq.gz
    ├── 1fc44f30b5e96fac74c777da3df83a18429354c0.nq.gz
    ├── 20f45331e6926f86c2d0092e2f2cc53237e9775d.nq.gz
    ├── 2233d1fa904f4cf6d7c0abe8b0bda690696b3de3.nq.gz
    ├── 231f76303b28916a3b5eba494bad1f77f5cec240.nq.gz
    ├── 238093943bf7eb6e79cd382be6c3d856b7ddc288.nq.gz
    ├── 239970dab14cbd840b2e93edf1899d24738368a7.nq.gz
    ├── 242f861a64584fe44d8c53a04150ff546964eac9.nq.gz
    ├── 2836771696be4497417678f09666bbf8475f419c.nq.gz
    ├── 2a348a2e7fa0f3651d9517a38aa7fe0477d107a7.nq.gz
    ├── 2b197873f4586e9c172ca62e5e61f4eea349397d.nq.gz
    ├── 2c8b16173596df70b5e2947a3023ef4e30facbb2.nq.gz
    ├── 2cf6113393d8d7dcac525ee2689fd0f0f687a938.nq.gz
    ├── 2d8c4b6cc1d5c53fa377137a6c1a9523893631a4.nq.gz
    ├── 2f577824ef3d4a770d27e5e1c4ff9f860b1beba6.nq.gz
    ├── 302db261382523fcfdbc09bf06d7d57e2bdf272b.nq.gz
    ├── 32c93351bed8e97ef9cdcdd4eace0e6411cbaa42.nq.gz
    ├── 33059b287e02e9fe3308a6252a6489c25d5e78ec.nq.gz
    ├── 38c5d1de7f2f1e70b9187132288502670ad3f697.nq.gz
    ├── 394a47557ac247a08606b737de2a19a183e914d8.nq.gz
    ├── 3a2ccab528492724032431abdda57a49795ec7b9.nq.gz
    ├── 3c6dbf749aa906933251a2bf1383651506fd41c9.nq.gz
    ├── 40086de7f725448174bb3267219f6a452fdaf804.nq.gz
    ├── 42ddca91050784d70baaf359dad7825f15a022d8.nq.gz
    ├── 43435aca87ce12ad694fbf74e99d43060ab70574.nq.gz
    ├── 43464ab3f63cac2f8fec353f3dd79ce0262cbe53.nq.gz
    ├── 452953740b9d1b96937f0e94df2aa28086a97519.nq.gz
    ├── 45b93bef8be48abc17cb19a6fa31a069f8ca5155.nq.gz
    ├── 480655af172a99204415ebd6ed76cf5a1caed71d.nq.gz
    ├── 483841f872b935beb5c88a338981afbdb0ca350a.nq.gz
    ├── 484f686ad094132edb3f462b6e5455885cd33b0a.nq.gz
    ├── 485e1a8380542346ac5bf4b17d8924d8296dc387.nq.gz
    ├── 4a44a6a920ed44dfecde47ffa3608dc64de92a70.nq.gz
    ├── 4a870cc28570e51f4506de1bdfeae578f809111b.nq.gz
    ├── 4aa03505b692e7ceaa64c7a1aa0a70fa07cd44de.nq.gz
    ├── 4bb54da9e17255196a4713d1f59b5c974ace5a59.nq.gz
    ├── 4c7a5776ad82169dbf5531b5fddef43c56996058.nq.gz
    ├── 4e1c8a67eb277a9c5be584dd85b7f0dec787bcd8.nq.gz
    ├── 4f8807e3aa35eadb54537f5e7a05b3552fd7df1f.nq.gz
    ├── 51ab5eb103d6f770b861f3de59c93acb6b387a72.nq.gz
    ├── 51ca863fe7f54758fe74e6541b309a18519e7353.nq.gz
    ├── 51e0859f36eac5f6e0c4ebaa523672fea7c27c2c.nq.gz
    ├── 561d93ff3b7e9d3bf8ab8ebf6405cf85ac48d089.nq.gz
    ├── 562dba86c529a1776bf7cb4613049e993d9ddbb0.nq.gz
    ├── 565df2de62d765ca800338880aeb8fdcf6bd7458.nq.gz
    ├── 5721aa7f447e6fb8d92dfcb161cab02b9ec2c29f.nq.gz
    ├── 574361fea4ef509c97a932bb5ace77f4194dffa3.nq.gz
    ├── 576d06fe7f889ea5722ce51dceb33a87bdc88d32.nq.gz
    ├── 58a05770ac0dfef29cb48e396170ac7c5f7032c4.nq.gz
    ├── 58ac3d45787e6cb6985b6c822069167adbea8a68.nq.gz
    ├── 5a9c4479c340ad12ae5f624d8e8ea9a165119bd1.nq.gz
    ├── 5ace414d826e6c93413b72a6e835ff1e7b23264b.nq.gz
    ├── 5ca17558f03606248483a584d09669ce09e68984.nq.gz
    ├── 5d6c97c5cd8c00fe0893960bb9c108b9a83d28b8.nq.gz
    ├── 5d7d9f9ca09b664bfbaa4e33bc544c66847721fd.nq.gz
    ├── 5da8982f4e9b726ad4f5df6db45cc6bb850e0f7b.nq.gz
    ├── 6134cf9177779ecb490f743f2adfd1cad49ee3a9.nq.gz
    ├── 6176134c335b059216a09f37c1383a77a9606eac.nq.gz
    ├── 61962a6ed69bbef0e82fa0651ef8195a3a2f712e.nq.gz
    ├── 61f839cf6d05f288c03333c1fb3342b1cfd0df48.nq.gz
    ├── 6249fd3939e18c1a612a2a023965d1a1aacb6d35.nq.gz
    ├── 6257244389d682ab638538d04158f373a585b71c.nq.gz
    ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
    ├── 640f0575b69f52b38765ee884c19bfedd6f51390.nq.gz
    ├── 6424e048d371654feb922441a1bd7489335febf8.nq.gz
    ├── 64bb7179001ce96922548c396b2168c6e892d987.nq.gz
    ├── 6640f9b6043cabf5ce36779c9aa2d8ee68c96e4c.nq.gz
    ├── 67434d505c2a8304bfbab506f0d114e255c0da79.nq.gz
    ├── 68758ac2c5d062cbc35c0bbe6e7dff541c5950f4.nq.gz
    ├── 69a1da66ebad568f5bd0ea5aadfd96e27e52f21a.nq.gz
    ├── 69bb42e49b15898f1edbc5fd84a6c5cc02946e2f.nq.gz
    ├── 6a4aa2e0b52d9b162df06006d367bd742f9a4b9e.nq.gz
    ├── 6b5912444ad11e8eab2a6b3b8327eb3169051385.nq.gz
    ├── 6ca4f0ca9c64f449bf3774f3e3d90a274f2261d0.nq.gz
    ├── 6cf6455622cfa33e6dda7aa9e92eab8df0add10d.nq.gz
    ├── 6d43e5eb119b9d23ef9282cff627058340d917a0.nq.gz
    ├── 6e50c04425fb8c4cdbcede568beb1fc56bbf8d22.nq.gz
    ├── 6fb23124918bc768aaacae2a8e0ac2e3ae3e639b.nq.gz
    ├── 713ab543efb99b38f13ebb32a71ac922106ba6e0.nq.gz
    ├── 74d65da1e27b7717d2eb976b9d928a09ec8c1852.nq.gz
    ├── 7852f7dd93c972d8a565764f3162b5833ab0c922.nq.gz
    ├── 7c774185ea30dc994120a0cbe41e1de6fcda0cf7.nq.gz
    ├── 7ccdaa967c1999396c3da5044559244235895b6a.nq.gz
    ├── 7cee2dbe3fc4fcbf5e9fe4cd63c4cce9aa1967ef.nq.gz
    ├── 7f7b48d76d9a128cd00e2ea6d0c9fa8a011a2063.nq.gz
    ├── 812fa0fa63a1dd6872ca83f7ab80243c45e7bf01.nq.gz
    ├── 81adfbc664215c36e2208ab0254b81f1a64297b7.nq.gz
    ├── 82a80bfc17103625afaf06009bf4ebb4c77bdce0.nq.gz
    ├── 83e69c08aa6b4163c82b488e94ef8ae222794a7c.nq.gz
    ├── 8772c827b325541e1fb46121b7175b1087fc7e26.nq.gz
    ├── 8a180ca8026a32f7a96bd378657981d0ba8f8fb8.nq.gz
    ├── 8a8ef10d674f98a20b081c96912b36c17e46fd0b.nq.gz
    ├── 8adc4891a69d0b97345e49fe1cac91d546d5ad06.nq.gz
    ├── 8cb02c411e9879a5c34bfa6b02f7554b467f6be8.nq.gz
    ├── 8d554fb701fd22c21cb2d0e75529ced5522acd65.nq.gz
    ├── 8ece9d897fd7e3713664830dc22b1b360a946d17.nq.gz
    ├── 930bea08acfe0b73af542002f8d4fa944db026a6.nq.gz
    ├── 930fa54a2c250f3ef4ac4dffe2ecc9752cf2e58a.nq.gz
    ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
    ├── 954f7837553a91c181a27a2273d3689c01b6f9a0.nq.gz
    ├── 96a94f5663eea48e1b08c96b290f101633c367e8.nq.gz
    ├── 96f386ec8a42bc0fd3e6af6f4a0dcbc4797070cd.nq.gz
    ├── 979eca31370b0039024d5d88c7e9667ed27bbc41.nq.gz
    ├── 9860994b5853158e160721cc572b93265a859b83.nq.gz
    ├── 9c307dc58c89b5b1858f7778088dc148daa72d8f.nq.gz
    ├── 9d2e3264a306fbd318cf5e6970886740484b8f03.nq.gz
    ├── 9d2e9ae9d1321c32cc20f57c724812c2c3e588a1.nq.gz
    ├── 9ee59d3ef1d6dcda6b7ce31eb9d9c661075ec218.nq.gz
    ├── a16e09bb1cb64f17dd4d400b5765597d601d2076.nq.gz
    ├── a18937d625b000b3b6052766af10e79e2f04a5f4.nq.gz
    ├── a67e4da21a6561110c6216465e0a8fa02b4a7274.nq.gz
    ├── a7b21223b03c1ab4c9a87b3ba5c29c28010ce68c.nq.gz
    ├── a8ed429ec4372a8886a32a67e4b13884e1776879.nq.gz
    ├── ab719770c3e14ed5489fec84eba6c3f02fbe0881.nq.gz
    ├── acb19c16a201abad741cdb5ca4e4c36426c33a6a.nq.gz
    ├── adb611cb466fde95664bb239887af6138fcd2dd8.nq.gz
    ├── af0c8f7b5227666ab85b59a60471668d74fcc070.nq.gz
    ├── b06a2843da7b18ad82a915b7a956336a519a7436.nq.gz
    ├── b0b9b6c157d82f8b420c3906ca7b605a3b14fad8.nq.gz
    ├── b123a478f441a7e076f4f4deb3e2015b80014833.nq.gz
    ├── b3372b68fc58fe1c7c1f127cfb3b2f1b9f79efeb.nq.gz
    ├── b457c5f55bf4af18e729138c3117e18ebfc7e2bf.nq.gz
    ├── b46d28e1611ea1dabdea743db6096b35f857a4eb.nq.gz
    ├── b47b536191b68687e50e5325b8a8f60261325435.nq.gz
    ├── b57a4d0faf278e0e897844ae1a0617e57512d62a.nq.gz
    ├── b70fc9c5aec441aca7cc1b690e7cfe489b0b4ca2.nq.gz
    ├── b91b7798e9d00d6964ac8bee911190a1896fa551.nq.gz
    ├── ba0c9822f738909d14de673726c32ba67277d874.nq.gz
    ├── bc09284781bad93490e1cfe7eb354785f44e29f6.nq.gz
    ├── bedddf64b03a5286b5c9c99d53eece86adf0d9e8.nq.gz
    ├── bee335813d9dc230bb65b106ba7e391b6ee0f61b.nq.gz
    ├── bf6494d1d16995371cfae6e754667ba39970ced1.nq.gz
    ├── c0b1cbe5d4590f41e6f193055cf25dd0e306134e.nq.gz
    ├── c19a231fa36f7cfe53b24a5e436f8b72b415318f.nq.gz
    ├── c224948595790960ff70b17820d525936605d978.nq.gz
    ├── c57e5829cec6274186bcc09400e9878f29c04dfa.nq.gz
    ├── c659d226c61526c2e08803ed8271941f12cbaefb.nq.gz
    ├── c68f17d71aee0f4e2e67825695226de45c04e486.nq.gz
    ├── c96c5e31f762cf748f7a8f63d6be4b17e11308f2.nq.gz
    ├── ca42b18b39b5e182db2f28e6d3b5c3715e7ac5b9.nq.gz
    ├── ca51cd7401b10ac31984e1927f3c7fdf480731f6.nq.gz
    ├── cc82dd7f3d710305ee36d9d3d78fb4d030f61a22.nq.gz
    ├── cdf0600dadbe56a62c1abf88e115dc7ebfa6a20e.nq.gz
    ├── cee6676bc8122e22f09a3a73e3d13aa641b56aca.nq.gz
    ├── cf07f9d83c37d5d95d57c36a7accf1bf195c731c.nq.gz
    ├── cf080e4767efa042730fe436f873a004a3f66ce4.nq.gz
    ├── cf2c5dd89dbe6bff5b7beaf178f3b5b3b69ca68d.nq.gz
    ├── d1995b0b9a2c5543c99bd74b3d329879b2668efa.nq.gz
    ├── d3f610139955959b02f6afc19faab47fc266edd6.nq.gz
    ├── d4de098fc877a5378ad948873a71c0e06a53456c.nq.gz
    ├── d60bee5a1c6a390715cbcfc3db1a09b30c28f641.nq.gz
    ├── d8719a1e5b918adf41184589b9e251cf2d49376a.nq.gz
    ├── d8beaa48e18a09c2a1c162de67266478ea06bed8.nq.gz
    ├── d955c79d449097f45fa658a7a530522f16df3af6.nq.gz
    ├── dbd66e11e668a8a4635e5ecaf18f8ecfae44b369.nq.gz
    ├── dd9a5241e9310d993ec7972378383b4f7d837af1.nq.gz
    ├── deb28ba1b8942c566a35b302613eb15010f1e0f3.nq.gz
    ├── df7f47729ee85238e671a9c479b22750991c691d.nq.gz
    ├── dfbf3a3f530afcb6dc2d3152a6480ac2fdfaa0ca.nq.gz
    ├── dfdccc7cc919da25b7c2166df3ded5128884bac1.nq.gz
    └── e166b733ef1e1f2931101e11e349b64b835d19ec.nq.gz

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

[cookiecutter/cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*

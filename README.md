# Repolex Knowledge Graph of langchain-ai/langchain

RDF knowledge graph data for [langchain-ai/langchain](https://github.com/langchain-ai/langchain), parsed by [repolex](https://repolex.ai).

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
lexq download langchain-ai/langchain
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 402298e3761719ace9800fb744175f3f4f84544e
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   ├── 7ec4dbeb802e6ffc1f413c42e2722145a91a6a2c
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── f0bb8395064b8cb52a18862a9bc6ed76e4ac98f6
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   ├── 402298e3761719ace9800fb744175f3f4f84544e.nq.gz
│   │   ├── 7ec4dbeb802e6ffc1f413c42e2722145a91a6a2c.nq.gz
│   │   └── f0bb8395064b8cb52a18862a9bc6ed76e4ac98f6.nq.gz
│   └── repolex
│       └── f0bb8395064b8cb52a18862a9bc6ed76e4ac98f6
│           └── chunk-001.nq.gz
└── blob
    ├── 000229aff0b4b082466ceab263cf7a0746cc5eb9.nq.gz
    ├── 000771b7dc87a76f50e0466ec1ab3f80a8f80adf.nq.gz
    ├── 0009b6160a6cd07b30c487e88aeb6fa00acd39bc.nq.gz
    ├── 000c70de4b388060ece6cd1ea4bde3f9ac30defb.nq.gz
    ├── 000fc669cf229629046b202d99b100a36ab281ca.nq.gz
    ├── 0011ddc008e8d7bf3ab7ee53f92664316925b774.nq.gz
    ├── 0014ca9f0e9062cb8e251d579b6f84fa80caaa9d.nq.gz
    ├── 0029deef21cedb9e7b8ee0ff90ae7976677f9f76.nq.gz
    ├── 002cdbe5799c06583717616d84e8f48da0220544.nq.gz
    ├── 00328bcf29b442edc5d3a9ea752f5098e1673301.nq.gz
    ├── 003439844a4437f04680d2a13e6d73fc1ae30571.nq.gz
    ├── 0036af614567d709b669c6dfb62996b11324ef4c.nq.gz
    ├── 0042c05debc8061d8da67ef45b6f96ab5f978174.nq.gz
    ├── 0046ab35ac4a533a0fa9902f03f36f1f25390d8a.nq.gz
    ├── 0048a8fba417172073abb41181f01717c7eddfe8.nq.gz
    ├── 004f93ba683c8b8545ec4d4c84ad88b62a349181.nq.gz
    ├── 005043629fea569610bf9e3a07638364645413e1.nq.gz
    ├── 0054b3471b85f46566baead3ec7a19799b8b23b2.nq.gz
    ├── 005faf239bf84b199ac6d41730bcf49feedddf11.nq.gz
    ├── 00679a764f377a6fe8f0387e5861a1d4c941c0f0.nq.gz
    ├── 0068da96c0e0dc575dcb6d5a2c50e9f164306887.nq.gz
    ├── 006972935ffc257752fe96db29edcc6d0f26d918.nq.gz
    ├── 0069ca72a74fa8e3f7449e0973f32add10569f0f.nq.gz
    ├── 0070531884fc7f202dfd84d96ed7b046eb426f09.nq.gz
    ├── 00753a5af1a2473ffff500820bf45a13f00b7447.nq.gz
    ├── 00762dcc0027186911acf397779f618c556be8a0.nq.gz
    ├── 007f9ed7c26ed1028c994e8f9b2b6670847b60bb.nq.gz
    ├── 008321a49288b53e9dc66f4525fbc97c9273eae7.nq.gz
    ├── 0083b0c4aef64abba74a040eeb13ba08f058d4e9.nq.gz
    ├── 008d4d3fa59132ebe817946035552cee06d29731.nq.gz
    ├── 008d5be0ae3234cdb883a8cadb27ad94045c27a6.nq.gz
    ├── 008e0d83210f5acaf41081a1b9df25736cebdbc2.nq.gz
    ├── 008e268a350b0bd7151b7f42954070fe303e737b.nq.gz
    ├── 0090596e3732034d5453bd1471384ae1342f8d34.nq.gz
    ├── 0095a5e4a2898b89a2c5172dd95f59039f3008c6.nq.gz
    ├── 00965e7a16d4b77839360489da785badf67c7476.nq.gz
    ├── 00a320a543ce112d74bbb809ca14f0877125320d.nq.gz
    ├── 00a50ab05bfe387f6b109302210902ed6c527690.nq.gz
    ├── 00aa003e114b9afe92f84b57c21fc68ebbbd6de6.nq.gz
    ├── 00ad314f45dc03ec676faa59c7fa22366801b6f9.nq.gz
    ├── 00b0ea57a9d15d4f337bfccba2b5461f08098058.nq.gz
    ├── 00caa9d5b290d8cd82eb10549873e48a0c4c7ef4.nq.gz
    ├── 00cde7098983fcc9d8d5d1dd214072baf174a308.nq.gz
    ├── 00d6d0298753e120fdab23291a80b9e76e834813.nq.gz
    ├── 00da416b0475ea92fc8a14a257cc286870d7df47.nq.gz
    ├── 00dd88d5304be6d78a0c4d3579add091df95c898.nq.gz
    ├── 00deec94fc0dd0382cc1f6f14518ad7168d18933.nq.gz
    ├── 00e08dfd1ba301e6150eaabd20fdbfef97ed5717.nq.gz
    ├── 00e2fccf217e51120d7efec6621f07448e823246.nq.gz
    ├── 00e3efd02e076566ca93d6e6ccaad0c8b93cae50.nq.gz
    ├── 00e8cb18dc97689bb820a71b8b9eab9d3fbc98f0.nq.gz
    ├── 00f0137cda0b2033847d964f69c73747075a086a.nq.gz
    ├── 00f158ed53b0f22d9fb2cb55f43d326d962d62cf.nq.gz
    ├── 00f23116bf4c0d2dc24cb047ae70fd7f9cad1f7f.nq.gz
    ├── 00fa6488e261b1b6bdb17ab45e68bf47ad8f18b8.nq.gz
    ├── 00fc7b25a09e7be3f0559b91e76ef740b78b0680.nq.gz
    ├── 00fe2c1683f162131011e3dc472a774b98286b90.nq.gz
    ├── 01039b772c689f99dbf690c40988d9701b4fd02f.nq.gz
    ├── 010417d2d2b34ffd57b85f9a3bb2593e878cca72.nq.gz
    ├── 010584097f5e19e5d8b7d09dd9072929755a7b2e.nq.gz
    ├── 010dd158667b74d4b38d8d2e12ef0e094ade6e43.nq.gz
    ├── 0110e4b40e01032afcab8d9307c868895a7aba05.nq.gz
    ├── 0113b835073151e300c2cfd2918ead2cb4424e3d.nq.gz
    ├── 0119c931ba45143561330c8cabeda55c29a33212.nq.gz
    ├── 0125b0f421add8ff77f137402dc720a007c18b77.nq.gz
    ├── 0126b70ca47c3ded79ca35fef4708321baa2769d.nq.gz
    ├── 012a18155adb846fc94346ea21e0eeb3e7ed19a3.nq.gz
    ├── 012ac4dcb07fca4bf834320481c4ee9a03fa0466.nq.gz
    ├── 012b9269537012830accb50472aaded98738a68a.nq.gz
    ├── 012daedd1b106670dfcacbeb99af03e03568f4ca.nq.gz
    ├── 0130415bbff4f537b8778454b7c4c20e2449ca63.nq.gz
    ├── 0130f427d92b88bcb0ad7925fd94c4364d2257c2.nq.gz
    ├── 013654f2f212c9ff191094d87a0fd21b6155d3e7.nq.gz
    ├── 013b281e33d7b5dea4609640040a1b73da830056.nq.gz
    ├── 013d0919f24343cd5ada2a30d9622cdbd475e1e4.nq.gz
    ├── 0143660f126e1c8f750bce2b5fdacb5e198a28e3.nq.gz
    ├── 0155aa86df1b2eb90e042b2718a85d4cc8236f67.nq.gz
    ├── 01562090c6a9aacbc19b71e30f56188d6acf3ee0.nq.gz
    ├── 015f29e790101f6608b0be44193c0c53f02e2564.nq.gz
    ├── 0161cbd17d76909937f269eaff7d280e3ff89f78.nq.gz
    ├── 016626086cc2fffb4742828b0ca3566c0b53a713.nq.gz
    ├── 016d6e21c73bac54c07963773d01a02b2dd1e8c1.nq.gz
    ├── 016f3e9fcced72cce1f95ed0e3bab906819d6303.nq.gz
    ├── 0176557308ff0d3482088d0d0440806d5c0f4ebd.nq.gz
    ├── 0176dd428de0a16018a959d952feb03117069c25.nq.gz
    ├── 0179cd135f2026b2103474ac767eb237286a79b5.nq.gz
    ├── 018781ffe8e120fc788bc6ddb99b519d88c8dfbe.nq.gz
    ├── 018d6b053722a58944f39bc0b78bcf3262fa7fbe.nq.gz
    ├── 018ec884f49d3c6ab54c9077f7aa4c31dcfbd5e3.nq.gz
    ├── 01937e4f71aff1d5d691cb255a4d84b2166decde.nq.gz
    ├── 0197b7a88669e38ab49784fbbcb3893065c214c5.nq.gz
    ├── 019d7146b794059d0b4324d171ba8f55279ca568.nq.gz
    ├── 019d9a6e2b3a8b0d6510394aaa327bd2a0ad6bf9.nq.gz
    ├── 019db881a883382b5273da589023b73991e5ead9.nq.gz
    ├── 019df5a8f4866fa22296c4c1e94e6d6378e2bbf6.nq.gz
    ├── 019f5b400bdcef5942f4a0fbf811cec6d460768c.nq.gz
    ├── 01a05a8903e274faa08b0ac86c03734e06f4f9c4.nq.gz
    ├── 01a400f9d37583095629d224dfb0b81465a69da7.nq.gz
    ├── 01ab5b81a52e88871851e0992c281a92696485d2.nq.gz
    ├── 01b26c2e71c83cc91d1ad6ef86710eadf365bacb.nq.gz
    ├── 01b7f845462a980baeecb23b8810fe6cb9d569e2.nq.gz
    ├── 01ba4bfb06210b0f2d9afe095318068980fbb8aa.nq.gz
    ├── 01bc9bffb2b3106ec27f58a8968f8deef5ee3df6.nq.gz
    ├── 01c220d64c9d29768a3b97b7bdd0463067001473.nq.gz
    ├── 01c2a5491ad3f9529693fd08fd702c12e0a4aafa.nq.gz
    ├── 01cafeb9bcdcc56ff1bd6e89c8a445f99dd00519.nq.gz
    ├── 01cf3260aea2572aad3396544173e6c62fb7be44.nq.gz
    ├── 01d84494896d575c52aacc04646eae6b2b724ad5.nq.gz
    ├── 01d86590af10b247f7036f9df26d1439459173b9.nq.gz
    ├── 01e197dabbe03154f953fa6fd5d61e94e171fa30.nq.gz
    ├── 01e2590b5ec74957d359db414ab0591168129625.nq.gz
    ├── 01eb3a0e3d5a33725cd590204229078e43101225.nq.gz
    ├── 01f0985625d6308d3cb09189200007bd2610427c.nq.gz
    ├── 020847fcce5e844b5a6105964c89d869f6e98524.nq.gz
    ├── 020ac8d1b4cb804b89953fa7a3962079963c161c.nq.gz
    ├── 020cb1133cb0c30e6dd7330facb624f067323ff3.nq.gz
    ├── 021159df69dd1d7b14715d68040882b2cce8389f.nq.gz
    ├── 02162a55016352c973f40e71353ba5dbfe5f1494.nq.gz
    ├── 021725c15a5bd3ac1dae26403d97f6fd5d1fbab7.nq.gz
    ├── 021b5c3aabaa822da1554be726035a0643d63e5a.nq.gz
    ├── 022422417ed1c67db26836cb8996e704bdcadcf0.nq.gz
    ├── 022a5200a0e6fe86947c461163582c4d9d6640bd.nq.gz
    ├── 022d5a5003fe3cd5e535dea3ef307c39c4d04f38.nq.gz
    ├── 023837e05d63acddfdf2cd5cc0508fbdfa2e9427.nq.gz
    ├── 023c07539e0f12da3297c7424da182f1f7cfbb98.nq.gz
    ├── 023dd32983261bee23ea1b0966112c58cf733998.nq.gz
    ├── 02407720065202c0acea30dd3e9d89786b2ef649.nq.gz
    ├── 0241008cc1f2353a8516a0783c8b894f30873d11.nq.gz
    ├── 0244923d3b449a78ec22951d2bb94e15fe958059.nq.gz
    ├── 024546de4fcd30f1eaf961307452d3408ff50061.nq.gz
    ├── 024a0f23ad54fe473f3095104538534bbfb53a22.nq.gz
    ├── 025012792cbb883a0c0fe9f08b9c4a53b351a30e.nq.gz
    ├── 0250de251bd2deec1d3a5622895bf8621da90755.nq.gz
    ├── 025212527cae1246b6014e5f650d2a8e76417f67.nq.gz
    ├── 0255121da4a045979795b9922f7a9c2be1bd74a9.nq.gz
    ├── 02569a560170b8f8fb9aad3986a2baf4e0bf108c.nq.gz
    ├── 0256bd2c85022a3287e3c7744057d988acc90ce5.nq.gz
    ├── 0257f6d046b6735bf644950a9ce25f522f5fca8a.nq.gz
    ├── 0258b83a5ff5c924a65740c00a89b637a0559a4d.nq.gz
    ├── 025c56cdb69af291b11c29f1a2c72b1f6654333b.nq.gz
    ├── 02647eb845188f18f06d9286b83dc886a1614a52.nq.gz
    ├── 026561b45419d9f86f6099620779792820842d68.nq.gz
    ├── 02672804e5b950e886d637e34e0f533aea7d48f8.nq.gz
    ├── 026b114889cd11fb7472ea61af5dfb5c1390639e.nq.gz
    ├── 026cf067c6117f3c304f76f839f8cfabc2eff8c2.nq.gz
    ├── 027f2750c94183b4a10684c6c9f315601c6aeb60.nq.gz
    ├── 028c4092a5b8cea4853f5d9f3002f49cabb5d108.nq.gz
    ├── 0293074e646c11e3fc6544e02ae29602c6d29636.nq.gz
    ├── 029de2cc4b9da0ea6d2e6b9b11f49e377b5e57dc.nq.gz
    ├── 02a089f43e6722f29f3b17b0804603031e6fe562.nq.gz
    ├── 02a2b1ceea94b145c2cefba94a33c8ee69426670.nq.gz
    ├── 02a523edebbddb3482e7ff738a4ef8037857d167.nq.gz
    ├── 02a57a1ce9266b80d5026b326bfb98b3cdb74fbc.nq.gz
    ├── 02a8faa77a4509cdcae144dabfd8f52d2aa9fbf1.nq.gz
    ├── 02aaa3ce5a8fe18b5e1e0f28a46e2f8275555bef.nq.gz
    ├── 02b518e8695a2b68a42035a319329ae483494654.nq.gz
    ├── 02b9ee4b212ea3276eeeea851e7d6df792996eee.nq.gz
    ├── 02bcb9e50ef547defc527911b18396631f9d989f.nq.gz
    ├── 02c0d35d64f50a417444f47db4e457343deef257.nq.gz
    ├── 02c1eaa3d7f3d22a42c9e8a732751a2d83e86452.nq.gz
    ├── 02c4f9fb3a85e3f489c372b2fb9aa8f7897cc2ae.nq.gz
    ├── 02c9618270481a7d86b327c5b955ca2c5f583cb8.nq.gz
    ├── 02d018f93726052eb0f5baf5dc67ecb3ac882795.nq.gz
    ├── 02d4fd946a61f2e842679ced585b958ea8c4ee9d.nq.gz
    ├── 02d64f04708bb44ca38bd012df02d5d19fe2c76e.nq.gz
    ├── 02dbe34b721b9b5e04cb0048fde6314a688794cb.nq.gz
    ├── 02dce6e9762000a994938a4ef9b2166c7a2e67be.nq.gz
    ├── 02dd3252c5d1257737fb02a846eb43951030c2df.nq.gz
    ├── 02dd890623a0d8ea67de76b76c4be64f1252e8b1.nq.gz
    ├── 02e66c19346d3222364f705d68260a9cb96a7406.nq.gz
    ├── 02e7f81659f5a224cb8aa3d3a661e99972d6b0e6.nq.gz
    ├── 02f2c6b2b3aa7a2ed27c2bdf14edb14168a99429.nq.gz
    ├── 02f659fa646869204b2038dc86226231889a5de8.nq.gz
    ├── 02fa848dbfa641536f68f4562a0a624f4f521cc3.nq.gz
    ├── 030516a822f7cfdae598360752ddd5ea5cfb454a.nq.gz
    ├── 03055ad36c25d021d25331480653cfc02b809e06.nq.gz
    ├── 030572528bf4142faf4284c41a2375671c257ec1.nq.gz
    ├── 030933b32e8b0b97a5888683d6af27076efbfa50.nq.gz
    ├── 030edb2eb37264c2e9e5d410a9ff2a468dd73d6b.nq.gz
    ├── 0315184115e4cb46f1e0cb8f767239a7466aec3c.nq.gz
    ├── 0316e2aac27444ad0296847af8ded54885aedb59.nq.gz
    ├── 031721fc247633ece24334aa0d3eec7a8aea3caf.nq.gz
    ├── 031fb96e8937f3b6aa9f830a9a06ff56fb2a0d60.nq.gz
    ├── 032268912195cc9638187105d4c130b321d72c18.nq.gz
    ├── 0325c7f6c63783d662342a78c6f4f7f8d624457e.nq.gz
    ├── 032691ee3eb6f6afae1b1dd5f969f2877abf541e.nq.gz
    ├── 032c2a65f1b6b57e9768668fffc11cc261d22f9b.nq.gz
    ├── 0336be88d7f87aee8d1b48c5c02a901735ec2a56.nq.gz
    └── 0339337fbff1aa1a2a509feb613b6a2ab88f70e2.nq.gz

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

## Source repository

[langchain-ai/langchain](https://github.com/langchain-ai/langchain)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*

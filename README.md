# Repolex Knowledge Graph of PyCQA/isort

RDF knowledge graph data for [PyCQA/isort](https://github.com/PyCQA/isort), parsed by [repolex](https://repolex.ai).

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
lexq download PyCQA/isort
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a333737ed43df02b18e6c95477ea1b285b3de15a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a333737ed43df02b18e6c95477ea1b285b3de15a.nq.gz
│   └── repolex
│       └── a333737ed43df02b18e6c95477ea1b285b3de15a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0677724de51a77dd1bcc62326b63184389acbd3a.nq.gz
│   ├── 069171357873987db2bd35adc46bdfc7f05e3af9.nq.gz
│   ├── 08a365e19e18d65cdcb42611ebb4824ffbfc9a7f.nq.gz
│   ├── 0a519cc6e292b6810c96df6b04e9ff4d4f0f952a.nq.gz
│   ├── 0a7a73baac0b2a28d48818580fcee7988fc438c7.nq.gz
│   ├── 0badd0a8bc17e58f24b7031c77356c0db583f9e8.nq.gz
│   ├── 0bc7a0fe80e9e8dad6bf4511e9858aeb0ef7e901.nq.gz
│   ├── 0fb525dcfca4e961e7fd4365f5bc5a106d785b4d.nq.gz
│   ├── 0fb972de0ef318321433cdce7889c0943948ad3d.nq.gz
│   ├── 0fdab29dd7e7edea44d2e469bd26ff6cc3f66378.nq.gz
│   ├── 103e1105a3bcf816adf652d649257595ee4dee8f.nq.gz
│   ├── 11830681f470b3293580dc754e1df484d939c9cd.nq.gz
│   ├── 120e0516ca381c2693e9bdf5c7ef593d68796662.nq.gz
│   ├── 149639dc4a65292dc2a3c84c8613d16d72007c2a.nq.gz
│   ├── 14f3a6322c56a35cdae48aee9847de0b0b8a9f50.nq.gz
│   ├── 16ddcba08e8165de619b2ffbe18c8c8383fa1fa6.nq.gz
│   ├── 180a945704f8f67a0a7947990b4e5ad7f0d799cc.nq.gz
│   ├── 1b8a961c7ae9acf5dff1e4bf06a93862dd7cf016.nq.gz
│   ├── 1e0dc2a9e37aff2238ec5eb91689d8100a249d4f.nq.gz
│   ├── 1e8d5d6154cc932894003aa0d01e93246827896c.nq.gz
│   ├── 209d83d8233318a17342b88eb088eea70c164d2a.nq.gz
│   ├── 20a9852807223590b99406d4b57d226756bcdb05.nq.gz
│   ├── 2aacfc2025b7c927b52aa6022986348803d7a18b.nq.gz
│   ├── 2bb857855475b37953e542b53f4c1ea67dca4ea6.nq.gz
│   ├── 2c4016d080d7f050e7dd2b41a91a1145b03fc7b6.nq.gz
│   ├── 2c4ee7232c6d3058c3f31ab8ea56fc51e8272278.nq.gz
│   ├── 2c514ccb5d88be43d7eb59c685d455da02771429.nq.gz
│   ├── 2cc3c5a6932ab04ef89c06821c271f0afe8e4049.nq.gz
│   ├── 2def240f304e47d85cdd3ba46954c20d7de66a4f.nq.gz
│   ├── 2f863b35cde6ec5ba566d6772975a589880cd70e.nq.gz
│   ├── 31ae8a6c419e850bbc5c453ab35c63e879fd2999.nq.gz
│   ├── 32f483a8cccff71863b33eb9d3779bbf1ebbae86.nq.gz
│   ├── 3397b30c92e71856bbd562d5b260761f376cc9e9.nq.gz
│   ├── 34d4e3023b55d924a96525114c5c7e60a3eb419b.nq.gz
│   ├── 35f643bfe7fe3a625e6a35b7fcaaefae3ad9be1a.nq.gz
│   ├── 3919c424583f61450dbcbc8c36de30724829803b.nq.gz
│   ├── 397b6f92358ab106dd4a075609cf80c73e8419b1.nq.gz
│   ├── 3b00ced938a009d4276c3e56de974e77aab6fc3f.nq.gz
│   ├── 3c80af85048cc5acc2bb1ea100caeb9f00b74605.nq.gz
│   ├── 3e69230e7d6d7387582f55b8b144dda52b4d4262.nq.gz
│   ├── 3ed8b52efe8ebea5d8fe8160a27cc26112b15689.nq.gz
│   ├── 440d596c02f20d074b87e19f3bb0929ebb1a85fe.nq.gz
│   ├── 4457efe6d26635ce7da9ceec23dc38c5e54af5c6.nq.gz
│   ├── 499655d23142ec3a6dcfd58741c57fb37e01505d.nq.gz
│   ├── 4a8ec67f6caaa189ddeb1467c01e7cfe54e9e1e5.nq.gz
│   ├── 4d8b873661f1354f87120c0c8c90e93763798442.nq.gz
│   ├── 4dc347b1ef9653f8a55ca2fdd537f9661dcb5664.nq.gz
│   ├── 4dd85b70cdf562e2784ab163e854a9ed32014ce5.nq.gz
│   ├── 4e76f5675d8dcf977ed1dde5b60b6a0e2ac1900b.nq.gz
│   ├── 4f7b163862cc0b0e14b1603ef639794952845769.nq.gz
│   ├── 4fc1578b35e0a18ee84f1d2b236e3c4b0ac25547.nq.gz
│   ├── 51ad3d812743e19b7c367fbfb1a993221e7f9f60.nq.gz
│   ├── 5284146ebf2bc6a26f50fefbe5ebb91a3ba91448.nq.gz
│   ├── 544f98b2155c9c72a753d4713d8a2b5e3a823145.nq.gz
│   ├── 54671a6b09d9020d9b38e612b222d2bfcc2d4190.nq.gz
│   ├── 580a48e9399c2d6623442370733dcc6a533ddc4e.nq.gz
│   ├── 59ebd24cb403ab0a6b79fdc8cc35276d719558c3.nq.gz
│   ├── 5b9f2478d8ddae3ee78734baa62931714e974f19.nq.gz
│   ├── 5de32d5811c96d67b6cff890721ed901bd379cf7.nq.gz
│   ├── 5e3e45b6efe7911c80fe99659724c997e25f89d7.nq.gz
│   ├── 5f0813d2ef3cbdec8dc06f47a5ad97142b9c7177.nq.gz
│   ├── 6377d8686ae49da731d108dc86095c560dfa36e5.nq.gz
│   ├── 6516f0b2e7688a8f432c839afd376d12853f38f1.nq.gz
│   ├── 65c5aa6025f50b08221336adc2b0fa4e6e487fa5.nq.gz
│   ├── 6b0d9be90d29536b1483c62e284c26d9cbaa5355.nq.gz
│   ├── 6eeb01787a0929189ff0e55bad4c7cc44ef3aa7f.nq.gz
│   ├── 6fb514421bd1dee6cb07c3cf00838a700c169426.nq.gz
│   ├── 706ecd8b2bd4a344c0deaac253c23f28ae24e9c9.nq.gz
│   ├── 719357aed804a134f4f07d1b599f0d3627a2a583.nq.gz
│   ├── 74af019e4910b5243a38939e3cd620b3f1d843e6.nq.gz
│   ├── 7615952c1a5f05332f2cb1e73f984c4072c8a946.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 7878148e5c3d9ac85256873a07895a246f03cedd.nq.gz
│   ├── 78db95188e0f17eb7a56a378523c33a6e4664b84.nq.gz
│   ├── 79a319093cd70d2b2cab6a7c9e44c74e4c3c57fa.nq.gz
│   ├── 7a1c706bbe411059bb55760ac2554e893c5b6a0d.nq.gz
│   ├── 7ee6acf403331312c0bf1e0c28f53c98ba2a5c17.nq.gz
│   ├── 7feac7fea31cd963fa1eb27fb985cf5c3a499818.nq.gz
│   ├── 8193b489b20e38d1afa641d6b41ffc6834553913.nq.gz
│   ├── 8238aa1718e31ffc7c4323c9368e78c807464bdd.nq.gz
│   ├── 83477ab00fa864b6a9bbb1fcf2893d451f27d682.nq.gz
│   ├── 84671cbbbaa406c44462805c1e205964c886279a.nq.gz
│   ├── 87027978b91bd71b19f2c092112bc2d6b12336e1.nq.gz
│   ├── 88be082101a31ccbc0847cd2e36d1622f7e95193.nq.gz
│   ├── 8c4ad7464370da553b6c121d9058c860730cef61.nq.gz
│   ├── 8db66d3d0f0f25d802c0ad5de1a019cce94d3d47.nq.gz
│   ├── 8db747831490756719b523b89245dd431cb8b78e.nq.gz
│   ├── 8dc2acb8c4bd8142011c04d66b83ae22d62f04b2.nq.gz
│   ├── 8e72565e22ab3a163aa6358375eca8c271524bce.nq.gz
│   ├── 8ecd3eea0d0f07aca50852ff875f0c6e76ed3729.nq.gz
│   ├── 8f12c5d811e17720535fb045ebd9ecf873ac5a0f.nq.gz
│   ├── 8fa5761b8dc133b75191f4c36033ff8882391102.nq.gz
│   ├── 9015a187017ccccdfdb29c3cbc038d2ffff9c988.nq.gz
│   ├── 92e3d132db77e340b4badd7b6f733e0811b7703e.nq.gz
│   ├── 94b1d057bb0c56e009182d3aea87a48b9b59b7bf.nq.gz
│   ├── 9824c23b227b7a04d23f38cbc4c1130df8be1fb8.nq.gz
│   ├── 986ddd5ded25cc6dfa9812a0d0cf428152473208.nq.gz
│   ├── 9a1235db9c30c4bddd50079e6e1d5dfdb20b9fda.nq.gz
│   ├── 9b99615980b9d5aa308ab152169b36e9134cd19f.nq.gz
│   ├── 9d99ce0fbdcb69d2a7ef6ba5a2e6d2f242b4e6f5.nq.gz
│   ├── 9e914f681dc93f944cef2bf21757a893511f34ff.nq.gz
│   ├── 9f50ec85d5a583ba7621e4e24807acf002e45a33.nq.gz
│   ├── a2caa57af33b980006f8d8da519c7a8740aa1c45.nq.gz
│   ├── a2da94520e7d6d361c3f2ce760efb7d53e5d14a3.nq.gz
│   ├── a39abf1381f07426381d7567a4147a0568617d98.nq.gz
│   ├── a3adb3cd42643756431ebbacb9fddf45523f881c.nq.gz
│   ├── a6091b724a2140c14230122772ac81db4ced2c72.nq.gz
│   ├── a72e1a876fa1b745c3dc1f649f7fa3ed7ad01e1f.nq.gz
│   ├── a8dab50a852f6b320d9334f42a9651bbb888241f.nq.gz
│   ├── a99acdc132180748e0a8afcc5db0d6b8eeebf9df.nq.gz
│   ├── a9bc99d0c7d7dab82c075c965f094162e5b876ca.nq.gz
│   ├── aab533567b7a92ef3dc33de8cb7650cae02a65d9.nq.gz
│   ├── ab36adc02c2c01cf5a8bbb4f4f38f56b8eaa4fa7.nq.gz
│   ├── ac1018add7bbfebf7ffd0bbb70eb99056ddaf2d9.nq.gz
│   ├── ae64ec9a97a1b054f7e22cbcdcf06e8419ef4182.nq.gz
│   ├── af9020ffec0cc4976b6ab915951e6624d93bbef3.nq.gz
│   ├── affb5da427ab4798332b9dc2499b9d85be98ce56.nq.gz
│   ├── b3093b344b8e14af83d0e54d00fbcc120e001179.nq.gz
│   ├── b4d8ed1a41962a807c47da1810888728eed7dc7b.nq.gz
│   ├── b5083a50d8cf8c6a404a0584416618915c58acf2.nq.gz
│   ├── ba2bef8951fbd8859e057db4ea4a936ad621585e.nq.gz
│   ├── ba6cc23f71c0251525578d33e0b90e26abf32820.nq.gz
│   ├── baeb7baa73cc9705b72cff9d48357b67aade6065.nq.gz
│   ├── bb5f9b0b40828fb61b0bf602ec75d929e991de72.nq.gz
│   ├── bf2cdf292734c2a7ff445e7a72693691e85782de.nq.gz
│   ├── bfb8db03540e1b586a43c93f835f99c6f8c3d484.nq.gz
│   ├── c08f184efef2fb0a402c2434761f6f17bb9abe9d.nq.gz
│   ├── c2202717fbe7856c36dc710b5611d31e3ebae871.nq.gz
│   ├── c335e3a39c53e42e1019cc99edbbf04402afa130.nq.gz
│   ├── c41ce4ecda6c512bf51f283dd5bbe0943e36f9db.nq.gz
│   ├── c850c689a6a5fe183eaaa61731d3e803c9a09525.nq.gz
│   ├── cb325ed7431df6eef7102e99e7dfa5782c68bffd.nq.gz
│   ├── cb42b15955e8ed79832ca70c12b60d9a0949adb2.nq.gz
│   ├── cc4a97fd814a9439508b9697bc2016dec4753a49.nq.gz
│   ├── cd32c7bab0a61a1d330d1de889d24cbcb3509595.nq.gz
│   ├── d2ebd9d8794a49b2c5cc5fc1c11867b523539689.nq.gz
│   ├── d3ae4c35aef88f877f46f53c834327ef3168f5a6.nq.gz
│   ├── d43286e95d78f1e6f4622858085af4ce0e5d14e3.nq.gz
│   ├── d67f355ef014808280c83ecf879557101b89535b.nq.gz
│   ├── d8efe3f07f31933d03e56c440c24db71df2a8741.nq.gz
│   ├── da197719d3b7b36ac4465cad9bbbb49759a05f6a.nq.gz
│   ├── deeda1e7a00269a725dbae96ed8c2fbd7ef941ec.nq.gz
│   ├── df8c1009cea3b80158178c21e1ea409333273e51.nq.gz
│   ├── e0ad1228a83aa38df12cc5b6c0c103b0d777c753.nq.gz
│   ├── e0c9eacc5192cfc839580846ab36771c40c6a25d.nq.gz
│   ├── e52548c4edefb0d190823832afa5271b5fde3f24.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e783e27c0e65c5134bea500c564e1c3a7ad84019.nq.gz
│   ├── e859590f886cd78344206af1a8ccb3080d4385e0.nq.gz
│   ├── ea0b68ddbfc60af01843412fa6a0a7dc97070a5a.nq.gz
│   ├── ead243b262611f2ee2518c635d470796c4c2d329.nq.gz
│   ├── efa129d0c31083c6c1d6eb9dad441b60232d56f1.nq.gz
│   ├── f011844376b5fc406d1681390e387083914abc54.nq.gz
│   ├── f10b3ee61acdba86749e0dfbf729ad465baa8de6.nq.gz
│   ├── f12cddba38e4e5908e71b5ed2f8b3a5766bb7bcc.nq.gz
│   ├── f3ce1fd32b68e6226db41325157c0ae13badd862.nq.gz
│   ├── f3d528fed2d378172ef08f61afea98f759f053b6.nq.gz
│   ├── f3d7ea20ec7cafb10a016ac5e1d5321a4d00db69.nq.gz
│   ├── f5bf73f1f4eb124a32d2f5a715ee919d20116f18.nq.gz
│   ├── f5c898c0a55f6a44ee71369f167a57f52b187b19.nq.gz
│   ├── f63b817e8ddb2a56ad2d8afa3324430d25dfcb36.nq.gz
│   ├── f6769965dfb888a5ed2c1fc56d09ae2b1647d2f8.nq.gz
│   ├── f6864f6a2bd9dc9d2835c1a01188acabf9e02510.nq.gz
│   ├── f6ba3c3195fa965b18e0502128b49e0efbf48070.nq.gz
│   ├── f6c6ac4f2902198fbd0835d25881198ae3253cba.nq.gz
│   ├── f85df769126d90e1863f52b187eb09eb7587a2b6.nq.gz
│   ├── f92ff12fd30a1f6ddea8778d0862df66109dcb2a.nq.gz
│   ├── fa401ed7349cc2ed8129b5b877dfde3362e397f5.nq.gz
│   └── fad53301b8786dc85f33d1db23116c3f24343c44.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a333737ed43df02b18e6c95477ea1b285b3de15a.nq.gz
├── filetree
│   └── a333737ed43df02b18e6c95477ea1b285b3de15a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 179 files
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

[PyCQA/isort](https://github.com/PyCQA/isort)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*

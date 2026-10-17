# Repolex Knowledge Graph of facebookresearch/xformers

RDF knowledge graph data for [facebookresearch/xformers](https://github.com/facebookresearch/xformers), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/xformers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f701fad69a6308e6b9f0c3f7863c40c881b30a7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f701fad69a6308e6b9f0c3f7863c40c881b30a7
│           └── chunk-001.nq.gz
├── blob
│   ├── 008578dde730ea6f58ece08d4904dd7c97e9a740.nq.gz
│   ├── 013b6ef00461021253a9ccc4f0049490f0f74721.nq.gz
│   ├── 015e3e36f2f1eb4a4f1738ca41411f72afac288e.nq.gz
│   ├── 01c1958543f938829346b858c708ab8cad129ed9.nq.gz
│   ├── 03984221ed46ff2183b98f8e0435d4affa5463ca.nq.gz
│   ├── 05b9d8cfc9a7a748eba81c581c194a1e7d90cec9.nq.gz
│   ├── 07bf0426ee44c48a4c58f026195704a53b7a2867.nq.gz
│   ├── 0a8ab8e0f6ebcc23b8aa5eaa5dfad7dd70c8acee.nq.gz
│   ├── 0b67bd3ef16989d587a9483974f3b95c86c32190.nq.gz
│   ├── 0e618f556bc8d0de8d7838287c88384aa39b64d0.nq.gz
│   ├── 0eba49933b099ed069eb1f41df2e795bacf72843.nq.gz
│   ├── 0efda94c9adfce93033ede347820f2d1aad37ff4.nq.gz
│   ├── 13908127a3d2e12cbfab03dc7e4a55de176d196f.nq.gz
│   ├── 14d2cd4d192bb8f5818d6cd2729c22aef40adbaa.nq.gz
│   ├── 155069a391da5b53d931c94d552690c07ce6f854.nq.gz
│   ├── 171165df640fcfbb1ae518cc671b91049f8df87a.nq.gz
│   ├── 19662af6190b86b18ccbf34110271d307739beb8.nq.gz
│   ├── 19a6518bb158d7fb58a1195e90f331c982297d6d.nq.gz
│   ├── 1aed84293060a5606be9ac27d816e90d96b0db87.nq.gz
│   ├── 1c309c727141f12e38e1de0ca2285c4ed73e95d9.nq.gz
│   ├── 1d5a2612af88bd9575f024b25251e1ed3762469c.nq.gz
│   ├── 1e9a0d908c9b9df46e676ec607ae354b12c9c629.nq.gz
│   ├── 1fb4f876e284b2657bff91bc46d010faed534dd4.nq.gz
│   ├── 20af4303197b9574d12da0c06fcb8bce06af71d1.nq.gz
│   ├── 20f21d64258380672f815a34d4f913fa8e71198e.nq.gz
│   ├── 2252e54df64a0493b2f714da3491cecd7cdd5a9f.nq.gz
│   ├── 2329a38c4f6ad8c213a364dd036f371e89580962.nq.gz
│   ├── 26b059fff36f715a4b590189fdeed6ba9d0818c8.nq.gz
│   ├── 27c8acc947bda39893978730f197b6b307413396.nq.gz
│   ├── 281cb2d85d911041de95f70eb121ce1021597bec.nq.gz
│   ├── 29cfdb2c3109d37cfd136f160afc518ec261a31c.nq.gz
│   ├── 2ab6b9f1782eebe400ca74c1edf28e19b218349c.nq.gz
│   ├── 2ac45f83402d52a416deec7ddac52a040390916d.nq.gz
│   ├── 2e638133aaae49a3fdd877216c7d634fa1251225.nq.gz
│   ├── 2f489fce925e819695d9bbaa062195f354cf08f3.nq.gz
│   ├── 30a7d0d67cdbbc0e51d8ed1e9088a255b8db9318.nq.gz
│   ├── 31f9748038ad87e40bff653cf5b25550af872921.nq.gz
│   ├── 3351051baa1855a96a5229d03ff97d1bb041f4eb.nq.gz
│   ├── 3594bdef06cc259291eeaf61a0bb08bea2d9da49.nq.gz
│   ├── 35ea2b4235770ee501ab1aa64182bc8bf87093bd.nq.gz
│   ├── 36c293df6deeca069eb33e907bad50519bd721df.nq.gz
│   ├── 3845b3d583c771189bc67afc46dfa3c77b679a3c.nq.gz
│   ├── 389cadd2ca13b8f102b22d35310bdfbebd64dbe5.nq.gz
│   ├── 3929afea05acbb1375cd7a421cec67f937d5c258.nq.gz
│   ├── 3ad97ec50c114e0bbdcae51ba696b4e76546196a.nq.gz
│   ├── 3bc943c6022144fcec34afa3ba66ee35f6554539.nq.gz
│   ├── 3ec9d69222b9e27a6554352291afc3e171e1c472.nq.gz
│   ├── 41b4653a299d9c44912f8325b82b8c7edc698e03.nq.gz
│   ├── 41bb32767dedef9975ff5b1826bd25f1aacb708e.nq.gz
│   ├── 421adce4c2439c54cb0da14d0e8bdbd7dd79e491.nq.gz
│   ├── 44247ee5d8e844293369e73887e899893ba1d4c7.nq.gz
│   ├── 4489be825918adb760658b868c405c87ca1d12e9.nq.gz
│   ├── 4555634d3e51beb788e94ac535d01b6482514a5b.nq.gz
│   ├── 470756ae266970ad1f2f81e55555ae1412167b2b.nq.gz
│   ├── 4c1b05e5ec8e72e98c2017c3babb71e235f4572e.nq.gz
│   ├── 4c2726a27f55d4ef2022464e6ef3e5184c06b1e2.nq.gz
│   ├── 4c4eff9d035c9906ddad13a8da3e580ce00b7679.nq.gz
│   ├── 4cf98c0412c5765e9bbf2e62748b0b7e74f6d6cf.nq.gz
│   ├── 4d31db0d6b1c6e1becd914fd9fdce3dff7a9121e.nq.gz
│   ├── 4e22ae0574c7d785c9137677181a249fdaa489aa.nq.gz
│   ├── 4f7b7ad627bf05cbcfa7429d3aa4a9d59ea881fa.nq.gz
│   ├── 4fafda54406130daf957b428b3e5e446fbdeaf3a.nq.gz
│   ├── 50391826903bb338696e1fcbb59b707b9c6d55bc.nq.gz
│   ├── 50433eaa792d76585cd6e217b1944d993957c894.nq.gz
│   ├── 505ef15e65b7638dc6332f4204793c708e7c5ae3.nq.gz
│   ├── 50a8b02e25d88e6533475eb9d32233f5ae710aae.nq.gz
│   ├── 518c7d5f7cd0a1c5f997dd447fdbaebd20b10500.nq.gz
│   ├── 53af9a9f728fabc0fac16d0cb8d5c015e66d293c.nq.gz
│   ├── 54812aba551489d53287ccdf3f39ec60ee0eb9de.nq.gz
│   ├── 5b9c269f0d67378a1406969231c51db225c9cce4.nq.gz
│   ├── 5f9e160f256917e67034c7635d022f73f9e2e3ab.nq.gz
│   ├── 600ef3f85db7af6280d712de801a156358d9589e.nq.gz
│   ├── 6126ff699e9e6026373293a9bb629e83e5655943.nq.gz
│   ├── 619bd4fda8f08902d27b41c09ec883430ec8f487.nq.gz
│   ├── 64b1adaeeb48df78f5ca1b2f4611553d907b17b5.nq.gz
│   ├── 64b2ad6b8cf0c41915a181bd30512d2f75c7c8f4.nq.gz
│   ├── 6677db08c0dcd87f7570a3249f61cc3eabe0532a.nq.gz
│   ├── 68bd94236177dbc1bfceac37e7619c685980d0d3.nq.gz
│   ├── 69515ece8f9cebeb02868156ab7c3e0abdb80489.nq.gz
│   ├── 6ab6bacc1b0697997beb5cb6cfb802a2ea80cee0.nq.gz
│   ├── 6b016d020deaeb21405a8cb78d580d2f514886b3.nq.gz
│   ├── 6d0ab740db4bd2ce6debe0008785a7d7c7468461.nq.gz
│   ├── 6dc9c56d1359b48c32a11e773e8f90b94903d6e8.nq.gz
│   ├── 70e1a9215633323c816c1b466aeb98af6d6eda7e.nq.gz
│   ├── 72151185e9d28d59dd309785716575de01102349.nq.gz
│   ├── 73ee0ebd7d4870938d84a3ccbd8f582195a003c9.nq.gz
│   ├── 754fac7fe7eb5fe26207cb03c89ddcf80ae86a31.nq.gz
│   ├── 7594f941044ff8bff4cc70a2a90b59db9fce635d.nq.gz
│   ├── 759646f9b1bdbab06093a674e9b05c58dbe75f0d.nq.gz
│   ├── 777847ef319d2198ba4c8e3c015825da9c770be0.nq.gz
│   ├── 78e5ef266685550905ac185302b5226977d04b1c.nq.gz
│   ├── 792077637f0bbc45be8e37343468243ee1d9d33e.nq.gz
│   ├── 7d35022303733889fb4280cfae1f2f493559d5a2.nq.gz
│   ├── 7e61edbad408097be4f07348da26d17cec931b32.nq.gz
│   ├── 7f1f27e54cee534507d7a8b73f6af34a395f1546.nq.gz
│   ├── 7fc1171db92cf13488bbe405a9e7d4014c0325fe.nq.gz
│   ├── 7fd155b1fb5f7563420d9e6d56366f0b65dfba24.nq.gz
│   ├── 821612ffecfcb9bd94d8fdcf0ea1a1c536821a63.nq.gz
│   ├── 8305309ed7f43180211655bcebfc52de242127fb.nq.gz
│   ├── 83f431e8feeb7e80d571f39c9f6c1b96857b5f85.nq.gz
│   ├── 848628bdc90cb3d3072ee76f2efe1014e1f3da0a.nq.gz
│   ├── 85dcc85b6489b5d733e2c2ebf7bf14e3c588d7a7.nq.gz
│   ├── 89723d9f30a0d18c793dd83b37b0fa5c4c53ac6f.nq.gz
│   ├── 898be2c2ce0db581b16b22eba79542703112d64a.nq.gz
│   ├── 8f7381ea3bce1c4df670d97630f273f7db79589e.nq.gz
│   ├── 9021f8c5a4c7a89ffdd6cd2bda83f7a79d8deb7b.nq.gz
│   ├── 903c38a0e9c97970e3308b7c2c0f248f020086df.nq.gz
│   ├── 90589fe9c8ce2b5b0984c6531af35a7b9c729661.nq.gz
│   ├── 915b9476d1399523df844335e1c374df4dcb68eb.nq.gz
│   ├── 93585723e8c36788f771d37d990d3b3868bd699f.nq.gz
│   ├── 94283d74785f07940a7425023ecaa4bc5e304bb9.nq.gz
│   ├── 947dd94ecd8d685c3aa0524a49e9073471cb4b7f.nq.gz
│   ├── 94a3743fbdf57e98fb1697bfc4f8a391d6a27651.nq.gz
│   ├── 95cb128885e073b1b2fbf8ffcf8b923930bc252e.nq.gz
│   ├── 95d844d354d42ef0e0925c4077859e3112db2350.nq.gz
│   ├── 96de3e714851841902bb4f7409ff5bf106f44ded.nq.gz
│   ├── 97d2afe2e1af86b6afec8ede2c8954acc5b4c475.nq.gz
│   ├── 986bbe82dcbc3b4bcc4e2ae87236ecd69f84d956.nq.gz
│   ├── 987278e4484cf8c9db03ddfaa394c58807636058.nq.gz
│   ├── 98fd4edc794899322979d15703c1dce949a0048b.nq.gz
│   ├── 9bc445c7709cfbdc25b5739d7cc825188501976a.nq.gz
│   ├── 9bf76aa69fe4583763a790a27e9ee83cf18b27f0.nq.gz
│   ├── 9dce9b28eb9cda3ee74e9349ddadfd139a7e73e0.nq.gz
│   ├── 9ea7555fd617977f21178bb5c26db0060004f42c.nq.gz
│   ├── a2ca26c3987c0320f6fc323300c501d745f9b438.nq.gz
│   ├── a3b9db039b25a4b494591aed9bd425b0d4eeac3c.nq.gz
│   ├── a3c83312346f392ddf461231e97b7528e1154e19.nq.gz
│   ├── a759bcc014abe51d14a5a369ad5aab915204f4f4.nq.gz
│   ├── aa3e568f9536cdc65fd5bfb3131bbb77cb3c60d8.nq.gz
│   ├── ab1fd96cf1fe1cdc11bb3526e3a7e511071cd966.nq.gz
│   ├── acc2c2ca9a919370687f57d417cb2cc6b9003cc9.nq.gz
│   ├── afc079492cbd19cc91244e4341731002583d8d03.nq.gz
│   ├── b2bec9d76c6058a1d264860610e76428e26e326f.nq.gz
│   ├── b60ef6eb8508a0d4fc6da79fc2f1eb3482724dfe.nq.gz
│   ├── b6e58c01ced1c38c50500b8870bf1b590af6219b.nq.gz
│   ├── b8b781d04f13c99ef90fce273da8181cf2cfe0c4.nq.gz
│   ├── bb219e4dc1482bd2727af0bec01d427cc2bb744d.nq.gz
│   ├── c1742b1d2f438fd92931482efcec857770022c54.nq.gz
│   ├── c22e4b5b10bfaef2a851f54e0d6dd180c0a36973.nq.gz
│   ├── c440af801f0438a5fb8b36822001f81c357c455d.nq.gz
│   ├── c476e1c5ec62278a681a6736005f31bb96f91473.nq.gz
│   ├── c4db8cd8faa69439a1c2aaa01e0475f9eb74df95.nq.gz
│   ├── c4f0d2cfeecdef2b18ab409d8a0d4f06d688551a.nq.gz
│   ├── c561656b13a1aad666fb30ea34e5111796059f97.nq.gz
│   ├── c90d4568d06268dd60b77254ce6e3462cc769a08.nq.gz
│   ├── cb64bb912dd6d368851222efb75673db28f73113.nq.gz
│   ├── cd0d646a53917524a9855e5977b827eb1ee5420e.nq.gz
│   ├── cd4bee0ee14e8a8ea47bb23e71c458b795ab0508.nq.gz
│   ├── ceb4e183d12d1b199e05ae2a20b76403b8306abc.nq.gz
│   ├── cf2f12b4aaf1fdd2e15c7c23169b9343bbc13ba5.nq.gz
│   ├── d01e5c740b0ab3526d944029f653929f9bfdae9b.nq.gz
│   ├── d051f138a642d3ae54ab471376d4efea2394130d.nq.gz
│   ├── d1559bf80c2bb49f99f7512c682ae634495c3a98.nq.gz
│   ├── d18054a30822b03940dffa230da1acadf2db9ff9.nq.gz
│   ├── d1aaa78a54f5ebb288b0666e2464447e291df207.nq.gz
│   ├── d23f1c1cd52ee81c46f9ac6b62a5a3fef94597b3.nq.gz
│   ├── d2abd3ee41fcdd57b010a7e7ca71a0c325c026fd.nq.gz
│   ├── d2f3491f00c3445d03f52524b988e5029d2c0c2a.nq.gz
│   ├── d2fc6c1044e08a1c156f8a55a43b4835c49f1ee8.nq.gz
│   ├── d304df7d02ea039670e9d1d6d654a881bdeeb361.nq.gz
│   ├── d33117fe31c20d23b3d1248d73b751e01454950b.nq.gz
│   ├── d34c32c326d98be702ee7ff3109364a3738fa8c8.nq.gz
│   ├── d38e0360ee56df731185c8359cb5e55fb0595068.nq.gz
│   ├── d3e77061248ba308c15ebcaead78af886e7191b0.nq.gz
│   ├── d774306c08038bd0efda1fff27425d60d315ff56.nq.gz
│   ├── d7fc0bd50fe6d39beeaf18db9ebbd53c640341e0.nq.gz
│   ├── d89561ae5ea30580b654bfd8e0879e83ce4bed54.nq.gz
│   ├── da04709095235781a75fd93db169542e777955f8.nq.gz
│   ├── da2d4386bb377a8be8eacad413388bc61b1cd8c2.nq.gz
│   ├── da5a290820e40b1f78cad6f45db179427155c1ae.nq.gz
│   ├── dd1bbb1372fed22af089c1102bb7efda2fc48700.nq.gz
│   ├── ddec7fb1473fde618a93f570b465076d1d960053.nq.gz
│   ├── de63f8c38fc1d6166a6705988f8500843a6fe8ba.nq.gz
│   ├── dec00a1ec4df55ec4807468b0163a06f45169be4.nq.gz
│   ├── def40e76367a462a8f79900945151ef87935cc6c.nq.gz
│   ├── e12067088f0631429ffaaa6dfa657aa2f6999eeb.nq.gz
│   ├── e2999a060bbe4f2826c1465a636ee5b54aedda50.nq.gz
│   ├── e72b96503a89a11fd65f3c56fc3f578eafca1060.nq.gz
│   ├── e85fcf52f6e19a49f6776c40c84b65cae334056c.nq.gz
│   ├── eac99cfd9d2e0cbaeebb66cc920dd74e155d2863.nq.gz
│   ├── ed99056bf6cb44a564ac4e1a050c55574464f2a4.nq.gz
│   ├── ee08024419462c9a0df3eb23dc6ed53264bcb274.nq.gz
│   ├── ef0c96342fd242ab7bdf260e10bb2dcb613caa69.nq.gz
│   ├── f17cc928314511c96ab80a5234e1a64820c49471.nq.gz
│   ├── f1ff4188b8731715666baf3395c510375329f724.nq.gz
│   ├── f2cd1b77bf5e2399a0d58dc711db674d81903643.nq.gz
│   ├── f2de1d83f0785be3ee27f3ab5af115593654968c.nq.gz
│   ├── f3152f340a2baeac124d2d6e76104ab9aaa53e7d.nq.gz
│   ├── f31fde7332be7e2156fad13406fb5df773f11427.nq.gz
│   ├── f496765a1103cf7097a6a5c26a901b3a55edcc2c.nq.gz
│   ├── f82e298816aca01547e3fa0a98a832a1f238f569.nq.gz
│   ├── fcd1132131693b07faddb6530ed0ef6df5156731.nq.gz
│   ├── fdb226b4739e26f9242a528827c6cea2fd6088d1.nq.gz
│   ├── fe9d0a492624968258c8d5b9180658e3b2fb113b.nq.gz
│   └── ff242115a6c190c4653afa19f8c303ffae2088e7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
└── filetree
    └── 4f701fad69a6308e6b9f0c3f7863c40c881b30a7.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[facebookresearch/xformers](https://github.com/facebookresearch/xformers)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

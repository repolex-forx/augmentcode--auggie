# Repolex Knowledge Graph of augmentcode/auggie

RDF knowledge graph data for [augmentcode/auggie](https://github.com/augmentcode/auggie), parsed by [repolex](https://repolex.ai).

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
rlex download augmentcode/auggie
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9cc3ead419db9486ad44e6e4bba30ecd6784ccff
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9cc3ead419db9486ad44e6e4bba30ecd6784ccff.nq.gz
│   └── repolex
│       └── 9cc3ead419db9486ad44e6e4bba30ecd6784ccff
│           └── chunk-001.nq.gz
├── blob
│   ├── 0094c5b493e45c5216823b31c639ce3f66680ed2.nq.gz
│   ├── 014886c8655e3fecff9dbc00d0e1248684758d54.nq.gz
│   ├── 036eef2ce0211a3524916e5faa1139c9d7e74dbc.nq.gz
│   ├── 038ef54ceef293c8fb16fecb4f024d8311679a5d.nq.gz
│   ├── 04535bb6bfce1c8c93bb94122628ac0bc058fef0.nq.gz
│   ├── 057eb57b7af043587dbfc8cdacda232f3dc87ece.nq.gz
│   ├── 0bd02d865e89881b42f8865e96ff00b9faf64160.nq.gz
│   ├── 0d427f1ff52a8ab43cef4fe08db2367c65520fb4.nq.gz
│   ├── 11c68a3b5d5bd9b1e1d956061699785b0e6a3fe7.nq.gz
│   ├── 13360e00a959ce23871d2addfbe21c9b1df46930.nq.gz
│   ├── 152a08d091dd4f6b88c40fe6b050b407a3e5fec2.nq.gz
│   ├── 18d02da4477a2a4fadf50496195ca2af27965821.nq.gz
│   ├── 193cfeef0a1736b97a056e83828b53f0c7cdb5b2.nq.gz
│   ├── 1a5d14cca026d0962a23651a1442b59d280759e9.nq.gz
│   ├── 1ac21afabba1154a249645b56b93e06f4a3632bd.nq.gz
│   ├── 1bbffc8d91356fb71a34a00d8a3fbcd949c2b603.nq.gz
│   ├── 1d5a6367dd4d8f3a6ed2216899cb39939d93ef31.nq.gz
│   ├── 218acf1c40006003955a4d22f612ae608624e535.nq.gz
│   ├── 221d97b987a6556c8cf18137b2fad85a8437df0d.nq.gz
│   ├── 24d21300ebfae82aeb40213eaee74dc60eea652b.nq.gz
│   ├── 266d9847eb94818ba4f703b7d65eef8fab959011.nq.gz
│   ├── 2f13c3d016ecf8c1710654971ab3dd10d0d9e4fe.nq.gz
│   ├── 2f3cb4bea5ba1c08f6e3e7f2dad0f4f02d76df18.nq.gz
│   ├── 2f5279984188f733762b8490413bc24225554cb3.nq.gz
│   ├── 30c89aa381d35a4111323985c7b9647ea5915f6f.nq.gz
│   ├── 316d4fa971abd454c73c10bcd5da7285127a3ea8.nq.gz
│   ├── 31ba7a8432050344b68a334588ee803f030251fe.nq.gz
│   ├── 337ed9c18d4326683dbd3dff9a8260cbb08b4063.nq.gz
│   ├── 364f2bfe117ffa5296a492f71646b6c87c7910c9.nq.gz
│   ├── 367a152ad1d3afeaaec764790af499d3754fc42d.nq.gz
│   ├── 378974c9814e356cec298abe87eefb09833ed05d.nq.gz
│   ├── 3991de4d8ddd22c8c70a215ed24c3eed5e3e6239.nq.gz
│   ├── 3b952fc48f4cfeaa98fd9a7a6bef03d55f81b188.nq.gz
│   ├── 3b98d24f963bf48a3fad0983b49ab3ff21fadb57.nq.gz
│   ├── 3bc43087e4510d8f1e4a8dd32c02079500908ab9.nq.gz
│   ├── 3c8c81ea835e5f595732ca5a9c74386bd1790448.nq.gz
│   ├── 3ca5f177c0e94896cec0fecbba75f99f97e705a4.nq.gz
│   ├── 3ee350d1f1d9317a0d3e62ce467e7136060eb63b.nq.gz
│   ├── 404dae98d8effa9a9e711e806778f0ee48fa7ba4.nq.gz
│   ├── 40ef95e08b96750d00b58a417ef129413dae90bc.nq.gz
│   ├── 43b891d2cf188180260eea5be985801e1dcc87ac.nq.gz
│   ├── 45d1f94fbd665b509d1a47bd54e130d64838d86f.nq.gz
│   ├── 472c16b75eccbf1c39820815cb3d2da855e13029.nq.gz
│   ├── 4936a9d6347954dbf9700c8376d688de46675902.nq.gz
│   ├── 499dfe6fa295d1f337c093ad5d7653e2d9a6ad9e.nq.gz
│   ├── 4a81ea54e67606d7e101b5c94a11adec81d572a8.nq.gz
│   ├── 51cff3592130df20557185889b8cd94c6e30b88d.nq.gz
│   ├── 523f873b338ecc2ca482219cd7919d622d71d6e4.nq.gz
│   ├── 53b2c0a3e1c4732051f721077db3405507d2d2da.nq.gz
│   ├── 53edc4fa1b4020d1d5c15abdbc1bcb56a0782395.nq.gz
│   ├── 5552b4e0e26d6059650358c93ea3ac60a812627f.nq.gz
│   ├── 557ab093803d4da6250f9cf709f8e2cfacec8dbd.nq.gz
│   ├── 58268dafec94774db58f07f3e173d86eadeb5b65.nq.gz
│   ├── 61dc1df9c86a19ef98d8200b6468a45260d86a56.nq.gz
│   ├── 643f6412289fb59864134263f5a6b82bae345c82.nq.gz
│   ├── 67643fafede7dc8fcf3fa08f3cd62987ec0fa5de.nq.gz
│   ├── 6b2df613fad03806bdbf91620b118ac38319f0f4.nq.gz
│   ├── 6b46b52dea5551ea04c810b08fcc280bd7b932af.nq.gz
│   ├── 6c4d31b2bf98897fa19594a1f02ab429ab460ea1.nq.gz
│   ├── 6ca05883a660cbedd5a90df70a374f4d2a2dd95e.nq.gz
│   ├── 6cedbbae02ab862010ea4106708d9a1eb3aa9f20.nq.gz
│   ├── 6d7bffe1dd0191fff2e976e3ff9daf29d621057c.nq.gz
│   ├── 6e0390522777d98b2d724d8a1341f86aea200266.nq.gz
│   ├── 7200f490df977c12b48d15ac3d9162b25ffcb4e6.nq.gz
│   ├── 7201648d3e4e0c9e591754513b032485c74ed085.nq.gz
│   ├── 7253b039ffee33a433ec654a3ac85b841c502c76.nq.gz
│   ├── 7399b7bc7a1d29ff4207fe24b1e82559a5783db1.nq.gz
│   ├── 760dc62315d92ef188c2a16777b041f1c1b8b11c.nq.gz
│   ├── 7a9d209401eb2f9224913e920af6a2384bb73018.nq.gz
│   ├── 7c0a68318164679a8ab630821a1da45aeab9df50.nq.gz
│   ├── 7f34c9894f6e984ad6d7814e666ff799594bb68c.nq.gz
│   ├── 7f382120a9ac65cf3bb0560f33dbe3479f17a993.nq.gz
│   ├── 7f67586d1eb2dbb168d88906b10ad43d56740ea4.nq.gz
│   ├── 83f5498abf6ba794913791fad2524a382caf2f27.nq.gz
│   ├── 88a7a42212177ade8286fda8592307d1870b04b9.nq.gz
│   ├── 88ab035906aaf0737d79fcad6064b0ae3e5dadcf.nq.gz
│   ├── 88ea5057da6b92d324bf3ce09ec7c56a89568357.nq.gz
│   ├── 89413432d26de2c4f24c5415303acf1f1917d55f.nq.gz
│   ├── 8b3dfc07948e8597d7c289b23d212751ef11cc58.nq.gz
│   ├── 8f41146d88625a36216c0de7bc248552c0ca01c2.nq.gz
│   ├── 92b2a1160263bbd7a502f9c7e6104136a3158ac6.nq.gz
│   ├── 9357a63f9391760b9926fe29007d01ab8766f881.nq.gz
│   ├── 93739c4bd772483d15250e5a9ff637ea831bc543.nq.gz
│   ├── 951f38f36367a804aeddd4320ef87bb8a4187dea.nq.gz
│   ├── 95be15bb63e98cadfe769583150bd46babc33b4e.nq.gz
│   ├── 9700aa1e5001279c08db06939f75408a6c543151.nq.gz
│   ├── 9872f2ac22c59b1dae251069a057f9e2ee068b20.nq.gz
│   ├── 9a0eff26b2d97494b0cc5b8073bb4e8f7b1f9e10.nq.gz
│   ├── 9af6543525bd084e9aa943c6b1200aeccc744e22.nq.gz
│   ├── 9d3a32e95fd33cb258628576915e6a7ae5737f20.nq.gz
│   ├── a177a2bdc3e38dd603d187dd6e7001d178b5eabf.nq.gz
│   ├── a25490743f65d88ba8d754b975ede8243a7f9e49.nq.gz
│   ├── a27b4f03bb05ea472b3c4521057c435fb6c30f4c.nq.gz
│   ├── a2999c7cf48036fc7abac97f458d5b7f32e11392.nq.gz
│   ├── a43427fd22c4660f5c92e86442db7eb4f0ef4116.nq.gz
│   ├── a4acea607cf9d14d2f29da1c765b261064adf41b.nq.gz
│   ├── a522a40c450770c1f7615a0583f72edadb78fc00.nq.gz
│   ├── a6686bcd2259abaa4afb08f7324ef746905308ee.nq.gz
│   ├── abea29ab1c658a8994b67d510d59fee52b1e80c3.nq.gz
│   ├── ac6eb5713f49f03778713aa5e495d1340fafac06.nq.gz
│   ├── acf0687497734d8eddec8ceffcb064dd53420df8.nq.gz
│   ├── b07135f52cbb7c34b633177535947519541ad39f.nq.gz
│   ├── b330ce7b073362ee255fdb4926eb8ce7c679b42a.nq.gz
│   ├── b4cb077b2d96fa562764608cba07dfee3efc9e70.nq.gz
│   ├── b5225bfc4b7705a0b14d0d58d5adecfb03aa6fc9.nq.gz
│   ├── b6b3c93e487ac356db2ca5cf98c3cf6016932e78.nq.gz
│   ├── b6f0c1d9ac135645abc438ab6adf0b915615dcb7.nq.gz
│   ├── bb60a24f330f0f2d2b781479de5c9b1be2f5e370.nq.gz
│   ├── bb87665a8dac7fa00e68da1dab7cb985157c5c9c.nq.gz
│   ├── bdb544c88de6f598e9115b9f7be3d521c5cffaf1.nq.gz
│   ├── bf60bd6db32ee9e58141c92ffc5532b0b0cb5edf.nq.gz
│   ├── c040be7adc7affaeebd6aa2ff319ae835e08adc6.nq.gz
│   ├── c2bf48f3ad9d4df71deb870ea4ac987b5d455f50.nq.gz
│   ├── c2def13b2c2acaa65617d2023b49a7ef2d1536ac.nq.gz
│   ├── c5201723d836265c3c2196cb0ef84fd72e6f579b.nq.gz
│   ├── c652c2615559f750861561925730c80709e48e35.nq.gz
│   ├── c7f37bbf472c2a6493f7d9cfbb441aa5b8f787f8.nq.gz
│   ├── cab8ddc166c6fbdf416662c2110614b005b834a8.nq.gz
│   ├── ccd9db1851ffb5dbc4d7bd6533b88cde35fc764d.nq.gz
│   ├── cf2040e02f22e2ea66bc4e1017001225aa185992.nq.gz
│   ├── d53e04506d6071702a04437188144d5cf1a75868.nq.gz
│   ├── d838c35f05210971bec46bfb17ac6615578c2bac.nq.gz
│   ├── ddf541df33a9ba0cb176744174eab003dcd8cf6b.nq.gz
│   ├── de7b1ab0aa57c9d6c406204b749a24172d0733b8.nq.gz
│   ├── e2d776e533ca0e50d2c2fab8bf756ddd96f400ca.nq.gz
│   ├── e300aeead60b5a9bf744c6cedba2c6a00b9d0fda.nq.gz
│   ├── e5458b1a03563fce1ece5606245c68f79cd6a3a4.nq.gz
│   ├── e9956a5e0b87fe8c8a5d2ff85f2b19c18bd9dfbf.nq.gz
│   ├── ea5b36fa48341c9159b0b703fc44d754112fb4bb.nq.gz
│   ├── eaa1271d69bffd0c3be252e6669864e56b8224ca.nq.gz
│   ├── eb70f123be2b1865f366698c169e5a9a9222107a.nq.gz
│   ├── ebc92b57e95841f6db7e6744787b6ebd3ecd2496.nq.gz
│   ├── ecf723d78bfc7478d78394bfdd42ba49130ac022.nq.gz
│   ├── f274cdd1bf149e22bd316df78688d2bb538bfe95.nq.gz
│   ├── f33d6bba079dbb93615b4f92f141f9a034a521c6.nq.gz
│   ├── f36a26f284d4bff138ae038fd1157cfa5b4a7a75.nq.gz
│   ├── f55ea35987cceff990ef680101abc776db8763ea.nq.gz
│   ├── f69bd6210a919534e4622dff31c099ec62555cd3.nq.gz
│   ├── f74e2436616aa50830cc9b078dc86a40fb739303.nq.gz
│   ├── f7b77b638b3635bc81b61cae1e223dd72950d986.nq.gz
│   ├── f9ca3747abce28851bfcabbe178ea7290cccccc8.nq.gz
│   ├── fd100653782445a4430835d3a2e38adcc0599577.nq.gz
│   └── fdac426695806fc2efb47cdd5087397a97a11aba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 9cc3ead419db9486ad44e6e4bba30ecd6784ccff.nq.gz
├── filetree
│   └── 9cc3ead419db9486ad44e6e4bba30ecd6784ccff.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 153 files
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

[augmentcode/auggie](https://github.com/augmentcode/auggie)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*

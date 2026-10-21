# Repolex Knowledge Graph of ibis-project/ibis-substrait

RDF knowledge graph data for [ibis-project/ibis-substrait](https://github.com/ibis-project/ibis-substrait), parsed by [repolex](https://repolex.ai).

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
rlex download ibis-project/ibis-substrait
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2cf1e0769ea93859be832cfa1554b4351e0f235f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2cf1e0769ea93859be832cfa1554b4351e0f235f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0866e1b20c49f842c7ff36c33fc6f5b73580a8b8.nq.gz
│   ├── 094e4cada05b96e549de5140c2d1d0b6f3f60624.nq.gz
│   ├── 15fe78b0db8b655a3d3527e0c6a6d75eab0c7b55.nq.gz
│   ├── 17f9a885ddc732a06e4717489caf8776b9b0152b.nq.gz
│   ├── 1878b341beb5ed0df28351db039bdd5ff1e2e25d.nq.gz
│   ├── 18a7ec856a869761777013098bc74e23da52590d.nq.gz
│   ├── 21923d90fffa11e585118e960a042c0e197bb930.nq.gz
│   ├── 2295063fa2d55e9f87a1452097edc5ecad5d2458.nq.gz
│   ├── 24bb6182ab66b5097ec1f88c1994a1fa2df8e911.nq.gz
│   ├── 2d77c69f8deb04cb0b67d102660fad4d78f94b1e.nq.gz
│   ├── 2e52e7af9b1023185743cf3784c4f4bc537f330c.nq.gz
│   ├── 35e94a50439b9786a31237cc8dfc62ac2bcd54fd.nq.gz
│   ├── 38de55839b7c16d45cbef0f9442468ab1c82ae95.nq.gz
│   ├── 3c284302288ab8fb8d01e5f7e4a6cd3b777d216d.nq.gz
│   ├── 465c9d765bf1ddf9b9d3ade59ca2c99232cd33ed.nq.gz
│   ├── 47ec4742e04a7478a88952af6cf22e5770852dd4.nq.gz
│   ├── 4c50ee32d87fa4aeed2bdee33ccf74cc815e6ac4.nq.gz
│   ├── 5705f0cf8c2920a9b4f4be469c4aff027a1dd2b7.nq.gz
│   ├── 58f5198ccf907717e810ecb1288152517fca36e2.nq.gz
│   ├── 5a4c39f35fbba417aec9347e6051b1ab7954daac.nq.gz
│   ├── 5df7ac3e1ec68e0912612b8e5df21ccae2a9953a.nq.gz
│   ├── 5fc4486b00f9a9afd5a9580343cc141ce855685d.nq.gz
│   ├── 61e52370bb81efa7fc0a6398700a77c05f93594a.nq.gz
│   ├── 699ca2d1e405f82a7f2413e3ae1bc9a2ba7bc5a8.nq.gz
│   ├── 6a9cefa9037b5b4479dfa6e9e76dcd4f9c0103d0.nq.gz
│   ├── 6b0050caa8a020e89144a84c3ae3106aa3b738f9.nq.gz
│   ├── 6c73af2613e165c3063cd4e6b7702e1635ed8d3f.nq.gz
│   ├── 6f457c913db99889e9374f1dc4635ec6122d7f52.nq.gz
│   ├── 70150b8535aaf460426f5efec920ebec2bbb0961.nq.gz
│   ├── 7027515569ea7c98fc473fdfa83beb321b0b3786.nq.gz
│   ├── 7172fbfd10d7ae8ad4a67e5bfae92cdc5339c8c6.nq.gz
│   ├── 7b758bf78be1e31e5fc981895fbba39f1a66caff.nq.gz
│   ├── 7ca3dce526b09e9edba9ca22eb00598ab715b493.nq.gz
│   ├── 815a1d5f6f185915e930f9937f32a5c3484d0942.nq.gz
│   ├── 8395399f1a9c0965b92d2ad7ab79969301e871c8.nq.gz
│   ├── 873ece49370301224b227491810eafe811261fa4.nq.gz
│   ├── 891ba116d7ba083358498ba51c67656620de5bb2.nq.gz
│   ├── 998a13b7ba6ab64f88ecc4efd329a588c0151138.nq.gz
│   ├── 99c268e7569962e00625c297c9f984d050882c64.nq.gz
│   ├── 9abd244247993593d044427be2224fb046d7b6d9.nq.gz
│   ├── 9c7fcea224b758b6760910865644fd7b7ffa308b.nq.gz
│   ├── 9daac6674cc707e3df19aa5071dbeff632ae6ae5.nq.gz
│   ├── 9eb132a589d4c98b0227604c5d548f77acc954d4.nq.gz
│   ├── a22f2e31c274e0d31b5ddc1eeea61131e288dc2e.nq.gz
│   ├── a60f4621cf546fead1a509b0356ef63a2354506f.nq.gz
│   ├── a6522ae0b9fd92f6a881e2f995fe1771c8788ca7.nq.gz
│   ├── a7d3c818df04de79b299946b800ca31fe5001669.nq.gz
│   ├── a8623d48c04b308f4b810891243bdcf08df6c6c1.nq.gz
│   ├── aa8483e27dd6c4dfa185da108254180ea6e40ff7.nq.gz
│   ├── af9b25ee06efc9077cd10e0eb01324d9ae831c55.nq.gz
│   ├── b3ee3da6ab6cfa4c17d6daa724ddd3acc4abcc49.nq.gz
│   ├── b49a1cba3b828b88d1afa586df5b0453ab6b281c.nq.gz
│   ├── bb157c1b55800ee14f67621095aebfc3fce706e0.nq.gz
│   ├── bb6c86831e99ad4fe6d3103f3d6375cf7c50e5fc.nq.gz
│   ├── be3a7923a0ba58aed7527f63de9858166fbdf5bd.nq.gz
│   ├── c14295b71adb1b5efbf551788425a7b30d3e47b1.nq.gz
│   ├── c3b421dfc6f96f177e9001d171ac30385c9633be.nq.gz
│   ├── c41943736ef021b35194d44ca81b04ef029c10cc.nq.gz
│   ├── c462824e3fe7002a6a50585c79f9f12460a10fbf.nq.gz
│   ├── c4adb600f0983213beab5a40d347ba4b918cbf8d.nq.gz
│   ├── c56a937cdb60f49eb9ec349fafde4cb06cf525a7.nq.gz
│   ├── c91b5810c2976f1e6c940bfc491e8e1d8f871180.nq.gz
│   ├── cac455722e968c32bc2a07a6c61a0961f44e943e.nq.gz
│   ├── cfe9e0ab17ad23ab9fe3c6ffbe4283186f2beb74.nq.gz
│   ├── d09abe65e833e175b97212564a70386559b1e274.nq.gz
│   ├── d1bcc209ca10ad61c38b49b8a7bd644c46a5bbc7.nq.gz
│   ├── d3404e10c18d4a1b91c049c7aa225157060cdbc0.nq.gz
│   ├── d783a2eb03a58954c34b000e46206091345a50ac.nq.gz
│   ├── d97ded72954a83aa0a7edbc2bb6b7c532ed03944.nq.gz
│   ├── da88c7f2bab02d06fcac5f42cf0eb5ced9fd0256.nq.gz
│   ├── db0e4edd49eae72c833d525db13ffec1cfaad52f.nq.gz
│   ├── db38ce76cc27c60c30e17509abd0eba10ce9ddca.nq.gz
│   ├── df754f2413d9a564c09253eefc419eb26436b3d9.nq.gz
│   ├── e3ddc1dc005460ecc167cd31b35885f631532e65.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee9ab3ff68714e295f5f4e9d57b56144f13a6aea.nq.gz
│   ├── f4dc8fa523c5e48852131c7670c32bbe29b084c9.nq.gz
│   ├── fa53df51f60d69c88cdee847d6593708951622a2.nq.gz
│   └── fc3ec083ec8a03f40d82a3a3d28fbd2fdb775e5c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2cf1e0769ea93859be832cfa1554b4351e0f235f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[ibis-project/ibis-substrait](https://github.com/ibis-project/ibis-substrait)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*

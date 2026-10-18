# Repolex Knowledge Graph of etianen/django-reversion

RDF knowledge graph data for [etianen/django-reversion](https://github.com/etianen/django-reversion), parsed by [repolex](https://repolex.ai).

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
rlex download etianen/django-reversion
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── abfd7d7d3617224eb267311f9379fabb1f8cec59
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── abfd7d7d3617224eb267311f9379fabb1f8cec59
│           └── chunk-001.nq.gz
├── blob
│   ├── 00874c4360e2dbf42a139b9480458774289d12d8.nq.gz
│   ├── 019ccd626ccca73c7c9b0bfb7d9ff8397d904658.nq.gz
│   ├── 04c881281560ca5a6230cd5852935d5dae17f29b.nq.gz
│   ├── 074b90842cbce8d3b5b975605469e9af1bb31a43.nq.gz
│   ├── 07ebf72bf03804aece6a36eb16652efce9e591a9.nq.gz
│   ├── 07eea74f6d7eba636935f5723934816d4683f765.nq.gz
│   ├── 0b0a0cbdd92bc457a539c454df6067d4ac419717.nq.gz
│   ├── 0d2dc8bfbd90f8f0d479fd13d0ae9cd0d899a1a0.nq.gz
│   ├── 0d89e8ba50e569220e010e76d84db358c1f05a8a.nq.gz
│   ├── 106d782d005a1dab891380e84015eb143ce64da3.nq.gz
│   ├── 13e1a33983b8d6f74a5e1dfc0872d87db39c9632.nq.gz
│   ├── 1420d26d4cc9990509b6a8cd7017ab7d4d370811.nq.gz
│   ├── 15aa07756ee875548c273b135f208774148fa5ec.nq.gz
│   ├── 15d54c84d21de1c535878acc38f32dcdca52583b.nq.gz
│   ├── 16ef56d797a2220db0b8b67dd99b74ba668db9e0.nq.gz
│   ├── 18ee221a04abfbee9eecb7b8f954958c06d5eb77.nq.gz
│   ├── 1a9b70976221cb4554db90f5392a75b6b9ae4b20.nq.gz
│   ├── 1adfd4430b65466db306226abc1961bc9fa6ab72.nq.gz
│   ├── 1cdd8ca9c81cf9ddc88cf1b5ec22cb6f8fd5a4ac.nq.gz
│   ├── 1ee671a6835a53740b3dad7a7a55c52261f7662b.nq.gz
│   ├── 1ffa042086e4e324eb874a261c7d232c4844b687.nq.gz
│   ├── 2257367a5d5a63966b52a3e1a42e4aac8dbd523c.nq.gz
│   ├── 23f0d3c0c5de6df0a2688c89a8e104b1e7f69dec.nq.gz
│   ├── 240762b4fe96bfb007d666aabc888457b2d54344.nq.gz
│   ├── 250bf5fb65533e84082a206389d2a372f749317b.nq.gz
│   ├── 2e23c4edf48b2ce97b98bac36994e3dfd7b304fa.nq.gz
│   ├── 32f6d84f87480e622fd860d252a1a45f0244b887.nq.gz
│   ├── 366cbb8272bda5769c32e9eaba64de8ea98959d5.nq.gz
│   ├── 374f3b4e3c507cd39073d58ee58ebd89a9349df8.nq.gz
│   ├── 37ea99ef98758a7b46c6ee797d11c1787d8adcf3.nq.gz
│   ├── 3c3988c7f12293be54c366e468a07ea03a0274f1.nq.gz
│   ├── 3ccc3aabff31ec3ef76cd31031f3c9fd57484e80.nq.gz
│   ├── 3fa0974373540457eeffb5ec54aa5bd4f5d5906a.nq.gz
│   ├── 40c7fbc6e8ab086d825ee28c69e307a5dec242a1.nq.gz
│   ├── 40e4c02a9faa30068cf07fc2739d01cac095987e.nq.gz
│   ├── 4243e5e4ea7219e77ca8d527fe1371aa99d42ca2.nq.gz
│   ├── 4467379b7d258cdc8b85999fa6f8a14b840ef50b.nq.gz
│   ├── 44c515b10ccba3215103fa7169a17fded5d650d8.nq.gz
│   ├── 490a373cb87ce0b9378b1a10f13446d4ce490c11.nq.gz
│   ├── 4a361f2d6766e7ec4a9f4d241c2b064e3837a557.nq.gz
│   ├── 4dbe5ca84be8076785942e7b5e73fad83ef70fc0.nq.gz
│   ├── 4faee0701254b00a139773495c638d658dcaa1d4.nq.gz
│   ├── 501605e4c1d7fb9abdc2d10f24af17865c6a190d.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56c5a162a5c39ea2e57efb4aa8c9e03bdce3c604.nq.gz
│   ├── 5de5ded1eec63cad1738b5050281b0012b7e1a66.nq.gz
│   ├── 5ff24a146ddc20ba13dfa9f25782b75036adb41c.nq.gz
│   ├── 61b49c0fdbc062df0e4c98abee396cc44d570004.nq.gz
│   ├── 61c4708fe5502730cec7f37aaff75b360592c9e1.nq.gz
│   ├── 6453543e4f2c6a199b2f81be0822acefdf6c2c13.nq.gz
│   ├── 69edcc4bb53f5a3a7e22c904aaba961c88b8c3de.nq.gz
│   ├── 6ab8b6507c8c20dc3f53a207339441b8f9676b2b.nq.gz
│   ├── 6b195b4ab26e2407d6679e5ace6807103d88fb85.nq.gz
│   ├── 6ba9b3e3dfc2ae314feedf2abfe4ec7e070af795.nq.gz
│   ├── 7169751a75bdd821800bab10c7ea5ca057605db1.nq.gz
│   ├── 741a7b4ac2b0b8f1eecac4d3a6b863264807569e.nq.gz
│   ├── 75a5a691dc9d48e4ad3374571e2627f7ad44e5d1.nq.gz
│   ├── 75a8bd40abe66c58a5065fdfe0c2698799ad5592.nq.gz
│   ├── 78179f3d9e8c0e20255c4ecac967d4cd3a4cfae7.nq.gz
│   ├── 7ab61bb585924a772a5dbe51eaaf032a1bfbcd06.nq.gz
│   ├── 7f73ee4c6d06375017afd39bd78a819d58fef988.nq.gz
│   ├── 8036ed0bf7e6685f0dfd0aeb7bb821b62d569840.nq.gz
│   ├── 90fbca2bcd1c3d66e73f27494559976f3d3a7347.nq.gz
│   ├── 94c4c7d3aa2c46f8334b111092d008c0313feba2.nq.gz
│   ├── 969ef1a4b90d372376d401048da429eca7fe451d.nq.gz
│   ├── 9d648fa1f8fa3b91180d186791581d568734c545.nq.gz
│   ├── 9e696fe093ada40ab863b23b4893beefeb3d2b8a.nq.gz
│   ├── a099af09c7a964257e69d2bfb6015b110a8f97af.nq.gz
│   ├── a4852709ab73378f540b759eeddaec44bdf18000.nq.gz
│   ├── a6c3b7bbce7a04be5a4351e99bb8025d63aad58a.nq.gz
│   ├── a93ee9569ea209f5ebea44539bccf48c1235c3b9.nq.gz
│   ├── af4b8650acbc1054a4f047cc5cb6cc5a40606d4a.nq.gz
│   ├── af86e1c35b05886cfc553d0a33b100e6923bf50e.nq.gz
│   ├── afb1618c4dc579f72023ea995404424489ec5329.nq.gz
│   ├── b03588774bf9383404d8d6ccde9844727b10ea55.nq.gz
│   ├── b06b12292dbd8299ed64513090734a4949b8311d.nq.gz
│   ├── b20da4e8d1d5ce13f651b70e853013208c9c21a8.nq.gz
│   ├── b404b08dc75fd2295255accf1062c23d75e79dd7.nq.gz
│   ├── b70ee59bbd2bbfb3d06a96a1e7803a4f5bc3066d.nq.gz
│   ├── b9af526d0d56df27dd51d6a89f0f8a493db342f7.nq.gz
│   ├── c05927e627d217ca1320717bdb075d7dd59d2e51.nq.gz
│   ├── c2892965c21ed6854528985e0b8e59cce333a2d7.nq.gz
│   ├── c86f4f2f906b1431005ac1f3ba6285bc605e2997.nq.gz
│   ├── c8dc7d98700e69e6ae03112180b5ef6c1771db67.nq.gz
│   ├── cb5a14eaf2c876c1b22975e9d6d42b0cc8d9400a.nq.gz
│   ├── cbece29d50a6f258bbb3ca55729972c2090d5e73.nq.gz
│   ├── cbf9fbc8e9d9b84dc080655bbf7020f8f2aec55a.nq.gz
│   ├── cfb9aec455f245620c3630292d84853685037aae.nq.gz
│   ├── d02186f97030e2e3f5929e288fad836874e6f578.nq.gz
│   ├── d111a300d5c2e142a31ea568cc1c5c8e0f6b81e2.nq.gz
│   ├── ddda11a2806d75d00020f2a53610e4b0bcbdfb5f.nq.gz
│   ├── dfae77ec00bf0df5cce155628622ea6df383921c.nq.gz
│   ├── e16343c9779a33ee7d153196bf944a8a39a0eaee.nq.gz
│   ├── e2170e50bbed5546c257f4a316f33fa0a4e0955f.nq.gz
│   ├── e3f29e235424de7e2906591f72ba8635050e574f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e71c9b7a73f379787ed56cd892efc71e56c99b06.nq.gz
│   ├── e7bdf6c412b54c937584396628ecf3020c9d59a0.nq.gz
│   ├── ea2fd6842c4a35ed97eb2145d014e491e6005460.nq.gz
│   ├── eaec79cde0905b4bb512e30cb15ca76907365635.nq.gz
│   ├── ec2abf31c8ca65b8e00c7385549b5f30e936c9d5.nq.gz
│   ├── ee57abe62a896b8de5d2e5aa09bedd2b96294596.nq.gz
│   ├── eec2aeabda402b32b08c3e7f17683e9490f42eca.nq.gz
│   ├── f1ad1a558ee39f001ce1bcda8d9423ed58c4019d.nq.gz
│   ├── f38c8b2f0c54c5d50932c5a12e7e36a8f34f0e40.nq.gz
│   ├── f5105517dcc46eab3c3d268766660eb69140b4e4.nq.gz
│   ├── f5f052b445977586f2fd25f2ade9962104981790.nq.gz
│   ├── f70ea51bffe60a8ce27f3b0e470d422f8508ff15.nq.gz
│   └── f7ffa009ee14b8ab286058ec56abd9f3192fe0e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── abfd7d7d3617224eb267311f9379fabb1f8cec59.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 117 files
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

[etianen/django-reversion](https://github.com/etianen/django-reversion)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*

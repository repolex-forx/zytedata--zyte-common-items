# Repolex Knowledge Graph of zytedata/zyte-common-items

RDF knowledge graph data for [zytedata/zyte-common-items](https://github.com/zytedata/zyte-common-items), parsed by [repolex](https://repolex.ai).

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
rlex download zytedata/zyte-common-items
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 297cb86af88b26106899eb231d50c7b96d164f78
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 297cb86af88b26106899eb231d50c7b96d164f78
│           └── chunk-001.nq.gz
├── blob
│   ├── 0072d14d7275efd8e06afc5136e9081828bcd3e5.nq.gz
│   ├── 01f1eb11e2095fb8f9aca78681b41c593469e5bb.nq.gz
│   ├── 02473b8c5671b5ae65489ed2f110aa10b3896ab8.nq.gz
│   ├── 0493ddbb9a56b7a11087024efb8a024cc4c10304.nq.gz
│   ├── 085efe945a20f68360514e4d51746c8cc9ab9d41.nq.gz
│   ├── 0925566b5fb3bfd29ac81802665e1e55c668ff52.nq.gz
│   ├── 0b49f3be0ac47b4f770474702e65c1e27186ba8b.nq.gz
│   ├── 0ebf96381b9d77f0c13e7b7474b71babe7c10d5c.nq.gz
│   ├── 0f6266605e327a6a71df1c00fabb678881ada6a6.nq.gz
│   ├── 1006928b02592631499b58e58570ac3643f57196.nq.gz
│   ├── 1110b581f9d30f425f0b2d07ff23cf3cdccccc2f.nq.gz
│   ├── 14aae9bb637584e0a685ec088db70a4738be3852.nq.gz
│   ├── 15aba829ea8f7034080fafe2f4d92ebb6a15aa00.nq.gz
│   ├── 18070d266a22b864d98db0a949276c39fca433a2.nq.gz
│   ├── 1a79c465c22ba2c43fa3d75333185dfc9456f529.nq.gz
│   ├── 1b86e9852efa98226d204350530e5d12e93012f2.nq.gz
│   ├── 1c7a349e5562502ed89512cb2cbc174355a9ecc1.nq.gz
│   ├── 1ef3fb0799f20f5d49103c6351339c89ccaedfa5.nq.gz
│   ├── 2007dd3bfb0a6e43905ce0cb5a1ce0534c98db36.nq.gz
│   ├── 20120d7d2afb9dadac0df73cd8db2f60e969fa2e.nq.gz
│   ├── 21dee437d7d45600b057309b5c6a0a4365a73ea4.nq.gz
│   ├── 24137630c3576a34437ae31cbbe5e1afab7ccdc9.nq.gz
│   ├── 24e560aa8f76c602ba2283d3670510c527264983.nq.gz
│   ├── 2655be26ded19ff36bd3189342c4fd8c678a3a02.nq.gz
│   ├── 2677f7dcdc4f9264b92bebeb958a1eca6a59c6b1.nq.gz
│   ├── 26bea73e811981fe7a2a09a00c54f23943d309aa.nq.gz
│   ├── 26fab613e823b62578ebeec89225fa2fe155c78e.nq.gz
│   ├── 2ee26ea5e7aeccd32e35740319e567b93702cf99.nq.gz
│   ├── 2efee3650886f16c4d9f0717581f2a0199d17277.nq.gz
│   ├── 3041db2759c9f58c9196269f15d8feb3b5a0bdf4.nq.gz
│   ├── 3103d387e68c97309c84fdfdf4d4dd9f437a2b2b.nq.gz
│   ├── 317d4355fa13a2f381fe8df7a630b1bb57e61ca1.nq.gz
│   ├── 37b5f332d1758eca73a24f182b15d9e67eecdf52.nq.gz
│   ├── 3880ffd25bb9cc68936eb68f55d5bc955fb36a41.nq.gz
│   ├── 3989954dbabaa7b82c2a627fd658c7407fb7e0f0.nq.gz
│   ├── 39d0d1629138ada62c770eb8f630d81496aab940.nq.gz
│   ├── 455a1aa24f100f9939e7d1e188d945e3d3d45ecd.nq.gz
│   ├── 45a3de28dad4f12c420ac9c099ec4a9558186669.nq.gz
│   ├── 49d3aab27fa198bf0f77a30bbb6673e873605410.nq.gz
│   ├── 4cd988e4ee1ffb2f576dab3959a1a9f359d839e0.nq.gz
│   ├── 4ce58f3213b907f76e31dd0e7b85742e70f25d2b.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5720e0f483fbf72357b42a01a2cf34d0c10af087.nq.gz
│   ├── 5832a0de8c893b71bd0331550f67476335ba7d1b.nq.gz
│   ├── 5b464016df3ef4bc1a41fca357ccba92c918e029.nq.gz
│   ├── 5da676171f5b7a83ec736cc1427de04031c25ff1.nq.gz
│   ├── 5e316d981dcb56d3271385dcc06c846554f9081c.nq.gz
│   ├── 623d48cfa6b6f2ba551dde2435254ed5a1b63862.nq.gz
│   ├── 6291543fb8285c437c8749d836e665ccaf5d4784.nq.gz
│   ├── 6514a5da757e14c01760ab48ef91766f2d8a4ef8.nq.gz
│   ├── 673e395a4049853afbf87e4a460253c0714cdf03.nq.gz
│   ├── 6817eb37e4bb1dec3e79fab6a85092018d3acaa6.nq.gz
│   ├── 6822ec0c70c3f28c5326bb0c45a3764872657cdf.nq.gz
│   ├── 6a97c6492129e5a20c248bcc252406dc262a435b.nq.gz
│   ├── 6a9af5215a9b045c78fcdadcc20906a905ca49b7.nq.gz
│   ├── 6b3aaaa4df594fd03ee25a9e9d988cb4a2d8d72d.nq.gz
│   ├── 6ccd1cfd0cc570d9dc81579ca96a5f188d1a99e9.nq.gz
│   ├── 6f04b6c22359124f7ded5db0b0671146c8b26517.nq.gz
│   ├── 706b019872bd9bb1da85bec4c208340da94d9f16.nq.gz
│   ├── 71ee71e81a81179b1ac92ac02e8df8388313d72d.nq.gz
│   ├── 730c9c8eccbcf80b14da5395597603090e5c0073.nq.gz
│   ├── 78b6db40d133f63b5bb93cb8d173c1411cae651f.nq.gz
│   ├── 7c8d21bd67c2644a1dd34a8d5d48e2b652a7a259.nq.gz
│   ├── 7e819a59d319aa6da1d9a7f42541eee5cda83e9f.nq.gz
│   ├── 7f1885a88635d217e7d35c6ed24ac12da728fbc7.nq.gz
│   ├── 811dd553f336a8e166b7bd4ca3a265d27fdc366c.nq.gz
│   ├── 83248a6152eaf6b65a8e0b706dd2df6d856be408.nq.gz
│   ├── 884acd3246586f0a3c349a18aa07696a71b1a9a6.nq.gz
│   ├── 8df6ee797ad518f875e0478aa82a8117bd0b9d58.nq.gz
│   ├── 8e393f4a3508feb4fd5638eeee7ae310c4ba7ce2.nq.gz
│   ├── 908d8d82d7a3276379b5fd94ad064119172b1081.nq.gz
│   ├── 9204c7f7dd6c4e051751dd1864ce703047a280ce.nq.gz
│   ├── 93e47e868e5bbdee38c86ab3bf4799b7ea5c5360.nq.gz
│   ├── 972996e98745a8a1da22a16ea832762e10ba17d2.nq.gz
│   ├── 97ed31162e99ff28fd153ee7ee26f86207460356.nq.gz
│   ├── 994866ffabcae20d6d937d48b7f0909b9a3c3eb0.nq.gz
│   ├── 998c2cd0fcac6d6494f4336d8c09a28d36b3e1cd.nq.gz
│   ├── 999c861a9cb427bb4cae4706c619aa99b2a4b42f.nq.gz
│   ├── 9a76deee2fcbcc7075773dc058afd68097e55a9a.nq.gz
│   ├── 9b1494e099aef4f8ffd9298d364e845ae2b7a87b.nq.gz
│   ├── 9d7e1e83ae9dbc7f70b5267bb8ac44323660130f.nq.gz
│   ├── 9e031c11ff22dd0b6cc4a61920c0336e2b2d292a.nq.gz
│   ├── a16050141d21871fd9c53882a1bf92629263b10a.nq.gz
│   ├── a7136e1dd907b26ea504aa269756a3b35d74d25c.nq.gz
│   ├── a75b5cb3f768749b342d934abdc9523f352c968d.nq.gz
│   ├── a8ba89026607847da1802bb1bbbdb0bb98e0af6c.nq.gz
│   ├── a993b06c8eac4ef2ecdb58166b8973aa5b882f22.nq.gz
│   ├── ac92c9780674bb88a2f3f9efe8b566f9ed2854cc.nq.gz
│   ├── b1129cbd3ad1a4ea36a7539e563742764e99951f.nq.gz
│   ├── b1958d2bfca0f3f93d282dc331e51ef44ddd8fd2.nq.gz
│   ├── b515b4cf634206ee2989a223ffac478ddeab816b.nq.gz
│   ├── b59a8627f4e61ee1d754fe325c4539e6a4c02365.nq.gz
│   ├── b75593bb28a5884900b8c1db0a9127e9d2f8369a.nq.gz
│   ├── b8de6659fe898fd151d14d076743ce2efeb1e9fd.nq.gz
│   ├── bc31c9fe3dfc27d185bf56345f71bb147d007241.nq.gz
│   ├── c165e8846f989f750b559c27d8940d9edb3e576e.nq.gz
│   ├── c3f0e219b312aa4a7d575467c0bcea721308f00e.nq.gz
│   ├── c458f1f2251af6a45a796604d71b0ddb855519ec.nq.gz
│   ├── c7175556494b925a7f12812bf34aec8526340615.nq.gz
│   ├── c7487640fc1d21d1df579017a44c0ef1ce499deb.nq.gz
│   ├── cc7b5b613256a175481046d929d59b731dbba0d8.nq.gz
│   ├── cda9fa628be0fd1f84b70e74f3e2ab7038469385.nq.gz
│   ├── d175bf71d2b634270b8b140edb235ca948178adb.nq.gz
│   ├── d277df41ec693d6eb1742415cb0ff9e1dc5be066.nq.gz
│   ├── d58b97a3dc48b5964b9dbc6fefa857d04926ff1a.nq.gz
│   ├── d5da221ab1907c8ad2ccf57704ad94e696c3e02b.nq.gz
│   ├── d8aa6b984fa2c4c4891f114100d205ad99801b34.nq.gz
│   ├── dc33d802327ddf247c3a28b28823806f3562918d.nq.gz
│   ├── dcefdae4cc7aa0b9cfcfb155f1a97c99fa8369cd.nq.gz
│   ├── dd536f79feb32164e102175034e84726ce7a40d9.nq.gz
│   ├── de97074714c75ab386ddbb0780b533ed3d6cc88b.nq.gz
│   ├── df4fe1fbaed5d90bdfed3639b3918979ade21c05.nq.gz
│   ├── e2340f75822690113b9719d3f6f2521e9fc2c694.nq.gz
│   ├── e34b1cad8b39fabc106cb7ac5efea2083e89c630.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e98a2d098517fa5547742d1790f4c748f29c3079.nq.gz
│   ├── ea5e66ec7c276d02968551afa520c0abdd6d70a8.nq.gz
│   ├── eb1185d96da2f64092ffee4bec4cfae4bbec42d5.nq.gz
│   ├── ee1d5dd93ba08bcf7a012174f281010ea9d74dcf.nq.gz
│   ├── eef439d74f9dabd856bb7ff1379e921d6343ac3a.nq.gz
│   ├── ef06943627e9e06d31e5eeebee28af6e1cdfe601.nq.gz
│   ├── f103ac8da557579ba266730bfa13e43a5871dc0a.nq.gz
│   ├── f372ce7fbc6582a71657741d0c81a57652ccdf8f.nq.gz
│   ├── f7a11fd413a29398914b94d140c72a3e10f2a9f8.nq.gz
│   ├── fab49080b9872ebebaf174101445d3c613d90d8e.nq.gz
│   ├── fb83bae8d05a76d1ad5ee65bec94c2591a488bbb.nq.gz
│   ├── fc5199ec2fedd9850bdcb1c5954fa19a8a2e758f.nq.gz
│   ├── fd8e0d94feacb9ca808e37eaffc114a82e467bda.nq.gz
│   ├── fec60aecec84948db191637fa8a01340942d6e5b.nq.gz
│   └── ff533e475ac1408eec841363941ae08ed09445d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 297cb86af88b26106899eb231d50c7b96d164f78.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 138 files
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

[zytedata/zyte-common-items](https://github.com/zytedata/zyte-common-items)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*

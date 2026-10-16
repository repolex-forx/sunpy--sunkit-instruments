# Repolex Knowledge Graph of sunpy/sunkit-instruments

RDF knowledge graph data for [sunpy/sunkit-instruments](https://github.com/sunpy/sunkit-instruments), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunkit-instruments
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── df64b4e3cf35b66493a7ee1be8456e83aedb1fb0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── df64b4e3cf35b66493a7ee1be8456e83aedb1fb0
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a7037ada59024a5a088f7b202d6a22d4176ca9.nq.gz
│   ├── 03e65300bc01481edcbdb0df0c4def44ccf6db9b.nq.gz
│   ├── 06d160a92c54cdefd1fd0ce53341c95cebc0b3a4.nq.gz
│   ├── 0707cab0a62a6090f0ff733022f8143fea5f8049.nq.gz
│   ├── 07af8b582d401fad7ee6c97055ef1da5f84e85e6.nq.gz
│   ├── 0a33af97c3b840967b6e9a4c09a7ef5c26e46dd2.nq.gz
│   ├── 0a94f6908a1df93dd6c2a23142cce613dab74f8e.nq.gz
│   ├── 10a6756d9da7fa1ed3b782ce7044f0dae910f4cb.nq.gz
│   ├── 1153ed311a8fa75c5db2a0c90b0ed7c2388556cb.nq.gz
│   ├── 14f2864be906a44269f6d95599b572f66ce6f61c.nq.gz
│   ├── 186b8a74a2c520e2e89c8dc294dbc003f5eeefca.nq.gz
│   ├── 193376dd16d470c38d2fea0b209663d54a6f7c97.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 21d80249f51e8c221a0c307014c511e99bf588dd.nq.gz
│   ├── 26e0cddb7cddfa49cfd9f32dcf389b68a5f701c9.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 285fe0e6aed76670b546a83b63eb9e7bc500aabe.nq.gz
│   ├── 2ba79fe790494850a4d14020fd04d39e60e996a3.nq.gz
│   ├── 2bcb7b511acd247993f736f6b6fe2403ab1543e6.nq.gz
│   ├── 31bf5268ed3708ba82fb358fd50b589281b205c0.nq.gz
│   ├── 32a31354eaf3da03da0e9547658c6d6f7c0e6451.nq.gz
│   ├── 33c0ce63f393f6313ca85801edd5645f4ba51ca5.nq.gz
│   ├── 340752f5eba462d24790d9a855fa976bdfddbd84.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 3a25b87ae6633aa82292daa1c8fbf626bc1c4752.nq.gz
│   ├── 3b478b6f456360219a2739ce32d094844557d920.nq.gz
│   ├── 3c468b5bad72a67b2872d64bd758564e9e36cee0.nq.gz
│   ├── 41a148d113fd37e7124cfbcb1929c9141941a9ad.nq.gz
│   ├── 4209546c1293e462366f5dfba60c6cfc12b0cfb5.nq.gz
│   ├── 42cc42bba64e7aa5f675d7bc7b43ba224c151673.nq.gz
│   ├── 4489bb98abaa0dbb9e5e906e6df0e818ec62d269.nq.gz
│   ├── 48806e2c9222cd69039e5bfa064a5e17207f3475.nq.gz
│   ├── 49dd5f3663599157d4094a50f3bc4ffc6beef550.nq.gz
│   ├── 4ae5f401ac3312887efd8d7c0f7c4f94797c055b.nq.gz
│   ├── 4d326b4fcd313859dd59e6acdbdfae4348c63462.nq.gz
│   ├── 4fc87ac4ad0a5cdeb42a46e5a2bce6bd860e3da7.nq.gz
│   ├── 51d9fe4dcc88bd5c582139aaf89ed89964c82357.nq.gz
│   ├── 544a2dba78d51ed662a71e941aac2b984933725b.nq.gz
│   ├── 56e10795b6804ea10048362fe97818d673046255.nq.gz
│   ├── 57353c20731ad3b32f884b65983f7e89f813441c.nq.gz
│   ├── 59894c3713870cd7dd5e17cba93a467e37d685ca.nq.gz
│   ├── 5a25d1a7d418c82d330afa5304e74fee7063ec2c.nq.gz
│   ├── 5f4d904c0f55e1387da6ab5ed32fe3df3e742493.nq.gz
│   ├── 5fd5b84212737f129b3198239c5cd79a684205f3.nq.gz
│   ├── 601b842dabee8122f7595e4c1bfa6f0e749d342a.nq.gz
│   ├── 63bd3fccb08e4852ee6a1fa7d892172ea0ee5e7a.nq.gz
│   ├── 6780e50fa87fcb7ec5b0ae82c63b6e1d4906401e.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6873a3fddbe3b762904e242be77fc3cd2cecce02.nq.gz
│   ├── 6890bc29b654e742c8ef0455cc88b9b0fc379c00.nq.gz
│   ├── 69a95f8012508cacef8259e2b214848657cad58d.nq.gz
│   ├── 6c95fc3775ca5a2d887f600db3f2ff13c721ea77.nq.gz
│   ├── 708fc34bec44d54e9600b691b691269f2780cfc3.nq.gz
│   ├── 719b254c976033954951df5c50311adcc0270f82.nq.gz
│   ├── 75931298c0a445d7a35356671a3234bc8c036b30.nq.gz
│   ├── 759c2ee2f767c0b803167e1c74de385f2b24ce59.nq.gz
│   ├── 75b03c08c6fcc9ca94c04c7d9caa6dc4c8ba000e.nq.gz
│   ├── 78e2a62f6da694192fa020b87ea5c2cae1459633.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 7d5eac0bb17d53ec3cae54a35cfbfc125914ca21.nq.gz
│   ├── 7de91ee5e7a01938d7839ff8677984c521c4b79e.nq.gz
│   ├── 80a10550906fd65ab45157fb2b49bb687e63e690.nq.gz
│   ├── 828a796e6367f8c2c81ecd510de7ed4eea7bba47.nq.gz
│   ├── 83b4848c6fe07acb153d7e47612b4ef121d84a5b.nq.gz
│   ├── 84edf3ffc4a7360ad9836ff865fa65209168c044.nq.gz
│   ├── 85a2d84c1c8161f51aec7919c4471d224658d632.nq.gz
│   ├── 8640e884178af4649f534e2df90cc362f8e16597.nq.gz
│   ├── 87ef935f35994745e56ed706c4ef3d0394d539b4.nq.gz
│   ├── 89d4dd8a3ba6313e95500048da00594ac66f05c2.nq.gz
│   ├── 8b7c7b0562c2badfb8912fb6c630d7b3f02e3d18.nq.gz
│   ├── 8c2be05c0d11bbb42bc87360e714ba1ed8c10409.nq.gz
│   ├── 8cea97d516588d1fed484415c8cb4ce8c5c35799.nq.gz
│   ├── 8e5c19ed8491f6adbaccc1da12022f1d1af38ba6.nq.gz
│   ├── 8f331d434aa9453ac8a12926c95289cdff3ee9f3.nq.gz
│   ├── 8fdcc0941730910d93fbe9236f815cd7dedda5a7.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 91cac1505b0de9dbd428990bcd72e884c909cbad.nq.gz
│   ├── 92a1054020406edf0b1a65e1f58200f4d2ffd31e.nq.gz
│   ├── 92bf46384f60e7faca15a0715c4dcba0d1e35fb4.nq.gz
│   ├── 92ea707303e3d1f4b6fc3bb3446d173c4f8d3c10.nq.gz
│   ├── 952b80b58051343c6d8316445c633d6e2e0bc22c.nq.gz
│   ├── 95ef9ac85c33287120515236da4853eadd85912b.nq.gz
│   ├── 96492292adb88c233616563bbaa552236977242c.nq.gz
│   ├── 97e89d8e643783a117bc0ede5f65dd2d3595073b.nq.gz
│   ├── 988debf51060eb223212788187f60b37891ac768.nq.gz
│   ├── 995a0445499e27cd760b66353e41fa89c30ab10d.nq.gz
│   ├── 995e890f7ccf88420c139013dd4579ed0045947f.nq.gz
│   ├── 99ac951b1f7fb2f3895e203a3ce58e6e562aa9e4.nq.gz
│   ├── 9e55d8315bfe120b27b7cc7c29a327c81d881787.nq.gz
│   ├── 9f40977bed65c6d3fe81cdfe7527008210a631fa.nq.gz
│   ├── a077a5385e685698a7950bd90cbe8d2f8272d880.nq.gz
│   ├── a17467016e3d7bedcf0cb3ce927d5cbea86184d6.nq.gz
│   ├── a2ac92b90e68829470e7b3be5a40d9962469206e.nq.gz
│   ├── a63842815e7e8383e602174736871ccfd12fe9ad.nq.gz
│   ├── a85acf224085e3cdce1be4f62ee6bff799dfb0c3.nq.gz
│   ├── aac79ee2ddd7af8341c866fc6fce6c724ff7d07e.nq.gz
│   ├── af41dc4b78eec8eebd7d3ef92cf23b26f617a557.nq.gz
│   ├── b53f27f518b399635fd2516985cb8badcfcaefb2.nq.gz
│   ├── b66a0740e1ecc20b4121be469509704a3a06a636.nq.gz
│   ├── b83ba9bb226db56759ee90222bda9832bf3fb2de.nq.gz
│   ├── b9431b2842c824a44280324cef02eac6b7de52c6.nq.gz
│   ├── b9a0042a5ed657b8a65267c39b049ce920146b4f.nq.gz
│   ├── b9d47a99e7a88b587ae8633f62650d802abdbdd3.nq.gz
│   ├── be22d4f37e530725804f4c84c33d362391737d77.nq.gz
│   ├── bf161b3853f6e710252e4fa9f8b4da01379e2405.nq.gz
│   ├── c1b73a946d4a8db994f8e5ca75e549e789231db0.nq.gz
│   ├── c82334553632d12caf96bd3d3d332d9683d2635c.nq.gz
│   ├── cb6828086e2cbcc5ab91a2dff7736f3e52d9911d.nq.gz
│   ├── ce2a449ce9acd8d2ce16a645a8933bae8f36be22.nq.gz
│   ├── d2d7c9bfc7f41cf82788f95fde9bab80d123e8c6.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d7535bddceb81c604243f077eab29058e35ada1c.nq.gz
│   ├── d9cad596b0cad99a1c3a94abe15be7e72ffc1e70.nq.gz
│   ├── dc736b566eebe3afdbe730c9c4557cea399d0033.nq.gz
│   ├── dd2f139733495550b96cb3348635e0a47ccda730.nq.gz
│   ├── df185d83e08ea0d42cb891116f20f45dd5e33076.nq.gz
│   ├── df810cf3bbb11db37d98c7343a37ca237d9edfbc.nq.gz
│   ├── e38b3a8dc183cbe2b71aedbaf793b8192981ce43.nq.gz
│   ├── e4f17158c00ca2e9ce9a711572786b5972f26736.nq.gz
│   ├── e58e93df6dcbaaa62c0a497c5fb461e4c2ddb4dc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7399bda1bb64cb5e5648c7b921fc9080c2e687f.nq.gz
│   ├── e8a1cd4082451c1b78f29304f6e4eea5ac673ec2.nq.gz
│   ├── e8ecc437cadb9d2b35e1d26075c49dee15a683ea.nq.gz
│   ├── ecd8affecc776f3a0fceaa66874626a870367de4.nq.gz
│   ├── f1ef25dc8ef2af7ac00bbca5e064c76707e1aa2b.nq.gz
│   ├── f432cca28647dbd682a737b94a93980e8952ae66.nq.gz
│   ├── f447a08de4968eea96b7038eacbf5f496c896270.nq.gz
│   ├── f611abe9f5f792a5f1c2cc47e11097e981f471ae.nq.gz
│   ├── f792376d61a6dcdf1d642e2e67f2ced2b4756d6f.nq.gz
│   ├── f8fda2ee758ff9b5614cc031fdebf392d53b7b43.nq.gz
│   ├── fa8ef21af547547bb88c5fb302eb5fa1f7f42192.nq.gz
│   ├── fae0a699104be0efe1207248e8c6c77c20b94ff0.nq.gz
│   └── fd6a44a205f39c2e54dc2c6905865bf2150efd2d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── df64b4e3cf35b66493a7ee1be8456e83aedb1fb0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[sunpy/sunkit-instruments](https://github.com/sunpy/sunkit-instruments)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*

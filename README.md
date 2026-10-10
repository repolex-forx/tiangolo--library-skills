# Repolex Knowledge Graph of tiangolo/library-skills

RDF knowledge graph data for [tiangolo/library-skills](https://github.com/tiangolo/library-skills), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/library-skills
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 114fa2c3b1a54177d3166669b7eae15a70d66467
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 114fa2c3b1a54177d3166669b7eae15a70d66467
│           └── chunk-001.nq.gz
├── blob
│   ├── 015962cec0750a2aa3cc7efb2f4c54106870081e.nq.gz
│   ├── 02ebffdef8c8b11c4a58832601ba50a5be014918.nq.gz
│   ├── 036923f9e02549d5a7b5b2146f606028b3e00798.nq.gz
│   ├── 09b639f6baced21dc7d738352bd8b8945079014e.nq.gz
│   ├── 0ce4397b78095b29fff965be6142e311d7d68799.nq.gz
│   ├── 0fe9cfbd9de7ce58cfa15e494462367332c3d2dc.nq.gz
│   ├── 125ee4d5054954a6c73fd1f85482adf3a3987d99.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 18d1cb115aea91cbbcd407597f46e774ded38d14.nq.gz
│   ├── 191efea85f9ea102bb140bcaaa98e668bc799d2e.nq.gz
│   ├── 19b5e78dde13b80361b4300c603e5e200cab3653.nq.gz
│   ├── 1b70d9a2d7ce8390dfee33580211fcc7e64e5bfb.nq.gz
│   ├── 1f960430f80568772683b052d47c9579842a0c57.nq.gz
│   ├── 21630d8a29d7af2a77fb672f5a1896756f1a7388.nq.gz
│   ├── 22372c6893fc70e677cda95a4042407207326398.nq.gz
│   ├── 22a7a1fddd34065297654ceabc51ffb4aedcf198.nq.gz
│   ├── 23c8899bec47b488f96216ea808964b37077c332.nq.gz
│   ├── 29939a7b6039b80652a45cb70ec3b1933ddfc27b.nq.gz
│   ├── 2ab52a0af5e5dc72f6102173915c9eebd4558cfb.nq.gz
│   ├── 2adb02c04550cbece07eb536e3705d40f7d66a45.nq.gz
│   ├── 2af78944b44edc47ff15e094904470c0fef33ca3.nq.gz
│   ├── 2b8fe43e80fcf6b26ddc21e7d675f66eb4219cf9.nq.gz
│   ├── 2df033432955fe97d28d24e425865cba62a036ac.nq.gz
│   ├── 3244943688da412249b771c3f40ce3d548779285.nq.gz
│   ├── 32e1058a7f15656f25d3b98e40babc4e52776f52.nq.gz
│   ├── 360e4ef30fcabbab4da95a8112900365b772d083.nq.gz
│   ├── 37e23d1230203ffdf156327a17353a1ebbcf770c.nq.gz
│   ├── 3834f2ba0bb6701fa0e31c3a0270375038f605ba.nq.gz
│   ├── 3ad9ae3e43f940eaba7cc536af06e5d7fad63d9f.nq.gz
│   ├── 3bd7ae8de3214c2bcc9c782590330d868f80c5ae.nq.gz
│   ├── 3ce8d14711ad6819c382e2142714d427e1ee0b09.nq.gz
│   ├── 402506f3d4888df2726d84a871bea1f4703eebd4.nq.gz
│   ├── 40f7c241f01ef3bb2657e1b16012a5e67e585bcc.nq.gz
│   ├── 411e9ac15e3fbae25447c32026ad94a6ce848cb0.nq.gz
│   ├── 4ba9ee2ba4ffb8b92008a85cb13b30c77e1361d5.nq.gz
│   ├── 4d252d86e68c2f374b1f79c1021756bc33c10936.nq.gz
│   ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
│   ├── 517d3c64b2026c3a2dc18988596a85cbea9ab932.nq.gz
│   ├── 5184058789729a406e19f4bdbb3c0a67c46d6dcd.nq.gz
│   ├── 545d30a18cec93495328868463868efc1fccb7d8.nq.gz
│   ├── 5479c711371bc04e12961e737265143bbe530260.nq.gz
│   ├── 5c81966703b79f0d151b7baafd4a481146c3b8a2.nq.gz
│   ├── 5d122595fe020a567d7444b808aa990c7f2de1ac.nq.gz
│   ├── 5e496d60bc9cd117516f679b8f6a55ce06297491.nq.gz
│   ├── 63d2a617bb6a091c7d2e5f9ea20a7bdfe8f192e6.nq.gz
│   ├── 6b4b80508a8ddec99dc8e68b6a00bb8bd1d54ae3.nq.gz
│   ├── 7202984a7e2362999a60ddd6bd5d3de503937f2d.nq.gz
│   ├── 743841c429e7c40a0f0c294ca2dbb09d45a6bae0.nq.gz
│   ├── 77ccdd526b58cb2c0bbd266438e9d785372b0fe1.nq.gz
│   ├── 7c6544af608bf5d0e5014d5ac9e3cf27853303b5.nq.gz
│   ├── 81f3cbcd19016551422dc0da4bd28f1bfeb57309.nq.gz
│   ├── 88a8ab671777e476ecb5b357e7873a5d1488fff1.nq.gz
│   ├── 8b170f7a27182db87c1a3031eb7fb4aadc72a7d7.nq.gz
│   ├── 8c76edb5325ea054b27e2f6399dd318173b1b4f0.nq.gz
│   ├── 8eddfa7baeaa73f695e24e13d57c3d0abc2c2f96.nq.gz
│   ├── 92160356610c310bb91decb355661d2333645856.nq.gz
│   ├── 947abc582bcc4cfdad715945b65fecbdec8efc04.nq.gz
│   ├── 95443ae06eacddc6a178d7a12b51175f3fd3231d.nq.gz
│   ├── a6091ab0f0d086e2590c813d05ee1380236e009d.nq.gz
│   ├── a7513150653b1386762accba9aa9bb71dc014afa.nq.gz
│   ├── ac204b94e9646f7938331df09b328ab685a33f13.nq.gz
│   ├── b018c8eadc45026dd9371d17132ea7db0657768a.nq.gz
│   ├── b0e973615e1292043dc49b521cc3e2681facf818.nq.gz
│   ├── b317eb8f25a2e038dee332ff6ce4979d56c49ef4.nq.gz
│   ├── b56df9da596ffe1a7554687a7f3b63441017ced0.nq.gz
│   ├── b830f31696f599cf6f803e6d9bcd9005b9142739.nq.gz
│   ├── b831c857948b57dc7a73ccfd950c269a3e69daa3.nq.gz
│   ├── b98b0b6c0b14e39277fa9edfd834df20bbb04c64.nq.gz
│   ├── ba82e6563a60f2ccf021c6864d8475ccfa55ed03.nq.gz
│   ├── bc7bea0d4ef5693099f63e058fc8be0fd2d3246d.nq.gz
│   ├── be297851f7234985f1acd08f9fc3f7bec1bcc4b7.nq.gz
│   ├── c4dd77029eb3d31d4b61f47c4d1a542a39a02a93.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── cb0ff5c3b541f646105198ee23ac0fc3d805023e.nq.gz
│   ├── cb7dcc7dcc4aa9a4f3af9fab147bfd798ee94cc0.nq.gz
│   ├── d0f2c2ca568104ec5470fbe0cbfaa66e80257581.nq.gz
│   ├── d4652398ebea5faa4ce2c3defa8c1e4d3d556d5f.nq.gz
│   ├── daa6038a0a8a386d6315b541c501a9a2abddc650.nq.gz
│   ├── de4d8d1442e93d761007e4be0c28dcf6b157d8da.nq.gz
│   ├── e005bb4badeadc00d5ed92ba6c890aa0dc4b573a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eba88d3a05ec02ea04bdfebab6ae42ba2306861c.nq.gz
│   ├── ecd1abdaa71524d60f7dc1f2fd9b7e552cf66e11.nq.gz
│   ├── ee9b1df11ded59daac1cbfaa3e8563413f7038b3.nq.gz
│   ├── f14d1ac6bc38e88b0f8fcfba02e01a2eee359bf8.nq.gz
│   ├── f558de1d815b264b2576a5b9698f83c46b0beee0.nq.gz
│   ├── f68f60fb7df32f69e3082b6488438fed82cba84d.nq.gz
│   ├── f6b3c0c7ba806b40c3596fac631cedf7ac9936e8.nq.gz
│   └── fd2d4b4cccb12cc8a6a7850149aa6a694b88fe46.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 114fa2c3b1a54177d3166669b7eae15a70d66467.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[tiangolo/library-skills](https://github.com/tiangolo/library-skills)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*

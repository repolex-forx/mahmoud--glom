# Repolex Knowledge Graph of mahmoud/glom

RDF knowledge graph data for [mahmoud/glom](https://github.com/mahmoud/glom), parsed by [repolex](https://repolex.ai).

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
rlex download mahmoud/glom
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd70d3051a6a1bcb5152ec2d8e2cdc8e852f95e6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd70d3051a6a1bcb5152ec2d8e2cdc8e852f95e6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0299e2fc3ef02480cc4dbc5de589acbd7cae892b.nq.gz
│   ├── 0338d95ffb89c5d826a83924342d341a76726698.nq.gz
│   ├── 122bd0863df47161b8eb663797705f4c3e00a4ab.nq.gz
│   ├── 1d3ff8beef01b53b73f352acec6abba2ed45b6a7.nq.gz
│   ├── 1d56784822083d23a2e4bfd513afb435b9495906.nq.gz
│   ├── 1db9118a1d96aabda083431a955712da0cec0488.nq.gz
│   ├── 1eb285e3b98cb7e5d4cb9c6b78b33a58b1365a4c.nq.gz
│   ├── 1fcd47af83c67cf6e99e722f907ab357f1947181.nq.gz
│   ├── 298706420dec85a83ec8073ceb299376199296b8.nq.gz
│   ├── 347cb083ee987ad5742660ba0937da6235c3db90.nq.gz
│   ├── 3844ec815434088d9683b17bd6e94604d7402263.nq.gz
│   ├── 391b51bfd63900c845fb9b1c7a9eb8f0f5e382e9.nq.gz
│   ├── 3eef79944bb90c9febdb56484f6a46f9d5b02860.nq.gz
│   ├── 44ef45bc4703a35016ea9ceae0d326881889388b.nq.gz
│   ├── 44fa2c21b0486725ef29fec8a793a5f2130617c0.nq.gz
│   ├── 46ced13b002c4926b82474ae2cfdaef62a0bd54c.nq.gz
│   ├── 4a27c8f772240a421dca7c8389cc3451e5b5e877.nq.gz
│   ├── 4da5fb50b26ace62b086106f7d731ca1d68840f0.nq.gz
│   ├── 506659a9456631752a2b11151a00075cda50f259.nq.gz
│   ├── 580980a36e4feef4f21ec25f75d3f8c5ddcc2b86.nq.gz
│   ├── 5cb7da65659846415bd19e2a85165aca9ef3b9ab.nq.gz
│   ├── 6758470ea66665d45e3ac81bbb4771f5fbc8717c.nq.gz
│   ├── 67fefe7ffa8c1fdd086ae9c76fc63a409b258744.nq.gz
│   ├── 6c31b39dbec4bfa00e9ae350ea6f09ebbf85a59e.nq.gz
│   ├── 6c555e5a02c06eedf9b90aeeec95f5c896b269af.nq.gz
│   ├── 6ded37c3f8efab0d652a67f5902f8ae860f122fa.nq.gz
│   ├── 7256ab6a785239c49ed0bd0b78de12807fe662ef.nq.gz
│   ├── 7392105175a7aa8eda662b314d426cd37f7e876b.nq.gz
│   ├── 7781bbaf8f8df1fe878a104c320431460ebf6eac.nq.gz
│   ├── 781acd876e0d9d1f634290cc863515a423a794f6.nq.gz
│   ├── 798ac402c07ccc59280e61e002a4f28069e0748a.nq.gz
│   ├── 7b08a02fa86137387a95d338ecd5e9b2e7260ab4.nq.gz
│   ├── 86e24e7b1434fd7ff7c5c9a5522c8a4276bcb428.nq.gz
│   ├── 881b4b76ba208136c7fbad43bfaff4b4d8d8d6c6.nq.gz
│   ├── 892197c3e1d6384d2f28ff8343d59fcfbe9c0868.nq.gz
│   ├── 8eb9f172f52454263fc0e6e568fefccccd6454e9.nq.gz
│   ├── 900a79efc13ba1c4f674910eb9dc4ad6c7debcd4.nq.gz
│   ├── 91872adc26dee02ef5531521987ba649e1eeb92a.nq.gz
│   ├── 932053e4beb7cf7c9d6577629e558415444a6419.nq.gz
│   ├── 949d9482d2c7fdba90e723fb5179b523278b3883.nq.gz
│   ├── 9935c57e675352d63f91a0faa07e1c54c2d11005.nq.gz
│   ├── a148bbcff0dda1209b4637c7574e37591caf0f54.nq.gz
│   ├── a608117a28ea4054e7a5daf5fe02f097fc26220f.nq.gz
│   ├── a673dacf10758913485875591ea3bbc106f0fcce.nq.gz
│   ├── ab95a8f9324a60369510d4da0b6c5d07949e3b7c.nq.gz
│   ├── aef5bff4ac9c1b7e7b6624337e28d6e611d1416c.nq.gz
│   ├── b400ce0d46e331e1d52f3924eb14ae1c38ef2ced.nq.gz
│   ├── b4e3c392127caf39a150a70b69cc9ab2f406623b.nq.gz
│   ├── b81024b68ca73cd2d8ac79693a037c390e633a65.nq.gz
│   ├── bdae731433c8d1bc39ee9e89d36dca1eb340db93.nq.gz
│   ├── c0b1aae271cb227dfc4d025078840f5b9e3a3c5d.nq.gz
│   ├── c856b35ffc65c95f6d97bc4938efcc80fd179ecd.nq.gz
│   ├── c9fb382d52e2df3973ba1f3d8785e6fd0d738ba5.nq.gz
│   ├── d102c2abc6651791b14953efc1b18b2d194011ea.nq.gz
│   ├── d38cc21c45119191cbe40fd534a233e3c226e243.nq.gz
│   ├── d8c54fc4c7abf078b2b1b637e373e97d25da7b36.nq.gz
│   ├── d8da949099ca29d28fa8ad00a5283d7ef6eae924.nq.gz
│   ├── d9cc9a12532dae7fb8c901d15dd82ab1a4c74eb6.nq.gz
│   ├── dca24b4b8dd2170706467266aaf3cbdce3f979a2.nq.gz
│   ├── e471488bac2ae1f5c803cb9426653d63372611d4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7cf77b45875f5ec604e89c28c579629cc5f0c7f.nq.gz
│   ├── e97c337cbb2bf87ff23d850cadda3d87f6e6b3d6.nq.gz
│   ├── eb7e691501c5127a8e5ab7851c5b1fbef1376a6f.nq.gz
│   ├── ec86b391ea93b1a0a2133f7644b546f3cc2d1702.nq.gz
│   ├── f22af56c7798c4b6c00109e9091ce3d7f24eec09.nq.gz
│   ├── f2603c3c4d10291c0d96fe62cc1b21fb61925215.nq.gz
│   ├── f6cd3a762549585594244e7a1cbf6d7490afc531.nq.gz
│   ├── fc214129cfd9b6eb0b2ca09c125e901bafc6b003.nq.gz
│   ├── fc38888bcf934b1de7b64ab0b3ad7003d7a22fa1.nq.gz
│   └── ffd950db3f96623431e852bb8adc2e79224c126f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fd70d3051a6a1bcb5152ec2d8e2cdc8e852f95e6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[mahmoud/glom](https://github.com/mahmoud/glom)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*

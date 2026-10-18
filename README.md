# Repolex Knowledge Graph of simplejson/simplejson

RDF knowledge graph data for [simplejson/simplejson](https://github.com/simplejson/simplejson), parsed by [repolex](https://repolex.ai).

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
rlex download simplejson/simplejson
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ae4376804cbd09e683eebedf714984360effbca
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1ae4376804cbd09e683eebedf714984360effbca
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f3cc66ba6e2a58897d966de81a89a5a926329e.nq.gz
│   ├── 0777c8837c5fd64a425ef1ee106d41f4f201c20f.nq.gz
│   ├── 0c7b1a6c444abcb041ddbc1c56e055144a695fb7.nq.gz
│   ├── 0c91d34c6b74a0b8dfe64ef9c3978eb59863822b.nq.gz
│   ├── 169761d3e55044a1144b4764a54d0e0b135c0870.nq.gz
│   ├── 1713fd9e244c57b1f05db7cbf033479d79f65264.nq.gz
│   ├── 1dfcc2c5f95703ce2cf890a60e293b770bacb061.nq.gz
│   ├── 2071a70206b83bf55d6b6e2b8b37c4d051a79e9e.nq.gz
│   ├── 239ea9adee4393ae53a37874d06e2543882fc442.nq.gz
│   ├── 2bae3b6309efa4ae9573055de5359bb30f6b05f3.nq.gz
│   ├── 2cf2cc2966ed35c64deb84522561b5c0dcd821bf.nq.gz
│   ├── 315ff5446346c2b2838a0276fc543b2dbd9905bf.nq.gz
│   ├── 35627db7c156c1e52fd9bf60091ffdb0cba85436.nq.gz
│   ├── 37b4ad9d16efe261374b09cf066081923aa1aec7.nq.gz
│   ├── 39fe3680fe18a46e0117e89af73f0ddcf281df91.nq.gz
│   ├── 3a840aa48cba3cdcba91be93cd4da4925fdaf301.nq.gz
│   ├── 43bf8953997776acfe9f7574ddac3f6753b97a93.nq.gz
│   ├── 49706bfd978b16c9cf31a89298bb71b4b91c7de6.nq.gz
│   ├── 4ad7b0e861bab79be612a5e2804c4143335304f6.nq.gz
│   ├── 5ba49f9706c07f2ea13208070fd3f3d85b5acaef.nq.gz
│   ├── 5d812b3bbe21ac603aa55c91fcb06cc7e3506c06.nq.gz
│   ├── 662eb667ece76d4a352dd09d7a51c0a1a0d21e9e.nq.gz
│   ├── 6bf42907bdaefb46ea9cf360b1fff1e258c7e072.nq.gz
│   ├── 6de219b4f34d748082d426b548e501e7e66042fa.nq.gz
│   ├── 70be7bcbbc6995be2e35d6b2e5a425f26dc5806a.nq.gz
│   ├── 73927e798441392b28067ac51ad932b3f8db3237.nq.gz
│   ├── 7a1de5b36bc10a7b57d472500946689060348e8f.nq.gz
│   ├── 809eeab902d5b9514b2fcbe696da0841b6095c37.nq.gz
│   ├── 821d60b22ccf32fecc941481b1ff0db59970d4eb.nq.gz
│   ├── 8fe2f47af9a18ad9f272357023d09f78aefebe2d.nq.gz
│   ├── 91b4d4fb6f386416824faa6a2b471cabf0337390.nq.gz
│   ├── 9557998539702639cc865074c673fdc81665aee9.nq.gz
│   ├── 98971b86ac7c096125a1d5d40e953e6c542f0820.nq.gz
│   ├── a048d0aae6aab8b94bbf7907ebd7ade49aebf9c5.nq.gz
│   ├── a41b61e4bf0fb320fb7f9d6aba53528650978995.nq.gz
│   ├── a421c7f9e9e56c7183b5db15a1bb8338ec438dde.nq.gz
│   ├── ac2327581e05eed2c7795ff62418368bc3c4ea4b.nq.gz
│   ├── b4cde83e659086a1c9ee6c74cfefd261417edebc.nq.gz
│   ├── b5fc0598a413df17284f046c31b53e8ac4a633d5.nq.gz
│   ├── b6c8351f2648aa76c1481636a3f2889c0ba49b83.nq.gz
│   ├── b97ab1e913fc8fa21010fb85d9f7f7c8360d3ed5.nq.gz
│   ├── bb695432a3066beded2a2f94a574c799923b7531.nq.gz
│   ├── bbad2df1aeff2bda132f8b06159b06f664964c64.nq.gz
│   ├── be15b8eb0701adae9e6a93e323479391ab749225.nq.gz
│   ├── bffb70b8add46e6102d815b56b18a63d4fb5a72f.nq.gz
│   ├── c0843d822d64495d4d5119614c8c3d04607b34c7.nq.gz
│   ├── c4edb58ce1a3c51c14f1986adb84d6a506097d39.nq.gz
│   ├── caa26050b7a4b5fc424096477594aca430a167a4.nq.gz
│   ├── cd5c41bcb1323d47aca79a1547c7dd321b12d9c8.nq.gz
│   ├── ce598f626ea0e964bb58baa67fc2574f9fa874ff.nq.gz
│   ├── cea25a575ed8780e4077f2a766675ed565e4d4b3.nq.gz
│   ├── d1eacb8c4c39fbdad1f24a026289314d0ea72884.nq.gz
│   ├── d5a55ebd0f76a9879cd1732fadf3693570002a32.nq.gz
│   ├── d72c6d22d63be2aeb8a6ed7c7ef876497ac306e3.nq.gz
│   ├── ddfaaf6c2034a809b743a63ad4d456dd5d0b1b80.nq.gz
│   ├── e05f49c3fd0d8edfb30be0232fcd4af64fdf9505.nq.gz
│   ├── e48aa29da52122c7fb4702047baa9910ff989cd9.nq.gz
│   ├── e6f6b34684dc130a0d973d70cc8383a1535fbb04.nq.gz
│   ├── ee3ad58933b853245b0000dcd10b73ac90d07813.nq.gz
│   ├── ef09db83578298cbe880373b6df3c757bfb14d1f.nq.gz
│   ├── f0b5b10e76194121dfe5b9a6201e9d18b9882267.nq.gz
│   ├── f483e2b2bdfd8f21b15891e40cb24fafbbf48fdc.nq.gz
│   └── fed1bd97cd64c1c15c8194972a017232004127c4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1ae4376804cbd09e683eebedf714984360effbca.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[simplejson/simplejson](https://github.com/simplejson/simplejson)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*

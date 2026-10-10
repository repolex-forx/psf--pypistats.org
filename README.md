# Repolex Knowledge Graph of psf/pypistats.org

RDF knowledge graph data for [psf/pypistats.org](https://github.com/psf/pypistats.org), parsed by [repolex](https://repolex.ai).

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
rlex download psf/pypistats.org
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2a433267de472f51c5594029f61fc73089109646
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2a433267de472f51c5594029f61fc73089109646
│           └── chunk-001.nq.gz
├── blob
│   ├── 002070d7cb9a96d7b888028a3956c663512cb4e4.nq.gz
│   ├── 06c93e776f6697b63206db27f877f542a362518f.nq.gz
│   ├── 1103075156b7b8ebfa32473117b9e3a1c4aee320.nq.gz
│   ├── 11956b2415cbe54c19a3d64c150a6e9590894f36.nq.gz
│   ├── 13abd5cb1b2a080d80866ae14c5bdaf3923cc84e.nq.gz
│   ├── 18bd13b91add14b9f5e5433c0b45ef402510e77d.nq.gz
│   ├── 1eaddd68d7704727ca0e3be36b667828bffdcf72.nq.gz
│   ├── 21f83d7366870364a228f91249856762ddd8c968.nq.gz
│   ├── 2c0156303a8df3ffdc9de87765bf801bf6bea4a5.nq.gz
│   ├── 2c53bb74c1e3e7742be6f7670ff43850afa01288.nq.gz
│   ├── 2e6272a34e50188c88112943febd8742dbc3dcaa.nq.gz
│   ├── 36a908ce200a6b874a4c8bd72ff71964103ab6b6.nq.gz
│   ├── 3edf182b64fc8d6a730ea91488ad55876554845f.nq.gz
│   ├── 40c27a0b385300ec3da4480bb3c664bb24525065.nq.gz
│   ├── 45506fc90fe5ea68a3bc9ea3679bbaf550434961.nq.gz
│   ├── 4c3a75a4d6f33ec4c44415f9399938dd950bbe6a.nq.gz
│   ├── 5c20a9482acde674024b71318b9462735d97984c.nq.gz
│   ├── 5db38d77c02c569ed9ca29c2020918f107b94ff3.nq.gz
│   ├── 6322cbc91742d3c8383f07b18a375be65fedb760.nq.gz
│   ├── 65b47ef57d69f54196687223ae2a5089fee55e68.nq.gz
│   ├── 69f6f12cbf148783920ea4a4b087fea22b9e2103.nq.gz
│   ├── 6a4f657bd38f99510c1dd29c9b0d98bb680e674b.nq.gz
│   ├── 6ba593adf46b2760144726e42e2941edb5276d58.nq.gz
│   ├── 7112394865f1c4ff89d4a71b1374d1d4297d314b.nq.gz
│   ├── 728ae7e80f59ac37a2772a53b8f46358e0c268be.nq.gz
│   ├── 728d3dfcdd60ce20a4fcc9afbe052c84db78d0d2.nq.gz
│   ├── 7695760aae0fabf710c3190752939a21e61be94e.nq.gz
│   ├── 7884f0fea7a3729a1d5908a5099dd1f2d5bdc714.nq.gz
│   ├── 79b3b2e4bc7b0171cd9d345f441db479bacbb7de.nq.gz
│   ├── 7a36ec695553058f1026be0100b7e4ca935b8ee0.nq.gz
│   ├── 90b3bd212103868ca6984a2eac77fb7caa8f90f4.nq.gz
│   ├── 91c88b8a7f52a98a2dd6d7d791c97c6e6cf4a623.nq.gz
│   ├── 98e4f9c44effe479ed38c66ba922e7bcc672916f.nq.gz
│   ├── 992d98ea2b00bb3503d57c2f172ade39a68bf99e.nq.gz
│   ├── 9b066d914d3955efb3b5f4a5966ce7b71852b59b.nq.gz
│   ├── 9f8b1310dc52782085443b7761ee7abd9c18d3bf.nq.gz
│   ├── a951c05c0916f6e4f035b5d1034d7f87f76fe4bb.nq.gz
│   ├── ae91da3e6c08cfa8714f3dced0062a96332ba6c2.nq.gz
│   ├── b24a28a011d56b73a831d9de5819571e9512751e.nq.gz
│   ├── b92412a9ae569a952ffacce9e84de0ddec59204d.nq.gz
│   ├── c7b4969956249a5df079e70266b7cb5790052a96.nq.gz
│   ├── cbab1fe899f647d6b7ecc90d15e32f966f8397eb.nq.gz
│   ├── d282913ab85f63531e62aa9fd676fa623f5e27b9.nq.gz
│   ├── d3148dc514e815e2a31b31faa97126c1c1af94a4.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── e2b373568a0524c3f1148927e3ab9dda95306d55.nq.gz
│   ├── e4bc0110885c01b017a5b2db1b8d5dc082d04a65.nq.gz
│   ├── e51531a3202b5304aaeef3d559698c6794c6ad55.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d91c6d9ced01fbb454a0abc7df9d771a5610d3.nq.gz
│   ├── e827ed841b7c096e29403ed6bbb204f5fe0a0fd0.nq.gz
│   ├── e8c2c9987cf350db7f67ca2fe453b282f874c393.nq.gz
│   ├── f24a0d6da8658e2c21219c7c9fa59c1e814c8975.nq.gz
│   ├── f3da74b256bb07d703fa1bfcd2fff2f6ea3679c6.nq.gz
│   └── f4221674166c4e023f80746ef56c3ccab0534f58.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2a433267de472f51c5594029f61fc73089109646.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[psf/pypistats.org](https://github.com/psf/pypistats.org)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*

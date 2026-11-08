# Repolex Knowledge Graph of UKPLab/tacl2026-citation-failure

RDF knowledge graph data for [UKPLab/tacl2026-citation-failure](https://github.com/UKPLab/tacl2026-citation-failure), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/tacl2026-citation-failure
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 14fcd7643e7d735081e2a3d1b4f551809f1de9b4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 14fcd7643e7d735081e2a3d1b4f551809f1de9b4
│           └── chunk-001.nq.gz
├── blob
│   ├── 020269518250c391da46c03f597d9f6e90eef8ce.nq.gz
│   ├── 0716b041bb38bb573a074b1639738f612ab66fcf.nq.gz
│   ├── 09ea7185d393249420635ecffe3b6d8b05a651b2.nq.gz
│   ├── 136daefae5d7ed2a3824f6b88951c4d50c87fbdd.nq.gz
│   ├── 17e0255fae706eef5b762dfafa3b1650f734133d.nq.gz
│   ├── 197b31cbfb7668404ef80f517d400db9da1f7007.nq.gz
│   ├── 1c041334068dd67771d75c91b026ed54408d6b8d.nq.gz
│   ├── 23405e23b0e53d304cd8e9ee295c5d6c62b0afa1.nq.gz
│   ├── 24a7e5b5d67db9961256e7e420dfde4a66895e05.nq.gz
│   ├── 28b9a90c61c5601fb989e08b3a48fa4e0bccb325.nq.gz
│   ├── 29b8130d5478f9b8a5c25114062bafdde56cab3f.nq.gz
│   ├── 2d5213243d69dd39fb99c490db5ea58dfd0328cd.nq.gz
│   ├── 2f4ba46c0e2187b91e38cefe0bb89c374a62309c.nq.gz
│   ├── 2ff88b5b1bf353aad7bea21ae91fd1a1ec4aaa2d.nq.gz
│   ├── 324b540c2e8ef5bb6465619c09d3211985abfa6e.nq.gz
│   ├── 342aca776322de4a9007826877785a10a57cf168.nq.gz
│   ├── 38b47614af18aebdb0149682fb9bbe3c34f90c5c.nq.gz
│   ├── 3c3eb097bc1c8ee4316f9f1f06d49cf7a326ca5f.nq.gz
│   ├── 3d4ead26a8ece387fcf20b2fe73fa93912b9acff.nq.gz
│   ├── 42b1b3ea1cdfbc191b7b8abbe44fba6a16637910.nq.gz
│   ├── 42e90228372109a2f8608ad7bb318b79bc7d07b9.nq.gz
│   ├── 4494992e95a890d760734ccf84e8f96ba53b132e.nq.gz
│   ├── 46c3659c02341ef83eccbacd08e227c45c806682.nq.gz
│   ├── 4b38509bd961567b1e92d27348ab964ba509574d.nq.gz
│   ├── 4e1ca0c09d646bd9c419e1dd5685f6b74b3e0972.nq.gz
│   ├── 51afbdacb0f37876f05dc8830ea6094d61af1708.nq.gz
│   ├── 51b678d9e904488b949a09e739e9e0b912b0f55d.nq.gz
│   ├── 52973b7b285bde0dcbcef48cb5b203c28af6c33a.nq.gz
│   ├── 579d152380307d0f5aa39e08ea137d4787385210.nq.gz
│   ├── 5b1a08c1381ffd652d14640e1af677dce156873b.nq.gz
│   ├── 5cea4907486b186dc5abe3e83845b040a4a54e74.nq.gz
│   ├── 5d68dfd7c011f82a9c9d78dc951bae1f7f0c91f7.nq.gz
│   ├── 5e21b9064725e8fa41d221b18b2e52732ae2823d.nq.gz
│   ├── 5fe70e4f5655efc79f758f5e9291af044c9e4b14.nq.gz
│   ├── 63cf5f30c09d511a4a5d098281416606645a3b88.nq.gz
│   ├── 6dd86c90f3bf84785be78a130a3209e72fcd01d4.nq.gz
│   ├── 6fd19ab066d8d41f3592c908243069a25d0b4c37.nq.gz
│   ├── 703d9c5d5a33c5005b7b71ef92f39128d68a30eb.nq.gz
│   ├── 71af7bea8fafe782ca90b58296f0d783b2349435.nq.gz
│   ├── 73a0b749f95ea86e5cfdef954e0d4575a4b2f301.nq.gz
│   ├── 74931060aa6ba88423d26b7bd37c00c5c7c4df35.nq.gz
│   ├── 7909e49a9fadf65b977bcd693244fa0e107525f5.nq.gz
│   ├── 82dec67875f7eb4d88adbc831fb2183fae7145b2.nq.gz
│   ├── 866cb2511217b4d4ec263e56f1ca56d7f26623ba.nq.gz
│   ├── 86d7db8b8dfc7978305d69cea237fc1bc8b53e69.nq.gz
│   ├── 8749dac2bf1f4978e1aaad4d2649c9fdd599ae78.nq.gz
│   ├── 8950adac219267a396877f41fecf02818cbcc4b8.nq.gz
│   ├── 8d25289cf636d04fd923c6a796ef2f038bdf271d.nq.gz
│   ├── 8fb9c340869a4e67247ee8d793777a0350ae8455.nq.gz
│   ├── 945e6e1eaba07a0f3f33d2f9f44a5a004ac34bcb.nq.gz
│   ├── 973e134d9d36cd0f10ee1be15d23f2db83c325bc.nq.gz
│   ├── 9dad8b881c5f5a124f712056ded03002664a201c.nq.gz
│   ├── 9df535781b9ce4fc47c6d572a243642bf6ea2919.nq.gz
│   ├── 9f71ebfd3cf8742c956555b6e8777239cc594f29.nq.gz
│   ├── 9ffb8ad5c5f0b6f1d03a7bc766ea074617aa8226.nq.gz
│   ├── a1566bba7026067b9e0dafce2c8eb89faa66fd10.nq.gz
│   ├── a2b44b509237a0cf35046508bd7666fe500ece7f.nq.gz
│   ├── a3a7bdd5ac42d7410db07b747a0b470c1c4741d0.nq.gz
│   ├── a6a068878691c1c175a9ef51d7a4148d55329055.nq.gz
│   ├── ae27452daddad344b8197ca5cadfa652ed1d44ca.nq.gz
│   ├── ae997aea1f319270560e48ce328f7a960f474bc7.nq.gz
│   ├── b0264bc48a1e70b949e9e1631d2f77a297230d9d.nq.gz
│   ├── b09c32c095397176664812843b8bc565952b97ad.nq.gz
│   ├── b3e4d3acbaa1703a104432b65cb07c0fa689a80c.nq.gz
│   ├── b70a55204933be203922ffeca91be9c917935b2c.nq.gz
│   ├── b7d6bb9c6da5d2fc8a4ddc3716125f8368aa98fc.nq.gz
│   ├── b818d6c88e8a78c02567d654efff56353251a97b.nq.gz
│   ├── b9f596ced052b1edece3f41d1a7c0cbbf220cd61.nq.gz
│   ├── bad4da76441b3c0822b6a438c160cffadd9bee37.nq.gz
│   ├── bc29f228e0e4af2962a013a4407ccc0c86cca7bf.nq.gz
│   ├── bc5bd626d80c23bd7c599ee1db78666e7eade4d3.nq.gz
│   ├── bc7a3cb94d68b5c92c149ad670a15216a645d037.nq.gz
│   ├── bf9420bc6766221e891503101f7e6f7ec79c16ad.nq.gz
│   ├── ce85ef612d41499c35a071d4681d1ddb03cdc660.nq.gz
│   ├── cf7640a6e063c1c45e84e2951f3c8e41f79e96e5.nq.gz
│   ├── d026b5c37724d06c4c9e8d897683ad560c7db25e.nq.gz
│   ├── d152c933ef46b3ee9f92e0ae29bc0c32bfc991e2.nq.gz
│   ├── d3c191c5815bfd50a4f0525a68bde19629b4e098.nq.gz
│   ├── d9683f02096c2012971b03e2205725da0956b10d.nq.gz
│   ├── d9af7c6f030f669c9dcadb1b8be295d29671f50d.nq.gz
│   ├── da8535f3cdce22ebb6cd49bedaa3ca63671de53d.nq.gz
│   ├── dbe5888ab2f33d55f9ddc1780c8a4a7324e29265.nq.gz
│   ├── e331aa469adaa4eb546f175ce57b5829818337ba.nq.gz
│   ├── e3b0daa95e5ae47b681d6cdf5718c66447356b67.nq.gz
│   ├── e43e3ce4202c9950ea2030be53e0f8cba6a811c1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   ├── f62947df70d0c1763f6e669e6f4f8fc45cf20d0b.nq.gz
│   ├── f66c15a8a7e905083b30d43646bb29e8d846e499.nq.gz
│   ├── f823db80ed96b6ac9722dff42f101c394e077f2d.nq.gz
│   ├── f8328f2ec5e883ec8855207284966f75d7b2e06d.nq.gz
│   ├── f990c86f2ad843eb7862794f460ade11b06da962.nq.gz
│   ├── fb184c52e110bb7b9add05c5de32829721f6b5f4.nq.gz
│   ├── fe9cd4757463e70976319cea2ce423f68aa5f539.nq.gz
│   └── ff75c61bf803bb1186a359d571b23ac2b0c76122.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 14fcd7643e7d735081e2a3d1b4f551809f1de9b4.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 102 files
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

[UKPLab/tacl2026-citation-failure](https://github.com/UKPLab/tacl2026-citation-failure)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

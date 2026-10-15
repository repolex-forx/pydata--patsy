# Repolex Knowledge Graph of pydata/patsy

RDF knowledge graph data for [pydata/patsy](https://github.com/pydata/patsy), parsed by [repolex](https://repolex.ai).

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
rlex download pydata/patsy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6d9d5697162c3543dc55009074695f9997a8471b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6d9d5697162c3543dc55009074695f9997a8471b
│           └── chunk-001.nq.gz
├── blob
│   ├── 052e0020ecc825d347d0e9570678ba850a499859.nq.gz
│   ├── 080af84a76df62361652a82c392b5a9bcb8237ef.nq.gz
│   ├── 0ea262b5c561c75c8ce4e36dad8a53db7df9538a.nq.gz
│   ├── 165310ce900a13a73b166015df9145bff64e6a65.nq.gz
│   ├── 17ee1dee461829638c1f4dd06c98d7176b0a4476.nq.gz
│   ├── 1a324f784df7da7c7cef7edd359f19189d915860.nq.gz
│   ├── 1af6ce8cbfeab87e0dbd501bb9e44f012acc1a65.nq.gz
│   ├── 1bf282cf1a261807c6711b5038302f101ccafd63.nq.gz
│   ├── 1e5f46b637f9f4359ecfbcaf829b6030c551a3e9.nq.gz
│   ├── 210350df2c9b772b06824e2ab99613ed1ec5b32b.nq.gz
│   ├── 23b31fecf3cc6d2fa6092ecfd256781ba0d6af64.nq.gz
│   ├── 24d3e32aba8604d8c91b58771323f6cdb74b5fd7.nq.gz
│   ├── 2608b45e307bbf1b09d51f02876cdf28362d830e.nq.gz
│   ├── 2617ee9520601f220e7ae55a48cf74fd1a844373.nq.gz
│   ├── 2760846382b940556c313412814572a8d79e82ff.nq.gz
│   ├── 2b18b119b97b776cb0d3803885989021fc1b8fdc.nq.gz
│   ├── 2c5a8e850d15379d9674ae0bd06b7c322327f8e4.nq.gz
│   ├── 2f9c77a5df4622b184e49a5c8f21ffaeff664764.nq.gz
│   ├── 2fad925c9158c1dca11f3572f96c3110db07e33a.nq.gz
│   ├── 34d8efcccdd516d36ea6764460e0c0eff4a46ff6.nq.gz
│   ├── 3822f261374c78c58e3005511e2dd98074456fa7.nq.gz
│   ├── 387c4d96f102ae223d1d9303c5566995927a0931.nq.gz
│   ├── 3b85f71d7e896de9b2f102b10dc1f76722146a63.nq.gz
│   ├── 3be1ec71ae090473844db74586313f585ca6c94a.nq.gz
│   ├── 40c3453fde13f99c06dd0361539b42da88be2871.nq.gz
│   ├── 4316c163791be054c6d28a08813e9b1df1c9e4e5.nq.gz
│   ├── 4595bac048869744864b9d054f6340b4d60da8ec.nq.gz
│   ├── 4cacbacf03cb49f61410482093783c084d2e0be7.nq.gz
│   ├── 4dbbb43d991052531c89db7227b326b053715ef9.nq.gz
│   ├── 4e0f39908f08ee2e02cc54ec875dfc026a3d3e45.nq.gz
│   ├── 4f85a35a000aad144f7532800800b4e6595efbbe.nq.gz
│   ├── 4fac8f74501b74bc8e57d0e8b91171a6a2f57351.nq.gz
│   ├── 50431ec93857b82503d65d345cc3612df7aa634f.nq.gz
│   ├── 509ae38cea52bb5ea6c14c71f34c2d23cc0441ab.nq.gz
│   ├── 5a1a308e8c05312af0ec6238484746cd139f76c9.nq.gz
│   ├── 5d56d228d7b48282f662d4c1e9ed2052aaf135da.nq.gz
│   ├── 5f9368096b34e210f2b7f27d7f862dc79f82345f.nq.gz
│   ├── 624f740736c766fbeb815bf2272c2d333672aa28.nq.gz
│   ├── 644a6626160956a0fe610d9e6064193c84202e52.nq.gz
│   ├── 6709ff4b2596cbb61986afcc17bd1f08cf81fec4.nq.gz
│   ├── 6a3f29529e2b24a51fadff804decc74e51ebf066.nq.gz
│   ├── 6a55eef03074dedb3732606622ea901afd72554e.nq.gz
│   ├── 6b233fcdec9eac4ea77f0ab18f9de87963859fae.nq.gz
│   ├── 6c127b534fff08951ada0097df5af6ea24fc33e0.nq.gz
│   ├── 6e801be4e581b870b79f509429d6d6c267dd193c.nq.gz
│   ├── 78faff7947d5f92ffeab3bd9b95a363416e56d5b.nq.gz
│   ├── 7a4623ef556dcdcc64961ef78d8fceb8ca29f263.nq.gz
│   ├── 7b6b4110ddf2421108327f0efd5f59e586eeacf8.nq.gz
│   ├── 7bd102c7492b256c65247f18992efc8568256c30.nq.gz
│   ├── 7bfcffe3789209bac77736880c3c8a6d0a5c4e3f.nq.gz
│   ├── 82089085277f8c597d05d9eef2f740a49f79c612.nq.gz
│   ├── 842237411b1655eff48e07fb314bed1c4e80a897.nq.gz
│   ├── 862be3f3d2820bbf0d166bc4d361a4064544a69e.nq.gz
│   ├── 8c0a6a4833c4b68f7da3f49ff3df3b9cf1f12861.nq.gz
│   ├── 8d174843c4f6205490c4fdba4cd7cf80c2c0b599.nq.gz
│   ├── 8d674ba240d9af5d4c63728367ba555816100c18.nq.gz
│   ├── 8feb3908fd3c12408179b33176c0bd442f511872.nq.gz
│   ├── 9d1fba021dc175175a766fcae5a936cfd694cf54.nq.gz
│   ├── a2f45bf2096ae0eb4e4423c31d6b322e4ef096a0.nq.gz
│   ├── a6735e5ce721322f1b0528ddffacd4c0333ec05a.nq.gz
│   ├── a6d9012c3f0b9b338ae422a00892b3894f81c498.nq.gz
│   ├── ae50247b5bf885cc775b65b169c7d4e04b25f6c1.nq.gz
│   ├── b32e9a07fdf8f83506629d2bd6c3e22ef728acfe.nq.gz
│   ├── b4dec44e1579f1f0574ea58fe7dd30321916b44a.nq.gz
│   ├── b5c79d63fe63b839c6f7d4147d800e87157c3bde.nq.gz
│   ├── bad3be6556fc5f12d847b934222d3a5530c3506c.nq.gz
│   ├── bde488ebce5ceb44af994c907a2c6fe086dcedfe.nq.gz
│   ├── c305f50130aef0175cf1327b9ecf11b684a0cbe7.nq.gz
│   ├── c339e59333e4c3b5bc5fd910796fda5469a2515f.nq.gz
│   ├── c4e2a5974d0ace6fd2539cd4715c7ad6ed98e4b9.nq.gz
│   ├── c5dcdb83323b031e97bef719211648c021916939.nq.gz
│   ├── c81d439f91044280c686b9b2fad7b68bf5d3e78c.nq.gz
│   ├── c88ecd50d485ff9c2fbff700d0853402941e3366.nq.gz
│   ├── c89b1d350dad9a473cd092c1afd712e4aab0238b.nq.gz
│   ├── cbe25248c5fed323b894d04322ac4829744013f4.nq.gz
│   ├── cedd4f782674ad42fe3cce8488af727ee41e8024.nq.gz
│   ├── d666d38fdac2d656911cfa17c2e0d6c82b601495.nq.gz
│   ├── d861b01606e87ed92143ceac901fb45507a2caff.nq.gz
│   ├── d94b97a8b790a4d7daa36c508a2c2139aecf11c2.nq.gz
│   ├── dbbe42bb65d4f82faf6c21eb4ccec1f68ff9816e.nq.gz
│   ├── e1af37b0652db849954b6422187e676fbadf6e85.nq.gz
│   ├── e644dc18a8232e80a97b15286464484e34799cac.nq.gz
│   ├── ea0ad0a776193f01c7f8ee57d6f4d00a69ead404.nq.gz
│   ├── f283872298c7b70845f4307a7d7d20026915119e.nq.gz
│   ├── f2a1f9d5f5345427bb0fc301472d4320919199ad.nq.gz
│   ├── f509ffed8a6085dc445451c4aff4328460277bae.nq.gz
│   ├── f5cf9bb0bcb37b546af542c8b57492cbdde16726.nq.gz
│   ├── f678fae325435f8ff8e0bc1eefb2f05b31ccae3c.nq.gz
│   ├── f7c265dc990aa263903b0ccde4af0acbf5012a96.nq.gz
│   ├── f864d5fd38b7466c76b5a36dc0e3e9455c0126e2.nq.gz
│   ├── f86ca6b7325ad2cf9fa808aa538e4b8f05349324.nq.gz
│   ├── f8a03972dfc82a60a4b0b47a049b789e2a32b5ee.nq.gz
│   ├── fb4b319329c84ad768257e6699edf49a2f4a884a.nq.gz
│   ├── fb5905c3d8738676b890d8938e4279c220358eb4.nq.gz
│   ├── fcabf21f43fdb2d8d89fbe25d464546b0b4fb44e.nq.gz
│   └── fcf1871943ee1b24d4c718183b6560fbf478fcb9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6d9d5697162c3543dc55009074695f9997a8471b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[pydata/patsy](https://github.com/pydata/patsy)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

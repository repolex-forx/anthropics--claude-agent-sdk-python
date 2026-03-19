# Repolex Knowledge Graph of anthropics/claude-agent-sdk-python

RDF knowledge graph data for [anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download anthropics/claude-agent-sdk-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   └── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   ├── lsp
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   └── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   └── repolex
│       ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│       └── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
├── blob
│   ├── 03710748e1efccfe820e7124bc57910e4220cb8e.nq.gz
│   ├── 0566ff7c4ab2fb4d162241a74cd768959524062b.nq.gz
│   ├── 0eb4354236d7b843b60027af331b1e89a6d87f35.nq.gz
│   ├── 10f02cbe3a673c55e3d777989e9aa2ee61c42309.nq.gz
│   ├── 12e8b335fc4c44759aee0aa9a72760911225b4ed.nq.gz
│   ├── 15d60bab922ca49babae4d0c0708edad4dc2e404.nq.gz
│   ├── 18503dd8474747d0fdca1ecc72aed5c1ab016501.nq.gz
│   ├── 189cdefb66cc6f679d6a98df186956e02d9f573c.nq.gz
│   ├── 1ad4767267b67e28d539a03899289c23b0d7119d.nq.gz
│   ├── 1eee01d4c8d5a429b682b8b5567b7fdfe17811f5.nq.gz
│   ├── 1ef17c7ee7a48c667a94f9fb4c3bbdd75cedcced.nq.gz
│   ├── 204676f9cd0b8cbda4c0969b242f297dfaeb1a70.nq.gz
│   ├── 22adf2eca4956b5e848f8f7b261fe324a576d44b.nq.gz
│   ├── 24c9745a1c60898fd11974f1b62c8ed4bab1b571.nq.gz
│   ├── 25a0a69ea5e6791a42e363f622a1931ba28f37b0.nq.gz
│   ├── 2bc0620a2f37bc0d87a1b6ef0ce6be82367aca0e.nq.gz
│   ├── 2cf9889c527aa069378314b6f59fb4ea684192b7.nq.gz
│   ├── 31bebd09faa70f9403de7b91f49b20f7af62f209.nq.gz
│   ├── 31ef0790b704d5197843d54bdf3efcd112c54137.nq.gz
│   ├── 3282ea1a8ab248f44277aa10e0c8f76a069cad10.nq.gz
│   ├── 33ef1223fb137a50c7bd040df8eda9c55a74e2c9.nq.gz
│   ├── 34b70342d54fd82883577c3cc0db746503bff31d.nq.gz
│   ├── 35553511d44c4e16df0ea32c78e703aecdbd437b.nq.gz
│   ├── 37476923a6939111fa92c67e2d43858993f76643.nq.gz
│   ├── 37d93b04362bc5776afaf50a1b0be639f9abc43e.nq.gz
│   ├── 38dc05f4b92654205a4d6aafa6008d5a01f06613.nq.gz
│   ├── 39cb7755ac4e73737e81ce8de019f470895fa0a4.nq.gz
│   ├── 3a672794cacb835d50b1a585094b68bb9df87dee.nq.gz
│   ├── 3f128552738f3bee42ed1d25495c542dc2b74551.nq.gz
│   ├── 3fa6a64e52f30d3ad836f98b3f0da6f4b6263bb8.nq.gz
│   ├── 426d42e5745fcde2176ed768926f010cc61935bd.nq.gz
│   ├── 43dcf017f942f40c26b9c95f1f7e7d3f24609d3d.nq.gz
│   ├── 45d39dfcd2062bf09fb198f4a69db95f87ca6b78.nq.gz
│   ├── 45fdf805e1c39a250f3af4209b02b1bb5a0b8bbb.nq.gz
│   ├── 509b766e7f6c6721ed27f32e357ad95d5757d5f2.nq.gz
│   ├── 5274b20e3bb1a1684293c6482292fb8e086c03b0.nq.gz
│   ├── 5b434546dbeb367b5725514c577712317c891095.nq.gz
│   ├── 5bd9f6dfd2a5b2829dfda56a2b472c42432e0568.nq.gz
│   ├── 5be2ac192a8b9b7566b3968e8ea16f535f4ca6ca.nq.gz
│   ├── 5c5999d13a046749e9bcae13b4f8aa617da030d7.nq.gz
│   ├── 60462923537d638aa7d847c07a79435c305e1b93.nq.gz
│   ├── 62791d73fc0c58a261398ff55b2f3fdef52badfb.nq.gz
│   ├── 634c48634c266f9e8a8f8b3b7feceda87948697e.nq.gz
│   ├── 6423e91aa46d5af8ceaf1d7453b60bdce263883b.nq.gz
│   ├── 65158272293e89d87f472cad9f989c3ffae161d3.nq.gz
│   ├── 675dd939c3fb327f8eb2ab73d4d56e01ed0f0daa.nq.gz
│   ├── 67f9e66eae797299bbbe190cee2ef281985048f4.nq.gz
│   ├── 6be5cc43a81542686ff58926eb61f4b58fb487cb.nq.gz
│   ├── 6dedef618013f925be512ef22062a886b520b3c0.nq.gz
│   ├── 6dfe374ed048dc7d4f76b890e5ebf818a81e45f6.nq.gz
│   ├── 709625a89f0ffa296eb0030db6b8dd368b85dd6f.nq.gz
│   ├── 715dab5e96103694583429571acb24e1e411678c.nq.gz
│   ├── 7265afa471409345c26c5fe2518b8442b99dc963.nq.gz
│   ├── 73eb410973c828ce8dbdd2cc69a0d4fecb5676de.nq.gz
│   ├── 763a7739a513068bfe271169e585f28e38bf9159.nq.gz
│   ├── 7821be4edf34c3b0a749617d243381d3ba4bd29b.nq.gz
│   ├── 790c9249b05e436fced784dd616780e260c47f77.nq.gz
│   ├── 7f7c9ea85005ce3a2e75ba54b8555dae9511cd7a.nq.gz
│   ├── 82c324b5c79fb528939045929dee568f414cd6fb.nq.gz
│   ├── 858e24fa63dde0ca1c2b3793bfdcbf26124dc492.nq.gz
│   ├── 884d7c4e782d8052224859b1b3c009f9c73041f8.nq.gz
│   ├── 8b9c4c2160d7b59edc38c8b3df71070a5792b64f.nq.gz
│   ├── 8d5499121a3bc5010dbf1fa0b061d77454fb0b0d.nq.gz
│   ├── 8e2fb3c41aecd248cea7f54aeb3073b596dbce17.nq.gz
│   ├── 8e86ba7c0d4027ecf88efbc30fd75e76680db61c.nq.gz
│   ├── 8f085a067163bd67d800f43677bf1d129cc9fd92.nq.gz
│   ├── 92c9c6fbd113ca3e12897f337bc365c94e1bb56e.nq.gz
│   ├── 9490d075b949a047edb5df99cbed56bffacbf147.nq.gz
│   ├── 98ed0c1c4e671363503140652fac66ddf347364a.nq.gz
│   ├── 9b5edb44f15f93415faa29f1ab2ad9e18fb83c2d.nq.gz
│   ├── 9d92a81779a6263acb3d1a75d3ff0eadc1d8fcae.nq.gz
│   ├── 9e7439ee18dcef4abda3047d4868642a43d6d80b.nq.gz
│   ├── a0b37d6321f5b37eacafc6ca46bfd09a490ecc94.nq.gz
│   ├── a185335f49be18d5bd59b9d58ced552fadf21f6c.nq.gz
│   ├── a2b31930941581eee4298a85c275c2b4a15a4645.nq.gz
│   ├── a33038eff9c4f98186e647070d41806a4474d1b5.nq.gz
│   ├── a49d2c63ce5f02e59116e924000a5a27a1c2821a.nq.gz
│   ├── a5247fa3d673fb7d95b23d28ae4393c97b8875c5.nq.gz
│   ├── a8001d4dbecfed3778b9b0d8c87a07679fdf596d.nq.gz
│   ├── aa63994c22e26c47a03f9575c5949ec6180ff01f.nq.gz
│   ├── aa9e432883e52637fbcf0f740086361bda808ced.nq.gz
│   ├── ac179f89932860f0d63e73963bbe4565c833b0e0.nq.gz
│   ├── ad77a1b112fe860e5dbecf8d20d92577d80205d0.nq.gz
│   ├── b304caa87cd9ecdbb3ed860e1e5c6962c57b9ce5.nq.gz
│   ├── b80bb3f256ac1967aaa0c027bb756a59f01d7d3f.nq.gz
│   ├── b8f035402f0081454067f025d27639a1518b7f88.nq.gz
│   ├── b980d5224df55074fae9be8fb5f2f04ebc47ffbf.nq.gz
│   ├── bb9777e8e887c3b4e5c90155883a369b8d6b9b8c.nq.gz
│   ├── bd3c7267fa942eab3786a657d95a880de43437db.nq.gz
│   ├── bd7512e0937c8c95a8a75ac07ab3ce1fdc1d79ba.nq.gz
│   ├── be0f219c9dda1a532a157eca2f26b6847f6693fb.nq.gz
│   ├── bfe632e56a9ec01b9d67eb0ab8eafdd61f9b984d.nq.gz
│   ├── c0a2d5413d91b622a03b8b66577a7661118a190a.nq.gz
│   ├── c31a9a2ab83418d44bdd337a6d0d8b57ceab7160.nq.gz
│   ├── c4d7c89f0cd9d210237bed839c210005b2118386.nq.gz
│   ├── c50630d64491dc8c08fe580320a0439a68369bcf.nq.gz
│   ├── c67e03234b8689c8b2ff25698b6c4bfa6fd6f847.nq.gz
│   ├── c86bf235cee20636dfe8993d67c332ce6e524b72.nq.gz
│   ├── c91c98c4085e7e8b82e95492b7acf2bb9a44da7a.nq.gz
│   ├── c949ad364480369b2063a49f407e025450085f8b.nq.gz
│   ├── cad31a12b1b81ddd66f48aabc2c6921d3566bec8.nq.gz
│   ├── cd7188c393395aa8fcc9e57d18b5a975d4b827c1.nq.gz
│   ├── d013f1bc257156b52346240b5525e74ba9c7e28c.nq.gz
│   ├── d5bdc4d080f993666f5164bd512955ccd315124b.nq.gz
│   ├── de6ff607ee38d940e7e1191cf224ace0e1046f6a.nq.gz
│   ├── e5f6904a6cde702b06b92672d3180ba65e2878b4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7b56e10e769164d2b047a8e14da559f4bab44b9.nq.gz
│   ├── ea419acbecc9b53a03b3c52547be77d4a06e724c.nq.gz
│   ├── ec6799af17d29fcb2f08b667fd1e84ad48402dd4.nq.gz
│   ├── edeb01f285e0276e249ba8da8581c633f4fb411d.nq.gz
│   ├── f009b614d3a0c2b35c828e32a358d6905287f583.nq.gz
│   ├── f0971067c681184bde1cd5ebb1c48f483143150c.nq.gz
│   ├── f12ffb68d0cd035c6da2f23323f096f1d3951432.nq.gz
│   ├── f1ce7909794ede3e515acb701806682c74876aa0.nq.gz
│   ├── f2b300aba939b7e5edd8dde49352c15a85731aff.nq.gz
│   ├── f6f187f98cc24cb2f1c2065469b96b711840cd04.nq.gz
│   ├── fb9ed47372fb9ec026be6b65693a9d58c4af487b.nq.gz
│   ├── fc7b6754da8fc14a0db7bab52f2d37bfb240ecdc.nq.gz
│   └── fd919247134ef2cba499e3d9a3f815690aa9b079.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   └── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
├── filetree
│   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   └── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 135 files
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

## Source repository

[anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*

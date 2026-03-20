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
│   │   ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│   │   ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│   │   ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│   │   ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│   │   ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│   │   ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   │   ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│   │   └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
│   ├── lsp
│   │   ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│   │   ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│   │   ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│   │   ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│   │   ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│   │   ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   │   ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│   │   └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
│   └── repolex
│       ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│       ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│       ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│       ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│       ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│       ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│       ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│       ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│       ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│       └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
└── blob
    ├── 03710748e1efccfe820e7124bc57910e4220cb8e.nq.gz
    ├── 03971eb2b84c4c2f96f6c5e1d52978af91ac0e7c.nq.gz
    ├── 03a5c38a462b07f42bfca5ec8824c3c2ad268aa1.nq.gz
    ├── 044502a2d4b029ebbc2b89c989624c3df79a2aaa.nq.gz
    ├── 05584e18034f4cac654b1e3ef1b6ac72e6892c56.nq.gz
    ├── 0566ff7c4ab2fb4d162241a74cd768959524062b.nq.gz
    ├── 0967e8a07ddfbcbcfaa70ef7daa4585adbc99447.nq.gz
    ├── 0eb4354236d7b843b60027af331b1e89a6d87f35.nq.gz
    ├── 10f02cbe3a673c55e3d777989e9aa2ee61c42309.nq.gz
    ├── 11c3a48e15be31a858a1ad09d0fa8842ac8d747f.nq.gz
    ├── 12e8b335fc4c44759aee0aa9a72760911225b4ed.nq.gz
    ├── 15d60bab922ca49babae4d0c0708edad4dc2e404.nq.gz
    ├── 18503dd8474747d0fdca1ecc72aed5c1ab016501.nq.gz
    ├── 189cdefb66cc6f679d6a98df186956e02d9f573c.nq.gz
    ├── 1ad4767267b67e28d539a03899289c23b0d7119d.nq.gz
    ├── 1d05eb0c52e227fd44a1c2c8224057e7c2ca1507.nq.gz
    ├── 1eee01d4c8d5a429b682b8b5567b7fdfe17811f5.nq.gz
    ├── 1ef17c7ee7a48c667a94f9fb4c3bbdd75cedcced.nq.gz
    ├── 204676f9cd0b8cbda4c0969b242f297dfaeb1a70.nq.gz
    ├── 214b953b0ed4cba6053323f57ff0e42dc49feb00.nq.gz
    ├── 22adf2eca4956b5e848f8f7b261fe324a576d44b.nq.gz
    ├── 24c9745a1c60898fd11974f1b62c8ed4bab1b571.nq.gz
    ├── 25a0a69ea5e6791a42e363f622a1931ba28f37b0.nq.gz
    ├── 27b90312b101f01e7f87fe56a47348049c7aba83.nq.gz
    ├── 29bb95008025188958832095bcb6242a76c4d133.nq.gz
    ├── 29eb57b0684790540cafa7c183bc0668b9d31a6e.nq.gz
    ├── 2bc0620a2f37bc0d87a1b6ef0ce6be82367aca0e.nq.gz
    ├── 2cf9889c527aa069378314b6f59fb4ea684192b7.nq.gz
    ├── 2e577f470a76892e3b6505883237f908298b0d42.nq.gz
    ├── 31bebd09faa70f9403de7b91f49b20f7af62f209.nq.gz
    ├── 31ef0790b704d5197843d54bdf3efcd112c54137.nq.gz
    ├── 3282ea1a8ab248f44277aa10e0c8f76a069cad10.nq.gz
    ├── 333b4887c14c2cbd42710ecf8f08ab67b76fef64.nq.gz
    ├── 33ef1223fb137a50c7bd040df8eda9c55a74e2c9.nq.gz
    ├── 34b70342d54fd82883577c3cc0db746503bff31d.nq.gz
    ├── 35553511d44c4e16df0ea32c78e703aecdbd437b.nq.gz
    ├── 357658d2167d6adebb3b1c2b27b964d48b72270c.nq.gz
    ├── 37476923a6939111fa92c67e2d43858993f76643.nq.gz
    ├── 37d93b04362bc5776afaf50a1b0be639f9abc43e.nq.gz
    ├── 38dc05f4b92654205a4d6aafa6008d5a01f06613.nq.gz
    ├── 392c213ac3dab53b364f8557f7b704e38e201c66.nq.gz
    ├── 39cb7755ac4e73737e81ce8de019f470895fa0a4.nq.gz
    ├── 3a672794cacb835d50b1a585094b68bb9df87dee.nq.gz
    ├── 3b95a4083851b36ff55f2b4faec9aecbc44b2388.nq.gz
    ├── 3dcfec25c1940ed106ea8b5d3ec88b6d3555d9a7.nq.gz
    ├── 3e14fbf7bdfa3cd79435cc41d099a417e0f7224b.nq.gz
    ├── 3f128552738f3bee42ed1d25495c542dc2b74551.nq.gz
    ├── 3f557b39cd046d3dd3ccf97c81c9c2dcef91bca0.nq.gz
    ├── 3fa6a64e52f30d3ad836f98b3f0da6f4b6263bb8.nq.gz
    ├── 426d42e5745fcde2176ed768926f010cc61935bd.nq.gz
    ├── 42aea656574dba4eaadbca1ab2c58cc773e1cdfb.nq.gz
    ├── 42d782d29f953d2549e128824c47f1da59148729.nq.gz
    ├── 43dcf017f942f40c26b9c95f1f7e7d3f24609d3d.nq.gz
    ├── 453b6d41774445f9b842ddb6eeca3c4b01b40a6f.nq.gz
    ├── 45d39dfcd2062bf09fb198f4a69db95f87ca6b78.nq.gz
    ├── 45fdf805e1c39a250f3af4209b02b1bb5a0b8bbb.nq.gz
    ├── 4802e9ad819dfe58904d0b755dec83bdcb740a3d.nq.gz
    ├── 49cae537e5f257f8539bb4d13bfac83994b77763.nq.gz
    ├── 4a1d54a306c00d25cf42dc8ead5a505a54fd41a5.nq.gz
    ├── 4cb841b7ef9447ac94515b783078517d57686ce8.nq.gz
    ├── 4e0892ee7c78c16514f618f4e10581b55eb91fba.nq.gz
    ├── 4f52a91bb04e4455d73469ee997ae35324cb7927.nq.gz
    ├── 50366f7fa7a49e699b40af595750721d79cd1730.nq.gz
    ├── 509b766e7f6c6721ed27f32e357ad95d5757d5f2.nq.gz
    ├── 50e093c1a991bf8e1e604aa953b2973e1bea7531.nq.gz
    ├── 51c7511f0fa9910e4509e98efbd04c1192117991.nq.gz
    ├── 5274b20e3bb1a1684293c6482292fb8e086c03b0.nq.gz
    ├── 56a2de9a24be2ef8e8016485bfa3d3234c907e93.nq.gz
    ├── 5796de3aff7f41fa300358b2dd7740080bf622ef.nq.gz
    ├── 58258222efa3ec6f9d812d424bc91a3cdf54b966.nq.gz
    ├── 58e58515d392ba061a33a6acea32d846f2bf0fe0.nq.gz
    ├── 5b434546dbeb367b5725514c577712317c891095.nq.gz
    ├── 5bc5d7aad3e710dc06d740ce1f6153acc14584cc.nq.gz
    ├── 5bd9f6dfd2a5b2829dfda56a2b472c42432e0568.nq.gz
    ├── 5be2ac192a8b9b7566b3968e8ea16f535f4ca6ca.nq.gz
    ├── 5c5999d13a046749e9bcae13b4f8aa617da030d7.nq.gz
    ├── 60462923537d638aa7d847c07a79435c305e1b93.nq.gz
    ├── 60dea982fec8134a01333e9ffb3cfb16342a692c.nq.gz
    ├── 62791d73fc0c58a261398ff55b2f3fdef52badfb.nq.gz
    ├── 634c48634c266f9e8a8f8b3b7feceda87948697e.nq.gz
    ├── 6423e91aa46d5af8ceaf1d7453b60bdce263883b.nq.gz
    ├── 65158272293e89d87f472cad9f989c3ffae161d3.nq.gz
    ├── 6532a2040371be1086343dfcbc8a63b02fd741b1.nq.gz
    ├── 65fe9c6fcf94d59e4573e51e4bf6198564a42673.nq.gz
    ├── 66fb6ebd294500e751720fdceb32d3ae6a64d6f6.nq.gz
    ├── 675dd939c3fb327f8eb2ab73d4d56e01ed0f0daa.nq.gz
    ├── 67f9e66eae797299bbbe190cee2ef281985048f4.nq.gz
    ├── 68f2e49f842438d2a71a93667d2ca680eb76b7c4.nq.gz
    ├── 6ab1363dd0048474cd5adc02b7d6f7e3fef7091b.nq.gz
    ├── 6b39a02501ec471828389cea3231a9a3488abdfd.nq.gz
    ├── 6be5cc43a81542686ff58926eb61f4b58fb487cb.nq.gz
    ├── 6bfc8452867d261bddaa44199a59b90d7aaf15a9.nq.gz
    ├── 6dedef618013f925be512ef22062a886b520b3c0.nq.gz
    ├── 6dfe374ed048dc7d4f76b890e5ebf818a81e45f6.nq.gz
    ├── 709625a89f0ffa296eb0030db6b8dd368b85dd6f.nq.gz
    ├── 715dab5e96103694583429571acb24e1e411678c.nq.gz
    ├── 71736502eaaec91910424c7d5c6fa1ad0fe8c225.nq.gz
    ├── 7265afa471409345c26c5fe2518b8442b99dc963.nq.gz
    ├── 73eb410973c828ce8dbdd2cc69a0d4fecb5676de.nq.gz
    ├── 763a7739a513068bfe271169e585f28e38bf9159.nq.gz
    ├── 769de13ba3e7c07ea490eaad1f219ded57122ebb.nq.gz
    ├── 7821be4edf34c3b0a749617d243381d3ba4bd29b.nq.gz
    ├── 78ebad8d641499b077506a73972ff87ed5dc0559.nq.gz
    ├── 790c9249b05e436fced784dd616780e260c47f77.nq.gz
    ├── 7b0b928312a595c58d8cf9971ef5aae53532a7eb.nq.gz
    ├── 7e6d2df1702ef4f643d6cb147b71f7d9deec61a0.nq.gz
    ├── 7f7c9ea85005ce3a2e75ba54b8555dae9511cd7a.nq.gz
    ├── 81560100c213224545c674c4c4067d5e2b4b4604.nq.gz
    ├── 81df3cd58c97ee3dedb3e935aae3456628d3d84b.nq.gz
    ├── 821ff967f64e5269dffb1e170d4c9d7e9a6fd1f1.nq.gz
    ├── 82c324b5c79fb528939045929dee568f414cd6fb.nq.gz
    ├── 8477e51a839e6c819068e68d0737c7d2e0404be3.nq.gz
    ├── 858e24fa63dde0ca1c2b3793bfdcbf26124dc492.nq.gz
    ├── 884d7c4e782d8052224859b1b3c009f9c73041f8.nq.gz
    ├── 8ac162e2e832d0459be3b6421572939025e9f602.nq.gz
    ├── 8b9c4c2160d7b59edc38c8b3df71070a5792b64f.nq.gz
    ├── 8d5499121a3bc5010dbf1fa0b061d77454fb0b0d.nq.gz
    ├── 8e2fb3c41aecd248cea7f54aeb3073b596dbce17.nq.gz
    ├── 8e86ba7c0d4027ecf88efbc30fd75e76680db61c.nq.gz
    ├── 8e990b1e211939832126f81f6d9c3c3578a2698c.nq.gz
    ├── 8efd879aec9bd6f849d18fe18abf42740f1f092b.nq.gz
    ├── 8f085a067163bd67d800f43677bf1d129cc9fd92.nq.gz
    ├── 92c9c6fbd113ca3e12897f337bc365c94e1bb56e.nq.gz
    ├── 9490d075b949a047edb5df99cbed56bffacbf147.nq.gz
    ├── 98afdef8f7e4cb55409d1f0fac6a489002eb4261.nq.gz
    ├── 98ed0c1c4e671363503140652fac66ddf347364a.nq.gz
    ├── 9a3e24a203e679f97af6a2bce0952d63eeb6cb76.nq.gz
    ├── 9b1a087a80437767b3cbe87b0dbb435d49a38b55.nq.gz
    ├── 9b5edb44f15f93415faa29f1ab2ad9e18fb83c2d.nq.gz
    ├── 9d92a81779a6263acb3d1a75d3ff0eadc1d8fcae.nq.gz
    ├── 9e7439ee18dcef4abda3047d4868642a43d6d80b.nq.gz
    ├── a0b37d6321f5b37eacafc6ca46bfd09a490ecc94.nq.gz
    ├── a185335f49be18d5bd59b9d58ced552fadf21f6c.nq.gz
    ├── a2b31930941581eee4298a85c275c2b4a15a4645.nq.gz
    ├── a33038eff9c4f98186e647070d41806a4474d1b5.nq.gz
    ├── a49d2c63ce5f02e59116e924000a5a27a1c2821a.nq.gz
    ├── a4f7181b685e56b0f77732b054df262dc9d3ea2e.nq.gz
    ├── a5247fa3d673fb7d95b23d28ae4393c97b8875c5.nq.gz
    ├── a5d8fbb248bf69c9c680406128aa12a2fa4b527c.nq.gz
    ├── a72323eb5365707ff299657f17db26daa7f156f5.nq.gz
    ├── a8001d4dbecfed3778b9b0d8c87a07679fdf596d.nq.gz
    ├── a9c2bb3c0d00a20467f38e6b2695e277db652bd4.nq.gz
    ├── aa63994c22e26c47a03f9575c5949ec6180ff01f.nq.gz
    ├── aa6d12e53bcfb82284c19d49d521809815d3fb0b.nq.gz
    ├── aa9e432883e52637fbcf0f740086361bda808ced.nq.gz
    ├── aae45bbfd3feef34fb0de4387f604d7896c2827d.nq.gz
    ├── ab8620cfe5a92578b3f294a997e735524b097388.nq.gz
    ├── ac179f89932860f0d63e73963bbe4565c833b0e0.nq.gz
    ├── ad77a1b112fe860e5dbecf8d20d92577d80205d0.nq.gz
    ├── b2d5ac2a1ca59c752c542c4c21bad3682f57acf2.nq.gz
    ├── b304caa87cd9ecdbb3ed860e1e5c6962c57b9ce5.nq.gz
    ├── b394833be6217cf5f3db1345b1aade2161a3e22d.nq.gz
    ├── b64753014254459bec820df56d4f4e867f1f3f27.nq.gz
    ├── b80bb3f256ac1967aaa0c027bb756a59f01d7d3f.nq.gz
    ├── b8f035402f0081454067f025d27639a1518b7f88.nq.gz
    ├── b980d5224df55074fae9be8fb5f2f04ebc47ffbf.nq.gz
    ├── bb9777e8e887c3b4e5c90155883a369b8d6b9b8c.nq.gz
    ├── bd3c7267fa942eab3786a657d95a880de43437db.nq.gz
    ├── bd7512e0937c8c95a8a75ac07ab3ce1fdc1d79ba.nq.gz
    ├── be0f219c9dda1a532a157eca2f26b6847f6693fb.nq.gz
    ├── bfe632e56a9ec01b9d67eb0ab8eafdd61f9b984d.nq.gz
    ├── c0a2d5413d91b622a03b8b66577a7661118a190a.nq.gz
    ├── c31a9a2ab83418d44bdd337a6d0d8b57ceab7160.nq.gz
    ├── c3e4feb4f1c78d4876962c4aafff9481090df21d.nq.gz
    ├── c4d7c89f0cd9d210237bed839c210005b2118386.nq.gz
    ├── c50630d64491dc8c08fe580320a0439a68369bcf.nq.gz
    ├── c61794e89136a1d3110fa4bf4e9b46717e35a242.nq.gz
    ├── c67e03234b8689c8b2ff25698b6c4bfa6fd6f847.nq.gz
    ├── c86bf235cee20636dfe8993d67c332ce6e524b72.nq.gz
    └── c91c98c4085e7e8b82e95492b7acf2bb9a44da7a.nq.gz

6 directories, 200 files
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
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*

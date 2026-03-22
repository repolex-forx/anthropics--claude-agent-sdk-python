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
│   │   ├── 00332f32dcb5121d063729293263a09f92240f82.nq.gz
│   │   ├── 04da88de3d8efa978c783e90e655dd5af0e070f4.nq.gz
│   │   ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│   │   ├── 0e9397e052ec5cb59a54b99c596df8d5656f2ccb.nq.gz
│   │   ├── 161c3bf37cc05ea90ebe1c4c86f3c2f77986912a.nq.gz
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│   │   ├── 29c12cd80b256e88f321b2b8f1f5a88445077aa5.nq.gz
│   │   ├── 2b367897a11247d26f90227d73aab93f002ad593.nq.gz
│   │   ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│   │   ├── 31899e9c806b2a23f3618a37f675bf428d47c0b2.nq.gz
│   │   ├── 333491eef58626a697fb961f0c77749f629be39c.nq.gz
│   │   ├── 389d54f8442217652609a66f8f9c7cbe9f15aa02.nq.gz
│   │   ├── 438ddf7e1bd2723ecf5f6bd705435fc1a78b81db.nq.gz
│   │   ├── 4703cae708b2cd1d0c14857240140a409091c05c.nq.gz
│   │   ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│   │   ├── 4b196427256f5a9518961efb850f6aa1e71d0e2a.nq.gz
│   │   ├── 4d747482377cbe681c56adc39849357e8eee5e65.nq.gz
│   │   ├── 597c758f98c9067ccf785f9d1f2b139925f7bb20.nq.gz
│   │   ├── 5b912962e200fbd37b8c872b443c57abfb05085d.nq.gz
│   │   ├── 5f0dcbd621bc1d7d53a55acea4867d2f63369aee.nq.gz
│   │   ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│   │   ├── 67e77e928aab66ddab05d22a59eff9379f2e1db5.nq.gz
│   │   ├── 7519c9642ce38eb779d5623153c0e3188a5edf8a.nq.gz
│   │   ├── 7b2f0067b3ec520bd642fae8caadb1010102bfd1.nq.gz
│   │   ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│   │   ├── 97de454ab6641478354cf8c34fae49bfec97ef31.nq.gz
│   │   ├── 9809fb6b5404ca60d70d4cddc18c0ff195095285.nq.gz
│   │   ├── 9d4659c97f4cf1029ebc109e1a7097cb079e85ad.nq.gz
│   │   ├── a1c338726f25f887cfed2e45eea7bd5049ea9cbf.nq.gz
│   │   ├── a969042cf90141c67c08a9c95a49d5c2c3ec4cc6.nq.gz
│   │   ├── b5447d999df597d52bd3153372a50d391faa18d1.nq.gz
│   │   ├── b82f9b9bf5ee729a058f52e834722f49da7292dd.nq.gz
│   │   ├── cf6b85fc5d913deaf1453d6c075ec8b5194b6adc.nq.gz
│   │   ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   │   ├── e2f8d814ea1bbd44804cae329c0dd5a90f357df6.nq.gz
│   │   ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│   │   ├── eba5675328703d47aa6210d6341a2fff9b06c43b.nq.gz
│   │   ├── ef4149d1c9dbed4bf5c329f500a866a61e9407c7.nq.gz
│   │   └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
│   ├── lsp
│   │   ├── 00332f32dcb5121d063729293263a09f92240f82.nq.gz
│   │   ├── 04da88de3d8efa978c783e90e655dd5af0e070f4.nq.gz
│   │   ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│   │   ├── 0e9397e052ec5cb59a54b99c596df8d5656f2ccb.nq.gz
│   │   ├── 161c3bf37cc05ea90ebe1c4c86f3c2f77986912a.nq.gz
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│   │   ├── 29c12cd80b256e88f321b2b8f1f5a88445077aa5.nq.gz
│   │   ├── 2b367897a11247d26f90227d73aab93f002ad593.nq.gz
│   │   ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│   │   ├── 31899e9c806b2a23f3618a37f675bf428d47c0b2.nq.gz
│   │   ├── 333491eef58626a697fb961f0c77749f629be39c.nq.gz
│   │   ├── 389d54f8442217652609a66f8f9c7cbe9f15aa02.nq.gz
│   │   ├── 438ddf7e1bd2723ecf5f6bd705435fc1a78b81db.nq.gz
│   │   ├── 4703cae708b2cd1d0c14857240140a409091c05c.nq.gz
│   │   ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│   │   ├── 4b196427256f5a9518961efb850f6aa1e71d0e2a.nq.gz
│   │   ├── 4d747482377cbe681c56adc39849357e8eee5e65.nq.gz
│   │   ├── 597c758f98c9067ccf785f9d1f2b139925f7bb20.nq.gz
│   │   ├── 5b912962e200fbd37b8c872b443c57abfb05085d.nq.gz
│   │   ├── 5f0dcbd621bc1d7d53a55acea4867d2f63369aee.nq.gz
│   │   ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│   │   ├── 67e77e928aab66ddab05d22a59eff9379f2e1db5.nq.gz
│   │   ├── 7519c9642ce38eb779d5623153c0e3188a5edf8a.nq.gz
│   │   ├── 7b2f0067b3ec520bd642fae8caadb1010102bfd1.nq.gz
│   │   ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│   │   ├── 97de454ab6641478354cf8c34fae49bfec97ef31.nq.gz
│   │   ├── 9809fb6b5404ca60d70d4cddc18c0ff195095285.nq.gz
│   │   ├── 9d4659c97f4cf1029ebc109e1a7097cb079e85ad.nq.gz
│   │   ├── a1c338726f25f887cfed2e45eea7bd5049ea9cbf.nq.gz
│   │   ├── a969042cf90141c67c08a9c95a49d5c2c3ec4cc6.nq.gz
│   │   ├── b5447d999df597d52bd3153372a50d391faa18d1.nq.gz
│   │   ├── b82f9b9bf5ee729a058f52e834722f49da7292dd.nq.gz
│   │   ├── cf6b85fc5d913deaf1453d6c075ec8b5194b6adc.nq.gz
│   │   ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   │   ├── e2f8d814ea1bbd44804cae329c0dd5a90f357df6.nq.gz
│   │   ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│   │   ├── eba5675328703d47aa6210d6341a2fff9b06c43b.nq.gz
│   │   ├── ef4149d1c9dbed4bf5c329f500a866a61e9407c7.nq.gz
│   │   └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
│   └── repolex
│       ├── 00332f32dcb5121d063729293263a09f92240f82.nq.gz
│       ├── 04da88de3d8efa978c783e90e655dd5af0e070f4.nq.gz
│       ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│       ├── 0e9397e052ec5cb59a54b99c596df8d5656f2ccb.nq.gz
│       ├── 161c3bf37cc05ea90ebe1c4c86f3c2f77986912a.nq.gz
│       ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│       ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│       ├── 29c12cd80b256e88f321b2b8f1f5a88445077aa5.nq.gz
│       ├── 2b367897a11247d26f90227d73aab93f002ad593.nq.gz
│       ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│       ├── 31899e9c806b2a23f3618a37f675bf428d47c0b2.nq.gz
│       ├── 333491eef58626a697fb961f0c77749f629be39c.nq.gz
│       ├── 389d54f8442217652609a66f8f9c7cbe9f15aa02.nq.gz
│       ├── 438ddf7e1bd2723ecf5f6bd705435fc1a78b81db.nq.gz
│       ├── 4703cae708b2cd1d0c14857240140a409091c05c.nq.gz
│       ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│       ├── 4b196427256f5a9518961efb850f6aa1e71d0e2a.nq.gz
│       ├── 4d747482377cbe681c56adc39849357e8eee5e65.nq.gz
│       ├── 597c758f98c9067ccf785f9d1f2b139925f7bb20.nq.gz
│       ├── 5b912962e200fbd37b8c872b443c57abfb05085d.nq.gz
│       ├── 5f0dcbd621bc1d7d53a55acea4867d2f63369aee.nq.gz
│       ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│       ├── 67e77e928aab66ddab05d22a59eff9379f2e1db5.nq.gz
│       ├── 7519c9642ce38eb779d5623153c0e3188a5edf8a.nq.gz
│       ├── 7b2f0067b3ec520bd642fae8caadb1010102bfd1.nq.gz
│       ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│       ├── 97de454ab6641478354cf8c34fae49bfec97ef31.nq.gz
│       ├── 9809fb6b5404ca60d70d4cddc18c0ff195095285.nq.gz
│       ├── 9d4659c97f4cf1029ebc109e1a7097cb079e85ad.nq.gz
│       ├── a1c338726f25f887cfed2e45eea7bd5049ea9cbf.nq.gz
│       ├── a969042cf90141c67c08a9c95a49d5c2c3ec4cc6.nq.gz
│       ├── b5447d999df597d52bd3153372a50d391faa18d1.nq.gz
│       ├── b82f9b9bf5ee729a058f52e834722f49da7292dd.nq.gz
│       ├── cf6b85fc5d913deaf1453d6c075ec8b5194b6adc.nq.gz
│       ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│       ├── e2f8d814ea1bbd44804cae329c0dd5a90f357df6.nq.gz
│       ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│       ├── eba5675328703d47aa6210d6341a2fff9b06c43b.nq.gz
│       ├── ef4149d1c9dbed4bf5c329f500a866a61e9407c7.nq.gz
│       └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
└── blob
    ├── 01f5a5760cdf88ff1cd2cc8c63e645fbc7887edf.nq.gz
    ├── 01fa8007d1896e7d532d40a0894bf4d48f91cca1.nq.gz
    ├── 0335a9f3cd9a3b8bf346d4f925839d189a4a03ba.nq.gz
    ├── 03710748e1efccfe820e7124bc57910e4220cb8e.nq.gz
    ├── 03971eb2b84c4c2f96f6c5e1d52978af91ac0e7c.nq.gz
    ├── 03a5c38a462b07f42bfca5ec8824c3c2ad268aa1.nq.gz
    ├── 044502a2d4b029ebbc2b89c989624c3df79a2aaa.nq.gz
    ├── 0546b3ef00b9ecd0707d1eb8e0977eee297a456d.nq.gz
    ├── 05584e18034f4cac654b1e3ef1b6ac72e6892c56.nq.gz
    ├── 0566ff7c4ab2fb4d162241a74cd768959524062b.nq.gz
    ├── 06930ab07f8dfb66a36f6e068a928f14d871601f.nq.gz
    ├── 06cf636646014d0bf721fa5ff9f41ea4bcc0e4fe.nq.gz
    ├── 08b1e0239f284c755cce1bb86f8a732d0fd105d3.nq.gz
    ├── 0967e8a07ddfbcbcfaa70ef7daa4585adbc99447.nq.gz
    ├── 097d2adc1232a9695699e9289a3d56de7178d2ca.nq.gz
    ├── 0b0ad2203d2b9269a6bcfd8e403b87a12a1c4da0.nq.gz
    ├── 0eb4354236d7b843b60027af331b1e89a6d87f35.nq.gz
    ├── 0f3c76cd00a11f0742cea2319f3ebc58902e5e47.nq.gz
    ├── 0f597bfecc3b9fe1c64389d97dcdb8122d4c7a6f.nq.gz
    ├── 10b0bad9f43775c3acc3cdcad0a20549886ea8f0.nq.gz
    ├── 10f02cbe3a673c55e3d777989e9aa2ee61c42309.nq.gz
    ├── 11720cf972e66a6049bb36ab667d2f5bc2f45af6.nq.gz
    ├── 11c3a48e15be31a858a1ad09d0fa8842ac8d747f.nq.gz
    ├── 12e8b335fc4c44759aee0aa9a72760911225b4ed.nq.gz
    ├── 1346eba4b480761ae2ff5b9cf5f789d489e8dbde.nq.gz
    ├── 14d299e1d51eab98577156fce40c4ba3e0f9fe03.nq.gz
    ├── 15d60bab922ca49babae4d0c0708edad4dc2e404.nq.gz
    ├── 15f172a11d1b0c343a1cd2936147853ace5df8f4.nq.gz
    ├── 18503dd8474747d0fdca1ecc72aed5c1ab016501.nq.gz
    ├── 189cdefb66cc6f679d6a98df186956e02d9f573c.nq.gz
    ├── 18ab818d1fe011a1ad91503cd07ef1fd31f38e64.nq.gz
    ├── 18bd8815f7d1febe9fbd086d751be7c6452797e3.nq.gz
    ├── 19a8d0fed687ed9d85ed7ba207f26ecbc0ce4abc.nq.gz
    ├── 1a5ebf5f430fe88d70c0c707662233bea55893dc.nq.gz
    ├── 1ad4767267b67e28d539a03899289c23b0d7119d.nq.gz
    ├── 1b544a4d00875841dff5757078e0502827f184cc.nq.gz
    ├── 1bfb4347e9bd6f5dc502767db17a6a9e40c08414.nq.gz
    ├── 1c2565cff53fb9b161e585513590ce3dd8c33837.nq.gz
    ├── 1cfc9c7e4c3af97306256209abaf2761e25829f3.nq.gz
    ├── 1d05eb0c52e227fd44a1c2c8224057e7c2ca1507.nq.gz
    ├── 1d8d79de5a635d9be168fa683d001dbc06e29f87.nq.gz
    ├── 1eee01d4c8d5a429b682b8b5567b7fdfe17811f5.nq.gz
    ├── 1ef17c7ee7a48c667a94f9fb4c3bbdd75cedcced.nq.gz
    ├── 1f0aac5850be616b5f7757efaf00762bc42044bb.nq.gz
    ├── 1f237dcc852165e83b5bc0e40b9562187fb576fb.nq.gz
    ├── 1fcb30d7cbc720732b9cea74b0787c4fe0177f25.nq.gz
    ├── 1fddf9cdfdef8756f5898a741c35d4f748521c89.nq.gz
    ├── 1fe7115b20e2379ed057ecbe79ea3a2cf8bb4757.nq.gz
    ├── 204676f9cd0b8cbda4c0969b242f297dfaeb1a70.nq.gz
    ├── 2111986107195125f671f896dd1703537e7bb699.nq.gz
    ├── 2142b5aa72944e43f19f35c80d3747d54751a777.nq.gz
    ├── 214b953b0ed4cba6053323f57ff0e42dc49feb00.nq.gz
    ├── 21a84da1961be2b1d90cd2342db3232b373b596e.nq.gz
    ├── 21ed672b561b5b7e95df89831a4d9f38f844035c.nq.gz
    ├── 22adf2eca4956b5e848f8f7b261fe324a576d44b.nq.gz
    ├── 2392b640aba96836833901f4e6b009416f58b329.nq.gz
    ├── 240d01747ba80aa86079b126dbb6b1673ff9545b.nq.gz
    ├── 24c9745a1c60898fd11974f1b62c8ed4bab1b571.nq.gz
    ├── 25a0a69ea5e6791a42e363f622a1931ba28f37b0.nq.gz
    ├── 267c286ffa913aad930ff1f58131be51bc489589.nq.gz
    ├── 26bd2ec46fc7c2aeac0d2c779d2296022deacad2.nq.gz
    ├── 27634c95090db6bf61aa8dff607330b7553ee853.nq.gz
    ├── 277e62f21eb74eb543fff6f2797d60ef67ccce69.nq.gz
    ├── 27b90312b101f01e7f87fe56a47348049c7aba83.nq.gz
    ├── 2850005b9f27d1d004738585ad022f5572bad1b8.nq.gz
    ├── 292944197b242b080f191238df8e35233f14ce64.nq.gz
    ├── 29bb95008025188958832095bcb6242a76c4d133.nq.gz
    ├── 29eb57b0684790540cafa7c183bc0668b9d31a6e.nq.gz
    ├── 2a7b1b0161f41fd3f20e95e7bf9d50ed07c2450e.nq.gz
    ├── 2abc2a497e68d7c6e6b0dbfc8ae364b42c3a5236.nq.gz
    ├── 2af0281faa0be9a64f84b79e23b8fad233653c48.nq.gz
    ├── 2bae2177a23991536282ff47d751625454903621.nq.gz
    ├── 2bc0620a2f37bc0d87a1b6ef0ce6be82367aca0e.nq.gz
    ├── 2bfc81b6d8cb0754e555e3fd8456df62398fa406.nq.gz
    ├── 2ca08d3e8cc80a3c787764151a22b89d66ddb7b0.nq.gz
    ├── 2cf9889c527aa069378314b6f59fb4ea684192b7.nq.gz
    ├── 2e577f470a76892e3b6505883237f908298b0d42.nq.gz
    ├── 2f6f5194d60a2ded403e4a03d1410eef04e70a55.nq.gz
    ├── 2f7426035b6ac94d67f4c1a10cd6d0bad64569a6.nq.gz
    └── 2ff4f2a830fa03e130ae6d035cb34791bba377b7.nq.gz

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
*Parsed on 2026-03-22 by [repolex](https://repolex.ai)*

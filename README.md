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
│   │   ├── 333491eef58626a697fb961f0c77749f629be39c.nq.gz
│   │   ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│   │   ├── 5b912962e200fbd37b8c872b443c57abfb05085d.nq.gz
│   │   ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│   │   ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│   │   ├── 9d4659c97f4cf1029ebc109e1a7097cb079e85ad.nq.gz
│   │   ├── b5447d999df597d52bd3153372a50d391faa18d1.nq.gz
│   │   ├── cf6b85fc5d913deaf1453d6c075ec8b5194b6adc.nq.gz
│   │   ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   │   ├── e2f8d814ea1bbd44804cae329c0dd5a90f357df6.nq.gz
│   │   ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│   │   └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
│   ├── lsp
│   │   ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│   │   ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│   │   ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│   │   ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│   │   ├── 333491eef58626a697fb961f0c77749f629be39c.nq.gz
│   │   ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│   │   ├── 5b912962e200fbd37b8c872b443c57abfb05085d.nq.gz
│   │   ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│   │   ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│   │   ├── 9d4659c97f4cf1029ebc109e1a7097cb079e85ad.nq.gz
│   │   ├── b5447d999df597d52bd3153372a50d391faa18d1.nq.gz
│   │   ├── cf6b85fc5d913deaf1453d6c075ec8b5194b6adc.nq.gz
│   │   ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│   │   ├── e2f8d814ea1bbd44804cae329c0dd5a90f357df6.nq.gz
│   │   ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│   │   └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
│   └── repolex
│       ├── 0de87a2a96fa981740425f4f94c27735d04700f3.nq.gz
│       ├── 1d8ba020624449838be9fe84f6a0e46eff01cf84.nq.gz
│       ├── 2831edff80a4e53350da9d296eed30246378432a.nq.gz
│       ├── 3010aaf092186a24dae240d78f0ee7d2e0d5d62a.nq.gz
│       ├── 333491eef58626a697fb961f0c77749f629be39c.nq.gz
│       ├── 472aa23aaef0f96e85e27f31690a26000337c8de.nq.gz
│       ├── 5b912962e200fbd37b8c872b443c57abfb05085d.nq.gz
│       ├── 6255850eb2c18dbb361880a10e540ca9bec6b83f.nq.gz
│       ├── 91315e38243426bacffaefc89cdd4bcd78150b81.nq.gz
│       ├── 9d4659c97f4cf1029ebc109e1a7097cb079e85ad.nq.gz
│       ├── b5447d999df597d52bd3153372a50d391faa18d1.nq.gz
│       ├── cf6b85fc5d913deaf1453d6c075ec8b5194b6adc.nq.gz
│       ├── d6f035259f2d7ac0ec284fc1aa1211ac2cd7ca8b.nq.gz
│       ├── e2f8d814ea1bbd44804cae329c0dd5a90f357df6.nq.gz
│       ├── e8832f115a4bc1f51311f1908e008b091e0b0151.nq.gz
│       └── ff4fe897a5d3ddef303c09049ecb3df5aaeec144.nq.gz
└── blob
    ├── 01f5a5760cdf88ff1cd2cc8c63e645fbc7887edf.nq.gz
    ├── 03710748e1efccfe820e7124bc57910e4220cb8e.nq.gz
    ├── 03971eb2b84c4c2f96f6c5e1d52978af91ac0e7c.nq.gz
    ├── 03a5c38a462b07f42bfca5ec8824c3c2ad268aa1.nq.gz
    ├── 044502a2d4b029ebbc2b89c989624c3df79a2aaa.nq.gz
    ├── 05584e18034f4cac654b1e3ef1b6ac72e6892c56.nq.gz
    ├── 0566ff7c4ab2fb4d162241a74cd768959524062b.nq.gz
    ├── 0967e8a07ddfbcbcfaa70ef7daa4585adbc99447.nq.gz
    ├── 0b0ad2203d2b9269a6bcfd8e403b87a12a1c4da0.nq.gz
    ├── 0eb4354236d7b843b60027af331b1e89a6d87f35.nq.gz
    ├── 0f3c76cd00a11f0742cea2319f3ebc58902e5e47.nq.gz
    ├── 10b0bad9f43775c3acc3cdcad0a20549886ea8f0.nq.gz
    ├── 10f02cbe3a673c55e3d777989e9aa2ee61c42309.nq.gz
    ├── 11c3a48e15be31a858a1ad09d0fa8842ac8d747f.nq.gz
    ├── 12e8b335fc4c44759aee0aa9a72760911225b4ed.nq.gz
    ├── 15d60bab922ca49babae4d0c0708edad4dc2e404.nq.gz
    ├── 18503dd8474747d0fdca1ecc72aed5c1ab016501.nq.gz
    ├── 189cdefb66cc6f679d6a98df186956e02d9f573c.nq.gz
    ├── 18ab818d1fe011a1ad91503cd07ef1fd31f38e64.nq.gz
    ├── 18bd8815f7d1febe9fbd086d751be7c6452797e3.nq.gz
    ├── 19a8d0fed687ed9d85ed7ba207f26ecbc0ce4abc.nq.gz
    ├── 1ad4767267b67e28d539a03899289c23b0d7119d.nq.gz
    ├── 1d05eb0c52e227fd44a1c2c8224057e7c2ca1507.nq.gz
    ├── 1d8d79de5a635d9be168fa683d001dbc06e29f87.nq.gz
    ├── 1eee01d4c8d5a429b682b8b5567b7fdfe17811f5.nq.gz
    ├── 1ef17c7ee7a48c667a94f9fb4c3bbdd75cedcced.nq.gz
    ├── 1f237dcc852165e83b5bc0e40b9562187fb576fb.nq.gz
    ├── 204676f9cd0b8cbda4c0969b242f297dfaeb1a70.nq.gz
    ├── 2111986107195125f671f896dd1703537e7bb699.nq.gz
    ├── 2142b5aa72944e43f19f35c80d3747d54751a777.nq.gz
    ├── 214b953b0ed4cba6053323f57ff0e42dc49feb00.nq.gz
    ├── 21a84da1961be2b1d90cd2342db3232b373b596e.nq.gz
    ├── 21ed672b561b5b7e95df89831a4d9f38f844035c.nq.gz
    ├── 22adf2eca4956b5e848f8f7b261fe324a576d44b.nq.gz
    ├── 240d01747ba80aa86079b126dbb6b1673ff9545b.nq.gz
    ├── 24c9745a1c60898fd11974f1b62c8ed4bab1b571.nq.gz
    ├── 25a0a69ea5e6791a42e363f622a1931ba28f37b0.nq.gz
    ├── 26bd2ec46fc7c2aeac0d2c779d2296022deacad2.nq.gz
    ├── 27634c95090db6bf61aa8dff607330b7553ee853.nq.gz
    ├── 277e62f21eb74eb543fff6f2797d60ef67ccce69.nq.gz
    ├── 27b90312b101f01e7f87fe56a47348049c7aba83.nq.gz
    ├── 292944197b242b080f191238df8e35233f14ce64.nq.gz
    ├── 29bb95008025188958832095bcb6242a76c4d133.nq.gz
    ├── 29eb57b0684790540cafa7c183bc0668b9d31a6e.nq.gz
    ├── 2abc2a497e68d7c6e6b0dbfc8ae364b42c3a5236.nq.gz
    ├── 2bc0620a2f37bc0d87a1b6ef0ce6be82367aca0e.nq.gz
    ├── 2cf9889c527aa069378314b6f59fb4ea684192b7.nq.gz
    ├── 2e577f470a76892e3b6505883237f908298b0d42.nq.gz
    ├── 2f7426035b6ac94d67f4c1a10cd6d0bad64569a6.nq.gz
    ├── 2ff4f2a830fa03e130ae6d035cb34791bba377b7.nq.gz
    ├── 31bebd09faa70f9403de7b91f49b20f7af62f209.nq.gz
    ├── 31ef0790b704d5197843d54bdf3efcd112c54137.nq.gz
    ├── 32775aecbcb1948fdf976b2fc9573ab8b63979b2.nq.gz
    ├── 3282ea1a8ab248f44277aa10e0c8f76a069cad10.nq.gz
    ├── 32e7ba21d9993315c2ec04afa8c945b574eb987e.nq.gz
    ├── 333b4887c14c2cbd42710ecf8f08ab67b76fef64.nq.gz
    ├── 33ef1223fb137a50c7bd040df8eda9c55a74e2c9.nq.gz
    ├── 34b70342d54fd82883577c3cc0db746503bff31d.nq.gz
    ├── 35553511d44c4e16df0ea32c78e703aecdbd437b.nq.gz
    ├── 35641f61dc698eaf6f1ad1fc60c220c55a6c8a68.nq.gz
    ├── 357658d2167d6adebb3b1c2b27b964d48b72270c.nq.gz
    ├── 364c72ad73d21ce4b9c77ca1f47eacd02e551dea.nq.gz
    ├── 36ecc8b82e74b6b4d2ee7c67558cf14a8ca4aea8.nq.gz
    ├── 37476923a6939111fa92c67e2d43858993f76643.nq.gz
    ├── 37d93b04362bc5776afaf50a1b0be639f9abc43e.nq.gz
    ├── 38dc05f4b92654205a4d6aafa6008d5a01f06613.nq.gz
    ├── 391ff9560fad51beb2a2bc9d33d76881c0654765.nq.gz
    ├── 392c213ac3dab53b364f8557f7b704e38e201c66.nq.gz
    ├── 39c32895b5cb58507091f93c33712f237988408d.nq.gz
    ├── 39cb7755ac4e73737e81ce8de019f470895fa0a4.nq.gz
    ├── 3a672794cacb835d50b1a585094b68bb9df87dee.nq.gz
    ├── 3b95a4083851b36ff55f2b4faec9aecbc44b2388.nq.gz
    ├── 3dcfec25c1940ed106ea8b5d3ec88b6d3555d9a7.nq.gz
    ├── 3dffe47c462b45728c0fb2cc56128976a5e257b3.nq.gz
    ├── 3e14fbf7bdfa3cd79435cc41d099a417e0f7224b.nq.gz
    ├── 3f128552738f3bee42ed1d25495c542dc2b74551.nq.gz
    ├── 3f557b39cd046d3dd3ccf97c81c9c2dcef91bca0.nq.gz
    ├── 3f6fc80a1e9f518dd812cea0d5ec53aebe63f7da.nq.gz
    ├── 3fa6a64e52f30d3ad836f98b3f0da6f4b6263bb8.nq.gz
    ├── 402465c822cd8384b98fb1434757e8cbb2ad1c2e.nq.gz
    ├── 426d42e5745fcde2176ed768926f010cc61935bd.nq.gz
    ├── 42aea656574dba4eaadbca1ab2c58cc773e1cdfb.nq.gz
    ├── 42b4d48296fe02b955bddbf34a88301b62b6ca1c.nq.gz
    ├── 42d782d29f953d2549e128824c47f1da59148729.nq.gz
    ├── 43dcf017f942f40c26b9c95f1f7e7d3f24609d3d.nq.gz
    ├── 453b6d41774445f9b842ddb6eeca3c4b01b40a6f.nq.gz
    ├── 45d39dfcd2062bf09fb198f4a69db95f87ca6b78.nq.gz
    ├── 45fdf805e1c39a250f3af4209b02b1bb5a0b8bbb.nq.gz
    ├── 4802e9ad819dfe58904d0b755dec83bdcb740a3d.nq.gz
    ├── 4898bc0b1afae580069f2667e4d1355402615783.nq.gz
    ├── 48e21de5f1b4b76943c30dbe7d51b545ca877ffd.nq.gz
    ├── 49cae537e5f257f8539bb4d13bfac83994b77763.nq.gz
    ├── 4a1d54a306c00d25cf42dc8ead5a505a54fd41a5.nq.gz
    ├── 4acf6225f0298f806a0f5ba4995955a824f423d7.nq.gz
    ├── 4bfe81457ee1e87cf217c83d7ae15a64705a59bc.nq.gz
    ├── 4cb841b7ef9447ac94515b783078517d57686ce8.nq.gz
    ├── 4e0892ee7c78c16514f618f4e10581b55eb91fba.nq.gz
    ├── 4e1abbaed1dcf437626e240af00f9d343fac17e1.nq.gz
    ├── 4f52a91bb04e4455d73469ee997ae35324cb7927.nq.gz
    ├── 4f674a65ab5d17d21eedf83cafa29497c0e240fe.nq.gz
    ├── 4f74ef20e3cfd692d65886eac28ca283b41459b5.nq.gz
    ├── 4f9c27ddda748e04790375692f205f7296e12bef.nq.gz
    ├── 50366f7fa7a49e699b40af595750721d79cd1730.nq.gz
    ├── 509b766e7f6c6721ed27f32e357ad95d5757d5f2.nq.gz
    ├── 50e093c1a991bf8e1e604aa953b2973e1bea7531.nq.gz
    ├── 51c7511f0fa9910e4509e98efbd04c1192117991.nq.gz
    ├── 524662725553461b407c789b70950b5e7c49dec2.nq.gz
    ├── 5274b20e3bb1a1684293c6482292fb8e086c03b0.nq.gz
    ├── 566e31617988556807f1541ab7dbca2acc99c0b4.nq.gz
    ├── 56a2de9a24be2ef8e8016485bfa3d3234c907e93.nq.gz
    ├── 5796de3aff7f41fa300358b2dd7740080bf622ef.nq.gz
    ├── 58258222efa3ec6f9d812d424bc91a3cdf54b966.nq.gz
    ├── 58e58515d392ba061a33a6acea32d846f2bf0fe0.nq.gz
    ├── 594cc89a1e59fc565f12918eeb3e661c6a0c62d8.nq.gz
    ├── 5b434546dbeb367b5725514c577712317c891095.nq.gz
    ├── 5bc5d7aad3e710dc06d740ce1f6153acc14584cc.nq.gz
    ├── 5bd9f6dfd2a5b2829dfda56a2b472c42432e0568.nq.gz
    ├── 5be2ac192a8b9b7566b3968e8ea16f535f4ca6ca.nq.gz
    ├── 5c5999d13a046749e9bcae13b4f8aa617da030d7.nq.gz
    ├── 5d21dd1f4926690f96a54233e0224a7b520ece8c.nq.gz
    ├── 5e39d1746214db00824eba5a0c31fae81bee5f6d.nq.gz
    ├── 60462923537d638aa7d847c07a79435c305e1b93.nq.gz
    ├── 60bcc53a2a5e48955d7d082eb7f7abd85fe74110.nq.gz
    ├── 60dea982fec8134a01333e9ffb3cfb16342a692c.nq.gz
    ├── 61a4c678b63c0db0b0ee93e8ef9e4ec0df50b78e.nq.gz
    ├── 62791d73fc0c58a261398ff55b2f3fdef52badfb.nq.gz
    ├── 63017d5c84e12055fc82730e82e275c3b066db68.nq.gz
    ├── 6309e4c527a0168fce01e91feb41971c7f07e788.nq.gz
    ├── 634c48634c266f9e8a8f8b3b7feceda87948697e.nq.gz
    ├── 6423e91aa46d5af8ceaf1d7453b60bdce263883b.nq.gz
    ├── 65158272293e89d87f472cad9f989c3ffae161d3.nq.gz
    ├── 6532a2040371be1086343dfcbc8a63b02fd741b1.nq.gz
    ├── 65fe9c6fcf94d59e4573e51e4bf6198564a42673.nq.gz
    ├── 66fb6ebd294500e751720fdceb32d3ae6a64d6f6.nq.gz
    ├── 675dd939c3fb327f8eb2ab73d4d56e01ed0f0daa.nq.gz
    ├── 678ea819df54774ae1dcc8e30a164ed7f7bf020a.nq.gz
    ├── 67f9e66eae797299bbbe190cee2ef281985048f4.nq.gz
    ├── 68f2e49f842438d2a71a93667d2ca680eb76b7c4.nq.gz
    ├── 694c52c381b27d49564586d1b9f9ff7ff5b464eb.nq.gz
    ├── 6ab1363dd0048474cd5adc02b7d6f7e3fef7091b.nq.gz
    ├── 6b39a02501ec471828389cea3231a9a3488abdfd.nq.gz
    ├── 6be5cc43a81542686ff58926eb61f4b58fb487cb.nq.gz
    ├── 6bfc8452867d261bddaa44199a59b90d7aaf15a9.nq.gz
    ├── 6d713225a21d1d0f0447b27478e9bae8759d6992.nq.gz
    ├── 6dedef618013f925be512ef22062a886b520b3c0.nq.gz
    ├── 6dfe374ed048dc7d4f76b890e5ebf818a81e45f6.nq.gz
    ├── 6e040664ea35267568d5f898108263984a57773c.nq.gz
    ├── 709625a89f0ffa296eb0030db6b8dd368b85dd6f.nq.gz
    ├── 715dab5e96103694583429571acb24e1e411678c.nq.gz
    ├── 71736502eaaec91910424c7d5c6fa1ad0fe8c225.nq.gz
    ├── 7265afa471409345c26c5fe2518b8442b99dc963.nq.gz
    └── 73eb410973c828ce8dbdd2cc69a0d4fecb5676de.nq.gz

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

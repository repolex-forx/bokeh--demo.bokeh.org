# Repolex Knowledge Graph of bokeh/demo.bokeh.org

RDF knowledge graph data for [bokeh/demo.bokeh.org](https://github.com/bokeh/demo.bokeh.org), parsed by [repolex](https://repolex.ai).

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
rlex download bokeh/demo.bokeh.org
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c8d25bfb95725654bf0cdf49a478041a7128e1c0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c8d25bfb95725654bf0cdf49a478041a7128e1c0
│           └── chunk-001.nq.gz
├── blob
│   ├── 002d1703720c1de98b81f6cfda6859bdb4d3b6cd.nq.gz
│   ├── 005083e2d04652f3ae2a8111076ecf476709441d.nq.gz
│   ├── 0058aa158addc4a4cffad557e09fbdf91953060d.nq.gz
│   ├── 016387e3780b4c4dcf1451edc17fcc3f22a8a908.nq.gz
│   ├── 028e3308b8365cb469fbe8028a2855e5f150aa70.nq.gz
│   ├── 032ac97357169897d5b1976d8f2189ae94bee84e.nq.gz
│   ├── 042fecf939c42ae4c169af4069a247f636e9dd2d.nq.gz
│   ├── 04a4e63eb7f56853bd85c125b49927cbe4130de5.nq.gz
│   ├── 05761e29c597e8a57eadc0091cce012b87743e1a.nq.gz
│   ├── 06765d36ebb6457a4551483b796745662668e89f.nq.gz
│   ├── 084d2373b08fa7ff82c601ad0762ad8deea170d9.nq.gz
│   ├── 086653faaab8d75effb23704d766f8efdd6720fa.nq.gz
│   ├── 089e5acd2dd754d605bd57d50bac322434fdf8b8.nq.gz
│   ├── 094706ff47dfbfab2a358c1168106606e1dc910a.nq.gz
│   ├── 095013c5cd7ea12671407e4ebc598e6f26daa978.nq.gz
│   ├── 0a06c5b3b81f8029c6cf32041990c646cc657433.nq.gz
│   ├── 0a71fe99f3dc96562eed43eb1ad91eea31f77aba.nq.gz
│   ├── 0db77f09aed8f25afa32bed8abde3a76a391346a.nq.gz
│   ├── 0e550ef54790dd4ed1600b0eefc29e0500c1d984.nq.gz
│   ├── 0f497b9b7d03f4181d67704c50fd81b63837447b.nq.gz
│   ├── 1161ecff316a7bd40a641f68ea42c1cc7ecd9c1e.nq.gz
│   ├── 11edb137686fd95a8c55972f2d3c76b5e47995e7.nq.gz
│   ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
│   ├── 123e2b4f2e26fda5b9604fc5bf8e48dcac35e241.nq.gz
│   ├── 13c58ec3d5da229ac39e119e3be10fb1c6e3e384.nq.gz
│   ├── 1439b6d0de95f3a6471a73419f3850ac7234661a.nq.gz
│   ├── 1454db510825a826a8200d637431b6a7a234d9f1.nq.gz
│   ├── 154a8eae8d6cfce61e4953f59c7b1285f18ba054.nq.gz
│   ├── 1649301f1536b44dae7c3607262d88ce48927ded.nq.gz
│   ├── 18c34586b84390e6a7c8668fbf63ccb793545925.nq.gz
│   ├── 18e97da5c5169319fb5a5a0e127bfa6b7dedb80d.nq.gz
│   ├── 1b8f915e9bcf29aef4abbbcff4813b15e3d12061.nq.gz
│   ├── 1cbda5d447d6d278ba4b7e3a00c3ea186b2aa472.nq.gz
│   ├── 1edc1f687aefbbb3db88abda481a493cc803eee5.nq.gz
│   ├── 230afb25ba541b26164d60f731e1db25b322ad8c.nq.gz
│   ├── 25303654d0a78032762f9e24835fbde10bb6e0a9.nq.gz
│   ├── 289a9884e649b6bd9722e1d247ae01abd3d135f2.nq.gz
│   ├── 29c353c977970fde7afe1c5bc0ae2f85fb66b133.nq.gz
│   ├── 2b3e092a3e22773969b30acce910b68d9f3eea56.nq.gz
│   ├── 2c36c0ed933148730b38995cc64e3fbc8a363f6b.nq.gz
│   ├── 2d3995053a17fa99e4f0624c9d341a7616c8fa39.nq.gz
│   ├── 2e567436f1ea952d7f2f88c4f3cb94cf969a675a.nq.gz
│   ├── 2f7366d26950b6acd54a99a90982473e2dc4b99f.nq.gz
│   ├── 300d2bc7e52bcc9a7a0a8829d5d0b00e2bbbbda6.nq.gz
│   ├── 308d857ec0213a2f157daf2459e91d7aef9ff241.nq.gz
│   ├── 351e8a705da1f586b4adc907b9c41ded96ff26bc.nq.gz
│   ├── 3624ea5fffe84a03fb9823ede2f6e69a016a88a7.nq.gz
│   ├── 3b1f3b9d3367dbd40bbc106d3d053183c78e3eb0.nq.gz
│   ├── 3d502f60f3ebb338da6530487b9f13efc15d88d5.nq.gz
│   ├── 3f4d1600c422a27d30b9fb21fdb2b409cdcb3ae9.nq.gz
│   ├── 3f8174a2b974768dd2c7a69f9b14cd821122b35f.nq.gz
│   ├── 40c733a2e4f6d35c1133c13834e0fd7690e20dd0.nq.gz
│   ├── 412af04bafe3155975b2a5b9b7b6dcdeca879c81.nq.gz
│   ├── 4146ac15af98cedf016da7b7aa33e9192e67f19a.nq.gz
│   ├── 447f70e60dff9b8584064c773127ec1eccd3a820.nq.gz
│   ├── 44adcc41e1b5ebede85af848f025be88b8484626.nq.gz
│   ├── 44bbe1a4bc67353faa8b5cff85655008b010edc9.nq.gz
│   ├── 44faac5251941844908b2c3b90b75c61732bcc2e.nq.gz
│   ├── 483fa6612f69f2466fb7adeacda6511ad2f1cceb.nq.gz
│   ├── 484c7c2c9a5495f70585fe9f4336113ed0343f07.nq.gz
│   ├── 4b02ddf67a85f1ec9afaf25f0fc7f809474ea6c0.nq.gz
│   ├── 4b5a4744357a67ee1bfd5172a73b7f52420e3b97.nq.gz
│   ├── 4e69c15ad67e879d721cc8f1c6c284d3f6870ba2.nq.gz
│   ├── 500a1fe53843b0cd3177c20ba853410680346e2e.nq.gz
│   ├── 505034381e3898edd54ba3f5cf04a29e15abc94b.nq.gz
│   ├── 51af099153b4ac1fddad15f88faaefc32bc70575.nq.gz
│   ├── 525a5209d36514e23ba72339d90435950a082c2d.nq.gz
│   ├── 55678c346b810a954eede3d95e5d47ff4d9fbe65.nq.gz
│   ├── 5639046a7f30f5f2741324a39cf3372ef6243a84.nq.gz
│   ├── 56fd0826eb00fa829b7a0f9d6f9e241080f374df.nq.gz
│   ├── 58392e5d6375ec64da5a84b8a8cc02fe01fd392a.nq.gz
│   ├── 59ac118a17331db90d568f40fc8ec91a2e844e65.nq.gz
│   ├── 5c117d3284723cd1ecc4d338334e60c2d91e8e60.nq.gz
│   ├── 5d31d7af6d4942f995ac987487c85ec5c980c2d9.nq.gz
│   ├── 623d21ffb91f15b7ed064604e68b75a644dcf313.nq.gz
│   ├── 625ceed32d686415f7e7d50ebb57f1f33c4aad85.nq.gz
│   ├── 664447328f4895bf37c0526506a9728509d57955.nq.gz
│   ├── 69274685f71368aa49c303ad6a927bec04f2d3b1.nq.gz
│   ├── 6a8562e35c4cc29ca7022290061811b9a71e5f7b.nq.gz
│   ├── 6e61722ee2c90c40e83f2dd7f3d1af86d41a5a7d.nq.gz
│   ├── 6f6fce549165ffa816546e4e6b869786b63c9e04.nq.gz
│   ├── 70a234361b7beb11f192377ab48f1287420aa6e3.nq.gz
│   ├── 71880818e236e4411f2375422f928d3c06102684.nq.gz
│   ├── 71d11436dcfaf170630df6adea62c7c5caf93e2c.nq.gz
│   ├── 7421b8a4c894acb59cb40ee4949ecdafedc9e3f1.nq.gz
│   ├── 7535f62367eeefd9d71791926e4b03fc270963bc.nq.gz
│   ├── 77cc4079f53c8d16fc78c4caf600c0b3ab0196b8.nq.gz
│   ├── 787cb56f5386bb03b56c1967bc2e410983d7a874.nq.gz
│   ├── 78db13a8c960c44059ff098a18af324c0bf0dbd1.nq.gz
│   ├── 79f356653b044f05037cab4868221f486b048183.nq.gz
│   ├── 79fd68e9a27b43ff4c5ae0bf47eb6297df39adba.nq.gz
│   ├── 7a65b14d72f3c3d53f2c2f7fc989e48e5e33099b.nq.gz
│   ├── 7a993b39740538f3f657865d615252fda42947b7.nq.gz
│   ├── 7b7e4d0f9d05a3f915a58d105ae8f80509b0fd1e.nq.gz
│   ├── 7bd48f2f70e6603eff96eb2adc6d25382839ccfe.nq.gz
│   ├── 7c1a94fb327325e39ee6540c497049b0ce311353.nq.gz
│   ├── 7e3e146f4c10d8482856c6d4807838fe16db2e00.nq.gz
│   ├── 7ef8c5ffe8d2774ee38bd78506cc9d975dc89654.nq.gz
│   ├── 81290145c3c8a26c9e74de296ba14454f3d1b804.nq.gz
│   ├── 81fecd335be43b0bf686fc890bccf46fd7d22ef2.nq.gz
│   ├── 8316ca60bc5e84b21474778f89d89c0f18359eb8.nq.gz
│   ├── 867111b2797eab073075264aecd9413768aeda67.nq.gz
│   ├── 881c57652971179d5af8a6f994e3168a9aae7abb.nq.gz
│   ├── 88214f9b31dafd8960261e9e33fbb09477f0e170.nq.gz
│   ├── 88303862fc84d1c9fc45f494e0ce5f774e5b8651.nq.gz
│   ├── 89416f1d0e9bc5f67dff7445be74ada7222660d3.nq.gz
│   ├── 8e86af9758bbf4bcc413a0a2d2190de3906f50be.nq.gz
│   ├── 8f3d167bb5499650dd0e8654da35201ea68031ec.nq.gz
│   ├── 8fe9e1ca67e673da5bc34a8131f25855e22005ef.nq.gz
│   ├── 900e6dc33fa3d4a7fa7f6d171616f18a85c8bb9e.nq.gz
│   ├── 908851e042101aaeb41dc9fd4eaa2f50ef124a79.nq.gz
│   ├── 91f4816e96084a6cfe829ace9feefb66649b0bff.nq.gz
│   ├── 926bc8ccaa45b7af8727f591a44af2601795759c.nq.gz
│   ├── 96b21b99329a0e5fadd1cf0005e737bd522a7fa7.nq.gz
│   ├── 97de4e7d4e41c4fd6aa50ac33f0f080c432b9f6f.nq.gz
│   ├── 9ba2916296dad22c050fb99700975a76922601ed.nq.gz
│   ├── 9d3de9188cf52075f717af61ee48ad0c3705773e.nq.gz
│   ├── 9ff7e4830f6558503f5748ef3746f11f024429b8.nq.gz
│   ├── a046de04f567b6846249e657003396a839264ee7.nq.gz
│   ├── a1b69686580fbf79afdb9e3b5f4c6b5394116f46.nq.gz
│   ├── a31b53033ad537232f5548aff9a5bfe0fe7111bc.nq.gz
│   ├── a820aa5770c61364a0d4a651f6a8e967f29828ab.nq.gz
│   ├── a8b310f426d8828164f21d529dbd4a3e313e594e.nq.gz
│   ├── aa533f60dc80c57bf2bb910290dcf4a6bf370552.nq.gz
│   ├── ad0b78695e782cdba1b272a6174664dcf157aa61.nq.gz
│   ├── ad0e71038a488650111c26748e59d5f5d7ed0c44.nq.gz
│   ├── ad5ed7c26073666c091dad6fdfe3a0c651b30b2d.nq.gz
│   ├── af05888db31e294d4acc0984ae2852c217635b04.nq.gz
│   ├── af1b4678540c806accf9cb5fa1b720da09ece7d3.nq.gz
│   ├── b045598d0686526587fea0740978dd545fd704c0.nq.gz
│   ├── b0a5c349ca8788ef8e48e8cda18c304b14958156.nq.gz
│   ├── b0b3fda0655ac9740403bde848a17d486a30bbf3.nq.gz
│   ├── b2da2eaa26b0c29394b6c3073e868bae136b3c60.nq.gz
│   ├── b2e7c3027407bbf3eec2686077728c1bb7f2711b.nq.gz
│   ├── b4f6c9e9beeaf2e4208e9cbd304587d60086cfb1.nq.gz
│   ├── b601a84099b9960218aced24e209b5b41da3bf12.nq.gz
│   ├── b992b0ec62487c639764b941af37b50722d8d432.nq.gz
│   ├── bbc80f8ab0db7dc47521c4bc6dd16d598329ed0c.nq.gz
│   ├── bc1147f084af44dca795bccf7d1a55574ff1792e.nq.gz
│   ├── bcf1e13bf70a121ee2697ddcf1e986b1b4b1ad06.nq.gz
│   ├── bfe7a7902a51cac907339452e2a1e6ce297c83b8.nq.gz
│   ├── c036f75b0119e486207a43d0f4d8edbbe0de2a1b.nq.gz
│   ├── c037ddc7e4a61e1680528bc96b375c778c73969d.nq.gz
│   ├── c179df42280a39af4d092ac5b0a4cbc238cc8ae7.nq.gz
│   ├── c2def308328aba74a252f146645f43029c6d5c7f.nq.gz
│   ├── c30fc88a1cdb9d6c82ae140984c02295a67597c4.nq.gz
│   ├── c907411bdef018fc1994c1e0ba0a1716393d4af7.nq.gz
│   ├── c9080a88f23f0f9e43f5c88c6394725816d549cf.nq.gz
│   ├── c9ad83577e893ce369f3bc432f0843b5a9d018bb.nq.gz
│   ├── ca7f197c78ad2791947b2cfc4060c4997034a1ee.nq.gz
│   ├── cabb0c69d74d8a2786664d95fabaa49ff3622d96.nq.gz
│   ├── cad9943f618d0e172ae36bebb2ea84418bde99aa.nq.gz
│   ├── cb2539da7f0d436210d73a29914196da3aafe488.nq.gz
│   ├── cc1d1d8003a5e320113b47f0d517c65a237e0ada.nq.gz
│   ├── ccd71a8ed1b0e575e6bbd171c602238957367bf5.nq.gz
│   ├── cdcdc6c6efeac7be945687b6b6f0862e35849683.nq.gz
│   ├── d07f6cbe78b92a4825b2913ecbcc29f20110102b.nq.gz
│   ├── d2c867c8f219163dd3558c014c672e6a5575739b.nq.gz
│   ├── d37cce4df6edb11d0f504bf1864bd6a8a45f5d81.nq.gz
│   ├── d46ca07ad3ef2a218faffa25ddd89d5a156c557a.nq.gz
│   ├── d671f527966229d47b4f4a5f41468c007e2c8207.nq.gz
│   ├── d6a1dc31433db55ca1dafc810544b2a01ec06426.nq.gz
│   ├── d75cb2d8a005dce2b17fff405b00d7309f8fa62d.nq.gz
│   ├── d84a779a94af9baa4332cd8cbe7dd734cc43741c.nq.gz
│   ├── d9cabd6690e10a3dbf9f5e645c14c36f12e1c034.nq.gz
│   ├── d9e79b292c3025bfd512072da18cd9030d8048db.nq.gz
│   ├── da2deab58885fb90e5263c7f444ee3a5aed4d535.nq.gz
│   ├── dafa26d243c2b7c5f636712924e9f43dac5127e5.nq.gz
│   ├── dd22eac290697b2130e1e556f8e722023366de05.nq.gz
│   ├── ddab4508d7cf15d367b848e5e4ace222a211677e.nq.gz
│   ├── df4dc111dfe84ee4696186b3abbc8e8927ed5cd0.nq.gz
│   ├── e00637ec15e1ede5dea6ca4ee03dd944efd87034.nq.gz
│   ├── e6f991bc179a3ee7966d7b40552ed47316770672.nq.gz
│   ├── e7ea496523e629d6e0878c389e530b6cee0c7034.nq.gz
│   ├── e84daaf38b29d48861a455394273d8b5cc58bad4.nq.gz
│   ├── ea96e4b0ea01a8091959811a05d2763b30b6b0ea.nq.gz
│   ├── eaf40a00a52bce4602ef2be4b07bc37a69564967.nq.gz
│   ├── eb7f285552ed2eea46b919caad6759db61897b23.nq.gz
│   ├── edd69300ebfdd28be47d023ff4b63cbb097624ac.nq.gz
│   ├── f1b3c8b91f82fa29e888a69234c88c101dfee457.nq.gz
│   ├── f2178a1c19c33f76d8f1c1075519fb83ad33389d.nq.gz
│   ├── f22e30b91d4c7a0dfaf225088ae958b0682f34aa.nq.gz
│   ├── f2717f5c2013b018cc06f880ccedd4ca62224747.nq.gz
│   ├── f857a19634d052b34456eb3db7622d4831fdc004.nq.gz
│   ├── f888658aee66a70722e734923e6bc04abb93d9eb.nq.gz
│   ├── faf0b4d8857ebdbd1789dbe15f5cdce64d8e729d.nq.gz
│   ├── fca89da20e75933c331e1c4781f0bb130d556040.nq.gz
│   ├── fdac149f66bdc7eae468592e8077279ac85c03bd.nq.gz
│   └── fe57368828b2b5382c2c5b5ba4d6d888bb079dde.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c8d25bfb95725654bf0cdf49a478041a7128e1c0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 197 files
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

[bokeh/demo.bokeh.org](https://github.com/bokeh/demo.bokeh.org)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*

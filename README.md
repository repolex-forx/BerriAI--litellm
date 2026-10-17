# Repolex Knowledge Graph of BerriAI/litellm

RDF knowledge graph data for [BerriAI/litellm](https://github.com/BerriAI/litellm), parsed by [repolex](https://repolex.ai).

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
rlex download BerriAI/litellm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae6f7f661355d0764031678d014c29f765897b68
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── ae6f7f661355d0764031678d014c29f765897b68
│           └── chunk-001.nq.gz
└── blob
    ├── 000b0cf5a0b212a7b1c2303e3ea4665f7f69f4d7.nq.gz
    ├── 00317e502ecd9ec87bdf26fe59e63e8e38664330.nq.gz
    ├── 003f0834e01d65ee3f1dfab5fa6deef387507f80.nq.gz
    ├── 00c070b09960248dc082a0c7916b4ac484f757b0.nq.gz
    ├── 00d5ef4e4056202111dbb84fa374a4430b443317.nq.gz
    ├── 0117fd4252ea2f9b7029737efcbe00a8c7daed11.nq.gz
    ├── 014597dba392d66f630a668c48594327c0b2e81c.nq.gz
    ├── 019b9c8096e153a3f6bb29626619fce40860b5f5.nq.gz
    ├── 01c4f2bf46fa6cbcc6eb0e6c4ebde4b2cd812041.nq.gz
    ├── 02f9e42ff3139918e95424517dbcdb735e6e2e2d.nq.gz
    ├── 031e84896b2d11cb72bf5f90dab622e63ce57a53.nq.gz
    ├── 032d4baadaca4ed0247555e7da032c245891d3d6.nq.gz
    ├── 044315168d2da24a2e2aeb714db3da518382346d.nq.gz
    ├── 04cf391c70065850ff8b5b41c16ec2025aac138a.nq.gz
    ├── 0632ec87f34e5eba44f7f7e7b0f71977f37409c0.nq.gz
    ├── 06aaca44e8a1e0aafed4b7e8601be064fbfbe716.nq.gz
    ├── 06b1a6aa11b20f95afaac6d31e1a20535af7b3e7.nq.gz
    ├── 06bd3329cc1c3d1939a7f54907a0ff5f3ab74fad.nq.gz
    ├── 06d41f2a5e06cd60aca118d53ea50f0beb234ce8.nq.gz
    ├── 06eab31680e08d0a26b6c06fcf160a9ca680a1c6.nq.gz
    ├── 0708920f5e79ccaebc508c5712e2b7102b59cacf.nq.gz
    ├── 07486762a64df5858b2df5a65c8616f75f900a42.nq.gz
    ├── 0765371dc4ab6cdadf80059bec8a06e140b4e3de.nq.gz
    ├── 080fc3d24c95fe1d50312440e20e35e2c78e8f00.nq.gz
    ├── 09591fe24d5fe73a79360b99d2bdfe743a1aad38.nq.gz
    ├── 0a14b9553394e399e60bfc5796773285307734d6.nq.gz
    ├── 0b58b1e6bc8a537afbaa78b9cc39bb8b4e930757.nq.gz
    ├── 0c01b93aa809d7481ceb10ede0b65b1a46c0b518.nq.gz
    ├── 0c360ce2ed9d76d6cf802b8e30f859b61220446e.nq.gz
    ├── 0db122b927f0173e823065c9b2642fee7848ba4e.nq.gz
    ├── 0dff25965f4a9b9519f215831a59938b2acb51c9.nq.gz
    ├── 0f5ce1c883d867c930149cf3eaf213558ab42c15.nq.gz
    ├── 0f74ddc18fab538938a0961a953dfe26a8069f6e.nq.gz
    ├── 100425a8c9fb3051a8cc1975ad4b8b52e12b0389.nq.gz
    ├── 1010d8b55f6d0ec11039f9bc750999d342c55ab8.nq.gz
    ├── 108ce8fed985c149cb02725a7f1b433020f44bd5.nq.gz
    ├── 11812208929d5d2a23aa83668cb6fa69af7efa4e.nq.gz
    ├── 11c5eaf84ef5eb8e271f72fcebcb1ef0a32c5470.nq.gz
    ├── 11d40b87783eb3be55781e2809aac5076f69a962.nq.gz
    ├── 122dd5b555a2f10faf021f61cc2d4d0de7112826.nq.gz
    ├── 12a7bfe68e91bfe0778eb283c31039e74644983e.nq.gz
    ├── 12ddf412ac3f3da0f23ae278537280f56c402c53.nq.gz
    ├── 12e9036572fc2d99623a0483b4cd35528fdf7034.nq.gz
    ├── 1328d3614048b9bd4e353d059f760bb93c9d240a.nq.gz
    ├── 1361b89ad90e3d2f43d907c61bc3a97c5d6fe264.nq.gz
    ├── 138b893e4caffb6c2ada28a6dcd625f131e42e2a.nq.gz
    ├── 158dea53b71d0527b4dcab3241f4f532e857330f.nq.gz
    ├── 159e4983ddc393d9992bdae750836e32db7c36d7.nq.gz
    ├── 15a254dd7a187276d3e35e3ce3602eb561956670.nq.gz
    ├── 15c8721a7f1fd5c0d811c91960838e981b42dcc2.nq.gz
    ├── 15e8783b96b5d1a0185fa25b3ce8ceef3ce2223b.nq.gz
    ├── 17619afbb0778e01060d498bb6296eb098d1e6e9.nq.gz
    ├── 17d49f591d7d01d685f3086e213e4a5fc900e07a.nq.gz
    ├── 17d7eb4b860f7d2850aceb415fcdd44c0ad4daa3.nq.gz
    ├── 18a4eeb7c0a0db599a10745f187ce33adc60c2c2.nq.gz
    ├── 18f136c3b282899b5aa2723769c680adeef54f81.nq.gz
    ├── 1a3baee1ce31d61317f0c0981727675cc33be8ac.nq.gz
    ├── 1b71db993ef8b28072f9fdcd6ea2d9326beaf20f.nq.gz
    ├── 1bc7853437b56406ad5a806106788e49d6e04fa0.nq.gz
    ├── 1beabca3064e7bfe8bc6c3bd463a147d79d32039.nq.gz
    ├── 1c3ce8052e3e616db2f4ca1ee284951866b6bf67.nq.gz
    ├── 1cdc288ff877f5382e7058e9c6fd5913923364a1.nq.gz
    ├── 1d63958faed4b439cd2e24e87a8d5bd837282093.nq.gz
    ├── 1f287c64fa75f430360fd3a177be36cad03d9219.nq.gz
    ├── 1fe7de0ba85ff688499fe2add2968c71d62236fa.nq.gz
    ├── 207e966ef281fb8359364f661237189a411dd362.nq.gz
    ├── 211d5a617f0b2f91a38fdffa4494da9f193d0d60.nq.gz
    ├── 21da835ee1674c1608aa0ede15a0acf394f388b0.nq.gz
    ├── 221b0e021964ea72634e6e76c68121f657f9956c.nq.gz
    ├── 2238006e86936dd7d4d6bd216baf9830081ea011.nq.gz
    ├── 2312d016abab68dd6ab1816f7ae126e9bcfb5df3.nq.gz
    ├── 231bc25a7f0646a0ce3bf985f10d2a3273320284.nq.gz
    ├── 244efc8047b334a77274492c47673e703d243dd7.nq.gz
    ├── 25c04caabba99d92fb8575ac846ea7064e9661df.nq.gz
    ├── 25c322e953da38070aabdb9d86cb4f7cbc7cb33a.nq.gz
    ├── 26709e77157ba830188f076700cce39087313fee.nq.gz
    ├── 28d048876b74806e2b2521fe22bc6f326390178d.nq.gz
    ├── 299ee6fcabf8e8113d6111e8af8b2de2f1f3218d.nq.gz
    ├── 29b18f1f2615f41776235870063ba54cd17c115f.nq.gz
    ├── 29b7702efa4725bea5c9558765c92b66d307fe5e.nq.gz
    ├── 2a5f79cf480afedeb6e52eb2ab210ca4bd0b66c1.nq.gz
    ├── 2b697671edaf5f3efc5663e326ef49a83f25827c.nq.gz
    ├── 2bbc9cf48553c934b69a415c04247fd2c7810a45.nq.gz
    ├── 2bc89f3513bf406aa561f5813dfd40d8cdd545c9.nq.gz
    ├── 2c0c179102eae60ef158a00bd1a30989e67ec116.nq.gz
    ├── 2c751ae6a34ef83d918f18c3e03c046a65c5a61f.nq.gz
    ├── 2c83261fc927d704fd4891d6c4c7794651fd6f2d.nq.gz
    ├── 2cd45edf43e09cc2a636223245f0563655d0cc0d.nq.gz
    ├── 2cfe2b79886d4b16fe01cc8036d8895eb774345a.nq.gz
    ├── 2d27172f824d7ac8029713edaa86ed9b13d8406f.nq.gz
    ├── 2e39d45e66085574151fa3772c9b7a2b97cb9c14.nq.gz
    ├── 2e8fcae2e0704357541ac3d6fcbb083ca3394436.nq.gz
    ├── 2f1b37646103e057fbc6fc3bec32dfdfdac3bd25.nq.gz
    ├── 2f46e548a7bc5625bff09ebce99833dd41aceaac.nq.gz
    ├── 2f6e1a5d62da046aa765d2f02ba197b2ab440a30.nq.gz
    ├── 2f82561d1b18a0d6214e0dcc5dafb9469c903945.nq.gz
    ├── 327f1368b5f5ede1c85d3901bc921d22006f655e.nq.gz
    ├── 33f3e81c68993e0905cacf978997c1ce9ee9b451.nq.gz
    ├── 3430b5876780cb7775fad066c7ee0bdf07b0b085.nq.gz
    ├── 34fc88e04bb02bebc8eb76cc496e11dcb859c2dc.nq.gz
    ├── 3567388de05117693cfe929b9f43b1729737cd49.nq.gz
    ├── 35cdb18326a729ad7e6cee409ea72f4ca955155c.nq.gz
    ├── 35f8d933cee97712efae6091b2af891b0f9c5f1c.nq.gz
    ├── 3621ff6a2fdb6ed3546ab312b7353c7a36ccd16f.nq.gz
    ├── 367671b3a3e23c650d1019402ce03da7e90ac91b.nq.gz
    ├── 372f27e2be14965a207b6261c2a7766c894613e7.nq.gz
    ├── 37c9da33c061cf72e93bcfe14b2f342148817739.nq.gz
    ├── 397252be7df0b666152f023b23c7b9d152b21072.nq.gz
    ├── 397ec408ae9fc8f72224513272ffb68ebd869bab.nq.gz
    ├── 3a153ff2a5f4ea03c2f14149246ca13e154a5a93.nq.gz
    ├── 3bb4ab0d3becb887fda7f08e28c0683c0c465484.nq.gz
    ├── 3bfef5bae9b48c334acf426d5b7f21bc1913aab9.nq.gz
    ├── 3c8c75e6d6f0e05076e7439028975f6e805ca51f.nq.gz
    ├── 3d23b69f846ff0bb626414abede7fe866ea9fdbb.nq.gz
    ├── 3d56d4192ab100e4736cef2e6ad4ef01d7036227.nq.gz
    ├── 3d95105bb3a67ec30fbe62921838fdd654b0698a.nq.gz
    ├── 3db6f68760ded1999b173314e020011ae06068d2.nq.gz
    ├── 3dece3053d25b8440d6f3d31bd4ab7f883180990.nq.gz
    ├── 3e37faafe156d119a89a070703a3c4d1fafb2774.nq.gz
    ├── 3e4d82d3a3ea802858904c1fa43ebe23ba36384e.nq.gz
    ├── 400420b0073cf5d7f675ea96473204947ec835cb.nq.gz
    ├── 40853f3e6135faa6806dc9a8df088a2233f3aa6c.nq.gz
    ├── 40c59de075f427d12bd0a216f5f0df41e1f46ef4.nq.gz
    ├── 40f553e6fdebc2b5990a6f75cfcc8c378c308f07.nq.gz
    ├── 426f6430c2305f69226993f6280f362e4e88caee.nq.gz
    ├── 42bc9bbe34aceae3e2fd3012126508debb53633f.nq.gz
    ├── 42c087c5b63c329d20e4d8ec009f26fc8cbbca77.nq.gz
    ├── 4420506bf91cfc1ab5de6e2065f6cd0fbadce18b.nq.gz
    ├── 443010b65da44329cb0011dc51f2c007451b14cf.nq.gz
    ├── 44a4bfdf448487bb75f99dc6ec7e7fe3f358adc6.nq.gz
    ├── 44f7959b2bff5a6e97de0f71c1d2d37f7e2362c5.nq.gz
    ├── 45180203a589182a5c3e60e01051e68d2c374e4a.nq.gz
    ├── 457389a063e0a5ec353fe916efb279e0058b77eb.nq.gz
    ├── 45c53af934968875bbdd44f695c8bb2f65c2703f.nq.gz
    ├── 45d915b7b3dfccd7c0d2dd41ee1f1fca0832508d.nq.gz
    ├── 4679382df41b998a126c5bc11d239d4853294e89.nq.gz
    ├── 47bdffb1209b178398100dd7b0b16c688ef77c71.nq.gz
    ├── 47efa21571a42891d57edfa1a3979eca761393e0.nq.gz
    ├── 488882c0186e4143397d0f2043c02ed6d36df71b.nq.gz
    ├── 49845bd07b5c10e9a066dd47ce050952cc8f7c54.nq.gz
    ├── 49dda5995bcd70486587ce5c941980a971bc7cf1.nq.gz
    ├── 4a7fb677190914a046ea78c2d98d69ac8552a5f0.nq.gz
    ├── 4a9a05c1023006ec7f50ab6d8cf5d635e2e7b3f4.nq.gz
    ├── 4b0690b2bd42d20b3a1bf67d94108361a72f7b05.nq.gz
    ├── 4b83740bc0947a5e8581c04068092c21bd5bb2b3.nq.gz
    ├── 4d0818987ce821fb00942b91e6f05949b74d8373.nq.gz
    ├── 4d11a41e8b00450f311557c8c24e2c9d68810e15.nq.gz
    ├── 4e7765b9e5d7256c92056467ec0ecdd23e2eac8b.nq.gz
    ├── 4e854f58229b5ac5935eecb136201fcf1f942161.nq.gz
    ├── 4ea3e9a592c8c99fdc74289528d926872782e35d.nq.gz
    ├── 4f1e43166b14ac978b8cebe795fa538de08266dc.nq.gz
    ├── 4f44a4adeed178d77bf3efce5a249c7a2910f07a.nq.gz
    ├── 4fcf590f0ebb6b07018853915a1d74e87bb63c3a.nq.gz
    ├── 501f5749ea48df63267817eada6c3a05df9ae72f.nq.gz
    ├── 50208cc278ebb2131dee07a859731ef867e563a0.nq.gz
    ├── 51e0d75a845a640519a74d1c06dc6c1e677effea.nq.gz
    ├── 524ec6a715e7eaa5a4f63ee75db44861e343636e.nq.gz
    ├── 52b4837ba97e06165b0ab6c959ed9558c8737f6d.nq.gz
    ├── 52dad8269ec2a6c7df78ce749e978427d97bdb06.nq.gz
    ├── 5320545fd49590c393f0b0e39127eb1d795999ce.nq.gz
    ├── 53c2f2efb1dc19caecdc5f9593ad13c46c3a4e87.nq.gz
    ├── 53d0d82a7f2beba4a06ce3f849b14c7552224158.nq.gz
    ├── 54ea3702cb40a42b1e216686b94a009dc60560d1.nq.gz
    ├── 54f8f3d4b3ffc51ccecc48a1a2cd11ba202e0401.nq.gz
    ├── 55e9f9322c7c838ecd01c5bcc007b4110d517d54.nq.gz
    ├── 5601c53d574d64f172981490f8567ca7fa2eb4de.nq.gz
    ├── 566b040a5e78c0bc5523278285ff792dfae6b33a.nq.gz
    ├── 5686005abc55960810b5120dda9c320fe602d7ef.nq.gz
    ├── 56a62da39a95e2fbdfe7eb79bcb217773470829c.nq.gz
    ├── 5717eab5a06e164fcd0d3601c153e954ed9e7f13.nq.gz
    ├── 5746bf510e27ddf9f2dadc30d5716d1d78080f4b.nq.gz
    ├── 585798903529ba359e2b96ad875b07a04e742b3b.nq.gz
    ├── 589882b2d77955b922fcd966df2b403985e11028.nq.gz
    ├── 58b5ca2a2f67630c3e26b45c2ef7d5ba7d16e5c4.nq.gz
    ├── 591a8ae0a701d74ebe5b6f8ad1008b81f0f55998.nq.gz
    ├── 5a72f2e0f9ab9d9c50d9de76e7f90b30914523fa.nq.gz
    ├── 5a7d86bdfb7ba8809566bf067f3ce56f91fe21e3.nq.gz
    ├── 5b77b0798ec9d161b99b2f692e08c9a7c6cf7949.nq.gz
    ├── 5bdcdddf4b7e9e0eaabff3caf8456fc8b81d0a61.nq.gz
    ├── 5c90d54ae90eed0f62faa7438ac10a9b0ba541cf.nq.gz
    ├── 5ca5728354c3f428933e0fefb1cbaded6e098578.nq.gz
    ├── 5cc590ffa790128350c2e4bb9d7f6121a80ed007.nq.gz
    ├── 5d69f070ce82dec3a76bcad3dd4568c2485489ff.nq.gz
    ├── 5d8cb45965d53aa825b8fe0fd00db551fa01094d.nq.gz
    ├── 5dda336dc944ed1d934bb35a1826c6b30920adc7.nq.gz
    ├── 5ecaacbe170a26544384b454db327a6ee060e545.nq.gz
    ├── 5f42c00efcbf7617f26f56b68d0114fed48f9405.nq.gz
    ├── 6045b8012f09ed01ed4a0a32a6df7ee1aca29f86.nq.gz
    ├── 60822321e5ba4a87a3ec177b6c124392e42dc4f5.nq.gz
    ├── 60bd7ae72a3479ea044d3cb336b5954681dc3400.nq.gz
    ├── 60f163392a8ddf6f0b92e880034e73a28db394a9.nq.gz
    ├── 60fc2a9295c8e1b3556f98a6d859e302acb0cea1.nq.gz
    ├── 610c49d5b5271ae72de579da988d535eb4ad1531.nq.gz
    ├── 61115e00d07613bd952d274ab2ee6767132bb05d.nq.gz
    ├── 6171874f491e88a1ba9b1be9c5d321d0570ba501.nq.gz
    ├── 62fcb97c0ef52c0075401e5bff9ef9f47cd6f524.nq.gz
    └── 637e56d2dfe0bd7cb18bfc3ba5ba100bd940ab2a.nq.gz

7 directories, 200 files
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

[BerriAI/litellm](https://github.com/BerriAI/litellm)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of pysal/pPysal

RDF knowledge graph data for [pysal/pPysal](https://github.com/pysal/pPysal), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/pPysal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 06b54c0e4db142cb3bb286301eb26dae12006a61
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 06b54c0e4db142cb3bb286301eb26dae12006a61
│           └── chunk-001.nq.gz
└── blob
    ├── 00892f8b1b6e4e62b0acdf3799fbeb65be122d39.nq.gz
    ├── 017b319bb7f4612a28348d6805af2dfed9b78dd7.nq.gz
    ├── 02edc842b36b6cf420dc943bf6bbd5922d8e6941.nq.gz
    ├── 035ea52e524951a6f332a3d4770b042db240c222.nq.gz
    ├── 052880eadf936fdee08e84efbd5ff84ceac52e81.nq.gz
    ├── 060c548517d1cb8c0597c3d888d995e46f1161d3.nq.gz
    ├── 08cb94ce76c1ace470f8ef01422300da9494e353.nq.gz
    ├── 096d25c2eb88ab5ce9477a8a738cee972c170f11.nq.gz
    ├── 0a0978beefcb1856a44f6d379d1a4153a6443219.nq.gz
    ├── 0ad2cbfb28e18f6ceaf85797788453afc269ae1e.nq.gz
    ├── 0ad2d4672f42099f384f0387603aa68e73271b7e.nq.gz
    ├── 0bc3f79a84ce96cdaae281bd34e8a128f523458f.nq.gz
    ├── 0c935d2a170385744dadd91a0c34a17650be6a76.nq.gz
    ├── 0d1743a32a07d7b93da4fe11e0c8bf8f0c63c909.nq.gz
    ├── 0dd9b2a775df93c542822ee1773878362cfa5484.nq.gz
    ├── 0e2065c6340e856afbafce9d90e48e24ab9c81de.nq.gz
    ├── 0e7613eb80ab3c5705413b6d88774caef413d71b.nq.gz
    ├── 0fdaedb5a18aa116bf4c2c791bf465b9ba5a3b68.nq.gz
    ├── 113faf0cce92d3fc4093ca9075e5123fe0ff0d19.nq.gz
    ├── 14a80df6dba883e84bcfa85c0a43d5b69d40cd86.nq.gz
    ├── 1577a4bb473fa3db898806cc22233ecab007d3ac.nq.gz
    ├── 173d4f26f60e2ac6bc69ee5e7811a14a976aa13c.nq.gz
    ├── 17c177b7c34ebcbc089344a6d769330b60ccae1d.nq.gz
    ├── 17f98740edc7bdd80bf31af41d33648048e46087.nq.gz
    ├── 19f88669305f0b6b17dd699d29b781236f57ac8b.nq.gz
    ├── 1a2c1b6a8296d3171df9fe33e70afe538a5ab307.nq.gz
    ├── 1b163d10fbd5300d6470d00532ed9f3c8775b353.nq.gz
    ├── 1c26ad53bfc7a875983fc32fed9b6ed272ad19de.nq.gz
    ├── 1d08d72a8d16acabb2ad5de35111f38c10ee83b0.nq.gz
    ├── 1f23d8f30d19121860a6523898828b84d2adc05e.nq.gz
    ├── 1f283e4e5539041ece75633b46f6cbd64e809a9f.nq.gz
    ├── 2042221847fffd917b28256be180ec9966fde594.nq.gz
    ├── 20663c1ceff2269c660299b1024b5515e75c0f03.nq.gz
    ├── 271ad72788e7edfc57a657a6b1f51b21c033cb68.nq.gz
    ├── 2746b85d216fc5cda43a18d8bcbaf18bc8b733cb.nq.gz
    ├── 274a7abdf74e8c6c719e2c2c7d80146860067ea2.nq.gz
    ├── 2860e9dd3c83db5180492eefc11f6111c928bfed.nq.gz
    ├── 28ddb131eb4b2d1b838d11125074616ed9615602.nq.gz
    ├── 2a504176cc0919dce99695b4a08a8e22a18ad9a5.nq.gz
    ├── 2ac5b0146fbc3cd7a31d2e9eabfc69c64ccb6a9e.nq.gz
    ├── 2b01d9ee285ebba510caea5353fbc6099bd2db72.nq.gz
    ├── 2b64c69acbc7c901c95a1ac347b98fbc9cb3324e.nq.gz
    ├── 2dab9e6343c4201a57bd0a5c331a5265af5a6bd2.nq.gz
    ├── 2f1ad6ac04d08dc12ba494c3e91e454e0e85c74e.nq.gz
    ├── 3038163dd97d4f5347d8336f69dea63b444dab09.nq.gz
    ├── 31e0f0c9b2517d8c099f8d25ec2dfabf50bc4114.nq.gz
    ├── 332657f569619c75c82b50dbaebceb9d3a36c628.nq.gz
    ├── 348ebd9491ed019f54af8f313ce8a4d782e0e609.nq.gz
    ├── 360eb37b4578ab446558a53cc9299f3a5ff67d15.nq.gz
    ├── 3718667f17e92a7bd3785944f6cdfaccc249fcc6.nq.gz
    ├── 3b0870c6ab57a4f2dac7b1a64206c6f2f2eaa4fd.nq.gz
    ├── 3d4720806e850806335c0ab5f6f94f70ebc4d2a6.nq.gz
    ├── 3d510da4a88b536a997df2b3cfa0dc7565644334.nq.gz
    ├── 3e85b096047df7fa653abc4f2b9e2b28daa223c2.nq.gz
    ├── 3fd358f7b7a78b09b66f6acac48c3651ea98f67b.nq.gz
    ├── 406a7477935abbe67a839b7a8441533394be4304.nq.gz
    ├── 413b46a8d754dceb58cacf8436795c8469fb5e3f.nq.gz
    ├── 420a324c6d60e1a81d4f90ab7b12e1cde177d293.nq.gz
    ├── 4288db93e683eb7b1d221e2de147a41c250cc297.nq.gz
    ├── 45ab83510b2bf6a1db883806b11049203c1922e7.nq.gz
    ├── 4653ef19655c5b7450ac442ea80d8642f901cf8e.nq.gz
    ├── 47ad24339bbb3d01dae82604d39f3fbcc4e3e259.nq.gz
    ├── 480c497b8206ef2436888b93645b9a46e2bb4a62.nq.gz
    ├── 49a3a8f60f2f80f2633861fb428b0911e3f19a12.nq.gz
    ├── 49eed30757929258203ce348e4ffa19e48238a40.nq.gz
    ├── 4b7e35bc506eb122525cf0da0523e2f8dd5d7c79.nq.gz
    ├── 4cde5e6933f363c49922b30b96e22989198d1f00.nq.gz
    ├── 4d46a2d899c2cf9a40b65a896de5358242d04a7f.nq.gz
    ├── 4d53ccdcb41166931f1b0e23dfbb2c0868c584ae.nq.gz
    ├── 4d77129211a37143c4b587fb86be5dfc3e31b9cd.nq.gz
    ├── 4d9d43962379773d6dbbb0e3faf89e0b1610624a.nq.gz
    ├── 4e63f4b20e45c121aef5492d47cf9512c90a0c85.nq.gz
    ├── 4f2782276493fabe0cafe25192361db31c089b2b.nq.gz
    ├── 4fd98a0511b3c5293884842297acac9144d422ef.nq.gz
    ├── 51853c8ebe60db6ad629abb6b629e758b81eb5d1.nq.gz
    ├── 51bb1acbee84e8cf929d938697633890e3115e41.nq.gz
    ├── 5480aa1d14cec729c3c3d9677ef3be40483d8e29.nq.gz
    ├── 55584cf345da49690d39b7f43607429134818272.nq.gz
    ├── 55ffff33eac7455a4034b7fd424e46fad32afac7.nq.gz
    ├── 56382f108a3b2fb25cc393f8987dbe1bc18a96b7.nq.gz
    ├── 576bcebc7e3e7afd279a4b4361614d7209c76899.nq.gz
    ├── 581620241a6fb8de121946a7cda5af7158fc2da9.nq.gz
    ├── 5894c798e0965de2d3717417b21ada7c800b4530.nq.gz
    ├── 5af0ccd235522d0791ea12fe0c02f76793e5fd4d.nq.gz
    ├── 5c695daf1bd6b2fa6a791c5587f2fe2d6ec0ef3d.nq.gz
    ├── 5c7bb52791c41fae593d228b107455bb8cbad9d1.nq.gz
    ├── 5cdefa3f1cf8f485a53d8b0c492057561063adc3.nq.gz
    ├── 5ce360f27c804a5acbf0349ccfd9924b861fbcc9.nq.gz
    ├── 5decb7f28e80e146cd7e064a9872eac1d772dc99.nq.gz
    ├── 5f91cc7fd6ecd8a91291c1156902ee3396fca1fe.nq.gz
    ├── 5fbc831e743348854289f8b0cacd8b553b1262cc.nq.gz
    ├── 5fffb83cd16b2018cd80b6ebffe9eb3ab72cfa16.nq.gz
    ├── 607da36e9a421a56b748be9ff4c548f403856f7f.nq.gz
    ├── 60c6c07e002352e10732eeaa1f084de4af1d0192.nq.gz
    ├── 60dea1d612b8fc08eb1e5baf77dfa1df09300f7e.nq.gz
    ├── 6217f436531df027f327f615a47682e6c58a6d17.nq.gz
    ├── 637945fd1b3482f7bdb0aff50be88706346547f7.nq.gz
    ├── 6432d4d77c44bf979224afff90239ec92f5e858a.nq.gz
    ├── 6483d15812bfea41114da341b5f6e0c14b51ada0.nq.gz
    ├── 64a71c67fbd785e09611ea15cb61641d488bf8ae.nq.gz
    ├── 64f69755f6e843afe35d2c86c671191e8fe4c51c.nq.gz
    ├── 673a6f6efb6e95b18baf4ce21344e4f01c40567b.nq.gz
    ├── 67ef7a02c9b77d1082dd6ab97ad833d4399352f8.nq.gz
    ├── 68588a92fa7d6c340349f8dafabe7f1632afb1e7.nq.gz
    ├── 688378873aa3e22f577a3deaef1ca24df209dbdd.nq.gz
    ├── 69b83ab9cf1ab572e1ae6b9b6831a7aaa90c8e1f.nq.gz
    ├── 69d507fc9da1e680375cfaa47be7c0dad00bee03.nq.gz
    ├── 6aa1970cbc717cd352277cb8d8ff552cf83db3a5.nq.gz
    ├── 6b067a6c70b231e18e6f38177f85d86b5c380ebe.nq.gz
    ├── 6b2f0113e9aa9f8dc2add31ae47bfd2667a4a5b6.nq.gz
    ├── 6d38685608f5de3f40c3352f7baf5b6c4eba2fb8.nq.gz
    ├── 6de4a57de8e00f07060737c131c7479c22a8475b.nq.gz
    ├── 6e9e3c5778627d6d3f1af9d83a398fe3dbc7f905.nq.gz
    ├── 6ff08a0f2e442a094215c58f12deb782ed676cf8.nq.gz
    ├── 7071998d51f3a55637952b543d21bf3f0a6ca073.nq.gz
    ├── 734bec440a34a9e8ac82fbf2c608440126f6cdb5.nq.gz
    ├── 7381b99f7bcd28d0c4f5b20a83e2b2565aa679f3.nq.gz
    ├── 73b14c1f1bd3edaf6590073a99b15b5b34dbb45f.nq.gz
    ├── 73c039f58ad4d1a42533e1e9dffd7183b1c0be73.nq.gz
    ├── 740c6b0e11af19448d1948d302a25a770b7216ad.nq.gz
    ├── 747df588c20bbd0050718b6e024048becb8492b8.nq.gz
    ├── 7569c3a71eff38895dbd4ef8d3aed612548889a6.nq.gz
    ├── 7703c1472f142b9cd569c4eabdd20fe30b62039a.nq.gz
    ├── 7755930116d6572c8ff833163eff974e37f1b88f.nq.gz
    ├── 77ae62685d2538928e3e193545de51cd4f0f0045.nq.gz
    ├── 77b0040ef9a3e0bbbd5ac60062aad572615d939b.nq.gz
    ├── 77fc294bb899092bed01e4996ecf0e91ba3b5ed4.nq.gz
    ├── 7b6443b2e6da8841a42d0d1d3a470ceda94d2e5c.nq.gz
    ├── 7c303e1ac2d87f469b5b25880e39ce04a340844f.nq.gz
    ├── 7cfa24b99d63571e7622c669a6a0dd050976a2ec.nq.gz
    ├── 8025fe2373e4d6078a36123a1294710c2c79f67b.nq.gz
    ├── 80440e2e5b741ba9f14ca08c0f35d340e627509f.nq.gz
    ├── 827a5d9f50842d806991670aaed8c1c224424491.nq.gz
    ├── 82b7f1328a2e4b8df8ef9dcfcf858fb23be3380c.nq.gz
    ├── 84a650945317e38fde3a1ed1e80218e1be54f8b3.nq.gz
    ├── 86c0e93392869472acce46318eee12d6e66b2865.nq.gz
    ├── 875e7e46ddfb3836d71ca6c23f338a0832477867.nq.gz
    ├── 87cd9f09467070be461badc5b5fe7cc317015c75.nq.gz
    ├── 891024a7f8e30fec90a7523b3bb56c8b10c02558.nq.gz
    ├── 8ac33d0e6bcb7ae17beff686dbeca62ade20e970.nq.gz
    ├── 8c575d1db026de249b6b4467c279a291d4060067.nq.gz
    ├── 8c6fff1e52782ae8d172633613b6d31ed1ab0362.nq.gz
    ├── 8d59ab7e44a0734c9a9fd5612a8554332a8985d4.nq.gz
    ├── 8dbd12f7a2dd43e113e08d39ce7abc99ad8c345a.nq.gz
    ├── 9073e4bf9fb0ac533d4bdf5bf9e6ec06f13adc6b.nq.gz
    ├── 92b49766533235726d9012ad60d4e92553382a68.nq.gz
    ├── 92ff959920c680877b8dc367d572c84918bfb619.nq.gz
    ├── 933d677d5e93513e2b8861cc012dd64c69525e51.nq.gz
    ├── 934708ae56e699beda22aa9f6cc5e4c006b5402c.nq.gz
    ├── 96aa1d31863de64746ebc99e976c3601fecc8353.nq.gz
    ├── 98098c1d6d48b914ccd108535d3013a335d04c71.nq.gz
    ├── 9863e82e1d944ff50af3faf84f0695b20d793370.nq.gz
    ├── 98e11e8eef274b577446e58ab6adda4380b68251.nq.gz
    ├── 98e154c795f1859302def4fe7bda5963ad78e319.nq.gz
    ├── 9cb1880698c17f53fbc1542dcfdfd41d41dd93ad.nq.gz
    ├── 9d68afb996331738bc4acd16fd679189d5baf5ea.nq.gz
    ├── 9e01b3f6f1939dc26027762ab4dcd49c536e3125.nq.gz
    ├── 9e468b260e9e7a134706674580b68291fb7c13e0.nq.gz
    ├── 9fa6977fd199273c07435002bf07a5d92888e4c2.nq.gz
    ├── a0bf412189ce80a990624f55f40d4ab5640068d2.nq.gz
    ├── a0bfde54772717959314f9770d925ff912950606.nq.gz
    ├── a0c63f65a2c605bde237179dad06cfdc85737ec1.nq.gz
    ├── a30c00a55de19be195abf9e942f6cff93bf0a825.nq.gz
    ├── a3e3294914e7d942533f88a4f4ef757887f4fe30.nq.gz
    ├── a52abc00ecfdb813376a2d88f9b91350e6f98647.nq.gz
    ├── a5a7af033c6908f4cb235a1048aa8f4ff8642d9f.nq.gz
    ├── a738922f87dca07928d8f390c097cb1c33b3b6ff.nq.gz
    ├── aa1d20edd01bd53ca6f09ede8d6988aca6da8ad8.nq.gz
    ├── aa46ce7bb3d1bdb1ef8866686d02f85728e86d89.nq.gz
    ├── aacf4260844c32af832bd4111c2dd0f2b0a9345b.nq.gz
    ├── abd9572bd1d57d3c0933cdb6963e5229348b6c88.nq.gz
    ├── abf07268be53c0ca5ea7853d6e8659cd0471c017.nq.gz
    ├── ac0da17ad6495ad16a0ffc1ef2b8ef27e520210a.nq.gz
    ├── ad4a213981bb83822cca87c87bf7950549b2c15d.nq.gz
    ├── addeda720db5529332f6eff624012be881568079.nq.gz
    ├── ae9aa142f196b5852730907a8a429c40933d6318.nq.gz
    ├── aff7b7bef03b86ff426bfca96617988920db71ea.nq.gz
    ├── b0dfaf4e92e039f51c4bb0fc24ca6ab908ba8d1c.nq.gz
    ├── b12b774c3621469151ff51991687186d0ff102a0.nq.gz
    ├── b1c3096c6d33082aaecfaf9dd8578bbfdaa37f6f.nq.gz
    ├── b22a8d0da2e5319bf6d9c165c2f1aebb8a67a483.nq.gz
    ├── b415a8f65634c5bf18033030c10a16df0592b878.nq.gz
    ├── b4329d4b58c4d8ce2f252a080ce1c472ce5f31e6.nq.gz
    ├── b4c63ee3506b6d332f9c7b575e1bdabb4c0876bd.nq.gz
    ├── b5554261f4d4e021b6db128f1bb39c7c5f38bee0.nq.gz
    ├── b5a83b3f97f2e199e0d30f6f1d02e70698985e59.nq.gz
    ├── b6737147c486c7c49168c605f26912a226ef5d72.nq.gz
    ├── b8a435faf3d3040327a888164971ef313f0993e7.nq.gz
    ├── b8ca1287a732af6f93b9eeede438ee130fdc57d1.nq.gz
    ├── bd6ecf477b323aa01c67e5a4265ba230cb39eb00.nq.gz
    ├── bdf5719a022875e378300fe44e902070b48d45cb.nq.gz
    ├── c02bd8b81f4b9f93f008c3c9a115a81c8b77231a.nq.gz
    ├── c1d273dfa323f7a2477d0c3fba3efaaa8d1df27e.nq.gz
    ├── ca286cde8862d3ce53dbe3971fb601e2e99976c1.nq.gz
    ├── cb94e6bb2c0ee6139ddab1a64fe3cfa6c124bcfa.nq.gz
    ├── cd4274711c77c9000b8a5663e0ba28b60acf9750.nq.gz
    ├── ce1d72bc4a634eb18b9a73ed2876107d15cc95f5.nq.gz
    └── cfd53330f4526098ebe721759272b7444ca54858.nq.gz

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

[pysal/pPysal](https://github.com/pysal/pPysal)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*

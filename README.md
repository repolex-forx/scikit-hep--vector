# Repolex Knowledge Graph of scikit-hep/vector

RDF knowledge graph data for [scikit-hep/vector](https://github.com/scikit-hep/vector), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/vector
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── caf34cddf9fa2cebc4d9c8c7ed090006ed4687cc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── caf34cddf9fa2cebc4d9c8c7ed090006ed4687cc
│           └── chunk-001.nq.gz
└── blob
    ├── 000a44224e6ca56b6278462adbbcd3089c440442.nq.gz
    ├── 0093f45ae3e4f9c1c5eb38fe443c494c9fb56083.nq.gz
    ├── 0099b57f3b362a7dbfda5fe3cb94618204b637a5.nq.gz
    ├── 01d74e6ab90487c2016314b05504e33fac182e1d.nq.gz
    ├── 0238fd0da06a282ce5591fbde98c77807ae63787.nq.gz
    ├── 031442c1a7e80487bac47b596f59828c1a93828b.nq.gz
    ├── 031fd0baa112196d1bdbb2473e87985a891cd3c0.nq.gz
    ├── 0419a813fe9f58f3bab8e78ce9fcc4c9e5a3bce5.nq.gz
    ├── 0444f334dd8b5ac7bfd4de3322ac590d5b37666d.nq.gz
    ├── 04974216a1ae4ab06bb2e1a3e10a55f1d374dd35.nq.gz
    ├── 063ba4969daa9548a9b3de3e9c0870ddf69c7e5f.nq.gz
    ├── 0645e3d3c7a01cb623c7d3c5ab12008c49d00fde.nq.gz
    ├── 064910f7f8e2be6ae2243137ecb042a85c5f6b54.nq.gz
    ├── 08b168442fef024121df4312b4fe695f0cb91c13.nq.gz
    ├── 0a04913f19ede25df6d68fac4fc246ea80db991e.nq.gz
    ├── 0a0bad989fdba999514bb546198d32adab778e23.nq.gz
    ├── 0a5c59c1cb0a8ec2dd852bff3af534d189c9a882.nq.gz
    ├── 0c67a72a70c977eb4c8df24450f4ae416c1e3d93.nq.gz
    ├── 0c741ac7d05b1b1b5913e2095607e68589dc74d5.nq.gz
    ├── 0e0b96ffeebb672fb22d8308beaa4742d70435a8.nq.gz
    ├── 103bd61be48b10504e693d6474f16fb51faefe6a.nq.gz
    ├── 10bc28ab8f0f20f62a41f7fc8bdc1abffffcc3f3.nq.gz
    ├── 142b27d436401176041838312d102a40120323b5.nq.gz
    ├── 14f4d7cd40004034ebc8fbab410a3f0bb0b68e9c.nq.gz
    ├── 151f86e917ec4024213161df5cc9bb7678f16274.nq.gz
    ├── 15dc99caddcd0bf026630d4fbb6de34f4a7ad6d3.nq.gz
    ├── 17233c3583adf3057c3a9625934e88f0e2f46bf8.nq.gz
    ├── 175be7f79ef54d4e3110dcced1e86ef4dcefad69.nq.gz
    ├── 1762c738f55f668aa54e8aba85142786d771bea0.nq.gz
    ├── 181a007e61e9ff0c826447a3a32db24bcc402b2c.nq.gz
    ├── 181a083dd92d946889c368de166916859734a493.nq.gz
    ├── 188dd5ad058784c830329627be91e09e05e0a3ec.nq.gz
    ├── 1929a3313f032cb2ae94bb1c4bca221db4a2b634.nq.gz
    ├── 1974bcd637687facb83a79c42ef22fd07cbd22b1.nq.gz
    ├── 1c72f757450de31599052af5bc020638ae5374ad.nq.gz
    ├── 1cebe10cb66c97c5cc91dab49a13fa74948a1138.nq.gz
    ├── 1d276d38b079819e77e234e50799af8041ad4878.nq.gz
    ├── 1e81945e74fa91811eff333ba725aed2e2b5e35e.nq.gz
    ├── 1ec40a76d5f6cfe779a19f2b5673de8b7b335a29.nq.gz
    ├── 1f9a03cb0caed6696842731cb00be6f3ba9c89f2.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 2163dbe86a41b75b7364889f741ca7545f7a5c25.nq.gz
    ├── 21f8c78306a5b603d429270fb8776cfd3672168b.nq.gz
    ├── 21fbaf99e9a0e877237951b3cde1cd7fcc5f6dab.nq.gz
    ├── 24ae6ed385e03005b9244bb4003c7734e4b132d6.nq.gz
    ├── 26250ed2bc92f0460d5fd5d1554accc9246ddff3.nq.gz
    ├── 27101bdf2d3a04cda9c988abcd7b318ea278f395.nq.gz
    ├── 27e7a2db129171400c054c62b6b36426fb484528.nq.gz
    ├── 280b02eea1cedffc3e78fe7478b5212bb75827dd.nq.gz
    ├── 28f10850dcdf9648e89ddff1f0903e6495dad6c9.nq.gz
    ├── 291c26e67d98ae64d9b9ee054df6b61b15b627de.nq.gz
    ├── 2b4d85126a981f623dd61cf87246b0f850af8c72.nq.gz
    ├── 2b83fdef5e349d6e8840f680d0cd7c33956524bb.nq.gz
    ├── 2e18e1bd4a3b154d09d08aba193efa7d2ea81087.nq.gz
    ├── 2eb25ad2ad6187e1a617769a8b3a21c20ec449ed.nq.gz
    ├── 2ffe43312587843a5fa309012fc35855b138d4fd.nq.gz
    ├── 30df8b19d1730e743fec4bdb69f6363715d896ad.nq.gz
    ├── 319573205ef02a7f0f1b749ed2cffe391a1de30b.nq.gz
    ├── 31ece24c8353ce07754a9021c0e1b182808a18f5.nq.gz
    ├── 3296e237efed5abf2a9f7458f857057366ffbf5f.nq.gz
    ├── 34f133f20011424db1dd78c15f22ffdee389fce9.nq.gz
    ├── 3571d5a40eb4575ae4ff2e09fbd35d82f6a7b687.nq.gz
    ├── 358e017206227c41d5a5d32e2757e9c0674c8bcf.nq.gz
    ├── 3631b15ce0970a16576aa718ac3dedeb43706c2e.nq.gz
    ├── 365e92a058056d35655fca6dfe7100a5b5027541.nq.gz
    ├── 38c2d8ff80e3d56ab82441bf4f1cfb6165e9ccd5.nq.gz
    ├── 39445a303512dbb33cd4d3d042f6dd6f6b231a29.nq.gz
    ├── 3a3dc85c860a3f0b90ef545f88771596f9de6301.nq.gz
    ├── 3a9e61598fe30e649c76e4d8f30a80923a6f1533.nq.gz
    ├── 3b3c643b3dad7eadc8e0e46bb065e9fe4376307c.nq.gz
    ├── 3bf3dbd1d94e92df92349ea518894de3a81d39de.nq.gz
    ├── 3cbca6922fdc97563682ee55a01d0853ee08da05.nq.gz
    ├── 3d1a0501c152247a79f63918039505eeafcbb60d.nq.gz
    ├── 3d63947518bd8022a59015db591f45948f51a4b5.nq.gz
    ├── 3e44f120dcb9c31c4ba6f45bd78cbed01dc56048.nq.gz
    ├── 3fd7355106400dc73b79f9c8f429df62d86694cf.nq.gz
    ├── 4213585aae6c94cd94e1a0e4a8e2a1b9b102ff9d.nq.gz
    ├── 43f96ee375d3ca08927a5c06fa4cc58935903511.nq.gz
    ├── 4410253783cdbabeddb7dfbb95917ab0908634a2.nq.gz
    ├── 44795274dc746c88f5f716afcd4e7d5c0e83c646.nq.gz
    ├── 4545713e23ac42c4d374181f42c0f39ad9863dad.nq.gz
    ├── 4622ce63a7a353bc3cfd0c2f88227b1a5d8dd39e.nq.gz
    ├── 467a0546b67c32cef2c31bd08ec696ac88208beb.nq.gz
    ├── 47ca03f4eb6aa2580a606bd19d9f80bff7508f72.nq.gz
    ├── 47e2d43eb7cf56606210c517217fa1b2a6a1add4.nq.gz
    ├── 47e81ce81bf5bc72d581176e55fe74317c2cb102.nq.gz
    ├── 4989cee9f36bb5b1c39eae0460b240202cc169b5.nq.gz
    ├── 4b2559a01e3ce78fd0d017048f7d33863c4e3abd.nq.gz
    ├── 4b5dbde4bfc897dfaaa20a198fff18e07cc09655.nq.gz
    ├── 4b8e11973248988212ae13450eb463073f0dcaf4.nq.gz
    ├── 4bacbb7a0bf30918d610330a9b208da7164c3391.nq.gz
    ├── 4c02994707e84731ee2dc7598a2dad054b84283c.nq.gz
    ├── 4c0d1745a0f78f886f4ac83b02d8906f1e0024e6.nq.gz
    ├── 4eaf69658b3b080da2f20156131cc6f3379c846f.nq.gz
    ├── 4eef0ae6f7aff382f9624a6487e254a89b598c9e.nq.gz
    ├── 51148f369b04c60050dea3810b24daa97f47dbcf.nq.gz
    ├── 515e15adb15938a75da085656eea8f420275a65a.nq.gz
    ├── 523c0f45a0e88147a62276f17458723ecbd65d10.nq.gz
    ├── 537ee58077ed8e4bfd3f6efa8903ace7ea83beba.nq.gz
    ├── 569d23b39b39307682aa5b27e966fd7da26c40a1.nq.gz
    ├── 56c7a53e7376ed4b7caf35cfbc24c0ac47eac4d3.nq.gz
    ├── 572e9ed939b53fe62f68f0d2a7250176060e2786.nq.gz
    ├── 57689d18c625dfe680f18b387108644fafaa52c3.nq.gz
    ├── 57cd325d96b77a23e1d7f16d5da9651d5f23b6cd.nq.gz
    ├── 57cde083e51ef21811f4542d1aeaeb6eaa01dd3d.nq.gz
    ├── 5804d2ca21745c328f7b1d978e686d5604f61d21.nq.gz
    ├── 5852b6ce7b1877ba082f8e4d82ca3834dca15ff7.nq.gz
    ├── 5890e8d5416b67fcec02cde20fa6327950e65a2a.nq.gz
    ├── 59f06d80c2ca3f88986f619529b8a9113725f98a.nq.gz
    ├── 5a4ff8e57938110f222542f0a1626cb0e88e7399.nq.gz
    ├── 5aed54a459e4169657e02234949248ea55a36f06.nq.gz
    ├── 5bb2b22f78faec68eeed9a623c15cad2747c9eba.nq.gz
    ├── 5cd65ab49c271d7fb95f57bd47fb0ad879261aec.nq.gz
    ├── 5d858b5e78db958de457fb52b89c453fb0821257.nq.gz
    ├── 5f33b59c90c8debc79ca428aa44aa65f5d833fb4.nq.gz
    ├── 5fad9fdada1777a3848fb7e393fd37ac4b6ef848.nq.gz
    ├── 6245051314d8360983408d0b450affc5a051cc47.nq.gz
    ├── 632b5a816e4f5f9f46d123a5aa19b3985c2d002e.nq.gz
    ├── 63401f5c53794b37ae76635217c2ca9e09d2b017.nq.gz
    ├── 63f72f72ae2b59b1333dd014886b51ec0564ea9c.nq.gz
    ├── 66a7657f727eb7aa596fa09c5aabb529139baa44.nq.gz
    ├── 684f01b59889d534cbf71f432a068fdf1c7ba292.nq.gz
    ├── 68863f49f9dfd6572662c3821a3ef39ff56c33c7.nq.gz
    ├── 6b847f12186e3741d438968e61b5dcdbab1e6cc6.nq.gz
    ├── 6b8a251609042babc0edd05821e1b5b455509bb4.nq.gz
    ├── 6bdd13e9fdadd75e953502f7d0a8b3709070959c.nq.gz
    ├── 6c2e8ef415ec58ef179ec07725998ac36384ee3c.nq.gz
    ├── 6dc2208d7179bdd3f71f9433fed2d8b469dcd4ad.nq.gz
    ├── 6f06cca1175582165b21a189e695ea2692d6ed2b.nq.gz
    ├── 6fb067599fad265360c54c7bc0d8b2fbed612d11.nq.gz
    ├── 7076494c1c88cc42e6e40fe11a90b51f3c5d01b5.nq.gz
    ├── 73a41cd8b91cb8d02fd1d714d6398ab9f762d317.nq.gz
    ├── 768d5af4d931f7732d1e9108dec13e7fbe01e5d5.nq.gz
    ├── 78d3bfb2079855139a69bfb3dbb39f92aa0f9f67.nq.gz
    ├── 796845f59516a9c4c87a12262475d2451595116d.nq.gz
    ├── 796f038fd9b012dcc5aa7353101eb3e198eb2535.nq.gz
    ├── 79c0683856c850d6d8b8d9e9682092cad85ac4a6.nq.gz
    ├── 7ab056062b51eb7a063cba1d753c4f8a4a2cb977.nq.gz
    ├── 7d31ed25d15a6b1b352510b4c34b389a42cef3c7.nq.gz
    ├── 7f014d8838799813dce7bf95535f00d11effcc2f.nq.gz
    ├── 80658b3b1c5c72d39c1a56e71c30ac5ef12bbfe6.nq.gz
    ├── 80ea5a926a04803cafd28da8ae140cbba73ee60e.nq.gz
    ├── 811e12d31b7b74dd5920a2ce952c106ba0a099e1.nq.gz
    ├── 8219469e7fea614ba58e5916a8e805b70f77eaf0.nq.gz
    ├── 8258081c328e5f8a58206ae1a2195dcf7d676e45.nq.gz
    ├── 835b436ac078350b2bfbf6ac11fcdb2f29b173fe.nq.gz
    ├── 837246ba2652cbcc862f52f28fb7924ed20f15d3.nq.gz
    ├── 84efb06bda8cbbd5cf1b82d914d4c89161f232b8.nq.gz
    ├── 853bb4aa23dcfde3e691df3f04f31dd26dd8cf61.nq.gz
    ├── 85cabfb74d3d03adbf51956ab9a1ecd5a71aedbf.nq.gz
    ├── 86e5d3a8492135b21d11095c103b085f152675b9.nq.gz
    ├── 883e6a29437412e6f39310be5d41cd95e9aa36a0.nq.gz
    ├── 88ec0bc3bb4f640ec50204f28dad50a00db7b1c3.nq.gz
    ├── 89abffca96bcca84e18ea13192d6af499b55857b.nq.gz
    ├── 89da4dcd0a51a90bbc2983ca2a58021c76f3602a.nq.gz
    ├── 8b01ea74b11be79c1ba00f6981d44ac62f07723d.nq.gz
    ├── 8b0f3e0813159db9d9462f7114a0c043f222a913.nq.gz
    ├── 8b298833b39bd5e555356cc5eca8f8a7399932fd.nq.gz
    ├── 8b8e5d3da34233525376331df6d4bf704735e5ad.nq.gz
    ├── 8c4100f8aebb2ec4615f625910e24ade1fde744b.nq.gz
    ├── 8c55ebf10925a6a8dffe0ead5e537382e3411f41.nq.gz
    ├── 8d5ce26c2c15b7dba8039a7d608c27c41c7da370.nq.gz
    ├── 8eca6454c8f75329ce2cd7c85ed8324199904f47.nq.gz
    ├── 8eee09c75112ad9def9078fa0c97f93c5098a871.nq.gz
    ├── 8eef165161470613555cdcde0b2d82a0cdb7f7e4.nq.gz
    ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
    ├── 8fef3074efdda4159e82fcd3f2fbf7b351fb634f.nq.gz
    ├── 9031d1e464cbc579b9427b065034a4de4eac3e09.nq.gz
    ├── 9091bb3333237dc920aa011a8a4a99f279cd6e20.nq.gz
    ├── 9140f54286178a07d6a707cef6995bd1fbb57502.nq.gz
    ├── 914da4051dba9a5de078af5936f4860fa6bcde17.nq.gz
    ├── 91759b880b757728ea7c3483cf032bf50abc585d.nq.gz
    ├── 91b5df9506d6f56b9f3370c6f53c625c02acd6f5.nq.gz
    ├── 942419bcf2e3fc8f54342fb810005f90057c25ad.nq.gz
    ├── 9454b0e7168c8e6e78d678393c3ff90f6043b0fb.nq.gz
    ├── 9619998ffc8cb56ad18bc403146928882187792e.nq.gz
    ├── 96dc117fd97f8d07b5c33b989b2701e0e4352031.nq.gz
    ├── 98533725febf396f9a06dbbd77f5fd3a56bf1811.nq.gz
    ├── 99ffbd97bb44e8a7195d56bd555495e9398bce63.nq.gz
    ├── 9a3f894d3ff0c0072a0830b741cb78aa1f93198e.nq.gz
    ├── 9adcfae511867643db9682bbaf37542e5aea1a52.nq.gz
    ├── 9c5e1c10caa9686982651af82fbbc275231173f3.nq.gz
    ├── 9cfea4885dadaf6d1a96834ff1b041505da3d39a.nq.gz
    ├── 9e34ca1e4ea8793dc82d61fa1dc754b8e8cc2ef4.nq.gz
    ├── 9f2b9644f6fd5a815fdc5bd1970a015884575d53.nq.gz
    ├── 9f7abf91ffbae9f4f07f72be262ae093e51a908c.nq.gz
    ├── 9f946164332a8a365d38fa43aa9d2430f6e681f1.nq.gz
    ├── 9ffec1afb7b4da1620a5e91e44ce97183b23c43c.nq.gz
    ├── a06d4f970f2898de2b6847851d4195934a361477.nq.gz
    ├── a0acf5eb68c5cb3cdfda9b99437abec1c082b4ea.nq.gz
    ├── a200e2e6b159d24413258df0c3932957ec48c2c1.nq.gz
    ├── a471d81c90b0ca5b898b6a302fd4bf7be075e799.nq.gz
    ├── a59a07898aa93b687cf9e55cf39355fee85902a3.nq.gz
    ├── a689f3641952bb00b6ea0d11780d5d8575188491.nq.gz
    ├── a6c6d4d8d9c79263eb0d05f90a27120110328f9f.nq.gz
    ├── a72f3728cc06f85b873ffaae9dd802b7a546b196.nq.gz
    ├── a7546acdad7f289efef21ea6f28006630d00e6f6.nq.gz
    └── a755037fff5b5131cc765ed105ac82c79354a65b.nq.gz

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

[scikit-hep/vector](https://github.com/scikit-hep/vector)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*

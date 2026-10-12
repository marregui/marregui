# Miguel Arregui

Senior software engineer, Castellón, Spain. I work on concurrency, JVM performance and database internals. At present I work on [HiveMQ Edge](https://github.com/hivemq/hivemq-edge), an industrial IoT gateway that connects OPC UA and other protocols to MQTT.

## Open source

| Project | What I did | Record |
|---|---|---|
| [questdb/questdb](https://github.com/questdb/questdb) | core database team, 2021–2023: SQL, partitions, storage, ingestion (ILP) | 60 merged PRs, 14th of all contributors, 75 PRs reviewed |
| [crate/crate](https://github.com/crate/crate) | core engine, 2019–2021: SQL functions, constraints, joins, storage-engine checkpoints | 38 merged PRs, 23rd of all contributors, 40 PRs reviewed |
| [hivemq/hivemq-edge](https://github.com/hivemq/hivemq-edge) | 2024–now: OPC UA adapter, browse and import, bridge and queue lifecycle, configuration | 41 merged PRs, 10th of all contributors, 124 PRs reviewed |
| [questdb/questdb-connect](https://github.com/questdb/questdb-connect) | author: SQLAlchemy dialect and Apache Superset integration for QuestDB | 139 commits, first contributor |
| [marregui/jfr](https://github.com/marregui/jfr) | author: `jfrq` asks a Java Flight Recorder recording why a thread stalled, who held the lock, what allocates | JDK 25, Apache-2.0 |
| [marregui/jfrc](https://github.com/marregui/jfrc) | author: `jfrq` ported to Clojure, byte-identical output on 1 229 parity cases | archived |

### Selected changes

| Repo | Change |
|---|---|
| QuestDB | [#3060](https://github.com/questdb/questdb/pull/3060) `SHOW PARTITIONS` and `table_partitions()` |
| QuestDB | [#2650](https://github.com/questdb/questdb/pull/2650), [#2710](https://github.com/questdb/questdb/pull/2710) attach partitions from other volumes as symbolic links, read-only |
| QuestDB | [#3975](https://github.com/questdb/questdb/pull/3975) `information_schema.columns()` |
| QuestDB | [#1251](https://github.com/questdb/questdb/pull/1251), [#1312](https://github.com/questdb/questdb/pull/1312) geohash ingestion and ILP parser edge cases |
| CrateDB | [#9309](https://github.com/crate/crate/pull/9309) advance checkpoints only after operations are persisted |
| CrateDB | [#9831](https://github.com/crate/crate/pull/9831) `CHECK` constraints |
| CrateDB | [#9046](https://github.com/crate/crate/pull/9046) overflow checks in arithmetic |
| CrateDB | [#9629](https://github.com/crate/crate/pull/9629) `JOIN ... USING` |
| HiveMQ Edge | [#1714](https://github.com/hivemq/hivemq-edge/pull/1714) periodic clean-up no longer clears live bridge and sampler queues |
| HiveMQ Edge | [#1759](https://github.com/hivemq/hivemq-edge/pull/1759) OPC UA reads and browses sized to the server's operation limits |
| HiveMQ Edge | [#1444](https://github.com/hivemq/hivemq-edge/pull/1444) bulk device tag browsing and import |

## Before databases

| Period | Where | Work |
|---|---|---|
| 2000–2002 | CERN, ALICE experiment | data acquisition system; M.Sc. thesis |
| — | European Space Agency | research software |
| 2006–2013 (papers) | EMBL-EBI, Cambridge | biomedical text mining: [EBIMed](https://doi.org/10.1093/bioinformatics/btl302), [Whatizit](https://doi.org/10.1093/bioinformatics/btm557) |
| — | RBS, UBS | investment-bank infrastructure |

### Publications

- Protein annotation by EBIMed. *Nature Biotechnology* 24(8), 2006. [doi](https://doi.org/10.1038/nbt0806-902)
- EBIMed — text crunching to gather facts for proteins from Medline. *Bioinformatics* 23(2), 2007. [doi](https://doi.org/10.1093/bioinformatics/btl302)
- Text processing through Web services: calling Whatizit. *Bioinformatics* 24(2), 2008. [doi](https://doi.org/10.1093/bioinformatics/btm557)
- PCorral — interactive mining of protein interactions from MEDLINE. *Database*, 2013. [doi](https://doi.org/10.1093/database/bat030)
- The ALICE DAQ: current status and future challenges. *Computer Physics Communications*, 2001.

[LinkedIn](https://www.linkedin.com/in/marregui)

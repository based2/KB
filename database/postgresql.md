https://www.postgresql.org/

https://www.pgadmin.org/

https://github.com/dhamaniasad/awesome-postgres

https://pgmodeler.io/

https://news.ycombinator.com/item?id=25910277

https://www.slony.info/

# SQL

https://postgres.cz/wiki/PostgreSQL_SQL_Tricks_III

https://news.ycombinator.com/item?id=23516947

https://hashrocket.com/blog/posts/custom-aggregates-in-postgresql

https://www.narrator.ai/blog/postgres-missing-datediff-function/
> https://lobste.rs/s/mxhevf/postgresql_s_missing_datediff_function
> select justify_interval('2021-06-04'::timestamp with time zone - '2020-04-06 23:53:45');

https://www.cybertec-postgresql.com/en/postgresql-limit-vs-fetch-first-rows-with-ties/
> https://news.ycombinator.com/item?id=27845360

https://notes.eatonphil.com/exploring-plpgsql.html

https://philbooth.me/blog/some-useful-non-obvious-postgres-patterns

https://www.dbaprogress.com/postgreslibrary/postgres-scripts
> https://news.ycombinator.com/item?id=36174077

## JSON
https://blog.crunchydata.com/blog/generating-json-directly-from-postgres
> https://news.ycombinator.com/item?id=27848085

http://coussej.github.io/2016/01/14/Replacing-EAV-with-JSONB-in-PostgreSQL/

https://blog.crunchydata.com/blog/better-json-in-postgres-with-postgresql-14
> https://news.ycombinator.com/item?id=27358977

## Types
https://blog.jonudell.net/2021/07/27/working-with-postgres-types/
> https://news.ycombinator.com/item?id=28095264

https://github.com/vramework/postgres-typed
> https://news.ycombinator.com/item?id=28326117

# Performance
https://explain.depesz.com/
> https://news.ycombinator.com/item?id=28771875

https://scalegrid.io/blog/introduction-to-auto-explain-postgres/

https://about.gitlab.com/blog/2021/09/29/why-we-spent-the-last-month-eliminating-postgresql-subtransactions/
> https://news.ycombinator.com/item?id=28730225
 
https://www.migops.com/blog/2021/04/09/pgbackrest-the-best-postgres-backup-tool-with-a-very-active-community/#Conclusion

https://github.com/ankane/pgvector vector similarity search
> https://news.ycombinator.com/item?id=26903105

http://eradman.com/ephemeralpg/

https://elephant-shed.io/

https://www.cybertec-postgresql.com/en/postgresql-detecting-slow-queries-quickly/

https://github.com/plv8/plv8

https://github.com/agroal/pgagroal High-performance protocol-native connection pool
> https://news.ycombinator.com/item?id=29303627

https://ardentperf.com/2022/07/16/postgresql-performance-puzzle/
> https://lobste.rs/s/k42r7b/postgresql_performance_puzzle

## Index
https://stackoverflow.com/questions/970562/postgres-and-indexes-on-foreign-keys-and-primary-keys

http://leopard.in.ua/2015/04/13/postgresql-indexes/

https://www.i-programmer.info/news/84-database/14855-a-deep-dive-into-postgresql-indexes.html

https://blog.crunchydata.com/blog/postgres-indexes-for-newbies
> https://news.ycombinator.com/item?id=30001964

https://github.com/supabase/index_advisor
> https://news.ycombinator.com/item?id=40028111

https://news.ycombinator.com/item?id=46751826

## Analysis
https://blog.crunchydata.com/blog/get-started-with-explain-analyze

https://github.com/marklit/datafluent_pg

https://www.percona.com/blog/improve-postgresql-query-performance-insights-with-pg_stat_monitor/

https://brandur.org/idempotency-keys

https://www.pgmustard.com/

### Debug
https://iamsafts.com/posts/postgres-gin-performance/
> https://news.ycombinator.com/item?id=27152507

https://www.cybertec-postgresql.com/en/how-to-interpret-postgresql-explain-analyze-output/

https://dev.to/jbranchaud/beware-the-missing-foreign-key-index-a-postgres-performance-gotcha-3d5i

# Admin
https://supabase.io/blog/2021/07/01/roles-postgres-hooks
> https://news.ycombinator.com/item?id=27712800

# Extensions
https://age.apache.org/# Graph

https://supabase.com/blog/2021/12/03/pg-graphql
> https://news.ycombinator.com/item?id=29430720
> https://www.getmotoradmin.com/supabase
> > https://news.ycombinator.com/item?id=30100077
> > > https://directus.io/

https://github.com/solidsnack/GraphpostgresQL

https://github.com/arkhipov/temporal_tables Table that records the period of time when a row is valid.

https://github.com/nearform/temporal_tables
> https://news.ycombinator.com/item?id=26748096

https://depth-first.com/articles/2021/09/07/a-rust-postgresql-extension-for-cas-numbers/

https://postgrest.org/en/v9.0/releases/v9.0.0.html
> https://news.ycombinator.com/item?id=29389576
> https://github.com/PostgREST/postgrest

https://www.pgelephant.com/blog/pg-stat-insights

# Security
https://goteleport.com/blog/securing-postgres-postgresql/
> https://news.ycombinator.com/item?id=26674756

https://www.cisecurity.org/benchmark/postgresql/

https://www.tangramvision.com/blog/hands-on-with-postgresql-authorization-part-2-row-level-security

https://github.com/inqueryio/inquery
> https://news.ycombinator.com/item?id=35082508

https://imfeld.dev/notes/postgresql_row_level_security
> https://news.ycombinator.com/item?id=35587196

https://postgrest.org/en/stable/references/admin.html

https://www.pgaudit.org/
> https://github.com/pgaudit/pgaudit
> > https://news.ycombinator.com/item?id=37082827

https://www.heap.io/blog/how-postgres-audit-tables-saved-us-from-taking-down-production

https://rlopzc.com/posts/securing-your-postgresql-db-with-roles--privileges/
> https://news.ycombinator.com/item?id=37100641

https://www.hezmatt.org/~mpalmer/blog/2023/11/07/postgresql-encryption-options.html
> https://news.ycombinator.com/item?id=38173141

http://peter.eisentraut.org/blog/2023/12/05/postgresql-and-fips-mode
> https://news.ycombinator.com/item?id=38529522

https://telablog.com/postgresql-protect-tables-against-accidental-deletion
> https://old.reddit.com/r/programming/comments/1b68nmy/postgresql_protect_tables_against_accidental/

https://news.ycombinator.com/item?id=42694732

# Operations

https://heap.io/blog/how-postgres-audit-tables-saved-us-from-taking-down-production

https://www.highgo.ca/2021/01/27/avoiding-identifying-and-dealing-with-postgresql-database-corruption-part-1/

https://www.mutuallyhuman.com/blog/how-a-read-query-can-write-to-disk-a-postgresql-story/ work_mem
> https://news.ycombinator.com/item?id=29056405
> > https://wiki.postgresql.org/wiki/Tuning_Your_PostgreSQL_Server

https://incident.io/blog/one-two-skip-a-few Postgres sequences can skip 32 unexpectedly
> https://news.ycombinator.com/item?id=27843084

## Audit
https://supabase.com/blog/2022/03/08/audit
> https://news.ycombinator.com/item?id=30615470
> https://www.reddit.com/r/programming/comments/tpj6zk/postgres_auditing_in_150_lines_of_sql/

## Backup
https://xata.io/blog/behind-the-scenes-speeding-up-pgstream-snapshots-for-postgresql
> https://news.ycombinator.com/item?id=44473888

https://abishekmuthian.com/backup-postgresql-to-cloud/

https://pganalyze.com/blog/5mins-postgres-17-incremental-backups
> https://news.ycombinator.com/item?id=38961463

## OOM
https://info.crunchydata.com/blog/deep-postgresql-thoughts-the-linux-assassin

# Migration
https://github.com/sastraxi/pgsh

https://github.com/djrobstep/migra
> https://news.ycombinator.com/item?id=16673526
> https://news.ycombinator.com/item?id=30464882

https://blog.discourse.org/2021/04/standing-on-the-shoulders-of-a-giant-elephant/

https://www.paulox.net/2021/05/28/upgrading-postgresql-from-version-12-to-13-on-ubuntu-21-04-focal-fossa/

https://engineering.theblueground.com/blog/zero-downtime-postgres-migration-done-right/

https://fabianlindfors.se/blog/schema-migrations-in-postgres/
> https://news.ycombinator.com/item?id=27531934
> > https://dba.stackexchange.com/questions/195104/postgres-group-by-id-works-on-table-directly-but-not-on-identical-view

https://www.migops.com/blog/2021/08/27/announcing-pg_dbms_job-in-postgresql-for-oracle-dbms_job-compatibility/

https://news.ycombinator.com/item?id=28707577
> https://vericred.com/how-we-migrated-a-1tb-database-from-heroku-to-aws-aurora-with-almost-no-downtime/

https://babelfishpg.org/
> https://github.com/babelfish-for-postgresql SQL server compatibility layer by AWS

https://fabianlindfors.se/blog/schema-migrations-in-postgres-using-reshape/
> https://news.ycombinator.com/item?id=29825520

https://github.com/fabianlindfors/reshape

https://github.com/bikeshedder/tusker

https://retool.com/blog/how-we-upgraded-postgresql-database/
> https://news.ycombinator.com/item?id=31084147

https://github.com/michelp/metagration

https://www.crunchydata.com/blog/postgres-migration-pitstop-collations

https://news.ycombinator.com/item?id=39860769

https://news.ycombinator.com/item?id=43989497

https://news.ycombinator.com/item?id=45224028

https://ananthakumaran.in/2025/11/02/moving-tables-across-postgres-instances.html
> https://news.ycombinator.com/item?id=45788086

# HA
https://dzone.com/articles/managing-high-availability-in-postgresql-part-i

https://github.com/zalando/patroni

https://fly.io/blog/globally-distributed-postgres/
> https://news.ycombinator.com/item?id=27690950

https://www.notion.so/blog/sharding-postgres-at-notion
> https://news.ycombinator.com/item?id=28776786

https://tapoueh.org/blog/2021/12/postgres-ha-roles-are-dynamic

https://github.com/vitabaks/postgresql_cluster
> https://news.ycombinator.com/item?id=36426128

https://xata.io/blog/geo-distributed-postgres
> https://news.ycombinator.com/item?id=40542940

# Restoration
https://www.highgo.ca/2023/05/09/various-restoration-techniques-using-postgresql-point-in-time-recovery/

# Generator
https://github.com/vramework/schemats Postgres to TypeScript Interfaces and Enums
> https://news.ycombinator.com/item?id=27570058

# Extensions
https://github.com/jie123108/imgsmlr-server

https://news.ycombinator.com/item?id=39704706

# Search
https://about.sourcegraph.com/blog/postgres-text-search-balancing-query-time-and-relevancy/
> https://news.ycombinator.com/item?id=28873779

https://supabase.com/blog/postgres-full-text-search-vs-the-rest
> https://news.ycombinator.com/item?id=33203370

# Queue
https://spin.atomicobject.com/2021/02/04/redis-postgresql/
> https://news.ycombinator.com/item?id=27482243

# Realtime
https://github.com/supabase/realtime Listen to your to PostgreSQL database in realtime via WebSockets (Erlang/Elixir)
> https://news.ycombinator.com/item?id=26968449

# Proxy

## NoSQL
https://www.mangodb.io/
> https://news.ycombinator.com/item?id=29071623

# Container
https://www.kubegres.io/
> https://www.reddit.com/r/PostgreSQL/comments/mqrsbn/kubegres_is_a_kubernetes_operator_for_postgresql/

https://www.postgresql.org/about/news/kubegres-is-available-as-open-source-2197/
> https://news.ycombinator.com/item?id=28758162

https://github.com/CrunchyData/postgres-operator
> https://news.ycombinator.com/item?id=31882256

https://github.com/justinclift/docker-pgautoupgrade

https://news.ycombinator.com/item?id=39960537 open-sourced the in-memory PostgreSQL I built at work for E2E tests

## K8s
https://stackgres.io/
> https://news.ycombinator.com/item?id=28865432

https://blog.crunchydata.com/blog/postgresql-14-on-kubernetes
> https://news.ycombinator.com/item?id=28767637

https://stackgres.io/blog/easily-running-babelfish-for-postgresql-on-kubernetes/

https://www.enterprisedb.com/blog/introducing-cloudnativepg-new-open-source-kubernetes-operator-postgres
> https://news.ycombinator.com/item?id=31366983

https://nhost.io/blog/individual-postgres-instances
> https://news.ycombinator.com/item?id=32986325

https://thenewstack.io/implement-postgres-on-kubernetes-with-ondat-and-suse-rancher/

https://ryan-schachte.com/blog/ha_postgres_zolando/

# Rest
https://postgrest.org/en/stable/how-tos/providing-html-content-using-htmx.html

# Web
https://blog.val.town/blog/migrating-from-supabase
> https://news.ycombinator.com/item?id=36004925

# SaaS
https://supabase.com/blog/postgres-on-fly-by-supabase
> https://news.ycombinator.com/item?id=38653212

# ML
https://news.ycombinator.com/item?id=41224286

https://news.ycombinator.com/item?id=43356039

# Incidents
https://www.theregister.com/2025/02/14/postgresql_bug_treasury/
> https://news.ycombinator.com/item?id=43048882

https://jesipow.com/blog/postgres-reads-cause-writes/
> https://news.ycombinator.com/item?id=42485505

# News
https://hexacluster.ai/blog/row-level-and-column-level-security-oracle-vs-postgresql

https://www.youtube.com/watch?v=QLb3nhIy2Lc
> https://news.ycombinator.com/item?id=46908700
> https://pganalyze.com/blog/5mins-postgres-19-better-planner-hints

https://stormatics.tech/blogs/unlocking-high-performance-postgresql-key-memory-optimizations
> https://news.ycombinator.com/item?id=46853261

https://github.com/DataDog/pg_tracing
> https://news.ycombinator.com/item?id=46804009

https://news.ycombinator.com/item?id=46725300

https://github.com/vnvo/pgwire-replication
> https://news.ycombinator.com/item?id=46574277

https://tanelpoder.com/posts/generate-qr-code-with-pure-sql-in-postgres/

https://github.com/timescale/pgvectorscale
> https://news.ycombinator.com/item?id=46379765

https://boringsql.com/posts/instant-database-clones/
> https://news.ycombinator.com/item?id=46363360

https://github.com/CrystallineCore/Biscuit index for fast pattern matching LIKE queries
> https://news.ycombinator.com/item?id=46289884

https://news.ycombinator.com/item?id=46292148

https://news.ycombinator.com/item?id=46272487

https://github.com/ayarotsky/diesel-guard

https://habr.com/en/companies/postgrespro/articles/504498/ Locks
> https://news.ycombinator.com/item?id=46182496

https://pglite.dev/
> https://news.ycombinator.com/item?id=46146133

https://github.com/sirrodgepodge/rrule_plpgsql rscale
> https://news.ycombinator.com/item?id=45915339

https://github.com/randoneering/pgFirstAid

https://boringsql.com/posts/regresql-testing-queries/
> https://news.ycombinator.com/item?id=45924619

https://news.ycombinator.com/item?id=45548125

https://news.ycombinator.com/item?id=45593358

https://www.crunchydata.com/blog/is-postgres-read-heavy-or-write-heavy-and-why-should-you-care

https://news.ycombinator.com/item?id=45593358

https://news.ycombinator.com/item?id=45533870

https://multigres.com/

https://neon.com/blog/implementing-a-kalman-filter-in-postgres-to-smooth-gps-data
> https://news.ycombinator.com/item?id=45389589

https://news.ycombinator.com/item?id=45412494 async

https://news.ycombinator.com/item?id=45405055

https://news.ycombinator.com/item?id=45323008

https://news.ycombinator.com/item?id=45248868

https://news.ycombinator.com/item?id=45214209

https://www.pgedge.com/blog/pgedge-goes-open-source
> https://news.ycombinator.com/item?id=45209065

https://news.ycombinator.com/item?id=44867374

https://news.ycombinator.com/item?id=44783368

https://www.paradedb.com/blog/lsm_trees_in_postgres pg_search
> https://news.ycombinator.com/item?id=44633933

https://news.ycombinator.com/item?id=44570389

https://news.ycombinator.com/item?id=44490510

https://news.ycombinator.com/item?id=44134728

https://github.com/pgdogdev/pgdog Horizontal scaling for PostgreSQL with automatic sharding
> https://news.ycombinator.com/item?id=44099187

https://news.ycombinator.com/item?id=44099187

https://news.ycombinator.com/item?id=44073588

https://news.ycombinator.com/item?id=44016289

https://news.ycombinator.com/item?id=44005899

https://xata.io/blog/xata-postgres-with-data-branching-and-pii-anonymization

https://github.com/cybertec-postgresql/pgwatch

https://news.ycombinator.com/item?id=43916577

https://news.ycombinator.com/item?id=43883732

https://github.com/pgdogdev/pgdog

https://news.ycombinator.com/item?id=43693326

https://news.ycombinator.com/item?id=43722981

https://github.com/supabase-community/postgres-language-server
> https://news.ycombinator.com/item?id=43513996

https://news.ycombinator.com/item?id=43398148

◊https://news.ycombinator.com/item?id=43380622

https://news.ycombinator.com/item?id=43364668

https://news.ycombinator.com/item?id=43270712

https://news.ycombinator.com/item?id=43177931

https://news.ycombinator.com/item?id=43111294

https://news.ycombinator.com/item?id=43107394

https://github.com/orf/locksmith

https://github.com/nexsol-technologies/pgassistant
> https://news.ycombinator.com/item?id=43026036

https://news.ycombinator.com/item?id=43012294

https://news.ycombinator.com/item?id=42991222

https://news.ycombinator.com/item?id=42867657

https://news.ycombinator.com/item?id=42880585

https://news.ycombinator.com/item?id=42881012

https://blog.sequinstream.com/using-watermarks-to-coordinate-change-data-capture-in-postgres/

https://news.ycombinator.com/item?id=42582203 cdc

https://news.ycombinator.com/item?id=42388973

https://news.ycombinator.com/item?id=42288258

https://news.ycombinator.com/item?id=42321596

https://news.ycombinator.com/item?id=42034237

https://news.ycombinator.com/item?id=41984184

https://news.ycombinator.com/item?id=41873957

https://news.ycombinator.com/item?id=41818446

https://news.ycombinator.com/item?id=41743464

https://news.ycombinator.com/item?id=41657986 17

https://www.crunchydata.com/blog/window-functions-for-data-analysis-with-postgres

https://github.com/achristmascarl/rainfrog TUI
> https://news.ycombinator.com/item?id=41563100

https://news.ycombinator.com/item?id=41457156

https://news.ycombinator.com/item?id=41428217

https://news.ycombinator.com/item?id=41415651

https://motherduck.com/blog/pg_duckdb-postgresql-extension-for-duckdb-motherduck/
> https://news.ycombinator.com/item?id=41275751

https://news.ycombinator.com/item?id=41232621

https://news.ycombinator.com/item?id=41228022

https://news.ycombinator.com/item?id=41209994

https://news.ycombinator.com/item?id=41184952

https://news.ycombinator.com/item?id=41159180

https://github.com/commandprompt/pgmanage
> https://news.ycombinator.com/item?id=41024576

https://news.ycombinator.com/item?id=41035183

https://news.ycombinator.com/item?id=40997826

https://xata.io/blog/migrations-and-exclusive-locks

https://news.ycombinator.com/item?id=40702985

https://news.ycombinator.com/item?id=40671858

https://news.ycombinator.com/item?id=40625656

https://news.ycombinator.com/item?id=40639742

https://news.ycombinator.com/item?id=40623504

https://github.com/sushrut141/pg_analytica Speed up queries by exporting tables to columnar format
> https://news.ycombinator.com/item?id=40617877

https://blog.peerdb.io/simple-postgres-to-clickhouse-replication-featuring-minio

http://rhaas.blogspot.com/2024/05/hacking-on-postgresql-is-really-hard.html

https://news.ycombinator.com/item?id=40194976

https://news.ycombinator.com/item?id=40163950

https://news.ycombinator.com/item?id=40169992

https://news.ycombinator.com/item?id=40160467

https://news.ycombinator.com/item?id=40060123

https://news.ycombinator.com/item?id=40083748

https://news.ycombinator.com/item?id=39965028

https://leontrolski.github.io/pglockpy.html

https://tembo.io/blog/managed-postgres-rust
> https://news.ycombinator.com/item?id=39967199

https://github.com/Florents-Tselai/pgJQ

https://news.ycombinator.com/item?id=39741956

https://www.pinaraf.info/2024/03/look-ma-i-wrote-a-new-jit-compiler-for-postgresql/
> https://news.ycombinator.com/item?id=39742916

https://github.com/ossc-db/pg_hint_plan
> https://news.ycombinator.com/item?id=39712211

https://kviklet.dev/blog/parsing-the-postgres-protocol/
> https://news.ycombinator.com/item?id=39706582

https://news.ycombinator.com/item?id=39619204

https://news.ycombinator.com/item?id=39593384

https://exaspark.medium.com/the-ultimate-guide-to-postgresql-data-change-tracking-c3fa88779572 CDC
> https://news.ycombinator.com/item?id=39488719

https://github.com/electric-sql/pglite wasm
> https://news.ycombinator.com/item?id=39477457

https://news.ycombinator.com/item?id=39458636

https://github.com/kaspermarstal/plprql
> https://news.ycombinator.com/item?id=39428609

https://github.com/GreenmaskIO/greenmask Dump and Obfuscation Tool - go aslv2
> https://news.ycombinator.com/item?id=39409159

https://hypirion.com/musings/implementing-system-versioned-tables-in-postgres
> https://news.ycombinator.com/item?id=39285752

https://www.citusdata.com/blog/2024/02/08/whats-new-in-postgres-16-query-planner-optimizer/
> https://news.ycombinator.com/item?id=39310837

https://gds.blog.gov.uk/2024/01/17/how-we-migrated-our-postgresql-database-with-11-seconds-downtime/
> https://news.ycombinator.com/item?id=39048317

https://wiki.postgresql.org/wiki/Operations_cheat_sheet
> https://news.ycombinator.com/item?id=39042456

https://elixirforum.com/t/partitioning-postgres-tables-by-timestamp-based-uuids/60916
> https://news.ycombinator.com/item?id=38965965

https://pganalyze.com/blog/exploring-postgres-vacuum-with-vacuum-simulator

https://github.com/ossc-db/pg_rman
> https://news.ycombinator.com/item?id=38915421

https://github.com/paradedb/paradedb
> https://news.ycombinator.com/item?id=38847571

https://jkatz05.com/post/postgres/postgresql-2024/
> https://news.ycombinator.com/item?id=38848001

https://news.ycombinator.com/item?id=38815150

https://patrick.engineering/posts/postgres-internals/
> https://news.ycombinator.com/item?id=38781442

https://www.theregister.com/2023/12/26/michael_stonebraker_feature/
> https://news.ycombinator.com/item?id=38777870

https://blog.peerdb.io/real-time-change-data-capture-from-postgres-16-read-replicas

https://www.phoronix.com/news/PostgreSQL-Incremental-Backups

https://www.thenile.dev/blog/transaction-isolation-postgres
> https://news.ycombinator.com/item?id=38684447

https://news.ycombinator.com/item?id=38664412

https://knock.app/blog/zero-downtime-postgres-upgrades
> https://news.ycombinator.com/item?id=38616181

https://supabase.com/blog/postgres-language-server-implementing-parser
> https://news.ycombinator.com/item?id=38568252

https://github.com/nearform/temporal_tables

https://news.ycombinator.com/item?id=38463731

https://news.ycombinator.com/item?id=38417391

https://news.ycombinator.com/item?id=38398305

https://pganalyze.com/blog/automatic-indexing-system-postgres-pganalyze-indexing-engine
> https://news.ycombinator.com/item?id=38300297

https://robertrode.com/2023/11/15/operating-an-entire-company-on-a-minimal-two-core-postgresql-instance-query-optimization-insights-part-1.html
> https://news.ycombinator.com/item?id=38276727

https://github.com/eugene-khyst/postgresql-event-sourcing
> https://news.ycombinator.com/item?id=38084098 event sourcing java

https://www.citusdata.com/blog/2023/10/26/making-postgres-tick-new-features-in-pg-cron/
> https://news.ycombinator.com/item?id=38029671

https://news.ycombinator.com/item?id=38014812

https://old.reddit.com/r/scala/comments/17ac10z/announcing_typo_typed_postgresql_integration_for/

https://www.specfy.io/blog/7-git-like-versioning-in-postgres
> https://news.ycombinator.com/item?id=37955617

https://github.com/omnigres/omnigres
> https://news.ycombinator.com/item?id=37893080

https://github.com/omnigres/omnigres/tree/master/pg_yregress
> https://news.ycombinator.com/item?id=37892061

https://news.ycombinator.com/item?id=37879216

https://tembo.io/blog/introducing-pg-later/
> https://news.ycombinator.com/item?id=37172689

https://blog.benthem.io/2023/08/16/what-actually-happens-when-you-run-copy-in-postgres.html
> https://news.ycombinator.com/item?id=37164115

https://supabase.com/blog/supavisor-1-million
> https://news.ycombinator.com/item?id=37089925

https://supabase.com/blog/supabase-local-dev
> https://news.ycombinator.com/item?id=37059400

https://github.com/supabase/postgres_lsp
> https://news.ycombinator.com/item?id=37020610

https://hydra-so.notion.site/Hydra-1-0-beta-318504444825401e8ce21796dcadd589
> https://news.ycombinator.com/item?id=36987920

https://neon.tech/blog/pg_embedding-on-disk-hnsw-index vector similarity search
> https://news.ycombinator.com/item?id=36989503

https://www.endpointdev.com/blog/2012/06/logstatement-postgres-all-full-logging/
> https://lobste.rs/s/e6g0fw/postgres_log_statement_all_should_be_your

https://www.citusdata.com/blog/2023/07/31/schema-based-sharding-comes-to-postgres-with-citus/
> https://news.ycombinator.com/item?id=36947711

https://fragland.dev/a-guide-to-table-partitioning-with-postgresql-12

https://twitter.com/BdKozlovski/status/1684098236426878976
> https://news.ycombinator.com/item?id=36888496

https://www.crunchydata.com/blog/remote-access-anything-from-postgres

https://news.ycombinator.com/item?id=36922957

https://hakibenita.com/postgresql-correlation-brin-multi-minmax
> https://news.ycombinator.com/item?id=36889365

https://news.ycombinator.com/item?id=36895220

https://www.kylehailey.com/post/postgres-partition-pains-lockmanager-waits

https://www.citusdata.com/blog/2023/07/18/citus-12-schema-based-sharding-for-postgres/
> https://news.ycombinator.com/item?id=36777053

https://www.orioledata.com/blog/no-more-vacuum-in-postgresql/
> https://news.ycombinator.com/item?id=36740921

https://www.timescale.com/blog/nearest-neighbor-indexes-what-are-ivfflat-indexes-in-pgvector-and-how-do-they-work/

https://cloud.google.com/blog/products/databases/announcing-vector-support-in-postgresql-services-to-power-ai-enabled-applications?hl=en
> https://news.ycombinator.com/item?id=36551936

https://lwn.net/SubscriberLink/934940/3abb2d4086680b78/
> https://lobste.rs/s/ndgtuv/postgresql_reconsiders_its_process

https://www.2ndquadrant.com/en/blog/what-is-select-skip-locked-for-in-postgresql-9-5/

https://github.com/vishesh92/pg-primer
> https://news.ycombinator.com/item?id=36409340

https://github.com/shayonj/pg_easy_replicate
> https://news.ycombinator.com/item?id=36405761

https://www.cybertec-postgresql.com/en/unexpected-downsides-of-uuid-keys-in-postgresql/
> https://news.ycombinator.com/item?id=36429986

https://nanovms.com/dev/tutorials/running-postgres-as-a-unikernel
> https://news.ycombinator.com/item?id=36420890

https://postgresml.org/blog/making-postgres-30-percent-faster-in-production

https://www.citusdata.com/blog/2018/02/15/when-postgresql-blocks/

https://www.postgresql.org/message-id/flat/31cc6df9-53fe-3cd9-af5b-ac0d801163f4@iki.fi
> https://news.ycombinator.com/item?id=36288617

https://github.com/centerofci/mathesar ui

https://rhaas.blogspot.com/2023/06/the-postgresql-documentation-and.html
> https://news.ycombinator.com/item?id=36328466

https://wiki.postgresql.org/wiki/Don%27t_Do_This
> https://news.ycombinator.com/item?id=36147624

https://manishrjain.com/running-postgresql-ubuntu-non-postgres-user

https://www.postgresql.org/about/news/postgresql-16-beta-1-released-2643/
> https://news.ycombinator.com/item?id=36070261

https://hakibenita.com/the-many-faces-of-distinct-in-postgre-sql 2017
> https://news.ycombinator.com/item?id=36029221

https://www.crunchydata.com/blog/pgvector-performance-for-developers

https://github.com/AdmTal/PostgreSQL-Query-Lock-Explainer
> https://news.ycombinator.com/item?id=35981238

https://blog.mastermind.dev/indexes-in-postgresql
> https://news.ycombinator.com/item?id=35978757

https://medium.com/the-prefect-blog/more-memory-more-problems-b182d7807e3c

https://ottertune.com/blog/how-to-fix-slow-postgresql-queries/
> https://news.ycombinator.com/item?id=35963572

https://ottertune.com/blog/the-part-of-postgresql-we-hate-the-most/
> https://news.ycombinator.com/item?id=35716963

https://philbooth.me/blog/nine-ways-to-shoot-yourself-in-the-foot-with-postgresql
> https://news.ycombinator.com/item?id=35684220

https://www.postgresql.org/docs/current/ecpg.html
> https://news.ycombinator.com/item?id=35598251

https://database.dev/
> https://news.ycombinator.com/item?id=35570758

https://tcdi.github.io/plrust/plrust.html
> https://news.ycombinator.com/item?id=35501065 PL/rust

https://pgdash.io/blog/postgres-replication-gotchas.html
> https://news.ycombinator.com/item?id=35478421

https://www.infoq.com/articles/wonders-of-postgres-logical-decoding-messages/
> https://news.ycombinator.com/item?id=35393040

https://cloud.google.com/blog/products/databases/run-alloydb-anywhere?hl=en
> https://news.ycombinator.com/item?id=35357252

https://www.postgresql.fastware.com/blog/inside-logical-replication-in-postgresql
> https://news.ycombinator.com/item?id=35203571

https://blog.hydra.so/blog/2023-03-02-columnar-updates-and-deletes

https://www.crunchydata.com/blog/postgres-query-optimization-left-join-vs-union-all

https://news.ycombinator.com/item?id=34903454

https://psql-tips.org/psql_tips_080.html
> https://news.ycombinator.com/item?id=34909670

https://www.crunchydata.com/blog/postgres-wal-files-and-sequuence-numbers
> https://news.ycombinator.com/item?id=34815464

https://supabase.com/blog/type-constraints-in-65-lines-of-sql
> https://news.ycombinator.com/item?id=34835063

https://pganalyze.com/blog/pg-stat-io
> https://news.ycombinator.com/item?id=34836683

https://www.crunchydata.com/blog/postgresl-unlogged-tables
> https://news.ycombinator.com/item?id=34846366

https://www.crunchydata.com/blog/five-tips-for-a-healthier-postgres-database-in-the-new-year
> https://news.ycombinator.com/item?id=34734021

https://www.crunchydata.com/blog/using-postgres-filter

https://gilslotd.com/blog/features_id_postgresql
> https://news.ycombinator.com/item?id=34560332

https://blog.chiselstrike.com/sqlite-based-databases-on-the-postgres-protocol-yes-we-can-358e61171d65
> https://news.ycombinator.com/item?id=34517474

https://rhaas.blogspot.com/2023/01/surviving-without-superuser-coming-to.html

https://supabase.com/blog/choosing-a-postgres-primary-key
> https://news.ycombinator.com/item?id=34451344

https://www.crunchydata.com/blog/state-of-json-in-postgres-2022

https://postgrest.org/en/stable/index.html
> https://news.ycombinator.com/item?id=34172205

https://www.timescale.com/blog/12-days-of-postgresql-tools-and-projects/
> https://news.ycombinator.com/item?id=34067247

https://supabase.com/blog/postgres-foreign-data-wrappers-rust
> https://news.ycombinator.com/item?id=34001493

https://github.com/IvorySQL/IvorySQL Open Source Oracle Compatible PostgreSQL
> https://news.ycombinator.com/item?id=34007403

https://www.amazingcto.com/postgres-for-everything/
> https://news.ycombinator.com/item?id=33934139

https://news.ycombinator.com/item?id=33899482

https://neon.tech/blog/time-travel-with-postgres/
> https://news.ycombinator.com/item?id=33897790

https://neon.tech/blog/serverless-driver-for-postgres/
> https://news.ycombinator.com/item?id=33909616

https://www.cybertec-postgresql.com/en/explain-that-parameterized-statement/

https://postgresml.org/blog/scaling-postgresml-to-one-million-requests-per-second/
> https://news.ycombinator.com/item?id=33518443

https://github.com/patrkris/pisk
> https://news.ycombinator.com/item?id=33449475

https://www.crunchydata.com/blog/challenging-postgres-terminology
> https://news.ycombinator.com/item?id=33462983

https://www.cybertec-postgresql.com/en/multiranges-in-postgresql-14/
> https://news.ycombinator.com/item?id=33353719

https://event-driven.io/en/push_based_outbox_pattern_with_postgres_logical_replication/
> https://news.ycombinator.com/item?id=33370649

https://webapp.io/blog/postgres-query-speedups/

https://www.crunchydata.com/blog/a-look-at-postgres-15-merge-command-with-examples
> https://news.ycombinator.com/item?id=33236780

https://event-driven.io/en/push_based_outbox_pattern_with_postgres_logical_replication/

https://www.postgresql.org/about/news/postgresql-15-released-2526/
> https://news.ycombinator.com/item?id=33190456
> https://www.postgresql.org/docs/current/release-15.html

https://supabase.com/blog/postgres-wasm
> https://news.ycombinator.com/item?id=33067962

https://www.cybertec-postgresql.com/en/products/pg_squeeze/
> https://news.ycombinator.com/item?id=33081709

https://www.timescale.com/blog/how-postgresql-views-and-materialized-views-work-and-how-they-influenced-timescaledb-continuous-aggregates/

https://blog.cleverelephant.ca/2022/10/postgresql-links.html

https://www.postgresql.org/about/news/postgresql-15-rc-1-released-2516/

https://pgmoneta.github.io/ Backup/Restore solution

https://www.timescale.com/blog/postgresql-timescaledb-1000x-faster-queries-90-data-compression-and-much-more/
> https://news.ycombinator.com/item?id=32940701

https://blog.xa0.de/post/Extending-supabase-with-your-own-backend%20---%20its-supa-easy%21/

https://www.crunchydata.com/blog/postgres-data-flow
> https://news.ycombinator.com/item?id=32900123

https://gocardless.com/blog/debugging-the-postgres-query-planner/
> https://news.ycombinator.com/item?id=32834182

https://it.badykov.com/blog/2022/09/12/simple-and-usefull-postgresql-features/
> https://www.reddit.com/r/programming/comments/xcgfkt/6_simple_and_useful_postgresql_features_that_i/

https://www.citusdata.com/blog/2022/09/12/distributed-postgres-goes-full-open-source-with-citus/

https://github.com/supabase/pg_netstat
> https://news.ycombinator.com/item?id=32823589

https://github.com/t3hmrman/pg_idkit uuid
> https://news.ycombinator.com/item?id=32798821

https://kristiandupont.github.io/kanel/

https://www.postgresql.org/docs/current/plpython.html

https://www.percona.com/blog/postgresql-15-stats-collector-gone-whats-new/
> https://news.ycombinator.com/item?id=32632715

https://github.com/fcoury/oxide Teach your PostgreSQL database how to speak MongoDB Wire Protocol.
> https://news.ycombinator.com/item?id=32276304

https://www.timescale.com/blog/what-postgresql-contributor-heikki-linnakangas-has-to-say-about-the-state-of-postgresql-2022/

https://www.thenile.dev/blog/multi-tenant-rls
> https://news.ycombinator.com/item?id=32241820

https://postgrespro.com/community/books/internals

https://supabase.com/blog/2022/07/18/seen-by-in-postgresql
> https://news.ycombinator.com/item?id=32138790

https://supabase.com/blog/2022/06/28/partial-postgresql-data-dumps-with-rls

https://andreas.scherbaum.la/blog/archives/1116-PostgreSQL-Upgrades-are-hard!.html#_content
> https://news.ycombinator.com/item?id=31873063

https://pganalyze.com/blog/automatic-indexing-system-postgres-pganalyze-indexing-engine

https://www.postgresql.org/about/news/postgresql-144-released-2470/

https://www.crunchydata.com/blog/indexes-selectivity-and-statistics

https://www.timescale.com/blog/how-to-write-better-queries-for-time-series-data-analysis-using-custom-sql-functions/

https://adamj.eu/tech/2022/06/20/how-to-find-and-stop-running-queries-on-postgresql/
> https://news.ycombinator.com/item?id=31809394

https://github.com/citusdata/citus/commit/184c7c0bce6b7bca61d25b828855fac5fba64816
> https://news.ycombinator.com/item?id=31770348
> https://www.reddit.com/r/programming/comments/velg5w/citus_11_for_postgres_goes_fully_open_source_with/

https://www.migops.com/blog/2022/06/09/important-postgresql-14-update-to-avoid-silent-corruption-of-indexes/
> https://news.ycombinator.com/item?id=31687782

https://github.com/neondatabase/neon serverless open source alternative to AWS Aurora Postgres

https://cloud.google.com/blog/products/databases/alloydb-for-postgresql-columnar-engine

https://www.crunchydata.com/blog/postgres-query-optimization-left-join-vs-union-all

https://www.citusdata.com/blog/2022/05/19/speeding-up-sort-performance-in-postgres-15/
> https://news.ycombinator.com/item?id=31444558

https://www.postgresql.org/docs/devel/release-15.html
> https://news.ycombinator.com/item?id=31423536

https://pganalyze.com/blog/how-postgres-chooses-index
> https://news.ycombinator.com/item?id=31115492

https://splitmind.dev/posts/generate-creds-postgres-vault-with-golang/
> https://news.ycombinator.com/item?id=31072936

https://bytebase.com/blog/database-migration-sqlite-to-postgresql
> https://news.ycombinator.com/item?id=31038614

https://postgrespro.com/blog/pgsql/5968022 Locks in PostgreSQL: 4. Locks in memory

https://github.com/postgres-ai/database-lab-engine/releases/tag/v3.1.0

https://www.highgo.ca/2021/07/23/the-amazing-buffer-tag-in-postgresql/

https://blog.crunchydata.com/blog/announcing-postgres-container-apps-easy-deploy-postgres-apps
> https://news.ycombinator.com/item?id=30867644

https://github.com/vitabaks/postgresql_cluster

https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=7103ebb7aae8ab8076b7e85f335ceb8fe799097c

https://github.com/gurjeet/pg_plan_guarantee
> https://news.ycombinator.com/item?id=30825069

https://github.com/porsager/postgres js
> https://news.ycombinator.com/item?id=30794332

https://eggerapps.at/postico/ A Modern PostgreSQL Client for the Mac
> https://news.ycombinator.com/item?id=30798274

https://www.tangramvision.com/blog/hands-on-with-postgresql-authorization-part-2-row-level-security
> https://news.ycombinator.com/item?id=30700899

https://arctype.com/blog/postgresql-hooks/

https://news.ycombinator.com/item?id=30629430 A word used only by Postgres developers

https://github.com/ossc-db/pg_hint_plan
> https://news.ycombinator.com/item?id=30614154

https://www.shayon.dev/post/2022/47/pg-osc-zero-downtime-schema-changes-in-postgresql/
> https://news.ycombinator.com/item?id=30579847

https://www.yagiz.co/postgresql-index-performance/

https://gist.github.com/jcoleman/1e6ad1bf8de454c166da94b67537758b Schema Change Guide
> https://news.ycombinator.com/item?id=30458580

https://www.shayon.dev/post/2022/47/pg-osc-zero-downtime-schema-changes-in-postgresql/

https://alexklibisz.com/2022/02/18/optimizing-postgres-trigram-search.html
> https://news.ycombinator.com/item?id=30433269

https://www.youtube.com/watch?v=j7UPVU5UCV4 Intro to Postgres Planner - Hacking Melanie Plageman

https://github.com/shayonj/pg-online-schema-change

https://blog.yugabyte.com/postgresql-timestamps-timezones/
> https://news.ycombinator.com/item?id=30318751

https://www.citusdata.com/blog/2018/02/22/seven-tips-for-dealing-with-postgres-locks/
> https://news.ycombinator.com/item?id=30316653

https://github.com/levkk/pgcat Show HN: PgCat, Postgres pooler with sharding, load balancing and failover
> https://news.ycombinator.com/item?id=30267539

https://datastation.multiprocess.io/blog/2022-02-08-the-world-of-postgresql-wire-compatibility.html
> https://news.ycombinator.com/item?id=30284538

https://ketansingh.me/posts/how-postgres-stores-rows/
> https://news.ycombinator.com/item?id=30279986

https://wiki.postgresql.org/wiki/Don%27t_Do_This
> https://news.ycombinator.com/item?id=30298736

https://ardentperf.com/2022/02/10/a-hairy-postgresql-incident/
> https://news.ycombinator.com/item?id=30296490

https://www.depesz.com/2022/02/06/waiting-for-postgresql-15-add-unique-null-treatment-option/

https://www.splitgraph.com/blog/postgresql-fdw-aggregation-pushdown-multicorn-part-1

https://www.evanjones.ca/postgres-large-json-performance.html

https://rclayton.silvrback.com/distributed-locking-with-postgres-advisory-locks

https://github.com/postgres-ai/database-lab-engine
> https://news.ycombinator.com/item?id=30068669

https://github.com/jorzel/postgres-full-text-search

https://www.dolthub.com/blog/2022-01-26-creating-a-postgres-foreign-data-wrapper/
> https://news.ycombinator.com/item?id=30089884

https://www.interdb.jp/pg/index.html The Internals of PostgreSQL
> https://news.ycombinator.com/item?id=30086374

https://spacelift.io/blog/tricking-postgres-into-using-query-plan
> https://news.ycombinator.com/item?id=29981737

https://postgres.ai/blog/20220114-progress-bar-for-postgres-queries-lets-dive-deeper

https://rhaas.blogspot.com/2022/01/who-contributed-to-postgresql.html
> https://news.ycombinator.com/item?id=29910327

https://www.adyen.com/blog/updating-a-50-terabyte-postgresql-database
> https://news.ycombinator.com/item?id=29923303
> > https://www.slony.info/

https://blog.crunchydata.com/blog/five-tips-for-a-healthier-postgres-database-in-the-new-year
> https://news.ycombinator.com/item?id=29858083

https://heap.io/blog/optimizing-postgres-queries-at-scale
> https://news.ycombinator.com/item?id=29715872

https://blog.crunchydata.com/blog/randomly-sampling-data-using-sql-and-postgresql

https://jezenthomas.com/fast-counting-with-postgresql-and-haskell/

https://pawelurbanek.com/postgresql-fix-performance

https://vadosware.io/post/everything-ive-seen-on-optimizing-postgres-on-zfs-on-linux/
> https://news.ycombinator.com/item?id=29647645

https://github.com/supabase/supabase
> https://supabase.com/blog/2021/11/30/supabase-studio

https://github.com/eulerto/wal2json

https://schemaverse.com/
> https://news.ycombinator.com/item?id=29375911

https://www.postgresql.org/about/news/pgpool-ii-426-419-4016-3721-and-3628-released-2357/

https://eradman.com/posts/ephemeral-databases.html
> https://news.ycombinator.com/item?id=29248299

https://www.migops.com/blog/2021/11/15/postgresql-15-will-include-some-more-regexp-functions/

https://github.com/yandex/odyssey Advanced multi-threaded PostgreSQL connection pooler and request router
> https://news.ycombinator.com/item?id=29201000

https://www.postgresql.fastware.com/blog/what-is-the-new-lz4-toast-compression-in-postgresql-14
> https://news.ycombinator.com/item?id=29147656

https://hakibenita.com/postgresql-unknown-features
> https://news.ycombinator.com/item?id=29163319

https://www.enterprisedb.com/products/biganimal-cloud-postgresql

https://github.com/postgrespro/jsquery
> https://news.ycombinator.com/item?id=29069777

https://notes.eatonphil.com/exploring-plpgsql-forth-like.html

https://stackgres.io/blog/stackgres-1-0-0-open-source-postgres-aas-with-120-extensions/

https://blog.timescale.com/blog/function-pipelines-building-functional-programming-into-postgresql-using-custom-operators/
> https://news.ycombinator.com/item?id=28919205

https://www.migops.com/blog/2021/10/14/stored-procedure-out-parameters-in-postgresql-14/
> https://news.ycombinator.com/item?id=28878918

https://heap.io/blog/the-million-indexes-incident

https://www.postgresql.org/about/news/postgresql-14-released-2318/
> https://news.ycombinator.com/item?id=28705699

https://pgloader.io/ LISP
> https://news.ycombinator.com/item?id=28659076

https://blog.crunchydata.com/blog/postgres-14-its-the-little-things

https://www.depesz.com/2021/09/10/waiting-for-postgresql-15-revoke-public-create-from-public-schema-now-owned-by-pg_database_owner/
> https://news.ycombinator.com/item?id=28537870

[Postgres: Boundless `text` and Back Again](https://brandur.org/text) 
> https://news.ycombinator.com/item?id=28484312

https://www.cybertec-postgresql.com/en/index-bloat-reduced-in-postgresql-v14/
> https://news.ycombinator.com/item?id=28486623

https://postgres.ai/blog/20210831-postgresql-subtransactions-considered-harmful
> https://news.ycombinator.com/item?id=28374333

https://blog.timescale.com/blog/how-postgresql-aggregation-works-and-how-it-inspired-our-hyperfunctions-design-2/
> https://news.ycombinator.com/item?id=28075774

https://drewdevault.com/2021/08/05/In-praise-of-Postgres.html
> https://news.ycombinator.com/item?id=28075204

https://www.channable.com/tech/dbcritic-constructively-criticizing-your-postgres-schema
> https://news.ycombinator.com/item?id=27760073

https://www.postgresql.org/about/news/postgresql-14-beta-1-released-2213/
> https://news.ycombinator.com/item?id=27220725

https://www.postgresql.org/about/news/postgresql-133-127-1112-1017-and-9622-released-2210/

https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=1e55e7d1755cefbb44982fbacc7da461fa8684e6
> https://news.ycombinator.com/item?id=26756568

https://rbranson.medium.com/10-things-i-hate-about-postgresql-20dbab8c2791
> https://news.ycombinator.com/item?id=26709019

https://www.postgresql.org/about/news/1960/ PostgreSQL 11.5, 10.10, 9.6.15, 9.5.19, 9.4.24, and 12 Beta 3 Released! Sec Fixes

https://archive.fosdem.org/2019/schedule/event/postgresql_fsync/
> https://news.ycombinator.com/item?id=19119991
> https://news.ycombinator.com/item?id=30131165
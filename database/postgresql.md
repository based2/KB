https://news.ycombinator.com/item?id=25910277

https://www.highgo.ca/2021/01/27/avoiding-identifying-and-dealing-with-postgresql-database-corruption-part-1/

https://dzone.com/articles/managing-high-availability-in-postgresql-part-i

https://www.slony.info/ 

https://postgres.cz/wiki/PostgreSQL_SQL_Tricks_III

https://blog.crunchydata.com/blog/get-started-with-explain-analyze

https://news.ycombinator.com/item?id=23516947

https://dzone.com/articles/managing-high-availability-in-postgresql-part-i

https://pgmodeler.io/

http://coussej.github.io/2016/01/14/Replacing-EAV-with-JSONB-in-PostgreSQL/
https://hashrocket.com/blog/posts/custom-aggregates-in-postgresql

ttps://github.com/dhamaniasad/awesome-postgres

https://www.migops.com/blog/2021/04/09/pgbackrest-the-best-postgres-backup-tool-with-a-very-active-community/#Conclusion

https://github.com/ankane/pgvector vector similarity search
* https://news.ycombinator.com/item?id=26903105

http://eradman.com/ephemeralpg/

https://elephant-shed.io/

https://www.cybertec-postgresql.com/en/postgresql-detecting-slow-queries-quickly/

https://github.com/plv8/plv8

https://fly.io/blog/globally-distributed-postgres/
* https://news.ycombinator.com/item?id=27690950

https://brandur.org/idempotency-keys

https://www.narrator.ai/blog/postgres-missing-datediff-function/
* https://lobste.rs/s/mxhevf/postgresql_s_missing_datediff_function
  * select justify_interval('2021-06-04'::timestamp with time zone - '2020-04-06 23:53:45');

https://blog.crunchydata.com/blog/generating-json-directly-from-postgres
* https://news.ycombinator.com/item?id=27848085

https://www.cybertec-postgresql.com/en/postgresql-limit-vs-fetch-first-rows-with-ties/
* https://news.ycombinator.com/item?id=27845360

https://blog.jonudell.net/2021/07/27/working-with-postgres-types/
* https://news.ycombinator.com/item?id=28095264

https://github.com/vramework/postgres-typed
* https://news.ycombinator.com/item?id=28326117

### OOM
https://info.crunchydata.com/blog/deep-postgresql-thoughts-the-linux-assassin

# Debug
https://iamsafts.com/posts/postgres-gin-performance/
* https://news.ycombinator.com/item?id=27152507

https://www.cybertec-postgresql.com/en/how-to-interpret-postgresql-explain-analyze-output/

https://dev.to/jbranchaud/beware-the-missing-foreign-key-index-a-postgres-performance-gotcha-3d5i

# Index
http://leopard.in.ua/2015/04/13/postgresql-indexes/

# Analysis
https://github.com/marklit/datafluent_pg

https://www.percona.com/blog/improve-postgresql-query-performance-insights-with-pg_stat_monitor/

### Extensions
https://age.apache.org/# Graph

https://github.com/arkhipov/temporal_tables Table that records the period of time when a row is valid.
https://github.com/nearform/temporal_tables
* https://news.ycombinator.com/item?id=26748096

# Queue
https://spin.atomicobject.com/2021/02/04/redis-postgresql/
* https://news.ycombinator.com/item?id=27482243

# Security
https://goteleport.com/blog/securing-postgres-postgresql/
* https://news.ycombinator.com/item?id=26674756
https://www.cisecurity.org/benchmark/postgresql/
  
# Realtime
https://github.com/supabase/realtime Listen to your to PostgreSQL database in realtime via WebSockets (Erlang/Elixir)
* https://news.ycombinator.com/item?id=26968449

# Migration
https://github.com/sastraxi/pgsh

https://github.com/djrobstep/migra
* https://news.ycombinator.com/item?id=16673526

https://blog.discourse.org/2021/04/standing-on-the-shoulders-of-a-giant-elephant/

https://www.paulox.net/2021/05/28/upgrading-postgresql-from-version-12-to-13-on-ubuntu-21-04-focal-fossa/

https://engineering.theblueground.com/blog/zero-downtime-postgres-migration-done-right/

https://fabianlindfors.se/blog/schema-migrations-in-postgres/
* https://news.ycombinator.com/item?id=27531934
 * https://dba.stackexchange.com/questions/195104/postgres-group-by-id-works-on-table-directly-but-not-on-identical-view

# Container
https://www.kubegres.io/
* https://www.reddit.com/r/PostgreSQL/comments/mqrsbn/kubegres_is_a_kubernetes_operator_for_postgresql/

# HA
https://github.com/zalando/patroni

# Generator
https://github.com/vramework/schemats Postgres to TypeScript Interfaces and Enums
* https://news.ycombinator.com/item?id=27570058

# Extensions
https://github.com/jie123108/imgsmlr-server

# News
https://blog.timescale.com/blog/how-postgresql-aggregation-works-and-how-it-inspired-our-hyperfunctions-design-2/
* https://news.ycombinator.com/item?id=28075774
https://drewdevault.com/2021/08/05/In-praise-of-Postgres.html
* https://news.ycombinator.com/item?id=28075204
https://incident.io/blog/one-two-skip-a-few Postgres sequences can skip 32 unexpectedly
* https://news.ycombinator.com/item?id=27843084
https://www.channable.com/tech/dbcritic-constructively-criticizing-your-postgres-schema
* https://news.ycombinator.com/item?id=27760073
https://supabase.io/blog/2021/07/01/roles-postgres-hooks
* https://news.ycombinator.com/item?id=27712800
https://blog.crunchydata.com/blog/better-json-in-postgres-with-postgresql-14
* https://news.ycombinator.com/item?id=27358977
https://www.postgresql.org/about/news/postgresql-14-beta-1-released-2213/
* https://news.ycombinator.com/item?id=27220725
https://www.postgresql.org/about/news/postgresql-133-127-1112-1017-and-9622-released-2210/
https://git.postgresql.org/gitweb/?p=postgresql.git;a=commit;h=1e55e7d1755cefbb44982fbacc7da461fa8684e6
* https://news.ycombinator.com/item?id=26756568
https://rbranson.medium.com/10-things-i-hate-about-postgresql-20dbab8c2791
* https://news.ycombinator.com/item?id=26709019
https://www.postgresql.org/about/news/1960/ PostgreSQL 11.5, 10.10, 9.6.15, 9.5.19, 9.4.24, and 12 Beta 3 Released! Sec Fixes

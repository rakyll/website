---
title: "Welcome"
type: "index"
---

The [Cloud Spanner Ecosystem](https://github.com/cloudspannerecosystem)
GitHub organization hosts a collection of public
repositories that are owned-by and
developed-for the [Google Cloud Spanner](https://cloud.google.com/spanner)
user community.

All the hosted projects are based on open source contributions.
We’d love for you to report issues, file feature requests,
and send pull requests. See details on [contributions](/contributing).
Note that none of the projects are officially supported by Google
as part of the Cloud Spanner product.
Please [let us know](https://gitter.im/cloudspannerecosystem/community)
if you’re interested in getting your project hosted! This will help other
Cloud Spanner developers find your project and contribute to it.

# Projects

* [SampleDB](https://github.com/cloudspannerecosystem/sampledb):
  This application allows you to quickly get a sample database
  into Cloud Spanner. It does so by loading data from a CSV file
  into a new Cloud Spanner database.

* [App Engine Java Sample](https://github.com/cloudspannerecosystem/appengine-java-sample):
  This sample demonstrates how to use Cloud Spanner
  from the App Engine Standard with Java 11 environment.

* [HarbourBridge](https://github.com/cloudspannerecosystem/harbourbridge):
  HarbourBridge is a stand-alone tool for Cloud Spanner evaluation,
  using data from an existing PostgreSQL database. The tool ingests
  pg_dump output, automatically builds a Spanner schema, and creates
  a new Spanner database populated with data from pg_dump.

* [spanner-cli](https://github.com/cloudspannerecosystem/spanner-cli):
  spanner-cli is an interactive command line tool, inspired by the
  mysql utility. It allows you to control your Cloud Spanner
  databases with idiomatic database commands, such as SHOW TABLES or
  SELECT / INSERT / UPDATE / DELETE.

* [spanner-dump](https://github.com/cloudspannerecosystem/spanner-dump):
  spanner-dump is a command line tool for exporting a Cloud Spanner
  database in text format. This tool can be used for Cloud Spanner
  service for testing purposes or databases running on
  Cloud Spanner Emulator.
  You can import exported databases into
  Cloud Spanner again with [spanner-cli](https://github.com/cloudspannerecosystem/spanner-cli).

* [PGAdapter](https://github.com/cloudspannerecosystem/pgadapter):
  PGAdapter is a client-side Java proxy which translates
  Postgres wire protocol into the Cloud Spanner equivalent.
  By running this proxy locally, any Postgres client
  (including the SQL command-line client PSQL) should function
  seamlessly by simply pointing its outbound port to the this
  proxy’s inbound port.

* [wrench](https://github.com/cloudspannerecosystem/wrench):
  wrench is a schema management tool for Cloud Spanner.
  It manages DDLs for schema migration and provides several
  schema related features like creating / deleting databases
  and loading schemas from files.

* [yo](https://github.com/cloudspannerecosystem/yo):
  yo is a command-line tool to generate database-specific code
  to access Cloud Spanner through Go objects instead of SQL queries.
  It does so by fetching schema metadata for a database by
  querying the information schema and applies Go templates to
  generate code / models.

* [Scheduled Backups](https://github.com/cloudspannerecosystem/scheduled-backups):
  Scheduled Backups shows how to use Cloud Scheduler and Cloud Functions to
  configure a schedule for creating Cloud Spanner backups.

# Resources

## Documentation

* [Official Documentation](https://cloud.google.com/spanner)
* [Best Practices](https://cloud.google.com/spanner/docs/best-practice-list)
* [API Reference](https://cloud.google.com/spanner/docs/reference/rest)
* [GCP Weekly: Spanner](https://www.gcpweekly.com/gcp-resources/tag/google-cloud-spanner/)

## Libraries and ORMs

### Client Libraries

* [Authentication via Application Default Credentials (ADC)](https://cloud.google.com/docs/authentication/production)
* [Java](https://googleapis.dev/java/google-cloud-clients/0.119.0-alpha/com/google/cloud/spanner/package-summary.html) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/java))
* [Go](https://pkg.go.dev/cloud.google.com/go/spanner) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/go))
* [Node.js](https://googleapis.dev/nodejs/spanner/latest/) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/nodejs))
* [Python](https://googleapis.dev/python/spanner/latest/index.html) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/python))
* [PHP](https://googleapis.github.io/google-cloud-php/#/docs/google-cloud/latest/spanner/readme) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/php))
* [Ruby](https://googleapis.dev/ruby/google-cloud-spanner/latest/Google/Cloud/Spanner.html) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/ruby))
* [C#](https://googleapis.github.io/google-cloud-dotnet/docs/Google.Cloud.Spanner.Data/api/Google.Cloud.Spanner.Data.html) ([tutorial](https://cloud.google.com/spanner/docs/getting-started/csharp))

### Drivers

* [Google's OSS](https://cloud.google.com/spanner/docs/jdbc-drivers) JDBC driver
* [Simba](https://cloud.google.com/spanner/docs/jdbc-drivers) JDBC driver
* [R2DBC](https://github.com/GoogleCloudPlatform/cloud-spanner-r2dbc) driver
* [Go database/sql](https://github.com/rakyll/go-sql-driver-spanner) driver

### ORM

* [Django](https://github.com/googleapis/python-spanner-django/)
* [Hibernate ORM](https://cloud.google.com/spanner/docs/use-hibernate)
* [Spring Data](https://cloud.google.com/spanner/docs/adding-spring)

## Tools

* [Spanner Console](https://console.cloud.google.com/spanner)
* [Spanner command-line](https://github.com/cloudspannerecosystem/spanner-cli)
* [gcloud Reference](https://cloud.google.com/sdk/gcloud/reference/spanner)
* [Spanner Emulator](https://github.com/GoogleCloudPlatform/cloud-spanner-emulator)
* [wrench](https://github.com/cloudspannerecosystem/wrench) - Schema management tool for Spanner.
* [hammer](https://github.com/daichirata/hammer) - Schema management tool for Spanner.
* [yo](https://github.com/cloudspannerecosystem/yo) - A command-line tool to generate Go code for Google Cloud Spanner.
* [handy-spanner](https://github.com/gcpug/handy-spanner) - An unofficial SQLite backed Spanner emulator.
* [spannerz](https://github.com/rakyll/spannerz) - Query planner visualizer that also provides introspection tools for Go programs.
* [spanner-dump](https://github.com/cloudspannerecosystem/spanner-dump) - A command-line tool to export Cloud Spanner databases in text format.

## Configuration Management

* [Chef](https://github.com/GoogleCloudPlatform/chef-google-spanner)
* [Puppet](https://github.com/GoogleCloudPlatform/puppet-google-spanner)
* [Terraform](https://www.terraform.io/docs/providers/google/r/spanner_database.html)

## Migration

* Migration from [PostgreSQL](https://cloud.google.com/spanner/docs/migrating-postgres-spanner), [MySQL](https://cloud.google.com/solutions/migrating-mysql-to-spanner), [Oracle](https://cloud.google.com/solutions/migrating-oracle-to-cloud-spanner), [DynomoDB](https://cloud.google.com/solutions/migrating-dynamodb-to-cloud-spanner).
* [Harbourbridge](https://github.com/cloudspannerecosystem/harbourbridge) - PostgreSQL to Spanner schema and data migrator.
* [pgadapter](https://github.com/cloudspannerecosystem/pgadapter) - A proxy that translates the wire protocol from Postgres to Cloud Spanner.
* [migrate](https://github.com/golang-migrate/migrate) - A migration tool with Spanner support.

## Performance and Debugging

* [Query Execution Plans](https://cloud.google.com/spanner/docs/query-execution-plans)
* [SQL Best Practices](https://cloud.google.com/spanner/docs/sql-best-practices)
* [CPU Utilization](https://cloud.google.com/spanner/docs/cpu-utilization)
* [Latency Debugging](https://cloud.google.com/spanner/docs/latency)
* [Distributed Tracing and Client Metrics](https://medium.com/@orijtech/cloud-spanner-instrumented-by-opencensus-and-exported-to-stackdriver-6ed61ed6ab4e)


## Whitepapers

* [Spanner: Google's Globally-Distributed Database](https://research.google/pubs/pub39966/)
* [Spanner, TrueTime and the CAP Theorem](https://research.google/pubs/pub45855/)
* [Spanner: Becoming a SQL System](https://research.google/pubs/pub46103/)

## Talks

* [Cloud Spanner 101: Google's mission-critical relational database](https://www.youtube.com/watch?v=IfsTINNCooY)
* [Spanner Internals Part 1: What Makes Spanner Tick?](https://www.youtube.com/watch?v=nvlt0dA7rsQ)
* [Spanner Internals Part 2: Global Meta-Data and Scalable Data Backend](https://www.youtube.com/watch?v=zy-rcR4MoN4)
* [Best Practices on Migrating to Cloud Spanner](https://www.youtube.com/watch?v=FNeGQUqMa_c)
* [Ben Sigelman presents the Spanner whitepaper](https://youtu.be/mYV6_OaZeEs?t=1629)

## Podcasts

* [Google Cloud Platform Podcast](https://www.gcppodcast.com/post/episode-62-cloud-spanner-with-deepti-srivastava/)
* [Software Engineering Daily](https://softwareengineeringdaily.com/2019/09/10/google-spanner-with-deepti-srivastava)
* [The Architect](http://architechtshow.com/ep-44-googles-deepti-srivastava-on-multi-region-spanner-and-case-for-cloud-databases)

## Meetups

* [Google Cloud Spanner Developers](https://www.meetup.com/Cloud-Spanner-Developers/), San Francisco, CA

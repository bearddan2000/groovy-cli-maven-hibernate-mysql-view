# groovy-cli-maven-hibernate-mysql-view

## Description
Creates a small database table
called `dog` and populates with
hql. Creates 2 lookup tables `breedLookup`
and `colorLookup` and 4N `dog`.

Joins `breedLookup` and `colorLookup`
to form a new table `dogextended`. These
views are deministrated 3 ways, `ResultTransformer`,
looking up ids on `breedLookup` and `colorLookup`,
and non-ResultTransformer method.

Add an immutable entity `breedcount` as a view uses a subquery join.

## Tech stack
- groovy
- maven
  - hibernate
  - hql
  - log4j
  - mysql driver

## Docker stack
- maven:3-openjdk-17
- mariadb:latest

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`
## For help
`sudo ./install.sh -h`

## Credit
- [ResultTransformer code based on](https://thorben-janssen.com/hibernate-resulttransformer/)
- [HQL code based on](https://www.journaldev.com/2954/hibernate-query-language-hql-example-tutorial)
- [Hibernate config based on](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/An-example-hibernatecfgxml-for-MySQL-8-and-Hibernate-5)
- [Hibernate code based on](https://github.com/lokeshgupta1981/hibernate/tree/master/hibernate-hello-world)

## groovy-cli specific search
- [Search by maven](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-maven&type=&language=&sort=)
- [Search by hibernate](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-hibernate&type=&language=&sort=)
- [Search by mysql](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-mysql&type=&language=&sort=)
- [Search by view](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-join&type=&language=&sort=)
- [Search by hql](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-hql&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=groovy-cli-driver&type=&language=&sort=)

## General search
- [Search by groovy](https://github.com/bearddan2000?tab=repositories&q=java&type=&language=&sort=)
- [Search by cli](https://github.com/bearddan2000?tab=repositories&q=cli&type=&language=&sort=)
- [Search by maven](https://github.com/bearddan2000?tab=repositories&q=maven&type=&language=&sort=)
- [Search by hibernate](https://github.com/bearddan2000?tab=repositories&q=hibernate&type=&language=&sort=)
- [Search by mysql](https://github.com/bearddan2000?tab=repositories&q=mysql&type=&language=&sort=)
- [Search by view](https://github.com/bearddan2000?tab=repositories&q=join&type=&language=&sort=)
- [Search by hql](https://github.com/bearddan2000?tab=repositories&q=hql&type=&language=&sort=)
- [Search by log4j](https://github.com/bearddan2000?tab=repositories&q=log4j&type=&language=&sort=)
- [Search by driver](https://github.com/bearddan2000?tab=repositories&q=driver&type=&language=&sort=)

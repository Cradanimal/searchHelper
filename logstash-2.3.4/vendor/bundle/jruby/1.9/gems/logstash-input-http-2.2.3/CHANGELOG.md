# 2.2.3
  - fix hanging tests
  - added some meta documents to the repository like contributing guide and github templates
# 2.2.2
  - Depend on logstash-core-plugin-api instead of logstash-core, removing the need to mass update plugins on major releases of logstash
# 2.2.1
  - New dependency requirements for logstash-core for the 5.0 release
## 2.2.0
 - Bump puma dependency to 2.16.0

## 2.1.1
 - Support for custom response headers

## 2.1.0
 - Support compressed and gziped requests (thanks dwapstra)

## 2.0.0
 - Plugins were updated to follow the new shutdown semantic, this mainly allows Logstash to instruct input plugins to terminate gracefully,
   instead of using Thread.raise on the plugins' threads. Ref: https://github.com/elastic/logstash/pull/3895
 - Dependency on logstash-core update to 2.0

## 1.0.3 (September 2, 2015)
* Include remote host address to events (#25)

## 1.0.2 (July 28, 2015)
* Fix for missing base64 require which was crashing Logstash (#17)

## 1.0.0 (July 1, 2015)

* First version: New input to receive HTTP requests
* Added basic authentication and SSL support

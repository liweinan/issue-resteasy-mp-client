RESTEASY-2335

* [RESTEASY-2335 RestEasy Microprofile Client has a immutable template problem/bug - JBoss Issue Tracker](https://issues.jboss.org/browse/RESTEASY-2335)


```bash
$ mvn compile quarkus:dev:
```

```bash
$ http http://localhost:8080/1/tags/1
HTTP/1.1 204 No Content
Date: Wed, 18 Sep 2019 06:55:05 GMT



$
```


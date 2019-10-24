**Mapowanie klas (java mapping frameworks):**

- Dozer
- Orika
- ModelMapper
- MapStruct

https://www.baeldung.com/java-performance-mapping-frameworks

**Kod źródłowy ze szkolenia:**

https://github.com/landrzejewski/spring-cloud-training/

**Apache2 Utils**

Narzędzie do testów wydajnościowych usług.

Instalacja: apt-get install apache2-utils

Przykładowe wywołanie w [pliku](apache2-utils.txt).

**Komponenty**

- Configuration (cloud config)
- Discovery (eureka)
- Gateway
- Agregacja, korelacja, prezentacja logów (zipkin, sleuth)
- Panel admina (Spring Boot Admin - patrz niżej)

**Kubernetes**

Spostrzeżenia:

- Wielkie możliwości
- Duży koszt wejścia (sam Kubernetes to min. 8 nodów: 3 master, 2 workery, lb...)
- Zastosowanie dla dużej liczby maszyn (50, 100?)

**Spring Boot Admin**

https://github.com/codecentric/spring-boot-admin

**Wzorce**

Wszystkie:

https://microservices.io/patterns/

Saga Pattern:

https://blog.couchbase.com/saga-pattern-implement-business-transactions-using-microservices-part/

https://blog.couchbase.com/saga-pattern-implement-business-transactions-using-microservices-part-2/
#### Mapowanie klas (java mapping frameworks)

- Dozer
- Orika
- ModelMapper
- MapStruct

https://www.baeldung.com/java-performance-mapping-frameworks

#### Kod źródłowy ze szkolenia

https://github.com/landrzejewski/spring-cloud-training/

https://github.com/landrzejewski/spring-training/

https://github.com/landrzejewski/kubernetes-training

#### Apache2 Utils

Narzędzie do testów wydajnościowych usług.

Instalacja: apt-get install apache2-utils

Przykładowe wywołanie w [pliku](apache2-utils.txt).

#### Komponenty

- Configuration (cloud config)
- Discovery (eureka)
- Gateway (api gateway)
- Agregacja, korelacja, prezentacja logów (zipkin, sleuth)
- Panel admina ([Spring Boot Admin](https://github.com/codecentric/spring-boot-admin))

#### Kubernetes

https://kubernetes.io/docs/concepts/

**Spostrzeżenia:**

- Wielkie możliwości
- Duży koszt wejścia (sam Kubernetes to min. 8 nodów: 3 master, 2 worker nody, proxy/lb)
- Zastosowanie dla dużej liczby maszyn (50, 100?)

Obraz, który należy odpalić na VirtualBox:

https://justpaste.it/2qv00

**Metallb**

Metallb umożliwia wystawienie puli adresów dla usług na zewnątrz.

W szczególności może wystawić adres dla Ingresa, który będzie zewnętrznym LB.

https://metallb.universe.tf/

**Ingres**

Zewnętrzny LB, który mapuje adresy na serwisy.

https://metallb.universe.tf/

**Istio**

https://istio.io/docs/concepts/what-is-istio/

**Rook**

https://rook.io/

**Blog Kubernetes hard way**

https://github.com/kelseyhightower/kubernetes-the-hard-way

**Książki**

- Docker in action
- Docker in practice
- Kubernetes in action
- https://www.oreilly.com/

#### Wzorce

**Wszystkie:**

https://microservices.io/patterns/

**Saga Pattern:**

https://blog.couchbase.com/saga-pattern-implement-business-transactions-using-microservices-part/

https://blog.couchbase.com/saga-pattern-implement-business-transactions-using-microservices-part-2/

**Docker Anti-Patterns**

https://blog.couchbase.com/docker-container-anti-patterns/

**Event sourcing / event logging**

https://blog.couchbase.com/event-sourcing-event-logging-an-essential-microservice-pattern/

#### OAuth

**Książki**

- OAuth in action
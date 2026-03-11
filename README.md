# Java-FullStack Roadmap

In this repository, you will find :
  - [A roadmap for learning Backend with Java](#backend-roadmap)
  - [A roadmap for learning Frontend with Java](#frontend-roadmap)
  - [Resources for learning Java-Backend](#resources-for-learning-java-backend)
  - [Resources for learning Java-Frontend](#resources-for-learning-java-frontend)
  - [References of the roadmap](#references-of-the-roadmap)
  - [Want to contribute to this repository?](#contribution)

---

# Backend Roadmap

## 1. Java
<details open>
<summary> <b>Learn Java</b> </summary>
  <ol>
    <li>
      <a> Basics </a>
      <ul>
        <li><a> Classes, Variables, Loops etc </a></li>
        <li><a> OOPs </a></li>
        <li><a> Collections </a></li>
        <li><a> Generics </a></li>
        <li><a> Exception Handling (Checked vs Unchecked) </a></li>
      </ul>
    </li>
    <li>
      <a> Advanced </a>
      <ul>
        <li><a> Design Patterns </a></li>
        <li><a> JVM </a></li>
        <li><a> Threads </a></li>
        <li><a> Servlets and JSP's </a></li>
        <li><a> Concurrency </a></li>
        <li><a> Garbage Collection </a></li>
        <li><a> Streams and Lambda Expressions </a></li>
        <li><a> Functional Interfaces </a></li>
        <li><a> Java Memory Model </a></li>
        <li><a> Reflection API </a></li>
        <li><a> Annotations (Custom Annotations) </a></li>
        <li><a> Java Modules (JPMS) </a></li>
        <li><a> JDBC (Java Database Connectivity) </a></li>
        <li><a> Java 17+ Features (Records, Sealed Classes, Pattern Matching, Text Blocks) </a></li>
      </ul>
    </li>
    <li><a> Build Tools (Maven, Gradle, Ant) </a></li>
    <li><a> Servers (Tomcat, Weblogic, JBOSS, WebSphere, Jetty) </a></li>
    <li>
      <a> Testing </a>
      <ul>
        <li><a> Unit Testing </a></li>
        <li><a> Integration Testing </a></li>
        <li><a> JUnit </a></li>
        <li><a> Mockito </a></li>
        <li><a> TestContainers </a></li>
        <li><a> Selenium </a></li>
      </ul>
    </li>
    <li><a> Logging (Log4j, Log4j2, Logback, SLF4J) </a></li>
  </ol>
</details>

## 2. Spring Framework
<details open>
<summary> <b>Learn Spring Framework</b> </summary>
  <ol>
    <li>
      <a> Core </a>
      <ul>
        <li><a> Bean Life Cycle </a></li>
        <li><a> Dependency Injection </a></li>
        <li><a> Inversion of Control </a></li>
        <li><a> Bean Factory and Application Context </a></li>
        <li><a> Bean Scopes (Singleton, Prototype, Request, Session) </a></li>
        <li><a> Spring Expression Language (SpEL) </a></li>
        <li><a> Event Handling </a></li>
      </ul>
    </li>
    <li>
      <a> Web </a>
      <ul>
        <li><a> Annotations </a></li>
        <li><a> MVC Structure </a></li>
        <li><a> Configurations </a></li>
        <li><a> Integrating different Libraries/Frameworks </a></li>
        <li><a> Profiles </a></li>
        <li><a> Exception Handling (@ControllerAdvice, @ExceptionHandler) </a></li>
        <li><a> Validation (@Valid, @Validated) </a></li>
        <li><a> Content Negotiation </a></li>
        <li><a> CORS Configuration </a></li>
      </ul>
    </li>
    <li>
      <a> AOP </a>
      <ul>
        <li><a> How AOP Works </a></li>
        <li><a> Creating PointCut, Join Point, Aspect etc </a></li>
      </ul>
    </li>
  </ol>
</details>

## 3. Spring Boot
<details open>
<summary> <b>Learn Spring Boot</b> </summary>
  <ol>
    <li><a> Importance of Spring Boot </a></li>
    <li><a> Auto Configuration </a></li>
    <li><a> Adding Configuration </a></li>
    <li><a> Properties/YAML </a></li>
    <li><a> Integrations with other Libraries/Frameworks </a></li>
    <li><a> Spring Boot Starters </a></li>
    <li><a> Actuator (Health Checks, Metrics) </a></li>
    <li><a> DevTools </a></li>
    <li><a> Embedded Server Configuration </a></li>
    <li><a> Spring Boot CLI </a></li>
    <li><a> Profiles (dev, test, prod) </a></li>
  </ol>
</details>

## 4. REST API
<details open>
<summary> <b>Learn REST API</b> </summary>
  <ol>
    <li>
      <a> HTTP Methods </a>
      <ul>
        <li><a> POST </a></li>
        <li><a> GET </a></li>
        <li><a> PUT </a></li>
        <li><a> PATCH </a></li>
        <li><a> DELETE </a></li>
        <li><a> HEAD </a></li>
        <li><a> OPTIONS </a></li>
        <li><a> TRACE </a></li>
      </ul>
    </li>
    <li>
      <a> HTTP Status Codes </a>
      <ul>
        <li><a> 1XX (Informational) </a></li>
        <li><a> 2XX (Success) </a></li>
        <li><a> 3XX (Redirection) </a></li>
        <li><a> 4XX (Client Error) </a></li>
        <li><a> 5XX (Server Error) </a></li>
      </ul>
    </li>
    <li>
      <a> API Design Best Practices </a>
      <ul>
        <li><a> API Versioning </a></li>
        <li><a> HATEOAS </a></li>
        <li><a> Swagger / OpenAPI Documentation </a></li>
        <li><a> Rate Limiting </a></li>
        <li><a> Pagination and Sorting </a></li>
        <li><a> Content Negotiation (JSON, XML) </a></li>
      </ul>
    </li>
  </ol>
</details>

## 5. Database
<details open>
<summary> <b>Learn Database</b> </summary>
  <ol>
    <li>
      <a> SQL </a>
      <ul>
        <li><a> MySQL </a></li>
        <li><a> PostgreSQL </a></li>
        <li><a> Oracle </a></li>
      </ul>
    </li>
    <li>
      <a> NoSQL </a>
      <ul>
        <li><a> MongoDB </a></li>
        <li><a> Cassandra </a></li>
        <li><a> Redis </a></li>
        <li><a> Elasticsearch </a></li>
      </ul>
    </li>
    <li>
      <a> ORM and Data Access </a>
      <ul>
        <li><a> Hibernate ORM </a></li>
        <li><a> Spring Data JPA </a></li>
        <li><a> Spring Data MongoDB </a></li>
        <li><a> Spring Data JDBC </a></li>
        <li><a> Spring Data Redis </a></li>
      </ul>
    </li>
    <li>
      <a> Database Migrations </a>
      <ul>
        <li><a> Flyway </a></li>
        <li><a> Liquibase </a></li>
      </ul>
    </li>
    <li><a> Connection Pooling (HikariCP) </a></li>
  </ol>
</details>

## 6. Spring Security
<details open>
<summary> <b>Learn Spring Security</b> </summary>
  <ol>
    <li><a> Authentication </a></li>
    <li><a> Authorization </a></li>
    <li><a> OAuth2 </a></li>
    <li><a> Form Authentication </a></li>
    <li><a> JWT (JSON Web Tokens) </a></li>
    <li><a> CSRF Protection </a></li>
    <li><a> CORS </a></li>
    <li><a> Method Level Security </a></li>
    <li><a> Role-Based Access Control (RBAC) </a></li>
    <li><a> Spring Security Filters </a></li>
    <li><a> Session Management </a></li>
    <li><a> LDAP Authentication </a></li>
  </ol>
</details>

## 7. Microservices
<details open>
<summary> <b>Learn Microservices</b> </summary>
  <ol>
    <li>
      <a> Spring Cloud </a>
      <ul>
        <li><a> Spring Cloud Gateway </a></li>
        <li><a> Spring Cloud Config </a></li>
        <li><a> Spring Cloud Circuit Breaker </a></li>
        <li><a> Spring Cloud OpenFeign </a></li>
        <li><a> Spring Cloud Sleuth </a></li>
        <li><a> Spring Cloud Netflix (Eureka, Hystrix) </a></li>
        <li><a> Spring Cloud Stream </a></li>
        <li><a> Spring Cloud Bus </a></li>
        <li><a> Other Spring Cloud Projects (based on requirement) </a></li>
      </ul>
    </li>
    <li>
      <a> DevOps </a>
      <ul>
        <li><a> Docker </a></li>
        <li><a> Kubernetes </a></li>
        <li><a> Cloud (AWS, GCP, Azure) </a></li>
        <li><a> CI/CD (Jenkins, GitHub Actions, GitLab CI) </a></li>
        <li><a> Terraform </a></li>
        <li><a> Monitoring (Prometheus, Grafana) </a></li>
        <li><a> Logging (ELK Stack - Elasticsearch, Logstash, Kibana) </a></li>
      </ul>
    </li>
    <li>
      <a> Microservices Patterns </a>
      <ul>
        <li><a> Aggregator </a></li>
        <li><a> CQRS </a></li>
        <li><a> SAGA </a></li>
        <li><a> Event Sourcing </a></li>
        <li><a> API Gateway Pattern </a></li>
        <li><a> Service Registry and Discovery </a></li>
        <li><a> Circuit Breaker Pattern </a></li>
        <li><a> Strangler Fig Pattern </a></li>
        <li><a> Sidecar Pattern </a></li>
      </ul>
    </li>
    <li>
      <a> Message Queues </a>
      <ul>
        <li><a> SQS </a></li>
        <li><a> Kafka </a></li>
        <li><a> RabbitMQ </a></li>
      </ul>
    </li>
    <li>
      <a> API Documentation </a>
      <ul>
        <li><a> Swagger / OpenAPI </a></li>
        <li><a> Spring REST Docs </a></li>
      </ul>
    </li>
  </ol>
</details>

---

# Frontend Roadmap

## 8. Web Fundamentals
<details open>
<summary> <b>Learn Web Fundamentals</b> </summary>
  <ol>
    <li><a> HTML5 </a></li>
    <li><a> CSS3 </a></li>
    <li><a> JavaScript (ES6+) </a></li>
    <li><a> TypeScript Basics </a></li>
    <li><a> Responsive Design </a></li>
    <li><a> Browser DevTools </a></li>
    <li><a> DOM Manipulation </a></li>
  </ol>
</details>

## 9. JSP (JavaServer Pages)
<details open>
<summary> <b>Learn JSP</b> </summary>
  <ol>
    <li><a> JSP Syntax and Directives </a></li>
    <li><a> JSTL (JSP Standard Tag Library) </a></li>
    <li><a> Expression Language (EL) </a></li>
    <li><a> Custom Tags </a></li>
    <li><a> MVC Pattern with Servlets and JSP </a></li>
    <li><a> Session Management in JSP </a></li>
  </ol>
</details>

## 10. Thymeleaf
<details open>
<summary> <b>Learn Thymeleaf</b> </summary>
  <ol>
    <li><a> Template Syntax </a></li>
    <li><a> Spring Boot Integration </a></li>
    <li><a> Fragments and Layouts </a></li>
    <li><a> Form Handling and Data Binding </a></li>
    <li><a> Conditional Rendering and Iteration </a></li>
    <li><a> Internationalization (i18n) </a></li>
    <li><a> Thymeleaf Security Dialect </a></li>
    <li><a> Template Caching </a></li>
  </ol>
</details>

## 11. Vaadin
<details open>
<summary> <b>Learn Vaadin</b> </summary>
  <ol>
    <li><a> Vaadin Flow (Java API) </a></li>
    <li><a> Components and Layouts </a></li>
    <li><a> Data Binding and Validation </a></li>
    <li><a> Theming and Styling </a></li>
    <li><a> Progressive Web Apps (PWA) </a></li>
    <li><a> Integration with Spring Boot </a></li>
    <li><a> Router and Navigation </a></li>
    <li><a> Grid and Data Providers </a></li>
  </ol>
</details>

## 12. JSF (Jakarta Server Faces)
<details open>
<summary> <b>Learn JSF</b> </summary>
  <ol>
    <li><a> JSF Lifecycle </a></li>
    <li><a> Facelets Templates </a></li>
    <li><a> Managed Beans and CDI </a></li>
    <li><a> Navigation and Routing </a></li>
    <li><a> Converters and Validators </a></li>
    <li><a> PrimeFaces / RichFaces Component Libraries </a></li>
    <li><a> AJAX Support in JSF </a></li>
  </ol>
</details>

## 13. JavaFX (Desktop Applications)
<details open>
<summary> <b>Learn JavaFX</b> </summary>
  <ol>
    <li><a> Scene Graph and Stages </a></li>
    <li><a> FXML Layouts </a></li>
    <li><a> CSS Styling </a></li>
    <li><a> Event Handling </a></li>
    <li><a> Animations and Charts </a></li>
    <li><a> Packaging and Distribution </a></li>
    <li><a> JavaFX with Spring Boot </a></li>
    <li><a> TableView and Data Binding </a></li>
  </ol>
</details>

## 14. Modern Java + Frontend Integration
<details open>
<summary> <b>Learn Modern Integration</b> </summary>
  <ol>
    <li><a> REST API Consumption from Frontend </a></li>
    <li><a> WebSocket Communication </a></li>
    <li><a> Server-Sent Events (SSE) </a></li>
    <li><a> Spring + React/Angular/Vue Integration </a></li>
    <li><a> HTMX with Spring Boot </a></li>
    <li><a> GraalVM and Native Images </a></li>
    <li><a> GraphQL with Spring Boot </a></li>
    <li><a> SPA vs Server-Side Rendering (SSR) </a></li>
  </ol>
</details>

---

# Resources for learning Java-Backend

### Docs and Articles
- [Tutorialspoint | Java](https://www.tutorialspoint.com/java/)
- [Spring Framework Official Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/index.html)
- [Spring Boot Official Documentation](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Baeldung - Java and Spring Tutorials](https://www.baeldung.com/)
- [Java Official Documentation (Oracle)](https://docs.oracle.com/en/java/)

### YouTube Channels
- [Amigoscode](https://www.youtube.com/c/amigoscode)
- [Daily Code Buffer](https://www.youtube.com/c/DailyCodeBuffer)
- [Java Brains](https://www.youtube.com/c/JavaBrainsChannel)
- [in28minutes - Cloud Made Easy](https://www.youtube.com/user/rithustutorials)
- [Java Guides](https://www.youtube.com/c/JavaGuides)
- [Laur Spilca](https://www.youtube.com/@laurspilca)
- [Telusko](https://www.youtube.com/c/Telusko)
- [Defog Tech](https://www.youtube.com/@DefogTech)

### Books
- [Head First Java](https://www.amazon.com/Head-First-Java-Kathy-Sierra/dp/0596009208)
- [Spring Start Here](https://www.amazon.com/Spring-Start-Here-Learn-learn/dp/1617298697)
- [Spring Security in Action](https://www.amazon.com/Spring-Security-Action-Laurentiu-Spilca/dp/1617297739)
- [Building Microservices](https://www.amazon.com/Building-Microservices-Designing-Fine-Grained-Systems/dp/1491950358)
- [Effective Java by Joshua Bloch](https://www.amazon.com/Effective-Java-Joshua-Bloch/dp/0134685997)
- [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
- [Spring in Action](https://www.amazon.com/Spring-Action-Craig-Walls/dp/1617297577)

### Projects
- [Inbox App using Spring Boot, Spring Security, and Cassandra](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTak0b5DnJ-x85MWMPaTdl4A)
- [Full Stack Development with Java Spring Boot, React, and MongoDB](https://www.youtube.com/watch?v=5PdEmeopJVQ)

### Helpful Links
- [Common Application Properties in Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/html/application-properties.html)
- [Design Patterns](https://refactoring.guru/design-patterns)
- [Spring Initializr](https://start.spring.io/)
- [Postman (API Testing)](https://www.postman.com/)
- [Docker Hub](https://hub.docker.com/)

### Interview Questions
- [Java Interview Questions](https://www.interviewbit.com/java-interview-questions/)
- [Java and Spring Boot Interview Questions](https://boldcoder.blogspot.com/2024/08/java-and-spring-boot-interview.html)
- [Spring Interview Questions](https://www.interviewbit.com/spring-interview-questions/)
- [REST API Interview Questions](https://www.interviewbit.com/rest-api-interview-questions/)
- [Back-End Developer Interview Questions](https://www.fullstack.cafe/blog/backend-developer-interview-questions)
- [DBMS Interview Questions](https://www.interviewbit.com/dbms-interview-questions/)
- [SQL Interview Questions](https://www.interviewbit.com/sql-interview-questions/)
- [Microservices Interview Questions](https://www.interviewbit.com/microservices-interview-questions/)
- [Docker Interview Questions](https://www.interviewbit.com/docker-interview-questions/)
- [Kubernetes Interview Questions](https://www.interviewbit.com/kubernetes-interview-questions/)

---

# Resources for learning Java-Frontend

### Frontend Docs and Articles
- [Thymeleaf Official Documentation](https://www.thymeleaf.org/documentation.html)
- [Vaadin Official Documentation](https://vaadin.com/docs)
- [Jakarta Faces (JSF) Specification](https://jakarta.ee/specifications/faces/)
- [JavaFX Documentation (OpenJFX)](https://openjfx.io/)
- [HTMX Documentation](https://htmx.org/docs/)
- [MDN Web Docs (HTML, CSS, JS)](https://developer.mozilla.org/)

### Frontend YouTube Channels
- [Amigoscode](https://www.youtube.com/c/amigoscode)
- [Java Brains](https://www.youtube.com/c/JavaBrainsChannel)
- [Vaadin Official](https://www.youtube.com/@vaadin)
- [Fireship](https://www.youtube.com/c/Fireship)
- [The Net Ninja](https://www.youtube.com/c/TheNetNinja)
- [Traversy Media](https://www.youtube.com/c/TraversyMedia)

### Frontend Books
- [Pro JavaFX 9](https://www.amazon.com/Pro-JavaFX-Definitive-Building-Applications/dp/1484230418)
- [Vaadin 14 Cookbook](https://www.amazon.com/dp/1800209029)
- [Learning JavaScript Design Patterns](https://www.amazon.com/Learning-JavaScript-Design-Patterns-Developers/dp/1098139879)

### Frontend Projects
- Build a To-Do App with Spring Boot + Thymeleaf
- Build an Admin Dashboard with Vaadin + Spring Boot
- Build a Chat Application with WebSockets + Spring Boot
- Build a Portfolio Website using JSP + Servlets
- Build a Desktop Note-Taking App with JavaFX
- Build a Real-Time Dashboard with HTMX + Spring Boot

---

# References of the roadmap
- Java Roadmap for Beginners [link](https://youtu.be/lXrr1OohGF0)
- How to Master Spring Boot - Complete Spring Boot Roadmap [link](https://youtu.be/gQHs8pnlagM)
- Learning Spring Boot in 2022 | Roadmap [link](https://youtu.be/YNEUMmtO_6k)

---

# Contribution
If you think that anything can be improved in any way, please do suggest :
  - Open pull request with improvements
  - Discuss ideas in issues

---

### If you found this roadmap helpful, please give it a star!
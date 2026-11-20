# Spring & Spring Boot Interview Questions

## 1. Core Spring Fundamentals
1. [What is Spring Framework?](#sb_001)
2. [Why was Spring introduced?](#sb_002)
3. [What problems does Spring solve?](#sb_003)
4. [What is IoC (Inversion of Control)?](#sb_004)
5. [What is Dependency Injection?](#sb_005)
6. [IoC vs Dependency Injection](#sb_006)
7. [What are the different types of Dependency Injection?](#sb_007)
8. [Constructor Injection](#sb_008)



9. [Setter Injection](#sb_009)



10. [Field Injection](#sb_010)



11. [Constructor vs Setter vs Field Injection](#sb_011)



12. [Why is Constructor Injection recommended?](#sb_012)



13. [What is a Spring Bean?](#sb_013)



14. [Java Object vs Spring Bean](#sb_014)



15. [What is Spring Container?](#sb_015)



16. [What is ApplicationContext?](#sb_016)



17. [What is BeanFactory?](#sb_017)



18. [ApplicationContext vs BeanFactory](#sb_018)



19. [What is Bean Scope?](#sb_019)



20. [Singleton Scope](#sb_020)



21. [Prototype Scope](#sb_021)



22. [Request Scope](#sb_022)



23. [Session Scope](#sb_023)



24. [Application Scope](#sb_024)



25. [WebSocket Scope](#sb_025)



26. [Spring Singleton vs Java Singleton](#sb_026)



27. [Can a Singleton Bean inject a Prototype Bean?](#sb_027)



28. [What problem occurs when Prototype Bean is injected into Singleton?](#sb_028)



29. [What is `@Lookup`?](#sb_029)



30. [What is Bean Lifecycle?](#sb_030)



31. [Explain the complete Spring Bean Lifecycle.](#sb_031)



32. [What is `@PostConstruct`?](#sb_032)



33. [What is `@PreDestroy`?](#sb_033)



34. [What is `InitializingBean`?](#sb_034)



35. [What is `DisposableBean`?](#sb_035)



36. [`@PostConstruct` vs `InitializingBean`](#sb_036)



37. [What are `initMethod` and `destroyMethod`?](#sb_037)



38. [What is `@Component`?](#sb_038)



39. [What is `@Service`?](#sb_039)



40. [What is `@Repository`?](#sb_040)



41. [What is `@Controller`?](#sb_041)



42. [What is `@RestController`?](#sb_042)



43. [`@Controller` vs `@RestController`](#sb_043)



44. [`@Component` vs `@Bean`](#sb_044)



45. [Why do we have `@Service` if `@Component` can do the same thing?](#sb_045)



46. [What special behavior does `@Repository` provide?](#sb_046)



47. [What is Component Scanning?](#sb_047)



48. [How does `@ComponentScan` work?](#sb_048)



49. [What happens if a component is outside the base package?](#sb_049)



50. [What are Spring configuration approaches?](#sb_050)



51. [XML Configuration](#sb_051)



52. [Java Configuration](#sb_052)



53. [Annotation Configuration](#sb_053)



54. [What is `@Configuration`?](#sb_054)



55. [What is `@Bean`?](#sb_055)



56. [What is `@Import`?](#sb_056)



57. [What is `@Value`?](#sb_057)



58. [What is `Environment`?](#sb_058)



59. [What is `@PropertySource`?](#sb_059)



## 2. Spring Internals



1. [How does Spring Container start?](#sb_060)



2. [How does Spring discover Beans?](#sb_061)



3. [How does Spring instantiate Beans?](#sb_062)



4. [How are dependencies resolved?](#sb_063)



5. [How does Spring maintain Beans internally?](#sb_064)



6. [What is `BeanDefinition`?](#sb_065)



7. [What is `BeanDefinitionRegistry`?](#sb_066)



8. [What is `BeanFactoryPostProcessor`?](#sb_067)



9. [What is `BeanPostProcessor`?](#sb_068)



10. [`BeanFactoryPostProcessor` vs `BeanPostProcessor`](#sb_069)



11. [When does BeanPostProcessor execute?](#sb_070)



12. [How does `@Autowired` work internally?](#sb_071)



13. [What is `AutowiredAnnotationBeanPostProcessor`?](#sb_072)



14. [How does Spring resolve dependency by type?](#sb_073)



15. [What happens if multiple Beans of the same type exist?](#sb_074)



16. [What is `NoUniqueBeanDefinitionException`?](#sb_075)



17. [What is `NoSuchBeanDefinitionException`?](#sb_076)



18. [What is `@Qualifier`?](#sb_077)



19. [What is `@Primary`?](#sb_078)



20. [`@Qualifier` vs `@Primary`](#sb_079)



21. [Can `@Autowired` be used on constructors?](#sb_080)



22. [Is `@Autowired` required for a single constructor?](#sb_081)



23. [What is Circular Dependency?](#sb_082)



24. [Why can constructor circular dependency fail?](#sb_083)



25. [How does Spring handle setter/field circular dependency?](#sb_084)



26. [What are Spring's three-level singleton caches?](#sb_085)



27. [What is `singletonObjects`?](#sb_086)



28. [What is `earlySingletonObjects`?](#sb_087)



29. [What is `singletonFactories`?](#sb_088)



30. [Why are circular references discouraged?](#sb_089)



31. [How do you redesign code to remove circular dependencies?](#sb_090)



32. [What is Lazy Initialization?](#sb_091)



33. [What is `@Lazy`?](#sb_092)



34. [Where can `@Lazy` be used?](#sb_093)



35. [Lazy vs Eager initialization](#sb_094)



36. [What is Spring Expression Language (SpEL)?](#sb_095)



37. [What can SpEL be used for?](#sb_096)



38. [What are proxies in Spring?](#sb_097)



39. [JDK Dynamic Proxy vs CGLIB Proxy](#sb_098)



40. [When does Spring use a JDK proxy?](#sb_099)



41. [When does Spring use a CGLIB proxy?](#sb_100)



42. [Why are Spring proxies important?](#sb_101)



43. [What is self-invocation?](#sb_102)



44. [Why can self-invocation bypass Spring proxy behavior?](#sb_103)



45. [Which Spring features depend heavily on proxies?](#sb_104)



## 3. Spring AOP



1. [What is AOP?](#sb_105)



2. [Why was AOP introduced?](#sb_106)



3. [What are Cross-Cutting Concerns?](#sb_107)



4. [What is an Aspect?](#sb_108)



5. [What is Advice?](#sb_109)



6. [What is Join Point?](#sb_110)



7. [What is Pointcut?](#sb_111)



8. [What is Target Object?](#sb_112)



9. [What is Weaving?](#sb_113)



10. [Compile-time vs Load-time vs Runtime weaving](#sb_114)



11. [How does Spring AOP work internally?](#sb_115)



12. [Spring AOP vs AspectJ](#sb_116)



13. [What is `@Aspect`?](#sb_117)



14. [What is `@Before`?](#sb_118)



15. [What is `@After`?](#sb_119)



16. [What is `@AfterReturning`?](#sb_120)



17. [What is `@AfterThrowing`?](#sb_121)



18. [What is `@Around`?](#sb_122)



19. [Which Advice is most powerful?](#sb_123)



20. [What is `ProceedingJoinPoint`?](#sb_124)



21. [What happens if `proceed()` is not called?](#sb_125)



22. [How do you write a Pointcut expression?](#sb_126)



23. [Explain the `execution()` Pointcut expression.](#sb_127)



24. [Can multiple Pointcuts be combined?](#sb_128)



25. [How do you control Aspect execution order?](#sb_129)



26. [What is `@Order`?](#sb_130)



27. [How does AOP use proxies?](#sb_131)



28. [Why does AOP not work as expected with self-invocation?](#sb_132)



29. [Can private methods be intercepted?](#sb_133)



30. [Can final methods cause proxy limitations?](#sb_134)



31. [Logging using AOP](#sb_135)



32. [Performance monitoring using AOP](#sb_136)



33. [Auditing using AOP](#sb_137)



34. [Security using AOP](#sb_138)



35. [Transaction management using AOP](#sb_139)



## 4. Spring Boot Fundamentals and Internals



1. [Why Spring Boot?](#sb_140)



2. [Spring vs Spring MVC vs Spring Boot](#sb_141)



3. [Advantages of Spring Boot](#sb_142)



4. [What is `@SpringBootApplication`?](#sb_143)



5. [What annotations are inside `@SpringBootApplication`?](#sb_144)



6. [What is `@SpringBootConfiguration`?](#sb_145)



7. [What is `@EnableAutoConfiguration`?](#sb_146)



8. [What is `@ComponentScan`?](#sb_147)



9. [What happens when `SpringApplication.run()` executes?](#sb_148)



10. [Explain Spring Boot application startup flow.](#sb_149)



11. [How is `ApplicationContext` created?](#sb_150)



12. [How does component scanning start?](#sb_151)



13. [How does Auto Configuration work?](#sb_152)



14. [What is conditional configuration?](#sb_153)



15. [What is `@Conditional`?](#sb_154)



16. [What is `@ConditionalOnClass`?](#sb_155)



17. [What is `@ConditionalOnMissingBean`?](#sb_156)



18. [What is `@ConditionalOnProperty`?](#sb_157)



19. [What is `@ConditionalOnBean`?](#sb_158)



20. [How does Boot decide which Auto Configurations to load?](#sb_159)



21. [How can Auto Configuration be excluded?](#sb_160)



22. [What are Starter Dependencies?](#sb_161)



23. [How do starters simplify dependency management?](#sb_162)



24. [What is Spring Boot's parent POM?](#sb_163)



25. [What is dependency management?](#sb_164)



26. [What is an Embedded Server?](#sb_165)



27. [How does embedded Tomcat start?](#sb_166)



28. [Tomcat vs Servlet Container](#sb_167)



29. [Tomcat vs Application Server](#sb_168)



30. [How do you replace Tomcat with Jetty or Undertow?](#sb_169)



31. [What is `CommandLineRunner`?](#sb_170)



32. [What is `ApplicationRunner`?](#sb_171)



33. [`CommandLineRunner` vs `ApplicationRunner`](#sb_172)



34. [What are Profiles?](#sb_173)



35. [What is `@Profile`?](#sb_174)



36. [How do dev/test/prod configurations work?](#sb_175)



37. [`application.properties` vs `application.yml`](#sb_176)



38. [Configuration precedence in Spring Boot](#sb_177)



39. [Environment variables vs properties](#sb_178)



40. [What is `@ConfigurationProperties`?](#sb_179)



41. [`@Value` vs `@ConfigurationProperties`](#sb_180)



42. [What is Actuator?](#sb_181)



43. [Important Actuator endpoints](#sb_182)



44. [`health`](#sb_183)



45. [`metrics`](#sb_184)



46. [`info`](#sb_185)



47. [`beans`](#sb_186)



48. [`env`](#sb_187)



49. [How do you secure Actuator endpoints?](#sb_188)



## 5. Spring MVC and REST API



1. [What is Spring MVC?](#sb_189)



2. [Explain MVC Architecture.](#sb_190)



3. [What is DispatcherServlet?](#sb_191)



4. [Explain the complete request lifecycle.](#sb_192)



5. [What is HandlerMapping?](#sb_193)



6. [What is HandlerAdapter?](#sb_194)



7. [What is ViewResolver?](#sb_195)



8. [How does Spring identify the correct Controller method?](#sb_196)



9. [`@Controller` vs `@RestController`](#sb_197)



10. [What is `@RequestMapping`?](#sb_198)



11. [What is `@GetMapping`?](#sb_199)



12. [What is `@PostMapping`?](#sb_200)



13. [What is `@PutMapping`?](#sb_201)



14. [What is `@PatchMapping`?](#sb_202)



15. [What is `@DeleteMapping`?](#sb_203)



16. [What is `@PathVariable`?](#sb_204)



17. [What is `@RequestParam`?](#sb_205)



18. [What is `@RequestBody`?](#sb_206)



19. [What is `@RequestHeader`?](#sb_207)



20. [What is `@ResponseBody`?](#sb_208)



21. [What is `ResponseEntity`?](#sb_209)



22. [Why use `ResponseEntity`?](#sb_210)



23. [POST vs PUT vs PATCH](#sb_211)



24. [PUT vs PATCH](#sb_212)



25. [What does idempotent mean?](#sb_213)



26. [Which HTTP methods are idempotent?](#sb_214)



27. [Important HTTP Status Codes](#sb_215)



28. [`200` vs `201`](#sb_216)



29. [`400` vs `422`](#sb_217)



30. [`401` vs `403`](#sb_218)



31. [`404` vs `204`](#sb_219)



32. [When should `409 Conflict` be used?](#sb_220)



33. [REST API naming conventions](#sb_221)



34. [API versioning](#sb_222)



35. [URI versioning vs Header versioning](#sb_223)



36. [Pagination in REST APIs](#sb_224)



37. [Sorting APIs](#sb_225)



38. [Filtering APIs](#sb_226)



39. [API Error Response Design](#sb_227)



40. [How should you return validation errors?](#sb_228)



41. [What is Content Negotiation?](#sb_229)



42. [JSON Serialization and Deserialization](#sb_230)



43. [How does Jackson work with Spring?](#sb_231)



44. [What is `@JsonIgnore`?](#sb_232)



45. [What is `@JsonIgnoreProperties`?](#sb_233)



46. [What is `@JsonManagedReference`?](#sb_234)



47. [What is `@JsonBackReference`?](#sb_235)



48. [How do you prevent infinite JSON recursion?](#sb_236)



49. [Why should Entities normally not be exposed directly from REST APIs?](#sb_237)



50. [Entity vs DTO](#sb_238)



51. [Request DTO vs Response DTO](#sb_239)



52. [DTO mapping approaches](#sb_240)



## 6. Exception Handling and Validation



1. [How does Spring exception handling work?](#sb_241)



2. [What is `@ExceptionHandler`?](#sb_242)



3. [What is `@ControllerAdvice`?](#sb_243)



4. [What is `@RestControllerAdvice`?](#sb_244)



5. [Local vs Global Exception Handling](#sb_245)



6. [How do you create Custom Exceptions?](#sb_246)



7. [What is `ResponseStatusException`?](#sb_247)



8. [How should a Global Error Response be designed?](#sb_248)



9. [How should validation errors be handled?](#sb_249)



10. [What is Bean Validation?](#sb_250)



11. [What is `@Valid`?](#sb_251)



12. [What is `@Validated`?](#sb_252)



13. [`@Valid` vs `@Validated`](#sb_253)



14. [What is `@NotNull`?](#sb_254)



15. [What is `@NotEmpty`?](#sb_255)



16. [What is `@NotBlank`?](#sb_256)



17. [What is `@Size`?](#sb_257)



18. [What are `@Min` and `@Max`?](#sb_258)



19. [What is `@Pattern`?](#sb_259)



20. [What is `@Email`?](#sb_260)



21. [How does nested DTO validation work?](#sb_261)



22. [How does custom validation work?](#sb_262)



23. [How do you create a custom validation annotation?](#sb_263)



24. [What is `ConstraintValidator`?](#sb_264)



25. [How do you implement cross-field validation?](#sb_265)



## 7. Filters, Interceptors and Events



1. [What is a Servlet Filter?](#sb_266)



2. [What is `HandlerInterceptor`?](#sb_267)



3. [Filter vs Interceptor](#sb_268)



4. [Where does a Filter execute?](#sb_269)



5. [Where does an Interceptor execute?](#sb_270)



6. [What is `preHandle()`?](#sb_271)



7. [What is `postHandle()`?](#sb_272)



8. [What is `afterCompletion()`?](#sb_273)



9. [When should you use a Filter?](#sb_274)



10. [When should you use an Interceptor?](#sb_275)



11. [Filter vs Interceptor vs AOP](#sb_276)



12. [How would you implement Request Logging?](#sb_277)



13. [How would you implement Correlation IDs?](#sb_278)



14. [What is `OncePerRequestFilter`?](#sb_279)



15. [What are Spring Events?](#sb_280)



16. [What is `ApplicationEventPublisher`?](#sb_281)



17. [What is `@EventListener`?](#sb_282)



18. [What is `@TransactionalEventListener`?](#sb_283)



19. [Synchronous vs asynchronous event handling](#sb_284)



## 8. Spring Data JPA and Hibernate



1. [What is ORM?](#sb_285)



2. [JDBC vs JPA vs Hibernate](#sb_286)



3. [JPA vs Hibernate](#sb_287)



4. [What is an Entity?](#sb_288)



5. [What are Entity class requirements?](#sb_289)



6. [What is `@Entity`?](#sb_290)



7. [What is `@Table`?](#sb_291)



8. [What is `@Id`?](#sb_292)



9. [What is `@GeneratedValue`?](#sb_293)



10. [What are ID generation strategies?](#sb_294)



11. [What is Persistence Context?](#sb_295)



12. [Explain the Entity Lifecycle.](#sb_296)



13. [What is Transient State?](#sb_297)



14. [What is Managed/Persistent State?](#sb_298)



15. [What is Detached State?](#sb_299)



16. [What is Removed State?](#sb_300)



17. [`persist()` vs `merge()`](#sb_301)



18. [What is Dirty Checking?](#sb_302)



19. [How does Hibernate Dirty Checking work?](#sb_303)



20. [What is `EntityManager`?](#sb_304)



21. [What is First-Level Cache?](#sb_305)



22. [Why is First-Level Cache enabled by default?](#sb_306)



23. [What is Second-Level Cache?](#sb_307)



24. [First-Level vs Second-Level Cache](#sb_308)



25. [What is Query Cache?](#sb_309)



26. [What is Lazy Loading?](#sb_310)



27. [What is Eager Loading?](#sb_311)



28. [LAZY vs EAGER](#sb_312)



29. [Default fetch type of `@OneToMany`](#sb_313)



30. [Default fetch type of `@ManyToOne`](#sb_314)



31. [Default fetch type of `@OneToOne`](#sb_315)



32. [Default fetch type of `@ManyToMany`](#sb_316)



33. [What is `LazyInitializationException`?](#sb_317)



34. [Why does `LazyInitializationException` occur?](#sb_318)



35. [How do you solve `LazyInitializationException` correctly?](#sb_319)



36. [What is Open Session in View?](#sb_320)



37. [Advantages and disadvantages of Open Session in View](#sb_321)



38. [What is the N+1 problem?](#sb_322)



39. [How do you identify N+1 queries?](#sb_323)



40. [How do you resolve N+1 queries?](#sb_324)



41. [What is Fetch Join?](#sb_325)



42. [What is `@EntityGraph`?](#sb_326)



43. [What is Batch Fetching?](#sb_327)



44. [What is Cascade?](#sb_328)



45. [`CascadeType.PERSIST`](#sb_329)



46. [`CascadeType.MERGE`](#sb_330)



47. [`CascadeType.REMOVE`](#sb_331)



48. [`CascadeType.REFRESH`](#sb_332)



49. [`CascadeType.DETACH`](#sb_333)



50. [`CascadeType.ALL`](#sb_334)



51. [What is `orphanRemoval`?](#sb_335)



52. [`CascadeType.REMOVE` vs `orphanRemoval`](#sb_336)



53. [One-to-One mapping](#sb_337)



54. [One-to-Many mapping](#sb_338)



55. [Many-to-One mapping](#sb_339)



56. [Many-to-Many mapping](#sb_340)



57. [Owning Side vs Inverse Side](#sb_341)



58. [What is `mappedBy`?](#sb_342)



59. [What is `@JoinColumn`?](#sb_343)



60. [What is `@JoinTable`?](#sb_344)



61. [Bidirectional vs Unidirectional mapping](#sb_345)



62. [How do you keep both sides of a bidirectional relationship synchronized?](#sb_346)



63. [What problems can happen if both sides are not synchronized?](#sb_347)



64. [What is JPQL?](#sb_348)



65. [JPQL vs SQL](#sb_349)



66. [What is a Native Query?](#sb_350)



67. [JPQL vs Native Query](#sb_351)



68. [What are Named Queries?](#sb_352)



69. [What are Spring Data Derived Query Methods?](#sb_353)



70. [How does `findByName` work?](#sb_354)



71. [How does `existsByEmail` work?](#sb_355)



72. [What does `IgnoreCase` mean in a derived query?](#sb_356)



73. [What does `Containing` mean?](#sb_357)



74. [How are `And` and `Or` used in derived queries?](#sb_358)



75. [How are `GreaterThan` and `LessThan` used?](#sb_359)



76. [What is `@Query`?](#sb_360)



77. [What are JPA Specifications?](#sb_361)



78. [When should you use Specifications?](#sb_362)



79. [How do you implement Dynamic Querying?](#sb_363)



80. [What is `Pageable`?](#sb_364)



81. [What is `Page`?](#sb_365)



82. [What is `Slice`?](#sb_366)



83. [Page vs Slice](#sb_367)



84. [Pagination and Sorting](#sb_368)



85. [What is Optimistic Locking?](#sb_369)



86. [What is Pessimistic Locking?](#sb_370)



87. [What is `@Version`?](#sb_371)



88. [Optimistic vs Pessimistic Locking](#sb_372)



## 9. Transaction Management



1. [What is a Transaction?](#sb_373)



2. [What is `@Transactional`?](#sb_374)



3. [How does `@Transactional` work internally?](#sb_375)



4. [How does Spring use AOP for transactions?](#sb_376)



5. [What is `PlatformTransactionManager`?](#sb_377)



6. [When is a transaction started?](#sb_378)



7. [When is it committed?](#sb_379)



8. [When is it rolled back?](#sb_380)



9. [Runtime Exception vs Checked Exception rollback behavior](#sb_381)



10. [What is `rollbackFor`?](#sb_382)



11. [What is `noRollbackFor`?](#sb_383)



12. [Can `@Transactional` be placed on a class?](#sb_384)



13. [Class-level vs method-level `@Transactional`](#sb_385)



14. [Why does `@Transactional` not work as expected on private methods in proxy-based Spring AOP?](#sb_386)



15. [What is the transactional self-invocation problem?](#sb_387)



16. [What happens when one transactional method calls another?](#sb_388)



17. [What is `readOnly = true`?](#sb_389)



18. [What is transaction timeout?](#sb_390)



19. [Propagation `REQUIRED`](#sb_391)



20. [Propagation `REQUIRES_NEW`](#sb_392)



21. [Propagation `SUPPORTS`](#sb_393)



22. [Propagation `NOT_SUPPORTED`](#sb_394)



23. [Propagation `MANDATORY`](#sb_395)



24. [Propagation `NEVER`](#sb_396)



25. [Propagation `NESTED`](#sb_397)



26. [`REQUIRED` vs `REQUIRES_NEW`](#sb_398)



27. [`REQUIRES_NEW` vs `NESTED`](#sb_399)



28. [What are Transaction Isolation Levels?](#sb_400)



29. [`READ_UNCOMMITTED`](#sb_401)



30. [`READ_COMMITTED`](#sb_402)



31. [`REPEATABLE_READ`](#sb_403)



32. [`SERIALIZABLE`](#sb_404)



33. [What is Dirty Read?](#sb_405)



34. [What is Non-Repeatable Read?](#sb_406)



35. [What is Phantom Read?](#sb_407)



36. [What is Lost Update?](#sb_408)



37. [Database isolation vs Spring isolation](#sb_409)



38. [What does `Isolation.DEFAULT` mean?](#sb_410)



## 10. Spring Security



1. [What is Spring Security?](#sb_411)



2. [Authentication vs Authorization](#sb_412)



3. [How does Spring Security work?](#sb_413)



4. [Explain the Security Filter Chain.](#sb_414)



5. [What is `SecurityFilterChain`?](#sb_415)



6. [What is `Authentication`?](#sb_416)



7. [What is `AuthenticationManager`?](#sb_417)



8. [What is `AuthenticationProvider`?](#sb_418)



9. [What is `UserDetailsService`?](#sb_419)



10. [What is `UserDetails`?](#sb_420)



11. [What is `PasswordEncoder`?](#sb_421)



12. [Why use BCrypt?](#sb_422)



13. [Roles vs Authorities](#sb_423)



14. [What is `SecurityContext`?](#sb_424)



15. [What is `SecurityContextHolder`?](#sb_425)



16. [Session-based authentication](#sb_426)



17. [Token-based authentication](#sb_427)



18. [What is JWT?](#sb_428)



19. [Explain JWT Structure.](#sb_429)



20. [JWT Header](#sb_430)



21. [JWT Payload](#sb_431)



22. [JWT Signature](#sb_432)



23. [How is JWT generated?](#sb_433)



24. [How is JWT validated?](#sb_434)



25. [Access Token vs Refresh Token](#sb_435)



26. [Where should tokens be stored?](#sb_436)



27. [JWT expiration handling](#sb_437)



28. [Explain JWT Filter flow.](#sb_438)



29. [What is `OncePerRequestFilter` in Spring Security?](#sb_439)



30. [`401` vs `403`](#sb_440)



31. [What is CSRF?](#sb_441)



32. [Why is CSRF often disabled for stateless APIs?](#sb_442)



33. [What is CORS?](#sb_443)



34. [CORS vs CSRF](#sb_444)



35. [What is OAuth2?](#sb_445)



36. [What are OAuth2 roles?](#sb_446)



37. [What is Authorization Code Flow?](#sb_447)



38. [OAuth2 vs JWT](#sb_448)



39. [What is OpenID Connect?](#sb_449)



## 11. Microservices



1. [Monolith vs Microservices](#sb_450)



2. [Advantages of Microservices](#sb_451)



3. [Disadvantages of Microservices](#sb_452)



4. [When should you NOT use Microservices?](#sb_453)



5. [How do Microservices communicate?](#sb_454)



6. [Synchronous vs Asynchronous communication](#sb_455)



7. [REST communication between services](#sb_456)



8. [What is OpenFeign?](#sb_457)



9. [Feign vs RestTemplate](#sb_458)



10. [Feign vs WebClient](#sb_459)



11. [What is Service Discovery?](#sb_460)



12. [What is Eureka Server?](#sb_461)



13. [What is Eureka Client?](#sb_462)



14. [What is an API Gateway?](#sb_463)



15. [What responsibilities should a Gateway have?](#sb_464)



16. [Authentication at Gateway vs Service](#sb_465)



17. [What is Load Balancing?](#sb_466)



18. [Client-side vs Server-side Load Balancing](#sb_467)



19. [What is Circuit Breaker?](#sb_468)



20. [What problem does Circuit Breaker solve?](#sb_469)



21. [What are Circuit Breaker states?](#sb_470)



22. [CLOSED state](#sb_471)



23. [OPEN state](#sb_472)



24. [HALF_OPEN state](#sb_473)



25. [What is Resilience4j?](#sb_474)



26. [What is Retry Pattern?](#sb_475)



27. [What is Timeout Pattern?](#sb_476)



28. [What is Bulkhead Pattern?](#sb_477)



29. [Circuit Breaker vs Retry](#sb_478)



30. [What is Distributed Tracing?](#sb_479)



31. [What is Correlation ID?](#sb_480)



32. [What is centralized logging?](#sb_481)



33. [What is eventual consistency?](#sb_482)



34. [What is a Distributed Transaction?](#sb_483)



35. [Why does normal `@Transactional` not work across microservices?](#sb_484)



36. [What is Saga Pattern?](#sb_485)



37. [What is Choreography-based Saga?](#sb_486)



38. [What is Orchestration-based Saga?](#sb_487)



39. [Choreography vs Orchestration](#sb_488)



40. [What is Outbox Pattern?](#sb_489)



41. [What is Idempotency in Microservices?](#sb_490)



42. [What happens if the same message is consumed twice?](#sb_491)



43. [How do you design retry-safe APIs?](#sb_492)



## 12. Caching, Async and Scheduling



1. [What is Spring Cache?](#sb_493)



2. [What is `@EnableCaching`?](#sb_494)



3. [What is `@Cacheable`?](#sb_495)



4. [What is `@CachePut`?](#sb_496)



5. [What is `@CacheEvict`?](#sb_497)



6. [`@Cacheable` vs `@CachePut`](#sb_498)



7. [Local vs Distributed Cache](#sb_499)



8. [What is Redis?](#sb_500)



9. [When would you use Redis caching?](#sb_501)



10. [What is Cache-Aside Pattern?](#sb_502)



11. [What are cache invalidation problems?](#sb_503)



12. [What is a cache stampede?](#sb_504)



13. [What happens when cached data becomes stale?](#sb_505)



14. [What is `@Async`?](#sb_506)



15. [How does `@Async` work internally?](#sb_507)



16. [Why can self-invocation break `@Async`?](#sb_508)



17. [What is `CompletableFuture`?](#sb_509)



18. [How do you configure a ThreadPool?](#sb_510)



19. [What is `@Scheduled`?](#sb_511)



20. [`fixedRate` vs `fixedDelay`](#sb_512)



21. [What is a Cron expression?](#sb_513)



## 13. Testing Spring Boot Applications



1. [Unit Test vs Integration Test](#sb_514)



2. [What is JUnit 5?](#sb_515)



3. [What is Mockito?](#sb_516)



4. [What is `@Mock`?](#sb_517)



5. [What is `@InjectMocks`?](#sb_518)



6. [What is `@MockBean`?](#sb_519)



7. [`@Mock` vs Spring-context mock replacement approaches](#sb_520)



8. [What is `Mockito.when()`?](#sb_521)



9. [What is `verify()`?](#sb_522)



10. [What is `ArgumentCaptor`?](#sb_523)



11. [How do you test Service classes?](#sb_524)



12. [How do you test Controllers?](#sb_525)



13. [What is MockMvc?](#sb_526)



14. [What is `@WebMvcTest`?](#sb_527)



15. [What is `@DataJpaTest`?](#sb_528)



16. [What is `@SpringBootTest`?](#sb_529)



17. [`@WebMvcTest` vs `@SpringBootTest`](#sb_530)



18. [How do you test Repository queries?](#sb_531)



19. [H2 vs real database testing](#sb_532)



20. [What is Testcontainers?](#sb_533)



21. [Why use Testcontainers for integration tests?](#sb_534)



## 14. Production, Performance and Observability



1. [How do you monitor a Spring Boot application?](#sb_535)



2. [What is Spring Boot Actuator?](#sb_536)



3. [Liveness vs Readiness](#sb_537)



4. [What is Micrometer?](#sb_538)



5. [What are application metrics?](#sb_539)



6. [How do you identify a slow API?](#sb_540)



7. [How do you identify slow DB queries?](#sb_541)



8. [What is Connection Pooling?](#sb_542)



9. [What is HikariCP?](#sb_543)



10. [What happens when the DB connection pool is exhausted?](#sb_544)



11. [Connection timeout vs Query timeout](#sb_545)



12. [How do you tune Hibernate queries?](#sb_546)



13. [How do you identify N+1 in production?](#sb_547)



14. [What is distributed tracing?](#sb_548)



15. [How does Correlation ID help debugging?](#sb_549)



16. [Logs vs Metrics vs Traces](#sb_550)



17. [How do you handle application configuration securely?](#sb_551)



18. [Why should credentials not be kept directly in `application.properties`?](#sb_552)



19. [What is Graceful Shutdown?](#sb_553)



20. [What are Health Checks?](#sb_554)



21. [What happens when downstream services become slow?](#sb_555)



22. [How do you prevent one slow dependency from exhausting application threads?](#sb_556)



23. [How would you troubleshoot high CPU?](#sb_557)



24. [How would you troubleshoot high memory usage?](#sb_558)



25. [How would you troubleshoot DB connection exhaustion?](#sb_559)



26. [How would you troubleshoot increasing response time?](#sb_560)



## 15. Senior-Level Scenario-Based Interview Questions



### Scenario 1: Missing Bean



1. [Why can this happen?](#sb_561)



2. [How would you investigate component scanning?](#sb_562)



3. [Could a missing `@Service` or `@Bean` cause it?](#sb_563)



4. [Could package structure cause it?](#sb_564)



5. [How would you fix it?](#sb_565)



### Scenario 2: Multiple Implementations



6. [Why can the application fail to start?](#sb_566)



7. [What exception do you expect?](#sb_567)



8. [Would you use `@Qualifier` or `@Primary`?](#sb_568)



9. [What is the difference?](#sb_569)



10. [Which approach is better when the implementation must be selected dynamically?](#sb_570)



### Scenario 3: Circular Dependency



11. [What happens?](#sb_571)



12. [Why is constructor-based circular dependency problematic?](#sb_572)



13. [Can `@Lazy` change the behavior?](#sb_573)



14. [Why is `@Lazy` often only a workaround?](#sb_574)



15. [How would you redesign the services to remove the cycle?](#sb_575)



### Scenario 4: Runtime Failure



16. [What happens to the transaction?](#sb_576)



17. [Will the order be committed?](#sb_577)



18. [Why?](#sb_578)



19. [When could the result be different?](#sb_579)



### Scenario 5: REQUIRES_NEW and Self Invocation



20. [Will `REQUIRES_NEW` necessarily create a new transaction?](#sb_580)



21. [Explain Spring proxy-based transaction management.](#sb_581)



22. [What is self-invocation?](#sb_582)



23. [How would you redesign this code?](#sb_583)



### Scenario 6: Checked Exception



24. [Why can this happen?](#sb_584)



25. [What are Spring's default rollback rules?](#sb_585)



26. [How can `rollbackFor` change the behavior?](#sb_586)



### Scenario 7: Independent Audit Transaction



27. [Would `REQUIRED` or `REQUIRES_NEW` better match an independent audit transaction?](#sb_587)



28. [What happens to the outer transaction when the inner transaction fails?](#sb_588)



29. [What trade-offs come with `REQUIRES_NEW`?](#sb_589)



30. [How could an event/outbox design change the solution?](#sb_590)



### Scenario 8: N+1 Queries



31. [What happened?](#sb_591)



32. [Why can LAZY relationships cause this access pattern?](#sb_592)



33. [How would a fetch join help?](#sb_593)



34. [When would you use `@EntityGraph`?](#sb_594)



35. [What is batch fetching?](#sb_595)



### Scenario 9: LazyInitializationException



36. [Why did it happen?](#sb_596)



37. [What is the Persistence Context?](#sb_597)



38. [What is the transaction boundary?](#sb_598)



39. [Why is changing every relationship to EAGER usually a poor fix?](#sb_599)



40. [How would DTO projection, fetch join, or EntityGraph help?](#sb_600)



### Scenario 10: Owning Side vs Inverse Side



41. [Which side is the owning side?](#sb_601)



42. [Why?](#sb_602)



43. [Which side contains the foreign key?](#sb_603)



44. [What does `mappedBy` mean?](#sb_604)



45. [What can happen if you only call `department.getEmployees().add(employee)` without `employee.setDepartment(department)`?](#sb_605)



46. [Why are helper methods useful for bidirectional relationships?](#sb_606)



### Scenario 11: Concurrent Update



47. [What kind of lost-update problem can occur?](#sb_607)



48. [How does `@Version` help?](#sb_608)



49. [What is optimistic locking?](#sb_609)



50. [When would pessimistic locking be more suitable?](#sb_610)



### Scenario 12: Duplicate User



51. [Would you return `400`, `404`, `409`, or `500`?](#sb_611)



52. [Why is `409 Conflict` often appropriate?](#sb_612)



53. [Where should the duplicate-email business rule be checked?](#sb_613)



54. [How should a database unique constraint complement application validation?](#sb_614)



### Scenario 13: Infinite JSON Recursion



55. [Why did this happen?](#sb_615)



56. [How do bidirectional relationships affect Jackson serialization?](#sb_616)



57. [What does `@JsonIgnore` do?](#sb_617)



58. [What does `@JsonIgnoreProperties` do?](#sb_618)



59. [Why can DTOs provide a cleaner API contract?](#sb_619)



### Scenario 14: Request Validation



60. [Which validation annotations would you use?](#sb_620)



61. [Where should `@Valid` be placed?](#sb_621)



62. [What exception is produced for invalid request-body validation?](#sb_622)



63. [How would `@RestControllerAdvice` handle it?](#sb_623)



64. [How would you return field-specific validation errors?](#sb_624)



### Scenario 15: API Suddenly Becomes Slow



65. [Which metric would you inspect first?](#sb_625)



66. [How would a trace identify a slow downstream call?](#sb_626)



67. [How would you detect connection-pool waiting?](#sb_627)



68. [How could a newly introduced N+1 query explain the issue?](#sb_628)



### Scenario 16: Slow Downstream Service



69. [Why can one slow downstream service affect unrelated requests?](#sb_629)



70. [How can blocked request threads cause resource exhaustion?](#sb_630)



71. [Where would you configure connect/read/response timeouts?](#sb_631)



72. [When would you use Circuit Breaker?](#sb_632)



73. [What does Bulkhead isolation solve?](#sb_633)



74. [When is Retry dangerous?](#sb_634)



### Scenario 17: Distributed Order Transaction



75. [Why can one normal local `@Transactional` method not atomically cover independent service databases?](#sb_635)



76. [What is Saga?](#sb_636)



77. [What is a compensating transaction?](#sb_637)



78. [Choreography vs Orchestration?](#sb_638)



79. [What does eventual consistency mean here?](#sb_639)



80. [How could an Outbox Pattern improve event reliability?](#sb_640)



### Scenario 18: Duplicate Event



81. [Why should consumers be designed as idempotent?](#sb_641)



82. [How could an event ID or processed-message table help?](#sb_642)



83. [How could a database unique constraint help?](#sb_643)



84. [What happens during retry after a partially completed operation?](#sb_644)



### Scenario 19: Payment Service Down



85. [Should you retry?](#sb_645)



86. [Should you fail fast?](#sb_646)



87. [Should you use Circuit Breaker?](#sb_647)



88. [Could the request be queued?](#sb_648)



89. [Why must the business requirement determine the strategy?](#sb_649)



90. [Which failures are safe to retry?](#sb_650)



### Scenario 20: JWT Expiration



91. [How should the API respond?](#sb_651)



92. [What is a refresh token?](#sb_652)



93. [How is a new access token issued?](#sb_653)



94. [When should reauthentication be required?](#sb_654)



95. [How should refresh-token revocation/rotation be handled?](#sb_655)



### Scenario 21: JWT Tampering



96. [Why should the server not trust the payload without verifying the token?](#sb_656)



97. [How does the signature detect modification?](#sb_657)



98. [What should happen if signature verification fails?](#sb_658)



99. [Why should authorization still be enforced server-side?](#sb_659)



### Scenario 22: Authentication vs Authorization



100. [Is this authentication failure or authorization failure?](#sb_660)



101. [Should the response normally be `401` or `403`?](#sb_661)



102. [Where would authorization rules be configured?](#sb_662)



103. [When would method security such as `@PreAuthorize` be useful?](#sb_663)



### Scenario 23: Database Connection Pool Exhaustion



104. [Connection leak](#sb_664)



105. [Slow queries](#sb_665)



106. [Long transactions](#sb_666)



107. [Database overload](#sb_667)



108. [Incorrect pool sizing](#sb_668)



109. [Traffic spike](#sb_669)



110. [How would you identify the real cause?](#sb_670)



111. [Which HikariCP metrics would you inspect?](#sb_671)



112. [Why can increasing the pool size blindly make things worse?](#sb_672)



113. [How can long-running transactions exhaust connections?](#sb_673)



### Scenario 24: OutOfMemoryError



114. [How would you investigate heap usage?](#sb_674)



115. [What does GC behavior tell you?](#sb_675)



116. [When would you capture a heap dump?](#sb_676)



117. [What are retained objects?](#sb_677)



118. [How can caches cause memory problems?](#sb_678)



119. [How can static collections cause leaks?](#sb_679)



120. [How can `ThreadLocal` usage cause leaks?](#sb_680)



121. [Which resources must be closed correctly?](#sb_681)



---


## 1. Core Spring Fundamentals

---

<h3 id="sb_001">What is Spring Framework?</h3>
Spring Framework is a lightweight Java-based framework used to build enterprise applications. Its core principle is Inversion of Control(Ioc), where the Spring container creates and manages application objects called beans and injects their dependencies instead of the application creating objects manually. It also provides support for AOP, transaction management, web applications, security integration, data access, which help us build loosely coupled and maintainable applications.

---

<h3 id="sb_002">Why was Spring introduced?</h3>
Spring was introduced to overcome the complexity of traditional Java enterprise development, especially the heavy infrastructure and tight coupling common in older J2EE applications.It provides IoC and Dependency Injection so that object creation and dependency management are handled by the Spring container. This makes applications more loosely coupled, testable, maintainable, and easier to extend.

### Mainly to provide:

Loose coupling through Dependency Injection
IoC for object creation and lifecycle management
Easier unit testing
Less infrastructure/boilerplate code
Declarative transaction management
AOP for cross-cutting concerns
Easier database and web application development
Better modularity and maintainability

---

<h3 id="sb_003">What problems does Spring solve?</h3>

Spring mainly solves the problems that make enterprise Java applications **tightly coupled, difficult to test, difficult to maintain, and full of repetitive infrastructure code**.

---

## 🔗 1. Tight Coupling between classes

### ❌ Without Spring

```java
public class OrderService {

    private PaymentService paymentService = new PaymentService();
}
```

Here, `OrderService` directly creates its dependency.

```text
OrderService
     ↓
     ↓ creates
     ↓
PaymentService
```

This creates **tight coupling** between the classes.

If the implementation changes from:

```text
PaymentService
      ↓
StripePaymentService
      ↓
RazorpayPaymentService
```

we may need to modify the dependent class.

### ✅ With Spring

```java
@Service
public class OrderService {

    private final PaymentService paymentService;

    public OrderService(PaymentService paymentService) {
        this.paymentService = paymentService;
    }
}
```

Now:

```text
Spring Container
      ↓
Creates PaymentService
      ↓
Creates OrderService
      ↓
Injects PaymentService
      ↓
OrderService is ready
```

✅ This provides **loose coupling**.

---

## 🏗️ 2. Manual Object Creation

### ❌ Without Spring

Developers may manually create objects:

```java
PaymentService paymentService = new PaymentService();

OrderRepository repository = new OrderRepository();

OrderService orderService =
        new OrderService(repository, paymentService);
```

For a small application this may look manageable.

But imagine:

```text
50 Services
30 Repositories
20 Controllers
Multiple external clients
Multiple configurations
```

Managing all these dependencies manually becomes difficult.

### ✅ Spring Solution

Spring provides:

```text
IoC Container
      +
Dependency Injection
```

The Spring Container handles:

- ✅ Object creation
- ✅ Dependency resolution
- ✅ Dependency injection
- ✅ Bean configuration
- ✅ Bean lifecycle management

---

## 🧪 3. Difficult Unit Testing

### ❌ Tightly Coupled Code

```java
public class OrderService {

    private PaymentService paymentService =
            new PaymentService();
}
```

Now OrderService is tightly coupled to the real PaymentService.

`OrderService` decides which `PaymentService` implementation to create.

That makes replacing it with a mock more difficult while testing.

### ✅ With Dependency Injection (constructor injection)

```java
public class OrderService {

    private final PaymentService paymentService;

    public OrderService(PaymentService paymentService) {
        this.paymentService = paymentService;
    }
}
```

Production:

```text
OrderService
     ↓
Real PaymentService
```

Testing:

```text
OrderService
     ↓
Mock PaymentService
```

✅ Dependencies can easily be replaced with mocks or stubs.

---

## 🔄 4. Transaction Management

Consider an order operation:

```text
Create Order
     ↓
Save Payment
     ↓
Update Inventory
```

These database operations may need to succeed or fail together.

### ❌ Without spring declarative transaction management

We would need infrastructure code for:

```text
Start Transaction
Execute Operations
Commit
Rollback
Exception Handling
Resource Management
```

### ✅ With Spring

```java
@Transactional
public void createOrder() {

    saveOrder();

    savePayment();

    updateInventory();
}
```

Spring handles the transaction boundary.

```text
        Start Transaction
               ↓
          saveOrder()
               ↓
         savePayment()
               ↓
       updateInventory()
               ↓
          Successful?
          /        \
        YES         NO
         ↓           ↓
      COMMIT      ROLLBACK
```

This is much easier than manually managing transactions.

---

## 🎯 5. Cross-Cutting Concerns

Some functionality is required in many classes.

Examples:

- 📝 Logging
- 🔐 Security
- 📊 Performance monitoring
- 📋 Auditing
- 🔄 Transaction management

Without a centralized mechanism:

```text
OrderService      → Logging
PaymentService    → Logging
CustomerService   → Logging
InventoryService  → Logging
```

We could end up repeating similar infrastructure code.

### ✅ Spring Solution: AOP

```text
             Logging Aspect
                  ↓
        ┌─────────┼─────────┐
        ↓         ↓         ↓
   OrderService PaymentService InventoryService
```

Spring AOP allows us to separate **cross-cutting concerns** from business logic.

---

## 🗄️ 6. Database Access Complexity

Traditional database code can involve a lot of repetitive work:

```text
Open connection
↓
Create statement
↓
Execute query
↓
Read ResultSet
↓
Map result
↓
Handle exception
↓
Close resources
```

This creates repetitive infrastructure code.

### ✅ With Spring Data JPA

```java
public interface OrderRepository
        extends JpaRepository<Order, Long> {
}
```

Now common operations are available directly:

```java
orderRepository.save(order);

orderRepository.findById(id);

orderRepository.findAll();

orderRepository.deleteById(id);
```

This reduces repetitive persistence-layer code.

✅ Less boilerplate  
✅ Cleaner repository layer  
✅ Easier maintenance

---

## ⚙️ 7. Object Lifecycle and Configuration

Enterprise applications contain many objects and dependencies.

Spring Container manages:

```text
Bean Definition
      ↓
Bean Creation
      ↓
Dependency Injection
      ↓
Initialization
      ↓
Bean Ready
      ↓
Destruction
```

So developers can focus more on **business logic** rather than object-management infrastructure.

---

## 🧠 Quick Revision Table

| Problem | Spring Solution |
|---|---|
| 🔗 Tight coupling | Dependency Injection |
| 🏗️ Manual object creation | IoC Container |
| 🧪 Difficult testing | Dependency Injection |
| 🎯 Cross-cutting concerns | Spring AOP |
| 🔄 Transaction complexity | `@Transactional` |
| 🗄️ Database boilerplate | Spring Data |
| ⚙️ Object lifecycle | Spring Container |


### 🎤 Interview-Ready Answer

> **Spring solves several common problems in enterprise Java applications, especially tight coupling, manual object creation, dependency management, transaction management, cross-cutting concerns, and repetitive data-access code.**
>
> **Using IoC and Dependency Injection, Spring manages application objects and their dependencies, making the application loosely coupled, testable, and maintainable. It also provides AOP, declarative transaction management, MVC, and data-access abstractions, which reduce infrastructure boilerplate.**

---

<h2 id="sb_004">What is IoC (Inversion of Control)?</h2>

**IoC stands for Inversion of Control.**

IoC is a design principle where the **control of creating objects, configuring them, managing their lifecycle, and providing their dependencies is transferred from the application code to the Spring Container**.

    ✅ IOC is a principle (concept).
    ✅ Spring Container is the mechanism/tool that implements IOC.
    
Think of it like:

    IOC = Idea/Principle
    Spring Container = Actual implementation of that idea

IOC -> Says:
"Application code should not create and manage objects. Let a container do it."
This is just a concept.

Spring Container -> Actually does the work:
Creates beans
Injects dependencies
Manages lifecycle
Destroys beans

Example:
When application starts:
Spring Container scans class.
Creates bean.
Stores bean in IOC Container.
Injects wherever needed.

In simple terms:

> 💡 Instead of our application creating dependent objects using `new`, we let Spring create and manage those objects and provide them wherever they are required.
> IOC (Inversion of Control) is a design principle where the responsibility of object creation and dependency management is transferred from application code to the Spring Container.
> Spring Container is the core component of Spring Framework that implements IOC by creating, managing, and injecting beans throughout the application lifecycle.

---

## ❌ Without IoC

Consider an `OrderService` that needs a `PaymentService`.

```java
public class OrderService {

    private PaymentService paymentService = new PaymentService();

    public void createOrder() {
        paymentService.makePayment();
    }
}
```

`OrderService` is directly responsible for creating its dependency:

```java
new PaymentService();
```

This creates stronger coupling between:

```text
OrderService
     ↓
PaymentService
```

If we later need another implementation:

```text
CreditCardPaymentService
UPIPaymentService
PaypalPaymentService
```

the dependent code may need to change.

---

### ✅ With Spring IoC

Using Spring:

```java
public interface PaymentService {

    void makePayment();
}
```

Implementation:

```java
@Service
public class UPIPaymentService implements PaymentService {

    @Override
    public void makePayment() {
        System.out.println("Payment through UPI");
    }
}
```

Order service:

```java
@Service
public class OrderService {

    private final PaymentService paymentService;

    public OrderService(PaymentService paymentService) {
        this.paymentService = paymentService;
    }
}
```

Notice something important.

There is no ```java 
new UPIPaymentService();
``` inside `OrderService`.

Instead:

```text
Spring Container
       |
       | creates
       ↓
UPIPaymentService
       |
       | injects
       ↓
OrderService
```

Spring takes responsibility for creating and connecting the objects.

---

### 🔄 Why is it called "Inversion of Control"?

Normally:

```text
Application Code
      |
      | controls object creation
      ↓
Dependent Objects
```

With Spring:

```text
Spring Container
      |
      | controls object creation
      ↓
Application Objects
```

So the control has been **inverted**.

### Before Spring

```java
PaymentService paymentService = new UPIPaymentService();
```

The developer controls object creation.

### With Spring

```java
public OrderService(PaymentService paymentService) {
    this.paymentService = paymentService;
}
```

The application says:

> "I need a `PaymentService`."

Spring decides how to provide the required bean.

That inversion of responsibility is called:

### 🔥 Inversion of Control

### 🏗️ What does the Spring IoC Container manage?

The Spring Container is responsible for:

- ✅ Creating beans
- ✅ Configuring beans
- ✅ Resolving dependencies
- ✅ Injecting dependencies
- ✅ Managing bean scopes
- ✅ Managing bean lifecycle
- ✅ Calling initialization callbacks
- ✅ Calling destruction callbacks
- ✅ Applying eligible `BeanPostProcessor`s
- ✅ Creating proxies when required by features such as AOP

Conceptually:

```text
Application Starts
       ↓
Spring Container Starts
       ↓
Reads Configuration / Bean Definitions
       ↓
Creates Beans
       ↓
Resolves Dependencies
       ↓
Injects Dependencies
       ↓
Performs Initialization
       ↓
Beans Ready
```

### How does Spring Container create and inject beans?

When the application starts, the Spring Container performs component scanning and identifies classes annotated with stereotypes like @Component, @Service, @Repository, and @Controller. It creates bean instances, stores them in the IOC container, and whenever it finds a dependency marked with @Autowired, it resolves the matching bean and injects it into the target class.

### How exactly does Spring create the bean? Using constructor? Reflection? JVM magic?
Spring uses Java Reflection API to create and manage beans.

### What is Reflection in Java?
Reflection is a Java API that allows a program to inspect and manipulate classes, methods, fields, constructors, and annotations at runtime.

Normally:

```java
EmployeeService service = new EmployeeService();
```

You know the class at compile time.

With Reflection:

```java
Class<?> clazz = Class.forName("EmployeeService");
Object obj = clazz.getDeclaredConstructor().newInstance();
```

Java creates the object dynamically at runtime.

### Why does Spring use Reflection?
Spring uses Reflection to discover annotated classes, create bean objects dynamically, inject dependencies, and manage the bean lifecycle at runtime.

Suppose Spring finds:

```java
@Service
public class EmployeeService {
}
```

Spring scans the class and says:
"I found a class marked with @Service. Let me create an object."
Internally it uses Reflection to:
> Discover the class
> Create the object
> Read annotations (@Service, @Autowired, etc.)
> Inject dependencies

Simple Example

Class:

```java
public class Employee {
 
public void display() {
System.out.println("Hello");
}
}
```

Using Reflection:

```java
Class<?> clazz = Employee.class;
 
Object obj = clazz.getDeclaredConstructor().newInstance();

Method method = clazz.getMethod("display");
 
method.invoke(obj);
```

Output:

```text
Hello
```

Notice:

```java
new Employee()
```
was never written.
Reflection created it dynamically.

### 🧩 What Exists Inside Spring Container?
The two major implementations are: 
or
Two important Spring container APIs are:

```text
BeanFactory
     ↑
     |
ApplicationContext
```

### BeanFactory

`BeanFactory` provides the basic IoC/container functionality.

It manages:

```text
Bean creation
Dependency resolution
Bean lifecycle
```

Features:
Lazy initialization
Lightweight
Rarely used nowadays

### ApplicationContext

`ApplicationContext` builds on `BeanFactory` functionality and is what we normally work with in modern Spring applications.

Features:
Most widely used
AOP support
Event handling
Internationalization
Bean lifecycle management

Spring Boot uses ApplicationContext internally.

---

# 🔥 IoC vs Dependency Injection

This is a **very common interview question**.

Do not say IoC and DI are exactly the same thing.

### IoC

IoC is the **broader design principle**.

```text
Control of object creation and dependency management
moves from application code
to the framework/container.
```

### Dependency Injection

DI is a **mechanism used to achieve IoC**.

Spring provides the dependency to an object instead of that object creating the dependency itself.

```text
           IoC
            |
            | implemented through
            ↓
     Dependency Injection
```

Example:

```java
public OrderService(PaymentService paymentService) {
    this.paymentService = paymentService;
}
```

Here Spring injecting `PaymentService` is **Dependency Injection**.

The larger concept of Spring controlling object creation and management is **IoC**.

---

### 🎤 Interview-Ready Answer

> **IoC, or Inversion of Control, is a design principle where the responsibility for creating objects, managing their lifecycle, and resolving their dependencies is transferred from application code to a container or framework.**
>
> **In Spring, the IoC container creates and manages objects called beans and injects their required dependencies. Dependency Injection is one of the main techniques Spring uses to implement IoC. This reduces coupling and makes the application easier to test, maintain, and extend.**

---

<h3 id="sb_005">What is Dependency Injection?</h3>

**Dependency Injection (DI)** is a design pattern where the dependencies required by a class are **provided from outside instead of the class creating those dependencies itself**.

In Spring, the **Spring IoC Container creates the required beans and injects them into dependent beans**.

> 💡 **Simple definition:**  
> A class should **receive its dependencies** instead of **creating them using `new`**.

Suppose we have:

```java
public class OrderService {

    private PaymentService paymentService;

}
```

Here:

```text
OrderService
     ↓
needs
     ↓
PaymentService
```

So `PaymentService` is a **dependency of `OrderService`**.


# ❌ Without Dependency Injection

```java
public class OrderService {

    private PaymentService paymentService =
            new PaymentService();

}
```

Here `OrderService` creates its own dependency:

```text
OrderService
     ↓
new PaymentService()
     ↓
PaymentService
```

This means:

```text
OrderService
      ↓
knows how PaymentService is created
      ↓
stronger coupling
```

---

### ⚠️ What's the problem?

Imagine that later we have:

```java
public interface PaymentService {

    void pay();
}
```

Implementations:

```java
public class StripePaymentService
        implements PaymentService {
}
```

```java
public class RazorpayPaymentService
        implements PaymentService {
}
```

If `OrderService` does this:

```java
private PaymentService paymentService =
        new StripePaymentService();
```

then `OrderService` is directly coupled to:

```text
StripePaymentService
```

Changing the implementation may require modifying `OrderService`.

---

# ✅ With Dependency Injection

Instead of creating the dependency:

```java
new StripePaymentService();
```

we receive it:

```java
@Service
public class OrderService {

    private final PaymentService paymentService;

    public OrderService(PaymentService paymentService) {
        this.paymentService = paymentService;
    }
}
```

Implementation:

```java
@Service
public class StripePaymentService
        implements PaymentService {

    @Override
    public void pay() {
        System.out.println("Payment completed");
    }
}
```

Spring handles the wiring:

```text
Spring Container
      ↓
Creates StripePaymentService
      ↓
Creates OrderService
      ↓
Injects PaymentService
      ↓
OrderService ready
```

---

### 🏗️ Who performs Dependency Injection in Spring?

**Spring IoC Container**

The container:

```text
Scans configuration/components
        ↓
Finds Bean definitions
        ↓
Creates Beans
        ↓
Identifies dependencies
        ↓
Resolves matching Beans
        ↓
Injects dependencies
        ↓
Bean ready
```

### 🎤 Interview-Ready Answer

> **Dependency Injection means providing an object's dependencies from outside instead of allowing the object to create them itself. In Spring, the IoC Container creates and injects the required beans, which helps achieve loose coupling and makes the application easier to test and maintain.**

---


<h3 id="sb_006">IoC vs Dependency Injection</h3>

IoC and Dependency Injection are closely related, but they are not the same.

### 🔹 IoC - Inversion of Control

**IoC is a design principle where the control of creating and managing objects is transferred from our application code to the Spring Container.**

Instead of creating objects manually:

```java
PaymentService paymentService = new PaymentService();
```

Spring creates and manages the object.

---

### 🔹 Dependency Injection

**Dependency Injection is a technique used to implement IoC, where an object's required dependencies are supplied from outside instead of being created by the object itself.**

Example:

```java
@Service
public class OrderService {

    private final PaymentService paymentService;

    public OrderService(PaymentService paymentService) {
        this.paymentService = paymentService;
    }
}
```

Here, `OrderService` does not create `PaymentService`.

Spring injects it.

---

### 🔥 Main Difference

| IoC | Dependency Injection |
|---|---|
| IoC is a design principle | DI is a technique/pattern |
| Transfers control to the container | Supplies dependencies to objects |
| Broader concept | More specific concept |
| Spring Container implements IoC | Constructor, setter, and field injection are DI approaches |

---

### 🧠 Easy Way to Remember

```text
IoC
 ↓
Who controls object creation?
 ↓
Spring Container


DI
 ↓
How does an object get its dependency?
 ↓
Dependency is injected
```

---

### 🎤 Interview Answer

> **IoC is a broader design principle where control of object creation and management is transferred from the application to the Spring Container. Dependency Injection is a technique used to achieve IoC, where the required dependencies of an object are provided from outside instead of the object creating them itself.**

### Example

```java
public OrderService(PaymentService paymentService) {
    this.paymentService = paymentService;
}
```

Here:

- Spring creating and managing `OrderService` and `PaymentService` represents **IoC**.
- Spring providing `PaymentService` to `OrderService` represents **Dependency Injection**.

> **IoC defines who controls object creation and management, while DI defines how dependencies are supplied to those objects.**

---

<h3 id="sb_007">What are the different types of Dependency Injection?</h3>

Spring commonly uses three Dependency Injection styles:

1. **Constructor Injection**
2. **Setter Injection**
3. **Field Injection**

The main difference is **how the dependency is provided to the class**.

---

### 1️⃣ Constructor Injection

Constructor Injection means the dependency is provided through the **constructor** when the object is created.

### Example

```java
@Service
public class OrderService {

    private final PaymentService paymentService;

    public OrderService(PaymentService paymentService) {
        this.paymentService = paymentService;
    }
}
```

Here, `OrderService` requires `PaymentService`.

Spring provides `PaymentService` while creating `OrderService`.

```text
PaymentService Bean
        ↓
        ↓ passed through constructor
        ↓
OrderService(PaymentService)
        ↓
OrderService ready
```

### ✅ When should we use Constructor Injection?

Use Constructor Injection when the dependency is **mandatory**.

For example:

```java
@Service
public class OrderService {

    private final OrderRepository orderRepository;
    private final PaymentService paymentService;

    public OrderService(
            OrderRepository orderRepository,
            PaymentService paymentService) {

        this.orderRepository = orderRepository;
        this.paymentService = paymentService;
    }
}
```

An `OrderService` cannot perform its job without:

- `OrderRepository`
- `PaymentService`

Therefore, both are required dependencies.

Constructor Injection is the best choice here.


### ✅ Advantages of Constructor Injection

### 1. Required dependencies are guaranteed

If `OrderService` needs `PaymentService`, you cannot normally create it without supplying one:

```java
new OrderService(paymentService);
```

This prevents creating an incomplete object.

### 2. Supports `final`

```java
private final PaymentService paymentService;
```

Once assigned through the constructor, the reference cannot be reassigned.

This makes the dependency relationship clearer.

### 3. Easy to unit test

```java
PaymentService paymentService =
        mock(PaymentService.class);

OrderService orderService =
        new OrderService(paymentService);
```

We can directly pass a mock without starting Spring.

---

### 4. Dependencies are visible

Looking at:

```java
public OrderService(
        OrderRepository orderRepository,
        PaymentService paymentService) {
}
```

we immediately know what `OrderService` depends on.

---

### ❌ Disadvantages of Constructor Injection

### 1. Constructor can become large

```java
public OrderService(
    OrderRepository repository,
    PaymentService paymentService,
    InventoryService inventoryService,
    NotificationService notificationService,
    AuditService auditService,
    CustomerService customerService) {
}
```

But this is often actually a **design warning**.

Too many constructor dependencies may indicate that the class has too many responsibilities and should be refactored.

### ⭐ Recommendation

> **Use Constructor Injection for mandatory dependencies. This should normally be your default choice in Spring application code.**

---

### 2️⃣ Setter Injection

Setter Injection means the dependency is provided using a **setter method** after the object has been created.

### Example

```java
@Service
public class NotificationService {

    private AuditService auditService;

    @Autowired
    public void setAuditService(AuditService auditService) {
        this.auditService = auditService;
    }
}
```

Conceptually:

```text
Create NotificationService
        ↓
Create/resolve AuditService
        ↓
setAuditService(auditService)
        ↓
NotificationService ready
```

### ✅ When should we use Setter Injection?

Setter Injection is useful when a dependency is genuinely **optional or reconfigurable**.

For example, imagine auditing is optional:

```java
public class NotificationService {

    private AuditService auditService;

    public void setAuditService(AuditService auditService) {
        this.auditService = auditService;
    }
}
```

The core object can exist without `AuditService`.

```text
NotificationService
       ↓
can work without
       ↓
AuditService
```

In that design, setter injection can communicate that the dependency isn't fundamental to constructing a valid object.


### ✅ Advantages of Setter Injection

### 1. Suitable for optional dependencies

The object can be created before the optional dependency is supplied.

### 2. Dependency can be changed

Because there is a setter:

```java
service.setAuditService(auditService1);

service.setAuditService(auditService2);
```

the reference can be replaced if the design intentionally requires that behavior.

### 3. Useful in specific configuration scenarios

Setter injection can be appropriate where construction and configuration are intentionally separate stages.

### ❌ Disadvantages of Setter Injection

### 1. Object can exist without its dependency

For a required dependency, this would be dangerous:

```java
OrderService orderService = new OrderService();

// paymentService may not be set
```

Therefore, setter injection is usually a poor choice for dependencies that are absolutely required.

### 2. Cannot normally keep the dependency `final`

```java
private PaymentService paymentService;
```

A setter assigns it after construction, so this cannot follow the normal constructor-set `final` pattern.

### 3. Dependency can accidentally be changed later

```java
setPaymentService(otherPaymentService);
```

If replacement isn't actually a requirement, mutability adds unnecessary risk.

### ⭐ Recommendation

> **Use Setter Injection when the dependency is intentionally optional or needs to remain changeable after object construction.**


### 3️⃣ Field Injection

Field Injection means Spring injects the dependency **directly into a field**.

### Example

```java
@Service
public class OrderService {

    @Autowired
    private PaymentService paymentService;
}
```

There is:

- No constructor parameter
- No setter method

Spring injects the field as part of managing the bean.

### ✅ When is Field Injection used?

You will commonly see it in:

- Older Spring applications
- Legacy codebases
- Small demos/tutorials
- Tests or framework-managed contexts where convenience is prioritized

For production service classes, **Constructor Injection is generally a better choice**.


### ✅ Advantages of Field Injection

### 1. Less code

```java
@Autowired
private PaymentService paymentService;
```

is concise.

### 2. Easy to read in very small examples

For demos or prototypes it may look simpler.

But less code does not necessarily mean better design.

### ❌ Disadvantages of Field Injection

### 1. Dependencies are hidden

Compare:

```java
public OrderService(
        PaymentService paymentService,
        OrderRepository orderRepository) {
}
```

with:

```java
@Autowired
private PaymentService paymentService;

@Autowired
private OrderRepository orderRepository;
```

With Constructor Injection, the required dependencies are visible directly in the constructor API.

### 2. Harder to unit test directly

Constructor Injection:

```java
OrderService service =
        new OrderService(mockPaymentService);
```

Very simple.

With private Field Injection:

```java
@Autowired
private PaymentService paymentService;
```

the dependency isn't supplied through the class's public construction API.

You may end up depending on Spring test infrastructure, Mockito annotation injection, or reflection instead of simply constructing the object.

### 3. Cannot make the dependency naturally `final`

Field injection typically looks like:

```java
@Autowired
private PaymentService paymentService;
```

instead of:

```java
private final PaymentService paymentService;
```

### 4. Can hide too many dependencies

A poorly designed class can quietly accumulate many dependencies:

```java
@Autowired
private PaymentService paymentService;

@Autowired
private OrderRepository repository;

@Autowired
private InventoryService inventoryService;

@Autowired
private NotificationService notificationService;

@Autowired
private AuditService auditService;

@Autowired
private CustomerService customerService;
```

The design problem is much easier to notice with a large constructor.

### ⭐ Recommendation

> **Avoid Field Injection for normal production service code. Prefer Constructor Injection for required dependencies.**

# 📊 Constructor vs Setter vs Field Injection

| Feature | Constructor | Setter | Field |
|---|---|---|---|
| Required dependency | ✅ Best choice | ⚠️ Possible but not ideal | ⚠️ Possible |
| Optional dependency | Possible | ✅ Good use case | Possible |
| Supports `final` naturally | ✅ Yes | ❌ No | ❌ Typically no |
| Easy unit testing | ✅ Excellent | ✅ Good | ⚠️ Less convenient |
| Dependencies clearly visible | ✅ Yes | ✅ Reasonably | ❌ Hidden in fields |
| Object complete after construction | ✅ Yes | ⚠️ Not necessarily | ⚠️ Injection occurs after construction |
| Recommended for service classes | ✅ Yes | Situation dependent | ❌ Generally avoid |

# 🎤 Interview-Ready Answer

> **Spring commonly uses Constructor, Setter, and Field Injection. Constructor Injection is preferred for mandatory dependencies because it makes dependencies explicit, allows final fields, ensures the object receives its required dependencies during construction, and makes unit testing easier. Setter Injection is appropriate when a dependency is genuinely optional or needs to be changed after object creation. Field Injection is concise, but it is generally avoided in production code because dependencies are hidden, final fields cannot be used naturally, and plain unit testing becomes less convenient.**

---

<h3 id="sb_008">Constructor Injection</h3>


**Constructor Injection** is a type of Dependency Injection where the required dependencies of a class are provided through its **constructor when the object is created**.

It is the **preferred approach for mandatory dependencies** in Spring applications.


### 🔄 How does it work in Spring?

Spring first identifies that `OrderService` requires a `PaymentService`.

```java
public OrderService(PaymentService paymentService)
```

Spring looks for a matching `PaymentService` bean.

Conceptually:

```text
Spring Container
      ↓
Find OrderService
      ↓
Inspect Constructor
      ↓
Constructor requires PaymentService
      ↓
Find PaymentService Bean
      ↓
Pass PaymentService to Constructor
      ↓
Create OrderService
```

So conceptually Spring performs something similar to:

```java
PaymentService paymentService = ...;

OrderService orderService =
        new OrderService(paymentService);
```

The important difference is that **Spring manages this process for Spring-managed beans**.


### 🧪 Practical Spring Boot Example

Consider:

```java
@Service
public class OrderService {

    private final OrderRepository orderRepository;
    private final PaymentService paymentService;
    private final InventoryService inventoryService;

    public OrderService(
            OrderRepository orderRepository,
            PaymentService paymentService,
            InventoryService inventoryService) {

        this.orderRepository = orderRepository;
        this.paymentService = paymentService;
        this.inventoryService = inventoryService;
    }

    public void createOrder(Order order) {

        inventoryService.checkStock(order);

        paymentService.processPayment();

        orderRepository.save(order);
    }
}
```

All three dependencies are required:

```text
OrderService
     |
     +---- OrderRepository
     |
     +---- PaymentService
     |
     +---- InventoryService
```

Therefore Constructor Injection is a good design.

### ⚠️ What if Spring cannot find the dependency?

Suppose:

```java
@Service
public class OrderService {

    public OrderService(PaymentService paymentService) {
    }
}
```

but there is **no `PaymentService` bean**.

Spring cannot create `OrderService` because its required constructor dependency cannot be satisfied.

The application startup will fail with a dependency resolution error, commonly involving:

```text
NoSuchBeanDefinitionException
```

or an `UnsatisfiedDependencyException` that points to the missing bean.

### ⚠️ What if multiple Beans match?

Suppose:

```java
@Service
public class StripePaymentService
        implements PaymentService {
}
```

and:

```java
@Service
public class RazorpayPaymentService
        implements PaymentService {
}
```

Then:

```java
public OrderService(PaymentService paymentService) {
    this.paymentService = paymentService;
}
```

Spring may not know which implementation should be injected.

There are two candidates:

```text
PaymentService
     |
     +---- StripePaymentService
     |
     +---- RazorpayPaymentService
```

We can resolve this using mechanisms such as:

```java
@Qualifier
```

or:

```java
@Primary
```


### ⚠️ What if the constructor has too many dependencies?

Example:

```java
public OrderService(
        PaymentService paymentService,
        InventoryService inventoryService,
        NotificationService notificationService,
        CustomerService customerService,
        AuditService auditService,
        DiscountService discountService,
        ShippingService shippingService) {
}
```

This isn't necessarily a problem with Constructor Injection.

Instead, it can reveal a **design problem**.

The class may have too many responsibilities.

```text
Large Constructor
       ↓
Many Dependencies
       ↓
Possible Too Many Responsibilities
       ↓
Review Class Design
```

This is actually an advantage of Constructor Injection because it makes excessive dependencies visible.

### 📊 Key Advantages

| Advantage | Why it matters |
|---|---|
| ✅ Mandatory dependency | Object cannot normally be created without required dependencies |
| ✅ Supports `final` | Dependency reference cannot be reassigned |
| ✅ Easy testing | Mocks can be passed directly |
| ✅ Explicit dependencies | Constructor shows exactly what the class needs |
| ✅ Valid object state | Required dependencies are available after construction |
| ✅ Design feedback | Too many constructor parameters can expose an oversized class |

### ❌ Main Disadvantage

The main practical disadvantage is that constructors can become large when a class has many dependencies.

```java
public OrderService(
    A a,
    B b,
    C c,
    D d,
    E e,
    F f) {
}
```

But instead of switching to Field Injection just to hide this, we should ask:

> **Does this class have too many responsibilities?**

It may indicate that the class should be split into smaller services.


### 🎯 Important Interview Follow-Ups

### Is `@Autowired` mandatory on constructor injection?

**No.** If the Spring bean has only one constructor, Spring can automatically use it for dependency injection.
If a Spring bean has only one constructor, @Autowired is not required because Spring automatically uses that constructor. If there are multiple constructors, @Autowired can be used to indicate which constructor Spring should use for dependency injection.

### Why use `final`?

```java
private final PaymentService paymentService;
```

It communicates that this dependency is required and the reference should not be reassigned after construction.

### What if Spring cannot find the required bean?

The bean cannot be constructed and application-context initialization typically fails with a dependency resolution error.

### What if two implementations exist?

Spring needs a way to select the appropriate candidate, such as `@Qualifier` or `@Primary`.

---

<h3 id="sb_009">Setter Injection</h3>

**Setter Injection** is a type of Dependency Injection where Spring provides a dependency to a class through a **setter method after the object has been created**.

It is mainly useful when a dependency is **optional or intentionally reconfigurable**.

### 🔹 Simple Example

```java
@Service
public class OrderService {

    private NotificationService notificationService;

    @Autowired
    public void setNotificationService(
            NotificationService notificationService) {

        this.notificationService = notificationService;
    }
}
```

Here, Spring:

```text
Creates OrderService
        ↓
Finds NotificationService Bean
        ↓
Calls setNotificationService(...)
        ↓
Injects NotificationService
```

The important difference from Constructor Injection is:

```text
Constructor Injection
Dependency provided while object is created

Setter Injection
Dependency provided after object is created
```

### ✅ When should we use Setter Injection?

Setter Injection is useful when the dependency is **not essential for creating a valid object**.

For example, suppose `NotificationService` is optional:

```java
public class OrderService {

    private NotificationService notificationService;

    public void setNotificationService(
            NotificationService notificationService) {

        this.notificationService = notificationService;
    }
}
```

The main `OrderService` functionality may work without notifications.

```text
OrderService
    |
    +---- OrderRepository      → Required
    |
    +---- NotificationService → Optional
```

A possible design would therefore be:

```java
@Service
public class OrderService {

    private final OrderRepository orderRepository;

    private NotificationService notificationService;

    public OrderService(OrderRepository orderRepository) {
        this.orderRepository = orderRepository;
    }

    @Autowired
    public void setNotificationService(
            NotificationService notificationService) {

        this.notificationService = notificationService;
    }
}
```

Here:

```text
OrderRepository
      ↓
Mandatory
      ↓
Constructor Injection


NotificationService
      ↓
Optional/reconfigurable by design
      ↓
Setter Injection
```

---

### ✅ Advantages of Setter Injection

### 1️⃣ Suitable for Optional Dependencies

The object can be constructed without that dependency.

```java
OrderService orderService =
        new OrderService(orderRepository);
```

The optional dependency can be supplied afterward.

### 2️⃣ Dependency Can Be Changed

Because a setter exists:

```java
orderService.setNotificationService(emailService);
```

it could later be replaced:

```java
orderService.setNotificationService(smsService);
```

This is useful when the design genuinely requires the dependency to be reconfigured.

### 3️⃣ Clear Separation Between Required and Optional Dependencies

You can use:

```text
Constructor
    ↓
Required Dependencies

Setter
    ↓
Optional/Reconfigurable Dependencies
```

This clearly expresses the intended relationship.

### ❌ Disadvantages of Setter Injection

### 1️⃣ Object Can Exist Without the Dependency

Suppose `PaymentService` is actually mandatory:

```java
@Service
public class OrderService {

    private PaymentService paymentService;

    @Autowired
    public void setPaymentService(
            PaymentService paymentService) {

        this.paymentService = paymentService;
    }
}
```

From a plain Java design perspective, this is possible:

```java
OrderService orderService =
        new OrderService();
```

Now the object exists before `PaymentService` is supplied.

For a mandatory dependency, Constructor Injection communicates the requirement better.

### 2️⃣ Cannot Naturally Use `final`

This works with Constructor Injection:

```java
private final PaymentService paymentService;
```

But normal Setter Injection requires reassignment:

```java
private PaymentService paymentService;
```

The field cannot follow the usual constructor-initialized `final` pattern.

---

### 3️⃣ Dependency Can Be Reassigned

Because there is a setter:

```java
setPaymentService(paymentService1);
```

someone could later call:

```java
setPaymentService(paymentService2);
```

If the dependency is not supposed to change, this creates unnecessary mutability.

### 🎤 Interview-Ready Answer

> **Setter Injection is a type of Dependency Injection where Spring injects a dependency through a setter method after creating the object. I would mainly use Setter Injection when a dependency is optional or intentionally needs to be replaceable after object creation. For mandatory dependencies, I prefer Constructor Injection because it ensures that the object is created with all of its required dependencies.**

---

<h3 id="sb_010">Field Injection</h3>

**Field Injection** is a type of Dependency Injection where Spring injects the required dependency **directly into a class field**, usually by using `@Autowired`.

Unlike Constructor Injection or Setter Injection, we don't provide the dependency through a constructor or setter method.

```text
Spring creates OrderService
        ↓
Finds @Autowired field
        ↓
Looks for PaymentService Bean
        ↓
Injects PaymentService
        ↓
OrderService ready
```

### ✅ Advantages of Field Injection

### 1️⃣ Less Boilerplate Code

Field Injection is very concise.

```java
@Autowired
private PaymentService paymentService;
```

We don't need to explicitly write:

```java
public OrderService(PaymentService paymentService) {
    this.paymentService = paymentService;
}
```

This is one reason Field Injection became common in older Spring applications and tutorials.

---

### 2️⃣ Easy to Write for Small Examples

For quick demos and prototypes:

```java
@Autowired
private UserRepository userRepository;
```

is simple and easy to write.

However, convenience alone does not make it the best design for production service classes.

### ❌ Disadvantages of Field Injection

### 1️⃣ Dependencies Are Hidden

Consider:

```java
@Service
public class OrderService {

    @Autowired
    private OrderRepository orderRepository;

    @Autowired
    private PaymentService paymentService;

    @Autowired
    private InventoryService inventoryService;
}
```

Looking only at:

```java
new OrderService();
```

we cannot tell what dependencies `OrderService` requires.

Compare this with Constructor Injection:

```java
public OrderService(
        OrderRepository orderRepository,
        PaymentService paymentService,
        InventoryService inventoryService) {
}
```

The required dependencies are immediately visible.

```text
Constructor Injection
        ↓
Dependencies are explicit ✅


Field Injection
        ↓
Dependencies are hidden inside fields ⚠️
```

### 2️⃣ Harder to Unit Test Without Spring

Suppose:

```java
public class OrderService {

    @Autowired
    private PaymentService paymentService;
}
```

In a simple unit test:

```java
OrderService orderService =
        new OrderService();
```

there is no constructor parameter through which we can directly provide:

```java
mockPaymentService
```

With Constructor Injection:

```java
PaymentService mockPaymentService =
        mock(PaymentService.class);

OrderService orderService =
        new OrderService(mockPaymentService);
```

Testing becomes straightforward without starting the Spring context.


### 3️⃣ Cannot Naturally Use `final`

With Constructor Injection:

```java
private final PaymentService paymentService;
```

This is possible because the dependency is assigned during construction.

With normal Field Injection:

```java
@Autowired
private PaymentService paymentService;
```

the dependency is injected after construction, so the standard constructor-initialized `final` design cannot be used.


### 4️⃣ Object Can Be Created in an Invalid State Outside Spring

Consider:

```java
public class OrderService {

    @Autowired
    private PaymentService paymentService;
}
```

Someone can write:

```java
OrderService orderService =
        new OrderService();
```

At this point, outside Spring-managed injection:

```text
paymentService = null
```

Calling code that uses it could result in:

```text
NullPointerException
```

With Constructor Injection:

```java
new OrderService(paymentService);
```

the required dependency must be provided at construction time.


### 5️⃣ Can Hide Too Many Dependencies

Field Injection can make it easy to keep adding dependencies:

```java
@Autowired
private OrderRepository orderRepository;

@Autowired
private PaymentService paymentService;

@Autowired
private InventoryService inventoryService;

@Autowired
private NotificationService notificationService;

@Autowired
private AuditService auditService;

@Autowired
private CustomerService customerService;

@Autowired
private ShippingService shippingService;
```

The class may have too many responsibilities, but the problem is less obvious.

With Constructor Injection:

```java
public OrderService(
        OrderRepository orderRepository,
        PaymentService paymentService,
        InventoryService inventoryService,
        NotificationService notificationService,
        AuditService auditService,
        CustomerService customerService,
        ShippingService shippingService) {
}
```

The large constructor immediately suggests:

```text
Too many dependencies
        ↓
Possible too many responsibilities
        ↓
Review the class design
```

### 🎯 When Should Field Injection Be Used?

For normal Spring Boot business/service code:

> **Prefer Constructor Injection rather than Field Injection.**

Field Injection is still commonly encountered in:

- Legacy Spring applications
- Older codebases
- Simple demonstrations/tutorials
- Some test code or framework-specific situations

But for classes such as:

```text
OrderService
PaymentService
CustomerService
InventoryService
```

Constructor Injection is generally the better design.


### ⚡ Short Interview Answer

> **Field Injection injects dependencies directly into fields using `@Autowired`. It is concise, but Constructor Injection is generally preferred because it makes dependencies explicit, supports final fields, and makes unit testing easier.**

---

<h3 id="sb_011">Constructor vs Setter vs Field Injection</h3>

The main difference between these three approaches is **when and how the dependency is supplied, and whether that dependency is mandatory or optional**.

### 📊 Comparison

| Point | Constructor Injection | Setter Injection | Field Injection |
|---|---|---|---|
| Dependency provided | During object creation | After object creation | Directly into field |
| Best suited for | Mandatory dependencies | Optional/reconfigurable dependencies | Generally avoided in application code |
| `final` field support | ✅ Yes | ❌ No | ❌ No |
| Dependency visibility | ✅ Very clear | ✅ Clear | ⚠️ Less explicit |
| Unit testing | ✅ Easiest | ✅ Easy | ⚠️ Less convenient |
| Object complete at construction | ✅ Yes | ⚠️ Not necessarily | ⚠️ Injection occurs later |
| Recommended approach | ⭐ Preferred | Use when appropriate | Generally avoid |

### 🎯 How Do I Choose?

Use this decision:

```text
Is the dependency mandatory?
        ↓
       YES
        ↓
Constructor Injection


Is the dependency genuinely optional
or intentionally reconfigurable?
        ↓
       YES
        ↓
Setter Injection


Field Injection?
        ↓
Generally avoid for service/business classes
```

> **The injection style should represent the dependency relationship. Mandatory dependencies belong naturally in the constructor. Setter Injection can be appropriate for genuinely optional or reconfigurable dependencies. Field Injection is convenient but generally avoided in application service classes because it hides dependencies and makes plain unit testing less convenient.**

---

<h3 id="sb_012">Why is Constructor Injection recommended?</h3>



<h3 id="sb_013">What is a Spring Bean?</h3>

A Spring Bean is an object managed by the Spring IoC Container. The container handles its creation, dependency injection, configuration, scope, and lifecycle.

Example:

```java
@Service
public class PaymentService {
}
```

Here, PaymentService is registered and managed by Spring, so its instance is a Spring Bean.

### 🔹 How Do We Create Spring Beans?

There are several ways to register objects as Spring Beans.

### 1️⃣ Using Component Annotations

Example:

```java
@Component
public class EmailService {
}
```

Other specialized component annotations include:

```java
@Service
@Repository
@Controller
@RestController
```

For example:

```java
@Service
public class OrderService {
}
```

Spring discovers these classes during component scanning and registers them as beans.

### 2️⃣ Using `@Bean`

Sometimes we want to explicitly create a bean through configuration.

```java
@Configuration
public class AppConfig {

    @Bean
    public PaymentService paymentService() {
        return new PaymentService();
    }
}
```

Here:

```java
@Bean
```

tells Spring:

> Register the object returned by this method as a Spring Bean.

This is especially useful when configuring objects whose class we don't directly control, such as objects from external libraries.

---

<h3 id="sb_014">Java Object vs Spring Bean</h3>

A Java object is any object created normally using Java, usually with the new keyword. A Spring Bean is a Java object whose creation, configuration, dependencies, and lifecycle are managed by the Spring IoC Container.

### Normal Java Object

```java
PaymentService paymentService =
        new PaymentService();
```

Here, **we created the object manually**.

Spring is not managing this particular instance.

```text
new PaymentService()
        ↓
Normal Java Object
```

### Spring Bean

```java
@Service
public class PaymentService {
}
```

Spring creates and manages the instance.

```text
Spring Container
      ↓
Creates PaymentService
      ↓
Manages PaymentService
      ↓
Spring Bean
```

Every Spring Bean is a Java object, but every Java object is not a Spring Bean. An object becomes a Spring Bean when it is registered with and managed by the Spring IoC Container.

---

<h3 id="sb_015">What is Spring Container?</h3>

The **Spring IoC Container is the core part of Spring responsible for creating, configuring, managing, and connecting Spring Beans throughout their lifecycle.**

The container reads the application's configuration, identifies the required beans, creates them, resolves their dependencies, and manages them.

### 🔹 Main Responsibilities

The Spring IoC Container handles:

```text
Read Bean Configuration
        ↓
Create Beans
        ↓
Resolve Dependencies
        ↓
Inject Dependencies
        ↓
Initialize Beans
        ↓
Manage Bean Scope & Lifecycle
        ↓
Destroy Beans when required
```

### 🔹 Main Types of Spring IoC Container

Spring provides two important container interfaces:

```text
BeanFactory
     ↓
Basic IoC Container

ApplicationContext
     ↓
More feature-rich IoC Container
```

`ApplicationContext` is commonly used in modern Spring applications.

### 🎤 Interview-Ready Answer

> **The Spring IoC Container is responsible for managing Spring Beans. It creates and configures beans, resolves and injects their dependencies, and manages their scope and lifecycle. Spring provides BeanFactory and ApplicationContext as the main container interfaces, with ApplicationContext being commonly used in modern Spring applications.**

### 🧠 Easy to Remember

```text
Spring IoC Container
        =
Create + Configure + Inject + Manage Beans
```

---

<h3 id="sb_016">What is ApplicationContext?</h3>

`ApplicationContext` is the **main Spring IoC container interface used to manage beans in a Spring application**.

It provides all the basic container capabilities and also supports additional enterprise features such as **events, internationalization, resource loading, and environment/property access**.

### 🔹 What Does ApplicationContext Do?

`ApplicationContext` provides access to:

- Bean creation and management
- Dependency injection
- Bean lifecycle
- Bean scopes
- Application events
- Environment and properties
- Resource loading
- Internationalization (i18n)

### 🔹 Example

```java
ApplicationContext context =
        new AnnotationConfigApplicationContext(AppConfig.class);

PaymentService paymentService =
        context.getBean(PaymentService.class);
```

Here:

```text
ApplicationContext
       ↓
Loads configuration
       ↓
Creates and manages Beans
       ↓
PaymentService Bean
       ↓
getBean()
```

Normally in a Spring Boot application, we don't manually create the `ApplicationContext`.

Spring Boot creates and initializes an appropriate application context during application startup.

---

### 🔹 Common ApplicationContext Implementations

Examples include:

```text
AnnotationConfigApplicationContext
        ↓
Annotation / Java configuration

ClassPathXmlApplicationContext
        ↓
XML configuration
```

Web-based Spring applications use web-aware `ApplicationContext` implementations.


### 🎤 Interview-Ready Answer

> **ApplicationContext is Spring's main IoC container interface. It is responsible for accessing and managing Spring beans and provides additional capabilities such as application events, resource loading, environment and property access, and internationalization. In Spring Boot, the ApplicationContext is created automatically during application startup.**

---

<h3 id="sb_017">What is BeanFactory?</h3>

`BeanFactory` is the **basic IoC container interface in Spring**.

It provides the fundamental functionality required to **create, configure, retrieve, and manage Spring Beans and their dependencies**.


### 🔹 What does BeanFactory do?

Its main responsibilities include:

- Creating and managing beans
- Resolving dependencies between beans
- Providing beans when requested
- Managing bean scopes
- Supporting bean lifecycle operations

### 🔹 Simple Example

```java
BeanFactory beanFactory = context;

PaymentService paymentService =
        beanFactory.getBean(PaymentService.class);
```

Here:

```java
getBean(PaymentService.class)
```

asks the `BeanFactory` for the `PaymentService` bean.

### 🔹 Where is BeanFactory used?

In normal Spring Boot application development, we usually work with:

```text
ApplicationContext
```

rather than directly using:

```text
BeanFactory
```

because `ApplicationContext` extends the basic container capabilities and provides additional application-level features.

### 🔥 Important Interview Point

`BeanFactory` is the **foundation of Spring's bean-management infrastructure**.

Conceptually:

```text
BeanFactory
     ↓
Basic Bean Container Capabilities
     ↓
ApplicationContext
     ↓
Bean Capabilities + Additional Application Features
```

## 🎤 Interview-Ready Answer

> **BeanFactory is the basic IoC container interface in Spring. It provides the fundamental functionality for creating, retrieving, configuring, and managing beans and their dependencies. In modern Spring applications, we generally use ApplicationContext, which builds on BeanFactory capabilities and provides additional features.**

---

<h3 id="sb_018">ApplicationContext vs BeanFactory</h3>

Both `BeanFactory` and `ApplicationContext` are Spring IoC container interfaces, but `ApplicationContext` provides more application-level features and is normally used in modern Spring applications.

### ⚠️ Important Interview Point: Lazy vs Eager

```text
BeanFactory = Lazy
ApplicationContext = Eager
```

> `ApplicationContext` normally pre-instantiates non-lazy singleton beans during context initialization. However, beans can still explicitly be configured for lazy initialization.

The major difference is the **additional application-level capabilities provided by `ApplicationContext`**.

---

<h3 id="sb_019">What is Bean Scope?</h3>

**Bean Scope defines how many instances of a Spring Bean are created and how long those instances are managed by the Spring Container.**

In simple terms, Bean Scope answers:

```text
How many Bean objects should Spring create?
                +
How long should each Bean instance live?
```
### 🔹 Common Spring Bean Scopes

| Scope | Instance |
|---|---|
| `singleton` | One bean instance per Spring container for that bean definition |
| `prototype` | A new bean instance each time it is requested from the container |
| `request` | One bean instance per HTTP request |
| `session` | One bean instance per HTTP session |
| `application` | One bean instance per web application's `ServletContext` |
| `websocket` | One bean instance per WebSocket session |

### 🔹 How to Define a Scope

```java
@Component
@Scope("prototype")
public class ReportService {
}
```

Or using constants:

```java
@Component
@Scope(ConfigurableBeanFactory.SCOPE_PROTOTYPE)
public class ReportService {
}
```

---

<h3 id="sb_020">Singleton Scope</h3>

**Singleton is the default bean scope in Spring.**

In Singleton Scope, Spring creates **one instance of a bean for each bean definition within a Spring IoC Container** and returns that same instance whenever the bean is requested.


### 🔹 Example

```java
@Service
public class OrderService {
}
```

Since no scope is specified, `OrderService` uses the default **singleton scope**.

If the bean is requested multiple times:

```java
OrderService service1 = context.getBean(OrderService.class);
OrderService service2 = context.getBean(OrderService.class);
```

then:

```java
service1 == service2
```

will normally be:

```text
true
```

because both references point to the same Spring-managed bean instance.

### 🔹 How It Works

```text
Spring Container Starts
        ↓
Creates OrderService Bean
        ↓
Stores the Bean
        ↓
Request 1 → Same OrderService
Request 2 → Same OrderService
Request 3 → Same OrderService
```
### ⚠️ Important: Thread Safety

A Spring `singleton` bean is normally **shared by multiple requests**.

Because of this, avoid storing **request-specific data in mutable instance variables**.

### ❌ Avoid Shared Mutable State

```java
@Service
public class OrderService {

    private String customerName;

    public void createOrder(String name) {
        customerName = name;
    }
}
```

If two users call this method:

```text
User A → customerName = "Indhu"

User B → customerName = "Rahul"
```

Both requests use the same `OrderService` object, so one request can overwrite the value used by another request.

### ✅ Prefer Local Variables

```java
@Service
public class OrderService {

    public void createOrder(String name) {

        String customerName = name;

        // process order
    }
}
```

Now each method call has its own local variable:

```text
User A → "Indhu" → separate method call

User B → "Rahul" → separate method call
```

They don't overwrite each other's local variable.

### 🧠 Simple Rule

```text
Singleton Bean
      ↓
Shared by multiple requests
      ↓
Avoid request-specific mutable instance fields
      ↓
Use method-local variables where appropriate
      ↓
Keep service classes generally stateless
```

> **Interview Point:** A Spring singleton bean is not automatically thread-safe. We should design singleton services to avoid shared mutable state, especially request-specific data.

---

<h3 id="sb_021">Prototype Scope</h3>

In **Prototype Scope**, Spring creates a **new bean instance every time that bean is requested from the Spring Container**.

### 🔹 Example

```java
@Component
@Scope("prototype")
public class ReportService {
}
```

Now:

```java
ReportService service1 =
        context.getBean(ReportService.class);

ReportService service2 =
        context.getBean(ReportService.class);
```

Here:

```java
service1 == service2
```

returns:

```text
false
```

because Spring creates two different objects.

### 🔹 How It Works

```text
Request Bean
    ↓
Create Object 1


Request Bean Again
    ↓
Create Object 2


Request Bean Again
    ↓
Create Object 3
```

So:

```text
Prototype Scope
      ↓
New Bean Instance
      ↓
Every time requested from container
```

### 🔹 When Do We Use Prototype Scope?

Prototype scope is useful when each usage requires a **separate object with its own mutable state**.

For example:

```java
@Component
@Scope("prototype")
public class ReportBuilder {

    private String reportName;

    private List<String> data = new ArrayList<>();
}
```

If different operations need independent `ReportBuilder` instances, prototype scope can provide a fresh instance for each container lookup.

### ⚠️ Important: Prototype Bean Lifecycle

For prototype beans, Spring:

```text
Creates Bean
    ↓
Injects Dependencies
    ↓
Initializes Bean
    ↓
Returns Bean
```

After that, Spring does **not manage the complete destruction lifecycle** in the same way it does for singleton beans.

For example, destruction callbacks such as:

```java
@PreDestroy
```

are not automatically called by the container when a prototype instance is no longer needed.

The application using the prototype bean is responsible for any necessary cleanup.

### ⚠️ Important Interview Point

Prototype does **not** mean:

> One new object automatically for every HTTP request.

That is:

```text
request scope
```

Prototype means:

> **A new instance whenever the bean is requested from the container.**

## 🎤 Interview-Ready Answer

> **Prototype is a Spring bean scope where the container creates a new bean instance every time the bean is requested from the container. It is useful when separate instances with independent state are required. Spring creates, injects, and initializes prototype beans, but unlike singleton beans, it does not manage their full destruction lifecycle.**

---

<h3 id="sb_022">Request Scope</h3>

**Request Scope means Spring creates one new bean object for each HTTP request.**

The bean exists only while that particular HTTP request is being processed.

### 🔹 Simple Example

```java
@Component
@RequestScope
public class RequestDetails {

}
```

Suppose three API requests reach the application:

```text
Request 1
   ↓
RequestDetails Object 1


Request 2
   ↓
RequestDetails Object 2


Request 3
   ↓
RequestDetails Object 3
```

Each HTTP request gets its **own separate object**.

### 🔹 Real Example

Suppose we want to store information related only to the current HTTP request:

```java
@Component
@RequestScope
public class RequestContext {

    private String requestId;

    public String getRequestId() {
        return requestId;
    }

    public void setRequestId(String requestId) {
        this.requestId = requestId;
    }
}
```

If two users call the API:

```text
User A Request
      ↓
RequestContext Object 1
requestId = "REQ-101"


User B Request
      ↓
RequestContext Object 2
requestId = "REQ-102"
```

The request-specific state is not shared between those two HTTP requests through this bean.

### 🔹 Lifecycle

```text
HTTP Request Starts
        ↓
Request-scoped Bean Created
        ↓
Bean Used During Request
        ↓
HTTP Request Completes
        ↓
Bean Lifecycle Ends
```

### 🔹 When to Use Request Scope

Use it when an object needs to hold data that belongs only to the **current HTTP request**, such as:

- Request-specific context
- Correlation/request ID
- Request processing metadata

### 🎤 Interview-Ready Answer

> **Request Scope creates one bean instance for each HTTP request. The bean is available during that request and its lifecycle ends when the request completes. I would use it when I need to maintain data that belongs specifically to the current HTTP request.**

---

<h3 id="sb_023">Session Scope</h3>

**Session Scope means Spring creates one bean object for each HTTP user session.**

The same bean object is reused for all requests that belong to the **same session**.

### 🔹 Simple Example

```java
@Component
@SessionScope
public class UserSession {

    private String username;

}
```

Suppose two users log in:

```text
User A
   ↓
HTTP Session A
   ↓
UserSession Object 1


User B
   ↓
HTTP Session B
   ↓
UserSession Object 2
```

If User A sends multiple requests:

```text
Request 1 ─┐
Request 2 ─┼──→ Session A ──→ Same UserSession Object
Request 3 ─┘
```

Spring keeps using the same session-scoped bean until that session ends.

### 🔹 Lifecycle

```text
HTTP Session Starts
        ↓
Session Bean Created
        ↓
Same Bean Used Across Requests
        ↓
Session Ends / Expires
        ↓
Bean Lifecycle Ends
```

### 🔹 When to Use Session Scope

Use Session Scope when data needs to remain available across **multiple requests from the same user session**.

Examples:

- Shopping cart state
- Multi-step form data
- User-specific temporary session information

### 🔥 Request Scope vs Session Scope

```text
Request Scope

Request 1 → Object 1
Request 2 → Object 2
Request 3 → Object 3
```

```text
Session Scope

Session A
   ├── Request 1
   ├── Request 2
   └── Request 3
          ↓
     Same Object
```

### 🎤 Interview-Ready Answer

> **Session Scope creates one bean instance for each HTTP session. The same bean is shared across multiple requests within that session, and its lifecycle ends when the session expires or is invalidated. It is useful for temporary user-specific state that needs to survive across multiple requests.**

### 🧠 Easy to Remember

```text
Request Scope
    ↓
One Object per HTTP Request


Session Scope
    ↓
One Object per HTTP Session
```

---

<h3 id="sb_024">Application Scope</h3>

**Application Scope means Spring creates one bean instance for one web application's `ServletContext`.**

The bean is shared across **all HTTP requests and all user sessions** belonging to that web application.

### 🔹 Example

```java
@Component
@ApplicationScope
public class ApplicationInfo {

    private boolean maintenanceMode;

}
```

Conceptually:

```text
             Web Application
                    ↓
              ServletContext
                    ↓
          ApplicationInfo Bean
              (One Object)
                    ↓
        ┌───────────┴───────────┐
        ↓                       ↓
     User A                  User B
        ↓                       ↓
  Multiple Requests       Multiple Requests
```

All requests and sessions in that web application access the same application-scoped bean.

### 🔹 Real-Time Example

Suppose we want to maintain application-wide runtime information:

```java
@Component
@ApplicationScope
public class ApplicationInfo {

    private boolean maintenanceMode;

    public boolean isMaintenanceMode() {
        return maintenanceMode;
    }

    public void setMaintenanceMode(boolean maintenanceMode) {
        this.maintenanceMode = maintenanceMode;
    }
}
```

If:

```java
maintenanceMode = true;
```

the same application-scoped bean is visible to requests across the web application.

> ⚠️ Because this is shared mutable state, concurrent access must be considered. Also, in a multi-instance deployment, this state is local to that application instance. Use a shared store such as Redis or a database when the value must be consistent across multiple instances.

### 🔹 Lifecycle

```text
Web Application Starts
        ↓
ServletContext Created
        ↓
Application-Scoped Bean Available
        ↓
Shared Across Requests & Sessions
        ↓
ServletContext Destroyed
        ↓
Bean Lifecycle Ends
```

### 🔥 Application Scope vs Singleton Scope

They can look similar in a normal Spring Boot web application, but they are **not the same scope**.

Singleton means:

> **One bean instance per bean definition per Spring IoC Container.**

Application scope means:

> **One bean instance per ServletContext in a web application.**

| Singleton Scope | Application Scope |
|---|---|
| One bean instance per bean definition per Spring container | One bean instance per `ServletContext` |
| General Spring scope | Web-specific scope |
| Default Spring scope | Must be explicitly selected |
| Tied to Spring container | Tied to web application's `ServletContext` |

### Easy Difference

```text
Singleton
    ↓
Spring Container boundary


Application Scope
    ↓
ServletContext / Web Application boundary
```

> In a typical Spring Boot web application with one `ApplicationContext` and one `ServletContext`, they may **behave very similarly**, because both often result in one object. But their **scope boundaries are different**, so they should not be considered the same scope.

### NOTE: Bean Definition vs ServletContext

A Bean Definition is metadata/instructions that tell Spring how a bean should be created and managed.

### Example 

Spring scans OrderService and internally registers information roughly like:

```text
Bean name → orderService
Bean class → OrderService
Scope → singleton
Lazy → false
Dependencies → ...
```

Spring creates:

```text
OrderService Object #1
```

and keeps returning that same object for that bean definition.

So:

> Singleton = one bean instance per bean definition per Spring container.

### ServletContext

ServletContext belongs to the web application / Servlet environment. It represents the running web application to the Servlet container.

For example, your Spring Boot application runs using embedded Tomcat:

```text
Tomcat
↓
Your Web Application
↓
ServletContext
```

Conceptually:

```text
ServletContext
|
+── DispatcherServlet
|
+── Filters
|
+── Servlets
|
+── Application-wide attributes/resources
```

There is generally one ServletContext for each deployed web application.

> Tomcat or Jetty is the server/Servlet container.
> ServletContext is an object created by that Servlet container to represent one deployed web application.

### 🔹 ApplicationContext vs ServletContext

Do not confuse these two:

```text
Tomcat / Jetty
      ↓
ServletContext
      ↓
Represents the Web Application


Spring
      ↓
ApplicationContext
      ↓
Represents the Spring IoC Container
      ↓
Manages Spring Beans
```

### Simple Comparison

| `ApplicationContext` | `ServletContext` |
|---|---|
| Spring concept | Servlet API concept |
| Spring IoC container | Represents a web application |
| Manages Spring Beans | Provides web-application context/resources |
| Created/managed by Spring | Created/managed by Servlet container |
| Can exist without a web application | Exists in Servlet-based web applications |

## 🎤 Interview-Ready Answer

> **Application Scope is a web-specific Spring bean scope where one bean instance is maintained for the web application's ServletContext. The same bean is shared across all requests and sessions within that web application, and its lifecycle is tied to the ServletContext. It differs from singleton scope because singleton is defined relative to the Spring container and bean definition, whereas application scope is defined relative to the ServletContext.**

---

<h3 id="sb_025">WebSocket Scope</h3>

**WebSocket Scope means Spring creates one bean instance for each WebSocket session.**

The same bean is available throughout that WebSocket connection and is destroyed when the WebSocket session ends.

### 🔹 Simple Example

```java
@Component
@Scope("websocket")
public class ChatSession {

    private String username;

}
```

If two users establish separate WebSocket connections:

```text
User A
   ↓
WebSocket Session A
   ↓
ChatSession Object 1


User B
   ↓
WebSocket Session B
   ↓
ChatSession Object 2
```

Each WebSocket session gets its own bean object.

### 🔹 Real-Time Example

A common example is a **real-time chat application**.

Suppose a user connects to a chat server:

```text
User connects
      ↓
WebSocket connection established
      ↓
WebSocket Session created
      ↓
ChatSession Bean created
      ↓
User sends/receives multiple messages
      ↓
Same ChatSession Bean used
      ↓
User disconnects
      ↓
WebSocket Session ends
      ↓
Bean lifecycle ends
```

The bean can hold information related to that WebSocket session, such as temporary connection-specific state.

### 🔹 When to Use WebSocket Scope

WebSocket scope is useful for applications involving persistent WebSocket connections, such as:

- 💬 Real-time chat
- 🔔 Live notifications
- 📈 Live dashboards
- 🎮 Multiplayer/interactive applications
- 📡 Real-time status updates

### 🔥 WebSocket Scope vs Request Scope

With a normal HTTP request:

```text
Client
  ↓
HTTP Request
  ↓
Response
  ↓
Request ends
```

With WebSocket:

```text
Client
  ↓
WebSocket Connection
  ↓
Connection remains open
  ↓
Message
  ↓
Message
  ↓
Message
  ↓
Connection closed
```

Therefore:

```text
Request Scope
      ↓
One bean per HTTP request


WebSocket Scope
      ↓
One bean per WebSocket session
```

### 🎤 Interview-Ready Answer

> **WebSocket Scope creates one Spring bean instance for each WebSocket session. The same bean remains available while that WebSocket connection/session is active and its lifecycle ends when the session ends. It is useful for maintaining connection-specific state in real-time applications such as chat, notifications, and live dashboards.**

---

## WebSocket

**WebSocket is a communication protocol that creates a persistent, two-way connection between a client and a server.**

It is mainly used when the server needs to send information to the client **immediately**, without waiting for the client to make another HTTP request.

### 🔹 First Understand Normal HTTP

In a normal REST API:

```text
Client
   ↓
HTTP Request
   ↓
Server
   ↓
HTTP Response
   ↓
Request/Response completes
```

Example:

```http
GET /orders/101
```

The client sends a request:

```text
Client
  ↓
"Give me Order 101"
```

Server responds:

```json
{
  "id": 101,
  "status": "SHIPPED"
}
```

After the response, that HTTP request is finished.

### 🔹 Problem: Real-Time Communication

Imagine you're building a **chat application**.

User A sends:

```text
Hello
```

User B should receive:

```text
Hello
```

immediately.

With only traditional request/response communication, User B may need to repeatedly ask:

```text
Any new message?

Any new message?

Any new message?

Any new message?
```

This is called **polling**.

Conceptually:

```text
Client → Any message? → Server
Client ← No          ← Server

Client → Any message? → Server
Client ← No          ← Server

Client → Any message? → Server
Client ← Yes         ← Server
```

This creates unnecessary repeated requests.

### 🔥 WebSocket Solves This Differently

With WebSocket, the connection remains open:

```text
Client
   ↕
   ↕
   ↕
Server
```

Both sides can send messages whenever needed.

```text
Client ───────→ Server
       Message

Client ←─────── Server
       Message
```

This is called:

**Full-Duplex Communication**

Meaning:

```text
Client can send → Server

AND

Server can send → Client
```

over the established WebSocket connection.

### 🔹 Chat Application Example

Suppose:

```text
Indhu
  ↓
Chat Application
  ↓
WebSocket Connection
  ↓
Chat Server
```

The connection stays active.

You send:

```text
Hello Rahul
```

Flow:

```text
Indhu
   ↓
WebSocket
   ↓
Server
   ↓
WebSocket
   ↓
Rahul
```

Rahul does not need to continuously call:

```http
GET /messages
```

The server can push the message through the existing WebSocket connection.

### 🔹 HTTP vs WebSocket

| HTTP / REST | WebSocket |
|---|---|
| Request-response communication | Persistent two-way communication |
| Client normally initiates requests | Client and server can send messages |
| Suitable for CRUD APIs | Suitable for real-time communication |
| Response completes that request | Connection remains open |
| Example: Create an order | Example: Live chat |

### 🔹 Where Do We Use WebSocket?

Typical real-time applications include:

### 💬 Chat Applications

```text
User sends message
       ↓
Server
       ↓
Immediately push message
       ↓
Other User
```


### 🔔 Live Notifications

For example:

```text
Order shipped
      ↓
Backend
      ↓
WebSocket message
      ↓
Browser
      ↓
"Your order has been shipped"
```

No page refresh is required.


### 📈 Live Dashboard

Imagine monitoring:

```text
CPU: 40%
CPU: 48%
CPU: 61%
CPU: 72%
```

The server can continuously push updated data to the dashboard.

### 🚕 Live Tracking

For example:

```text
Driver location changes
       ↓
Backend receives location
       ↓
Push update
       ↓
Customer map updates
```

### 🎮 Multiplayer Applications

```text
Player moves
      ↓
Server
      ↓
Other players receive update
```

### 🔹 What is a WebSocket Session?

When a client establishes a WebSocket connection, a **WebSocket session** represents that active communication session.

Example:

```text
Indhu Browser
      ↓
WebSocket Connection
      ↓
WebSocket Session A
```

Another user:

```text
Rahul Browser
      ↓
WebSocket Connection
      ↓
WebSocket Session B
```

They have separate sessions.

### 🔹 Now WebSocket Scope Makes Sense

Suppose we define:

```java
@Component
@Scope("websocket")
public class ChatSession {

    private String username;
}
```

For each WebSocket session, Spring can maintain a separate bean instance.

```text
Indhu
   ↓
WebSocket Session A
   ↓
ChatSession Object A


Rahul
   ↓
WebSocket Session B
   ↓
ChatSession Object B
```

The same bean instance remains associated with that WebSocket session during its lifetime.

### 🔹 WebSocket Bean Lifecycle

```text
Client connects
      ↓
WebSocket Session Starts
      ↓
WebSocket-scoped Bean available
      ↓
Message 1
      ↓
Message 2
      ↓
Message 3
      ↓
Connection closes
      ↓
WebSocket Session Ends
      ↓
Bean lifecycle ends
```

### 🧠 Compare All the Web Scopes

```text
HTTP Request
     ↓
@RequestScope
     ↓
One object per HTTP request
```

```text
HTTP Session
     ↓
@SessionScope
     ↓
One object per HTTP session
```

```text
Web Application
     ↓
@ApplicationScope
     ↓
One object per ServletContext
```

```text
WebSocket Session
     ↓
WebSocket Scope
     ↓
One object per WebSocket session
```

### 🎤 What Should You Say in an Interview?

> **WebSocket is a protocol used for persistent, bidirectional communication between a client and server. Unlike the normal HTTP request-response model, after a WebSocket connection is established, both the client and server can send messages over the same connection. It is useful for real-time applications such as chat, live notifications, dashboards, and tracking. In Spring, WebSocket scope associates a bean instance with a WebSocket session, so that instance remains available for the lifetime of that WebSocket session.**

### 🧠 Very Simple Memory

```text
REST API

Request
   ↓
Response
   ↓
Done
```

```text
WebSocket

Connect
   ↓
Keep Connection Open
   ↕
Client ↔ Server
   ↕
Many Messages
   ↓
Disconnect
```

> **In one line:** WebSocket is useful when the client and server need to communicate continuously in real time without creating a new HTTP request for every update.

---

<h3 id="sb_026">Spring Singleton vs Java Singleton</h3>

Spring Singleton and the Java Singleton Design Pattern both often result in a single object being reused, but **their scope and object management are different**.

### 🔹 Spring Singleton

In Spring, `singleton` is a **bean scope**.

Spring maintains **one bean instance per bean definition within a Spring IoC Container**.

```java
@Service
public class OrderService {
}
```

Since `singleton` is the default scope, Spring manages one `OrderService` bean instance for that bean definition in that container.

```text
Spring Container
      ↓
orderService Bean Definition
      ↓
One OrderService Object
      ↓
Shared wherever that Bean is injected
```

We don't need to implement any special Singleton-pattern code.

### 🔹 Java Singleton

Java Singleton is a **design pattern implemented by the developer** to restrict normal construction and expose a single shared instance.

A simple example:

```java
public class DatabaseManager {

    private static final DatabaseManager INSTANCE =
            new DatabaseManager();

    private DatabaseManager() {
    }

    public static DatabaseManager getInstance() {
        return INSTANCE;
    }
}
```

Usage:

```java
DatabaseManager manager1 =
        DatabaseManager.getInstance();

DatabaseManager manager2 =
        DatabaseManager.getInstance();
```

Both references point to the same singleton instance:

```text
DatabaseManager
      ↓
static instance
      ↓
getInstance()
      ↓
Same Object
```

### 🔥 Main Difference

| Spring Singleton | Java Singleton |
|---|---|
| Spring bean scope | Design pattern |
| Managed by Spring Container | Managed through application/class design |
| One instance per bean definition per Spring container | Typically one instance per class loader, depending on implementation |
| Spring controls creation and lifecycle | Developer implements object-creation restriction |
| No private constructor required | Usually uses a private constructor |
| No `getInstance()` required | Commonly exposes `getInstance()` or similar mechanism |
| Works naturally with Dependency Injection | Usually accessed explicitly through its singleton mechanism |

### ⚠️ Important Difference

Suppose an application has two independent Spring containers:

```text
ApplicationContext A
       ↓
OrderService Object A


ApplicationContext B
       ↓
OrderService Object B
```

Both containers can have their **own singleton `OrderService` bean**.

Therefore, Spring Singleton does **not** mean:

```text
Exactly one object in the entire JVM
```

It means:

```text
One bean instance
        ↓
per Bean Definition
        ↓
per Spring Container
```

### 🎤 Interview-Ready Answer

> **Spring Singleton is a bean scope where Spring maintains one bean instance per bean definition within a Spring IoC container. Java Singleton, on the other hand, is a design pattern implemented by the developer, usually using a private constructor and a static instance to restrict object creation. So Spring Singleton is container-managed, while Java Singleton is class/design-pattern managed.**

---

<h3 id="sb_027">Can a Singleton Bean inject a Prototype Bean?</h3>

**Yes. A Singleton Bean can inject a Prototype Bean.**

However, there is an important behavior to understand:

> If a Prototype Bean is directly injected into a Singleton Bean, the prototype instance is usually resolved when the Singleton Bean is created. Therefore, that Singleton Bean keeps using the **same injected prototype object**, rather than automatically receiving a new prototype object on every method call.


## 🔹 Example

```java
@Component
@Scope("prototype")
public class ReportService {
}
```

```java
@Service
public class OrderService {

    private final ReportService reportService;

    public OrderService(ReportService reportService) {
        this.reportService = reportService;
    }

    public void generateReport() {
        System.out.println(reportService);
    }
}
```

Here:

```text
OrderService
     ↓
Singleton

ReportService
     ↓
Prototype
```

When Spring creates the singleton `OrderService`:

```text
Create OrderService
       ↓
OrderService needs ReportService
       ↓
Spring creates ReportService Object #1
       ↓
Injects it into OrderService
       ↓
OrderService keeps that reference
```

Later:

```text
generateReport() → ReportService Object #1

generateReport() → ReportService Object #1

generateReport() → ReportService Object #1
```

So simply injecting a prototype into a singleton does **not** mean a new prototype object appears on every method invocation.


### 🔥 What if I need a new Prototype Bean every time?

If you need:

```text
generateReport()
      ↓
New ReportService


generateReport()
      ↓
Another new ReportService
```

you need to request the prototype dynamically.

Spring provides approaches such as:

- `ObjectProvider`
- `@Lookup`

For example:

```java
@Service
public class OrderService {

    private final ObjectProvider<ReportService> reportServiceProvider;

    public OrderService(
            ObjectProvider<ReportService> reportServiceProvider) {

        this.reportServiceProvider = reportServiceProvider;
    }

    public void generateReport() {

        ReportService reportService =
                reportServiceProvider.getObject();

        System.out.println(reportService);
    }
}
```

Now:

```text
generateReport()
      ↓
getObject()
      ↓
ReportService Object #1


generateReport()
      ↓
getObject()
      ↓
ReportService Object #2
```

Because `ReportService` is prototype-scoped, each lookup asks Spring for a new instance.

## 🎤 Interview-Ready Answer

> **Yes, a singleton bean can depend on a prototype bean. However, if the prototype bean is injected directly through normal constructor injection, the prototype is resolved when the singleton is created, so that singleton keeps the same prototype instance. If I need a new prototype instance during each operation, I would perform a dynamic lookup using something like `ObjectProvider` or `@Lookup`.**

### 🧠 Easy to Remember

```text
Prototype directly injected into Singleton
              ↓
Prototype created during Singleton creation
              ↓
Singleton keeps same reference


Need new Prototype every time?
              ↓
Dynamic lookup
              ↓
ObjectProvider / @Lookup
```

---

<h3 id="sb_028">What problem occurs when Prototype Bean is injected into Singleton?</h3>

The main problem is a scope mismatch.

When a prototype bean is directly injected into a singleton bean, Spring creates the prototype object while creating the singleton.

The singleton then keeps that same prototype object.

So we may expect a new prototype object every time, even if we expected a fresh prototype object for every operation. but we continue using the same one.

### 🔹 Example

Prototype bean:

```java
@Component
@Scope("prototype")
public class ReportService {

    private List<String> data = new ArrayList<>();

    public void addData(String value) {
        data.add(value);
    }

    public List<String> getData() {
        return data;
    }
}
```

Singleton bean:

```java
@Service
public class OrderService {

    private final ReportService reportService;

    public OrderService(ReportService reportService) {
        this.reportService = reportService;
    }

    public void generateReport(String order) {
        reportService.addData(order);
    }
}
```

When Spring creates `OrderService`:

```text
Create Singleton OrderService
           ↓
Constructor needs ReportService
           ↓
Spring creates Prototype Object 1
           ↓
Injects Object 1 into OrderService
           ↓
OrderService keeps Object 1
```

### ⚠️ Where Does the Problem Come?

Suppose User A calls:

```java
generateReport("Order-A");
```

The prototype object contains:

```text
["Order-A"]
```

Then User B calls:

```java
generateReport("Order-B");
```

Since the Singleton still holds the same `ReportService` object:

```text
["Order-A", "Order-B"]
```

But our expected behavior was:

```text
User A
   ↓
ReportService Object 1
   ↓
["Order-A"]


User B
   ↓
ReportService Object 2
   ↓
["Order-B"]
```

Instead, we got:

```text
User A ───┐
          ↓
   ReportService Object 1
          ↑
User B ───┘
          ↓
["Order-A", "Order-B"]
```

So the state is unintentionally shared.

### 🔥 Why Does This Happen?

Prototype means:

> **Spring creates a new object every time the Prototype Bean is requested from the Spring Container.**

During normal constructor injection:

```java
public OrderService(ReportService reportService) {
    this.reportService = reportService;
}
```

Spring requests `ReportService` only once:

```text
Singleton Creation
       ↓
Request Prototype
       ↓
Create Object 1
       ↓
Inject Object 1
```

Later method calls:

```java
generateReport();
generateReport();
generateReport();
```

do not request another bean from Spring.

They simply reuse:

```java
this.reportService
```

which still points to:

```text
ReportService Object 1
```

### ✅ How Do We Solve It?

If we actually need a new Prototype Bean for each operation, the Singleton must request a new object from Spring each time.

For example, using `ObjectProvider`:

```java
@Service
public class OrderService {

    private final ObjectProvider<ReportService> provider;

    public OrderService(
            ObjectProvider<ReportService> provider) {
        this.provider = provider;
    }

    public void generateReport(String order) {

        ReportService reportService =
                provider.getObject();

        reportService.addData(order);
    }
}
```

Now:

```text
Operation 1
    ↓
getObject()
    ↓
Prototype Object 1


Operation 2
    ↓
getObject()
    ↓
Prototype Object 2


Operation 3
    ↓
getObject()
    ↓
Prototype Object 3
```

Spring also provides approaches such as `@Lookup` for this requirement.

### 🎤 Interview-Ready Answer

> **When a Prototype Bean is directly injected into a Singleton Bean, the prototype is created only when the singleton is created. The singleton then keeps the same prototype reference. This becomes a problem when we expect a fresh prototype instance for every operation, especially if the prototype contains mutable state. In that situation, we can dynamically request a new prototype using `ObjectProvider`, `@Lookup`, or another appropriate scoped lookup mechanism.**
---

<h3 id="sb_029">What is `@Lookup`?</h3>

`@Lookup` is a Spring annotation used when a bean needs to **get a fresh instance of another bean from the Spring Container whenever a method is called**.

A common use case is:

> **A Singleton Bean needs a new Prototype Bean for every operation.**

### 🔹 Why Do We Need `@Lookup`?

Suppose `ReportService` is Prototype scoped:

```java
@Component
@Scope("prototype")
public class ReportService {
}
```

If we directly inject it into a Singleton:

```java
@Service
public class OrderService {

    private final ReportService reportService;

    public OrderService(ReportService reportService) {
        this.reportService = reportService;
    }
}
```

The prototype is resolved when the Singleton is created.

So:

```text
OrderService Singleton
        ↓
ReportService Object 1
        ↓
Same object continues to be used
```

But suppose our requirement is:

```text
generateReport()
       ↓
ReportService Object 1


generateReport()
       ↓
ReportService Object 2


generateReport()
       ↓
ReportService Object 3
```

We need to ask Spring for a new Prototype Bean each time.

This is where `@Lookup` can be used.

### 🔹 Example Using `@Lookup`

```java
@Service
public class OrderService {

    public void generateReport() {

        ReportService reportService =
                getReportService();

        System.out.println(reportService);
    }

    @Lookup
    protected ReportService getReportService() {
        return null;
    }
}
```

The method:

```java
getReportService();
```

is annotated with:

```java
@Lookup
```

Spring overrides this method at runtime and retrieves `ReportService` from the Spring Container.

### 🔹 What Happens on Each Call?

```text
generateReport()
       ↓
getReportService()
       ↓
Spring Container
       ↓
Prototype requested
       ↓
ReportService Object 1
```

Next call:

```text
generateReport()
       ↓
getReportService()
       ↓
Spring Container
       ↓
Prototype requested again
       ↓
ReportService Object 2
```

Therefore:

```text
@Lookup Method Call
        ↓
Ask Spring Container
        ↓
Prototype Bean Requested
        ↓
New Object Returned
```

### 🔹 Why Does the Method Return `null`?

We may write:

```java
@Lookup
protected ReportService getReportService() {
    return null;
}
```

Normally, returning `null` would not make sense.

But Spring replaces/overrides this method behavior at runtime.

Conceptually, Spring makes it behave like:

```java
protected ReportService getReportService() {
    return applicationContext.getBean(ReportService.class);
}
```

So our original `return null` implementation is not what gets used when Spring manages the bean with lookup-method injection.

## 🔹 How Does `@Lookup` Work Internally?

Spring uses **method injection**.

Conceptually:

```text
Original OrderService
        ↓
Spring creates runtime subclass
        ↓
Overrides @Lookup method
        ↓
getReportService()
        ↓
Spring Container lookup
        ↓
ReportService returned
```

Because Spring needs to override the lookup method, the method must be overridable.

For example, making the lookup method `final` would prevent this mechanism.

---

## 🔹 `@Lookup` vs `ObjectProvider`

Both can be used when we need dynamic access to a bean.

### Using `@Lookup`

```java
@Lookup
protected ReportService getReportService() {
    return null;
}
```

Spring handles the lookup through method injection.

### Using `ObjectProvider`

```java
private final ObjectProvider<ReportService> provider;

public OrderService(
        ObjectProvider<ReportService> provider) {
    this.provider = provider;
}
```

Then:

```java
ReportService reportService =
        provider.getObject();
```

Here, the lookup is explicit in our code.

### 🎤 Interview-Ready Answer

> **`@Lookup` is a Spring annotation used for method injection. It is useful when a long-lived bean such as a Singleton needs a fresh instance of a shorter-lived bean such as a Prototype. Spring overrides the method annotated with `@Lookup` at runtime, and whenever that method is called, Spring performs a bean lookup from the container. If the requested bean is Prototype scoped, a new instance is returned for each lookup.**

## 🧠 Easy to Remember

```text
Singleton
    ↓
Needs fresh Prototype
    ↓
@Lookup method called
    ↓
Spring Container asked for Bean
    ↓
New Prototype returned
```

> **`@Lookup` = Ask Spring for the bean again whenever the lookup method is called.**

---

<h3 id="sb_030">What is Bean Lifecycle?</h3>

The **Spring Bean Lifecycle** is the sequence of steps a Spring Bean goes through from **creation until destruction**.

In simple terms:

> **Spring creates the bean, injects its dependencies, initializes it, makes it ready for use, and finally destroys it when the container shuts down.**

### 🔹 Bean Lifecycle Flow

```text
1. Bean Definition Loaded
        ↓
2. Bean Instantiation
        ↓
3. Dependency Injection
        ↓
4. Aware Interface Callbacks
        ↓
5. BeanPostProcessor - Before Initialization
        ↓
6. @PostConstruct
        ↓
7. InitializingBean.afterPropertiesSet()
        ↓
8. Custom initMethod
        ↓
9. BeanPostProcessor - After Initialization
        ↓
10. Bean Ready for Use
        ↓
11. @PreDestroy
        ↓
12. DisposableBean.destroy()
        ↓
13. Custom destroyMethod
```


## 1️⃣ Bean Definition Loaded

Before creating the bean, Spring first has metadata describing it.

For example:

```java
@Service
public class OrderService {
}
```

Spring registers information such as:

```text
Bean Name
Bean Class
Bean Scope
Dependencies
Lazy/Eager Configuration
Initialization Methods
Destruction Methods
```

This metadata is represented internally using a `BeanDefinition`.

---

## 2️⃣ Bean Instantiation

Spring creates the actual Java object.

```text
BeanDefinition
      ↓
Spring creates object
      ↓
OrderService instance
```

At this point, the object exists.

---

## 3️⃣ Dependency Injection

Spring resolves and supplies the bean's dependencies.

```java
public OrderService(PaymentService paymentService) {
    this.paymentService = paymentService;
}
```

```text
PaymentService
      ↓
Injected into
      ↓
OrderService
```

---

## 4️⃣ Aware Interface Callbacks

If the bean implements Spring `Aware` interfaces, Spring provides the requested container information.

Examples:

```text
BeanNameAware
BeanFactoryAware
ApplicationContextAware
```

For example:

```java
@Override
public void setBeanName(String beanName) {
    this.beanName = beanName;
}
```

---

## 5️⃣ BeanPostProcessor - Before Initialization

Registered `BeanPostProcessor`s can process the bean before initialization callbacks.

Conceptually:

```java
postProcessBeforeInitialization(bean, beanName);
```

Flow:

```text
Bean
 ↓
BeanPostProcessor
 ↓
Before Initialization
```

---

## 6️⃣ `@PostConstruct`

Spring invokes methods annotated with `@PostConstruct`.

```java
@PostConstruct
public void init() {
    System.out.println("Initializing OrderService");
}
```

This is commonly used when initialization logic should run after dependencies are available.

---

## 7️⃣ `InitializingBean.afterPropertiesSet()`

If the bean implements:

```java
InitializingBean
```

Spring calls:

```java
afterPropertiesSet();
```

Example:

```java
@Override
public void afterPropertiesSet() {
    System.out.println("Initialization completed");
}
```

---

## 8️⃣ Custom `initMethod`

If a custom initialization method is configured:

```java
@Bean(initMethod = "initialize")
public PaymentClient paymentClient() {
    return new PaymentClient();
}
```

Spring calls:

```java
initialize();
```

---

## 9️⃣ BeanPostProcessor - After Initialization

Spring executes:

```java
postProcessAfterInitialization(bean, beanName);
```

This stage is especially important because infrastructure may return a **wrapped/proxied object** instead of the original object.

Conceptually:

```text
Original Bean
     ↓
BeanPostProcessor
     ↓
Possible Proxy Creation
     ↓
Final Bean Reference
```

This is important for features based on Spring proxies, such as AOP.

### 🔟 Bean Ready for Use

After initialization completes:

```text
Bean Created
    ↓
Dependencies Injected
    ↓
Initialization Completed
    ↓
Post Processing Completed
    ↓
READY
```

The application can now use the bean.

### 🔻 Destruction Phase

When the Spring Container shuts down, destruction callbacks can run for beans whose destruction lifecycle the container manages.

### 1️⃣1️⃣ `@PreDestroy`

```java
@PreDestroy
public void cleanup() {
    System.out.println("Cleaning resources");
}
```

This is commonly used for cleanup logic.

### 1️⃣2️⃣ `DisposableBean.destroy()`

If the bean implements:

```java
DisposableBean
```

Spring calls:

```java
destroy();
```

### 1️⃣3️⃣ Custom `destroyMethod`

A custom destruction method can also be configured:

```java
@Bean(destroyMethod = "close")
public PaymentClient paymentClient() {
    return new PaymentClient();
}
```

Spring calls:

```java
close();
```

during destruction.

### 🎯 Initialization Order

If multiple initialization mechanisms are configured, remember:

```text
@PostConstruct
      ↓
InitializingBean.afterPropertiesSet()
      ↓
Custom initMethod
```

### 🎯 Destruction Order

Similarly:

```text
@PreDestroy
      ↓
DisposableBean.destroy()
      ↓
Custom destroyMethod
```

### ⚠️ Important: Prototype Beans

Spring does not manage the complete destruction lifecycle of prototype beans.

For a prototype bean, Spring mainly handles:

```text
Creation
   ↓
Dependency Injection
   ↓
Initialization
   ↓
Returns Bean
```

After that, destruction/cleanup of that prototype instance is generally the application's responsibility.

# ⚠️ Why Is the Destruction Lifecycle Not Automatically Managed for Prototype Beans?

For a **Prototype Bean**, Spring manages the bean through **creation, dependency injection, and initialization**, but it does not automatically manage that bean instance through destruction.

### 🔹 Singleton Bean

For a Singleton Bean, Spring keeps the bean inside the container.

```text
Spring creates Bean
        ↓
Injects Dependencies
        ↓
Initializes Bean
        ↓
Spring keeps managing Bean
        ↓
Application runs
        ↓
Container shuts down
        ↓
Spring destroys Bean
        ↓
@PreDestroy ✅
```

Because Spring continues managing the Singleton Bean, it knows when the bean should be destroyed.

### 🔹 Prototype Bean

For a Prototype Bean:

```text
Application requests Prototype Bean
        ↓
Spring creates Bean
        ↓
Injects Dependencies
        ↓
Runs Initialization
        ↓
Returns Bean to Application
        ↓
Application uses Bean
```

After Spring returns the Prototype Bean, Spring does **not automatically manage the complete destruction lifecycle of that individual instance**.

Therefore:

```java
@PreDestroy
```

is **not automatically called** by the container for prototype instances.

### 🔹 Example

```java
@Component
@Scope("prototype")
public class ReportService {

    @PostConstruct
    public void init() {
        System.out.println("ReportService Created");
    }

    @PreDestroy
    public void destroy() {
        System.out.println("ReportService Destroyed");
    }
}
```

When:

```java
ReportService report =
        context.getBean(ReportService.class);
```

Spring performs:

```text
Create ReportService
        ↓
Inject Dependencies
        ↓
@PostConstruct ✅
        ↓
Return Bean
```

But Spring does not automatically perform:

```text
@PreDestroy ❌
```

for that Prototype Bean.

### 🔹 Why?

Spring does not know exactly when the application has finished using that particular Prototype object.

For example:

```text
Prototype Object 1 → Used for 5 seconds

Prototype Object 2 → Used for 10 minutes

Prototype Object 3 → Used for 2 hours
```

Once those objects have been handed to application code, the container cannot automatically determine when each individual object is no longer needed.

Therefore, it cannot automatically decide:

```text
"When should I run its destruction callback?"
```

### 🔹 Who Handles Cleanup?

If the Prototype Bean owns resources that require explicit cleanup, the application using that bean should perform the necessary cleanup.

For example:

```java
ReportService report =
        context.getBean(ReportService.class);

try {

    report.generate();

} finally {

    report.close();
}
```

This is especially important if the object owns resources such as:

```text
File handles
Connections
Streams
Threads
Other external resources
```

> **For a Prototype Bean, Spring manages creation, dependency injection, and initialization, but it does not automatically manage the complete destruction lifecycle. Once Spring creates and returns a Prototype Bean to the application, it does not determine when that individual instance is no longer needed. Therefore, destruction callbacks such as `@PreDestroy` are not automatically invoked, and any required resource cleanup should be handled explicitly by the application.**


### 🎤 Interview-Ready Answer

> **The Spring Bean Lifecycle starts when Spring loads the bean definition and instantiates the bean. It then resolves and injects dependencies and invokes any required Aware callbacks. After that, BeanPostProcessors run before initialization, followed by initialization callbacks such as `@PostConstruct`, `afterPropertiesSet()`, and a custom init method. BeanPostProcessors then run after initialization, where proxy creation can also occur. The bean is then ready for use. During container shutdown, Spring invokes destruction callbacks such as `@PreDestroy`, `DisposableBean.destroy()`, and configured destroy methods.**

---

<h3 id="sb_031">Explain the complete Spring Bean Lifecycle.</h3>



<h3 id="sb_032">What is `@PostConstruct`?</h3>

`@PostConstruct` is used to mark a method that should run **after Spring creates the bean and injects its dependencies**. It is mainly used for **initialization logic that requires the bean's dependencies to already be available**.

So when `initialize()` executes, the required dependencies have already been injected.


## 🔹 When Do We Use `@PostConstruct`?

Use it when some initialization must happen **once after a bean has been created and configured**.

For example:

```java
@Service
public class ProductService {

    private final ProductRepository productRepository;

    private Map<Long, String> productCache;

    public ProductService(ProductRepository productRepository) {
        this.productRepository = productRepository;
    }

    @PostConstruct
    public void loadProducts() {

        productCache = new HashMap<>();

        productRepository.findAll()
                .forEach(product ->
                    productCache.put(
                        product.getId(),
                        product.getName()
                    )
                );
    }
}
```

Here:

```text
ProductService Created
        ↓
ProductRepository Injected
        ↓
@PostConstruct
        ↓
Load initial product data
        ↓
Service Ready
```


## 🔹 Why Not Put This Logic in the Constructor?

Consider:

```java
public ProductService(ProductRepository productRepository) {

    this.productRepository = productRepository;

    // lots of initialization logic
}
```

The constructor's primary purpose should generally be to establish the object's required state.

If additional initialization must happen after Spring has completed dependency injection, `@PostConstruct` provides an explicit lifecycle hook.

---

## 🔹 Method Requirements

A typical `@PostConstruct` method looks like:

```java
@PostConstruct
public void init() {

}
```

It should not require method arguments.

---

## ⚠️ Package Used in Modern Spring

In modern Spring Boot versions using Jakarta APIs:

```java
import jakarta.annotation.PostConstruct;
```

Older applications may contain:

```java
import javax.annotation.PostConstruct;
```

---

<h3 id="sb_033">What is `@PreDestroy`?</h3>

`@PreDestroy` is a lifecycle annotation used to execute **cleanup logic before a Spring-managed Bean is destroyed**.

It is commonly used to release resources before the Spring Container shuts down.

### 🔹 Example

```java
@Service
public class PaymentService {

    @PreDestroy
    public void cleanup() {
        System.out.println("Cleaning up PaymentService resources");
    }
}
```

When the application shuts down normally:

```text
Application Running
        ↓
Spring Container Shutting Down
        ↓
@PreDestroy
        ↓
Cleanup Logic Executed
        ↓
Bean Destroyed
```

### 🔹 When Do We Use `@PreDestroy`?

Use it when a Bean owns resources that require explicit cleanup.

Examples:

- Closing custom connections
- Closing files or streams
- Stopping background threads/executors
- Unsubscribing from external resources
- Releasing other resources owned by the Bean

Example:

```java
@Component
public class ReportService {

    private final ExecutorService executor =
            Executors.newFixedThreadPool(5);

    @PreDestroy
    public void shutdown() {
        executor.shutdown();
    }
}
```

Before the Bean is destroyed, the executor is shut down properly.

### 🎤 Interview-Ready Answer

> **`@PreDestroy` is a lifecycle annotation used to execute cleanup logic before a Spring-managed Bean is destroyed. It is useful for releasing resources such as custom connections, executors, files, or other resources owned by the Bean. It is normally called when the Spring Container shuts down, but Spring does not automatically invoke it for Prototype Bean instances.**

---

<h3 id="sb_034">What is `InitializingBean`?</h3>


`InitializingBean` is a Spring lifecycle interface used to execute **initialization logic after Spring has injected the bean's dependencies**.

It provides one method:

```java
void afterPropertiesSet() throws Exception;
```

Spring automatically calls `afterPropertiesSet()` during bean initialization.


## 🔹 Example

```java
@Service
public class PaymentService implements InitializingBean {

    @Override
    public void afterPropertiesSet() {
        System.out.println("PaymentService initialized");
    }
}
```

Spring calls:

```java
afterPropertiesSet();
```

after the bean's dependencies have been configured.

---

## 🔹 When Is It Used?

It can be used when a bean needs to perform some initialization after its required properties/dependencies are available.

For example:

```java
@Service
public class PaymentService implements InitializingBean {

    private final PaymentClient paymentClient;

    public PaymentService(PaymentClient paymentClient) {
        this.paymentClient = paymentClient;
    }

    @Override
    public void afterPropertiesSet() {
        paymentClient.initialize();
    }
}
```

### 🎤 Interview-Ready Answer

> **`InitializingBean` is a Spring lifecycle interface that provides the `afterPropertiesSet()` method. Spring calls this method after the bean's dependencies have been configured, so it can be used for initialization logic. However, it creates a direct dependency on the Spring API, so `@PostConstruct` is often preferred for application-level initialization.**

---

<h3 id="sb_035">What is `DisposableBean`?</h3>


`DisposableBean` is a Spring lifecycle interface used to execute **cleanup logic before a Spring-managed bean is destroyed**.

It provides one method:

```java
void destroy() throws Exception;
```

Spring calls the `destroy()` method when the container is shutting down and the bean is being destroyed.

---

## 🔹 Example

```java
@Service
public class PaymentService implements DisposableBean {

    @Override
    public void destroy() {
        System.out.println("Cleaning PaymentService resources");
    }
}
```

The `destroy()` method can be used to release resources owned by the bean.

For example:

```java
@Component
public class FileService implements DisposableBean {

    @Override
    public void destroy() {
        // Close files, connections, executors, etc.
    }
}
```

---

## 🔹 When Is It Used?

Use it when the bean needs cleanup before destruction, such as:

- Closing connections
- Closing files or streams
- Stopping executors or background threads
- Releasing resources owned by the bean

## 🎤 Interview-Ready Answer

> **`DisposableBean` is a Spring lifecycle interface that provides the `destroy()` method. Spring invokes this method before destroying a managed bean, so it can be used to release resources such as connections, files, or background executors. Since implementing `DisposableBean` directly couples the class to Spring, `@PreDestroy` is often preferred for application-level cleanup.**

---

<h3 id="sb_036">`@PostConstruct` vs `InitializingBean`</h3>

Both are used to execute **initialization logic after Spring has configured the bean's dependencies**.

The main difference is **how the initialization logic is defined and whether the class becomes directly dependent on Spring APIs**.

---

## 🔹 `@PostConstruct`

`@PostConstruct` is an annotation placed on an initialization method.

```java
@Service
public class PaymentService {

    @PostConstruct
    public void initialize() {
        System.out.println("PaymentService initialized");
    }
}
```

The class does not need to implement a Spring lifecycle interface.

---

## 🔹 `InitializingBean`

With `InitializingBean`, the class implements Spring's lifecycle interface and overrides:

```java
afterPropertiesSet()
```

Example:

```java
@Service
public class PaymentService implements InitializingBean {

    @Override
    public void afterPropertiesSet() {
        System.out.println("PaymentService initialized");
    }
}
```

This creates a direct dependency on the Spring API:

```java
implements InitializingBean
```

---

## 📊 Main Difference

| `@PostConstruct` | `InitializingBean` |
|---|---|
| Annotation-based | Interface-based |
| Method can have a meaningful name like `initialize()` | Must implement `afterPropertiesSet()` |
| Does not require implementing a Spring lifecycle interface | Directly depends on Spring's `InitializingBean` |
| Usually preferred for application code | Useful when Spring-specific lifecycle integration is acceptable |

---

## ⚠️ If Both Are Used

If the same bean uses both:

```java
@PostConstruct
public void firstInit() {
}
```

and:

```java
@Override
public void afterPropertiesSet() {
}
```

the order is:

```text
@PostConstruct
      ↓
InitializingBean.afterPropertiesSet()
```

---

## 🎤 Interview-Ready Answer

> **Both `@PostConstruct` and `InitializingBean` are used for bean initialization after dependencies are configured. `@PostConstruct` is annotation-based and does not require the class to implement a Spring lifecycle interface, whereas `InitializingBean` requires implementing Spring's `InitializingBean` interface and overriding `afterPropertiesSet()`. I generally prefer `@PostConstruct` for application code because it avoids directly coupling the class to Spring's lifecycle interface.**

---

# 🟢 `@PreDestroy` vs `DisposableBean`

Both are used to run **cleanup logic before a Spring-managed Bean is destroyed**.

The main difference is how we define the cleanup method.

---

## 🔹 `@PreDestroy`

We annotate our own cleanup method with `@PreDestroy`.

```java
@Service
public class PaymentService {

    @PreDestroy
    public void cleanup() {
        System.out.println("Cleaning resources...");
    }
}
```

Spring calls:

```java
cleanup();
```

before destroying the Bean.

---

## 🔹 `DisposableBean`

The class implements Spring's `DisposableBean` interface.

```java
@Service
public class PaymentService implements DisposableBean {

    @Override
    public void destroy() {
        System.out.println("Cleaning resources...");
    }
}
```

Spring calls:

```java
destroy();
```

before destroying the Bean.

---

## 📊 Simple Difference

| `@PreDestroy` | `DisposableBean` |
|---|---|
| Annotation-based | Interface-based |
| We define our own method name | Must implement `destroy()` |
| No need to implement a Spring interface | Class becomes directly dependent on Spring's API |
| Generally preferred for application code | Useful when Spring-specific lifecycle integration is acceptable |

---

## 🎤 Interview-Ready Answer

> **Both `@PreDestroy` and `DisposableBean` are used for cleanup before a Spring-managed Bean is destroyed. `@PreDestroy` is annotation-based, whereas `DisposableBean` is a Spring interface that requires implementing the `destroy()` method. I generally prefer `@PreDestroy` because it avoids directly coupling the application class to Spring's `DisposableBean` interface.**

---

## 🧠 Easy to Remember

```text
@PostConstruct  → Initialization annotation
InitializingBean → Initialization interface

@PreDestroy     → Destruction annotation
DisposableBean  → Destruction interface
```
---

<h3 id="sb_037">What are `initMethod` and `destroyMethod`?</h3>

initMethod and destroyMethod are used to tell Spring which methods of a bean should be called automatically during initialization and destruction. They are useful when we want to define bean lifecycle behavior without using @PostConstruct, @PreDestroy, InitializingBean, or DisposableBean.

initMethod and destroyMethod are custom lifecycle methods configured while defining a Spring bean. initMethod runs during bean initialization, and destroyMethod runs during bean destruction. They are especially useful for third-party classes where we cannot add Spring lifecycle annotations or implement Spring lifecycle interfaces.


`initMethod` and `destroyMethod` are used to tell Spring:

- **Which method should run when the Bean is initialized**
- **Which method should run before the Bean is destroyed**

They are configured using `@Bean`.

### 🔹 Simple Example
 
Suppose we have a normal Java class:
 
```java
public class PaymentClient {
 
public void connect() {
System.out.println("Payment connection started");
}
 
public void disconnect() {
System.out.println("Payment connection closed");
}
}
```
 
There are no Spring annotations inside this class.
 
Now we register it as a Spring Bean:
 
```java
@Configuration
public class AppConfig {
 
@Bean(
initMethod = "connect",
destroyMethod = "disconnect"
)
public PaymentClient paymentClient() {
return new PaymentClient();
}
}
```
 
We are telling Spring:
 
```text
When PaymentClient Bean is initialized
↓
Call connect()
 
 
When PaymentClient Bean is destroyed
↓
Call disconnect()
```
 
### 🔹 How It Works
 
When the application starts:
 
```text
Spring creates PaymentClient
↓
Spring calls connect()
↓
PaymentClient ready
```
 
When the application shuts down:
 
```text
Spring Container shutting down
↓
Spring calls disconnect()
↓
PaymentClient destroyed
```
 
### 🔹 Why Do We Need This?
 
Imagine `PaymentClient` comes from an external library.
 
You cannot change its source code.
 
The class already provides:
 
```java
connect();
```
 
and:
 
```java
disconnect();
```
 
You cannot add:
 
```java
@PostConstruct
```
 
or:
 
```java
@PreDestroy
```
 
because you don't own the class.
 
Instead, while registering the object as a Spring Bean, you tell Spring:
 
```java
@Bean(
initMethod = "connect",
destroyMethod = "disconnect"
)
```
 
So Spring knows which existing methods should be used for initialization and cleanup.
  
### 🎤 Interview-Ready Answer
 
> **`initMethod` and `destroyMethod` are used with `@Bean` to specify custom initialization and cleanup methods. Spring calls the `initMethod` during Bean initialization and the `destroyMethod` before Bean destruction. They are particularly useful when configuring third-party classes that already provide setup and cleanup methods but cannot be modified to add Spring lifecycle annotations.**

---

<h3 id="sb_038">What is `@Component`?</h3>

`@Component` is a Spring annotation used to tell Spring that a class should be **automatically detected, instantiated, and managed as a Spring Bean**.

When component scanning finds a class annotated with `@Component`, Spring registers it in the IoC Container.

### 🔹 Example

```java
@Component
public class EmailService {

    public void sendEmail() {
        System.out.println("Email sent");
    }
}


<h3 id="sb_039">What is `@Service`?</h3>

`@Service` is a Spring stereotype annotation used to mark a class as part of the **service or business logic layer**.

Spring detects the class during component scanning and manages it as a Spring Bean.

### 🔹 Example

```java
@Service
public class OrderService {

    public void createOrder() {
        // Business logic
    }
}
```

The `@Service` class usually contains the application's **business logic** and coordinates operations between controllers, repositories, and other services.

---

<h3 id="sb_040">What is `@Repository`?</h3>


`@Repository` is a Spring stereotype annotation used to mark a class as part of the **data access or persistence layer**.

It is generally used for classes that interact with a database.

### 🔹 Example

```java
@Repository
public class OrderRepository {

    public void save(Order order) {
        // Database operation
    }
}
```

The Repository layer is responsible for operations such as:

```text
Save data
Read data
Update data
Delete data
Execute database queries
```

### 🎤 Interview-Ready Answer

> **`@Repository` is a Spring stereotype annotation used to identify a class as part of the persistence or data-access layer. Like `@Component`, it makes the class eligible for Spring component scanning and bean management. The important additional feature is persistence exception translation, where supported persistence exceptions can be translated into Spring's `DataAccessException` hierarchy. With Spring Data JPA repository interfaces, we usually don't need to explicitly add `@Repository` because Spring Data automatically creates and manages the repository implementation.**

---

<h3 id="sb_041">What is `@Controller`?</h3>


`@Controller` is a Spring MVC stereotype annotation used to mark a class as a **web controller that handles incoming HTTP requests**.

A controller receives a request, calls the required service/business logic, and returns a **view name** or response.

### 🔹 Example

```java
@Controller
public class UserController {

    private final UserService userService;

    public UserController(UserService userService) {
        this.userService = userService;
    }

    @GetMapping("/users")
    public String getUsers(Model model) {

        model.addAttribute(
            "users",
            userService.getUsers()
        );

        return "users";
    }
}
```

Here:

```text
GET /users
     ↓
UserController
     ↓
UserService
     ↓
Add data to Model
     ↓
Return "users"
     ↓
View rendered to client
```

The returned:

```java
return "users";
```

normally represents a **view name**, such as a Thymeleaf/JSP page, rather than the literal text `"users"` being returned in the HTTP response body.

### 🔹 Can `@Controller` Return JSON?

Yes, but the handler method should indicate that the return value goes into the HTTP response body.

For example:

```java
@Controller
public class UserController {

    @GetMapping("/users")
    @ResponseBody
    public List<User> getUsers() {
        return userService.getUsers();
    }
}
```

`@ResponseBody` tells Spring:

```text
Don't treat return value as View
           ↓
Write return value to HTTP response body
```

For REST APIs, instead of adding `@ResponseBody` to every method, we normally use:

```java
@RestController
```

### 🎤 Interview-Ready Answer

> **`@Controller` is a Spring MVC stereotype annotation used to define a web controller that handles HTTP requests. Controller methods are mapped to URLs using annotations such as `@GetMapping` and `@PostMapping`. By default, a returned String is typically interpreted as a view name. If we want to return data directly in the HTTP response body, we can use `@ResponseBody`, or use `@RestController` for REST APIs.**

---

<h3 id="sb_042">What is `@RestController`?</h3>



<h3 id="sb_043">`@Controller` vs `@RestController`</h3>



<h3 id="sb_044">`@Component` vs `@Bean`</h3>



<h3 id="sb_045">Why do we have `@Service` if `@Component` can do the same thing?</h3>



<h3 id="sb_046">What special behavior does `@Repository` provide?</h3>



<h3 id="sb_047">What is Component Scanning?</h3>



<h3 id="sb_048">How does `@ComponentScan` work?</h3>



<h3 id="sb_049">What happens if a component is outside the base package?</h3>



<h3 id="sb_050">What are Spring configuration approaches?</h3>



<h3 id="sb_051">XML Configuration</h3>



<h3 id="sb_052">Java Configuration</h3>



<h3 id="sb_053">Annotation Configuration</h3>



<h3 id="sb_054">What is `@Configuration`?</h3>



<h3 id="sb_055">What is `@Bean`?</h3>



<h3 id="sb_056">What is `@Import`?</h3>



<h3 id="sb_057">What is `@Value`?</h3>



<h3 id="sb_058">What is `Environment`?</h3>



<h3 id="sb_059">What is `@PropertySource`?</h3>



## 2. Spring Internals



<h3 id="sb_060">How does Spring Container start?</h3>



<h3 id="sb_061">How does Spring discover Beans?</h3>



<h3 id="sb_062">How does Spring instantiate Beans?</h3>



<h3 id="sb_063">How are dependencies resolved?</h3>



<h3 id="sb_064">How does Spring maintain Beans internally?</h3>



<h3 id="sb_065">What is `BeanDefinition`?</h3>



<h3 id="sb_066">What is `BeanDefinitionRegistry`?</h3>



<h3 id="sb_067">What is `BeanFactoryPostProcessor`?</h3>



<h3 id="sb_068">What is `BeanPostProcessor`?</h3>



<h3 id="sb_069">`BeanFactoryPostProcessor` vs `BeanPostProcessor`</h3>



<h3 id="sb_070">When does BeanPostProcessor execute?</h3>



<h3 id="sb_071">How does `@Autowired` work internally?</h3>



<h3 id="sb_072">What is `AutowiredAnnotationBeanPostProcessor`?</h3>



<h3 id="sb_073">How does Spring resolve dependency by type?</h3>



<h3 id="sb_074">What happens if multiple Beans of the same type exist?</h3>



<h3 id="sb_075">What is `NoUniqueBeanDefinitionException`?</h3>



<h3 id="sb_076">What is `NoSuchBeanDefinitionException`?</h3>



<h3 id="sb_077">What is `@Qualifier`?</h3>



<h3 id="sb_078">What is `@Primary`?</h3>



<h3 id="sb_079">`@Qualifier` vs `@Primary`</h3>



<h3 id="sb_080">Can `@Autowired` be used on constructors?</h3>



<h3 id="sb_081">Is `@Autowired` required for a single constructor?</h3>



<h3 id="sb_082">What is Circular Dependency?</h3>



<h3 id="sb_083">Why can constructor circular dependency fail?</h3>



<h3 id="sb_084">How does Spring handle setter/field circular dependency?</h3>



<h3 id="sb_085">What are Spring's three-level singleton caches?</h3>



<h3 id="sb_086">What is `singletonObjects`?</h3>



<h3 id="sb_087">What is `earlySingletonObjects`?</h3>



<h3 id="sb_088">What is `singletonFactories`?</h3>



<h3 id="sb_089">Why are circular references discouraged?</h3>



<h3 id="sb_090">How do you redesign code to remove circular dependencies?</h3>



<h3 id="sb_091">What is Lazy Initialization?</h3>



<h3 id="sb_092">What is `@Lazy`?</h3>



<h3 id="sb_093">Where can `@Lazy` be used?</h3>



<h3 id="sb_094">Lazy vs Eager initialization</h3>



<h3 id="sb_095">What is Spring Expression Language (SpEL)?</h3>



<h3 id="sb_096">What can SpEL be used for?</h3>



<h3 id="sb_097">What are proxies in Spring?</h3>



<h3 id="sb_098">JDK Dynamic Proxy vs CGLIB Proxy</h3>



<h3 id="sb_099">When does Spring use a JDK proxy?</h3>



<h3 id="sb_100">When does Spring use a CGLIB proxy?</h3>



<h3 id="sb_101">Why are Spring proxies important?</h3>



<h3 id="sb_102">What is self-invocation?</h3>



<h3 id="sb_103">Why can self-invocation bypass Spring proxy behavior?</h3>



<h3 id="sb_104">Which Spring features depend heavily on proxies?</h3>



## 3. Spring AOP



<h3 id="sb_105">What is AOP?</h3>



<h3 id="sb_106">Why was AOP introduced?</h3>



<h3 id="sb_107">What are Cross-Cutting Concerns?</h3>



<h3 id="sb_108">What is an Aspect?</h3>



<h3 id="sb_109">What is Advice?</h3>



<h3 id="sb_110">What is Join Point?</h3>



<h3 id="sb_111">What is Pointcut?</h3>



<h3 id="sb_112">What is Target Object?</h3>



<h3 id="sb_113">What is Weaving?</h3>



<h3 id="sb_114">Compile-time vs Load-time vs Runtime weaving</h3>



<h3 id="sb_115">How does Spring AOP work internally?</h3>



<h3 id="sb_116">Spring AOP vs AspectJ</h3>



<h3 id="sb_117">What is `@Aspect`?</h3>



<h3 id="sb_118">What is `@Before`?</h3>



<h3 id="sb_119">What is `@After`?</h3>



<h3 id="sb_120">What is `@AfterReturning`?</h3>



<h3 id="sb_121">What is `@AfterThrowing`?</h3>



<h3 id="sb_122">What is `@Around`?</h3>



<h3 id="sb_123">Which Advice is most powerful?</h3>



<h3 id="sb_124">What is `ProceedingJoinPoint`?</h3>



<h3 id="sb_125">What happens if `proceed()` is not called?</h3>



<h3 id="sb_126">How do you write a Pointcut expression?</h3>



<h3 id="sb_127">Explain the `execution()` Pointcut expression.</h3>



<h3 id="sb_128">Can multiple Pointcuts be combined?</h3>



<h3 id="sb_129">How do you control Aspect execution order?</h3>



<h3 id="sb_130">What is `@Order`?</h3>



<h3 id="sb_131">How does AOP use proxies?</h3>



<h3 id="sb_132">Why does AOP not work as expected with self-invocation?</h3>



<h3 id="sb_133">Can private methods be intercepted?</h3>



<h3 id="sb_134">Can final methods cause proxy limitations?</h3>



<h3 id="sb_135">Logging using AOP</h3>



<h3 id="sb_136">Performance monitoring using AOP</h3>



<h3 id="sb_137">Auditing using AOP</h3>



<h3 id="sb_138">Security using AOP</h3>



<h3 id="sb_139">Transaction management using AOP</h3>



## 4. Spring Boot Fundamentals and Internals



<h3 id="sb_140">Why Spring Boot?</h3>



<h3 id="sb_141">Spring vs Spring MVC vs Spring Boot</h3>



<h3 id="sb_142">Advantages of Spring Boot</h3>



<h3 id="sb_143">What is `@SpringBootApplication`?</h3>



<h3 id="sb_144">What annotations are inside `@SpringBootApplication`?</h3>



<h3 id="sb_145">What is `@SpringBootConfiguration`?</h3>



<h3 id="sb_146">What is `@EnableAutoConfiguration`?</h3>



<h3 id="sb_147">What is `@ComponentScan`?</h3>



<h3 id="sb_148">What happens when `SpringApplication.run()` executes?</h3>



<h3 id="sb_149">Explain Spring Boot application startup flow.</h3>



<h3 id="sb_150">How is `ApplicationContext` created?</h3>



<h3 id="sb_151">How does component scanning start?</h3>



<h3 id="sb_152">How does Auto Configuration work?</h3>



<h3 id="sb_153">What is conditional configuration?</h3>



<h3 id="sb_154">What is `@Conditional`?</h3>



<h3 id="sb_155">What is `@ConditionalOnClass`?</h3>



<h3 id="sb_156">What is `@ConditionalOnMissingBean`?</h3>



<h3 id="sb_157">What is `@ConditionalOnProperty`?</h3>



<h3 id="sb_158">What is `@ConditionalOnBean`?</h3>



<h3 id="sb_159">How does Boot decide which Auto Configurations to load?</h3>



<h3 id="sb_160">How can Auto Configuration be excluded?</h3>



<h3 id="sb_161">What are Starter Dependencies?</h3>



<h3 id="sb_162">How do starters simplify dependency management?</h3>



<h3 id="sb_163">What is Spring Boot's parent POM?</h3>



<h3 id="sb_164">What is dependency management?</h3>



<h3 id="sb_165">What is an Embedded Server?</h3>



<h3 id="sb_166">How does embedded Tomcat start?</h3>



<h3 id="sb_167">Tomcat vs Servlet Container</h3>



<h3 id="sb_168">Tomcat vs Application Server</h3>



<h3 id="sb_169">How do you replace Tomcat with Jetty or Undertow?</h3>



<h3 id="sb_170">What is `CommandLineRunner`?</h3>



<h3 id="sb_171">What is `ApplicationRunner`?</h3>



<h3 id="sb_172">`CommandLineRunner` vs `ApplicationRunner`</h3>



<h3 id="sb_173">What are Profiles?</h3>



<h3 id="sb_174">What is `@Profile`?</h3>



<h3 id="sb_175">How do dev/test/prod configurations work?</h3>



<h3 id="sb_176">`application.properties` vs `application.yml`</h3>



<h3 id="sb_177">Configuration precedence in Spring Boot</h3>



<h3 id="sb_178">Environment variables vs properties</h3>



<h3 id="sb_179">What is `@ConfigurationProperties`?</h3>



<h3 id="sb_180">`@Value` vs `@ConfigurationProperties`</h3>



<h3 id="sb_181">What is Actuator?</h3>



<h3 id="sb_182">Important Actuator endpoints</h3>



<h3 id="sb_183">`health`</h3>



<h3 id="sb_184">`metrics`</h3>



<h3 id="sb_185">`info`</h3>



<h3 id="sb_186">`beans`</h3>



<h3 id="sb_187">`env`</h3>



<h3 id="sb_188">How do you secure Actuator endpoints?</h3>



## 5. Spring MVC and REST API



<h3 id="sb_189">What is Spring MVC?</h3>



<h3 id="sb_190">Explain MVC Architecture.</h3>



<h3 id="sb_191">What is DispatcherServlet?</h3>



<h3 id="sb_192">Explain the complete request lifecycle.</h3>



<h3 id="sb_193">What is HandlerMapping?</h3>



<h3 id="sb_194">What is HandlerAdapter?</h3>



<h3 id="sb_195">What is ViewResolver?</h3>



<h3 id="sb_196">How does Spring identify the correct Controller method?</h3>



<h3 id="sb_197">`@Controller` vs `@RestController`</h3>



<h3 id="sb_198">What is `@RequestMapping`?</h3>



<h3 id="sb_199">What is `@GetMapping`?</h3>



<h3 id="sb_200">What is `@PostMapping`?</h3>



<h3 id="sb_201">What is `@PutMapping`?</h3>



<h3 id="sb_202">What is `@PatchMapping`?</h3>



<h3 id="sb_203">What is `@DeleteMapping`?</h3>



<h3 id="sb_204">What is `@PathVariable`?</h3>



<h3 id="sb_205">What is `@RequestParam`?</h3>



<h3 id="sb_206">What is `@RequestBody`?</h3>



<h3 id="sb_207">What is `@RequestHeader`?</h3>



<h3 id="sb_208">What is `@ResponseBody`?</h3>



<h3 id="sb_209">What is `ResponseEntity`?</h3>



<h3 id="sb_210">Why use `ResponseEntity`?</h3>



<h3 id="sb_211">POST vs PUT vs PATCH</h3>



<h3 id="sb_212">PUT vs PATCH</h3>



<h3 id="sb_213">What does idempotent mean?</h3>



<h3 id="sb_214">Which HTTP methods are idempotent?</h3>



<h3 id="sb_215">Important HTTP Status Codes</h3>



<h3 id="sb_216">`200` vs `201`</h3>



<h3 id="sb_217">`400` vs `422`</h3>



<h3 id="sb_218">`401` vs `403`</h3>



<h3 id="sb_219">`404` vs `204`</h3>



<h3 id="sb_220">When should `409 Conflict` be used?</h3>



<h3 id="sb_221">REST API naming conventions</h3>



<h3 id="sb_222">API versioning</h3>



<h3 id="sb_223">URI versioning vs Header versioning</h3>



<h3 id="sb_224">Pagination in REST APIs</h3>



<h3 id="sb_225">Sorting APIs</h3>



<h3 id="sb_226">Filtering APIs</h3>



<h3 id="sb_227">API Error Response Design</h3>



<h3 id="sb_228">How should you return validation errors?</h3>



<h3 id="sb_229">What is Content Negotiation?</h3>



<h3 id="sb_230">JSON Serialization and Deserialization</h3>



<h3 id="sb_231">How does Jackson work with Spring?</h3>



<h3 id="sb_232">What is `@JsonIgnore`?</h3>



<h3 id="sb_233">What is `@JsonIgnoreProperties`?</h3>



<h3 id="sb_234">What is `@JsonManagedReference`?</h3>



<h3 id="sb_235">What is `@JsonBackReference`?</h3>



<h3 id="sb_236">How do you prevent infinite JSON recursion?</h3>



<h3 id="sb_237">Why should Entities normally not be exposed directly from REST APIs?</h3>



<h3 id="sb_238">Entity vs DTO</h3>



<h3 id="sb_239">Request DTO vs Response DTO</h3>



<h3 id="sb_240">DTO mapping approaches</h3>



## 6. Exception Handling and Validation



<h3 id="sb_241">How does Spring exception handling work?</h3>



<h3 id="sb_242">What is `@ExceptionHandler`?</h3>



<h3 id="sb_243">What is `@ControllerAdvice`?</h3>



<h3 id="sb_244">What is `@RestControllerAdvice`?</h3>



<h3 id="sb_245">Local vs Global Exception Handling</h3>



<h3 id="sb_246">How do you create Custom Exceptions?</h3>



<h3 id="sb_247">What is `ResponseStatusException`?</h3>



<h3 id="sb_248">How should a Global Error Response be designed?</h3>



<h3 id="sb_249">How should validation errors be handled?</h3>



<h3 id="sb_250">What is Bean Validation?</h3>



<h3 id="sb_251">What is `@Valid`?</h3>



<h3 id="sb_252">What is `@Validated`?</h3>



<h3 id="sb_253">`@Valid` vs `@Validated`</h3>



<h3 id="sb_254">What is `@NotNull`?</h3>



<h3 id="sb_255">What is `@NotEmpty`?</h3>



<h3 id="sb_256">What is `@NotBlank`?</h3>



<h3 id="sb_257">What is `@Size`?</h3>



<h3 id="sb_258">What are `@Min` and `@Max`?</h3>



<h3 id="sb_259">What is `@Pattern`?</h3>



<h3 id="sb_260">What is `@Email`?</h3>



<h3 id="sb_261">How does nested DTO validation work?</h3>



<h3 id="sb_262">How does custom validation work?</h3>



<h3 id="sb_263">How do you create a custom validation annotation?</h3>



<h3 id="sb_264">What is `ConstraintValidator`?</h3>



<h3 id="sb_265">How do you implement cross-field validation?</h3>



## 7. Filters, Interceptors and Events



<h3 id="sb_266">What is a Servlet Filter?</h3>



<h3 id="sb_267">What is `HandlerInterceptor`?</h3>



<h3 id="sb_268">Filter vs Interceptor</h3>



<h3 id="sb_269">Where does a Filter execute?</h3>



<h3 id="sb_270">Where does an Interceptor execute?</h3>



<h3 id="sb_271">What is `preHandle()`?</h3>



<h3 id="sb_272">What is `postHandle()`?</h3>



<h3 id="sb_273">What is `afterCompletion()`?</h3>



<h3 id="sb_274">When should you use a Filter?</h3>



<h3 id="sb_275">When should you use an Interceptor?</h3>



<h3 id="sb_276">Filter vs Interceptor vs AOP</h3>



<h3 id="sb_277">How would you implement Request Logging?</h3>



<h3 id="sb_278">How would you implement Correlation IDs?</h3>



<h3 id="sb_279">What is `OncePerRequestFilter`?</h3>



<h3 id="sb_280">What are Spring Events?</h3>



<h3 id="sb_281">What is `ApplicationEventPublisher`?</h3>



<h3 id="sb_282">What is `@EventListener`?</h3>



<h3 id="sb_283">What is `@TransactionalEventListener`?</h3>



<h3 id="sb_284">Synchronous vs asynchronous event handling</h3>



## 8. Spring Data JPA and Hibernate



<h3 id="sb_285">What is ORM?</h3>



<h3 id="sb_286">JDBC vs JPA vs Hibernate</h3>



<h3 id="sb_287">JPA vs Hibernate</h3>



<h3 id="sb_288">What is an Entity?</h3>



<h3 id="sb_289">What are Entity class requirements?</h3>



<h3 id="sb_290">What is `@Entity`?</h3>



<h3 id="sb_291">What is `@Table`?</h3>



<h3 id="sb_292">What is `@Id`?</h3>



<h3 id="sb_293">What is `@GeneratedValue`?</h3>



<h3 id="sb_294">What are ID generation strategies?</h3>



<h3 id="sb_295">What is Persistence Context?</h3>



<h3 id="sb_296">Explain the Entity Lifecycle.</h3>



<h3 id="sb_297">What is Transient State?</h3>



<h3 id="sb_298">What is Managed/Persistent State?</h3>



<h3 id="sb_299">What is Detached State?</h3>



<h3 id="sb_300">What is Removed State?</h3>



<h3 id="sb_301">`persist()` vs `merge()`</h3>



<h3 id="sb_302">What is Dirty Checking?</h3>



<h3 id="sb_303">How does Hibernate Dirty Checking work?</h3>



<h3 id="sb_304">What is `EntityManager`?</h3>



<h3 id="sb_305">What is First-Level Cache?</h3>



<h3 id="sb_306">Why is First-Level Cache enabled by default?</h3>



<h3 id="sb_307">What is Second-Level Cache?</h3>



<h3 id="sb_308">First-Level vs Second-Level Cache</h3>



<h3 id="sb_309">What is Query Cache?</h3>



<h3 id="sb_310">What is Lazy Loading?</h3>



<h3 id="sb_311">What is Eager Loading?</h3>



<h3 id="sb_312">LAZY vs EAGER</h3>



<h3 id="sb_313">Default fetch type of `@OneToMany`</h3>



<h3 id="sb_314">Default fetch type of `@ManyToOne`</h3>



<h3 id="sb_315">Default fetch type of `@OneToOne`</h3>



<h3 id="sb_316">Default fetch type of `@ManyToMany`</h3>



<h3 id="sb_317">What is `LazyInitializationException`?</h3>



<h3 id="sb_318">Why does `LazyInitializationException` occur?</h3>



<h3 id="sb_319">How do you solve `LazyInitializationException` correctly?</h3>



<h3 id="sb_320">What is Open Session in View?</h3>



<h3 id="sb_321">Advantages and disadvantages of Open Session in View</h3>



<h3 id="sb_322">What is the N+1 problem?</h3>



<h3 id="sb_323">How do you identify N+1 queries?</h3>



<h3 id="sb_324">How do you resolve N+1 queries?</h3>



<h3 id="sb_325">What is Fetch Join?</h3>



<h3 id="sb_326">What is `@EntityGraph`?</h3>



<h3 id="sb_327">What is Batch Fetching?</h3>



<h3 id="sb_328">What is Cascade?</h3>



<h3 id="sb_329">`CascadeType.PERSIST`</h3>



<h3 id="sb_330">`CascadeType.MERGE`</h3>



<h3 id="sb_331">`CascadeType.REMOVE`</h3>



<h3 id="sb_332">`CascadeType.REFRESH`</h3>



<h3 id="sb_333">`CascadeType.DETACH`</h3>



<h3 id="sb_334">`CascadeType.ALL`</h3>



<h3 id="sb_335">What is `orphanRemoval`?</h3>



<h3 id="sb_336">`CascadeType.REMOVE` vs `orphanRemoval`</h3>



<h3 id="sb_337">One-to-One mapping</h3>



<h3 id="sb_338">One-to-Many mapping</h3>



<h3 id="sb_339">Many-to-One mapping</h3>



<h3 id="sb_340">Many-to-Many mapping</h3>



<h3 id="sb_341">Owning Side vs Inverse Side</h3>



<h3 id="sb_342">What is `mappedBy`?</h3>



<h3 id="sb_343">What is `@JoinColumn`?</h3>



<h3 id="sb_344">What is `@JoinTable`?</h3>



<h3 id="sb_345">Bidirectional vs Unidirectional mapping</h3>



<h3 id="sb_346">How do you keep both sides of a bidirectional relationship synchronized?</h3>



<h3 id="sb_347">What problems can happen if both sides are not synchronized?</h3>



<h3 id="sb_348">What is JPQL?</h3>



<h3 id="sb_349">JPQL vs SQL</h3>



<h3 id="sb_350">What is a Native Query?</h3>



<h3 id="sb_351">JPQL vs Native Query</h3>



<h3 id="sb_352">What are Named Queries?</h3>



<h3 id="sb_353">What are Spring Data Derived Query Methods?</h3>



<h3 id="sb_354">How does `findByName` work?</h3>



<h3 id="sb_355">How does `existsByEmail` work?</h3>



<h3 id="sb_356">What does `IgnoreCase` mean in a derived query?</h3>



<h3 id="sb_357">What does `Containing` mean?</h3>



<h3 id="sb_358">How are `And` and `Or` used in derived queries?</h3>



<h3 id="sb_359">How are `GreaterThan` and `LessThan` used?</h3>



<h3 id="sb_360">What is `@Query`?</h3>



<h3 id="sb_361">What are JPA Specifications?</h3>



<h3 id="sb_362">When should you use Specifications?</h3>



<h3 id="sb_363">How do you implement Dynamic Querying?</h3>



<h3 id="sb_364">What is `Pageable`?</h3>



<h3 id="sb_365">What is `Page`?</h3>



<h3 id="sb_366">What is `Slice`?</h3>



<h3 id="sb_367">Page vs Slice</h3>



<h3 id="sb_368">Pagination and Sorting</h3>



<h3 id="sb_369">What is Optimistic Locking?</h3>



<h3 id="sb_370">What is Pessimistic Locking?</h3>



<h3 id="sb_371">What is `@Version`?</h3>



<h3 id="sb_372">Optimistic vs Pessimistic Locking</h3>



## 9. Transaction Management



<h3 id="sb_373">What is a Transaction?</h3>



<h3 id="sb_374">What is `@Transactional`?</h3>



<h3 id="sb_375">How does `@Transactional` work internally?</h3>



<h3 id="sb_376">How does Spring use AOP for transactions?</h3>



<h3 id="sb_377">What is `PlatformTransactionManager`?</h3>



<h3 id="sb_378">When is a transaction started?</h3>



<h3 id="sb_379">When is it committed?</h3>



<h3 id="sb_380">When is it rolled back?</h3>



<h3 id="sb_381">Runtime Exception vs Checked Exception rollback behavior</h3>



<h3 id="sb_382">What is `rollbackFor`?</h3>



<h3 id="sb_383">What is `noRollbackFor`?</h3>



<h3 id="sb_384">Can `@Transactional` be placed on a class?</h3>



<h3 id="sb_385">Class-level vs method-level `@Transactional`</h3>



<h3 id="sb_386">Why does `@Transactional` not work as expected on private methods in proxy-based Spring AOP?</h3>



<h3 id="sb_387">What is the transactional self-invocation problem?</h3>



<h3 id="sb_388">What happens when one transactional method calls another?</h3>



<h3 id="sb_389">What is `readOnly = true`?</h3>



<h3 id="sb_390">What is transaction timeout?</h3>



<h3 id="sb_391">Propagation `REQUIRED`</h3>



<h3 id="sb_392">Propagation `REQUIRES_NEW`</h3>



<h3 id="sb_393">Propagation `SUPPORTS`</h3>



<h3 id="sb_394">Propagation `NOT_SUPPORTED`</h3>



<h3 id="sb_395">Propagation `MANDATORY`</h3>



<h3 id="sb_396">Propagation `NEVER`</h3>



<h3 id="sb_397">Propagation `NESTED`</h3>



<h3 id="sb_398">`REQUIRED` vs `REQUIRES_NEW`</h3>



<h3 id="sb_399">`REQUIRES_NEW` vs `NESTED`</h3>



<h3 id="sb_400">What are Transaction Isolation Levels?</h3>



<h3 id="sb_401">`READ_UNCOMMITTED`</h3>



<h3 id="sb_402">`READ_COMMITTED`</h3>



<h3 id="sb_403">`REPEATABLE_READ`</h3>



<h3 id="sb_404">`SERIALIZABLE`</h3>



<h3 id="sb_405">What is Dirty Read?</h3>



<h3 id="sb_406">What is Non-Repeatable Read?</h3>



<h3 id="sb_407">What is Phantom Read?</h3>



<h3 id="sb_408">What is Lost Update?</h3>



<h3 id="sb_409">Database isolation vs Spring isolation</h3>



<h3 id="sb_410">What does `Isolation.DEFAULT` mean?</h3>



## 10. Spring Security



<h3 id="sb_411">What is Spring Security?</h3>



<h3 id="sb_412">Authentication vs Authorization</h3>



<h3 id="sb_413">How does Spring Security work?</h3>



<h3 id="sb_414">Explain the Security Filter Chain.</h3>



<h3 id="sb_415">What is `SecurityFilterChain`?</h3>



<h3 id="sb_416">What is `Authentication`?</h3>



<h3 id="sb_417">What is `AuthenticationManager`?</h3>



<h3 id="sb_418">What is `AuthenticationProvider`?</h3>



<h3 id="sb_419">What is `UserDetailsService`?</h3>



<h3 id="sb_420">What is `UserDetails`?</h3>



<h3 id="sb_421">What is `PasswordEncoder`?</h3>



<h3 id="sb_422">Why use BCrypt?</h3>



<h3 id="sb_423">Roles vs Authorities</h3>



<h3 id="sb_424">What is `SecurityContext`?</h3>



<h3 id="sb_425">What is `SecurityContextHolder`?</h3>



<h3 id="sb_426">Session-based authentication</h3>



<h3 id="sb_427">Token-based authentication</h3>



<h3 id="sb_428">What is JWT?</h3>



<h3 id="sb_429">Explain JWT Structure.</h3>



<h3 id="sb_430">JWT Header</h3>



<h3 id="sb_431">JWT Payload</h3>



<h3 id="sb_432">JWT Signature</h3>



<h3 id="sb_433">How is JWT generated?</h3>



<h3 id="sb_434">How is JWT validated?</h3>



<h3 id="sb_435">Access Token vs Refresh Token</h3>



<h3 id="sb_436">Where should tokens be stored?</h3>



<h3 id="sb_437">JWT expiration handling</h3>



<h3 id="sb_438">Explain JWT Filter flow.</h3>



<h3 id="sb_439">What is `OncePerRequestFilter` in Spring Security?</h3>



<h3 id="sb_440">`401` vs `403`</h3>



<h3 id="sb_441">What is CSRF?</h3>



<h3 id="sb_442">Why is CSRF often disabled for stateless APIs?</h3>



<h3 id="sb_443">What is CORS?</h3>



<h3 id="sb_444">CORS vs CSRF</h3>



<h3 id="sb_445">What is OAuth2?</h3>



<h3 id="sb_446">What are OAuth2 roles?</h3>



<h3 id="sb_447">What is Authorization Code Flow?</h3>



<h3 id="sb_448">OAuth2 vs JWT</h3>



<h3 id="sb_449">What is OpenID Connect?</h3>



## 11. Microservices



<h3 id="sb_450">Monolith vs Microservices</h3>



<h3 id="sb_451">Advantages of Microservices</h3>



<h3 id="sb_452">Disadvantages of Microservices</h3>



<h3 id="sb_453">When should you NOT use Microservices?</h3>



<h3 id="sb_454">How do Microservices communicate?</h3>



<h3 id="sb_455">Synchronous vs Asynchronous communication</h3>



<h3 id="sb_456">REST communication between services</h3>



<h3 id="sb_457">What is OpenFeign?</h3>



<h3 id="sb_458">Feign vs RestTemplate</h3>



<h3 id="sb_459">Feign vs WebClient</h3>



<h3 id="sb_460">What is Service Discovery?</h3>



<h3 id="sb_461">What is Eureka Server?</h3>



<h3 id="sb_462">What is Eureka Client?</h3>



<h3 id="sb_463">What is an API Gateway?</h3>



<h3 id="sb_464">What responsibilities should a Gateway have?</h3>



<h3 id="sb_465">Authentication at Gateway vs Service</h3>



<h3 id="sb_466">What is Load Balancing?</h3>



<h3 id="sb_467">Client-side vs Server-side Load Balancing</h3>



<h3 id="sb_468">What is Circuit Breaker?</h3>



<h3 id="sb_469">What problem does Circuit Breaker solve?</h3>



<h3 id="sb_470">What are Circuit Breaker states?</h3>



<h3 id="sb_471">CLOSED state</h3>



<h3 id="sb_472">OPEN state</h3>



<h3 id="sb_473">HALF_OPEN state</h3>



<h3 id="sb_474">What is Resilience4j?</h3>



<h3 id="sb_475">What is Retry Pattern?</h3>



<h3 id="sb_476">What is Timeout Pattern?</h3>



<h3 id="sb_477">What is Bulkhead Pattern?</h3>



<h3 id="sb_478">Circuit Breaker vs Retry</h3>



<h3 id="sb_479">What is Distributed Tracing?</h3>



<h3 id="sb_480">What is Correlation ID?</h3>



<h3 id="sb_481">What is centralized logging?</h3>



<h3 id="sb_482">What is eventual consistency?</h3>



<h3 id="sb_483">What is a Distributed Transaction?</h3>



<h3 id="sb_484">Why does normal `@Transactional` not work across microservices?</h3>



<h3 id="sb_485">What is Saga Pattern?</h3>



<h3 id="sb_486">What is Choreography-based Saga?</h3>



<h3 id="sb_487">What is Orchestration-based Saga?</h3>



<h3 id="sb_488">Choreography vs Orchestration</h3>



<h3 id="sb_489">What is Outbox Pattern?</h3>



<h3 id="sb_490">What is Idempotency in Microservices?</h3>



<h3 id="sb_491">What happens if the same message is consumed twice?</h3>



<h3 id="sb_492">How do you design retry-safe APIs?</h3>



## 12. Caching, Async and Scheduling



<h3 id="sb_493">What is Spring Cache?</h3>



<h3 id="sb_494">What is `@EnableCaching`?</h3>



<h3 id="sb_495">What is `@Cacheable`?</h3>



<h3 id="sb_496">What is `@CachePut`?</h3>



<h3 id="sb_497">What is `@CacheEvict`?</h3>



<h3 id="sb_498">`@Cacheable` vs `@CachePut`</h3>



<h3 id="sb_499">Local vs Distributed Cache</h3>



<h3 id="sb_500">What is Redis?</h3>



<h3 id="sb_501">When would you use Redis caching?</h3>



<h3 id="sb_502">What is Cache-Aside Pattern?</h3>



<h3 id="sb_503">What are cache invalidation problems?</h3>



<h3 id="sb_504">What is a cache stampede?</h3>



<h3 id="sb_505">What happens when cached data becomes stale?</h3>



<h3 id="sb_506">What is `@Async`?</h3>



<h3 id="sb_507">How does `@Async` work internally?</h3>



<h3 id="sb_508">Why can self-invocation break `@Async`?</h3>



<h3 id="sb_509">What is `CompletableFuture`?</h3>



<h3 id="sb_510">How do you configure a ThreadPool?</h3>



<h3 id="sb_511">What is `@Scheduled`?</h3>



<h3 id="sb_512">`fixedRate` vs `fixedDelay`</h3>



<h3 id="sb_513">What is a Cron expression?</h3>



## 13. Testing Spring Boot Applications



<h3 id="sb_514">Unit Test vs Integration Test</h3>



<h3 id="sb_515">What is JUnit 5?</h3>



<h3 id="sb_516">What is Mockito?</h3>



<h3 id="sb_517">What is `@Mock`?</h3>



<h3 id="sb_518">What is `@InjectMocks`?</h3>



<h3 id="sb_519">What is `@MockBean`?</h3>



<h3 id="sb_520">`@Mock` vs Spring-context mock replacement approaches</h3>



<h3 id="sb_521">What is `Mockito.when()`?</h3>



<h3 id="sb_522">What is `verify()`?</h3>



<h3 id="sb_523">What is `ArgumentCaptor`?</h3>



<h3 id="sb_524">How do you test Service classes?</h3>



<h3 id="sb_525">How do you test Controllers?</h3>



<h3 id="sb_526">What is MockMvc?</h3>



<h3 id="sb_527">What is `@WebMvcTest`?</h3>



<h3 id="sb_528">What is `@DataJpaTest`?</h3>



<h3 id="sb_529">What is `@SpringBootTest`?</h3>



<h3 id="sb_530">`@WebMvcTest` vs `@SpringBootTest`</h3>



<h3 id="sb_531">How do you test Repository queries?</h3>



<h3 id="sb_532">H2 vs real database testing</h3>



<h3 id="sb_533">What is Testcontainers?</h3>



<h3 id="sb_534">Why use Testcontainers for integration tests?</h3>



## 14. Production, Performance and Observability



<h3 id="sb_535">How do you monitor a Spring Boot application?</h3>



<h3 id="sb_536">What is Spring Boot Actuator?</h3>



<h3 id="sb_537">Liveness vs Readiness</h3>



<h3 id="sb_538">What is Micrometer?</h3>



<h3 id="sb_539">What are application metrics?</h3>



<h3 id="sb_540">How do you identify a slow API?</h3>



<h3 id="sb_541">How do you identify slow DB queries?</h3>



<h3 id="sb_542">What is Connection Pooling?</h3>



<h3 id="sb_543">What is HikariCP?</h3>



<h3 id="sb_544">What happens when the DB connection pool is exhausted?</h3>



<h3 id="sb_545">Connection timeout vs Query timeout</h3>



<h3 id="sb_546">How do you tune Hibernate queries?</h3>



<h3 id="sb_547">How do you identify N+1 in production?</h3>



<h3 id="sb_548">What is distributed tracing?</h3>



<h3 id="sb_549">How does Correlation ID help debugging?</h3>



<h3 id="sb_550">Logs vs Metrics vs Traces</h3>



<h3 id="sb_551">How do you handle application configuration securely?</h3>



<h3 id="sb_552">Why should credentials not be kept directly in `application.properties`?</h3>



<h3 id="sb_553">What is Graceful Shutdown?</h3>



<h3 id="sb_554">What are Health Checks?</h3>



<h3 id="sb_555">What happens when downstream services become slow?</h3>



<h3 id="sb_556">How do you prevent one slow dependency from exhausting application threads?</h3>



<h3 id="sb_557">How would you troubleshoot high CPU?</h3>



<h3 id="sb_558">How would you troubleshoot high memory usage?</h3>



<h3 id="sb_559">How would you troubleshoot DB connection exhaustion?</h3>



<h3 id="sb_560">How would you troubleshoot increasing response time?</h3>



## 15. Senior-Level Scenario-Based Interview Questions



### Scenario 1: Missing Bean



<h3 id="sb_561">Why can this happen?</h3>



<h3 id="sb_562">How would you investigate component scanning?</h3>



<h3 id="sb_563">Could a missing `@Service` or `@Bean` cause it?</h3>



<h3 id="sb_564">Could package structure cause it?</h3>



<h3 id="sb_565">How would you fix it?</h3>



### Scenario 2: Multiple Implementations



<h3 id="sb_566">Why can the application fail to start?</h3>



<h3 id="sb_567">What exception do you expect?</h3>



<h3 id="sb_568">Would you use `@Qualifier` or `@Primary`?</h3>



<h3 id="sb_569">What is the difference?</h3>



<h3 id="sb_570">Which approach is better when the implementation must be selected dynamically?</h3>



### Scenario 3: Circular Dependency



<h3 id="sb_571">What happens?</h3>



<h3 id="sb_572">Why is constructor-based circular dependency problematic?</h3>



<h3 id="sb_573">Can `@Lazy` change the behavior?</h3>



<h3 id="sb_574">Why is `@Lazy` often only a workaround?</h3>



<h3 id="sb_575">How would you redesign the services to remove the cycle?</h3>



### Scenario 4: Runtime Failure



<h3 id="sb_576">What happens to the transaction?</h3>



<h3 id="sb_577">Will the order be committed?</h3>



<h3 id="sb_578">Why?</h3>



<h3 id="sb_579">When could the result be different?</h3>



### Scenario 5: REQUIRES_NEW and Self Invocation



<h3 id="sb_580">Will `REQUIRES_NEW` necessarily create a new transaction?</h3>



<h3 id="sb_581">Explain Spring proxy-based transaction management.</h3>



<h3 id="sb_582">What is self-invocation?</h3>



<h3 id="sb_583">How would you redesign this code?</h3>



### Scenario 6: Checked Exception



<h3 id="sb_584">Why can this happen?</h3>



<h3 id="sb_585">What are Spring's default rollback rules?</h3>



<h3 id="sb_586">How can `rollbackFor` change the behavior?</h3>



### Scenario 7: Independent Audit Transaction



<h3 id="sb_587">Would `REQUIRED` or `REQUIRES_NEW` better match an independent audit transaction?</h3>



<h3 id="sb_588">What happens to the outer transaction when the inner transaction fails?</h3>



<h3 id="sb_589">What trade-offs come with `REQUIRES_NEW`?</h3>



<h3 id="sb_590">How could an event/outbox design change the solution?</h3>



### Scenario 8: N+1 Queries



<h3 id="sb_591">What happened?</h3>



<h3 id="sb_592">Why can LAZY relationships cause this access pattern?</h3>



<h3 id="sb_593">How would a fetch join help?</h3>



<h3 id="sb_594">When would you use `@EntityGraph`?</h3>



<h3 id="sb_595">What is batch fetching?</h3>



### Scenario 9: LazyInitializationException



<h3 id="sb_596">Why did it happen?</h3>



<h3 id="sb_597">What is the Persistence Context?</h3>



<h3 id="sb_598">What is the transaction boundary?</h3>



<h3 id="sb_599">Why is changing every relationship to EAGER usually a poor fix?</h3>



<h3 id="sb_600">How would DTO projection, fetch join, or EntityGraph help?</h3>



### Scenario 10: Owning Side vs Inverse Side



<h3 id="sb_601">Which side is the owning side?</h3>



<h3 id="sb_602">Why?</h3>



<h3 id="sb_603">Which side contains the foreign key?</h3>



<h3 id="sb_604">What does `mappedBy` mean?</h3>



<h3 id="sb_605">What can happen if you only call `department.getEmployees().add(employee)` without `employee.setDepartment(department)`?</h3>



<h3 id="sb_606">Why are helper methods useful for bidirectional relationships?</h3>



### Scenario 11: Concurrent Update



<h3 id="sb_607">What kind of lost-update problem can occur?</h3>



<h3 id="sb_608">How does `@Version` help?</h3>



<h3 id="sb_609">What is optimistic locking?</h3>



<h3 id="sb_610">When would pessimistic locking be more suitable?</h3>



### Scenario 12: Duplicate User



<h3 id="sb_611">Would you return `400`, `404`, `409`, or `500`?</h3>



<h3 id="sb_612">Why is `409 Conflict` often appropriate?</h3>



<h3 id="sb_613">Where should the duplicate-email business rule be checked?</h3>



<h3 id="sb_614">How should a database unique constraint complement application validation?</h3>



### Scenario 13: Infinite JSON Recursion



<h3 id="sb_615">Why did this happen?</h3>



<h3 id="sb_616">How do bidirectional relationships affect Jackson serialization?</h3>



<h3 id="sb_617">What does `@JsonIgnore` do?</h3>



<h3 id="sb_618">What does `@JsonIgnoreProperties` do?</h3>



<h3 id="sb_619">Why can DTOs provide a cleaner API contract?</h3>



### Scenario 14: Request Validation



<h3 id="sb_620">Which validation annotations would you use?</h3>



<h3 id="sb_621">Where should `@Valid` be placed?</h3>



<h3 id="sb_622">What exception is produced for invalid request-body validation?</h3>



<h3 id="sb_623">How would `@RestControllerAdvice` handle it?</h3>



<h3 id="sb_624">How would you return field-specific validation errors?</h3>



### Scenario 15: API Suddenly Becomes Slow



<h3 id="sb_625">Which metric would you inspect first?</h3>



<h3 id="sb_626">How would a trace identify a slow downstream call?</h3>



<h3 id="sb_627">How would you detect connection-pool waiting?</h3>



<h3 id="sb_628">How could a newly introduced N+1 query explain the issue?</h3>



### Scenario 16: Slow Downstream Service



<h3 id="sb_629">Why can one slow downstream service affect unrelated requests?</h3>



<h3 id="sb_630">How can blocked request threads cause resource exhaustion?</h3>



<h3 id="sb_631">Where would you configure connect/read/response timeouts?</h3>



<h3 id="sb_632">When would you use Circuit Breaker?</h3>



<h3 id="sb_633">What does Bulkhead isolation solve?</h3>



<h3 id="sb_634">When is Retry dangerous?</h3>



### Scenario 17: Distributed Order Transaction



<h3 id="sb_635">Why can one normal local `@Transactional` method not atomically cover independent service databases?</h3>



<h3 id="sb_636">What is Saga?</h3>



<h3 id="sb_637">What is a compensating transaction?</h3>



<h3 id="sb_638">Choreography vs Orchestration?</h3>



<h3 id="sb_639">What does eventual consistency mean here?</h3>



<h3 id="sb_640">How could an Outbox Pattern improve event reliability?</h3>



### Scenario 18: Duplicate Event



<h3 id="sb_641">Why should consumers be designed as idempotent?</h3>



<h3 id="sb_642">How could an event ID or processed-message table help?</h3>



<h3 id="sb_643">How could a database unique constraint help?</h3>



<h3 id="sb_644">What happens during retry after a partially completed operation?</h3>



### Scenario 19: Payment Service Down



<h3 id="sb_645">Should you retry?</h3>



<h3 id="sb_646">Should you fail fast?</h3>



<h3 id="sb_647">Should you use Circuit Breaker?</h3>



<h3 id="sb_648">Could the request be queued?</h3>



<h3 id="sb_649">Why must the business requirement determine the strategy?</h3>



<h3 id="sb_650">Which failures are safe to retry?</h3>



### Scenario 20: JWT Expiration



<h3 id="sb_651">How should the API respond?</h3>



<h3 id="sb_652">What is a refresh token?</h3>



<h3 id="sb_653">How is a new access token issued?</h3>



<h3 id="sb_654">When should reauthentication be required?</h3>



<h3 id="sb_655">How should refresh-token revocation/rotation be handled?</h3>



### Scenario 21: JWT Tampering



<h3 id="sb_656">Why should the server not trust the payload without verifying the token?</h3>



<h3 id="sb_657">How does the signature detect modification?</h3>



<h3 id="sb_658">What should happen if signature verification fails?</h3>



<h3 id="sb_659">Why should authorization still be enforced server-side?</h3>



### Scenario 22: Authentication vs Authorization



<h3 id="sb_660">Is this authentication failure or authorization failure?</h3>



<h3 id="sb_661">Should the response normally be `401` or `403`?</h3>



<h3 id="sb_662">Where would authorization rules be configured?</h3>



<h3 id="sb_663">When would method security such as `@PreAuthorize` be useful?</h3>



### Scenario 23: Database Connection Pool Exhaustion



<h3 id="sb_664">Connection leak</h3>



<h3 id="sb_665">Slow queries</h3>



<h3 id="sb_666">Long transactions</h3>



<h3 id="sb_667">Database overload</h3>



<h3 id="sb_668">Incorrect pool sizing</h3>



<h3 id="sb_669">Traffic spike</h3>



<h3 id="sb_670">How would you identify the real cause?</h3>



<h3 id="sb_671">Which HikariCP metrics would you inspect?</h3>



<h3 id="sb_672">Why can increasing the pool size blindly make things worse?</h3>



<h3 id="sb_673">How can long-running transactions exhaust connections?</h3>



### Scenario 24: OutOfMemoryError



<h3 id="sb_674">How would you investigate heap usage?</h3>



<h3 id="sb_675">What does GC behavior tell you?</h3>



<h3 id="sb_676">When would you capture a heap dump?</h3>



<h3 id="sb_677">What are retained objects?</h3>



<h3 id="sb_678">How can caches cause memory problems?</h3>



<h3 id="sb_679">How can static collections cause leaks?</h3>



<h3 id="sb_680">How can `ThreadLocal` usage cause leaks?</h3>



<h3 id="sb_681">Which resources must be closed correctly?</h3>



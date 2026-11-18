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



# Question Headings



## 1. Core Spring Fundamentals



<h3 id="sb_001">What is Spring Framework?</h3>
Spring Framework is a lightweight Java-based framework used to build enterprise applications. Its core principle is Inversion of Control(Ioc), where the Spring container creates and manages application objects called beans and injects their dependencies instead of the application creating objects manually. It also provides support for AOP, transaction management, web applications, security integration, data access, which help us build loosely coupled and maintainable applications.



<h3 id="sb_002">Why was Spring introduced?</h3>
Spring was introduced to overcome the complexity of traditional Java enterprise development, especially the heavy infrastructure and tight coupling common in older J2EE applications.It provides IoC and Dependency Injection so that object creation and dependency management are handled by the Spring container. This makes applications more loosely coupled, testable, maintainable, and easier to extend.

Mainly to provide:

Loose coupling through Dependency Injection
IoC for object creation and lifecycle management
Easier unit testing
Less infrastructure/boilerplate code
Declarative transaction management
AOP for cross-cutting concerns
Easier database and web application development
Better modularity and maintainability

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

# 🧠 Quick Revision Table

| Problem | Spring Solution |
|---|---|
| 🔗 Tight coupling | Dependency Injection |
| 🏗️ Manual object creation | IoC Container |
| 🧪 Difficult testing | Dependency Injection |
| 🎯 Cross-cutting concerns | Spring AOP |
| 🔄 Transaction complexity | `@Transactional` |
| 🗄️ Database boilerplate | Spring Data |
| ⚙️ Object lifecycle | Spring Container |

---


### 🎤 Interview-Ready Answer

> **Spring solves several common problems in enterprise Java applications, especially tight coupling, manual object creation, dependency management, transaction management, cross-cutting concerns, and repetitive data-access code.**
>
> **Using IoC and Dependency Injection, Spring manages application objects and their dependencies, making the application loosely coupled, testable, and maintainable. It also provides AOP, declarative transaction management, MVC, and data-access abstractions, which reduce infrastructure boilerplate.**

---

<h3 id="sb_004">What is IoC (Inversion of Control)?</h3>

**IoC stands for Inversion of Control.**

IoC is a design principle where the **control of creating objects, configuring them, managing their lifecycle, and providing their dependencies is transferred from the application code to the Spring Container**.

In simple terms:

> 💡 Instead of our application creating dependent objects using `new`, we let Spring create and manage those objects and provide them wherever they are required.

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

Here:

```text
OrderService
     |
     | creates using new
     ↓
PaymentService
```

`OrderService` itself controls:

```text
Which object should be created?
How should it be created?
When should it be created?
```

The control is inside our application code.

### Problem

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

# ✅ With Spring IoC

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

There is no:

```java
new UPIPaymentService();
```

inside `OrderService`.

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

# 🔄 Why is it called "Inversion of Control"?

This is the most important part.

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

# 🔥 Inversion of Control

---

# 🏗️ What does the Spring IoC Container manage?

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

---

# 🧩 IoC Container in Spring

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

### ApplicationContext

`ApplicationContext` builds on `BeanFactory` functionality and is what we normally work with in modern Spring applications.

Later we'll cover:

```text
BeanFactory
      vs
ApplicationContext
```

in depth.

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

# 📊 IoC vs DI Quick Comparison

| IoC | Dependency Injection |
|---|---|
| Design principle | Technique/pattern used to implement IoC |
| Broader concept | More specific concept |
| Transfers control to container/framework | Supplies dependencies from outside |
| Includes object/lifecycle management concerns | Focuses on dependency provisioning |

---

# 🛒 Real-Time Example

Consider an e-commerce application.

```text
OrderController
       ↓
OrderService
       ↓
PaymentService
       ↓
PaymentGateway
```

Without IoC, you might manually create everything:

```java
PaymentGateway gateway = new RazorpayGateway();

PaymentService paymentService =
        new PaymentService(gateway);

OrderService orderService =
        new OrderService(paymentService);

OrderController controller =
        new OrderController(orderService);
```

Imagine doing this manually for:

```text
50 Controllers
100 Services
80 Repositories
20 External Clients
```

It becomes difficult to manage.

With Spring:

```text
Spring Container
       |
       +------> OrderController
       |
       +------> OrderService
       |
       +------> PaymentService
       |
       +------> PaymentGateway
```

Spring resolves the dependency graph and wires the beans together.

---

# 🎯 Important Point

IoC does **not** simply mean:

> "We don't use `new` anywhere."

You can absolutely use `new` in a Spring application.

The important point is:

> **For Spring-managed components, object creation, dependency wiring, configuration, and lifecycle are controlled by the Spring container instead of being manually managed throughout the application.**

---

# 🧠 Easy Way to Remember

```text
Without Spring

Developer
   ↓
creates objects
   ↓
connects dependencies
   ↓
manages lifecycle
```

```text
With Spring IoC

Developer
   ↓
defines components/configuration
   ↓
Spring Container
   ↓
creates beans
   ↓
injects dependencies
   ↓
manages lifecycle
```

That's the **inversion**.

---

> 💡 **Key Point**
>
> IoC means that responsibility for creating and managing Spring beans is moved from application code to the Spring IoC Container.

---

# 🎤 Interview-Ready Answer

> **IoC, or Inversion of Control, is a design principle where the responsibility for creating objects, managing their lifecycle, and resolving their dependencies is transferred from application code to a container or framework.**
>
> **In Spring, the IoC container creates and manages objects called beans and injects their required dependencies. Dependency Injection is one of the main techniques Spring uses to implement IoC. This reduces coupling and makes the application easier to test, maintain, and extend.**

---

# ⚡ Short Interview Answer

> **IoC means transferring the control of object creation and dependency management from application code to the Spring Container. Spring creates and manages beans and injects their dependencies, while Dependency Injection is the primary mechanism used to achieve IoC.**

---

# 🎯 5+ Years Interview Follow-Up Questions

Be ready for these:

1. What is the difference between IoC and Dependency Injection?
2. What is the Spring IoC Container?
3. `BeanFactory` vs `ApplicationContext`?
4. How does Spring know which objects to manage?
5. What exactly is a Spring Bean?
6. How does Spring create a Bean internally?
7. How does Spring resolve dependencies?
8. What happens when two Beans implement the same interface?
9. How does `@Autowired` work internally?
10. Can we achieve IoC without Spring?
11. Can we use `new` inside a Spring application?
12. How does IoC improve unit testing?

---

# 🔥 Important Connection

```text
Spring
   ↓
IoC
   ↓
Spring Container
   ↓
Creates & Manages Beans
   ↓
Dependency Injection
   ↓
Loose Coupling
   ↓
Easier Testing & Maintenance
```

---


<h3 id="sb_005">What is Dependency Injection?</h3>



<h3 id="sb_006">IoC vs Dependency Injection</h3>



<h3 id="sb_007">What are the different types of Dependency Injection?</h3>



<h3 id="sb_008">Constructor Injection</h3>



<h3 id="sb_009">Setter Injection</h3>



<h3 id="sb_010">Field Injection</h3>



<h3 id="sb_011">Constructor vs Setter vs Field Injection</h3>



<h3 id="sb_012">Why is Constructor Injection recommended?</h3>



<h3 id="sb_013">What is a Spring Bean?</h3>



<h3 id="sb_014">Java Object vs Spring Bean</h3>



<h3 id="sb_015">What is Spring Container?</h3>



<h3 id="sb_016">What is ApplicationContext?</h3>



<h3 id="sb_017">What is BeanFactory?</h3>



<h3 id="sb_018">ApplicationContext vs BeanFactory</h3>



<h3 id="sb_019">What is Bean Scope?</h3>



<h3 id="sb_020">Singleton Scope</h3>



<h3 id="sb_021">Prototype Scope</h3>



<h3 id="sb_022">Request Scope</h3>



<h3 id="sb_023">Session Scope</h3>



<h3 id="sb_024">Application Scope</h3>



<h3 id="sb_025">WebSocket Scope</h3>



<h3 id="sb_026">Spring Singleton vs Java Singleton</h3>



<h3 id="sb_027">Can a Singleton Bean inject a Prototype Bean?</h3>



<h3 id="sb_028">What problem occurs when Prototype Bean is injected into Singleton?</h3>



<h3 id="sb_029">What is `@Lookup`?</h3>



<h3 id="sb_030">What is Bean Lifecycle?</h3>



<h3 id="sb_031">Explain the complete Spring Bean Lifecycle.</h3>



<h3 id="sb_032">What is `@PostConstruct`?</h3>



<h3 id="sb_033">What is `@PreDestroy`?</h3>



<h3 id="sb_034">What is `InitializingBean`?</h3>



<h3 id="sb_035">What is `DisposableBean`?</h3>



<h3 id="sb_036">`@PostConstruct` vs `InitializingBean`</h3>



<h3 id="sb_037">What are `initMethod` and `destroyMethod`?</h3>



<h3 id="sb_038">What is `@Component`?</h3>



<h3 id="sb_039">What is `@Service`?</h3>



<h3 id="sb_040">What is `@Repository`?</h3>



<h3 id="sb_041">What is `@Controller`?</h3>



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



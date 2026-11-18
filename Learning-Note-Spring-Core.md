# Spring & Spring Boot Interview Preparation

<br>

## 1. Core Spring Fundamentals

<br>

1. [What is Spring Framework?](#sb_01)<br>
2. [Why was Spring introduced?](#sb_02)<br>
3. [What problems does Spring solve?](#sb_03)<br>
4. [What is IoC (Inversion of Control)?](#sb_04)<br>
5. [What is Dependency Injection?](#sb_05)<br>
6. [IoC vs Dependency Injection](#sb_06)<br>
7. [What are the different types of Dependency Injection?](#sb_07)<br>
8. [What is Constructor Injection?](#sb_08)<br>
9. [What is Setter Injection?](#sb_09)<br>
10. [What is Field Injection?](#sb_10)<br>
11. [Constructor vs Setter vs Field Injection](#sb_11)<br>
12. [Why is Constructor Injection recommended?](#sb_12)<br>
13. [What is a Spring Bean?](#sb_13)<br>
14. [Java Object vs Spring Bean](#sb_14)<br>
15. [What is Spring Container?](#sb_15)<br>
16. [What is ApplicationContext?](#sb_16)<br>
17. [What is BeanFactory?](#sb_17)<br>
18. [ApplicationContext vs BeanFactory](#sb_18)<br>
19. [What is Bean Scope?](#sb_19)<br>
20. [What is Singleton Scope?](#sb_20)<br>
21. [What is Prototype Scope?](#sb_21)<br>
22. [What is Request Scope?](#sb_22)<br>
23. [What is Session Scope?](#sb_23)<br>
24. [What is Application Scope?](#sb_24)<br>
25. [What is WebSocket Scope?](#sb_25)<br>
26. [Spring Singleton vs Java Singleton](#sb_26)<br>
27. [Can a Singleton Bean inject a Prototype Bean?](#sb_27)<br>
28. [What problem occurs when Prototype Bean is injected into Singleton?](#sb_28)<br>
29. [What is @Lookup?](#sb_29)<br>
30. [What is Bean Lifecycle?](#sb_30)<br>
31. [Explain the complete Spring Bean Lifecycle.](#sb_31)<br>
32. [What is @PostConstruct?](#sb_32)<br>
33. [What is @PreDestroy?](#sb_33)<br>
34. [What is InitializingBean?](#sb_34)<br>
35. [What is DisposableBean?](#sb_35)<br>
36. [@PostConstruct vs InitializingBean](#sb_36)<br>
37. [What are initMethod and destroyMethod?](#sb_37)<br>
38. [What is @Component?](#sb_38)<br>
39. [What is @Service?](#sb_39)<br>
40. [What is @Repository?](#sb_40)<br>
41. [What is @Controller?](#sb_41)<br>
42. [What is @RestController?](#sb_42)<br>
43. [@Controller vs @RestController](#sb_43)<br>
44. [@Component vs @Bean](#sb_44)<br>
45. [Why do we have @Service if @Component can do the same thing?](#sb_45)<br>
46. [What special behavior does @Repository provide?](#sb_46)<br>
47. [What is Component Scanning?](#sb_47)<br>
48. [How does @ComponentScan work?](#sb_48)<br>
49. [What happens if a component is outside the base package?](#sb_49)<br>
50. [What are Spring configuration approaches?](#sb_50)<br>
51. [What is XML Configuration?](#sb_51)<br>
52. [What is Java Configuration?](#sb_52)<br>
53. [What is Annotation Configuration?](#sb_53)<br>
54. [What is @Configuration?](#sb_54)<br>
55. [What is @Bean?](#sb_55)<br>
56. [What is @Import?](#sb_56)<br>
57. [What is @Value?](#sb_57)<br>
58. [What is Environment?](#sb_58)<br>
59. [What is @PropertySource?](#sb_59)<br>

<br><br>

<br>

## Phase 2: Spring Internals

60. [How does Spring Container start?](#sb_60)
61. [How does Spring discover Beans?](#sb_61)
62. [How does Spring instantiate Beans?](#sb_62)
63. [How are dependencies resolved?](#sb_63)
64. [How does Spring maintain Beans internally?](#sb_64)
65. [What is BeanDefinition?](#sb_65)
66. [What is BeanDefinitionRegistry?](#sb_66)
67. [What is BeanFactoryPostProcessor?](#sb_67)
68. [What is BeanPostProcessor?](#sb_68)
69. [BeanFactoryPostProcessor vs BeanPostProcessor](#sb_69)
70. [When does BeanPostProcessor execute?](#sb_70)
71. [How does @Autowired work internally?](#sb_71)
72. [What is AutowiredAnnotationBeanPostProcessor?](#sb_72)
73. [How does Spring resolve dependency by type?](#sb_73)
74. [What happens if multiple Beans of the same type exist?](#sb_74)
75. [What is NoUniqueBeanDefinitionException?](#sb_75)
76. [What is NoSuchBeanDefinitionException?](#sb_76)
77. [What is @Qualifier?](#sb_77)
78. [What is @Primary?](#sb_78)
79. [@Qualifier vs @Primary](#sb_79)
80. [Can @Autowired be used on constructors?](#sb_80)
81. [Is @Autowired required for a single constructor?](#sb_81)
82. [What is Circular Dependency?](#sb_82)
83. [Why can constructor circular dependency fail?](#sb_83)
84. [How does Spring handle setter/field circular dependency?](#sb_84)
85. [What are Spring's three-level singleton caches?](#sb_85)
86. [What is singletonObjects?](#sb_86)
87. [What is earlySingletonObjects?](#sb_87)
88. [What is singletonFactories?](#sb_88)
89. [Why are circular references discouraged?](#sb_89)
90. [How do you redesign code to remove circular dependencies?](#sb_90)
91. [What is Lazy Initialization?](#sb_91)
92. [What is @Lazy?](#sb_92)
93. [Where can @Lazy be used?](#sb_93)
94. [Lazy vs Eager initialization](#sb_94)
95. [What is Spring Expression Language (SpEL)?](#sb_95)
96. [What can SpEL be used for?](#sb_96)
97. [What are proxies in Spring?](#sb_97)
98. [JDK Dynamic Proxy vs CGLIB Proxy](#sb_98)
99. [When does Spring use a JDK proxy?](#sb_99)
100. [When does Spring use a CGLIB proxy?](#sb_100)
101. [Why are Spring proxies important?](#sb_101)
102. [What is self-invocation?](#sb_102)
103. [Why can self-invocation bypass Spring proxy behavior?](#sb_103)
104. [Which Spring features depend heavily on proxies?](#sb_104)

<br><br>

<br>

<br>

## Phase 3: Spring AOP

<br>

105. [What is AOP?](#sb_105)
106. [Why was AOP introduced?](#sb_106)
107. [What are Cross-Cutting Concerns?](#sb_107)
108. [What is an Aspect?](#sb_108)
109. [What is Advice?](#sb_109)
110. [What is Join Point?](#sb_110)
111. [What is Pointcut?](#sb_111)
112. [What is Target Object?](#sb_112)
113. [What is Weaving?](#sb_113)
114. [Compile-time vs Load-time vs Runtime weaving](#sb_114)
115. [How does Spring AOP work internally?](#sb_115)
116. [Spring AOP vs AspectJ](#sb_116)
117. [What is @Aspect?](#sb_117)
118. [What is @Before?](#sb_118)
119. [What is @After?](#sb_119)
120. [What is @AfterReturning?](#sb_120)
121. [What is @AfterThrowing?](#sb_121)
122. [What is @Around?](#sb_122)
123. [Which Advice is most powerful?](#sb_123)
124. [What is ProceedingJoinPoint?](#sb_124)
125. [What happens if proceed() is not called?](#sb_125)
126. [How do you write a Pointcut expression?](#sb_126)
127. [Explain the execution() Pointcut expression.](#sb_127)
128. [Can multiple Pointcuts be combined?](#sb_128)
129. [How do you control Aspect execution order?](#sb_129)
130. [What is @Order?](#sb_130)
131. [How does AOP use proxies?](#sb_131)
132. [Why does AOP not work as expected with self-invocation?](#sb_132)
133. [Can private methods be intercepted?](#sb_133)
134. [Can final methods cause proxy limitations?](#sb_134)
135. [Logging using AOP](#sb_135)
136. [Performance monitoring using AOP](#sb_136)
137. [Auditing using AOP](#sb_137)
138. [Security using AOP](#sb_138)
139. [Transaction management using AOP](#sb_139)

<br>

<br>

## Phase 4: Spring Boot Fundamentals and Internals

<br>

140. [Why Spring Boot?](#sb_140)
141. [Spring vs Spring MVC vs Spring Boot](#sb_141)
142. [Advantages of Spring Boot](#sb_142)
143. [What is `@SpringBootApplication`?](#sb_143)
144. [What annotations are inside `@SpringBootApplication`?](#sb_144)
145. [What is `@SpringBootConfiguration`?](#sb_145)
146. [What is `@EnableAutoConfiguration`?](#sb_146)
147. [What is `@ComponentScan`?](#sb_147)
148. [What happens when `SpringApplication.run()` executes?](#sb_148)
149. [Explain Spring Boot application startup flow.](#sb_149)
150. [How is `ApplicationContext` created?](#sb_150)
151. [How does component scanning start?](#sb_151)
152. [How does Auto Configuration work?](#sb_152)
153. [What is conditional configuration?](#sb_153)
154. [What is `@Conditional`?](#sb_154)
155. [What is `@ConditionalOnClass`?](#sb_155)
156. [What is `@ConditionalOnMissingBean`?](#sb_156)
157. [What is `@ConditionalOnProperty`?](#sb_157)
158. [What is `@ConditionalOnBean`?](#sb_158)
159. [How does Boot decide which Auto Configurations to load?](#sb_159)
160. [How can Auto Configuration be excluded?](#sb_160)
161. [What are Starter Dependencies?](#sb_161)
162. [How do starters simplify dependency management?](#sb_162)
163. [What is Spring Boot's parent POM?](#sb_163)
164. [What is dependency management?](#sb_164)
165. [What is an Embedded Server?](#sb_165)
166. [How does embedded Tomcat start?](#sb_166)
167. [Tomcat vs Servlet Container](#sb_167)
168. [Tomcat vs Application Server](#sb_168)
169. [How do you replace Tomcat with Jetty or Undertow?](#sb_169)
170. [What is `CommandLineRunner`?](#sb_170)
171. [What is `ApplicationRunner`?](#sb_171)
172. [`CommandLineRunner` vs `ApplicationRunner`](#sb_172)
173. [What are Profiles?](#sb_173)
174. [What is `@Profile`?](#sb_174)
175. [How do dev/test/prod configurations work?](#sb_175)
176. [`application.properties` vs `application.yml`](#sb_176)
177. [Configuration precedence in Spring Boot](#sb_177)
178. [Environment variables vs properties](#sb_178)
179. [What is `@ConfigurationProperties`?](#sb_179)
180. [`@Value` vs `@ConfigurationProperties`](#sb_180)
181. [What is Actuator?](#sb_181)
182. [Important Actuator endpoints](#sb_182)
183. [`health`](#sb_183)
184. [`metrics`](#sb_184)
185. [`info`](#sb_185)
186. [`beans`](#sb_186)
187. [`env`](#sb_187)
188. [How do you secure Actuator endpoints?](#sb_188)

<br>


# 1. Core Spring Fundamentals

<br>

<h3 id="sb_01">What is Spring Framework?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_02">Why was Spring introduced?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_03">What problems does Spring solve?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_04">What is IoC (Inversion of Control)?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_05">What is Dependency Injection?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_06">IoC vs Dependency Injection</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_07">What are the different types of Dependency Injection?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_08">What is Constructor Injection?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_09">What is Setter Injection?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_10">What is Field Injection?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_11">Constructor vs Setter vs Field Injection</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_12">Why is Constructor Injection recommended?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_13">What is a Spring Bean?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_14">Java Object vs Spring Bean</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_15">What is Spring Container?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_16">What is ApplicationContext?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_17">What is BeanFactory?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_18">ApplicationContext vs BeanFactory</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_19">What is Bean Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_20">What is Singleton Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_21">What is Prototype Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_22">What is Request Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_23">What is Session Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_24">What is Application Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_25">What is WebSocket Scope?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_26">Spring Singleton vs Java Singleton</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_27">Can a Singleton Bean inject a Prototype Bean?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_28">What problem occurs when Prototype Bean is injected into Singleton?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_29">What is @Lookup?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_30">What is Bean Lifecycle?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_31">Explain the complete Spring Bean Lifecycle.</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_32">What is @PostConstruct?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_33">What is @PreDestroy?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_34">What is InitializingBean?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_35">What is DisposableBean?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_36">@PostConstruct vs InitializingBean</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_37">What are initMethod and destroyMethod?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_38">What is @Component?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_39">What is @Service?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_40">What is @Repository?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_41">What is @Controller?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_42">What is @RestController?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_43">@Controller vs @RestController</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_44">@Component vs @Bean</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_45">Why do we have @Service if @Component can do the same thing?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_46">What special behavior does @Repository provide?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_47">What is Component Scanning?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_48">How does @ComponentScan work?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_49">What happens if a component is outside the base package?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_50">What are Spring configuration approaches?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_51">What is XML Configuration?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_52">What is Java Configuration?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_53">What is Annotation Configuration?</h3>

<br>

<!-- Answer goes here -->

<br>

## Phase 2: Spring Internals

<br>

<h3 id="sb_60">60. How does Spring Container start?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_61">61. How does Spring discover Beans?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_62">62. How does Spring instantiate Beans?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_63">63. How are dependencies resolved?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_64">64. How does Spring maintain Beans internally?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_65">65. What is BeanDefinition?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_66">66. What is BeanDefinitionRegistry?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_67">67. What is BeanFactoryPostProcessor?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_68">68. What is BeanPostProcessor?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_69">69. BeanFactoryPostProcessor vs BeanPostProcessor</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_70">70. When does BeanPostProcessor execute?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_71">71. How does @Autowired work internally?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_72">72. What is AutowiredAnnotationBeanPostProcessor?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_73">73. How does Spring resolve dependency by type?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_74">74. What happens if multiple Beans of the same type exist?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_75">75. What is NoUniqueBeanDefinitionException?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_76">76. What is NoSuchBeanDefinitionException?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_77">77. What is @Qualifier?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_78">78. What is @Primary?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_79">79. @Qualifier vs @Primary</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_80">80. Can @Autowired be used on constructors?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_81">81. Is @Autowired required for a single constructor?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_82">82. What is Circular Dependency?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_83">83. Why can constructor circular dependency fail?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_84">84. How does Spring handle setter/field circular dependency?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_85">85. What are Spring's three-level singleton caches?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_86">86. What is singletonObjects?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_87">87. What is earlySingletonObjects?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_88">88. What is singletonFactories?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_89">89. Why are circular references discouraged?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_90">90. How do you redesign code to remove circular dependencies?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_91">91. What is Lazy Initialization?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_92">92. What is @Lazy?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_93">93. Where can @Lazy be used?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_94">94. Lazy vs Eager initialization</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_95">95. What is Spring Expression Language (SpEL)?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_96">96. What can SpEL be used for?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_97">97. What are proxies in Spring?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_98">98. JDK Dynamic Proxy vs CGLIB Proxy</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_99">99. When does Spring use a JDK proxy?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_100">100. When does Spring use a CGLIB proxy?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_101">101. Why are Spring proxies important?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_102">102. What is self-invocation?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_103">103. Why can self-invocation bypass Spring proxy behavior?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_104">104. Which Spring features depend heavily on proxies?</h3>

<br>

<!-- Answer goes here -->

<br>

## Phase 3: Spring AOP

<br>

<h3 id="sb_105">105. What is AOP?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_106">106. Why was AOP introduced?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_107">107. What are Cross-Cutting Concerns?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_108">108. What is an Aspect?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_109">109. What is Advice?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_110">110. What is Join Point?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_111">111. What is Pointcut?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_112">112. What is Target Object?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_113">113. What is Weaving?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_114">114. Compile-time vs Load-time vs Runtime weaving</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_115">115. How does Spring AOP work internally?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_116">116. Spring AOP vs AspectJ</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_117">117. What is @Aspect?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_118">118. What is @Before?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_119">119. What is @After?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_120">120. What is @AfterReturning?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_121">121. What is @AfterThrowing?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_122">122. What is @Around?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_123">123. Which Advice is most powerful?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_124">124. What is ProceedingJoinPoint?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_125">125. What happens if proceed() is not called?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_126">126. How do you write a Pointcut expression?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_127">127. Explain the execution() Pointcut expression.</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_128">128. Can multiple Pointcuts be combined?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_129">129. How do you control Aspect execution order?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_130">130. What is @Order?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_131">131. How does AOP use proxies?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_132">132. Why does AOP not work as expected with self-invocation?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_133">133. Can private methods be intercepted?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_134">134. Can final methods cause proxy limitations?</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_135">135. Logging using AOP</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_136">136. Performance monitoring using AOP</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_137">137. Auditing using AOP</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_138">138. Security using AOP</h3>

<br>

<!-- Answer goes here -->

<br>

<h3 id="sb_139">139. Transaction management using AOP</h3>

<br>

<!-- Answer goes here -->


## Phase 4: Spring Boot Fundamentals and Internals

<br>
<h3 id="sb_140">Why Spring Boot?</h3>
<br>

<h3 id="sb_141">Spring vs Spring MVC vs Spring Boot</h3>
<br>

<h3 id="sb_142">Advantages of Spring Boot</h3>
<br>

<h3 id="sb_143">What is @SpringBootApplication?</h3>
<br>

<h3 id="sb_144">What annotations are inside @SpringBootApplication?</h3>
<br>

<h3 id="sb_145">What is @SpringBootConfiguration?</h3>
<br>

<h3 id="sb_146">What is @EnableAutoConfiguration?</h3>
<br>

<h3 id="sb_147">What is @ComponentScan?</h3>
<br>

<h3 id="sb_148">What happens when SpringApplication.run() executes?</h3>
<br>

<h3 id="sb_149">Explain Spring Boot application startup flow.</h3>
<br>

<h3 id="sb_150">How is ApplicationContext created?</h3>
<br>

<h3 id="sb_151">How does component scanning start?</h3>
<br>

<h3 id="sb_152">How does Auto Configuration work?</h3>
<br>

<h3 id="sb_153">What is conditional configuration?</h3>
<br>

<h3 id="sb_154">What is @Conditional?</h3>
<br>

<h3 id="sb_155">What is @ConditionalOnClass?</h3>
<br>

<h3 id="sb_156">What is @ConditionalOnMissingBean?</h3>
<br>

<h3 id="sb_157">What is @ConditionalOnProperty?</h3>
<br>

<h3 id="sb_158">What is @ConditionalOnBean?</h3>
<br>

<h3 id="sb_159">How does Boot decide which Auto Configurations to load?</h3>
<br>

<h3 id="sb_160">How can Auto Configuration be excluded?</h3>
<br>

<h3 id="sb_161">What are Starter Dependencies?</h3>
<br>

<h3 id="sb_162">How do starters simplify dependency management?</h3>
<br>

<h3 id="sb_163">What is Spring Boot's parent POM?</h3>
<br>

<h3 id="sb_164">What is dependency management?</h3>
<br>

<h3 id="sb_165">What is an Embedded Server?</h3>
<br>

<h3 id="sb_166">How does embedded Tomcat start?</h3>
<br>

<h3 id="sb_167">Tomcat vs Servlet Container</h3>
<br>

<h3 id="sb_168">Tomcat vs Application Server</h3>
<br>

<h3 id="sb_169">How do you replace Tomcat with Jetty or Undertow?</h3>
<br>

<h3 id="sb_170">What is CommandLineRunner?</h3>
<br>

<h3 id="sb_171">What is ApplicationRunner?</h3>
<br>

<h3 id="sb_172">CommandLineRunner vs ApplicationRunner</h3>
<br>

<h3 id="sb_173">What are Profiles?</h3>
<br>

<h3 id="sb_174">What is @Profile?</h3>
<br>

<h3 id="sb_175">How do dev/test/prod configurations work?</h3>
<br>

<h3 id="sb_176">application.properties vs application.yml</h3>
<br>

<h3 id="sb_177">Configuration precedence in Spring Boot</h3>
<br>

<h3 id="sb_178">Environment variables vs properties</h3>
<br>

<h3 id="sb_179">What is @ConfigurationProperties?</h3>
<br>

<h3 id="sb_180">@Value vs @ConfigurationProperties</h3>
<br>

<h3 id="sb_181">What is Actuator?</h3>
<br>

<h3 id="sb_182">Important Actuator endpoints</h3>
<br>

<h3 id="sb_183">health</h3>
<br>

<h3 id="sb_184">metrics</h3>
<br>

<h3 id="sb_185">info</h3>
<br>

<h3 id="sb_186">beans</h3>
<br>

<h3 id="sb_187">env</h3>
<br>

<h3 id="sb_188">How do you secure Actuator endpoints?</h3>
<br>

### Phase 1: Core Spring Fundamentals

1. [What is Spring Framework?](#sb_01)
2. [Why was Spring introduced?](#sb_02)
3. [What is IoC (Inversion of Control)?](#sb_03)
4. [What is Dependency Injection?](#sb_04)
5. [What is Constructor Injection?](#sb_05)
6. [What is Setter Injection?](#sb_06)
7. [What is Field Injection?](#sb_07)
8. [What is Spring Bean Lifecycle?](#sb_08)
9. [What are Bean Scopes?](#sb_09)
10. [What is Singleton Scope?](#sb_10)
11. [What is Prototype Scope?](#sb_11)
12. [What is Request Scope?](#sb_12)
13. [What is Session Scope?](#sb_13)
14. [What are @Component, @Service, @Repository and @Controller?](#sb_14)
15. [What is Component Scanning?](#sb_15)
16. [What are Spring Configuration Types?](#sb_16)
17. [What is XML-based Configuration?](#sb_17)
18. [What is Java-based Configuration?](#sb_18)
19. [What is Annotation-based Configuration?](#sb_19)


### Phase 2: Spring Internals - Very Important for 5+ Years

20. [ApplicationContext vs BeanFactory](#sb_20)
21. [How does Spring create Beans?](#sb_21)
22. [What is BeanPostProcessor?](#sb_22)
23. [What is Spring Container?](#sb_23)
24. [How does @Autowired work internally?](#sb_24)
25. [What is @Qualifier?](#sb_25)
26. [What is @Primary?](#sb_26)
27. [What is Circular Dependency?](#sb_27)
28. [What is Lazy Initialization?](#sb_28)
29. [What is Spring Expression Language (SpEL)?](#sb_29)


### Phase 3: Spring AOP

30. [Why do we need AOP?](#sb_30)
31. [What are Advice Types?](#sb_31)
32. [What is a Pointcut?](#sb_32)
33. [What is a Join Point?](#sb_33)
34. [What is an Aspect?](#sb_34)
35. [What are real-time use cases of AOP?](#sb_35)
36. [How is AOP used for Logging?](#sb_36)
37. [How is AOP used for Security?](#sb_37)
38. [How is AOP used for Transaction Management?](#sb_38)


### Phase 4: Spring Boot Fundamentals

39. [Why Spring Boot?](#sb_39)
40. [Spring vs Spring Boot](#sb_40)
41. [What is Auto Configuration?](#sb_41)
42. [What are Starter Dependencies?](#sb_42)
43. [What is Embedded Tomcat?](#sb_43)
44. [What is the Spring Boot Project Structure?](#sb_44)
45. [application.properties vs application.yml](#sb_45)
46. [What is CommandLineRunner?](#sb_46)
47. [What are Spring Profiles?](#sb_47)
48. [What is Spring Boot Actuator?](#sb_48)


### Phase 5: Spring Boot Enterprise Questions

49. [How does a request flow from Browser to Database?](#sb_49)
50. [What is DispatcherServlet?](#sb_50)
51. [How does Exception Handling work in Spring Boot?](#sb_51)
52. [What is @ControllerAdvice?](#sb_52)
53. [What is Global Exception Handling?](#sb_53)
54. [Filters vs Interceptors](#sb_54)
55. [What are REST API Best Practices?](#sb_55)
56. [How does Validation work in Spring Boot?](#sb_56)
57. [What is Custom Validation?](#sb_57)


### Phase 6: Spring Data JPA

58. [JPA vs Hibernate](#sb_58)
59. [What is Entity Lifecycle?](#sb_59)
60. [What is First Level Cache?](#sb_60)
61. [What is Second Level Cache?](#sb_61)
62. [What are Fetch Types?](#sb_62)
63. [Lazy vs Eager Loading](#sb_63)
64. [What is the N+1 Problem?](#sb_64)
65. [What are Cascade Types?](#sb_65)
66. [What is JPQL?](#sb_66)
67. [What is a Native Query?](#sb_67)
68. [What are JPA Specifications?](#sb_68)
69. [What is Pagination and Sorting?](#sb_69)


### Phase 7: Transaction Management

70. [What is @Transactional?](#sb_70)
71. [How does @Transactional work internally?](#sb_71)
72. [What are Transaction Propagation Types?](#sb_72)
73. [REQUIRED Propagation](#sb_73)
74. [REQUIRES_NEW Propagation](#sb_74)
75. [SUPPORTS Propagation](#sb_75)
76. [NOT_SUPPORTED Propagation](#sb_76)
77. [MANDATORY Propagation](#sb_77)
78. [NEVER Propagation](#sb_78)
79. [NESTED Propagation](#sb_79)
80. [What are Transaction Isolation Levels?](#sb_80)
81. [What is READ_UNCOMMITTED?](#sb_81)
82. [What is READ_COMMITTED?](#sb_82)
83. [What is REPEATABLE_READ?](#sb_83)
84. [What is SERIALIZABLE?](#sb_84)
85. [What is Dirty Read?](#sb_85)
86. [What is Non-Repeatable Read?](#sb_86)
87. [What is Phantom Read?](#sb_87)


### Phase 8: Security & Microservices

88. [What is JWT Authentication?](#sb_88)
89. [What is OAuth2?](#sb_89)
90. [How does Spring Security Flow work?](#sb_90)
91. [What is an API Gateway?](#sb_91)
92. [What is Service Discovery?](#sb_92)
93. [What is Feign Client?](#sb_93)
94. [What is Circuit Breaker?](#sb_94)
95. [What are Distributed Transactions?](#sb_95)


### Important Questions for 5+ Years Experience

96. [What happens when a Spring Boot application starts?](#sb_96)
97. [How does AutoConfiguration work internally?](#sb_97)
98. [What is LazyInitializationException?](#sb_98)
99. [How do you solve the N+1 Query Problem?](#sb_99)
100. [Explain Spring Security with JWT](#sb_100)


---

# Phase 1: Core Spring Fundamentals

<h3 id="sb_01">1. What is Spring Framework?</h3>

<!-- Add answer here -->

---

<h3 id="sb_02">2. Why was Spring introduced?</h3>

<!-- Add answer here -->

---

<h3 id="sb_03">3. What is IoC (Inversion of Control)?</h3>

<!-- Add answer here -->

---

<h3 id="sb_04">4. What is Dependency Injection?</h3>

<!-- Add answer here -->

---

<h3 id="sb_05">5. What is Constructor Injection?</h3>

<!-- Add answer here -->

---

<h3 id="sb_06">6. What is Setter Injection?</h3>

<!-- Add answer here -->

---

<h3 id="sb_07">7. What is Field Injection?</h3>

<!-- Add answer here -->

---

<h3 id="sb_08">8. What is Spring Bean Lifecycle?</h3>

<!-- Add answer here -->

---

<h3 id="sb_09">9. What are Bean Scopes?</h3>

<!-- Add answer here -->

---

<h3 id="sb_10">10. What is Singleton Scope?</h3>

<!-- Add answer here -->

---

<h3 id="sb_11">11. What is Prototype Scope?</h3>

<!-- Add answer here -->

---

<h3 id="sb_12">12. What is Request Scope?</h3>

<!-- Add answer here -->

---

<h3 id="sb_13">13. What is Session Scope?</h3>

<!-- Add answer here -->

---

<h3 id="sb_14">14. What are @Component, @Service, @Repository and @Controller?</h3>

<!-- Add answer here -->

---

<h3 id="sb_15">15. What is Component Scanning?</h3>

<!-- Add answer here -->

---

<h3 id="sb_16">16. What are Spring Configuration Types?</h3>

<!-- Add answer here -->

---

<h3 id="sb_17">17. What is XML-based Configuration?</h3>

<!-- Add answer here -->

---

<h3 id="sb_18">18. What is Java-based Configuration?</h3>

<!-- Add answer here -->

---

<h3 id="sb_19">19. What is Annotation-based Configuration?</h3>

<!-- Add answer here -->


# Phase 2: Spring Internals

<h3 id="sb_20">20. ApplicationContext vs BeanFactory</h3>

<!-- Add answer here -->

---

<h3 id="sb_21">21. How does Spring create Beans?</h3>

<!-- Add answer here -->

---

<h3 id="sb_22">22. What is BeanPostProcessor?</h3>

<!-- Add answer here -->

---

<h3 id="sb_23">23. What is Spring Container?</h3>

<!-- Add answer here -->

---

<h3 id="sb_24">24. How does @Autowired work internally?</h3>

<!-- Add answer here -->

---

<h3 id="sb_25">25. What is @Qualifier?</h3>

<!-- Add answer here -->

---

<h3 id="sb_26">26. What is @Primary?</h3>

<!-- Add answer here -->

---

<h3 id="sb_27">27. What is Circular Dependency?</h3>

<!-- Add answer here -->

---

<h3 id="sb_28">28. What is Lazy Initialization?</h3>

<!-- Add answer here -->

---

<h3 id="sb_29">29. What is Spring Expression Language (SpEL)?</h3>

<!-- Add answer here -->


# Phase 3: Spring AOP

<h3 id="sb_30">30. Why do we need AOP?</h3>

<!-- Add answer here -->

---

<h3 id="sb_31">31. What are Advice Types?</h3>

<!-- Add answer here -->

---

<h3 id="sb_32">32. What is a Pointcut?</h3>

<!-- Add answer here -->

---

<h3 id="sb_33">33. What is a Join Point?</h3>

<!-- Add answer here -->

---

<h3 id="sb_34">34. What is an Aspect?</h3>

<!-- Add answer here -->

---

<h3 id="sb_35">35. What are real-time use cases of AOP?</h3>

<!-- Add answer here -->

---

<h3 id="sb_36">36. How is AOP used for Logging?</h3>

<!-- Add answer here -->

---

<h3 id="sb_37">37. How is AOP used for Security?</h3>

<!-- Add answer here -->

---

<h3 id="sb_38">38. How is AOP used for Transaction Management?</h3>

<!-- Add answer here -->


# Phase 4: Spring Boot Fundamentals

<h3 id="sb_39">39. Why Spring Boot?</h3>

<!-- Add answer here -->

---

<h3 id="sb_40">40. Spring vs Spring Boot</h3>

<!-- Add answer here -->

---

<h3 id="sb_41">41. What is Auto Configuration?</h3>

<!-- Add answer here -->

---

<h3 id="sb_42">42. What are Starter Dependencies?</h3>

<!-- Add answer here -->

---

<h3 id="sb_43">43. What is Embedded Tomcat?</h3>

<!-- Add answer here -->

---

<h3 id="sb_44">44. What is the Spring Boot Project Structure?</h3>

<!-- Add answer here -->

---

<h3 id="sb_45">45. application.properties vs application.yml</h3>

<!-- Add answer here -->

---

<h3 id="sb_46">46. What is CommandLineRunner?</h3>

<!-- Add answer here -->

---

<h3 id="sb_47">47. What are Spring Profiles?</h3>

<!-- Add answer here -->

---

<h3 id="sb_48">48. What is Spring Boot Actuator?</h3>

<!-- Add answer here -->


# Phase 5: Spring Boot Enterprise Questions

<h3 id="sb_49">49. How does a request flow from Browser to Database?</h3>

<!-- Add answer here -->

---

<h3 id="sb_50">50. What is DispatcherServlet?</h3>

<!-- Add answer here -->

---

<h3 id="sb_51">51. How does Exception Handling work in Spring Boot?</h3>

<!-- Add answer here -->

---

<h3 id="sb_52">52. What is @ControllerAdvice?</h3>

<!-- Add answer here -->

---

<h3 id="sb_53">53. What is Global Exception Handling?</h3>

<!-- Add answer here -->

---

<h3 id="sb_54">54. Filters vs Interceptors</h3>

<!-- Add answer here -->

---

<h3 id="sb_55">55. What are REST API Best Practices?</h3>

<!-- Add answer here -->

---

<h3 id="sb_56">56. How does Validation work in Spring Boot?</h3>

<!-- Add answer here -->

---

<h3 id="sb_57">57. What is Custom Validation?</h3>

<!-- Add answer here -->


# Phase 6: Spring Data JPA

<h3 id="sb_58">58. JPA vs Hibernate</h3>

<!-- Add answer here -->

---

<h3 id="sb_59">59. What is Entity Lifecycle?</h3>

<!-- Add answer here -->

---

<h3 id="sb_60">60. What is First Level. How does AutoConfiguration work internally?</h3>

<!-- Add answer here -->

---

<h3 id="sb_98">98. What is LazyInitializationException?</h3>

<!-- Add answer here -->

---

<h3 id="sb_99">99. How do you solve the N+1 Query Problem?</h3>

<!-- Add answer here -->

---

<h3 id="sb_100">100. Explain Spring Security with JWT</h3>

<!-- Add answer here -->


# Spring - Dependency Injection

### First: What is a “dependency”? 

A **dependency** is **something a class needs to work**.

Example:

* A **Car** needs an **Engine**
* A **Phone** needs a **Battery**
* A **StudentService** needs a **StudentRepository**

So,
👉 *Engine is a dependency of Car*

### Now: What is “Dependency Injection”?

**Dependency Injection = Giving what is needed from outside**

Instead of:

> “I will create what I need”

We say:

> “Someone else will give me what I need”

That **someone else** is **Spring**.

### ❌ Life WITHOUT Dependency Injection (Normal Java)

```java
class Car {
    Engine engine = new Engine(); // Car creates Engine
}
```

### What is happening?

* Car **creates** Engine
* Car **controls** Engine

### Why this is bad?

* Car is **stuck** with this Engine
* If Engine changes → Car must change
* Too many responsibilities

💡 *Car should only DRIVE, not CREATE engines*

### ✅ Life WITH Dependency Injection (Spring Way)

```java
class Car {
    Engine engine;

    Car(Engine engine) {
        this.engine = engine;
    }
}
```

### What is happening?

* Car does **NOT create** Engine
* Engine is **given from outside**
* Car just **uses** it

👉 This is **Dependency Injection**

### 🔁 What Spring Boot Actually Does

Spring Boot:

1. Creates objects (beans)
2. Keeps them ready
3. Gives them to classes when needed

You just say:

```java
@Autowired
Engine engine;
```

Spring says:

> “Okay, I’ll give you an Engine”

### ❓ Why is this IMPORTANT?

### 1️⃣ One Job Per Class

* Car → drive
* Engine → generate power
* Spring → connect them

Clean separation 👍

### 2️⃣ Easy to Change Things

Today:

```java
PetrolEngine
```

Tomorrow:

```java
ElectricEngine
```

Car code stays same ✔

### 3️⃣ Less Confusion, Less Code

You don’t write:

```java
new Engine();
```

Spring handles it 💚

### 🧠 Key Sentence (Remember This)

> **Dependency Injection means a class does not create what it needs; it receives it.**

OR even simpler:

> **“Don’t make it, take it.”**

### ⚡ Tiny Example (Complete Flow)

```java
@Component
class Engine {
}

@Component
class Car {
    @Autowired
    Engine engine;
}
```

What happens?

* Spring creates Engine
* Spring creates Car
* Spring puts Engine inside Car

That’s it. Nothing magical.

---

# Types of DI

### PART 1: First understand the BASIC PROBLEM (before IoC / DI)

### Imagine ONLY normal Java (no Spring)

```java
class Engine {
}

class Car {
    Engine engine = new Engine();
}
```

### What is happening here?

* `Car` **creates** `Engine`
* `Car` **controls** `Engine`
* `Car` has **two jobs**:

  1. Drive
  2. Create engine ❌

This is the **problem**.

### Why is this a problem? (Very important)

Suppose tomorrow:

* You want **ElectricEngine** instead of **PetrolEngine**

Now you must change `Car` code.

👉 **Car is tightly tied to Engine**

### PART 2: The IDEA — IoC (Inversion of Control)

### What is IoC REALLY?

IoC is just a **decision**:

> “My class should NOT create what it needs.”

That’s it. No magic.

---

# What changes with IoC?

### ❌ Old thinking

> “I will create Engine.”

### ✅ New thinking

> “Someone else will create Engine for me.”

That **someone else** = **Spring**

👉 Control is **inverted** (reversed).

### IoC is NOT code

IoC is **who is in charge**.

### PART 3: Now HOW does Spring help? → DI

### DI = Dependency Injection

Plain meaning:

> **Spring gives the needed object to your class.**

So:

* You stop creating
* Spring starts giving

### PART 4: Slowly build a Spring example

### Step 1: Tell Spring which classes it must manage

```java
@Component
class Engine {
}
```

```java
@Component
class Car {
}
```

Now Spring says:

> “Okay, I will create these objects.”

### Step 2: Remove `new`

❌ Don’t do this anymore:

```java
new Engine();
```

### Step 3: Ask Spring to give Engine to Car

Now we reach **DI types**.

### PART 5: Types of Dependency Injection (Very Slowly)

### 🔹 Type 1: Constructor Injection (Start here)

### Code:

```java
@Component
class Car {

    Engine engine;

    Car(Engine engine) {
        this.engine = engine;
    }
}
```

### What is happening internally?

1. Spring creates `Engine`
2. Spring wants to create `Car`
3. Spring sees:

   > “Car needs Engine in constructor”
4. Spring gives Engine
5. Car is created

### Plain meaning:

> “Car CANNOT exist without Engine.”

This is **safe and clean**.

### 🔹 Type 2: Setter Injection (Slower & optional)

### Code:

```java
@Component
class Car {

    Engine engine;

    @Autowired
    void setEngine(Engine engine) {
        this.engine = engine;
    }
}
```

### What happens?

1. Spring creates Car (engine is null)
2. Spring creates Engine
3. Spring calls `setEngine()`
4. Engine is set later

### Plain meaning:

> “Car can exist without Engine, but Engine can be added later.”

### 🔹 Type 3: Field Injection (Shortcut)

### Code:

```java
@Component
class Car {

    @Autowired
    Engine engine;
}
```

### What happens?

1. Spring creates Car
2. Spring puts Engine directly into field

### Why is this bad?

* Hidden dependency
* Hard to test
* Not clear from constructor

### PART 6: Compare all three (VERY CLEAR)

| Question                      | Constructor | Setter         | Field          |
| ----------------------------- | ----------- | -------------- | -------------- |
| When engine is given?         | At creation | After creation | After creation |
| Can Car exist without engine? | ❌ No        | ✅ Yes          | ✅ Yes          |
| Safe?                         | ✅ Yes       | ⚠️ Medium      | ❌ No           |
| Recommended?                  | ✅ Best      | ⚠️ Sometimes   | ❌ Avoid        |

### PART 7: Now connect IoC + DI (MOST IMPORTANT)

### IoC:

> “Spring creates objects, not me.”

### DI:

> “Spring gives needed objects.”

### In one flow:

1. Spring controls creation → **IoC**
2. Spring injects dependencies → **DI**

### PART 8: Final mental picture 🧠

### Without Spring

You:

* Buy parts
* Assemble
* Maintain

### With Spring

Spring:

* Creates
* Assembles
* Gives ready object

You:

* Use it

# FINAL ONE-SENTENCE MEMORY

> **IoC decides WHO creates objects. DI decides HOW objects are given.**

---

#  DI Type to Use - senario

### 1️⃣ What is SETTER Injection? (Reminder)

```java
@Component
class Car {

    private Engine engine;

    @Autowired
    public void setEngine(Engine engine) {
        this.engine = engine;
    }
}
```

Plain meaning:

> “Create the object first, then give the dependency later.”

### 2️⃣ FIELD vs SETTER vs CONSTRUCTOR (Big Picture)

### 🔴 1. Visibility of dependency (MOST IMPORTANT)

### Field Injection ❌

```java
@Component
class Car {
    @Autowired
    Engine engine;
}
```

* You don’t immediately see:

  * Is `Engine` required?
  * Can `Car` work without it?

Hidden dependency ❌

### Setter Injection ⚠️

```java
@Autowired
void setEngine(Engine engine) { }
```

* You can see dependency
* But it looks **optional**

Better than field ✔
Still not perfect ⚠️

### Constructor Injection ✅

```java
Car(Engine engine) { }
```

* Dependency is obvious
* Mandatory

Best ✅

### 🔴 2. Object safety (null problem)

### Field Injection ❌

* Object is created with `engine = null`
* Engine comes later

Risk of `NullPointerException`

### Setter Injection ⚠️

* Same issue
* Engine set later

Still risky

### Constructor Injection ✅

* Object cannot exist without Engine
* No null state

### 🔴 3. Testing without Spring

### Field Injection ❌

Hard to test:

```java
Car car = new Car(); // engine is null
```

### Setter Injection ⚠️

Possible but extra step:

```java
Car car = new Car();
car.setEngine(new Engine());
```

Works, but easy to forget

### Constructor Injection ✅

Easy & clean:

```java
Car car = new Car(new Engine());
```

### 🔴 4. Immutability (simple explanation)

### Field Injection ❌

* Cannot use `final`
* Object can change

### Setter Injection ⚠️

* Can change engine anytime
* Less stable

### Constructor Injection ✅

* `final` possible
* Object is fixed after creation

### 🔴 5. Design intention

| Injection Type | Meaning               |
| -------------- | --------------------- |
| Field          | “Just put it there”   |
| Setter         | “Optional dependency” |
| Constructor    | “Required dependency” |

### 🧠 Real-life analogy 🚗

### Field Injection

You get a car
Someone secretly adds engine later 😬

### Setter Injection

You get a car
You *may* add engine later ⚠️

### Constructor Injection

You get a complete car
Engine already installed ✅

### 🧠 Final comparison table (Very clear)

| Aspect                       | Field | Setter | Constructor |
| ---------------------------- | ----- | ------ | ----------- |
| Dependency visibility        | ❌     | ⚠️     | ✅           |
| Null-safe                    | ❌     | ❌      | ✅           |
| Easy testing                 | ❌     | ⚠️     | ✅           |
| Can mark dependency required | ❌     | ❌      | ✅           |
| Recommended                  | ❌     | ⚠️     | ✅           |

### 🧠 Simple rules to remember

1️⃣ **Required dependency → Constructor Injection**
2️⃣ **Optional dependency → Setter Injection**
3️⃣ **Avoid Field Injection**

### 🧠 One-line memory sentence

> **Constructor = required, Setter = optional, Field = hidden.**

### Inversion of Control

### 🧠 What is IoC? (Inversion of Control)

### Meaning in plain words:

> **IoC means you are NOT in control anymore — someone else is.**

### Simple sentence:

👉 **Control is inverted (reversed).**

### ❌ Normal life (YOU are in control)

You decide:

* When to wake up
* What to cook
* What to buy
* How to do everything

You control everything.

### ✅ IoC life (Someone else is in control)

Hostel / College / Office:

* Food is provided
* Electricity is managed
* Cleaning is handled

You **don’t control** these things anymore.

👉 **Control moved from you to the system**

That is **IoC**.

### In Spring Boot terms (still simple)

### ❌ Without IoC

Your class:

* Creates objects
* Manages objects
* Decides dependencies

```java
Engine engine = new Engine();
```

You are in control.

### ✅ With IoC

Spring:

* Creates objects
* Manages objects
* Decides when and how to give them

You **lose control**.

Spring **gets control**.

👉 This is **Inversion of Control**

### 🧠 Now: What is DI? (Dependency Injection)

### Plain meaning:

> **DI is HOW IoC happens**

DI is just a **method** used to achieve IoC.

### Very simple sentence:

* **IoC = What**
* **DI = How**

### 🎯 Example to connect both

### You need a pen ✍️

### ❌ Without IoC

You:

* Go to shop
* Buy pen
* Bring it

You control everything.

### ✅ With IoC

Office:

* Gives pen to you

You didn’t get it yourself.

👉 Control is inverted (**IoC**)

👉 Pen is given to you (**DI**)

### 🧩 Spring Boot Example (No complexity)

```java
@Component
class Engine {
}

@Component
class Car {
    @Autowired
    Engine engine;
}
```

What happens?

* Spring creates Engine (**IoC**)
* Spring gives Engine to Car (**DI**)

### 🧠 One-line Memory Trick

### 🔹 IoC:

> “I don’t control object creation”

### 🔹 DI:

> “Object is given to me”

## 🧠 Super Simple Summary

| Term         | Plain Meaning                                 |
| ------------ | --------------------------------------------- |
| **IoC**      | Control is taken from you and given to Spring |
| **DI**       | Spring gives required objects to your class   |
| **Relation** | DI is one way to implement IoC                |

### Final sentence (remember forever ❤️)

> **IoC is the idea. DI is the action.**

---

# How the Object creation happends inside Ioc 

### First: Important Truth 🌱

👉 **You do NOT “create IoC” manually in Spring Boot**

**Spring Boot already has IoC built-in.**
You just **USE it correctly**.

### 🧠 So what does “create IoC” really mean?

It means:

> **Let Spring control object creation instead of you**

That’s it.

### ❌ Wrong way (No IoC)

```java
class Car {
    Engine engine = new Engine(); // YOU are controlling
}
```

Here:

* You created Engine
* You control everything

❌ No IoC

### ✅ Correct way (IoC in Spring Boot)

You do **3 simple things**:

### ✅ STEP 1: Tell Spring “This is an object I want you to manage”

Use `@Component`

```java
@Component
class Engine {
}
```

```java
@Component
class Car {
}
```

This means:

> “Spring, please create and manage this class”

### ✅ STEP 2: Remove `new` keyword

❌ Don’t do this:

```java
new Engine();
```

### ✅ STEP 3: Ask Spring to give dependency (DI)

```java
@Component
class Car {

    @Autowired
    Engine engine;
}
```

That’s it 🎉

### 🔄 What Spring Boot does internally (Simple Flow)

1. Spring starts
2. Finds `@Component` classes
3. Creates objects (beans)
4. Stores them in a container
5. Injects needed objects

👉 **Spring is in control = IoC**

### 🧠 Spring Container (Very Simple Idea)

Think of Spring container as a **big box 📦**

* Inside the box:

  * Engine
  * Car
  * Other objects

When Car says:

> “I need Engine”

Spring takes Engine from box and puts it inside Car.

### 🧩 Minimal Example (Full)

```java
@SpringBootApplication
public class DemoApplication {
    public static void main(String[] args) {
        SpringApplication.run(DemoApplication.class, args);
    }
}
```

```java
@Component
class Engine {
}
```

```java
@Component
class Car {

    @Autowired
    Engine engine;
}
```

👉 You did NOTHING extra.
👉 IoC is already working.

### 🧠 One sentence to remember

> **IoC is created when you stop using `new` and let Spring manage objects.**

### ⚡ Alternative way (Using `@Bean`)

```java
@Configuration
class Config {

    @Bean
    Engine engine() {
        return new Engine();
    }
}
```

Spring controls it → IoC ✔

### 🧠 Final Super-Simple Summary

| What you do      | Result                    |
| ---------------- | ------------------------- |
| Use `@Component` | Spring creates object     |
| Remove `new`     | You lose control          |
| Use `@Autowired` | Spring injects dependency |
| Result           | IoC happens               |

---

# ✅ 3 Ways to Create IoC Container (Spring Framework)

### 1️⃣ **Using XML Configuration**

```java
ApplicationContext context =
    new ClassPathXmlApplicationContext("beans.xml");
```

📄 Uses `beans.xml`

🧠 **Remember:**
XML → `ClassPathXmlApplicationContext`

### 2️⃣ **Using Java Configuration (Annotations)**

```java
ApplicationContext context =
    new AnnotationConfigApplicationContext(AppConfig.class);
```

```java
@Configuration
@ComponentScan("com.example")
public class AppConfig {
}
```

🧠 **Remember:**
Java class → `AnnotationConfigApplicationContext`

### 3️⃣ **Using Spring Boot**

```java
SpringApplication.run(MyApplication.class, args);
```

✔️ IoC container is created **automatically**

🧠 **Remember:**
Boot → `SpringApplication.run()`

### 🎯 Interview Answer (Perfect)

> **There are 3 ways to create an IoC container:

1. XML-based configuration
2. Java-based (annotation) configuration
3. Spring Boot, where the container is auto-created using SpringApplication.run().**


### 🧠 Super Easy Memory Trick

```
XML   → XML Context
JAVA  → Annotation Context
BOOT  → Auto Context
```

### ⚠️ Interview Note (Important!)

Strictly speaking:

* **Spring Framework → 2 manual ways (XML + Java)**
* **Spring Boot → automatic (no manual creation)**

👉 But interviewers usually accept **3 ways*

> **In Spring Framework, we manually create the IoC container using ApplicationContext or BeanFactory.
> In Spring Boot, the IoC container is automatically created by SpringApplication.run(), so no manual creation is needed.**

---

# @Bean Vs @Component

### First: What do both do?

👉 **Both `@Component` and `@Bean` create objects that Spring controls.**
That’s the only common point.

### 🧠 Think of Spring as a **factory 🏭**

Spring factory makes objects and keeps them ready.

### 1️⃣ `@Component` (Spring finds it by itself)

### Plain meaning:

> **“Spring, please find this class and create its object automatically.”**

### Example

```java
@Component
class Engine {
}
```

What happens?

* Spring scans the project
* Sees `@Component`
* Creates Engine object
* Keeps it in its box 📦

👉 You did **nothing extra**

### Important point

* Class **must be yours**
* You control the source code

### 2️⃣ `@Bean` (You tell Spring how to create it)

### Plain meaning:

> **“Spring, create this object using MY method.”**

### Example

```java
@Configuration
class Config {

    @Bean
    Engine engine() {
        return new Engine();
    }
}
```

What happens?

* Spring calls this method
* Takes the returned object
* Stores it in container

👉 You **manually explain** how to create it

### 🧠 Real-Life Analogy (Very Easy)

### `@Component`

You say:

> “Spring, cook rice whenever you need.”

Spring knows the recipe and cooks itself 🍚

### `@Bean`

You say:

> “Spring, here is how to cook biryani step by step.”

Spring follows **your instructions** 🍛

### 🧩 When do we use each?

### Use `@Component` when:

* Class is **your own**
* Simple object
* No special setup

✔ Most common
✔ Easy
✔ Clean

### Use `@Bean` when:

* Class is **from external library**
* Needs special setup
* Cannot add `@Component`

Example:

* `DataSource`
* `ObjectMapper`
* `RestTemplate`

### 🧠 Why external classes need `@Bean`?

Because you **cannot edit their source code** to add `@Component`.

So you do:

```java
@Bean
ObjectMapper objectMapper() {
    return new ObjectMapper();
}
```

### 🧠 Key Difference in One Line

| Thing               | `@Component`   | `@Bean`              |
| ------------------- | -------------- | -------------------- |
| Who creates object  | Spring         | You                  |
| How Spring finds it | Class scanning | Method call          |
| Where written       | On class       | Inside config method |
| External classes    | ❌ No           | ✅ Yes                |
| Simplicity          | Very simple    | Slightly manual      |

### 🧠 Memory Trick 🧠

### 👉 `@Component`

**“Spring, you do it.”**

### 👉 `@Bean`

**“Spring, do it THIS way.”**

### 🧠 Final simple sentence

> Use `@Component` when you own the class.
> Use `@Bean` when you don’t own the class or need control.

### 🌱 Simple mental model

* `@Component` / `@Bean` → **Create bean**
* `@Autowired` → **Use bean**

Creation **must happen first**.

---

# @Bean with DI & why external classes inside @Bean?

### ❓ Can we use **external classes** with **DI**?

### ✅ **YES, absolutely**

Spring uses **external classes with DI all the time**.

Examples:

* `DataSource`
* `ObjectMapper`
* `RestTemplate`
* `JdbcTemplate`

👉 DI works **the same** for external classes and our classes.

### ❓ Then why do we need `new` keyword at all?

This is the **core confusion**.
Let’s clear it carefully.

### 🧠 Two different worlds

### 🌍 World 1: Normal Java (no Spring)

If there is **no Spring container**:

```java
ObjectMapper mapper = new ObjectMapper(); // must use new
```

Why?

* No one else exists to create the object
* YOU must create it

### 🌍 World 2: Spring Boot (with IoC + DI)

If Spring is managing objects:

```java
@Autowired
ObjectMapper mapper;
```

Why no `new`?

* Spring already created it
* Spring gives it to you

👉 Using `new` would **break IoC**

### 🧩 So how does Spring create external objects?

Using **`@Bean`** or **auto-configuration**.

### Example using `@Bean`

```java
@Configuration
class AppConfig {

    @Bean
    ObjectMapper objectMapper() {
        return new ObjectMapper(); // new is used HERE
    }
}
```

Important:

* `new` is used **only inside config**
* NOT inside business classes

### why does it sometimes NOT work?”

> “If I write `@Autowired ObjectMapper mapper;`

### 🔴 IMPORTANT TRUTH (This is the key)

👉 **`@Autowired` works ONLY if Spring already has an object (bean).**

If Spring **did NOT create** `ObjectMapper`, then:

❌ Spring has nothing to inject
❌ `@Autowired` fails

### ❓ Why Spring does NOT always create ObjectMapper?

Because:

* Spring **does not automatically create every class**
* Spring creates **only beans**
* External classes are **NOT beans by default**

### ❌ What you wrote (why it doesn’t work)

```java
@Autowired
ObjectMapper mapper;
```

You are **asking Spring**:

> “Please give me an ObjectMapper”

Spring replies:

> “Sorry, I don’t have one.”

💥 Result:
`NoSuchBeanDefinitionException`

---

### 🧠 Why Spring has no ObjectMapper?

Because you did NOT tell Spring:

* “Create ObjectMapper”
* “Manage ObjectMapper”

So Spring never used `new ObjectMapper()`.

### ✅ When does `@Autowired ObjectMapper` WORK?

### Case 1: You define it using `@Bean`

```java
@Configuration
class AppConfig {

    @Bean
    ObjectMapper objectMapper() {
        return new ObjectMapper();
    }
}
```

Now Spring has it ✔

```java
@Autowired
ObjectMapper mapper; // works
```

### Case 2: Spring Boot Auto-Configuration

Spring Boot **automatically creates** some beans.

Example:

* `ObjectMapper`
* `DataSource`

So this works **only if auto-config is enabled**.

### 🧠 So where is `new` actually used?

### ✔ Correct place

```java
@Bean
ObjectMapper objectMapper() {
    return new ObjectMapper(); // Spring uses new
}
```

### ❌ Wrong place

```java
class Service {
    ObjectMapper mapper = new ObjectMapper(); // breaks IoC
}
```

### 🔄 Why using `new` in service breaks IoC?

Because:

* Spring does NOT know about that object
* No lifecycle management
* No sharing
* No injection

Spring is **out of control** ❌

### 🧠 Why `new` is forbidden in business classes?

Because:

* You bypass Spring
* Spring cannot manage lifecycle
* No DI
* No IoC

❌ Bad:

```java
class Service {
    ObjectMapper mapper = new ObjectMapper();
}
```

✅ Good:

```java
class Service {
    @Autowired
    ObjectMapper mapper;
}
```

### 🧠 Who should use `new`?

### Only ONE place:

> **Spring configuration code**

Never in:

* Services
* Controllers
* Repositories

### 🧠 Real-life analogy (Very clear)

### ❌ Using `new`

You go to market and buy vegetables yourself 🛒

### ✅ Using DI

Office provides lunch 🍱

### Where is `new` used?

* Kitchen (configuration)
* NOT by employees (services)

### 🧠 Final Simple Rules (Remember these)

### Rule 1

> **If Spring manages it → don’t use `new`**

### Rule 2

> **External class + DI → use `@Bean`**

### Rule 3

> **`new` belongs only in `@Configuration`**

### 🧠 Tiny Full Example

```java
@Configuration
class AppConfig {

    @Bean
    RestTemplate restTemplate() {
        return new RestTemplate(); // new here only
    }
}
```

```java
@Service
class MyService {

    @Autowired
    RestTemplate restTemplate; // DI
}
```

### 🧠 One-line answer (Plain words)

> Yes, we can use external classes with DI. We avoid using `new` in our classes because Spring creates and injects the object for us. The `new` keyword is used only inside configuration so Spring stays in control.

### 🧠 Simple Rule (Very Important)

> **`@Autowired` does not create objects. It only asks for existing ones.**

> `@Autowired` fails because Spring never created the object in the first place.

### 🧠 Final clarity (Keep this in mind forever)

| Situation                  | Result             |
| -------------------------- | ------------------ |
| Spring created bean        | `@Autowired` works |
| Spring did NOT create bean | `@Autowired` fails |
| You used `new`             | Spring is bypassed |

---

# ❓ Are our Java classes beans by default?

### ❌ **NO**

👉 **Normal Java classes are NOT beans by default.**

Spring does **NOT** automatically manage every class you write.

### 🧠 Simple rule (remember this)

> **A class becomes a Spring bean ONLY if Spring knows about it.**

### ❌ Normal Java class (NOT a bean)

```java
class StudentService {
}
```

This is just:

* A Java class
* Spring ignores it
* You cannot `@Autowired` it

### ✅ How does a class become a bean?

You must **explicitly tell Spring**.

### 🟢 Method 1: `@Component` (Most common)

```java
@Component
class StudentService {
}
```

Now:

* Spring finds it
* Creates object
* Manages it

✔ It is a bean

### 🟢 Method 2: Stereotype annotations

These are also `@Component` internally:

```java
@Service
@Repository
@Controller
@RestController
```

So:

```java
@Service
class StudentService {
}
```

✔ Bean created

### 🟢 Method 3: `@Bean`

```java
@Configuration
class AppConfig {

    @Bean
    StudentService studentService() {
        return new StudentService();
    }
}
```

✔ Bean created

### ❓ Why do we need to “create” beans?

Because:

* Spring cannot guess which classes you want
* Creating everything would waste memory
* You may have helper or utility classes

So **you decide**.

### 🧠 Important clarification (Common confusion)

### ❌ This will NOT work

```java
@Autowired
StudentService service;
```

if `StudentService` has **no annotation**.

### ✅ This WILL work

```java
@Service
class StudentService {
}
```

```java
@Autowired
StudentService service;
```

### 🧠 Real-life analogy

### Your house 🏠

* Only people with **ID cards** can enter

Spring container:

* Only classes marked as beans get entry

Annotations = ID cards 🪪

### 🧠 One-line answer

> Our Java classes are NOT beans by default. A class becomes a bean only when we annotate it or define it using `@Bean`.

### 🧠 Final summary (very clear)

| Class type       | Is it a bean? |
| ---------------- | ------------- |
| Plain Java class | ❌ No          |
| `@Component`     | ✅ Yes         |
| `@Service`       | ✅ Yes         |
| `@Repository`    | ✅ Yes         |
| `@Bean` method   | ✅ Yes         |

---

# 🌱 Spring Bean Lifecycle 

## ✅ What is Spring Bean Lifecycle?

Spring Bean Lifecycle describes:

> **The steps a bean goes through from creation to destruction inside the Spring IoC container.**

## 🔁 COMPLETE LIFECYCLE FLOW (INTERVIEW MUST)

```
1. Bean Instantiation
2. Dependency Injection
3. Aware Interfaces (optional)
4. BeanPostProcessor (Before Init)
5. Initialization Phase
   ├─ @PostConstruct
   ├─ afterPropertiesSet() (InitializingBean)
   ├─ Custom Init Method
6. BeanPostProcessor (After Init)
7. Bean Ready to Use
8. Destruction Phase
```

## 🔍 STEP-BY-STEP EXPLANATION

## 1️⃣ Bean Instantiation

* Spring creates the bean object
* Uses constructor (default or parameterized)

```java
@Component
class Car {
    public Car() {
        System.out.println("Bean instantiated");
    }
}
```

## 2️⃣ Dependency Injection

* Spring injects dependencies using:

  * Constructor
  * Setter
  * `@Autowired`

```java
@Autowired
Engine engine;
```

📌 **Important:**

> All dependencies are injected **before initialization starts**

## 3️⃣ Aware Interfaces (Optional)

If a bean implements these, Spring injects internal objects:

* `BeanNameAware`
* `BeanFactoryAware`
* `ApplicationContextAware`

👉 Rarely used, but good for interviews.

## 4️⃣ BeanPostProcessor (Before Initialization)

Spring internally calls:

```java
postProcessBeforeInitialization()
```

Used for:

* Validation
* Proxy preparation

### 5️⃣ Initialization Phase ⭐ (VERY IMPORTANT)

Initialization happens **AFTER dependency injection**.

> **Spring provides 3 ways to initialize a bean: @PostConstruct, InitializingBean, and a custom init method defined using configuration.**

Bean is initialized using any of these:

### a) `@PostConstruct` (Recommended)

```java
@PostConstruct
public void init() {
    System.out.println("PostConstruct called");
}
```

### b) `InitializingBean`

```java
public class Car implements InitializingBean {
    @Override
    public void afterPropertiesSet() {
        System.out.println("InitializingBean called");
    }
}
```

### c) **Custom Init Method** (Explicit Configuration) ⭐

### a) Java Config (Spring / Spring Boot)

Defined using `@Bean`

```java
@Configuration
public class AppConfig {

    @Bean(initMethod = "customInit")
    public Car car() {
        return new Car();
    }
}
```

```java
public class Car {
    public void customInit() {
        System.out.println("Custom init called");
    }
}
```

### b) XML Config (Old Style)

```xml
<bean id="car"
      class="com.Car"
      init-method="customInit"/>
```

📌 Points:

* Bean class remains clean
* Method name can be anything
* Works in both Spring & Spring Boot

> ✅ **After DI and after @PostConstruct / InitializingBean, but before bean is ready to use**

## 6️⃣ BeanPostProcessor (After Initialization)

Spring calls:

```java
postProcessAfterInitialization()
```

Used for:

* AOP
* Transaction management
* Security proxies

## 7️⃣ Bean Ready to Use

* Bean is fully created
* Bean is injected wherever required
* Application can use it

## 8️⃣ Destruction Phase ⭐

Occurs when container shuts down.

### a) `@PreDestroy`

```java
@PreDestroy
public void destroy() {
    System.out.println("Cleanup logic");
}
```

### b) `DisposableBean`

```java
destroy()
```

### c) `destroy-method` (XML)

⚠️ Important:

> Destruction callbacks are **NOT called for prototype beans**

## 🧠 EASY MEMORY FLOW (WRITE THIS)

```
Constructor
→ Autowire
→ @PostConstruct
→ Custom Init
→ Ready
→ @PreDestroy
```

## ❓ Spring Boot Impact

❌ Spring Boot does **NOT** change bean lifecycle
✔️ Same lifecycle rules apply

Spring Boot only:

* Creates IoC container automatically
* Reduces configuration

## 🎯 PERFECT INTERVIEW ANSWER

> **Spring Bean Lifecycle consists of instantiation, dependency injection, initialization, and destruction. Initialization includes @PostConstruct, InitializingBean, and custom init methods, which are executed after dependency injection and before the bean is ready for use. Spring Boot follows the same lifecycle.**

---

# ❓ Why Do We Need an Init Method in Spring?

## ✅ Short Answer (Interview)

> **We need an init method to perform initialization logic after all dependencies are injected but before the bean is used.**

### 🔹 What Problem Does Init Method Solve?

### Without Init Method ❌

* Bean is created
* Dependencies may not be ready when constructor runs
* Complex setup cannot be safely done in constructor

### With Init Method ✅

* Bean is **fully created**
* All dependencies are **already injected**
* Safe place to perform setup logic

### 🔍 What Kind of Logic Goes in Init Method?

### Common Real-Time Examples:

1️⃣ **Validate injected dependencies**

```java
@PostConstruct
public void init() {
    if (dataSource == null) {
        throw new IllegalStateException("DataSource not injected");
    }
}
```

2️⃣ **Open resources**

* Database connections
* File streams
* Socket connections

3️⃣ **Load cache / configuration**

```java
@PostConstruct
public void loadCache() {
    cache = loadFromDB();
}
```

4️⃣ **Pre-compute values**

* Encryption keys
* Lookup tables

5️⃣ **Start background tasks**

* Schedulers
* Polling threads

## 🔹 Why NOT Use Constructor for This?

| Constructor                      | Init Method                |
| -------------------------------- | -------------------------- |
| Dependencies may not be injected | All dependencies are ready |
| Object creation only             | Full initialization        |
| Limited logic recommended        | Best for heavy logic       |

🎯 Interview line:

> Constructors should be lightweight; heavy initialization belongs in init methods.

## ❓ Is Init Method Still Needed in Spring Boot?

✅ YES — 100%

⚠️ Important:

> **Spring Boot does NOT remove the need for init methods.**

Boot:

* Creates container automatically
* Follows same lifecycle rules

## ⚠️ Interview Trap

**Q: Can we skip init method?**

✔️ Yes, **if no post-injection logic is required**
❌ No, **if setup depends on injected beans**

## 🎯 Perfect Interview Answer (Say This)

> **Init methods are used to execute initialization logic after dependency injection is completed. They ensure the bean is in a fully usable state before being accessed. Spring Boot follows the same lifecycle.**

## 🧠 Easy Memory Line

```
Constructor → Create object
Init method → Prepare object
```

---

# 🌱 Spring Bean Scopes 

### ✅ What is a Bean Scope?

A **bean scope** defines: **How many instances of a bean Spring creates and how long they live inside the IoC container.**

👉 🔹 Default Scope - **singleton** - Main Bean Scopes in Spring

## 1️⃣ Singleton (DEFAULT) ⭐

```java
@Component
@Scope("singleton")
public class Car { }
```

### Meaning:

* **One bean instance per IoC container**
* Same object shared everywhere

### Points:

* Created at startup (eager by default)
* Destruction managed by Spring

⚠️ Trap:

> Singleton ≠ one object per JVM
> It is **per container**

---

## 2️⃣ Prototype

```java
@Component
@Scope("prototype")
public class Engine { }
```

### Meaning:

* New object created **every time it is requested**

### Points:

* Created only when requested (lazy)
* **Spring does NOT manage destruction**

⚠️ Trap:

> @PreDestroy is NOT called for prototype beans

## 3️⃣ Request (Web Scope)

```java
@Component
@Scope("request")
public class UserRequestBean { }
```

### Meaning:

* One bean per **HTTP request**

### Points:

* Works only in web applications
* Automatically destroyed after request ends

## 4️⃣ Session (Web Scope)

```java
@Component
@Scope("session")
public class UserSessionBean { }
```

### Meaning:

* One bean per **HTTP session**

### Points:

* Same bean reused for one user session
* Destroyed when session expires

## 5️⃣ Application (Web Scope)

```java
@Component
@Scope("application")
public class AppBean { }
```

### Meaning:

* One bean per **ServletContext**
* Shared across whole application

## 6️⃣ WebSocket (Rare)

```java
@Scope("websocket")
```

* One bean per WebSocket session
* Rarely asked

## 🧠 Easy Memory Table

| Scope       | Instance Created     |
| ----------- | -------------------- |
| singleton   | One per container    |
| prototype   | New per request      |
| request     | One per HTTP request |
| session     | One per HTTP session |
| application | One per app          |

## ❓ Spring Boot Impact

❌ Spring Boot does **NOT** change scopes
✔️ Same scopes apply in Spring Boot

## 🎯 Interview One-Line Answer

> **Bean scope defines the lifecycle and visibility of a bean. The default scope is singleton, and Spring also supports prototype, request, session, and application scopes.**

## ⚠️ Common Interview Traps

* Singleton is **not** per JVM
* Prototype beans are **not destroyed** by Spring
* Request/session scopes work **only in web apps**

## 🧠 One-Line Memory Trick

```
Single → One
Proto → Many
Request → One HTTP
Session → One User
```

---

# Stereotype Annotations

### ✅ What is **Annotation-Based Configuration** (Stereotype Annotations)?

**Annotation-based configuration** means **using annotations instead of XML** to define and manage Spring beans.

👉 Spring automatically **creates objects (beans)** and **manages them** using annotations.

### 🔹 What are **Stereotype Annotations**?

Stereotype annotations tell Spring:

> **“This class is a Spring bean — manage it in the IoC container.”**

### ⭐ Main Stereotype Annotations (MOST IMPORTANT)

### 1️⃣ `@Component`

👉 **Generic** stereotype
Used when the class doesn’t fit other categories.

```java
@Component
public class Engine {
}
```

### 2️⃣ `@Service`

👉 Used in **Service / Business Logic layer**

```java
@Service
public class PaymentService {
}
```

### 3️⃣ `@Repository`

👉 Used in **DAO / Persistence layer**

```java
@Repository
public class UserRepository {
}
```

✔️ Provides **exception translation** (important interview point)

### 4️⃣ `@Controller`

👉 Used in **Spring MVC** (Web layer)

```java
@Controller
public class UserController {
}
```

### 5️⃣ `@RestController`

👉 Used for **REST APIs**

```java
@RestController
public class UserRestController {
}
```

✔️ Combination of:

```java
@Controller + @ResponseBody
```

### 🔁 How Spring Finds These Beans?

Using **component scanning** 👇

```java
@ComponentScan("com.example")
```

or in Spring Boot:

```java
@SpringBootApplication
```

(Already includes component scanning ✅)

### 🎯 One-Line Interview Answer

> **Annotation-based configuration uses stereotype annotations like @Component, @Service, @Repository, and @Controller to define Spring beans without XML.**

### 🧠 Easy Memory Trick

```
Component  → General
Service    → Business Logic
Repository → Database
Controller → Web
```

> Stereotype annotations like @Component and @Service are part of the Spring Framework. Spring Boot only auto-configures and scans them automatically.

---

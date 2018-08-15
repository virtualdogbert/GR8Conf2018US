# GR8Conf2018US
Some notes, and links from slides from GR8Conf.US 2018

Had a Great time at GR8Conf, picked up a few things, gave a couple of talks, and talked to a bunch of other engineers.

It's all Micronaut nowadays... Micronaut was very present at the four talks, and a workshop. Although Jeff would be the first to point out that Grails is still very much alive, and that we shouldn't consider monolith architecture a pejorative. Also with mico vs monolith it's not a all or nothing deal, in fact in the future Grails will be getting a Micronaut profile, and have various places, where it can take advantage of Micronaut. Technically speaking you can already use Micronaut in Grails, with the http client, and the Java side, although you may have issues with depedenacies if you try to mix it with the Groovy options in Micronaut, because Micronaut uses Groovy 2.5, and Grails doesn't yet... 

So Grails is supposed to come out by the end of the year, and that may or may not include the Micronaut profile. If it doesn't the profile will come shortly after. Grails 4 from my memory will include, Groovy 2.5, Spring Boot 2.0, and Gorm 7(hibernate 5.2).

For Groovy 2.5 was released and it has some interesting new features for those who develop AST Transforms, with macros, ASTMatcher, and macro methods. Also a bunch of internal AST transforms got updates, and some new ones added. Some issues with JDK 9+ have been worked through, and they are working through more for 3.0. I think the time-frame I heard for 3.0 was sometime around the end of the year, maybe a little after. 


Here's a bunch of links to slides and repos from some of the talks. If you have more feel free to submit a pull request:

* [Groovy 2.5 features & Groovy 3+ Roadmap](https://speakerdeck.com/paulk/groovy-roadmap)
* [Macro method examples](https://github.com/touchez-du-bois/akatsuki/tree/master/src/main/java/org/jggug/magica/akatsuki)
* [Launching the Micro Future](https://github.com/micronaut-projects/presentations/blob/master/Gr8conf-2018.md)
* [Functional Groovy](https://speakerdeck.com/paulk/functional-groovy)
* [Making your testing Groovy](https://speakerdeck.com/paulk/make-your-testing-groovy)
* [AST Transform Magic Revealed](https://docs.google.com/presentation/d/1D4B0YQd0_0HYxK2FOt3xILM9XIymh-G-jh1TbQldbVA/edit?usp=sharing)
* [Grails Security Options](https://docs.google.com/presentation/d/17nHhrMuN5eLM5gpY6Y5GVJGOmjkaWQWylXnvQjxAIZg/edit?usp=sharing)
* [6 things you need to know about GORM6](https://www.slideshare.net/alvarosanchezmariscal/6-things-you-need-to-know-about-gorm-6)
  * [GitHub](https://github.com/alvarosanchez/gorm-gr8conf-us-2018)
* [asynchronous and eventdriven grails applications](https://www.slideshare.net/alvarosanchezmariscal/asynchronous-and-eventdriven-grails-applications)
  * [Github](https://github.com/alvarosanchez/async-grails-gr8conf-us-2018/tree/master)
* [Asset Pipeline and Developing good plugins](https://github.com/davydotcom/talks)
* [HANDS ON DEBUGGING IN MICROSERVICES WITH ZIPKIN](http://beckje01.com/talks/gr8us-2018-zipkin-light.html#/)
* [High performant in-memory datasets with Netflix H0110W and High Scalable Streaming Microservices with Kafka Streams](https://github.com/rpalcolea/gr8confus-2018-presentations)
  * [hollow demos](https://github.com/rpalcolea/gr8confus-2018-hollow-demos)
* [Add some Groovy magic to your Java project](https://speakerdeck.com/olgamaciaszek/gr8conf-us-2018-add-some-groovy-magic-to-your-java-project-why-where-and-how-to-leverage-groovy-in-a-java-codebase)
* [Creating and testing REST and Messaging Contracts with Spring Cloud Contract](https://speakerdeck.com/olgamaciaszek/talk-creating-and-testing-rest-and-messaging-contracts-with-spring-cloud-contract)
* [Better Know a Grails Plugin](https://gingkoapp.com/better-know-a-grails-plugin.impress#/step-1)
* [configuration-demo](https://github.com/jameskleeh/configuration-demo)

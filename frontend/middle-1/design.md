#Базовые принципы проектирования

* Что такое инкапсуляция? Какова мотивация для улучшения уровня инкапсуляции?
* Что такое абстрагирование? Какие есть отличия между абстракцией, инкапсуляцией и скрытием информации?
* Что такое Coupling? Как инкапсуляция влияет на это?
* Что такое Cohesion? Является ли эта величина обратной величине Coupling?
* Simplicity
  * Что такое принцип KISS?
  * В чем отличие Simple от Easy?
  * Как KISS помогает в формировании ментальных моделей? В чём ценность этих моделей?
  * Как участие в разработке требований от бизнеса может помочь следованию KISS?
  * Когда абстрагирование противоречит KISS?
  * Почему наследование может приводить к нарушению KISS?
  * Может ли полиморфизм приводить к нарушению KISS?
  * Что такое принцип YAGNI? Как он соотносится с принципом KISS?
* DRY
  * В чём основная идея принципа DRY?
  * Как принцип связан с Cohesion?
  * Как принцип связан с принципом SRP?
  * Почему этот принцип неразрывно связан с SPOT (Single point of truth)?
  * Какие есть примеры дублирования кода, которые не нарушают DRY?
  * Какие есть примеры копирования кода бизнес-логики, которые также не нарушают DRY?
  * Как следование принципу DRY может привести к нарушению KISS?
  * Как следование принципу DRY может привести к Premature Generalization?
  * Как вы объясните фразу "Duplication is far cheaper than the wrong abstraction."?
* Что такое Separation of concerns?
* Что такое Cross-cutting concerns? Что значит coarse-grained и fine-grained ответственность?

# Ресурсы
* [Abstraction, Encapsulation, and Information Hiding](http://www.tonymarston.co.uk/php-mysql/abstraction.txt)
* [Difference between Abstraction and Encapsulation](https://www.guru99.com/difference-between-abstraction-and-encapsulation.html#2)
* [The DRY Principle Explained: Its Benefit and Cost with Examples](https://thevaluable.dev/dry-principle-explained/) [[RUS](https://habr.com/ru/company/mailru/blog/349978/)]
* [ The Wrong Abstraction 0](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)
* [A Detailed Explanation of The KISS Principle in Software](https://thevaluable.dev/kiss-principle-explained/)
* [Simple Made Easy — talk of Rich Hickey](https://www.infoq.com/presentations/Simple-Made-Easy/)
* [The Art of Separation of Concerns](http://aspiringcraftsman.com/2008/01/03/art-of-separation-of-concerns/)
* [Cross cutting concern example on SO](https://stackoverflow.com/questions/23700540/cross-cutting-concern-example)
* [Cross cutting concern on Wiki](https://en.wikipedia.org/wiki/Cross-cutting_concern)
* [Coarse-grained vs fine-grained on SO](https://stackoverflow.com/questions/3766845/coarse-grained-vs-fine-grained)
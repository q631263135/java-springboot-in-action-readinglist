# readinglist
## springboot实战中的演示项目
### 开发第一个应用程序
>在本书中，我们会构建一个简单的阅读列表应用程序。在这个程序里，用户可以输入想读的
图书信息，查看列表，删除已经读过的书。我们将使用Spring Boot来辅助快速开发，各种繁文缛
节越少越好。
开始前，我们需要先初始化一个项目。在第1章里，我们看到了好几种从Spring Initializr开始
Spring Boot开发的方法。因为选择哪种方法都行，所以要选个最合适的，着手用Spring Boot开发
就好了。
从技术角度来看，我们要用Spring MVC来处理Web请求，用Thymeleaf来定义Web视图，用
Spring Data JPA来把阅读列表持久化到数据库里，姑且先用嵌入式的H2数据库。虽然也可以用
Groovy，但是我们还是先用Java来开发这个应用程序吧。此外，我们使用Gradle作为构建工具。
无论是用Web界面、Spring Tool Suite还是IntelliJ IDEA，只要用了Initializr，你就要确保勾选
了Web、Thymeleaf和JPA这几个复选框。还要记得勾上H2复选框，这样才能在开发应用程序时使
用这个内嵌式数据库。

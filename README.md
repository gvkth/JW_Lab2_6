# JW_Lab2_6
Thử nghiệm cài đặt DI bằng Constructor Injection, Setter Injection, hay Field Injection

<bean id="myCoach"
class="BaseballCoach">
<!-- set up constructor injection -->
<constructor-arg ref="myFortune" />
</bean>
<bean id="myFortune" class="HappyFortuneService"></bean>

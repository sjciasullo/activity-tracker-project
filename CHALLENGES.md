# Challenges

#### Multilingual Date object support across PostgreSQL, Spring (Java), and React (JS)
- (FAIL) attempt DateTimeFormat annotation [approach](https://codingexplained.com/coding/java/spring-framework/date-parameter-in-spring-mvc-controller)
- (SUCCESS) use [java.sql.Date](http://www.baeldung.com/hibernate-date-time) type in controller
- Will this work coming in with JS date type?
  - JS date's month (and java.util.Date) is 0 based !?!?!?
  - [get string of current date](https://www.codexworld.com/how-to/get-current-date-time-using-javascript/)
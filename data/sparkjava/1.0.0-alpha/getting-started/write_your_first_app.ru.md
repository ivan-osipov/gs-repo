# Write your first app #

{{ dependency_for_the_latest_version }}

```kotlin
import spark.kotlin.*

fun main(args: Array<String>) {
    val http: Http = ignite()

    http.get("/hello") {
        "Hello Spark Kotlin!"
    }
}
```
## Run and view

```
http://localhost:4567/hello
```
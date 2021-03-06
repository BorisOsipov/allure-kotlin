## Contributing 

We love pull requests from everyone. 

Fork, then clone the repo:

```bash
$ git clone git@github.com:your-username/allure-kotlin.git
```

Then build the project (build requires JDK 1.6 or higher):

```bash
$ ./gradlew build -x :samples:junit4-android:testReleaseUnitTest -x :samples:junit4-android:testDebugUnitTest
```

Make your change. Add tests for your change. Make sure all the tests pass:

```bash
$ ./gradlew test -x :samples:junit4-android:testReleaseUnitTest -x :samples:junit4-android:testDebugUnitTest
```

Push your fork and submit a pull request.
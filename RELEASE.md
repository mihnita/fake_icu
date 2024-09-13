# This is a test only and contains nothing

We are pleased to announce the release candidate for Unicode® ICU 76. It updates to [CLDR 46](https://cldr.unicode.org/index/downloads/cldr-46).
C++ code now requires C++17 and is being made more robust.

The Unicode data is updated to 16.0.0.

The CLDR MessageFormat 2.0 specification is now in [technology preview](https://github.com/unicode-org/message-format-wg?tab=readme-ov-file#messageformat-2-technical-preview), together with a corresponding
update of the ICU4J (Java) tech preview and a new ICU4C (C++) tech preview.

For details, please see https://icu.unicode.org/download/76.

Please test this release candidate on your platforms and report bugs and regressions by Monday, 2024-apr-15, via the [icu-support](https://icu.unicode.org/contacts) mailing list, and/or please [find/submit error reports](https://icu.unicode.org/bugs).

Please do not use this release candidate in production.

The preliminary API reference documents are published on [unicode-org.github.io/icu-docs/](https://unicode-org.github.io/icu-docs/) – follow the “Dev” links there.


##  ICU4J Artifacts

Links to Maven Central, with dependencies ready to copy/paste in maven, gradle, etc:
* https://mvnrepository.com/artifact/com.ibm.icu/icu4j/75.1
* https://mvnrepository.com/artifact/com.ibm.icu/icu4j-charset/75.1
* https://mvnrepository.com/artifact/com.ibm.icu/icu4j-localespi/75.1

---

Direct links to the release .jar files, as a list:

* [`icu4j-75.1.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar.sha1))
    * [`icu4j-75.1-javadoc.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar.sha1))
    * [`icu4j-75.1-sources.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar.sha1))
* [`icu4j-charset-75.1.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar.sha1))
    * [`icu4j-charset-75.1-javadoc.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar.sha1))
    * [`icu4j-charset-75.1-sources.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar.sha1))
* [`icu4j-localespi-75.1.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar.sha1))
    * [`icu4j-localespi-75.1-javadoc.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar.sha1))
    * [`icu4j-localespi-75.1-sources.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar) ([`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar.asc), [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar.md5), [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar.sha1))

---

Or a table:

| Artifact | GPG Signature | MD5 Checksum | SHA1 Checksum |
| -------- | ------------- | ------------ | ------------- |
| [`icu4j-75.1.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1.jar.sha1) |
| &#xa0; &#xa0; &#xa0; &#xa0; [`icu4j-75.1-javadoc.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-javadoc.jar.sha1) |
| &#xa0; &#xa0; &#xa0; &#xa0; [`icu4j-75.1-sources.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j/75.1/icu4j-75.1-sources.jar.sha1) |
| [`icu4j-charset-75.1.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1.jar.sha1) |
| &#xa0; &#xa0; &#xa0; &#xa0; [`icu4j-charset-75.1-javadoc.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-javadoc.jar.sha1) |
| &#xa0; &#xa0; &#xa0; &#xa0; [`icu4j-charset-75.1-sources.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-charset/75.1/icu4j-charset-75.1-sources.jar.sha1) |
| [`icu4j-localespi-75.1.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1.jar.sha1) |
| &#xa0; &#xa0; &#xa0; &#xa0; [`icu4j-localespi-75.1-javadoc.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-javadoc.jar.sha1) |
| &#xa0; &#xa0; &#xa0; &#xa0; [`icu4j-localespi-75.1-sources.jar`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar) | [`.asc`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar.asc) | [`.md5`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar.md5) | [`.sha1`](https://repo1.maven.org/maven2/com/ibm/icu/icu4j-localespi/75.1/icu4j-localespi-75.1-sources.jar.sha1) |


# XmltoCsv_StackExchange

A **PySpark** notebook to convert XML files to CSV format. I needed the [Stack Exchange Data Dump](https://archive.org/details/stackexchange) in CSV format for my project. All the converters available online are good for small files but when you have **xmls ranging from hundreds of MB to GB,** they were taking too much time.
<br><br>
This one works in parallel, utilizing Spark's RDDs and complete the conversion in few minutes with a minimal 2-core and 2 GB RAM Spark setup.

[![HitCount](http://hits.dwyl.com/adich23/XmltoCsv_StackExchange.svg)](http://hits.dwyl.com/adich23/XmltoCsv_StackExchange)

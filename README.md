# Code and data from the UC Berkeley Fung Institute

## Code repositories


* The most current fork of the [Python preprocessor](https://github.com/doolin/patentprocessor).
* Latest [disambiguation code](https://bitbucket.org/doolin/disambiguator/).

Both the preprocessor and the disambiguation code will get forked into
Fung Institute github repos in late 2012 or 2013. The repos above are the
best ones to fork for contributing at the moment.


## File Downloads

* [Full September 4, 2012 disambiguation](https://s3.amazonaws.com/funginstitute/full.sqlite3)

SQLite databases uploaded after November 17 will reflect schema
updates with respect to the data originally distributed via the Harvard
Dataverse Network. These schema updates will transition to SQL standards
compliant, as implemented by PostgresQL. Schema migration is likely to
continue through 2013 as the data are prepared and delivered for access via
a web-accessible API. When in doubt about schemas, examine specific file
timestamps.

* [patent.sqlite3 October 15, 2012](https://s3.amazonaws.com/funginstitute/patent.sqlite3)
* [class.sqlite3 October 15, 2012](https://s3.amazonaws.com/funginstitute/class.sqlite3)



## Applications and APIs

A prototype API server is under development right now (November 6, 2012).
A lightweight application is being built on top of the API, and serves
as a proof-of-concept. The anticipated development looks like this:

1. Combined application and API for developing use cases.
2. API for serving parsed, cleaned, consolidated  & disambiguated patent 
data split from application as an independent service.
3. Prototype consumes json via API from patent service.

Prototype application will be operating by close of 2012.

---

Note: there are RSS feeds available for all the repositories.
Feel free to follow along in the RSS reader of your choice.

---

Markdown code test:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

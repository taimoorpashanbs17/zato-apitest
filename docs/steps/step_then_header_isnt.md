
Then header "{header}" isn't "{value}"
=============================================================================================================

Usage example
-------------

```
Feature: zatoapi-test docs

Scenario: Then header "{header}" isn't "{value}"

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/json"
    Given format "JSON"

    When the URL is invoked

    Then header "Content-Type" isn't "text/csv"
```

Discussion
----------

(None)
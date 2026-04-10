# Bug Report

| Bug ID | Bug Title | Steps to reproduce | Expected result | Actual result |
----------------------------------------------------------------------------------------------------
| BG01 | Send post request with not complete field | set body with field empty title | status 400, it should be rejected because the title is empty | status 201, API accept the request |

| BG02 | Send post request with no body | send post request without body | status 400, it should be rejected because there's no body | status 201, API accept the request |

| BG03 | Send post request with just 1 body | set body with just title field | status 400, it should be rejected because there's n0 body and user_id | status 200, API accept the request |

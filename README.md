# ideal-postcodes-openapi
An OpenAPI (2.0) specification of the IdealPostcodes API with normalization for integration in platforms such as ScribeSoft

Note that there is a missing endpoint due to the lack of ability to use `oneOf` in the schema specification for the `keys/:key` endpoint. Specifically, the variation where you may pass the querstring `user_token` in order to get the details for the specific key rather than checking it's availability before making a request.

This document may be converted to OpenAPI 3.0 to support this additional endpoint, but you will lose the ability to integrate into more restrictive platforms that do not yet support this version of the OpenAPI initiative.

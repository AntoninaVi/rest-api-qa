# REST API Checklist

## GET Requests

- [ ] Send request with valid resource ID
- [ ] Send request with invalid resource ID
- [ ] Send request with non-existing resource ID
- [ ] Check response status code
- [ ] Check response body
- [ ] Check response headers
- [ ] Check Content-Type
- [ ] Check query parameters where available

## POST Requests

- [ ] Create resource with valid data
- [ ] Check created resource data
- [ ] Send request with missing required field
- [ ] Send request with empty required field
- [ ] Send request with invalid data type
- [ ] Send request with unexpected field
- [ ] Check response status code
- [ ] Check response body

## PUT / PATCH Requests

- [ ] Update resource with valid data
- [ ] Update one field
- [ ] Update multiple fields
- [ ] Update non-existing resource
- [ ] Send invalid field value
- [ ] Check updated response data

## DELETE Requests

- [ ] Delete existing resource
- [ ] Delete non-existing resource
- [ ] Check response status
- [ ] Try to retrieve deleted resource

## Response Validation

- [ ] Check status code
- [ ] Check Content-Type
- [ ] Check required response fields
- [ ] Check field data types
- [ ] Check null values
- [ ] Check response structure
- [ ] Check response time

## Negative Testing

- [ ] Missing required parameter
- [ ] Invalid parameter value
- [ ] Invalid data type
- [ ] Empty request body
- [ ] Malformed request body
- [ ] Non-existing endpoint
- [ ] Unsupported HTTP method

## Postman

- [ ] Create environment variables
- [ ] Store resource ID in variable
- [ ] Use variable in another request
- [ ] Add status code test
- [ ] Add response field test
- [ ] Add response time test
- [ ] Add basic schema validation

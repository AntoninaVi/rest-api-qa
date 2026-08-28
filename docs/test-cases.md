# REST API Test Cases

## TC-API-01 — Get existing resource

**Method:** GET

**Precondition:** A valid resource ID exists.

**Steps:**
1. Send GET request using a valid resource ID.

**Expected result:**
- Successful response is returned.
- Correct resource is present in the response body.
- Response structure is valid.

**Status:** Not Run

---

## TC-API-02 — Get non-existing resource

**Method:** GET

**Steps:**
1. Send GET request using a non-existing resource ID.

**Expected result:**
The API returns an appropriate response for a resource that does not exist.

**Status:** Not Run

---

## TC-API-03 — Create resource with valid data

**Method:** POST

**Steps:**
1. Send POST request with valid request body.

**Expected result:**
- Resource creation is accepted.
- Response contains expected resource data.

**Status:** Not Run

---

## TC-API-04 — Create resource without required field

**Method:** POST

**Steps:**
1. Remove a required field from the request body.
2. Send the request.

**Expected result:**
The API rejects the invalid request and returns an appropriate error response.

**Status:** Not Run

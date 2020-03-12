---
# This file is automatically generated from the API using `api-docs/generate.py`
# Do not manually this file.
{
  "api_path": "/api/0/projects/{organization_slug}/{project_slug}/tags/{key}/values/", 
  "authentication": "required", 
  "description": "Return a list of values associated with this key.  The `query`\nparameter can be used to to perform a \"contains\" match on\nvalues.", 
  "example_request": "", 
  "example_response": "", 
  "method": "GET", 
  "parameters": null, 
  "path_parameters": [
    {
      "description": "the slug of the organization.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the slug of the project.", 
      "name": "project_slug", 
      "type": "string"
    }, 
    {
      "description": "the tag key to look up.", 
      "name": "key", 
      "type": "string"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 18, 
  "title": "List a Tag's Values", 
  "warning": null
}
---
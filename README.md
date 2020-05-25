# gcp-functions-apigee
Apigee with GCP cloud functions as backend using Auth extension for tokens.

## Instructions

### GCP Project
1. Create GCP Project
2. Create Cloud function
3. Provide access to service account
   1. select function
   2. Show info panel
   3. Add member
   4. enter service account
   5. Select role - cloud functios invoker
4. Import API
5. Create Auth extension with service account key
6. Create cache resource, API product, app
7. Update API with your project, region, function name
8. Use curl below to invoke API

### Usage
```
    curl https://org-env.apigee.net/cfbqtest?apikey=<you-key>
```



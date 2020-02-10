# LambdaDynamoDataModelService
This is a CRUD service for interacting with objects stored in DyanmoDB via Lambdas

# Instructions

package.json:
  "name": "!!REPLACE-server",  // Should be plural version of model name such as emails-server not email-service
  "description": "This is the server side code to manipulate the !!REPLACE data model.", // Should be the singular version of the model name suc has email not emails

serverless.yml:
  custom:
    saasName: '!!REPLACE' // Should be lowercase name of the website/saas
    model: '!!REPLACE' // Should be the plural version of the model name such as emails not email

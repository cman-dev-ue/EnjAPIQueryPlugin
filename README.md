# EnjinAPIPlugin
Documentation for the Enjin API Plugin on the UE Marketplace

With the plugin you can easily create Queries for the GraphQL Enjin API.
All you need to do can be explained in a few steps :
- Create an Enjin Generic Query
- Bind an event to get the result from the request
- Send the request
- Get the result

## A few words about the Enjin generic query parameters :
- In App Token : It's an optional token that you will need to do specific requests. You can get it by sending a specific request to the Enjin API
- In Type : Can be query or mutation. According to GraphQL specifications
- In URL : The URL where you will be sending the request
- In Name : The name of the request that you want to send. You can easily find it on the GraphQL Enjin API documentation
- In Input Parameters : The parameters if there are in a GraphQL format
- In Expected Object Type : The type of Object that will be returned by the Enjin API. You can find it on the GraphQL Enjin API documentation where you see all the requests
- In Query Return : The parameters you want to get from the query as GraphQL parameters. Here you can set any parameter you want with GraphQL syntax

## About the App token :
The App Token is a critical data and you should always make sure nobody can access it.

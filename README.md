# EnjAPIQuery Plugin
![image](https://user-images.githubusercontent.com/89269028/130444264-3ab200c2-ac74-4c29-a0ba-e2d10a245c7b.png)

## Description
The  EnjAPIQuery Plugin is made to help game developers using Unreal Engine to send queries to the Enjin GraphQL API.

You will be able to access Enjin's Mainnet, Jumpnet and Kovan Testnet with this plugin.

> Cryptocurrency is growing more and more and 2021 is the year of NFT's!
>
> It's time for you to upgrade or create your own game by combining Enjin's based gaming platform and the powerful Unreal Engine!
>
> Enjin is making it accessible to anyone to create a NFT game today.
>
> Create tokens that can be used across multiple video games & platforms from PC to mobile at ease thanks to the EnjAPIQuery Plugin. Allow your players to have true item ownership of their in-game items! Fear no gas fee and low speed transactions thanks to the Enjin Jumpnet.

By using this plugin you will be able to use the Enjin API with Blueprints!

- Link your wallet with QR code
- Create NFT
- Mint NFT
- Send and Receive NFT
- Access the Metadata stored in the NFT
- Send ENJs
- And more...

## Documentation
With the plugin you can easily create Queries for the GraphQL Enjin API.

It only takes a few steps to create a query, send it and get the result:

- Create an Enjin Generic Query or Enjin Generic Array Query, the parameters are the same as the Enjin generic query except it will return an array

![image](https://user-images.githubusercontent.com/89269028/130332918-4563b6b3-21ce-45be-bf14-03defcadd47a.png)

- Bind an event to get the result (fail/success) from the request

![image](https://user-images.githubusercontent.com/89269028/130332860-4028180c-7199-4937-af2c-e5291b082eba.png)

- Send the request

![image](https://user-images.githubusercontent.com/89269028/130328020-d455f593-590e-4c6d-ac2e-82c8814ea5e6.png)

- Get the result

![image](https://user-images.githubusercontent.com/89269028/130332889-2ff82c96-7b34-46d2-aef8-ebdc93ce18c9.png)

Depending on which query you used you will get the GraphQLObject filled or the Array GraphQLObjects

![image](https://user-images.githubusercontent.com/89269028/130327986-a3790acb-460a-4cef-a2b2-b65d40294c43.png)

You can access any of the properties of the object by simply calling a Get function!

Please report any missing parameter or incorrect parameter. 

### A few words about the Enjin generic query parameters
- `In App Token` : It's an optional token that you will need to do specific requests. You can get it by sending a specific request to the Enjin API
- `In Type` : Can be `query` or `mutation`. According to GraphQL query you are sending
- `In URL` : The URL where you will be sending the request
- `In Name` : The name of the request that you want to send. You can easily find it on the Enjin GraphQL API documentation
- `In Input` Parameters : The parameters if there are in a GraphQL format
- `In Expected Object Type` : The type of Object that will be returned by the Enjin API. You can find it on the Enjin GraphQL API documentation where you see all the requests
- `In Query Return` : The parameters you want to get from the query as GraphQL parameters. Here you can set any parameter you want with GraphQL syntax

![image](https://user-images.githubusercontent.com/89269028/130444325-b03c417e-dfb2-40c9-8aa8-763025cf9401.png)

### About the App token
The App Token is a critical data and you should always make sure nobody can access it.

### Enjin GraphQL documentation
You can find all the queries that you can make on the Enjin GraphQL API (Mainnet, Jumpnet, Kovan Testnet).

### Links
- Discord support server : https://discord.gg/49m4aZeYRZ
- Enjin Website : https://enjin.io/
- Enjin Mainnet : https://cloud.enjin.io/graphiql/
- Enjin Kovan Testnet : https://kovan.cloud.enjin.io/graphiql
- Enjin Jumpnet : https://jumpnet.cloud.enjin.io/graphiql

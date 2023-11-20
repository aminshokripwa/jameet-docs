# Jameet API

A set of tools to add features, services or more information with the help of Jameet API
## Start
To use Jameet features, you must have an account at (https://jameet.com/dashboard).
In the Jameet panel, you create the required key to call the APIs, at any moment you can replace the previous key with a new key, but you must replace this key in your application.

## App Management
Each user account can define a key and provide its services to users through them. Each key can provide multiple names, profile images, and different services.
See the details of application specifications and its management in [app management page](./app_analytics).

## Server Key
Each application can have API keys with different accesses and send requests to Jameet through them.
This key must be sent in the `server-key` header along with all requests that are sent to the side.

To create a new key or edit the permissions of existing keys, after logging in to the panel, go to the [API Keys page](https://jameet.com/your_app).

Use the ''Generate Server Key'' button to create a new key. Create a new key by selecting your app and selecting the required permissions.
* Use the `server-key' header to send the key.
* You can see and change API keys at any time.
* The responsibility of improper use of API and access is with the owner of the application
* Every user of your application has a key that can be used as a token after logging in, so that all requests of this user related to this token are sent from the `jmt-token' header.

## Steps
> in Create Login Verify User folder
1. Create user
2. Verify user's email
3. Login User
4. Chat/Post/Story/User/Follow/Privacy/Notifications

## List
- [Create Login Verify User](./Create_Login_Verify_User)
- [Chat](./Chat)
- [Post](./Post)
- [Story](./Story)
- [User](./User)
- [Follow](./Follow)
- [Privacy](./Privacy)
- [Notifications](./Notifications)
- [Admin](./Admin)

## Postman(Online)
>In the link below, you can view the online document and enter it into Postman software.
[Online Postman Documnet](https://documenter.getpostman.com/view/12464310/2s9Ye8guxC).
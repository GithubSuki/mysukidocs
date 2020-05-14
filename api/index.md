# API Documentation for Project Sari

updated by Victor Javier

Project Sari is a platform that allows mom-and-pop retailers (Sari Sari Stores) to order groceries goods from vendors ( wholesellers) such as supermarkets and distributors directly. This document explains how client application can connect to the platform, access vendor product list and submit orders.

- [My Profile](/my_profile.md)
- [Mobile Authentication](/mobile.auth.md)

Vendor API's:

- [Product Upload API](/vendor/products_upload.md)
- [Picking API](/vendor/picking.md)
- [Driver API](/vendor/driver_api.md)
- [Device API](/vendor/device.md)

## API End Point

- The API is developed using REST approach.
- Current API end point: https://project-sari/herokuapp.com/c/api
- Example: To get list of available vendors https://project-sari/heroku.com/c/api/vendors/

## Security

To secure the API, user needs to signup and login. Please see next section. Upon login, the API will return a token. You shuold include the token in the header section of your API call.

Example:

```javascript
header: {
  Authentication: "Bearer {token}";
}
```

## Signup

To sign up using API.

```javacript

```

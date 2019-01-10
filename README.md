<<<<<<< HEAD
# NativePrototype

[Amplify CLI Documentation](https://aws-amplify.github.io/docs/cli/init?sdk=js)

[Amplify Auth API Getting Started](https://aws-amplify.github.io/docs/js/authentication)

[Amplify Auth API Documentation](https://aws-amplify.github.io/amplify-js/api/classes/authclass.html)

[React Navigation API Documentation](https://reactnavigation.org/docs/en/hello-react-navigation.html)

[React Native Elements API Documentation](https://react-native-training.github.io/react-native-elements/docs/getting_started.html)

[Async Await Docs From JavaScript.info](https://javascript.info/async-await)

[Expo Docs](https://docs.expo.io/versions/latest/workflow/expo-cli)

Must be running 8.0.0+ NPM
```bash
$ git clone https://github.com/paranoia1906/NativePrototype.git

$ npm install -g @aws-amplify/cli
$ amplify configure

$ npm install -g expo-cli
$ expo login|signin [options]

$ npm install
=======
# LambdaGetSiteInfo

### JSON Object fetched.
```javascript
{ address: '3000 Main St.',
  hours: '9: 00 AM - 5: 00 PM Mon - Fri',
  phone: '1 800 555 7777',
  email: 'anthony@ledesma.tech'
}
```

### Response out of Lambda.
```javascript
{ statusCode: 200,
  body: '{
        "address": "3000 Main St.",
        "hours": "9:00 AM - 5:00 PM Mon - Fri",
        "phone": "1 800 555 7777",
        "email": "anthony@ledesma.tech"
    }'
}
>>>>>>> lambdamongo/master
```
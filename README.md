# cloudfront-deploy

```javascript
const config = {
  resourcePrefix: 'petergeorgantascom',
  cloudfrontOriginAccessIdentity: {
    id: 'E2Z5QS0HZPP4XG',
    s3CanonicalUserId: '1b81d33fb41258444d137694ba870321badb3d8cb44c58ba3bef386cab8e2379b76ce90bd8a05f82c9bd509e599c5146'
  },
  defaultRootObject: 'index.html',
  mainDomain: {
    name: 'petergeorgantas.com',
    hostedZoneName: 'petergeorgantas.com'
  },
  alternameDomains: [{
    name: 'www.petergeorgantas.com',
    hostedZoneName: 'petergeorgantas.com'
  }]
};
```

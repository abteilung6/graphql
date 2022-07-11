query fragments

```
{
  apple: company(id: "1") {
    ...companyDetails
  }
}

fragment companyDetails on Company {
  id,
  name,
  description
}
```

mutation

```
mutation {
  addUser(firstName:"Steven", age: 29) {
    id,
    firstName,
    age
  }
}
```

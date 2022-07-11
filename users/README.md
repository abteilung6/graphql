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

add mutation

```
mutation {
  addUser(firstName:"Steven", age: 29) {
    id,
    firstName,
    age
  }
}
```

delete mutation

```
mutation {
  deleteUser(id: "23") {
    id
  }
}
```

edit mutation

```
mutation {
  editUser(id:"23", firstName: "foo") {
    firstName,
    age,
  }
}
```

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

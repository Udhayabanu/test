# This package is to get the access token to access salesforce services.

## Things to consider
- Input parameters to pass and its type
- Exceptions to handle while using thi package

### Input parameters

you have to pass 2 varibale as method parameters 

- The Authorization server URL as type String 
- Client credentials configuartion as type dictionary

Here is the sample parameter that you have to pass and fill the value

>
> the dictionary parameter should contain all the key as specified below 
> 

```sh

auth_sever_url=""

auth_sever_config={
'salesforce_private_key':'',
'salesforce_private_key_passphrase':'',
'salesforce_jwt_iss':'',
'salesforce_endpoint':'',
'salesforce_jwt_prn':'',
'salesforce_jwt_algorithm':'',
'salesforce_grant_type_bearer':''
}
```

### Exceptions

- you have to handle the TypeError and ValueError on your code if you are not passing incomplete value
>>>>>>> 365002e (frirst commit)

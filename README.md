## Check-whether-following-json-is-valid-or-invalid.-If-Invalid-correct-it
## Sample code 
```sh
def validateJSON(jsonData):
    try:
        json.loads(jsonData)
    except ValueError as err:
        return False
    return True
```
## Expected output
Given JSON string is Valid False
    
    
    

## Account Table
```bash
aws --region us-east-1 cloudformation create-stack --stack-name ti-account-table --template-body file://ti-account-table.yaml
```

## Investiments Table
```bash
aws --region us-east-1 cloudformation create-stack --stack-name ti-investiments-table --template-body file://ti-investiments-table.yaml
```


## Stocks Table
```bash
aws --region us-east-1 cloudformation create-stack --stack-name ti-stocks-table --template-body file://ti-stocks-table.yaml
```
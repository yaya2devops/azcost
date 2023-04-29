# Azure Costs From CLI

[Install the tool](https://github.com/mivano/azure-cost-cli#installation)

- **Print Costs**

```
azure-cost accumulatedCost -s e526ca44-ef99-496e-8ca7-5c80e3c6e763 --debug
```

- **And output JSON**
```
azure-cost accumulatedCost -s e526ca44-ef99-496e-8ca7-5c80e3c6e763 -o json
```

- **Direct to JSON file**
```
azure-cost show -s e526ca44-ef99-496e-8ca7-5c80e3c6e763 -o json > cost.json
```
- **Direct to Text file**
```
azure-cost costByResource -s e526ca44-ef99-496e-8ca7-5c80e3c6e763 -o text
```

- **Direct to Markdown file**
```
azure-cost show -s e526ca44-ef99-496e-8ca7-5c80e3c6e763 -o markdown > cost.md
```

- **Query from yesterday**
```
azure-cost -s e526ca44-ef99-496e-8ca7-5c80e3c6e763 -o json --query "totals.yesterdayCost"
```


- Query by Azure Costs
<img src="costs-april-azure-ngcsc.png">


> [cause](https://www.linkedin.com/feed/update/urn:li:activity:7058067925382918144/)

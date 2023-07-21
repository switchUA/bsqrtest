# bsqrtest
Repo for pre interview test task

## How to apply and test:
1. Go to aws console and create new stack from template.
2. chose cloudformation.yaml file from this repo as a template
3. After creation of stack you can upload few files to newly created bucket
4. Run lambda function to see result

## Improvements: 
1. Parametrize lambda name, s3 bucket name
2. Add information how to apply and use it without web console, use awscli instead 
3. Probably add trigger, so lambda triggers whenever new files were upload so we always have latest presigned url(in current implementation it requires manual trigger of lambda)


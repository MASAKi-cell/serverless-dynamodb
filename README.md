# serverless-dynamodb


#### ■ serverless-dynamodb-local 公式ドキュメント： https://www.npmjs.com/package/serverless-dynamodb-local
#### ■ DynamoDB Resource definitions：https://www.serverless.com/framework/docs/providers/aws/guide/resources/#configuration <br>

#### DynamoDBパッケージをインストール<br>

```
npm install --save serverless-dynamodb-local<br>
```

#### serverless.ymlに設定を追加
```
plugins:
  - serverless-dynamodb-local
```

#### DynamoDB localをインストール

```
sls dynamodb install
```

#### DynamoDBを起動

```
sls dynamodb start
```

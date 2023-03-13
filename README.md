# openapi

## oapi-codegen

このディレクトリは以下の記事の学習のために作成しました。  
[[Go] OpenAPI コード自動生成でビジネスロジックに集中する開発へ](https://qiita.com/nyanchu/items/1c259750352b49e96a18)

## openapi-generator

このディレクトリは以下の記事の学習のために作成しました。  
[OpenAPIからGo言語のコードを自動生成してくれるツールを試してみた](https://zenn.dev/rescuenow/articles/3c9a19eb2c0655#openapi-generator)

```
docker run --rm -v <パス>:/local openapitools/openapi-generator-cli generate -i /local/api.yaml -g go-echo-server -o /local/openapi-generator
```
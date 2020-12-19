### Mock 時のエラー回避

amplify/backend/function/createPostAndTimeline/createPostAndTimeline-cloudformation-template.json

```
{
    "permissions": {
        "api": {
            "BoyakiGql": [
                "create",
                "read"
            ]
        }
    },
    "apiBoyakiGqlGraphQLAPIIdOutput": "",
    "apiBoyakiGqlGraphQLAPIEndpointOutput": ""
}
```

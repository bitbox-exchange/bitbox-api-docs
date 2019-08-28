# Server time

Gets the server's current time in milliseconds since Unix Epoch in UTC.

> **Note**
>
> Only `X-API-Key` is required in the request header for this API.

## Endpoint URI

```
GET https://openapi.bitbox.me/v1/public/time
```

## Request parameters

None

## Response

| Name           | Description                                                   | Type   | Included |
| -------------- | ------------------------------------------------------------- | ------ | -------- |
| `timezone`     | The time standard for the `responseTime`. It is always "UTC". | String | O        |
| `responseTime` | The time when it responds. <br/>It is a timestamp in milliseconds since Unix Epoch in UTC. | Long | O |

**A response example**

``` json
{
  "timezone": "UTC",
  "responseTime": 1527747579424
}
```

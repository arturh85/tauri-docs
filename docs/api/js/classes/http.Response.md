[@tauri-apps/api](../README.md) / [http](../modules/http.md) / Response

# Class: Response<T\>

[http](../modules/http.md).Response

Response object.

## Type parameters

| Name |
| :------ |
| `T` |

## Properties

### data

• **data**: `T`

The response data.

#### Defined in

[http.ts:232](https://github.com/tauri-apps/tauri/blob/13c2fc1/tooling/api/src/http.ts#L232)

___

### headers

• **headers**: `Record`<`string`, `string`\>

The response headers.

#### Defined in

[http.ts:228](https://github.com/tauri-apps/tauri/blob/13c2fc1/tooling/api/src/http.ts#L228)

___

### ok

• **ok**: `boolean`

A boolean indicating whether the response was successful (status in the range 200–299) or not.

#### Defined in

[http.ts:226](https://github.com/tauri-apps/tauri/blob/13c2fc1/tooling/api/src/http.ts#L226)

___

### rawHeaders

• **rawHeaders**: `Record`<`string`, `string`[]\>

The response raw headers.

#### Defined in

[http.ts:230](https://github.com/tauri-apps/tauri/blob/13c2fc1/tooling/api/src/http.ts#L230)

___

### status

• **status**: `number`

The response status code.

#### Defined in

[http.ts:224](https://github.com/tauri-apps/tauri/blob/13c2fc1/tooling/api/src/http.ts#L224)

___

### url

• **url**: `string`

The request URL.

#### Defined in

[http.ts:222](https://github.com/tauri-apps/tauri/blob/13c2fc1/tooling/api/src/http.ts#L222)

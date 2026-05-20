
# GrokEntity


## Properties

Name | Type
------------ | -------------
`fromIndex` | string
`ref` | [GrokEntityRef](GrokEntityRef.md)
`toIndex` | string

## Example

```typescript
import type { GrokEntity } from 'twitter-openapi-typescript-generated'

// TODO: Update the object below with actual values
const example = {
  "fromIndex": null,
  "ref": null,
  "toIndex": null,
} satisfies GrokEntity

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as GrokEntity
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)



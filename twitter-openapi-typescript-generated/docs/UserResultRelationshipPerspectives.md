
# UserResultRelationshipPerspectives


## Properties

Name | Type
------------ | -------------
`blockedBy` | boolean
`blocking` | boolean
`followedBy` | boolean
`following` | boolean

## Example

```typescript
import type { UserResultRelationshipPerspectives } from 'twitter-openapi-typescript-generated'

// TODO: Update the object below with actual values
const example = {
  "blockedBy": null,
  "blocking": null,
  "followedBy": null,
  "following": null,
} satisfies UserResultRelationshipPerspectives

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as UserResultRelationshipPerspectives
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)



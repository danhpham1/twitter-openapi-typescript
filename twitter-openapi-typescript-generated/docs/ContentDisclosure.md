
# ContentDisclosure


## Properties

Name | Type
------------ | -------------
`advertisingDisclosure` | [ContentDisclosureAdvertisingDisclosure](ContentDisclosureAdvertisingDisclosure.md)
`aiGeneratedDisclosure` | [ContentDisclosureAiGeneratedDisclosure](ContentDisclosureAiGeneratedDisclosure.md)

## Example

```typescript
import type { ContentDisclosure } from 'twitter-openapi-typescript-generated'

// TODO: Update the object below with actual values
const example = {
  "advertisingDisclosure": null,
  "aiGeneratedDisclosure": null,
} satisfies ContentDisclosure

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ContentDisclosure
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)



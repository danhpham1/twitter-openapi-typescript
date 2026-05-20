
# ArticlePreview


## Properties

Name | Type
------------ | -------------
`articleId` | number
`coverMedia` | [ArticleCoverMedia](ArticleCoverMedia.md)
`previewText` | string
`title` | string

## Example

```typescript
import type { ArticlePreview } from 'twitter-openapi-typescript-generated'

// TODO: Update the object below with actual values
const example = {
  "articleId": null,
  "coverMedia": null,
  "previewText": null,
  "title": null,
} satisfies ArticlePreview

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ArticlePreview
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)



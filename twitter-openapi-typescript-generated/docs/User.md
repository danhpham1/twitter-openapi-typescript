
# User


## Properties

Name | Type
------------ | -------------
`typename` | [TypeName](TypeName.md)
`affiliatesHighlightedLabel` | { [key: string]: any; }
`businessAccount` | { [key: string]: any; }
`creatorSubscriptionsCount` | number
`hasGraduatedAccess` | boolean
`hasHiddenLikesOnProfile` | boolean
`hasHiddenSubscriptionsOnProfile` | boolean
`hasNftAvatar` | boolean
`highlightsInfo` | [UserHighlightsInfo](UserHighlightsInfo.md)
`id` | string
`isBlueVerified` | boolean
`isProfileTranslatable` | boolean
`legacy` | [UserLegacy](UserLegacy.md)
`legacyExtendedProfile` | [UserLegacyExtendedProfile](UserLegacyExtendedProfile.md)
`parodyCommentaryFanLabel` | string
`premiumGiftingEligible` | boolean
`professional` | [UserProfessional](UserProfessional.md)
`profileImageShape` | string
`restId` | string
`superFollowEligible` | boolean
`superFollowedBy` | boolean
`superFollowing` | boolean
`tipjarSettings` | [UserTipJarSettings](UserTipJarSettings.md)
`userSeedTweetCount` | number
`verificationInfo` | [UserVerificationInfo](UserVerificationInfo.md)

## Example

```typescript
import type { User } from 'twitter-openapi-typescript-generated'

// TODO: Update the object below with actual values
const example = {
  "typename": null,
  "affiliatesHighlightedLabel": null,
  "businessAccount": null,
  "creatorSubscriptionsCount": null,
  "hasGraduatedAccess": null,
  "hasHiddenLikesOnProfile": null,
  "hasHiddenSubscriptionsOnProfile": null,
  "hasNftAvatar": null,
  "highlightsInfo": null,
  "id": null,
  "isBlueVerified": null,
  "isProfileTranslatable": null,
  "legacy": null,
  "legacyExtendedProfile": null,
  "parodyCommentaryFanLabel": null,
  "premiumGiftingEligible": null,
  "professional": null,
  "profileImageShape": null,
  "restId": null,
  "superFollowEligible": null,
  "superFollowedBy": null,
  "superFollowing": null,
  "tipjarSettings": null,
  "userSeedTweetCount": null,
  "verificationInfo": null,
} satisfies User

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as User
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)



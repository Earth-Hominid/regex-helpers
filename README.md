# regex-helpers
RegEX helpers in TypeScript

```ts
function removeSpacesAndNonAlphabeticCharacters(input: string): string {
  return input.replace(/[\s\d_,.;:\/\\|+!=@#$%^&*()'"<>?`~]/g, "");
}

```

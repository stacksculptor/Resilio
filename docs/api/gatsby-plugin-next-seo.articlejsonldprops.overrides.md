<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [gatsby-plugin-next-seo](./gatsby-plugin-next-seo.md) &gt; [ArticleJsonLdProps](./gatsby-plugin-next-seo.articlejsonldprops.md) &gt; [overrides](./gatsby-plugin-next-seo.articlejsonldprops.overrides.md)

## ArticleJsonLdProps.overrides property

An overrides object with custom article properties for the provided article type.

<b>Signature:</b>

```typescript
overrides?: Article;
```

## Remarks

This is where you can override any provided attributes.

To set the article type to a blog post pass in the following props.

```tsx
const props: ArticleJsonLdProps = {
  ...initialProps,
  extra: {
    '@type': 'BlogPosting', // Make this a blog post
  }
};

```

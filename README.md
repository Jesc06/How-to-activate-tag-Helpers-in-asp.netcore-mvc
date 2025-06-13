# How-to-activate-tag-Helpers-in-asp.netcore-mvc

### Add this to _ViewImports.cshtml to enable Tag Helpers such as asp-action, asp-controller, etc.
![Step 1](./Screenshot%2025-06-13%20153349.png)

```csharp
@addTagHelper *, Microsoft.AspNetCore.Mvc.TagHelpers
```

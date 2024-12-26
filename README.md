# rspack-problem-matchers

> Modified according to [esbuild-problem-matchers](https://github.com/connor4312/esbuild-problem-matchers)


To use this, add the rspack-watch problem matcher to your tasks.json, as appropriate. For example:

```json
{
  "version": "2.0.0",
  "tasks": [
    {
      "type": "npm",
      "script": "watch",
      "group": "build",
      "problemMatcher": "$rspack-watch",
      "isBackground": true,
      "label": "npm: watch"
    }
  ]
}
```
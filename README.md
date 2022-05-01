# Clash-of-Clans-Swagger
Using a tool like OpenApi Generator you can use this to automatically produce methods to query the API.
The swagger-source.yml file is whatever SuperCell gives us currently.
The swagger.yml file is an improved version of that.
The swagger-3.0.yaml is a rewrite in a newer OpenApi version. 
This version gives us many more features that produces better output.

C#
```
-jar pathToOpenApiGenerator.jar generate `
  -g csharp-netcore `
  -i pathToSwagger.yml `
  -c pathToGeneratorConfig.json `
  -o pathToOutputDirectory `
  -t pathToTemplatesIfDesired
```

## Disclaimer
This content is not affiliated with, endorsed, sponsored, or specifically approved by Supercell and Supercell is not responsible for it. For more information see [Supercell's Fan Content Policy](https://supercell.com/en/fan-content-policy/).
# Clash-of-Clans-Swagger
Using a tool like OpenApi Generator you can use this to automatically produce methods to query the API.  

C#
```
-jar pathToOpenApiGenerator.jar 
  generate 
  -g csharp-netcore 
  -i pathToSwagger.yml 
  -c pathToGeneratorConfig.json 
  -o pathToOutputDirectory 
  -t pathToTemplatesIfDesired
```
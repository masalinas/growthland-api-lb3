# Description

PoC Growthland API implemented by Loopback 3

## STEP01: Create models throw inverse engineering from database. Installed [loopback-discover-models](https://github.com/slively/loopback-discover-models)

node cli.js --prompt

## STEP02: export swagger.json specification file from Loopback Project

lb export-api-def -o swagger.json

## STEP03: generate C# models from swagger.json specification file. Install [swagger codegen cli](https://mvnrepository.com/artifact/io.swagger.codegen.v3/swagger-codegen-cli/3.0.19)

java -jar swagger-codegen-cli-3.0.19.jar generate -i swagger.json -l csharp

## STEP04: generate Angular Typescript from swagger.json specification file. Install [swagger codegen cli](https://mvnrepository.com/artifact/io.swagger.codegen.v3/swagger-codegen-cli/3.0.19)

java -jar swagger-codegen-cli-3.0.19.jar generate -i swagger.json -l typescript-angular
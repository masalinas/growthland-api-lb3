# Description

PoC Growthland API implemented by Loopback 3

## Create models throw inverse engineering from database

node cli.js --prompt

## export swagger from Loopback Project

lb export-api-def -o swagger.json

## generate C# models from swagger file

java -jar swagger-codegen-cli.jar generate -i swagger.json -l csharp
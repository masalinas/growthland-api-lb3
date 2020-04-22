# Description

PoC Growthland API implemented by Loopback 3

## STEP01: Create models throw inverse engineering from database. Installed loopback-discover-models package before

node cli.js --prompt

## STEP02: export swagger.json specification file from Loopback Project

lb export-api-def -o swagger.json

## STEP03: generate C# models from swagger.json specification file. Install swagger generator

java -jar swagger-codegen-cli.jar generate -i swagger.json -l csharp
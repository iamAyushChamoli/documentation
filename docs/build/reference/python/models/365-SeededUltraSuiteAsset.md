---
title: SeededUltraSuiteAsset | Python SDK
---

# SeededUltraSuiteAsset

A SeededUEAsset is the minimum data sent from UE required to create an asset within Pieces.  Fragment & file are both optional properties however we will throw an internal error if both fragment and file are passed through or if both are undefined.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_schema** | [**EmbeddedModelSchema**](EmbeddedModelSchema) |  | [optional] 
**name** | **str** | (optional) name is the name of the file | [optional] 
**ext** | [**ClassificationSpecificEnum**](ClassificationSpecificEnum) |  | [optional] 
**format** | [**SeededFormat**](SeededFormat) |  | 
**description** | **str** |  | [optional] 



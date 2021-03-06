# Message ChangeTwist

This page describes the C++ Kinova::Api::Base::ChangeTwist message.

## Overview / Purpose

Defines an action to increase \(or reduce\) the maximum Cartesian velocity by a specific increment

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|linear|float32|Linear Cartesian velocity increment \(in meters per second\)|
|angular|float32|Angular Cartesian velocity increment \(in degrees per second\)|

 **Methods** 

The methods listed below are some of the most commonly used. Please refer to Google Protocol Buffer documentation for an exhaustive list.

|Method name|Return type|Input type|Description|
|-----------|-----------|----------|-----------|
|linear\(\)|float32|void|Returns the current value of linear. If the linear is not set, returns 0.|
|set\_linear\(\)|void|float32|Sets the value of linear. After calling this, linear\(\) will return value.|
|clear\_linear\(\)|void|void|Clears the value of linear. After calling this, linear\(\) will return 0.|
|angular\(\)|float32|void|Returns the current value of angular. If the angular is not set, returns 0.|
|set\_angular\(\)|void|float32|Sets the value of angular. After calling this, angular\(\) will return value.|
|clear\_angular\(\)|void|void|Clears the value of angular. After calling this, angular\(\) will return 0.|

**Parent topic:** [Base](../references/summary_Base.md)


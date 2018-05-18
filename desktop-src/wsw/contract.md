---
title: Contract
description: A service contract carries metadata that defines how a service to handles channel messages.
ms.assetid: '670530bf-344b-4480-8357-8984d80c0c68'
keywords: ["Contract Web Services for Windows", "WWSAPI", "WWS"]
---

# Contract

A service contract carries metadata that defines how a service to handles channel messages.

## 

A [**WS\_SERVICE\_CONTRACT**](ws-service-contract.md) carries metadata for a service to handle a [WS\_MESSAGE](ws-message.md).

![](images/servicecontractintro.png)

It has a [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md) and a function table. An application can optionally specify [**WS\_SERVICE\_MESSAGE\_RECEIVE\_CALLBACK**](ws-service-message-receive-callback.md).

If a [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md) and a function table are not given, the application is required to specify [**WS\_SERVICE\_MESSAGE\_RECEIVE\_CALLBACK**](ws-service-message-receive-callback.md).

![](images/servicecontract.png)

## 

``` syntax
static WS_SERVICE_CONTRACT calculatorContract = 
{
    &calculatorContractDescription, 
    NULL, 
    &calculatorFunctions, 
};
```

See the [calculator](httpcalculatorserviceexample.md) example for details.

Contract Description

[**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md) is metadata defining the type-contract of the service. Generated by [wsutil.exe](web-service-compiler-tool.md).

In terms of WSDL, a [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md) maps to a wsdl:portType. For each wsdl:portType in the WSDL document a separate **WS\_CONTRACT\_DESCRIPTION** will be generated.

A contract description is made up of on or more [service operations](service-operation.md). These operations are given as an array of [**WS\_OPERATION\_DESCRIPTION**](ws-operation-description.md).

![](images/porttypetocontract.png)

``` syntax
<wsdl:definitions xmlns:soap="http://schemas.xmlsoap.org/wsdl/soap/" 
xmlns:wsu="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-utility-1.0.xsd" 
xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:tns="http://Example.org" 
xmlns:wsa="http://schemas.xmlsoap.org/ws/2004/08/addressing" xmlns:wsp="http://schemas.xmlsoap.org/ws/2004/09/policy" 
xmlns:wsap="http://schemas.xmlsoap.org/ws/2004/08/addressing/policy" xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:msc="http://schemas.microsoft.com/ws/2005/12/wsdl/contract" xmlns:wsaw="http://www.w3.org/2006/05/addressing/wsdl" 
xmlns:soap12="http://schemas.xmlsoap.org/wsdl/soap12/" xmlns:wsa10="http://www.w3.org/2005/08/addressing" 
xmlns:wsx="http://schemas.xmlsoap.org/ws/2004/09/mex" targetNamespace="http://Example.org" 
xmlns:wsdl="http://schemas.xmlsoap.org/wsdl/">
 <wsdl:portType name="ICalculator">
  <wsdl:operation name="Add">
   <wsdl:input wsaw:Action="http://Example.org/ICalculator/Add" 
   message="tns:ICalculator_Add_InputMessage" />
   <wsdl:output wsaw:Action="http://Example.org/ICalculator/AddResponse" 
   message="tns:ICalculator_Add_OutputMessage" />
  </wsdl:operation>
 </wsdl:portType>
</wsdl:definitions>
```

For details of wsdl:portType to [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md) conversion, see the [WSDL output section](wsdl-support.md).

Example: [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md)

``` syntax
static WS_CONTRACT_DESCRIPTION contractDescriptionICalculator =
{
    WsCountOf(serviceOperationsICalculator),
    serviceOperationsICalculator
};
```

Function Table

Function Table is an struct of function pointers representing each of the [service operations](service-operation.md) in the service contract. The function table definition is also generated by [wsutil.exe](web-service-compiler-tool.md).

Example: Function Table

``` syntax
 // Function Table
struct CalculatorServiceFunctionTable
{
      AddOperation Add;
      SubtractOperation Subtract;
};

// Populate the Function Table
static const CalculatorServiceFunctionTable calculatorFunctions = {Add, Subtract};
```

Using the [**WS\_SERVICE\_MESSAGE\_RECEIVE\_CALLBACK**](ws-service-message-receive-callback.md)

[**WS\_SERVICE\_MESSAGE\_RECEIVE\_CALLBACK**](ws-service-message-receive-callback.md) has a dual mutually exclusive role.

If a [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md) is specified on the [**WS\_SERVICE\_CONTRACT**](ws-service-contract.md), this becomes the default message handler for all the actions which are not supported by the specified **WS\_CONTRACT\_DESCRIPTION**. Otherwise, if **WS\_CONTRACT\_DESCRIPTION** is not specified on the **WS\_SERVICE\_CONTRACT**, and the [**WS\_SERVICE\_MESSAGE\_RECEIVE\_CALLBACK**](ws-service-message-receive-callback.md) is specified on the **WS\_SERVICE\_CONTRACT** all in coming [messages](ws-message.md) are passed to this callback.

For more examples, please see

-   [Untyped service example](untypedserviceexample.md)
-   [Calculator service example](httpcalculatorserviceexample.md)
-   [Service operations](service-operation.md)

The following callbacks are part of the contract:

-   [**WS\_SERVICE\_MESSAGE\_RECEIVE\_CALLBACK**](ws-service-message-receive-callback.md)
-   [**WS\_SERVICE\_STUB\_CALLBACK**](ws-service-stub-callback.md)

The following structures are part of the contract:

-   [**WS\_CONTRACT\_DESCRIPTION**](ws-contract-description.md)
-   [**WS\_SERVICE\_CONTRACT**](ws-service-contract.md)

 

 




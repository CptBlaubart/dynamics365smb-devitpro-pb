---
title: "HyperLinkHandler Attribute"
ms.custom: na
ms.date: 08/26/2019
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.service: "dynamics365-business-central"
author: jswymer
---

# HyperLinkHandler Attribute

Specifies that the method is a HyperLinkHandler method.

## Applies To  
AL test methods on test codeunits. A test method is a method that has the [Test Attribute](devenv-test-attribute.md) declared. 

## Syntax  
  
```  
[HyperLinkHandler]
procedure HyperLinkHandler(Message : Text[1024]);
```    
  
## Remarks

The **HyperLinkHandler** method is called when a hyperlink is invoked in the code.

The **HyperLinkHandler** attribute requires that the method where it is applied has the signature `HyperLinkHandler(Message: Text[1024])`. The parameter type, *Text*,  contains the actual hyperlink.

## See Also  
[Method Attributes](devenv-method-attributes.md)  
[Test Codeunits and Test Functions](../devenv-test-codeunits-and-test-methods.md)
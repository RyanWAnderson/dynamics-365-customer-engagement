---
title: "Select a template to configure forecasting"
description: "Select a template to define the hierarchy to be used in a forecast in Dynamics 365 Sales."
ms.date: 10/26/2021
ms.topic: article
author: lavanyakr01
ms.author: lavanyakr
manager: shujoshi
ms.custom: 
  - dyn365-sales
---
# Select a template 

Select a template to define the hierarchy to be used in a forecast in your organization.

## License and role requirements

| &nbsp; | &nbsp; |
|-----------------------|---------|
| **License** | Dynamics 365 Sales Premium or Dynamics 365 Sales Enterprise  <br>More information: [Dynamics 365 Sales pricing](https://dynamics.microsoft.com/sales/pricing/) |
| **Security roles** | System Administrator <br> See [Predefined security roles for Sales](security-roles-for-sales.md)|
|||

## Select template  

You can select a template to create a forecast. The selected templates populate the **Hierarchy route** field that defines the entity type in your hierarchy. However, to create a forecast based on your custom rollup and hierarchy entities, select **Create from scratch**.   

To select a template, go to the **Forecast configurations** page and select one of the following templates:

-	**Org chart forecast**: Rollup columns and projections are based on your organization's reporting structure. This template uses the **Manager** field on the **User** entity for the hierarchy.

-	**Territory forecast**: Rollup columns and projections are based on the sales territory hierarchy.

- **Product forecast**: Rollup columns and projections are based on the product hierarchy. 

> [!div class="mx-imgBorder"]
> ![Select template.](media/forecast-ce-template-selection.png "Select template")

[!INCLUDE[cant-find-option](../includes/cant-find-option.md)]


<table>
<tr><td>

> [!div class="nextstepaction"] 
> [Next step: Define general properties and scheduling](define-general-properties-scheduling-forecast.md)
</td></tr>
</table>

### See also

[Configure forecasts in your organization](configure-forecast.md)

[Configure forecast using custom rollup entity](configure-forecast-using-custom-rollup-entity.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]

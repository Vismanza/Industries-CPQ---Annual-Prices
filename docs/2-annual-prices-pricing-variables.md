

## Salesforce Metadata

Fields will be needed on xLI, Assets, Headers (Opp/Quote/Order).

They will also need to be mapped with Field Mapper for CPQ functionality (submit, MACD, etc).



### Annual Std Price

With this Pricing Variable created it is possible to create charge PLEs for products using Product Designer.

CPQ Test:

Note that the PLE for Annual is displaed under Recurring section in UI for products. It does not show in the cart itself (expected behaviour at this stage as no UI configureed in Cart).


#### Opportunity

PLE is written to mapped field (expected).

#### Opportunity --> Quote 

Annual Charge field is populated (expected).

#### Quote

PLE is written to mapped field (expected).

#### Quote --> Order

Annual Charge field is populated (expected).

#### Order

PLE is written to mapped field (expected).

#### Order --> Asset

Order submit currently failing in test org (for all products not just annually priced ones) - need to resolve.

#### Asset --> Order



### Annual Std Cost


With this Pricing Variable created it is possible to create cost PLEs for products using Product Designer.



### Annual Margin




Effective Annual Std Price Total

Group Rollup Annual Std Price Total


Master Rollup Annual Std Price Total


Annual Fee





Annual Std Price Adjustment Abs


Annual Std Price Adjustment Pct


Annual Std Price Calculated


Annual Std Price Discount Pct Manual


Annual Std Price Total


Parent Rollup Annual Std Price Total


Rollup Annual Std Price Total
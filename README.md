# Annual Pricing for Industries CPQ

The steps for getting Industries CPQ to support Annual Prices is as follows:

1. Create custom pricing variables for Annual Prices;
2. Configuring Price List Entries for Annual Prices;
3. Configuring Attribute Based Pricing for Annual Prices;
4. Update UI (Cart) for Annual Prices

## Structure

All configuration that involves Industries CPQ managed package objects will be configured using IDX / VBT. These are all in a folder called vlocity.

All Salesforce metadata is stored as a standard Salesforce project in the force-app folder.

Currently Omnistudio components are not configured in the repo yet. The goal is to have all the configuration be done on Omnistudio Standard Runtime using Omnistudio Metadata.
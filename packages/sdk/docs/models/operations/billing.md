# Billing

IMPORTANT: If extending Billing, particularly with optional fields, make sure you also update `sync-orb-subscription-to-owner.ts` to handle the items when the object is recreated.

## Example Usage

```typescript
import { Billing } from "@vercel/sdk/models/operations/createteam.js";

let value: Billing = {
  period: {
    start: 3920.22,
    end: 1439.77,
  },
  plan: "hobby",
};
```

## Fields

| Field                                                                        | Type                                                                         | Required                                                                     | Description                                                                  |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `currency`                                                                   | [operations.Currency](../../models/operations/currency.md)                   | :heavy_minus_sign:                                                           | N/A                                                                          |
| `cancelation`                                                                | *number*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `period`                                                                     | [operations.Period](../../models/operations/period.md)                       | :heavy_check_mark:                                                           | N/A                                                                          |
| `contract`                                                                   | [operations.Contract](../../models/operations/contract.md)                   | :heavy_minus_sign:                                                           | N/A                                                                          |
| `plan`                                                                       | [operations.CreateTeamPlan](../../models/operations/createteamplan.md)       | :heavy_check_mark:                                                           | N/A                                                                          |
| `planIteration`                                                              | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `platform`                                                                   | [operations.Platform](../../models/operations/platform.md)                   | :heavy_minus_sign:                                                           | N/A                                                                          |
| `orbCustomerId`                                                              | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `syncedAt`                                                                   | *number*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `programType`                                                                | [operations.ProgramType](../../models/operations/programtype.md)             | :heavy_minus_sign:                                                           | N/A                                                                          |
| `trial`                                                                      | [operations.Trial](../../models/operations/trial.md)                         | :heavy_minus_sign:                                                           | N/A                                                                          |
| `email`                                                                      | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `tax`                                                                        | [operations.Tax](../../models/operations/tax.md)                             | :heavy_minus_sign:                                                           | N/A                                                                          |
| `language`                                                                   | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `address`                                                                    | [operations.Address](../../models/operations/address.md)                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `name`                                                                       | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `invoiceItems`                                                               | [operations.InvoiceItems](../../models/operations/invoiceitems.md)           | :heavy_minus_sign:                                                           | N/A                                                                          |
| `invoiceSettings`                                                            | [operations.InvoiceSettings](../../models/operations/invoicesettings.md)     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `subscriptions`                                                              | [operations.Subscriptions](../../models/operations/subscriptions.md)[]       | :heavy_minus_sign:                                                           | N/A                                                                          |
| `controls`                                                                   | [operations.Controls](../../models/operations/controls.md)                   | :heavy_minus_sign:                                                           | N/A                                                                          |
| `purchaseOrder`                                                              | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `status`                                                                     | [operations.CreateTeamStatus](../../models/operations/createteamstatus.md)   | :heavy_minus_sign:                                                           | N/A                                                                          |
| `pricingExperiment`                                                          | [operations.PricingExperiment](../../models/operations/pricingexperiment.md) | :heavy_minus_sign:                                                           | N/A                                                                          |
| `orbMigrationScheduledAt`                                                    | *number*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
| `forceOrbMigration`                                                          | *boolean*                                                                    | :heavy_minus_sign:                                                           | N/A                                                                          |
| `awsMarketplace`                                                             | [operations.AwsMarketplace](../../models/operations/awsmarketplace.md)       | :heavy_minus_sign:                                                           | N/A                                                                          |
| `reseller`                                                                   | *string*                                                                     | :heavy_minus_sign:                                                           | N/A                                                                          |
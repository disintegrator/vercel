# GetConfigurationResponseBodyIntegrationsResponseInstallationType

Defines the installation type. - 'external' integrations are installed via the existing integrations flow - 'marketplace' integrations are natively installed: - when accepting the TOS of a partner during the store creation process - if undefined, assume 'external'

## Example Usage

```typescript
import { GetConfigurationResponseBodyIntegrationsResponseInstallationType } from "@vercel/sdk/models/operations/getconfiguration.js";

let value: GetConfigurationResponseBodyIntegrationsResponseInstallationType =
  "marketplace";
```

## Values

```typescript
"marketplace" | "external"
```
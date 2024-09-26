# LastAliasRequest

## Example Usage

```typescript
import { LastAliasRequest } from "@vercel/sdk/models/operations/updateprojectdatacache.js";

let value: LastAliasRequest = {
  fromDeploymentId: "<value>",
  toDeploymentId: "<value>",
  jobStatus: "pending",
  requestedAt: 7486.64,
  type: "rollback",
};
```

## Fields

| Field                                                                                                                                | Type                                                                                                                                 | Required                                                                                                                             | Description                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| `fromDeploymentId`                                                                                                                   | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `toDeploymentId`                                                                                                                     | *string*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `jobStatus`                                                                                                                          | [operations.JobStatus](../../models/operations/jobstatus.md)                                                                         | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `requestedAt`                                                                                                                        | *number*                                                                                                                             | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
| `type`                                                                                                                               | [operations.UpdateProjectDataCacheProjectsResponse200Type](../../models/operations/updateprojectdatacacheprojectsresponse200type.md) | :heavy_check_mark:                                                                                                                   | N/A                                                                                                                                  |
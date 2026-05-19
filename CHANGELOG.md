## 2026-05-19 — commit 1fa0782
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/analytics/overview
-  added the non-success response with the status `404`
-  removed the non-success response with the status `403`


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots
-  added the non-success response with the status `400`


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes
-  added the non-success response with the status `400`


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}/attach
-  added the non-success response with the status `422`


### GET /v1/orgs/{orgSlug}/quotas
-  added the non-success response with the status `404`
-  removed the non-success response with the status `403`







## 2026-05-19 — commit c1f8cd5
# API Changelog 1.0.0 vs. 1.0.0

No changes to report, but the specs are different



## 2026-05-19 — commit d3e4b08
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### GET /v1/apps
- :warning: api path removed without deprecation


### GET /v1/apps/{slug}
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/audit-log
-  removed the `connector` enum value from the `result/items/resourceType` response property for the response status `200`


### GET /v1/orgs/{orgSlug}/audit-log/export
-  removed the `connector` enum value from the `result/items/resourceType` response property for the response status `200`


### GET /v1/orgs/{orgSlug}/audit-log/{id}
-  removed the `connector` enum value from the `result/resourceType` response property for the response status `200`


### POST /v1/orgs/{orgSlug}/billing/auto-top-up
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/balance
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/invoices
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/member-caps
- :warning: api path removed without deprecation


### DELETE /v1/orgs/{orgSlug}/billing/member-caps/{userId}
- :warning: api path removed without deprecation


### PUT /v1/orgs/{orgSlug}/billing/member-caps/{userId}
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/payment-methods
- :warning: api path removed without deprecation


### DELETE /v1/orgs/{orgSlug}/billing/payment-methods/{id}
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/billing/payment-methods/{id}/default
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/payments
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/billing/portal
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/pricing
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/profile
- :warning: api path removed without deprecation


### PATCH /v1/orgs/{orgSlug}/billing/profile
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/spending-caps
- :warning: api path removed without deprecation


### PATCH /v1/orgs/{orgSlug}/billing/spending-caps
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/billing/top-up
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/transactions
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/usage-chart
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/billing/usage-summary
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log
-  removed the `connector` enum value from the `result/items/resourceType` response property for the response status `200`


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log/export
-  removed the `connector` enum value from the `result/items/resourceType` response property for the response status `200`


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log/{id}
-  removed the `connector` enum value from the `result/resourceType` response property for the response status `200`


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/pool
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/analytics
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs
- :warning: api path removed without deprecation


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}
- :warning: api path removed without deprecation


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/logs
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/restart
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/rotate-secrets
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/volumes
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs:validate-bulk
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/metrics
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/network
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/resume
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/snapshots
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/traffic
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/sync-status
- :warning: api path removed without deprecation


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/{connectorId}
- :warning: api path removed without deprecation


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/{connectorId}
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/{connectorId}/reapply
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/preferences
- :warning: api path removed without deprecation


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/preferences
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots/for-restore
- :warning: api path removed without deprecation


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/spending-cap
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/spending-cap
- :warning: api path removed without deprecation


### PUT /v1/orgs/{orgSlug}/projects/{projectSlug}/spending-cap
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/templates
- :warning: api path removed without deprecation


### POST /v1/orgs/{orgSlug}/templates
- :warning: api path removed without deprecation


### DELETE /v1/orgs/{orgSlug}/templates/{id}
- :warning: api path removed without deprecation


### GET /v1/orgs/{orgSlug}/templates/{id}
- :warning: api path removed without deprecation


### PATCH /v1/orgs/{orgSlug}/templates/{id}
- :warning: api path removed without deprecation







## 2026-05-19 — commit 5553d1a
# API Changelog 1.0.0 vs. 1.0.0

No changes to report, but the specs are different



## 2026-05-19 — commit 84b8da0
# API Changelog 1.0.0 vs. 1.0.0

No changes to report, but the specs are different



## 2026-05-17 — commit 526097b
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### POST /v1/orgs
-  added the non-success response with the status `403`







## 2026-05-17 — commit 05b9cdc
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### POST /v1/orgs
-  added the non-success response with the status `422`
-  added the non-success response with the status `429`







## 2026-05-17 — commit 93e87f3
# API Changelog 1.0.0 vs. 1.0.0

No changes to report, but the specs are different



## 2026-05-17 — commit d0b8d30
# API Changelog 1.0.0 vs. 1.0.0

No changes to report, but the specs are different



## 2026-05-17 — commit b4057a3
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### GET /orgs/{orgSlug}/projects/{projectSlug}/api-tokens
- :warning: api path removed without deprecation


### POST /orgs/{orgSlug}/projects/{projectSlug}/api-tokens
- :warning: api path removed without deprecation


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/api-tokens/{id}
- :warning: api path removed without deprecation


### GET /orgs/{orgSlug}/projects/{projectSlug}/snapshots
- :warning: api path removed without deprecation


### GET /orgs/{orgSlug}/projects/{projectSlug}/snapshots/for-restore
- :warning: api path removed without deprecation


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/snapshots/{snapshotId}
- :warning: api path removed without deprecation


### GET /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
- :warning: api path removed without deprecation


### POST /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
- :warning: api path removed without deprecation


### POST /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/sync
- :warning: api path removed without deprecation


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
- :warning: api path removed without deprecation


### PATCH /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
- :warning: api path removed without deprecation


### GET /orgs/{orgSlug}/quotas
- :warning: api path removed without deprecation


### GET /v1/apps
-  endpoint added


### GET /v1/apps/{slug}
-  endpoint added


### GET /v1/orgs
-  endpoint added


### POST /v1/orgs
-  endpoint added


### DELETE /v1/orgs/{orgSlug}
-  endpoint added


### GET /v1/orgs/{orgSlug}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}
-  endpoint added


### GET /v1/orgs/{orgSlug}/audit-log
-  endpoint added


### GET /v1/orgs/{orgSlug}/audit-log/export
-  endpoint added


### GET /v1/orgs/{orgSlug}/audit-log/security-summary
-  endpoint added


### GET /v1/orgs/{orgSlug}/audit-log/{id}
-  endpoint added


### POST /v1/orgs/{orgSlug}/billing/auto-top-up
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/balance
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/invoices
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/member-caps
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/billing/member-caps/{userId}
-  endpoint added


### PUT /v1/orgs/{orgSlug}/billing/member-caps/{userId}
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/payment-methods
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/billing/payment-methods/{id}
-  endpoint added


### POST /v1/orgs/{orgSlug}/billing/payment-methods/{id}/default
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/payments
-  endpoint added


### POST /v1/orgs/{orgSlug}/billing/portal
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/pricing
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/profile
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/billing/profile
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/spending-caps
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/billing/spending-caps
-  endpoint added


### POST /v1/orgs/{orgSlug}/billing/top-up
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/transactions
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/usage-chart
-  endpoint added


### GET /v1/orgs/{orgSlug}/billing/usage-summary
-  endpoint added


### GET /v1/orgs/{orgSlug}/me
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/analytics/overview
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens
- :warning: removed the optional property `result_info` from the response with the `200` status


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens
- :warning: added required request body
- :warning: removed the optional property `result_info` from the response with the `201` status


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens/{id}
- :warning: removed the optional property `result_info` from the response with the `200` status


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log/export
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log/security-summary
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/audit-log/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/pool
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/analytics
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/events
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/firewall
-  endpoint added


### PUT /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/firewall
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/logs
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/restart
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/rotate-secrets
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs/{installId}/volumes
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/installs:validate-bulk
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/logs
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/metrics
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/network
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/resize
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/restart
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/restore
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/resume
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/snapshot
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/snapshots
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/snapshots/{snapshotId}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/ssh-keys
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/ssh-keys
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/ssh-keys/{keyId}
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/start
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/stop
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{id}/traffic
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/sync-status
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/{connectorId}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/{connectorId}
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/instances/{instanceId}/connectors/{connectorId}/reapply
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/preferences
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/preferences
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots
- :warning: removed the optional property `result_info` from the response with the `200` status


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots/for-restore
- :warning: removed the optional property `result_info` from the response with the `200` status


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots/{snapshotId}
- :warning: removed the optional property `result_info` from the response with the `200` status


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/spending-cap
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/spending-cap
-  endpoint added


### PUT /v1/orgs/{orgSlug}/projects/{projectSlug}/spending-cap
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
- :warning: removed the optional property `result_info` from the response with the `200` status


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
- :warning: added required request body
- :warning: removed the optional property `result_info` from the response with the `201` status


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/sync
- :warning: removed the optional property `result_info` from the response with the `200` status


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
- :warning: removed the optional property `result_info` from the response with the `200` status


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
- :warning: added required request body
- :warning: removed the optional property `result_info` from the response with the `200` status


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}/attach
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}/detach
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/volumes/{id}/resize
-  endpoint added


### GET /v1/orgs/{orgSlug}/quotas
- :warning: removed the optional property `result_info` from the response with the `200` status


### GET /v1/orgs/{orgSlug}/templates
-  endpoint added


### POST /v1/orgs/{orgSlug}/templates
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/templates/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/templates/{id}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/templates/{id}
-  endpoint added







## 2026-05-16 — commit f87c732
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### GET /orgs/{orgSlug}/projects/{projectSlug}/snapshots
-  endpoint added


### GET /orgs/{orgSlug}/projects/{projectSlug}/snapshots/for-restore
-  endpoint added


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/snapshots/{snapshotId}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots/for-restore
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/snapshots/{snapshotId}
-  endpoint added







## 2026-05-16 — commit aeeb270
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### GET /orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  api operation id `getOrgsByOrgSlugProjectsByProjectSlugApiTokens` removed and replaced with `listApiTokens`
-  added the optional property `result_info` to the response with the `200` status


### POST /orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  api operation id `postOrgsByOrgSlugProjectsByProjectSlugApiTokens` removed and replaced with `createApiToken`
-  added the optional property `result_info` to the response with the `201` status


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/api-tokens/{id}
-  api operation id `deleteOrgsByOrgSlugProjectsByProjectSlugApiTokensById` removed and replaced with `revokeApiToken`
-  added the optional property `result_info` to the response with the `200` status


### GET /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
-  endpoint added


### POST /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
-  endpoint added


### POST /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/sync
-  endpoint added


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
-  endpoint added


### PATCH /orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
-  endpoint added


### GET /orgs/{orgSlug}/quotas
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  api operation id `getV1OrgsByOrgSlugProjectsByProjectSlugApiTokens` removed and replaced with `listApiTokens`
-  added the optional property `result_info` to the response with the `200` status


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  api operation id `postV1OrgsByOrgSlugProjectsByProjectSlugApiTokens` removed and replaced with `createApiToken`
-  added the optional property `result_info` to the response with the `201` status


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens/{id}
-  api operation id `deleteV1OrgsByOrgSlugProjectsByProjectSlugApiTokensById` removed and replaced with `revokeApiToken`
-  added the optional property `result_info` to the response with the `200` status


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/sync
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
-  endpoint added


### PATCH /v1/orgs/{orgSlug}/projects/{projectSlug}/ssh-keys/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/quotas
-  endpoint added







## 2026-05-16 — commit 358aee1
# API Changelog 1.0.0 vs. 1.0.0


## API Changes

### GET /orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  endpoint added


### POST /orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  endpoint added


### DELETE /orgs/{orgSlug}/projects/{projectSlug}/api-tokens/{id}
-  endpoint added


### GET /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  endpoint added


### POST /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens
-  endpoint added


### DELETE /v1/orgs/{orgSlug}/projects/{projectSlug}/api-tokens/{id}
-  endpoint added







## 2026-05-16 — commit b9cdc81
# API Changelog 1.0.0 vs. 1.0.0



## Components
-  the component security scheme `bearerAuth` was added
-  the component security scheme `sessionCookie` was added


## Security
-  the security scheme `bearerAuth` was added to the API
-  the security scheme `sessionCookie` was added to the API





# Changelog

Auto-generated by CI on every spec update.

## 2026-05-16 — initial seed (empty stub)
- Repository created.

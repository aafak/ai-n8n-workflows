# ai-n8n-workflows

# Install n8n using poweshell
```
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\WINDOWS\System32>  npm install -g n8n
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: @n8n/typeorm@0.3.20-12
npm warn Found: @sentry/node@9.46.0
npm warn node_modules/n8n/node_modules/@sentry/node
npm warn   @sentry/node@"^9.42.1" from n8n@1.111.1
npm warn   node_modules/n8n
npm warn     n8n@"*" from the root project
npm warn   2 more (@n8n/task-runner, n8n-core)
npm warn
npm warn Could not resolve dependency:
npm warn peerOptional @sentry/node@"<=8.x" from @n8n/typeorm@0.3.20-12
npm warn node_modules/n8n/node_modules/@n8n/typeorm
npm warn   @n8n/typeorm@"0.3.20-12" from n8n@1.111.1
npm warn   node_modules/n8n
npm warn   3 more (@n8n/backend-test-utils, @n8n/db, @n8n/n8n-nodes-langchain)
npm warn
npm warn Conflicting peer dependency: @sentry/node@8.55.0
npm warn node_modules/@sentry/node
npm warn   peerOptional @sentry/node@"<=8.x" from @n8n/typeorm@0.3.20-12
npm warn   node_modules/n8n/node_modules/@n8n/typeorm
npm warn     @n8n/typeorm@"0.3.20-12" from n8n@1.111.1
npm warn     node_modules/n8n
npm warn     3 more (@n8n/backend-test-utils, @n8n/db, @n8n/n8n-nodes-langchain)
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: @browserbasehq/stagehand@1.14.0
npm warn Found: openai@5.12.2
npm warn node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/openai
npm warn   openai@"5.12.2" from @n8n/n8n-nodes-langchain@1.110.0
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn     @n8n/n8n-nodes-langchain@"1.110.0" from n8n@1.111.1
npm warn     node_modules/n8n
npm warn   1 more (@langchain/community)
npm warn
npm warn Could not resolve dependency:
npm warn peer openai@"^4.62.1" from @browserbasehq/stagehand@1.14.0
npm warn node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@browserbasehq/stagehand
npm warn   peer @browserbasehq/stagehand@"^1.0.0" from @langchain/community@0.3.50
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@langchain/community
npm warn
npm warn Conflicting peer dependency: openai@4.104.0
npm warn node_modules/openai
npm warn   peer openai@"^4.62.1" from @browserbasehq/stagehand@1.14.0
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@browserbasehq/stagehand
npm warn     peer @browserbasehq/stagehand@"^1.0.0" from @langchain/community@0.3.50
npm warn     node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@langchain/community
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: @langchain/community@0.3.50
npm warn Found: @qdrant/js-client-rest@1.14.1
npm warn node_modules/n8n/node_modules/@qdrant/js-client-rest
npm warn   @qdrant/js-client-rest@"1.14.1" from @n8n/n8n-nodes-langchain@1.110.0
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn     @n8n/n8n-nodes-langchain@"1.110.0" from n8n@1.111.1
npm warn     node_modules/n8n
npm warn   1 more (@langchain/qdrant)
npm warn
npm warn Could not resolve dependency:
npm warn peerOptional @qdrant/js-client-rest@"^1.15.0" from @langchain/community@0.3.50
npm warn node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@langchain/community
npm warn   @langchain/community@"0.3.50" from @n8n/n8n-nodes-langchain@1.110.0
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn
npm warn Conflicting peer dependency: @qdrant/js-client-rest@1.15.1
npm warn node_modules/@qdrant/js-client-rest
npm warn   peerOptional @qdrant/js-client-rest@"^1.15.0" from @langchain/community@0.3.50
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@langchain/community
npm warn     @langchain/community@"0.3.50" from @n8n/n8n-nodes-langchain@1.110.0
npm warn     node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: @langchain/community@0.3.50
npm warn Found: mongodb@6.11.0
npm warn node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/mongodb
npm warn   mongodb@"6.11.0" from @n8n/n8n-nodes-langchain@1.110.0
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn     @n8n/n8n-nodes-langchain@"1.110.0" from n8n@1.111.1
npm warn     node_modules/n8n
npm warn
npm warn Could not resolve dependency:
npm warn peerOptional mongodb@"^6.17.0" from @langchain/community@0.3.50
npm warn node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@langchain/community
npm warn   @langchain/community@"0.3.50" from @n8n/n8n-nodes-langchain@1.110.0
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn
npm warn Conflicting peer dependency: mongodb@6.20.0
npm warn node_modules/mongodb
npm warn   peerOptional mongodb@"^6.17.0" from @langchain/community@0.3.50
npm warn   node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain/node_modules/@langchain/community
npm warn     @langchain/community@"0.3.50" from @n8n/n8n-nodes-langchain@1.110.0
npm warn     node_modules/n8n/node_modules/@n8n/n8n-nodes-langchain
npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm warn deprecated @npmcli/move-file@1.1.2: This functionality has been moved to @npmcli/fs
npm warn deprecated npmlog@6.0.2: This package is no longer supported.
npm warn deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated are-we-there-yet@3.0.1: This package is no longer supported.
npm warn deprecated gauge@4.0.4: This package is no longer supported.
npm warn deprecated node-domexception@1.0.0: Use your platform's native DOMException instead
npm warn deprecated gm@1.25.1: The gm module has been sunset. Please migrate to an alternative. https://github.com/aheckmann/gm?tab=readme-ov-file#2025-02-24-this-project-is-not-maintained
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated lodash.get@4.4.2: This package is deprecated. Use the optional chaining (?.) operator instead.
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated @aws-sdk/protocol-http@3.374.0: This package has moved to @smithy/protocol-http
npm warn deprecated @aws-sdk/signature-v4@3.374.0: This package has moved to @smithy/signature-v4
npm warn deprecated rimraf@2.6.3: Rimraf versions prior to v4 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated infisical-node@1.3.0: Package no longer supported. Contact Support at https://www.npmjs.com/support for more info.

added 1998 packages in 4m

245 packages are looking for funding
  run `npm fund` for details
PS C:\WINDOWS\System32> n8n
No encryption key found - Auto-generating and saving to: C:\Users\aafak\.n8n\config
Initializing n8n process
n8n ready on ::, port 5678
Migrations in progress, please do NOT stop the process.
Starting migration InitialMigration1588102412422
Finished migration InitialMigration1588102412422
Starting migration WebhookModel1592445003908
Finished migration WebhookModel1592445003908
Starting migration CreateIndexStoppedAt1594825041918
Finished migration CreateIndexStoppedAt1594825041918
Starting migration MakeStoppedAtNullable1607431743769
Finished migration MakeStoppedAtNullable1607431743769
Starting migration AddWebhookId1611071044839
Finished migration AddWebhookId1611071044839
Starting migration CreateTagEntity1617213344594
Finished migration CreateTagEntity1617213344594
Starting migration UniqueWorkflowNames1620821879465
Finished migration UniqueWorkflowNames1620821879465
Starting migration AddWaitColumn1621707690587
Finished migration AddWaitColumn1621707690587
Starting migration UpdateWorkflowCredentials1630330987096
Finished migration UpdateWorkflowCredentials1630330987096
Starting migration AddExecutionEntityIndexes1644421939510
Finished migration AddExecutionEntityIndexes1644421939510
Starting migration CreateUserManagement1646992772331
Finished migration CreateUserManagement1646992772331
Starting migration LowerCaseUserEmail1648740597343
Finished migration LowerCaseUserEmail1648740597343
Starting migration CommunityNodes1652254514001
Finished migration CommunityNodes1652254514001
Starting migration AddUserSettings1652367743993
Finished migration AddUserSettings1652367743993
Starting migration AddAPIKeyColumn1652905585850
Finished migration AddAPIKeyColumn1652905585850
Starting migration IntroducePinData1654089251344
Finished migration IntroducePinData1654089251344
Starting migration AddNodeIds1658930531669
Finished migration AddNodeIds1658930531669
Starting migration AddJsonKeyPinData1659888469333
Finished migration AddJsonKeyPinData1659888469333
Starting migration CreateCredentialsUserRole1660062385367
Finished migration CreateCredentialsUserRole1660062385367
Starting migration CreateWorkflowsEditorRole1663755770892
Finished migration CreateWorkflowsEditorRole1663755770892
Starting migration WorkflowStatistics1664196174000
Finished migration WorkflowStatistics1664196174000
Starting migration CreateCredentialUsageTable1665484192211
Finished migration CreateCredentialUsageTable1665484192211
Starting migration RemoveCredentialUsageTable1665754637024
Finished migration RemoveCredentialUsageTable1665754637024
Starting migration AddWorkflowVersionIdColumn1669739707124
Finished migration AddWorkflowVersionIdColumn1669739707124
Starting migration AddTriggerCountColumn1669823906993
Finished migration AddTriggerCountColumn1669823906993
Starting migration MessageEventBusDestinations1671535397530
Finished migration MessageEventBusDestinations1671535397530
Starting migration RemoveWorkflowDataLoadedFlag1671726148419
Finished migration RemoveWorkflowDataLoadedFlag1671726148419
Starting migration DeleteExecutionsWithWorkflows1673268682475
Finished migration DeleteExecutionsWithWorkflows1673268682475
Starting migration AddStatusToExecutions1674138566000
Finished migration AddStatusToExecutions1674138566000
Starting migration CreateLdapEntities1674509946020
Finished migration CreateLdapEntities1674509946020
Starting migration PurgeInvalidWorkflowConnections1675940580449
Finished migration PurgeInvalidWorkflowConnections1675940580449
Starting migration MigrateExecutionStatus1676996103000
Finished migration MigrateExecutionStatus1676996103000
Starting migration UpdateRunningExecutionStatus1677237073720
Finished migration UpdateRunningExecutionStatus1677237073720
Starting migration CreateVariables1677501636752
Finished migration CreateVariables1677501636752
Starting migration CreateExecutionMetadataTable1679416281777
Finished migration CreateExecutionMetadataTable1679416281777
Starting migration AddUserActivatedProperty1681134145996
Finished migration AddUserActivatedProperty1681134145996
Starting migration RemoveSkipOwnerSetup1681134145997
Finished migration RemoveSkipOwnerSetup1681134145997
Starting migration MigrateIntegerKeysToString1690000000002
Finished migration MigrateIntegerKeysToString1690000000002
Starting migration SeparateExecutionData1690000000010
Finished migration SeparateExecutionData1690000000010
Starting migration FixMissingIndicesFromStringIdMigration1690000000020
Finished migration FixMissingIndicesFromStringIdMigration1690000000020
Starting migration RemoveResetPasswordColumns1690000000030
Finished migration RemoveResetPasswordColumns1690000000030
Starting migration AddMfaColumns1690000000030
Finished migration AddMfaColumns1690000000030
Starting migration CreateWorkflowNameIndex1691088862123
Finished migration CreateWorkflowNameIndex1691088862123
Starting migration CreateWorkflowHistoryTable1692967111175
Finished migration CreateWorkflowHistoryTable1692967111175
Starting migration ExecutionSoftDelete1693491613982
Finished migration ExecutionSoftDelete1693491613982
Starting migration DisallowOrphanExecutions1693554410387
Finished migration DisallowOrphanExecutions1693554410387
Starting migration AddWorkflowMetadata1695128658538
Finished migration AddWorkflowMetadata1695128658538
Starting migration ModifyWorkflowHistoryNodesAndConnections1695829275184
Finished migration ModifyWorkflowHistoryNodesAndConnections1695829275184
Starting migration AddGlobalAdminRole1700571993961
Finished migration AddGlobalAdminRole1700571993961
Starting migration DropRoleMapping1705429061930
Finished migration DropRoleMapping1705429061930
Starting migration RemoveFailedExecutionStatus1711018413374
Finished migration RemoveFailedExecutionStatus1711018413374
Starting migration MoveSshKeysToDatabase1711390882123
[MoveSshKeysToDatabase1711390882123] No SSH keys in filesystem, skipping
Finished migration MoveSshKeysToDatabase1711390882123
Starting migration RemoveNodesAccess1712044305787
Finished migration RemoveNodesAccess1712044305787
Starting migration CreateProject1714133768519
Finished migration CreateProject1714133768519
Starting migration MakeExecutionStatusNonNullable1714133768521
Finished migration MakeExecutionStatusNonNullable1714133768521
Starting migration AddActivatedAtUserSetting1717498465931
Finished migration AddActivatedAtUserSetting1717498465931
Starting migration AddConstraintToExecutionMetadata1720101653148
Finished migration AddConstraintToExecutionMetadata1720101653148
Starting migration CreateInvalidAuthTokenTable1723627610222
Finished migration CreateInvalidAuthTokenTable1723627610222
Starting migration RefactorExecutionIndices1723796243146
Finished migration RefactorExecutionIndices1723796243146
Starting migration CreateAnnotationTables1724753530828
Finished migration CreateAnnotationTables1724753530828
Starting migration AddApiKeysTable1724951148974
Finished migration AddApiKeysTable1724951148974
Starting migration CreateProcessedDataTable1726606152711
Finished migration CreateProcessedDataTable1726606152711
Starting migration SeparateExecutionCreationFromStart1727427440136
Finished migration SeparateExecutionCreationFromStart1727427440136
Starting migration AddMissingPrimaryKeyOnAnnotationTagMapping1728659839644
Finished migration AddMissingPrimaryKeyOnAnnotationTagMapping1728659839644
Starting migration UpdateProcessedDataValueColumnToText1729607673464
Finished migration UpdateProcessedDataValueColumnToText1729607673464
Starting migration AddProjectIcons1729607673469
Finished migration AddProjectIcons1729607673469
Starting migration CreateTestDefinitionTable1730386903556
Finished migration CreateTestDefinitionTable1730386903556
Starting migration AddDescriptionToTestDefinition1731404028106
Finished migration AddDescriptionToTestDefinition1731404028106
Starting migration MigrateTestDefinitionKeyToString1731582748663
Finished migration MigrateTestDefinitionKeyToString1731582748663
Starting migration CreateTestMetricTable1732271325258
Finished migration CreateTestMetricTable1732271325258
Starting migration CreateTestRun1732549866705
Finished migration CreateTestRun1732549866705
Starting migration AddMockedNodesColumnToTestDefinition1733133775640
Finished migration AddMockedNodesColumnToTestDefinition1733133775640
Starting migration AddManagedColumnToCredentialsTable1734479635324
Finished migration AddManagedColumnToCredentialsTable1734479635324
Starting migration AddStatsColumnsToTestRun1736172058779
Finished migration AddStatsColumnsToTestRun1736172058779
Starting migration CreateTestCaseExecutionTable1736947513045
Finished migration CreateTestCaseExecutionTable1736947513045
Starting migration AddErrorColumnsToTestRuns1737715421462
Finished migration AddErrorColumnsToTestRuns1737715421462
Starting migration CreateFolderTable1738709609940
Finished migration CreateFolderTable1738709609940
Starting migration CreateAnalyticsTables1739549398681
Finished migration CreateAnalyticsTables1739549398681
Starting migration UpdateParentFolderIdColumn1740445074052
Finished migration UpdateParentFolderIdColumn1740445074052
Starting migration RenameAnalyticsToInsights1741167584277
Finished migration RenameAnalyticsToInsights1741167584277
Starting migration AddScopesColumnToApiKeys1742918400000
Finished migration AddScopesColumnToApiKeys1742918400000
Starting migration ClearEvaluation1745322634000
Finished migration ClearEvaluation1745322634000
Starting migration AddWorkflowStatisticsRootCount1745587087521
Finished migration AddWorkflowStatisticsRootCount1745587087521
Starting migration AddWorkflowArchivedColumn1745934666076
Finished migration AddWorkflowArchivedColumn1745934666076
Starting migration DropRoleTable1745934666077
Finished migration DropRoleTable1745934666077
Starting migration AddProjectDescriptionColumn1747824239000
Finished migration AddProjectDescriptionColumn1747824239000
Starting migration AddLastActiveAtColumnToUser1750252139166
Finished migration AddLastActiveAtColumnToUser1750252139166
Starting migration AddScopeTables1750252139166
Finished migration AddScopeTables1750252139166
Starting migration AddRolesTables1750252139167
Finished migration AddRolesTables1750252139167
Starting migration LinkRoleToUserTable1750252139168
Finished migration LinkRoleToUserTable1750252139168
Starting migration RemoveOldRoleColumn1750252139170
Finished migration RemoveOldRoleColumn1750252139170
Starting migration AddInputsOutputsToTestCaseExecution1752669793000
Finished migration AddInputsOutputsToTestCaseExecution1752669793000
Starting migration LinkRoleToProjectRelationTable1753953244168
Finished migration LinkRoleToProjectRelationTable1753953244168
Starting migration CreateDataStoreTables1754475614601
Finished migration CreateDataStoreTables1754475614601
Starting migration ReplaceDataStoreTablesWithDataTables1754475614602
Finished migration ReplaceDataStoreTablesWithDataTables1754475614602

There are deprecations related to your environment variables. Please take the recommended actions to update your configuration:
 - DB_SQLITE_POOL_SIZE -> Running SQLite without a pool of read connections is deprecated. Please set `DB_SQLITE_POOL_SIZE` to a value higher than zero. See: https://docs.n8n.io/hosting/configuration/environment-variables/database/#sqlite
 - N8N_RUNNERS_ENABLED -> Running n8n without task runners is deprecated. Task runners will be turned on by default in a future version. Please set `N8N_RUNNERS_ENABLED=true` to enable task runners now and avoid potential issues in the future. Learn more: https://docs.n8n.io/hosting/configuration/task-runners/
 - N8N_BLOCK_ENV_ACCESS_IN_NODE -> The default value of N8N_BLOCK_ENV_ACCESS_IN_NODE will be changed from false to true in a future version. If you need to access environment variables from the Code Node or from expressions, please set N8N_BLOCK_ENV_ACCESS_IN_NODE=false. Learn more: https://docs.n8n.io/hosting/configuration/environment-variables/security/

[license SDK] Skipping renewal on init: license cert is not initialized
Version: 1.111.1

Editor is now accessible via:
http://localhost:5678

Press "o" to open in Browser.
(node:13756) [DEP0060] DeprecationWarning: The `util._extend` API is deprecated. Please use Object.assign() instead.
(Use `node --trace-deprecation ...` to show where the warning was created)
Owner was set up successfully
User survey updated successfully
Node does not have any credentials set
The service refused the connection - perhaps it is offline
NodeApiError The service refused the connection - perhaps it is offline
The service refused the connection - perhaps it is offline
McpClientTool: Failed to connect to MCP Server
[license SDK] license successfully activated
[license SDK] license activation failed: consumer already has a valid entitlement for this reservation
400 Activation key has already been used on this instance
[license SDK] license successfully renewed
[license SDK] license successfully renewed
```


# First Start MCP server using  https://github.com/aafak/ai-agent-exp/blob/main/flight_booking_mcp.py

```
aafak@aafak MINGW64 /d/git-repos/ai-agent-exp (main)
$ uv run python flight_booking_mcp.py


+----------------------------------------------------------------------------+
|                                                                            |
|        _ __ ___  _____           __  __  _____________    ____    ____     |
|       _ __ ___ .'____/___ ______/ /_/  |/  / ____/ __ \  |___ \  / __ \    |
|      _ __ ___ / /_  / __ `/ ___/ __/ /|_/ / /   / /_/ /  ___/ / / / / /    |
|     _ __ ___ / __/ / /_/ (__  ) /_/ /  / / /___/ ____/  /  __/_/ /_/ /     |
|    _ __ ___ /_/    \____/____/\__/_/  /_/\____/_/      /_____(*)____/      |
|                                                                            |
|                                                                            |
|                                FastMCP  2.0                                |
|                                                                            |
|                                                                            |
|               \U0001f5a5\ufe0f  Server name:     Flight_booking_MCP_Server                |
|               \U0001f4e6 Transport:       Streamable-HTTP                          |
|               \U0001f517 Server URL:      http://127.0.0.1:8000/mcp                |
|                                                                            |
|               \U0001f3ce\ufe0f  FastMCP version: 2.12.3                                   |
|               \U0001f91d MCP SDK version: 1.14.0                                   |
|                                                                            |
|               \U0001f4da Docs:            https://gofastmcp.com                    |
|               \U0001f680 Deploy:          https://fastmcp.cloud                    |
|                                                                            |
+----------------------------------------------------------------------------+


[09/20/25 10:55:22] INFO     Starting MCP server                 server.py:1572
                             'Flight_booking_MCP_Server' with
                             transport 'http' on
                             http://127.0.0.1:8000/mcp

````

# Open the n8n console and import the "agent with MCP.json"


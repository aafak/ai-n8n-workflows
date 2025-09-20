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
<img width="1913" height="943" alt="image" src="https://github.com/user-attachments/assets/fa938bf2-5be6-44a3-be6a-766129b00a8e" />


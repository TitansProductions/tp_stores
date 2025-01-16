# TP Stores

## Development Exports

```lua

-- @param storeId : Requires the storeId name from the configuration file (Such as 'GENERAL_STORE_VALENTINE' )
-- @param cb : Set to true if the opened store is Custom, set to false if the store is not Custom.
-- If storeId is custom, the @storeId must be having a name which is located on Config.CustomStores

exports.tp_stores:openStoreByName(storeName, cb)

```

## Development Events

```lua

-- @param storeId : Requires the storeId name from the configuration file (Such as 'GENERAL_STORE_VALENTINE' )
-- @param cb : Set to true if the opened store is Custom, set to false if the store is not Custom.
-- If storeId is custom, the @storeId must be having a name which is located on Config.CustomStores

TriggerEvent("tp_stores:openStoreByName", storeName, cb) -- client to client
TriggerClientEvent("tp_stores:openStoreByName", source, storeName, cb) -- server to client

```

---
-api-id: T:Windows.Networking.Connectivity.NetworkUsageStates
-api-type: winrt struct
---

<!-- Structure syntax.
public struct NetworkUsageStates 
-->

# NetworkUsageStates

## -description
Defines the desired state of the connection profile for which usage data is returned by the method [GetNetworkUsageAsync](connectionprofile_getnetworkusageasync.md).

## -struct-fields

### -field Roaming
Defines the desired roaming state of the network connection.
    

### -field Shared
Defines the desired sharing state of the network connection.
    

## -remarks
The Shared [NetworkUsageState](networkusagestates.md) corresponds to when a network connection is made available to provide internet access for other devices. For an example of how [NetworkUsageStates](networkusagestates.md) is used, see [How to retrieve connection usage data for a specific period of time](http://msdn.microsoft.com/library/c9409429-7712-42e9-a2af-3940a7375c21).

## -examples

## -see-also
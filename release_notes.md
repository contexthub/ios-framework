## 1.3.1 - September 8, 2014
- CCHPush - **Method signature changed**: added CCHContextHubPush boolean to remote notification handler.
- CCHSensorPipeline - added new delegate method `sensorPipeline:didDetectEvent`
- CCHSensorPipeline - **Method renamed**: renamed `addSubscriptionsForTags:`, `removeSubscriptionsForTags` to `addElementsWithTags:`, `removeElementsWithTags:`
- CCHDevice - **Method renamed**: renamed `updateDeviceAlias:tags:completionHandler` to `setDeviceAlias:tags:completionHandler`
- Updated the structure of the `context` in the event dictionary.
- added optimizations to the way HTTP sessions are queued.

## 1.2.0 - August 15, 2014
- **CCHSubscriptionService - Method Renamed** - renamed 'getSubscriptionsWithCompletion:' to 'getSubscriptionsWithCompletionHandler'
- CCHSubscriptionService - you can subscribe to device changes in and observe change notifications (CCHDeviceCreatedNotification, CCHDeviceUpdatedNotification, CCHDeviceDeletedNotification)
- CCHDevice - A new api for working with devices stored on the ContextHub server.

## 1.1.4 - July 31, 2014
- CCHSensorPipeline - changed method name `triggerEvent:completionHandler:`
- CCHVersion - allows you to check the version of the framework.

## 1.1.3 - July 15, 2014
- CCHSensorPipeline - you can trigger custom events
- CCHSubscriptions - improved the way you add and remove subscriptions
- CCHLog - new api for creating log statements on the ContextHub server

## 1.1.2 - July 11, 2014
- CCHVault - added ability to query vault items using key paths
- Bug Fix - background fetch completion handler is now executed for all resource actions (created, updated, deleted)

## 1.1.1 - June 30, 2014
- added docset
- updated documentation in header files

## 1.1.0 - June 30, 2014
- framework release
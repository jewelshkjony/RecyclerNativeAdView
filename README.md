# [PAID] Recycler Native Ad View Extension : Monetize & boost your earning with native ads into recycler view
The Recycler Native Ad View Extension for MIT App Inventor 2 is a powerful tool that enhances the app-building experience by seamlessly integrating native ads into your application. This extension allows you to display native ads within a recycler view, providing a user-friendly and unobtrusive way to monetize your app. With its easy-to-use interface and extensive customization options, this extension is perfect for developers looking to generate revenue through native advertising.
* **

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/3eee6c83-3918-4e1f-9cbd-b7ad4ff534c9)

## :sparkle: Initialize
You need to initialize the recycler view first.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8ad93a18-16c8-42b6-bb01-b32bade012ff)

* `layout` - Set any view layout here.
* `layoutManager` - Set layout manager using extension properties.
* `snapHelper` - Set snap helper from extension properties.
* `data` - Set item list.
* `adAfterItem` - Set number to show ad after items.
* `adSize` - Set ad size using extension properties or functions.
* `adUnitId` - Set ad unit id for banner ad.
* `testMode` - Set true for enable test ads.
* **

## :sparkle: Create View
Here you need to create your item view for binding it’s data on bind view event.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/7b094f94-4450-4034-9fdb-869866f81a17)

* `rootView` - It’s return the root view.
* **

## :sparkle: Bind View
Here you need to bind data to created view.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/f9bb9c69-95d0-4f28-ba45-a2b12c26a38c)

* `rootView` - It’s return the root view.
* `itemPosition` - It’s return the position for item view.
* `dataItem` - It’s return the item from given data list.
* `adapterPosition` - It’s return the position of adapter.
* **

## :sparkle: Bind Ad View
Here you need to bind native ad to created view.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/fc590028-b3ba-4c89-b521-4ec7fe95080d)

* `nativeAdView` - It’s return the native ad view.
* `nativeAd` - It’s return the loaded native ad for this position.
* `adapterPosition` - It’s return the position of adapter.
* **

## :sparkle: View Attached To Window
It’s triggered when view attached to window.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/b5259ed8-079d-4f1a-b334-c3b440cb1e6b)

* `rootView` - It’s return the root view.
* `itemPosition` - It’s return the position for item view.
* `adapterPosition` - It’s return the position of adapter.
* **

## :sparkle: View Detached From Window
It’s triggered when view detached from window.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/f3900fea-1d10-4318-b86f-2fed0730a881)

* `rootView` - It’s return the root view.
* `adapterPosition` - It’s return the position of adapter.
* **

## :sparkle: Scroll State Changed
Event for scroll state change.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/3e8dcaa4-6195-4e90-8a0b-804a1ab946d7)

* `scrollState` - It’s return the scrolling state.
* **

## :sparkle: Scrolled
Event for scrolled listener.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/3217bf8b-bcf9-4d14-a04f-e12829eca2f9)

* `dx` - It’s return the dx position.
* `dy` - It’s return the dy position of screen.
* **

## :sparkle: Left Swiped
It’s triggered when item swiped right to left.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/822e0441-445c-4e5d-9c2d-8494724f21e0)

* `itemPosition` - It’s return the position for item view.
* `adapterPosition` - It’s return the position of adapter.
* **

## :sparkle: Right Swiped
It’s triggered when item swiped left to right.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/68f3b30a-998a-4fff-b837-16e0d69af0b5)

* `itemPosition` - It’s return the position for item view.
* `adapterPosition` - It’s return the position of adapter.
* **

## :sparkle: Draaged
It’s triggered when item moved between them.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/12e8fcca-70a5-4818-b78b-47302253438a)

* `fromAdapterPosition` - It’s return the from adapter position for item view.
* `toAdapterPosition` - It’s return the to adapter position for item view.
* **

## :sparkle: Over Scrolled
It’s triggered when user over scrolling the list view.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/5f8ec06f-f04b-4b40-86cf-bdcc51be5595)

* `state` - It’s returning the state of over scrolled.
* `offset` - It’s returning the over scrolled offset.
* **

## ❇️ Failed To Inflate Xml
It's triggered when extension failed to inflate xml layout for native ad view.
Read the message to understand the error reason.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/f4dbcae7-b484-47ed-9f44-37907f1df0ed)

* `message` - It's return the error message.
* **

## ❇️ Ad Loaded
It’s triggered when ad loaded.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/cb70589d-c773-4756-83b2-a379de7f0d8b)

* `hasVideo` - It's return true if the ad has video content.
* **

## :sparkle: Ad Failed To Load
It’s triggered when ad failed to load.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8c63c68f-37ab-486a-89b4-97bdcc9aa04b)

* `error Code` - It's return the error code.
* `error Message` - It's return error message as string.
* `response` - It's return the error code & message as json.
* **

## :sparkle: Ad Clicked
It’s triggered when user click on any banner ad.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/269a840a-9d93-4666-8a71-38169f0a28d2)
* **

## :sparkle: Ad Impression
It’s triggered when the ad count impression.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/030da76e-092f-4497-a582-c844031400f8)
* **

## :sparkle: Ad Swipe Gesture Clicked
It’s triggered for ad swipe gesture clicked.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/68ef02cf-5e4b-427b-b5c9-b2e361b0a926)
* **

## :sparkle: Ad Opened
It’s triggered when ad is opened.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d67cf74f-68fb-48fb-a7d9-905ccb7ebf37)
* **

## :sparkle: Ad Closed
It's triggered when ad is closed.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/12f17864-a72b-47bf-b177-c6adaf9332db)
* **

## ❇️ Video Start
It's triggered when video is started.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/b17c4647-f278-4f09-b681-0fad5f7f2036)

* `duration` - It’s return the duration of video in second.
* **

## ❇️ Video Play
It's triggered when video played.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d29844f1-5350-4205-8d5a-8b7e786889e5)
* **

## ❇️ Video Pause
It's triggered when video is paused.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/7891750c-e788-4c57-aad1-6e08bc8deea0)
* **

## ❇️ Video End
It's triggered when video is ended.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/53a7096c-cd62-4ec9-b068-43e8c865c1c6)

* `duration` - It’s return the duration of video in second. 
* **

## ❇️ VideoMute
It's triggered when video muted or unmuted.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/6a99ba28-9df4-4b50-a26a-5c08b2138b7a)

* `isMuted` - It’s return true is video is muted.
* **

## :sparkle: Scroll To Position
Use this method to scroll adapter to the item position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8a989f7e-ea92-451d-92fd-3d49a7c43058)

* `itemPosition` - Set item position.
* **

## :sparkle: Smooth Scroll To Position
Use this method to smoothly scroll to item position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/e8594f2d-7403-4144-994d-ab137ed86d0a)

* `itemPosition` - Set item position.
* **

## :sparkle: Stop Scroll
Use this method to manually stop scrolling.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/efc85a9f-b663-4f38-acd9-19886898526b)
* **

## :sparkle: Ad Gap Decorator
Use this method to add gap between items.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/e2557439-a82b-4c73-8082-cd5100429235)

* `gap` - Set gap as integer number.
* **

## :sparkle: Get Data
Use this method to get given data list.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/a3d8fdad-3a47-4394-bf71-f33f4658e6c1)
* **

## :sparkle: Update Data
Use this method to update data with new or modified list.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/dae08992-598e-4450-be28-b49506a34029)

* `data` - Set data as list.
* **

## :sparkle: Update Data Smoothly
Use this method to update data smoothly.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/dde91182-cc48-40f7-830b-068bbadb0256)

* `data` - Set data as list.
* **

## :sparkle: Notify Data Set Changed
You can use this function to manually notify the adapter to re-create all views after any changes to views.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/ff22aaee-ff27-46ce-b192-d2015814ae37)
* **

## :sparkle: Notify Item Changed
Use this function to notify the adapter for re-create view for given position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d7b4a58c-d7d7-4b16-a2ab-f50f96cd4419)

* `adapterPosition` - Set adapter position.
* **

## :sparkle: Notify Item Inserted
Use this function to notify adapter to add item to given position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8b143cde-7b75-435b-8691-d7e128b14ddf)

* `adapterPosition` - Set adapter position.
* **

## :sparkle: Notify Item Removed
Use this function to notify adapter for remove item from given position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/207c3900-6dfd-491b-a363-4ed147f71ec3)

* `adapterPosition` - Set adapter position.
* **

## :sparkle: Notify Item Moved
Use this function to notify adapter for item moving by given positions.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/670feca7-38af-4aea-8751-fc0974afd7f6)

* `fromAdapterPosition` - Set item position from where to move item.
* `toAdapterPosition` - Set item position to where to move item.
* **

## :sparkle: Notify Item Range Changed
Use this function to notify adapter for multiple items changed.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/a5d1a06b-b19e-4e15-b98c-bfdd512802b6)

* `adapterPositionStart` - Set start position.
* `itemCount` - Set item count.
* **

## :sparkle: Notify Item Range Inserted
Use this function to notify adapter for multiple items insertion.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/5a91a0f9-5bd2-410d-a77b-f0d83ea2aa5a)

* `adapterPositionStart` - Set start position.
* `itemCount` - Set item count.
* **

## :sparkle: Notify Item Range Removed
Use this function to notify adapter for multiple items removed.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/45a93af2-1b2c-4e7c-823d-cbf8d903610e)

* `adapterPositionStart` - Set start position.
* `itemCount` - Set item count.
* **

## :sparkle: Item Position
Get item position by adapter position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/e402c897-bca9-49e7-b77f-e81dc1fad979)

* `adapterPosition` - Set adapter position.
* **

## :sparkle: Adapter Position
Get adapter position by item position.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d0ec6eeb-a08a-4acd-a985-dae0f4df095f)

* `itemPosition` - Set item position.
* **

## :sparkle: Get Root View
Use this function to get root view by child view.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8efb3316-cd2e-4699-ad58-0777bb5c2859)

* `component` - Set view component to get root view.
* **

## :sparkle: Get Adapter Position
Use this function to get adapter position by root view.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/3ed25f9c-11d1-4473-98c1-34986bbfe17e)

* `rootView` - Set root view.
* **

## :sparkle: Create Component
Use this function to create dynamic views.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/57b07bc9-716f-4aee-bbc5-fa65e1cfa292)

* `parent` - Set parent view where to create new view.
* `name` - Set the name of component to create view.
* `tag` - Set tag for view.
* `properties` - Set properties for view.
* **

## :sparkle: Create Template
Use this function to create dynamic views using JSON template.

![image](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d6d87402-8112-42ab-89d7-6f0a9b3e0464)

* `in` - Set view component where to create new views.
* `template` - Set template to create views.
* `parameters` - Set parameters for dynamic views.
* **

## :sparkle: Set Properties
Use this function to set properties for any dynamic view.

![033cd](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/19f5cf4f-326e-4153-9f3b-afcfacfa0b8f)

* `component` - Set view to apply properties.
* `properties` - Set properties.
* **

## ❇️ Set Property
Set single property for a component.

![b8459](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/227642d2-4fe7-48b5-a12d-0815bc1970fb)

* `component` - Set view to apply properties.
* `name` - Set property name.
* `value` - Set property value.
* **

## :sparkle: Set Unique Id
Use this function to set unique id to view. It’s required to use click listener.

![357082a](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/bc6e97d8-13bd-4ea5-b4d9-4055f27c0d27)

* `component` - Set view component to apply unique id.
* `id` - Set id for view component.
* **

## :sparkle: Get Unique Id
Use this function to get unique id for any view.

![030db88c](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/63f32d16-ff9c-4608-83f9-f82685ba8319)

* `component` - Set view component to get unique id.
* **

## ❇️ Unique Ids
It's return all used unique ids as list.

![10b13](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d3fc8ba4-694b-4939-9b06-085aed745a10)
* **

## :sparkle: Get Component
Use this function to get child view from parent view by it’s tag.

![a6d598c](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/154ea931-e36f-42f1-9ef3-12fa667b2d35)

* `parent` - Set the child view component.
* `tag` - Set tag to find parent view.
* **

## :sparkle: Get Component By Id
Use this function to get view component by it’s unique id.
For using this method you should set unique id to this view.

![5f448ee](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8cb58a88-0f47-48bf-8034-01c0c1c5d6db)

* `uniqueId` - Set unique id to find the view component.
* **

## :sparkle: Is Dynamic Component
It’s returning true if the view is created dynamically.

![3f295](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/1e2c48d6-e046-499f-b77b-7416c0504595)

* `component` - Set view component.
* **

## :sparkle: Get Component Name
It’s returning the name of component.
You can use this function to get the actual name of in-built components.

![635d5](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/cb3b7dac-41dd-4079-a2e8-f2a40fb5119c)

* `component` - Set any in-build component to get it’s name.
* **

## :sparkle: Animate View On Click
Use this function to animate root view when clicked.

![143e6de](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/242a1069-3ac7-422a-8001-dc3e2cbaa293)

* `rootView` - Set view to animate.
* `duration` - Set duration in milliseconds.
* **

## :sparkle: Linear Layout Manager
Use this function to create linear layout manager for initialize recycler view.

![41e954](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/0bdb50be-d6c7-4e4a-bbc3-83c56977a049)

* `orientation` - Set orientation for recycler view from extension properties.
* `reverseLayout` - Set boolean value here. Set true to show list in reverse order.
* **

## :sparkle: Grid Layout Manager
Use this function to create grid layout manager for initialize recycler view.

![08ec7ae](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/885ca28c-a6f2-4765-8f1e-05ac69ebf45f)

* `spanCount` - Set span count as integer number. Span count is for create items per row.
* `orientation` - Set orientation for recycler view from extension properties.
* `reverseLayout` - Set boolean value here. Set true to show list in reverse order.
* **

## :sparkle: Staggered Grid Layout Manager
Use this function to create staggered grid layout manager for initialize recycler view.

![4ba33ba](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d3599eae-fc44-4252-af33-2cf621944c05)

* `spanCount` - Set span count as integer number. Span count is for create items per row.
* `orientation` - Set orientation for recycler view from extension properties.
* **

## ❇️ Populate Native Ad Views
You've to populate add created ad views for bind native ad to the native ad view.
Use this functions to populate views and watch tutorial video for better understanding.

![b9f3318](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/9f7c5fa6-7175-4526-8022-4e21c54b3825)

* `nativeAdView` - Set native ad view object from BindAdView event.
* `nativeAd` - Set native ad object from the BindAdView event.
* `tag` - Set view tag which one you've used for this view into xml code.
* `backgroundColor` - Set background color for the CallToActionView (Button).
* **

## ❇️ Finish Populating Views
You've to call this at the end of populating views to notify that populating views is finished and native ad view is read to display ad.

![fc00c84be](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/2d735911-f344-44f8-ac12-b266f611823b)

* `nativeAdView` - Set native ad view object from BindAdView event.
* `nativeAd` - Set native ad object from the BindAdView event.
* **

## ❇️ Get Ads Count
It's return total loaded ads count.

![99f6838f](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d7e61b2c-24f7-4290-acc4-2882a6a42ff7)
* **

## :sparkle: Get Adapter Position
Using this properties you can get adapter position.

![1fd1b5](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/9bda6ea9-9086-4aee-a6fb-9c8611810d01)
* **

## :sparkle: Orientation
Set recycler view orientation using this properties.

![0d9c096](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/3d2d2ff2-2b90-4001-930b-c4e07b99a222)
* **

## :sparkle: Snap Helper
To create snap helper use this properties.

![22cdf76](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/77abf823-7041-466f-b028-397278d300ba)
* **

## :sparkle: Scroll State
To handle scroll state use this properties.

![27b789](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/a8cb2035-b3fd-4166-90b4-740a37c8ef82)
* **

## ❇️ Xml Layout
Set xml file from asset to inflate native ad view or set xml code as string using block section.

![67ab24e97](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/17e1d6e9-b87e-4c47-b7c1-bae840a95ae7)

![55540678](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/354bc2d7-917e-42bd-9ad0-8c54d7384379)
* **

## ❇️ Animate Ad View
Set true to animate the native ad view on scrolling.

![b6d7f3f2a7](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/2a63c4ca-4a04-4549-b42b-35288dfc5b2f)

![7812adfb](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/1442d14a-be1e-4031-8b2e-afde0854c7db)
* **

## :sparkle: Left Swipable
Set `true` to enable left swipe on items.

![image|253x42](upload://o7SSKi787cS8SdsVcuYC2cTnyly)

![image|384x88](upload://9GXB6oDtOcMXDVPFuY5pN2AxH3h.png)
* **

## :sparkle: Swipe Left Background Color
Change background color of left swiped view.

![image|288x71](upload://yt4sWZcGegywuEgkWj4zehElA6h)

![image|460x83](upload://zW1SP7ssvMcUoRtcgrXersOciT2.png)
* **

## :sparkle: Swipe Left Label Color
Change the label color of swiped left label text.

![image|286x75](upload://2vtm1oBBRIz4pnhg8T2hzg2oDS8)

![image|412x89](upload://fbfZThX9BFgRxsKmR44yN8LBtwr.png)
* **

## :sparkle: Swipe Left Label
Change swipe left label text. Make it empty to disable swipe left label text.

![image|282x68](upload://mZd3WYQ09K2O7sPTUSbM2PBeNPg)

![image|387x76](upload://v0QdGcAGPdngtPqs597f3ZXpuDe.png)
* **

## :sparkle: Swipe Left Label Size
Change swipe left label text size.

![image|285x70](upload://psTJ8WU3ZRsC1jMiyKz8EL0XrnU)

![image|420x86](upload://cModsyvHHA8wKkphO5DHapc0SGK.png)
* **

## :sparkle: Swipe Left Icon
Set image on swipe left view. Make it empty to disable swipe left icon.

![image|284x66](upload://yTgdtXPKymuc2neWrD95aj2kqVc)

![image|378x81](upload://59mAAQtw82uuopMI5M5gFhWzHV9.png)
* **

## :sparkle: Right Swipable
Set `true` to enable right swipe.

![image|257x42](upload://p3UzT0zYNlQbJzgRncCLIGPzXto)

![image|390x80](upload://tL19lI6howvEV39iuld0qWwwBkg.png)
* **

## :sparkle: Swipe Right Background Color
Change background color of right swiped view.

![image|280x68](upload://lfSnlO35upmtTcqFeK5ZxqyW8qS)

![image|452x80](upload://aThdROzRHkfdnv0LQfPbQZqglNr.png)
* **

## :sparkle: Swipe Right Label Color
Change the label color of swiped view.

![image|284x68](upload://xIB5a5Ob0dtK9pX01llwQZFAuGu)

![image|426x90](upload://sY7HSRtiYC74gYDChPJ39Sy0QhN.png)
* **

## :sparkle: Swipe Right Label
Change the text for swipe right text. Make it empty to disable swipe right label.

![image|280x65](upload://86ReiiJEWXQ6hCaXhnhKZpNQN1D)

![image|388x81](upload://gIx2AG4HCyFNb3jl9PzHf98ythe.png)
* **

## :sparkle: Swipe Right Label Size
Change the text size of swipe right label.

![image|281x69](upload://vujQl4A7w87e9NRM6T0xmGBmf2L)

![image|409x82](upload://b9JiMyHlTaWLU4olY9RMYNp38g9.png)
* **

## :sparkle: Swipe Right Icon
Set the swipe right icon, set None or make it empty to disable swipe right icon.

![image|282x63](upload://pxKkZ5phWChbTejvgX0hSBuJlIS)

![image|375x79](upload://myBIKyCyWrmG6Myr1Ub0Jlow3AB.png)
* **

## :sparkle: Draggable
Set `true` to enable dragging items between them.

![image|257x44](upload://eIpJBRv8TVzaNo8MRdPEDfeIM9N)

![image|363x76](upload://6dUGpYqbesmlvdi9fKsah3do6zI.png)
* **

## :sparkle: Fixed Size
Set `true` to improve performance.

![image|234x42](upload://beDaN7d206LSKzoFb0r19ek9g3C)

![image|361x73](upload://ppt8S65A0hdXuL8RCSM4osRAicU.png)
* **

## :sparkle: Nested Scrolling
Set `false` to improve scrolling.

![image|254x40](upload://qh4APwt94ZJX3CaaXMst13M422F)

![image|388x74](upload://pQ2OzZuHJld2RzM9mkscoix4NKI.png)
* **

## :sparkle: Over Scroll
Set `true` to enable over scroll effect.

![image|249x39](upload://6AvKIFUiZc7qDoPrKRvn5p2sfpl)

![image|365x76](upload://mXQ3bp9zZ59sDUYDbSFrqUyU6ri.png)
* **

## :sparkle: Animation Duration
Set item animation duration in milliseconds.

![image|280x67](upload://aIi8DvK42hdNkZSMaDP7F0svijo)

![image|412x86](upload://gi21GlZS3jHtAyAMKjYpwJXRfNB.png)
* **

## :sparkle: AlwaysAnimate
Set `false` to animate only on first scroll.

![image|240x45](upload://8DXO68MtYABoK53H4qyR1h2e4Id)

![image|386x86](upload://fmCaztf6k2KIPIWSHHAmsG20P49.png)
* **

## :sparkle: Item Animator
Chage item animation from available animations.

![image|282x66](upload://z4fD1rVx4Xji8idVoUwFNaywbVD)

![image|395x84](upload://a02e9vvGmzdQ9gpxdR1fB0s4EsE.png)
* **

## :sparkle: Available Animations
Total 51+ animations are available. More animations will be added soon.

![image|690x379](upload://vsRI1ZDms4JOwayd2suaa83PswJ.png)
* **

[details="Demo blocks"]
* **
📝 <a href="https://github.com/jewelshkjony/RecyclerNativeAdView/blob/main/files/item.json">item.json</a> - Download demo template json.

📝 <a href="https://github.com/jewelshkjony/RecyclerNativeAdView/blob/main/files/small_template.xml">small_template.xml</a> - Download demo xml layout.
* **

![blocks|690x366](upload://5955TPt2CzPBLpRdgvtNjGB6tpB.png)
[/details]
* **

[details="Demo output"]
![RecyclerNativeAdDemo|240x426](upload://y5T0SdoNSvmuTc0g45RaDgnF4BB.gif)
[/details]
* **

## :receipt: Extension Specifications
* **
:android: **SDK:** 22.1.0
:man_lifting_weights: **Size:** 126 KB
:coin: **Price:** $25 <small>(One time purchase only)</small>
:coin: **Price:** $30 <small>(Lifetime support + minor updates)</small>
:coin: **Price:** $35 <small>(Lifetime support + major + minor updates)</small>
:earth_americas: **Released On:** 28 June 2023 <small>(GMT+06:00)</small>
:earth_americas: **Updated On:** 28 June 2023 <small>(GMT+06:00)</small>
:credit_card: **Payment methods:** [Binance](https://www.binance.me/en/activity/referral-entry/CPA?fromActivityPage=true&ref=CPA_0068YL77KV) | [Skrill](https://www.skrill.com/en/) | [Wise](https://wise.com/?sourceCurrency=USD&targetCurrency=BDT&sourceAmount=25) | [Pyypl](https://play.google.com/store/apps/details?id=com.pyypl) | [Xoom](https://www.xoom.com/bangladesh/send-money) | [Pay2Me](https://play.google.com/store/apps/details?id=com.jewelshkjony.pay2me) | [Paypal](https://www.paypal.com/) | **UPI** <small>(India)</small> | **bKash** <small>(Bangladesh)</small> | **Jazz Cash** <small>(Pakistan)</small>
* **

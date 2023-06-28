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

![a9178](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/c9e6a2fd-423d-41e0-b732-1ae0c51276e9)

![43e2f](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/125f0ca7-58a7-4aca-b7fa-e43ef714087e)
* **

## :sparkle: Swipe Left Background Color
Change background color of left swiped view.

![f8cd](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/8758edfa-bfa4-4ad6-a545-b4eb25988297)

![fb5439c](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/2001af6c-5f74-447b-a721-bc569259e653)

* **

## :sparkle: Swipe Left Label Color
Change the label color of swiped left label text.

![11058](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d7cfbe35-a0d5-4ea4-bf0d-2f3ccde690ce)

![6a6de57](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/ee30e749-174b-4feb-88d0-641b45476584)
* **

## :sparkle: Swipe Left Label
Change swipe left label text. Make it empty to disable swipe left label text.

![a152e](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/865b0989-5e70-402d-bfbe-611cb4306c5e)

![d95bc0080](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/2bf8ad47-1cf0-4872-83e8-cce5e901f8df)
* **

## :sparkle: Swipe Left Label Size
Change swipe left label text size.

![b2757e](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/5f0a6473-8021-4c25-b566-cc422bd741f6)

![59d0d2](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/3b58ad51-e6fe-44c1-a4f1-5a92ab5e138a)
* **

## :sparkle: Swipe Left Icon
Set image on swipe left view. Make it empty to disable swipe left icon.

![f666a062](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/0983b7b9-9276-4bec-9742-2127e4ef4a62)

![24eec2b](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/972c6e06-cea9-4c33-8bce-92a163eb0956)
* **

## :sparkle: Right Swipable
Set `true` to enable right swipe.

![afa81d5862](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/0fde9a09-76ab-46b3-94cf-7bf5ddc37fa6)

![d0870b3bc](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/395f5b25-18c3-4f07-a5dc-effebfa94592)
* **

## :sparkle: Swipe Right Background Color
Change background color of right swiped view.

![94f94472](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/7f0ae2a2-7e24-47a7-9aa3-8395681f142a)

![4c55610094d](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/79b01286-3c13-4392-912f-51444e16ac2c)
* **

## :sparkle: Swipe Right Label Color
Change the label color of swiped view.

![eca92](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/f019c272-e648-4919-b5a7-0957d78ffc9f)

![c75603f](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/90905176-bb4f-4455-a09e-2c080f984803)

* **

## :sparkle: Swipe Right Label
Change the text for swipe right text. Make it empty to disable swipe right label.

![38d7bdb9](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/fb96642c-3b87-4083-bfd4-8bc029cf4e9a)

![752b78730](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/b9411e7a-f164-4568-9ab3-1fd8bec41377)
* **

## :sparkle: Swipe Right Label Size
Change the text size of swipe right label.

![dc521f47](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/ff5339c4-4779-4aa1-a686-fdd5bd0d44eb)

![4e3fd861](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/b0a7def8-322a-4e88-83ad-ec3e8ed7f939)
* **

## :sparkle: Swipe Right Icon
Set the swipe right icon, set None or make it empty to disable swipe right icon.

![d740a](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/4c224b07-9bee-4c4c-8176-9ed3eb27bdba)

![909](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/f245955c-1ff1-4afa-8708-88d93b851c9a)
* **

## :sparkle: Draggable
Set `true` to enable dragging items between them.

![637f](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/01e843f0-0846-44c3-ada9-3bebba6687ff)

![2ba21ae](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/d2b45c59-98be-411c-becc-9a946751a669)
* **

## :sparkle: Fixed Size
Set `true` to improve performance.

![4e8418](https://github.com/jewelshkjony/RecyclerNativeAdView/assets/75406851/2281e62e-3fb3-477b-9203-836e78c213ed)

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/b/2/b21768ae8d280fe55bef2198b2c2080577721c18.png"/>

* **

## :sparkle: Nested Scrolling
Set `false` to improve scrolling.

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/b/8/b8269e4dcdeda91fe562f7538c89653e84b952ed.png"/>

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/b/5/b518745e5bf1e86a06ec497052ffd176e415fac4.png"/>

* **

## :sparkle: Over Scroll
Set `true` to enable over scroll effect.

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/2/e/2e2da4a301ceb67bba49e2c13dc3b917187f763f.png"/>

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/a/0/a0f37b307368667ccccfff54874ad8ac7c81ec14.png"/>

* **

## :sparkle: Animation Duration
Set item animation duration in milliseconds.

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/4/b/4b177dabd0cafc53c2f00f351a63b833fce7e482.png"/>

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/7/2/722c9e6f203af9edf1e354f01280f4e7c21f4e27.png"/>

* **

## :sparkle: AlwaysAnimate
Set `false` to animate only on first scroll.

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/3/c/bc1qugrtknpjz52vc4m559q7zumkc4268kp7skrsee.png"/>

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/6/b/6baf115fe1909a4e57bf0e6b0c0810f1f0c8f7ad.png"/>

* **

## :sparkle: Item Animator
Chage item animation from available animations.

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/f/5/f5c7231554933a08508ee0cdd045cd5700775ac1.png"/>

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/4/6/4616c79c732562099922a088faf1290a554c81f0.png"/>

* **

## :sparkle: Available Animations
Total 51+ animations are available. More animations will be added soon.

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/optimized/3X/d/c/dc86bbf4b0bc14e0ca90530d2e90001401cf0e75_2_690x379.png"/>

* **

<details>
<summary>Demo blocks</summary>

* **
📝 <a href="https://github.com/jewelshkjony/RecyclerNativeAdView/blob/main/files/item.json">item.json</a> - Download demo template json.

📝 <a href="https://github.com/jewelshkjony/RecyclerNativeAdView/blob/main/files/small_template.xml">small_template.xml</a> - Download demo xml layout.
* **

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/optimized/3X/2/4/2411b14e9c01fab8d11e053a17f8be55eff5dbc7_2_690x366.png"/>
</details>

* **

<details>
<summary>Demo output</summary>

<img src="https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/3X/e/e/eef448b6b3a5b5ef4e4ae0ed41d54dda6e31b613.gif"/>
</details>

* **

# More extensions
<a href="https://github.com/jewelshkjony?tab=repositories">See more extensions</a>

## :receipt: Extension Specifications

⚙️ **SDK:** 22.1.0\
🏋️‍♂️ **Size:** 126 KB\
🪙 **Price:** $25 <small>(One time purchase only)</small>\
🪙 **Price:** $30 <small>(Lifetime support + minor updates)</small>\
🪙 **Price:** $35 <small>(Lifetime support + major + minor updates)</small>\
🌏 **Released On:** 28 June 2023 <small>(GMT+06:00)</small>\
🌏 **Updated On:** 28 June 2023 <small>(GMT+06:00)</small>\
💳 **Payment methods:** [Binance](https://www.binance.me/en/activity/referral-entry/CPA?fromActivityPage=true&ref=CPA_0068YL77KV) | [Skrill](https://www.skrill.com/en/) | [Wise](https://wise.com/?sourceCurrency=USD&targetCurrency=BDT&sourceAmount=25) | [Pyypl](https://play.google.com/store/apps/details?id=com.pyypl) | [Xoom](https://www.xoom.com/bangladesh/send-money) | [Pay2Me](https://play.google.com/store/apps/details?id=com.jewelshkjony.pay2me) | [Paypal](https://www.paypal.com/) | **UPI** <small>(India)</small> | **bKash** <small>(Bangladesh)</small> | **Jazz Cash** <small>(Pakistan)</small>

## 📫 How to reach me ↓

<a href="https://t.me/jewelshkjony" target="_blank">Telegram</a> | <a href="https://wa.me/8801775668913" target="_blank">WhatsApp</a> | <a href="https://fb.com/jewelshkjony" target="_blank">Facebook</a> | <a href="https://m.me/jewelshkjony" target="_blank">Messenger</a> | <a href="https://m.youtube.com/c/JewelShikderJony?sub_confirmation=1" target="_blank">Youtube</a>

# - *DR.CARE App*

**DR.CARE** is an android app support in hospital, can be used by both Doctor and Patient.

Time spent: **X** hours spent in total

## User Stories

The following **required** functionality is completed:

* [ ]	User (Doctor/Patient) can **sign in to DR.CARE** by input ID manually or scan QRcode (provided by Receiptionist)

**DOCTOR**
* [ ]	Doctor can **view list of patient by day** in homescreen
  * [ ] Doctor can sort for specific day.
  * [ ] Data is refreshed every 5 secs.
  * [ ] List is sorted by FIFO.
  * [ ] Data is refreshed every 5 secs.
  * [ ] Doctor can **pull down to refresh list of patient**
  * [ ] User can view more patients as they scroll with [infinite pagination](http://guides.codepath.com/android/Endless-Scrolling-with-AdapterViews-and-RecyclerView). Number of patients is unlimited.
  * [ ] Differentiate status of patient (done/ not yet)
  
 * [ ] Doctor can add diagnosis and prescription for their patients (2th screen: click on item_patient in homescreen)
    * [ ] there is Reactive Programming to [reactive response](https://medium.com/@matdziu/using-rxjava-in-searchview-f1d1d5dcb8b7) to query change
 
 **PATIENT**
 * [ ] Patient can **view list of Diagnosis by day** in homescreen: default is today.
 * [ ] Patient can view prescription by click on item_diagnosis.
 * [ ] Set remind manually for individual prescription/Diagnosis.
 
 **BOTH**
 * [ ] Doctor and Patient can chat to each other.
 * [ ] Doctor and Patient can video call to each other.
 
 

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/dXdluNY.gif' title='For Patient' width='' alt='For Patient' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Picasso](http://square.github.io/picasso/) - Image loading and caching library for Android

## License

    Copyright [2017] [Team TLS]
    *Team members:
    - Samn Nguyễn
    - Đức Lộc
    - Huỳnh Hữu Tâm

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

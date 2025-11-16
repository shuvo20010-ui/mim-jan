# Gitap
> Create an GitHub issue with your screenshots without any stress.

[![Swift Version][swift-image]][swift-url]
[![License][license-image]][license-url]
[![Platform](https://img.shields.io/cocoapods/p/LFAlertController.svg?style=flat)](http://cocoapods.org/pods/LFAlertController)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Gitap offers a share extension that enable you to create an GitHub issue with your screenshots without any stress.

![gitap-demo](https://user-images.githubusercontent.com/3691498/32142379-c421f220-bcd9-11e7-9244-3d4aeb5023a0.gif)


## Why I made this app

Mobile environmet has had huge impact on web since iPhone has released in 2007. Most web trafic recently comes from mobile rather than desktop. However, no app can't be found to create an issue with mobile screenshots easily. People need to upload to some storage, such as dropbox or google drive and copy the link of images and paste it into issue descriptions. Those copy and paste task is what I'd love to eliminate.

## Limitation

- Using Imgur API, the api has limit to number of images to upload daily. The app can't be work after the api limitation. I accept all the suggestion of using other image uploader services. Tell me by issue.
    **Other sevices for uploading images**  
      - Dropbox: It has an api to produce an url to share images, however, the url expires in 4 hours after it produced. Therefore, it can't meet the requirement.   
      - GitHub: On the web browser, images can't be uploaded in issue editor page. However, no API is opened for this task.   
      - Google Drive, Google Photo, iCloud: No API is available for the requirement.   
      - AWS S3: It could be the most flexible and meet the requirement. However, it costs too much if many users use Gitap. This choice would be the best if this app can sustainably raise money.   

## Requirements

- iOS 10.0+
- Xcode 9.0+
- Github Account

## Installation

As of Octorber 2017, Gitap is beeing prepared to release in App Store, which means you need to set up an environment to run Gitap. Here's how.

1. Clone the repository into your local environemnt.  
    `$git clone https://github.com/justin999/gitap.git`
2. run in terminal  
    `$ carthage update --platform iOS`
3. find the file named `gitap/Configs.swift.example`. Rename it from `Configs.swift.example` into `Configs.swift`
4. Get GitHub app client id and client secret. See detail in [GitHub documentation](https://developer.github.com/apps/building-integrations/setting-up-and-registering-oauth-apps/registering-oauth-apps/)
5. Get Imgur app client id. See detail in [Imgur Documentation](https://apidocs.imgur.com/#authorization-and-oauth)
6. Type client id and secrets in `Configs.swift`
7. Build and Run. You should see run the application!

## Contribute

We would love you for the contribution to Gitap, check the ``LICENSE`` file for more info.

## Meta

Justin – [Twitter:@justin999_](https://twitter.com/justin999_) – [Facebook:Koichi Justin Sato](https://www.facebook.com/koichi.sato.aow)

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/justin999/github-link](https://github.com/justin999/)

[swift-image]:https://img.shields.io/badge/swift-3.0-orange.svg
[swift-url]: https://swift.org/
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
[codebeat-image]: https://codebeat.co/badges/c19b47ea-2f9d-45df-8458-b2d952fe9dad
[codebeat-url]: https://codebeat.co/projects/github-com-vsouza-awesomeios-com
[
    {
        "key": "datr",
        "value": "vGYZaZSVxkgdE4JmbHhWOTlC",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.325Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "sb",
        "value": "vGYZaWow544fIcDTTWIacJiO",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "m_pixel_ratio",
        "value": "1.875",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "wd",
        "value": "385x854",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "c_user",
        "value": "61568706302157",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "xs",
        "value": "47%3A_0lO3STwwm1Www%3A2%3A1763272421%3A-1%3A-1",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "fr",
        "value": "0pVrHdRJlhyGHlEGo.AWfszRVBCyy42UYD4cwBvKHmjdP4cfdrw74xaTdvP-3qZbEm148.BpGWa8..AAA.0.0.BpGWb1.AWcOrwHb4aVGriOeanPwYc47zjM",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "locale",
        "value": "en_US",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "pas",
        "value": "61568706302157%3A2UtY0mNpaT",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "wl_cbv",
        "value": "v2%3Bclient_version%3A2986%3Btimestamp%3A1763272437",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "fbl_st",
        "value": "101423842%3BT%3A29387873",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    },
    {
        "key": "vpd",
        "value": "v1%3B766x384x1.875",
        "domain": "facebook.com",
        "path": "/",
        "hostOnly": false,
        "creation": "2025-11-16T05:56:09.327Z",
        "lastAccessed": "2025-11-16T05:56:09.327Z"
    }
]

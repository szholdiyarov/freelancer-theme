---
layout: default
modal-id: 3
date: 2017-04-18
img: happy-drive.png
alt: image-alt
project-date: March 2015 - May 2016
client: Hired
client_url: upwork.com
category: Android
description: <h3></h3><font color="#334d4d"> The <b>HappyDrive</b> app is designed and developed for small and medium size business CEOs. They use this to save and then share their contact details using Photo/Video or NFC with QR code. A user typically saves his email, phone numbers and media content. He also able to browse other business cards and take actions like/comment on them. <h4>Technical description.</h4> When I was working on this project the most challenging experience was to implement reader and generator of QR code. I decided to make this feature as a service for the app. I created a QR contract(interface) which was describing what functionality it can provide to clients and then implemented this contract as a service. The QRService itself was containing protected QRCameraService(handling camera opening/closing/pausing/lifecycle and detecting QR) protected QRReaderService(takes image and processing it, either return null or QR content). This gave me a good and easy to use QR API which was responsible for its own camera handling and lifecycle callbacks handling(which was connected to calling context). I only needed to delegate the "readQr" command to it. </font>
url_market: https://play.google.com/store/apps/details?id=kz.telecom.happydrive
url_title: Play Market
using: java 8
---

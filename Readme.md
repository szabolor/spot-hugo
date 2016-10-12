SPOT hugo photography theme
===========================

Hugo theme for a responsive photography site with nested albums, justified gallery and full-screen lightbox.
Template may contain logos and labels which copyrights belong to "BME VIK SPOT Fotókör".

#WiP!

##Nested gallery listing example
```toml
+++
title = "dezso"
date = "2015-11-09T00:00:00Z"
type = "sublist"
levels = [
  "4c6e3f4d-af33-4bfa-a9ce-b662d82fe416",
  "4c6e3f4d-af33-4bfa-a9ce-b662d82fe416"
]
uuid = "4c6e3f4d-af33-4bfa-a9ce-b662d82fe416"
events = [ ]
cover = "400/1109-052000-csenge.jpg"
gallerybase = "/photos/2015/20151109_dezso/vagas"
+++
```

##Photo gallery example
```json
{
  "title": "Party",
  "date": "2015-11-09T00:00:00Z",
  "gallerybase": "/photos/2015/20151109_dezso/buli",
  "cover": "400/1109-213549-csenge.jpg",
  "levels": [
    "4c6e3f4d-af33-4bfa-a9ce-b662d82fe416",
    "0011889f-98ae-476a-a8e1-c50e3014c458"
  ],
  "uuid": "0011889f-98ae-476a-a8e1-c50e3014c458",
  "thumbprefix": 400,
  "webprefix": 2048,
  "photos": [
    {
      "height": 1365,
      "width": 2048,
      "filename": "1109-210816-csenge.jpg"
    },
    {
      "height": 1365,
      "width": 2048,
      "filename": "1109-210846-csenge.jpg"
    },
}```


##Screen captures:

![photswipe lightbox](https://github.com/szabolor/spot-hugo/raw/master/readme_img/lightbox.jpg "Photoswipe in action")
![gallery](https://github.com/szabolor/spot-hugo/raw/master/readme_img/photos.jpg "Justified layout of photos")
![year summary](https://github.com/szabolor/spot-hugo/raw/master/readme_img/yearlist.jpg "Year summary by month")

Powered by:
 - gallery module: [Photoswipe](https://github.com/dimsemenov/PhotoSwipe)
 - justified layout: [Flickr's justified layout](https://github.com/flickr/justified-layout)
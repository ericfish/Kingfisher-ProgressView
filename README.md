# Kingfisher-ProgressView
Adding a progress view while images are downloaded using Kingfisher
![]()(example.jpg)


## Installation
Add UIImageView+ProgressView.swift to your project

## Usage
```
`img.kf_setImageWithURL(NSURL(string: imgURL)!,
placeholderImage: UIImage(named: "photo-placeholder"),
options: KingfisherOptions.None,
progressBlock: nil,
completionHandler: nil,
usingProgressView: nil
)
```
`## Thanks
The idea for this project came from [ SDWebImage-ProgressView]()([https://github.com/JJSaccolo/UIActivityIndicator-for-SDWebImage][2]).

[2]:	https://github.com/kevinrenskers/SDWebImage-ProgressView


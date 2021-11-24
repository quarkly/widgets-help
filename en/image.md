# Image

![Image image](https://github.com/quarkly/widgets-help/raw/main/images/Image.png)

## 📖 Detailed overview

The Image primitive represents an image
The Image properties specify the source of the image, the cropping method,
and alignment when cropping. You can also adjust sources for devices with
high pixel densities and for different layouts. The Loading property helps
speed up page loading.

## ⚙️ Usage

Add the component to the page

## 🧩 Props

| Prop name       | Description                                                                                                                                                                           |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| object fit      | Defines the way the content should fill the container relative to its height and width                                                                                                |
| object position | Used with object fit and specifies the position of the contents inside the container                                                                                                  |
| src             | Image link                                                                                                                                                                            |
| srcset          | A comma-separated list of one or more lines defining a set of possible images to display in the browser. Each line of the list must contain a pixel width or pixel density descriptor |
| sizes           | A list of image sizes for different page sizes. It contains comma-separated media queries with image width values                                                                     |
| alt             | Alternative text description of the image will be displayed in the browser if the image couldn't be loaded                                                                            |
| title           | The image title that will be shown as a tooltip when you hover over the image                                                                                                         |
| loading         | Postpone image loading outside the screen                                                                                                                                             |

## 🗓 Changelog

- 19/10/2021 (0.2.60)
- First version

## 📮 Feedback

If you encountered a bug, please contact us so we can fix it promptly. We’re rapidly developing, so don’t hesitate to send us your feedback and request new features you would like to see added. Feel free to share what you’re working on - we **love** to see what you’re building with Quarkly!

[Help with widgets](https://community.quarkly.io/c/requests/11)

[We're on Discord](https://discord.gg/SuF9vCMJGW)

[Our Twitter](https://twitter.com/quarklyapp)

[dev@quarkly.io](mailto:dev@quarkly.io)

## 📝 License

Licensed under the ISC License

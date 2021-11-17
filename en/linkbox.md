# LinkBox

## 📖 Detailed overview

The LinkBox primitive is used for:

- creating a link to other pages;
- creating a link to parts within the current or another page (anchor link);
- creating a link to open files;
- creating a link to write an email;
- creating a link with a phone number.

In the LinkBox properties, you can set the target address, the tab
behavior when you click the link, the LinkBox behavior when transferring
lines and when overflowing.

## ⚙️ Usage

Add the component to the page

## 🧩 Props

| Prop name     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| href          | Sets the address to go to when the link is clicked                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| target        | You can define the window where the page opened by the link will be loaded: <ul>   <li> `_self` - loads the page into the current window</li>   <li> `_blank` - loads the page into a new browser window</li>   <li> `_parent` - loads the page into the frame parent. If there are no frames, this value works as `_self`</li>   <li> `_top` - cancels all frames and loads the page in the full browser window. If there are no frames, this value works as `_self`</li>   </ul> |

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

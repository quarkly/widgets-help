# Link

![Link image](https://github.com/quarkly/widgets-help/raw/main/images/Link.png)

## 📖 Detailed overview

The Link primitive is used for:

- creating a link to other pages;
- creating a link to parts within the current or another page (anchor link);
- creating a link to open files;
- creating a link to write an email;
- creating a link with a phone number.

In the Link properties, you can set the target address, the tab behavior
when you click the link, the Link behavior when transferring lines and
when overflowing.

## ⚙️ Usage

Add the component to the page

## 🧩 Props

| Prop name     | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| overflow-wrap | Sets whether the browser should insert line breaks within an otherwise unbreakable string to prevent text from overflowing its line box                                                                                                                                                                                                                                                                                                                                            |
| word-break    | Sets whether line breaks appear wherever the text would otherwise overflow its content box                                                                                                                                                                                                                                                                                                                                                                                         |
| white-space   | Sets how white space inside an element is handled                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| text-indent   | Sets the length of empty space (indentation) that is put before lines of text in a block                                                                                                                                                                                                                                                                                                                                                                                           |
| text-overflow | Sets how hidden overflow content is signaled to users                                                                                                                                                                                                                                                                                                                                                                                                                              |
| hyphens       | Specifies how words should be hyphenated when text wraps across multiple lines                                                                                                                                                                                                                                                                                                                                                                                                     |
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

## Dify Plugin for Bilibili Search

**Author:** jingfelix
**Version:** 0.0.3
**Type:** tool

### Description

This Dify plugin allows you to search for videos and retrieve video information from Bilibili.

### Tools

This plugin provides the following functionalities:

*   **Search Videos (`bilibili_search`):** Allows you to search for videos on Bilibili using keywords.
*   **Get Video Info (`bilibili_get_video_info`):** Allows you to retrieve detailed information about a specific Bilibili video using its bvid.

### Setup

1.  **Obtain your Bilibili Cookies:**
    *   Log in to your Bilibili account in your web browser.
    *   Open the browser's developer tools (usually by pressing F12).
    *   Go to the "Console" tab.
    *   Type the following command and press Enter:
        ```javascript
        console.log(document.cookie);
        ```
    *   This will display your cookies in the console


2.  **Configure the Plugin in Dify:**
    *   When adding or configuring the Bilibili Search plugin in Dify, you will be prompted to enter your Bilibili cookies in the credentials section.
    *   Paste the copied cookies into the designated field.
    *   This will allow the plugin to make authenticated requests to Bilibili on your behalf.

![_assets/auth.png](_assets/auth.png)

3. **Enjoy the plugin!** You can now use the Bilibili Search tools within your Dify applications.

![_assets/example.png](_assets/example.png)

### Privacy Policy

Check the [Privacy Policy](PRIVACY.md) for more information on how we handle your data.




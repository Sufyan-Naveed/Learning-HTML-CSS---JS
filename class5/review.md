Embedding YouTube videos into an HTML document is a common practice for sharing videos on websites. Let's review the essential elements and attributes involved in embedding a YouTube video, focusing on the `<iframe>` tag, `src`, `height`, and `width`.

### HTML Video Embedding from YouTube

Here's an example of embedding a YouTube video in an HTML document:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    HTML video embedding from YouTube

    <iframe width="460" height="500" src="https://www.youtube.com/embed/y_I2YOP91Is?si=x0lkEqAHRpTfR2Fy"
        title="YouTube video player" frameborder="1"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</body>

</html>
```

### Key Elements and Attributes

#### 1. `<iframe>`
- The `<iframe>` element is used to embed another HTML page within the current page. In this case, it embeds a YouTube video.
- Example:
    ```html
    <iframe src="URL"></iframe>
    ```

#### 2. `src`
- The `src` attribute specifies the URL of the page or resource to be embedded. For YouTube videos, this URL is formatted to include the video ID.
- Example:
    ```html
    <iframe src="https://www.youtube.com/embed/y_I2YOP91Is"></iframe>
    ```

#### 3. `height`
- The `height` attribute specifies the height of the embedded frame in pixels.
- Example:
    ```html
    <iframe height="500"></iframe>
    ```

#### 4. `width`
- The `width` attribute specifies the width of the embedded frame in pixels.
- Example:
    ```html
    <iframe width="460"></iframe>
    ```

### Additional Attributes

#### `title`
- The `title` attribute provides a brief description of the content within the `<iframe>`. This is useful for accessibility.
- Example:
    ```html
    <iframe title="YouTube video player"></iframe>
    ```

#### `frameborder`
- The `frameborder` attribute specifies whether or not to display a border around the frame. The value "1" shows the border, while "0" hides it.
- Example:
    ```html
    <iframe frameborder="1"></iframe>
    ```

#### `allow`
- The `allow` attribute specifies a list of features the embedded content is allowed to use. This can include features like autoplay, fullscreen, and more.
- Example:
    ```html
    <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
    ```

#### `referrerpolicy`
- The `referrerpolicy` attribute controls how much referrer information is sent when fetching the frame content.
- Example:
    ```html
    <iframe referrerpolicy="strict-origin-when-cross-origin"></iframe>
    ```

#### `allowfullscreen`
- The `allowfullscreen` attribute allows the video to be viewed in fullscreen mode.
- Example:
    ```html
    <iframe allowfullscreen></iframe>
    ```

### Summary

- **`<iframe>`**: Embeds an external HTML page or resource within the current page.
- **`src`**: Specifies the URL of the content to embed.
- **`height`** and **`width`**: Define the size of the embedded frame in pixels.
- **`title`**: Provides a brief description for accessibility.
- **`frameborder`**: Shows or hides the border around the frame.
- **`allow`**: Specifies allowed features for the embedded content.
- **`referrerpolicy`**: Controls the referrer information sent.
- **`allowfullscreen`**: Enables fullscreen mode for the video.

Embedding a YouTube video with these attributes ensures that it is displayed correctly and offers various functionalities, enhancing the user experience on your website.
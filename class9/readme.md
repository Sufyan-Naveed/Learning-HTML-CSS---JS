### Multimedia Elements in HTML

HTML provides various tags for embedding multimedia elements like videos and audio into web pages. Below are the key tags and their attributes:

#### 1. **Embedding Videos (`<video>` tag)**

The `<video>` tag is used to embed video content in an HTML document. 

##### Basic Syntax:
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

##### Attributes:
- **`src`**: Specifies the URL of the video file.
- **`controls`**: Adds video controls, like play, pause, and volume.
- **`autoplay`**: Automatically starts playing the video when the page loads.
- **`loop`**: Replays the video after it ends.
- **`muted`**: Mutes the audio of the video.
- **`width`** and **`height`**: Define the dimensions of the video player.

##### Example:
```html
<video width="600" height="400" controls>
  <source src="example.mp4" type="video/mp4">
  <source src="example.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

#### 2. **Embedding Audio (`<audio>` tag)**

The `<audio>` tag is used to embed audio content in an HTML document.

##### Basic Syntax:
```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3">
  Your browser does not support the audio element.
</audio>
```

##### Attributes:
- **`src`**: Specifies the URL of the audio file.
- **`controls`**: Adds audio controls, like play, pause, and volume.
- **`autoplay`**: Automatically starts playing the audio when the page loads.
- **`loop`**: Replays the audio after it ends.
- **`muted`**: Mutes the audio.

##### Example:
```html
<audio controls>
  <source src="song.mp3" type="audio/mp3">
  <source src="song.ogg" type="audio/ogg">
  Your browser does not support the audio element.
</audio>
```

#### 3. **Adding Captions and Subtitles**

Captions and subtitles can be added to videos using the `<track>` tag inside the `<video>` element. The `<track>` tag specifies text tracks for the `<video>` and `<audio>` elements.

##### Basic Syntax:
```html
<video width="600" height="400" controls>
  <source src="example.mp4" type="video/mp4">
  <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">
  Your browser does not support the video tag.
</video>
```

##### Attributes:
- **`src`**: Specifies the URL of the track file (e.g., `.vtt` for WebVTT).
- **`kind`**: Specifies the type of text track (e.g., subtitles, captions).
- **`srclang`**: Specifies the language of the track text.
- **`label`**: Provides a user-readable title for the track.

##### Example:
```html
<video width="600" height="400" controls>
  <source src="example.mp4" type="video/mp4">
  <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">
  <track src="subtitles_es.vtt" kind="subtitles" srclang="es" label="Spanish">
  Your browser does not support the video tag.
</video>
```

This covers the basics of embedding videos and audio and adding captions and subtitles in HTML.
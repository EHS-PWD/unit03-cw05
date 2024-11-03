### **Lesson 5: Audio and Source Tags**

#### **Objective:**  
Students will learn how to organize their files by creating an `audio` folder, then add a locally hosted audio file to a webpage using the `<audio>` tag, ensuring compatibility with MP3 and OGG formats.

---

### **Instructions**

#### **Step 1: Find a Copyright-Free MP3 Audio File**
1. Visit [Pixabay Music](https://pixabay.com/music/).
2. Search for a copyright-free MP3 audio file that you’d like to use in your media gallery. Download the MP3 file to your computer.

#### **Step 2: Convert the MP3 File to OGG Format**
3. Go to [Convertio](https://convertio.co/mp3-ogg/).
4. Upload your downloaded MP3 file and convert it to OGG format.
5. Once the conversion is complete, download the OGG file to your computer.

#### **Step 3: Organize Files in the `media-gallery` Folder**
6. In your `media-gallery` folder, create a new folder called `audio`.
7. Move both the MP3 and OGG files into the new `audio` folder, so your file structure looks like this:
   ```
   media-gallery/
   ├── audios/
   │   ├── your-audio-file.mp3
   │   └── your-audio-file.ogg
   ├── images/
   │   ├── your-image-file.jpg
   │   ├── your-image-file.jpg
   │   └── your-image-file.jpg
   ├── videos/
   │   └── your-video-file.mp4
   ├── iframe.html
   └── index.html
   ```

#### **Step 4: Open `iframe.html`**
8. In VSCode, open the `iframe.html` file within the `media-gallery` folder.

#### **Step 5: Add a Section for Audio Content**
9. Below the existing video section, add a new heading to indicate the start of the audio content:
   ```html
   <h2>Audio Content</h2>
   ```

#### **Step 6: Embed the Audio Files Using the `<audio>` Tag**
10. Below the new heading, use the `<audio>` tag to add both the MP3 and OGG audio files for compatibility. Reference the audio files in the `audio` folder:
    ```html
    <audio controls>
        <source src="audio/UPDATE WITH YOU AUDIO FILE NAME" type="audio/mp3">
        <source src="audio/UPDATE WITH YOU AUDIO FILE NAME" type="audio/ogg">
        Your browser does not support the audio tag.
    </audio>
    ```
    - **Explanation of attributes**:
      - `controls`: Adds playback controls like play, pause, and volume.
      - `<source src="audio/UPDATE WITH YOU AUDIO FILE NAME" type="audio/mp3">`: Specifies the MP3 file in the `audio` folder.
      - `<source src="audio/UPDATE WITH YOU AUDIO FILE NAME" type="audio/ogg">`: Specifies the OGG file in the `audio` folder.

11. Add a caption or short description below the audio player to explain the content:
    ```html
    <p>This is a copyright-free audio file from Pixabay, stored in the audio folder with both MP3 and OGG formats for compatibility.</p>
    ```

#### **Step 7: Save and Preview**
12. Save `iframe.html` and open it in a web browser to preview the audio player with playback controls.
13. You should see the audio player below the videos.

#### **Step 8: Submit Your Work**
14. Once you've confirmed that the audio looks good, submit the following:
   - Take a screeshot of your `iframe.html` page by holding `CMD+SHIFT+4`, then use your mouse to select the webpage. Add screenshot to the media-gallery folder.
   - The zipped media-gallery folder with the index.html file, iframe.html, screenshot.png, screenshot2.png, images folder. **DO NOT INCLUDE THE AUDIO AND VIDEO FOLDERS.**
      - *The audio and video folders are too large and it will not upload to Google Classroom.*
   - Upload the zip file to the classwork assignment on Google Classroom

### **Outcome**
- Students will have successfully organized their files, created an `audio` folder within `media-gallery`, and embedded a locally hosted audio file in both MP3 and OGG formats for broad compatibility.
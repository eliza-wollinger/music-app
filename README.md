![Banner](https://user-images.githubusercontent.com/57842220/228262237-997d257c-a219-49cb-bbd1-21dc92112e97.png)

This music web application has an elegant and intuitive interface, designed using Figma and built using the ReactJS framework.

With ReactJS, the application provides real-time music playback, smooth transitions between pages, and fast response times, all essential for a perfect and enjoyable user experience.

To create a visually appealing and consistent design across all pages and components, the application uses Tailwind, a CSS framework. The pre-built components and classes that Tailwind allows, made it easy for me to customize the layout, typography, and color palette of the application, resulting in a professional and polished appearance.

One of the main features of this application would be its integration with RapidAPI. This API offers a wide range of music-related information, such as metadata, information about artists, and music streaming services, which the application can leverage to provide users with a more personalized discovery experience.

## ✏️ Project Concept and Design

The music web app design process started with a thorough search of the top music players on the market, including Spotify, Apple Music, and SoundCloud. This research helped identify strengths and weaknesses in terms of usability.

I then created low fidelity wireframes as starter examples. These wireframes focused on the user experience and functionality of the app, ensuring the interface was user-friendly and easy to navigate.

Using Figma I developed high fidelity prototypes that incorporated visual elements such as typography, color schemes and graphics.

![Colors](https://user-images.githubusercontent.com/57842220/228262836-a1b0e5c1-e631-400a-ba20-ddd47b794817.png)

In addition to the design considerations mentioned above, I also considered the importance of light and dark modes in the application's design. Users have different preferences when it comes to the brightness of their screens, and the ability to switch between light and dark modes can greatly improve the user experience.

To achieve this, I carefully selected color schemes to ensure that the app's design elements were optimized for both light and dark modes. This included testing the color contrast, adjusting the text size and weight, and tweaking the graphics to ensure they look great in both modes.

![Light and Dark Mode](https://user-images.githubusercontent.com/57842220/228262480-f49d226b-cd5e-491f-bdc3-8352bd90f519.png)

### Functionalities

1. **Music Player** - Users can select any song from the app and play it with ease. The music player comes equipped with basic controls, including options for playing the previous song, skipping to the next song, and pausing or playing the current song. Additional features like song details such as the song's name, author, volume control, repeat function, and duration are also included for added convenience.

2. **Homepage** - Users can browse by genre and discover the top songs for each genre. This feature allows for easy exploration of new music and helps users find their favorite songs more quickly.

3. **Explore** - Users can choose a country and discover the top songs for that country. This feature helps users discover new music from around the world and explore different music cultures.

4. **Artists Page** - Users can access a list of the most famous artists from the app's database. This feature makes it easy for users to find their favorite musicians and explore their discography.

5. **Artist Detail Page** - Users can access additional information about an artist, including their biography, discography, and all of their most popular songs. This feature helps users discover more about their favorite artists and explore their music in greater depth.

6. **Song Detail Page** - Users can access detailed information about a specific song, including its music video, lyrics, and a list of similar songs. This feature helps users discover new music based on their preferences and explore different genres and artists.


## ⚙️ Technologies and Setup

### System Requirements

To get started with development, you need to install few tools

1. **git**
   
   `git` version 2.13.1 or higher. Download [git](https://git-scm.com/downloads) if you don't have it already.

   To check your version of git, run:

   ```shell
    git --version
   ```

2. **node**
   
   `node` version 16.15.1 or higher. Download [node](https://nodejs.org/en/download/) if you don't have it already.

   To check your version of node, run:

   ```shell
    node --version
   ```

3. **npm**
  
   `npm` version 5.6.1 or higher. You will have it after you install node.

   To check your version of npm, run:

   ```shell
    npm --version
   ```

### Setup

To set up a development environment, please follow these steps:

1. **Clone the repo**

   ```shell
    git clone https://github.com/eliza-wollinger/music-app.git
   ```

2. **Change directory to the project directory**

    ```shell
    cd music-app
    ```

3. **Install the dependencies**
   
    ```shell
     npm install
    ```

    If you get an error, please check the console for more information.

    If you don't get an error, you are ready to start development.

4. **Run the app**
   
    ```shell
    npm run dev
    ```

    Project will be running in the browser.

    Open [http://localhost:3000](http://localhost:3000) to view it in your browser.






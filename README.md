# Skip or Play Liked Songs - Spotify/Spicetify
Spicetify extension that allows users to only played like songs in a collection (playlist/album/etc..) or skip them. Can also be disabled.

Maintained version of [@Tetrax-10](https://github.com/Tetrax-10)'s archived [Skip-or-Play-Liked-Songs](https://github.com/Tetrax-10/Spicetify-Extensions/tree/master/Skip-or-Play-Liked-Songs) extension.

Original repo: [Github](https://github.com/Tetrax-10/Spicetify-Extensions)

# Version

Date: 2023-12-10

Spicetify version: 2.28.1

Spotify version: 1.2.26.1187.g36b715a1

# Usage
- If you don't have spicetify installed:
  - [Spicetify-Getting Started](https://spicetify.app/docs/getting-started)
- ```git clone https://github.com/giorgosathanasopoulos/skip-or-play-liked-songs```
- ```cd skip-or-play-liked-songs```
- ```npm install``` or ```yarn```
- ```npm run build-local``` or ```yarn build-local```
- ```cp dist/skip-or-play-liked-songs.js ~/.spicetify/Extensions/``` (Note: POSIX, Windows users modify accordingly)
- If it's your first time using spicetify:
  - ```spicetify backup apply```
- ```spicetify config extensions skip-or-play-liked-songs.js```
- ```spicetify apply```
- Next time you start Spotify, you should have a menu item ```Play/Skip Liked Songs``` under your profile
  picture's click-menu. Hover over the item and select the mode to use.

# Note 
I will try to push this maintained version in the spicetify marketplace for ease-of-use.

I will update with my progress.


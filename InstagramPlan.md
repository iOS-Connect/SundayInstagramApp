# Instagram App Project Plan #

It would be really great to get out project group working through a multi-week project.

## High Level Plan ##
Take a few weeks to build an instagram style app using a custom backend, (probably firebase). The rest of the features are TBD, at this point.

# Week 1 #

Have 10, photos and some associated metadata (poster's name, caption) to use as a base for a simple scrolling collection view.
 - UICollectionView
 - Custom Cell
 - Cell Re-use
 - Storyboards and autolayout (for new members)
 - JSON Parsing

### Required Preparation ###
10 photos
JSON data usernames, comments, photonames (to go with photo files)

(I know it might feel like we should start with cocoapods and firebase sdk, but I think it's important to get something on the screen that people can see and be excited about)

Cocoapods + Firebase SDK
(Possible difficulties due to HackerDojo Networking) Maybe we should have a local copy of the sdk to be distributed with the photos? Perhaps we should integrate manually instead of using cocoapods? Maybe we should do this first when we know everyone will have internet?

# Week 2 #

Your own photo stream. Be able to post photos to firebase, and retrieve a list of photos, which you have posted. No friending, liking, commenting yet just photos in a timeline. (need to keep it simple and do-able)

**Maybe we should setup the backend for this? and just have everyone call into one instace of firebase? using the same api keys and stuff?**

# Week 3 #

Settings? Friending? Liking?

# Week 4 #

Animations, custom transitions, photo filters, Auto sizing cells,


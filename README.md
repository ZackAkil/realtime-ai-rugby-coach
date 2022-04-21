# Realtime AI rugby coach
My ambitious project to use a combination of ML, hardware, and cloud tech to capture and conquer the rugby pitch.


## Step 1 : Capture
Using 360 video capture to record the entire pitch.

## Step 2 : Track
Use custom object tracking models to track players.

## Step 3 : Transform
Using the player tracks and some mathmatical things that I need to learn, generate a neat 2D orthoganal projection of the player tracks.

## Step 4 : Analyse
Using the clean 2D player tracks, train models to detect when specific plays are excuted and when score happen.

## Step 5 : Learn the game
Feed the time timeline of data (plays, scores, location on pitch) into a reinforcement learning model to devise a model that can predict which plays have the highest chance of resulting in scores. 

## Step 6 : Take it to the pitch
Have all this run in real-time at the side of the pitch to give instant tactical suggestions.

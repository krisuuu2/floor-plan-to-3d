# Prompt: floor plan to a 3D model you can walk through

Use it in claude.ai (or any Claude with artifacts). Attach the floor plan as an image, a photo of the plan from a listing works.

## Step 1: build the model

```
This is the floor plan of an apartment I am thinking of renting. Build me a 3D model of it that I can walk through in the browser.
```

## Step 2: give it one real measurement

A plan has no real size on it, so Claude has to guess the scale. Give it one number you know, like the width of the front door, and everything else scales from that.

```
The front door of the flat is 90 cm wide. Please rescale the model to that. Then put a three-seat sofa, 2.2 m wide, in the living room against the longest wall, and tell me if I can still walk around it comfortably.
```

Change 90 cm to your real door width, and the sofa to the furniture you want to test.

## What to check

- Windows and anything drawn with dashes are guesses. Compare them with the photos from the listing.
- Ask Claude to list the room sizes it assumed, then check one of them with a tape measure.

In my test the total area changed from 74.5 m² to 81.6 m² after the door measurement, so the first scale is only an estimate.

## Plan used in the video

"Grundriss Typ P2" by Martin Pöschel, Wikimedia Commons, CC BY-SA 3.0.

# CompyCore Records Music Production Tips

## General

- When producing/mixing and especially when mastering, be sure to listen to your track on multiple headphones and speakers to get a decent idea of how it'll sound to the average listener.
- If your mix feels "muddy," remove some bass with an EQ (it's easy to make your reverb muddy if you leave in too much bass).
- Using an automation in your DAW to lower the volume of your track 1 db right before the chorus and then snapping the volume back as the chorus hits helps add some extra power to the chorus.
- Try to keep 3-10 db of headroom on your master track (meaning keep the peak volume at -3 to -10 db) during producing. Get the volume back in the mastering phase using compressors and EQ.

## EQ

- Slap a lowcut on your kickdrums (sometimes as high as 500 hz with a shallow slope) to help them pop.

## Ableton

- When importing audio samples in Ableton, be aware of the "autowarp long samples" preference. If your audio [seems slightly off key or a bit jittery](https://www.reddit.com/r/ableton/comments/caywxv/weird_stuttering_on_imported_mp3_files/), check to see if Ableton automatically turned on sample warping for that sample.

## Miscellaneous

- If you download an audio file from Discord, it will likely be compressed in a way that Ableton will not like. You can use `ffmpeg` to reconvert it to fix the Ableton "this file has DLC or is corrupted" message.

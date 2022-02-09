
<!--####################################################################################################################-->
# Export
<!--####################################################################################################################-->

  - GIF
    - use `Animated GIF` (*regular `GIF` exports individual frames*)

  - All Clips, Individually
    - Approach 1
      - Steps
        - clear `In`/`Out` points
        - `File > Project Manager`
          - @ `Resulting Project`
            - [x] `Consolidate and Transcode`
            - `Source`: `Individual Clips`
      - Settings
        - `Include Handles`: export additional frames outside of `In`/`Out` points
      - Limitations
        - doesn't apply [Clip, Master] [Effects, Transitions] to exported clips
    - Approach 2
      - Steps
        - @ Each Clip
          - `Clip Menu > Nest`
        - @ Project Bin
          - Select clips
          - [`Ctrl` + `M`] to show `Export > Media`


<!--####################################################################################################################-->
# Settings
<!--####################################################################################################################-->

  - `Menu > Sequence > Selection Follows Playhead`
    - auto-select Clips when moving Playhead

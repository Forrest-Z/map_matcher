# map_matcher
map_matcher is a ros node which matches a source map to a reference map.

## Usage example
Create a map with gmapping. When done, save ```map.yaml``` and ```map.pgm``` to ```~/maps/``` .
Then, run gmapping again. While gmapping is running, launch the localizer_example:
```$roslaunch map_matcher localizer_example.launch```

After successful map matching, both maps should be visible in rviz, and transforms between the two map frames will be published to tf.




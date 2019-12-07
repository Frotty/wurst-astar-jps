# Wurst Astar Jump Point Search

Usage example:

```
let finder = new Pathfinder(first, mpos)
finder.outputPath = true
finder.setCond() (pos) ->
    return pos.isTerrainWalkable()

finder.search() (result) ->
    if result.success
        Log.info("Path found. Nodes = " + result.path.size().toString())

```

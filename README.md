# hoistables

A tap of tested install skills for real apps. Add the tap, install an app, and ask your agent to run it. The app comes up in a sandbox on your machine, its own tests run there, and you get an honest score. Nothing you already run is touched.

## Use it

    /plugin marketplace add 3dl-dev/hoistables
    /plugin install agent-dyno@hoistables

Then in your agent:

    /agent-dyno:hoist

Same shape for the others: `/honcho:hoist`, `/hoistable:hoist` (which stands the Hoistable framework up on your machine).

Each app is its own plugin, so nothing collides, and anyone can self-host their own app the same way from their own repo without listing here. The tools that build and run these live in [3dl-dev/hoistable](https://github.com/3dl-dev/hoistable).

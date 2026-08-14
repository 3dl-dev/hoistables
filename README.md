# hoistables

A tap of tested install skills for real apps. Add the tap, install an app, and ask your agent to run it. The app comes up in a sandbox on your machine, its own tests run there, and you get an honest score. Nothing you already run is touched.

## Use it

    /plugin marketplace add 3dl-dev/hoistables
    /plugin install agent-dyno@hoistables

Then in your agent:

    /agent-dyno:deploy

Same shape for the others: `/honcho:deploy`, `/hoistable:deploy`. Each app is its own plugin named after the app, so nothing collides and no framework branding lands on anyone's product. The tools that build and run these live in [3dl-dev/hoistable](https://github.com/3dl-dev/hoistable).

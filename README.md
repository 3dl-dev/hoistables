# hoistables

A tap of tested hoist skills for real apps. Each one is a self-building `SKILL.md`: install it, ask your agent to hoist the app, and it fetches a checksum-verified harness, brings the app up in a throwaway sandbox on your machine, runs the app's own tests there, and reports an honest score. Nothing you already run is touched.

These are deployment recipes, the way a Homebrew tap carries formulas. Naming an app here is descriptive; it does not imply affiliation or endorsement.

## Use it

    /plugin marketplace add 3dl-dev/hoistables
    /plugin install agent-dyno@hoistables

Then ask your agent to hoist agent-dyno. Same for `honcho@hoistables` and `hoistable@hoistables` (which stands the hoistable framework up on your target).

The tools that make and run these, `/hoistable` (build one) and `/hoist` (run one), live in [3dl-dev/hoistable](https://github.com/3dl-dev/hoistable).

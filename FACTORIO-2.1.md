# Factorio 2.1 compatibility

The New Game+ configuration retains the supported technology price multiplier. Recipe and technology expensive-mode selectors were removed because Factorio 2.1 provides a single mode. Water controls are shown once, the advanced frame uses the current GUI style, and noise expressions use stable name ordering without removed prototype attributes. Research resets use LuaTechnology.saved_progress.

Native Factorio 2.1.24 headless test scenarios exercised the actual mod GUI and both world-regeneration paths (research preserved and reset). Base and Quality-without-Space-Age profiles passed: the character and inventory survived, rare/legendary qualities were retained when enabled, partially used ammunition and repair-pack durability were unchanged, map seeds changed, and the configured research cost was applied. Private QA closures existed only in isolated test copies; this release contains no QA interface. No graphical or multiplayer rendering claim is made.

Original Bilka history, MIT license and authorship are retained.

Public namespace newgameplus-updated adopts the original complete storage root through native migrates_from. Original prototype, setting, remote and metatable identifiers remain stable. Existing native ownership is transferred by Factorio. Historical Wind migrations skip a current adopted registry to avoid duplicate companions or reset protection/health.
